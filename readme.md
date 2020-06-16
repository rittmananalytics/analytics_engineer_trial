# Introduction

This trial project simulates real-world working conditions as closely as possible by:
- covering the end-to-end process of sourcing, modeling, transforming and presenting data for analysis
- using tools similar-to or the same as we use on client projects
- being long enough to generate a meaningful deliverable at the end.

## What are trial projects?

Trial projects are short (usually between 3-5 hours), fully-paid projects which are designed to be similar to the actual work that we do at Rittman Analytics. 

What we ask you to deliver in a trial project is used for evaluative purposes only, and not used for our own products, consulting or marketing.  We do however pay £40/hour (£200 for a five hour trial) as compensation for your time, payable within 30 days to your Paypal email account or UK bank account.

Please note that usually have multiple people do trial projects, so please don't be too disappointed if we don't proceed past the trial.

Trial projects are designed to be challenging so please don't get too stressed if you find that it's difficult to finish everything within the specified time frame. Just prioritize accordingly and give it your best effort. 

## Guidance Notes

- Please spend no more than a total of 5 hours on this trial. 
- If you don't finish within those 5 hours, just send what you have delivered. 
- If you have questions along the way, don't hesitate to ask. 
- Please summarise your project deliverables in a Google doc that's publicly viewable. 
- Please provide your paypal email in the Google doc so that you can get paid after the trial. 

# Project Specification

Stack Overflow (https://stackoverflow.com/) is an open community for anyone that codes. It helps members get answers to their toughest coding questions, share knowledge with their coworkers in private, and find their next dream job.

In this exercise we'd like to understand what topics for questions are popular and trending but not being answered, something that could indicate either an opportunity for potential subject matter experts to provide those answers and/or a risk that users posting those questions might become frustrated, churn and look for answers elsewhere.

To do this we’d like you to use the sample set of Stack Overview questions and answers available for public access at https://cloud.google.com/blog/products/gcp/google-bigquery-public-datasets-now-include-stack-overflow-q-a to create a new dataset in Google BigQuery, model the data as a dimensional model (“star schema”) suitable for answering these plus any other related questions that could be answered by this dataset, and then create a series of data visualisations that answer our question and “tell a story” about the data.

We would like you to use the development tools we use on our projects, all of which are either open-source or have free trials that you can obtain from their web sites:

- Google BigQuery (https://cloud.google.com/bigquery/docs/sandbox)
- dbt (https://www.getdbt.com/signup/)
- Google Data Studio (https://datastudio.google.com/u/0/navigation/reporting)
- Github (https://github.com/)

## What we are looking for in-terms of deliverables are:

1. The dbt project created, developed and tested to the standard you think a customer would expect with around five hours effort spent on it, stored in a public Github repository.

2. A Google BigQuery dataset, populated with data from the Stack Overflow sample dataset, shared as a public dataset using the steps here: https://cloud.google.com/bigquery/docs/dataset-access-controls

3. A data model diagram created using Google Docs, Sheets and/or Slides that provides  narrative to explain how you came to this design and demonstrates to that you communicate your understanding of dimensional modeling concepts such as:
- use of business and surrogate keys
- what hierarchies, dimensions, attributes and levels are in the data model
- conformed dimensions
- types of fact table, and your use of bridge and other fact tables

4. A Data Studio dashboard accessible through a public URL that answers the question we have posed and “tells a story” about this data."
