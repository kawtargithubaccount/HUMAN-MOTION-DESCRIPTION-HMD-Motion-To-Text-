Challenge Data - Master of Data Science, University of Lille/Centrale Lille/IMT Nord Europe - 2025

Overview
This is Kaggle competition on the Human Motion description, which is part of the 2025 Master of Data Science course.

In this data challenge, you will explore Generative AI at the intersection of natural language processing (NLP) and human motion synthesis by working on text-to-motion and motion-to-text tasks using the HumanML3D dataset.
This dataset contains 3D human motion sequences paired with rich textual descriptions, enabling models to learn bidirectional mappings between language and motion.

Description
In this challenge you are given sequences of 3D human motion data and your task is to develop a generative AI Motion-to-Text Model, allowing to describe the human motion in natural language given a sequence of 3D poses.

The specific format of Human motion data provided in this challenge is explained in more detail in the Data Description section. Along with the data, we provide a skeleton code that helps you to load and visualize the data.

Evaluation Metrics
The evaluation metric for this competition is the METEOR (Metric for Evaluation of Translation with Explicit ORdering):

METEOR Score: evaluates generated text by comparing it to ground truth texts, focusing on precision, recall, and content alignment. It addresses limitations of other metrics like BLEU by considering synonyms, stemming, and paraphrasing. METEOR score considers synonyms and word stems to more accurately capture meaning and language variations.
The METEOR score ranges from 0 to 1, with 1 indicating a perfect match. We are providing the implementation of METEOR score with an example how to use, and also scripts that let you export the predictions into a CSV file that you can then upload to Kaggle for evaluation on the test set.
