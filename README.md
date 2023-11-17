# Module 20 Report

## Overview of the Analysis

For this analysis, I used a LogisticRegression to observe the data and look at data that was classified as either a high-risk loan or healthy loan. We wanted to predict based off of other variable whether we could determine if a loan was a high-risk loan, or if the loan was healthy.

## Results

* Machine Learning Model 1:
  * The balanced accuracy score for *Model 1* was 0.952.
  * The precision for healthy loans was 1.00.
  * The precision for high-risk loans was 0.85.
  * The recall for healthy loans was 0.99.
  * The recall for high-risk loans was 0.91.

* Machine Learning Model 2:
  * The balanced accuracy score for *Model 2* was 0.993.
  * The precision for healthy loans was 1.00.
  * The precision for high-risk loans was 0.84.
  * The recall for both healthy and high-risk loans was 0.99.

## Summary

Looking at these models, I believe that *Model 2* is a good model to use, because the recall for high-risk loans was high, as well as the f-1 scores for both healthy and high-risk loans. The reason we want a high recall for high-risk loans is to ensure that there are very few loans that are actually high-risk that are being classified as healthy loans, because we do not want to decieve our customers.
