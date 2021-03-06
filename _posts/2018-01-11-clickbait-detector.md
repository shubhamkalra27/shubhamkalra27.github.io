---
layout: post
title: Clickbait Detector 
category: Project
tags: fake-news click-bait clickbait sentence-classifier python machine-learning
---


![Clickbait]({{ site.url }}//images/retire-on-200-a-month-headline.jpg)

Detect clickbait with Machine Learning - [http://clickbait.pythonanywhere.com/](http://clickbait.pythonanywhere.com/?utm_source=website) 

#### What is Clickbait?
* Clickbait is a fancy headline written to grab attention of generation that needs instant gratification
* Clickbait is an acknowledgement that anything that needs to be done to move the revenue, ad, CTR needle forward - will be done. 
* Here is an interesting blog on why clickbait is so popular - [link](https://blog.kissmetrics.com/why-clickbait-works/)
* And another that talks about the psychology of clickbait - [link](https://www.wired.com/2015/12/psychology-of-clickbait/)
* My personal opinion is - that this form of writing like many other bublbles is just a trend, will die down  soon. Until then - we will keep trying to find a way to seperate genuine news from baity articles. :) 
* Facebook's effort to curb clickbait - [News Feed FYI:FB](https://newsroom.fb.com/news/2017/05/news-feed-fyi-new-updates-to-reduce-clickbait-headlines/)

#### Science
* The demo is a text classifier that determines weather the headline is a clickbait. 
* The clickbait corpus consists of article headlines from ‘BuzzFeed’, ‘Upworthy’, ‘ViralNova’, ‘Thatscoop’, ‘Scoopwhoop’ and ‘ViralStories’. 
* The non-clickbait article headlines are collected from ‘WikiNews’, ’New York Times’, ‘The Guardian’, and ‘The Hindu’.


![Clickbait]({{ site.url }}//images/clickbait-slow.gif) 


#### Web Service
* The idea to have a simple interface to allow people to be aware and rather surprised - to how many news articles they read in a day are based on appealing to your dopamine - Link to the demo again - [clickbait detector ](http://clickbait.pythonanywhere.com/?utm_source=website)
* This is a hobby project to get the idea out there - I will someday work on a chrome plugin to get it to highlight all the news that one might read as baity or safe

#### Future  
* If the tool reaches a significant audience. I would be happy to wrap it in a AWS lambda function and call it from a chrome extension- which looks for articles on google news, facebook etc. - for a more significant usage. 
* If you think so too - let me know at [@shubhamkalra27](https://twitter.com/shubhamkalra27) 

#### My thanks to 
* Training data has been used from this [study](http://cse.iitkgp.ac.in/~abhijnan/papers/chakraborty_clickbait_asonam16.pdf) - data posted [here](https://github.com/bhargaviparanjape/clickbait/tree/master/dataset)
* Good people at [pythonanywhere.com](https://www.pythonanywhere.com)
* Machine learning tutorials by Jose Marcial Portilla on Udemy. 
 



