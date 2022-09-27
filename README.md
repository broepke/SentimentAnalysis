# Up Your Game in Social Media Sentiment Analysis

Sentiment analysis helps understand the tone of text data, positive, negative, or neutral. Capturing sentiment can help organizations better understand the **Voice of Customer (VOC)** and even direct product development to improve functionality [^IJCA]. Frequently, sentiment analysis is lexicon and rule-based, meaning it performs a lookup on words tagged by humans as positive, negative, or neutral. There are more advanced models available such as BERT, which was open-sourced by Google in 2018 [^BERT]. This post will cover the more traditional lexicon-based approach; we'll take a look at the deep learning models later.

You need to be familiar with new terms to interpret the results. They are simple concepts but understanding them upfront will help you follow along better.

* **Polarity**: A value expressing the degree of emotion of a sentence from negative to positive. A value within the range [-1.0, 1.0] (negative sentiment => -1.0, neutral => 0.0, positive sentiment => 1.0)
* **Subjectivity**: A subjective sentence expresses personal feelings, views, or beliefs. The subjectivity is a value within the range [0.0, 1.0] where 0.0 is very objective, and 1.0 is subjective.

Read more here: https://www.dataknowsall.com/sentiment.html
