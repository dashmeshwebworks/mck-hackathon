# mck-hackathon

McKinsey Hackathon: Digital Banking

## About the hackathon

[Analytics Vidhya](https://www.analyticsvidhya.com/)
hosted a competition called
[_McKinsey Analytics Online Hackathon: Sales Excellence_](https://datahack.analyticsvidhya.com/contest/mckinsey-analytics-online-hackathon-ii/). The dataset was released and each participant had 24 hours to submit their best scoring model. Evaluation critera was ROC AUC.

* My AUC score 0.7859
* Winner score 0.8581

This was my first hackathon.
I ended up 155 out of thousands participants, which I consider to be a decent outcome, given my non-existent experience, weak preparation and the little time I spent on this task.
See the  [leaderboard](https://datahack.analyticsvidhya.com/contest/mckinsey-analytics-online-hackathon-ii/pvt_lb)

## Problem statement

A digital arm of a bank faces challenges with lead conversions. The primary objective of this division is to increase customer acquisition through digital channels. The division was set up a few years back and the primary focus of the division over these years has been to increase the number of leads getting into the conversion funnel.

They source leads through various channels like search, display, email campaigns and via affiliate partners. As expected, they see differential conversion depending on the sources and the quality of these leads.

They now want to identify the leads' segments having a higher conversion ratio (lead to buying a product) so that they can specifically target these potential customers through additional channels and re-marketing. They have *provided a partial data set for salaried customers from the last 3 months*. They also capture basic details about customers. We need to *identify the segment of customers with a high probability of conversion in the next 30 days.*
predict proba, gärna based on channel => actionable

## Method

GradientBoostingClassifier

## Important files

`do5.ipynb`

## Status 

This repo can be considered "done" since the hackathon is over. On the other hand, improvements can be made - see the TODO file.
