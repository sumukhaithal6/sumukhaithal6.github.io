---
title: "Customer Feedback Analysis (2019)"
excerpt: "Developed a Customer Feedback Analysis Model to analyze the customer review data of a company, and help identify critical issues based on their severity and impact on customers as well as management."
collection: projects
---
## Abstract
A Customer Feedback Model to analyze the customer review data of a company, and help identify critical issues based on their severity and impact
on customers as well as management. Customer review data for a company is collected and classified into categories (buckets). Aspect-based sentiment/emotion analysis is performed to filter out the negative-sentiment issues; Non-granular reviews (reviews that don’t give specific/detailed issues) are removed using dependency parsing, and issues are ranked based on a severity score that is generated, to finally return the top-ranked issues.
## Project Workflow
1. Data Collection: Web Scraping\
In order to obtain the customer reviews for the company, we scrape websites such as TripAdvisor.
2. Data Preprocessing\
Preprocessing techniques like sentence segmentation, lemmatization, emoticon removal are performed.
3. Keyword, Sentiment and Emotion extraction\
The problem of aspect-based sentiment analysis deals with classifying sentiments (negative, neutral, positive) for a given aspect in a sentence. In other words, instead of classifying the overall sentiment of a text into positive or negative, aspect-based analysis allows us to associate specific sentiments with different aspects of a product or service. \
The pre-processed reviews are passed to IBM’s NLU (Natural Language Understanding), a tool that offers different NLP operations. The review segments are now tagged with a sentiment score, emotions scores and keywords using IBM NLU. 
4. Review Categorization\
The segmented reviews are then classified into categories or buckets, which specify which domain the review segment belongs to. Buckets are manually defined, and may differ from one industry to another.
5. Ranking\
Reviews are to be ranked in the order or severity, such that the most severe issue is ranked first, and the least severe is ranked last.

## [Project Report](../../files/customer_feedback_analysis/Customer_Feedback_Model.pdf)
## [Project Presentation](../../files/customer_feedback_analysis/CritiQali.pdf)
