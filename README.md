# Cloud Data Warehouse User Study
A user study on the pricing models and related features of the cloud data warehouse.

## Introduction
This user study is to understand the preferences of cloud data warehouse customers in the following aspects.
> 1. Pricing models: whether customers prefer provisioned pricing, on-demand pricing, or on-demand pricing with flexible SLAs.
> 2. Absolute performance-price: whether customers prefer to know the absolute performance of queries under a give price.
> 3. Cost visibility: whether customers prefer to view the cost and performance of historical queries.
> 4. Text-to-SQL: whether customers prefer to have the cloud data warehouse translating natural-language questions to SQL,

The origin questionnaire is in Chinese. An English translation is [HERE](questionnaire.md).
We create the questionnaire in Tencent Survey and send to the database communities on WeChat.
Each WeChat account can only answer the questionnaire once, and all WeChat accounts have been verified with real names.
The questionnaire was view by 887 and answered by 416 participants.

## Validation Rules
We filter out invalid submissions using the validation rules.
A questionnaire submission is considered invalid if it meets any of the following rules:
> 1. The participant took less than 55 seconds to answer the questionnaire. Because we found by a lab study that it is hard for most people to fully read the questionnaire within 55 seconds.
> 2. The participant checked any options other than `Snowflake` and `Redshift` in `Q3`.
> 3. The participant selected `I know nothing about cloud data warehouses` in `Q2`.

With these validation rules, 109 out of the 416 submissions are considered valid.
The valid and invalid submissions are in the [RESULT](result) folder.
