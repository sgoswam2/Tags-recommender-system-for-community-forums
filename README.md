# Tags-recommender-system-for-community-forums
Tags recommender system for the community forums. Works for forums like Stack Overflow, Stack Exchange, Discourse, Codechef etc.,.  
## Project Demo

![](./demo-C.gif)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sailikhithk/Tags-recommender-system-for-community-forums)

[Dataset](./webscraping_stack4.xlsx)

I was intrigued going through this amazing article on building a multi-label image classification model last week. The data scientist enthusiast in me started exploring possibilities of transforming this idea into a Natural Language Processing (NLP) problem.

Most of the NLP tutorials are dealing with idea of single-label classification challenges. But community forum posts are not one-dimensional. One post can span several tags. 

#### For example: 

##### Post: How to do webscraping using python and Selenium? 
##### Tags: webscraping, python, selenium.

In the above scenerio, three tags are used for classification. Now THAT is a challenge, I would love to take up and embrace as a data scientist enthusiast. 

#### I extracted a bunch of tags and topics from Stack Exchange, Stack Overflow and got down to work using this concept of multi-label classification. 

And the results, even using a simple model, are truly impressive.

### F1 Score- 0.45 , Accuracy is 0.96 for my scraped dataset. 


