# FB_comments_data

Project Overview

This repository contains a dataset of Facebook comments collected from two Czech media outlets: ČT24 and Seznam Zprávy, specifically focusing on news items related to the 2023 Czech presidential election campaign. The data was gathered one week prior to the first round of elections in January 2023.

The primary purpose of this dataset is to train Large Language Model to code and analyze public discourse, particularly focusing on selected categories. The objective is to assign values to selected variables and to compare the machine coding with the inductively coded assessement of the same dataset.

Dataset Description

The dataset consists of four files:

	1.	Partially inductively coded version of the dataset with comments from ČT24.
	2.	Partially inductively coded version of the dataset with comments from Seznam Zprávy.
	3.	Clean (pre-coding) version of the dataset with comments from ČT24.                                                                       4.	Clean (pre-coding) version of the dataset with comments Seznam Zprávy.

Data Scope:

	•	Data includes all comments on news posts related to the 2023 presidential elections.
	•	Covers the week preceding the first round of elections in January 2023.
	•	Manual inductive coding has been applied to a part of the dataset, serving as an initial step to gain a preliminary understanding of the data and evaluate public discourse on the topic, as well as intended to serve as initial a comparison for the LLM-generated results.

Language Models

The following Czech language models exist for training the LLM on this dataset:

  1.	RobeCzech:
A transformer-based language model trained on Czech texts.
Model link: RobeCzech on Huggingface
	2.	Retromae-small-cs:
Another Czech-focused language model, useful for text analysis and comprehension.
Model link: Retromae-small-cs on Huggingface

Objectives

The key goal of this project is to:

	1.	Set up and train the LLMs using the dataset.
	2.	Compare results from the LLM-generated coding with the inductively coded assessments.

This comparison will help in evaluating the effectiveness of language models in automating content classification for Czech-language social media data.

Please contact me (julia.gottstein@fsv.cuni.cz) for any questions or further information.
