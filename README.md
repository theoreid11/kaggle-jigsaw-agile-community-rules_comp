
## Competition Description 

Reddit Rule Violation Classification 
# Overview

If you’ve ever had a comment taken down on Reddit and wondered “why?”, you’re not alone.
Each subreddit has its own guidelines, and understanding moderation decisions can feel chaotic.

In this competition, the goal is to build a binary classifier that predicts whether a Reddit comment violates a specific rule. The dataset is derived from millions of moderated comments, with subreddit-specific norms, tones, and community expectations.

This project aims to bring some “comment sense” by training models that can identify potential rule violations and support moderation tasks in real-world communities.

# Competition Details

Host: Kaggle

Task: Predict whether a comment broke a given rule.

Data:

Several years of moderated Reddit comments.

A small labeled dev set for training/few-shot experiments.

Unlabeled content forms the test set.

Evaluation Metric: Column-averaged AUC.

Submission format: CSV with two columns
