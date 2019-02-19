---
author: Deyan Spasov
date: "2019-01-12T12:52:36+06:00"
description: MRS Award Winning Project
image: images/blog/znps.jpg
title: Reducing Churn Rate Using Super-Detractor Identification Model
---

This project won the 2018 MRS award for innovation in Data Analytics.

# The Problem:

The client uses customer satisfaction surveys to identify and contact unhappy customers (super-detractors). However, only a fraction of the customers filled out the NPS surveys, and a ML solution for identifying super detractors was needed.

# Our Approach:
 
By analyzing usage and transaction data we managed to rank customers in terms of their likelihood of being super detractors. A variety of feature selection, imputation, and modeling techniques were tested. An ensemble of boosting models was used thanks to which a 5x lift was achieved in the rate of correctly identified detractors.

# Deliverables:

We implemented the model in the customer’s data architecture, using a parallel implementation for regular re-training and daily scoring. Top 10% of model predictions are sent daily to the client’s call centеr where unhappy customers are contacted. In the first three months, accuracy of 80% was reported by the client’s call center.
