# ToxicCommentClassification

# Project Overview: 
Discussing things that you care about on a social platform can be difficult. The threat of abuse and harassment online either means people stop expressing themselves and give up on seeking different opinions, or lose sight of what they really care about and go down the rabbit hole of abusing each other. Especially in this day and age where freedom of speech is acknowledged to be a basic human right, everyone should be able to have a healthy online presence and share their opinions. Social media platforms struggle to facilitate such communication however, and most of the time just end up shutting down the comment section if things get out of hand.  
This project aims at helping social media improve online conversation by identifying toxicity in comments. We plan on identifying which type of toxicity the text represents, so that users can pick and choose which ones they are fine with and which ones they want to avoid.  
 
# NLP Keywords: 
Convolutional neural network (CNN), word representations, text encoding, Bag-of-Words, text classification, BERT, FastText

# Dataset:  
We used the Wikipedia comments dataset (https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data) provided by Jigsaw/ Conversational AI, which is a combination of ~ 550,000 comments from Wikipedia articles. The toxicity is categorized into the following categories: Toxic, Severe_Toxic, Obscene, Threat, Insult, and Identity_hate.

# Method:
This repository contains one of the models we tried, BERT with Logistic Regression. You can read more about it, and the other models we tried, in the attached paper.
