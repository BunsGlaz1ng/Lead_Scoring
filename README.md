# Lead_Scoring
## Problem Statement

X Education, an online education company, offers courses to industry professionals. Daily, many professionals visit their website to explore these courses. The company promotes its offerings through various websites and search engines like Google. Visitors to the website can browse courses, complete a form with their contact information, or watch course videos. When visitors provide their email or phone number in a form, they become classified as leads. Additionally, the company receives leads through referrals. The sales team then follows up with these leads through calls and emails. Despite this effort, only about 30% of leads convert into paying customers.

While X Education generates a significant number of leads, the conversion rate is suboptimal. For instance, if they obtain 100 leads in a day, only around 30 convert. To improve efficiency, the company aims to identify 'Hot Leads'—those most likely to convert. By doing so, the sales team can focus on these promising leads, potentially increasing the conversion rate. The lead conversion process resembles a funnel, with many leads at the top but only a few converting at the bottom. Effective nurturing, such as educating leads about the product and maintaining communication, is essential for higher conversion rates.

X Education has tasked you with developing a model to identify the most promising leads. Your goal is to assign a lead score to each lead, indicating their likelihood of conversion. The CEO has set a target lead conversion rate of approximately 80%.

### Data

You have been provided with a dataset containing around 9,000 leads. This dataset includes various attributes such as Lead Source, Total Time Spent on Website, Total Visits, and Last Activity. The target variable is 'Converted,' where 1 indicates a converted lead and 0 indicates a non-converted lead. Additionally, you should address the 'Select' level present in many categorical variables, as it is equivalent to a null value.

### Goals of the Case Study

1. Build a logistic regression model to assign a lead score between 0 and 100 to each lead. A higher score suggests a higher likelihood of conversion (hot lead), while a lower score indicates a lower likelihood (cold lead).
2. Adjust the model to accommodate additional problems outlined by the company, ensuring flexibility for future requirements. These additional problems are detailed in a separate document.
3. Incorporate these findings and recommendations into a final presentation (PPT), including the logistic regression model results and solutions to the additional problems.

By achieving these goals, X Education hopes to enhance its lead conversion process and improve overall efficiency.
