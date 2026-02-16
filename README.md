CREATED RETENSION DASHBOARD LINK IS GIVEN BELOW JUST CLICK AND SHOW -------

https://app.powerbi.com/links/dBZF-EfZez?ctid=e219f8f2-44b7-46c3-95e1-06b3146aeb5e&pbi_source=linkShare


RETENTION METRIC DEFINITIONS – CAMPUSKUL-How many users come back again after signing up?
COHORT - A group of users who signed up in the same week.

• Cohort Week:                                                                                                                                           
  The week when a user signed up (Week 0).

• Week Number:
  Number of weeks after signup.
  Week 0 = Signup week
  Week 1 = First week after signup
  Week 2 = Second week after signup

Active User:
  A user who performed at least one activity 
  (post, comment, job post, event registration, etc.)

• Retention %:
  (Active Users in Week N ÷ Total Users in Cohort) × 100

TASK - COHORT RETENSION

First, we grouped users based on the week they signed up. This means all users who registered in the same week were placed into one group, called a cohort. Instead of analyzing all users together, we studied them week by week based on their signup date.

Next, we checked whether those users came back to use the product again in the following weeks. For each user, we looked at their activity dates and compared them with their signup week to see if they returned in Week 1, Week 2, and so on.

Then, we calculated how many users from each cohort were active in each later week. For example, if 100 users signed up in one week and 40 of them came back in the next week, the Week 1 retention for that cohort would be 40%.

After that, we converted these numbers into percentages to clearly understand retention rates. This helps us see how user engagement changes over time for each signup group.

Finally, we created a retention table that shows signup weeks in rows and returning weeks (W0, W1, W2, etc.) in columns. We exported this table as a CSV file and documented the full process in a notebook.

This analysis helps measure how well users continue to engage with the product over time, which is very important for understanding product growth and user satisfaction.
This is called Retention.






