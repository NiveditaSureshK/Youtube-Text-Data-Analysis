# Youtube-Text-Data-Analysis

The revolution of social media sites has also attracted the users towards video sharing sites, such as YouTube. The online users express their opinions or sentiments on the videos that they watch on such sites.

According to the latest YouTube statistics, the video-sharing platform has 2.6 billion users worldwide as of 2022 (Statista, 2022). It’s ranked as the second-most popular social network, and the only platform that has more active users than YouTube is Facebook. 

The objective is to automatically recognize and categorize opinions expressed in the comments to determine overall sentiment of the user.

Sentiment analysis helps data analysts within large enterprises gauge public opinion, conduct nuanced market research, monitor brand and product reputation, and understand customer experiences. 

## Business Problem Statements

Observations on the following are made:
1. Sentiment analysis on YouTube comments.
2. Exploratory data analysis on positive sentences
3. Exploratory data analysis on negative sentences.

## Dataset

- The dataset includes data gathered from the (up to) 200 listed videos on YouTube that are contained within the trending category each day in the US.
- The headers in the comments file are:
   - **video_id**
   - **comment_text**
   - **likes**
   - **replies**
 
## Data Analysis Using Python

1. Polarity determination using TextBlob
2. WordCloud representation of sentiments
3. Removal of STOPWORDS
4. Emoji’s Analysis

### Polarity determination using TextBlob
- 
<p align="center"></p>
<p align="center"></p>

### WordCloud representation of sentiments
- Perform WordCloud of positive and negative sentences.
- To generate a word cloud, convert all comments into string format using the join function
- Polarity one indicates a positive sentence, polarity -1 indicates a negative sentence.

<p align="center"><img width="692" alt="image" src="https://user-images.githubusercontent.com/71536311/193200845-7235ef53-2351-415d-8588-80e60768c976.png"></p>

### Removal of STOPWORDS
- As you can see from the below image, the highlighted words don't add any value to the sentiments.

<p align="center"><img width="685" alt="image" src="https://user-images.githubusercontent.com/71536311/193201401-2fdc9b93-916f-4f01-8717-99bca1327a6c.png"></p>

- Remove stop words WordCloud's Stopword feature, which already has all the stop words present, to get the proper WordCloud, otherwise inaccurate data will be provided.

### Emoji’s Analysis

<p align="center"></p>
<p align="center"></p>

## Tools Used
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)   ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)   ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)   ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23#ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=white)   ![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)

- Jupyter Notebook is used as IDE.
- Among the Python libraries, Pandas is used for handling and preprocessing data.
- Plotly, Seaborn, and Matplotlib are used for visualizing plots.

For more details, please go through the Jupyter Notebook attached above.

## Conclusion
- 
