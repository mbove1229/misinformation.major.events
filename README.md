# misinformation.major.events

False Information Spikes During Major Events
A Political Misinformation Analysis Project

This repository contains the R code and write-up for my final project analyzing whether major political or public-health events increase the proportion of false claims on social-media fact-checking sites.

Overview
I used a dataset of 9,960 Politifact fact-checked statements and identified four major events (2016 election, 2018 midterms, 2019 impeachment inquiry, and 2020 COVID declaration). I compared event-week vs. non-event-week misinformation levels.

Methods
- Cleaned and prepared data in R
- Created binary outcome (is_false)
- Defined event windows

Ran:
- Chi-square test
- Logistic regression
- Linear regression trend analysis

Key Findings
- Event weeks show a significantly higher proportion of false statements
- Logistic regression shows increased odds of false claims during events
- There is a long-term upward trend in misinformation over time
