# Natural Language Processing of State of the Union Speeches

The State of the Union (SotU) is an annual address delivered by the President of the United States to Congress. It provides an opportunity for the president to speak directly to the nation, outlining their administration’s agenda and priorities. The speech often highlights the nation’s overall condition, particularly its economic health. For this analysis, we’ll examine transcribed SotU speeches from 1945 to 2023, covering 14 presidents—7 Democrats and 7 Republicans.

Here were my guiding questions:

1. Do different presidents exhibit variations in tone or sentiment?
2. What factors might explain changes in sentiment within individual SotU speeches? Are there indicators that could help predict sentiment?
3. How has the language of these speeches evolved over time, and are there discernible patterns?
4. Are there significant differences between the speeches of presidents from the two major political parties?

![text](https://github.com/zberman1234/NLP-State-of-the-Union/blob/main/sentiment.png "SotU Sentiment Analysis")

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- nltk
- spacy
    - "python -m spacy download en_core_web_sm"
- textblob
- sklearn
- scipy
- wordcloud
