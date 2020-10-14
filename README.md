### Web-based-Dashboard-for-COVID-19-Twitter-Sentiment-Analysis

### Category: 
Artificial Intelligence

### Skills Required:
Tone Analyzer,Node- RED

### Project Description:

### Project Idea:

As governments and organizations continue to work towards COVID-19 and stem the growing humanitarian toll it is exacting, the economic effects are also beginning to be felt. We can track sentiment to gauge how people’s expectations, incomes, spending, and behaviors change throughout the crisis across the country over time and also predict their
state if the lockdown is extended.

### Solution Requirement:

The project mainly focuses on people’s sentiment towards the pandemic, understands the sentiments of people on government’s decisions to extend the lockdown and possibility to predict riots against the government. 

In this Project, our server application subscribes to a Twitter feed as configured by the user. Each tweet received will be analyzed for emotional tone and sentiment, all data is stored in a Cloudant database, with the opportunity to store historical data as well. The resulting analysis is presented in a Node-Red based Web UI as a series of graphs and charts

1. Tweets are pushed out by Twitter based on Hashtag.

2. The Watson Tone Analyzer Service /Sentiment node performs an analysis of
sentiment and emotional tone.

3. Tweets and metadata are stored in Cloudant

4. The Web UI displays charts and graphs.

### Proposed Technical Architecture:

<div align="center">
    <img src="https://github.com/SmartPracticeschool/SPS-5824-Web-based-Dashboard-for-COVID-19-Twitter-Sentiment-Analysis/blob/main/Screenshot%20(25).png" height="500" alt="IBM Sentiment Analysis">    

</div>



