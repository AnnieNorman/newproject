# AI-Driven Moderation of LGBTQ-Related Online Harassment

Final project for the Building AI course

## Summary

This project aims to develop an AI-based system to detect and flag harassment directed at LGBTQ individuals online. By analyzing text data using NLP (Natural Language Processing), the AI model can identify hateful speech and provide users with tools to report or moderate harmful content effectively.


## Background

LGBTQ individuals often face harassment and hate speech on social media and online forums. Studies show that a significant number of them avoid expressing themselves online due to fear of negative responses. This creates a limitation on free speech and an unsafe digital environment. The goal of this project is to improve moderation of such content and reduce the mental stress on affected individuals.

Problems this project addresses:
* Detecting hate speech targeting LGBTQ individuals.
* Improving moderation of social media and online forums.
* Automatically flagging harmful content for review by moderators.


## How is it used?

The system can be integrated into social media platforms, discussion forums, or comment sections. When a user posts a comment, the AI analyzes it in real time. If it contains potentially harmful language, it can:
* Flag the post for moderator review.
* Automatically hide it until it has been reviewed.
* Send a warning to the user explaining why the content may violate platform rules.


## Data sources and AI methods
The project will use a combination of publicly available datasets and data collected from online platforms that allow access to moderation logs. Some potential sources include: 
[Twitter API](https://developer.twitter.com/en/docs) and [Hatebase](https://hatebase.org/)

AI methods to be used will be NLP (Natural Language Processing) for text classification


## Challenges

AI Bias: The model may be biased if trained on skewed datasets.
Misclassification: The risk of neutral or ironic content being wrongly flagged.

## What next?

Initially focused on English and Swedish, but can be adapted to other languages eventually. 
Engaging with social media companies to test the tool in real world scenarios.


## Acknowledgments

* Inspired by research papers on AI and hate speech detection.
