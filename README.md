# TED Talk View Prediction

This project aims to predict the number of views on TED Talks using various regression models. It involves exploratory data analysis (EDA), feature engineering, model training, hyperparameter tuning, and evaluation using multiple metrics.

---
Dataset info

Number of records: 4,005

Number of attributes: 19

Features information:

The dataset contains features like:

talk_id: Talk identification number provided by TED
title: Title of the talk
speaker_1: First speaker in TED's speaker list
all_speakers: Speakers in the talk
occupations: Occupations of the speakers
about_speakers: Blurb about each speaker
recorded_date: Date the talk was recorded
published_date: Date the talk was published to TED.com
event: Event or medium in which the talk was given
native_lang: Language the talk was given in
available_lang: All available languages (lang_code) for a talk
comments: Count of comments
duration: Duration in seconds
topics: Related tags or topics for the talk
related_talks: Related talks (key='talk_id',value='title')
url: URL of the talk
description: Description of the talk
transcript: Full transcript of the talk
Target Variable :

views: Contains Count of views of every talk
