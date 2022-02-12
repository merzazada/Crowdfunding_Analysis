# **Crowdfunding Analysis**
### Overview of project
The purpose of this project is to analyze the dataset and make an outcome based on launch date and goal amount of fundraising so Louise can easily understand when is the best time is to start a fundraising campaigns and how much should be the goal amount for the specific fundraising campaign to be successful.
### Analysis and Challenges

The challenging parts was the outcome based on goal, for each row for the Successful, Failed and Canceled Number I had to write separated formula and I had to be very focused. And there was a tricky part in Kickstarter sheet which was converting the unix timestamps to the actual date.

> <img src="https://user-images.githubusercontent.com/97934695/153729561-8b04d60a-f949-407b-87c7-5d215aaac487.png" width="450">


### Results

**Two conclusions are made about the Theater Outcome by Launch Date:**

-	The month that launched the most successful Kickstarter campaigns was May.
- June, July, and October all had roughly the same number of failed campaigns launched. 

> <img src="https://user-images.githubusercontent.com/97934695/153730177-c8d2198d-7970-4ace-aad9-0e9a920dbd33.png" width="450">

### One conclusion is made about Outcomes based on Goals:
The campaigns below 1000$ goal and between 1000$-5000$ goal is the most successful campaigns, and campaigns between 45000$ and 50000$ and more are the most failed campaigns, if Louise wants successful campaigns outcomes, she must lower the goal amount of the campaigns.


### Summary of the limitations of the dataset

In the Kickstarter worksheet there was few limitations on the deadline and launched_at columns had to convert the unix timestamps to the regular dates. Another limitation for the dataset was the category and subcategory were mixed, I had to separate the parent category and subcategory.
