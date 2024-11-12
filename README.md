# Operations-Analytics-Investigating-Metric-Spike

This case study is focused on carrying out in-depth analysis of operations of a company. Metric spike investigation is also an important part of operation analytics.

Case Study 1 (Job Data) Below is the structure of the table with the definition: 
Table-1: job_data job_id: unique identifier of jobs actor_id: unique identifier of actor event: decision/skip/transfer language: language of the content time_spent: time spent to review the job in seconds org: organization of the actor ds: date in the yyyy/mm/dd format. It is stored in the form of text and we use presto to run. no need for date function

1.Number of jobs reviewed: Amount of jobs reviewed over time.
2.Throughput: It is the no. of events happening per second.
3.Percentage share of each language: Share of each language for different contents. 
4.Duplicate rows: Rows that have the same value present in them. 

Case Study 2 (Investigating metric spike)

Table-1: users This table includes one row per user, with descriptive information about that user’s account. 
Table-2: events This table includes one row per event, where an event is an action that a user has taken. These events include login events, messaging events, search events, events logged as users progress through a signup funnel, events around received emails. 
Table-3: email_events This table contains events specific to the sending of emails. It is similar in structure to the events table above.

1.User Engagement: To measure the activeness of a user. Measuring if the user finds quality in a product/service.
2.User Growth: Amount of users growing over time for a product. 
3.Weekly Retention: Users getting retained weekly after signing-up for a product. 
4.Weekly Engagement: To measure the activeness of a user. Measuring if the user finds quality in a product/service weekly.
5.Email Engagement: Users engaging with the email service. 
