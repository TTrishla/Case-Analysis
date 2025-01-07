# Case-Analysis

Scenario
You are working as a data scientist for a national grocery chain named Regork. You have been charged with identifying a potential area of growth where the company could invest future resources to increase revenue and profits. Your manager has asked that you prepare a report that outlines your findings along with a 3 minute presentation for the CEO. Good luck!

Business Question
Organizations are always looking for growth opportunities. Unfortunately this can be quite vague and you, as the data scientist, are required to interpret, identify, and defend your proposition.  So where do we find growth opportunities? The following are some examples:

Maybe a certain demographic group is generating large amounts of revenue for a particular product and we could invest to capture market share in this area?
Is there a certain demographic group that we notice is not buying particular products? This could be for valid reasons or it could be because there is insufficient marketing to this group. This could be an opportunity to increase awareness of these products for this demographic group to gain more interest.
Do we notice a trend (positive or negative) where purchasing behavior is changing over time. Maybe sales volume is increasing for a particular product or customer segment and we could invest in marketing to hopefully compound this trend?
Do certain products tend to be purchased with other products on a regular basis? For example, when customers purchase frozen pizzas do they often purchase beer at the same time? Identifying these relationships can help marketing develop paired product marketing plans.
Do certain products have spikes on particular dates (i.e. holidays)? Identifying these relationships can help marketing created relevant marketing plans based on the calendar.
Are certain marketing campaigns more successful than others in driving sales volume or revenue? 
Are certain coupons or promotions more impactful than others?
The list is endless and its your job to propose the business question of interest and use the data and your data wrangling skills to answer the question. Keep in mind that your initial business question may change as you dive deeper into the data and find insights. Regardless of the business question you start researching, your final report should have one clear business question that is addressed.

Analytic Approach
Coming up with a business question is one thing but interpreting the business question into the analytic approach is another.  You will be charged with defining the logical approach to answer the business question of your choice. For example say the business question is "Do customers that purchase frozen pizzas have a greater tendency to also purchase beer at the same time?"  To answer this question your analytic approach could include:

Joining transactions with product information data.
Performing regular expressions to identify relevant pizza and beer products.
Creating a variable that indicates when both items are purchased versus transactions where neither (or one but not the other) are purchased.
Computing relevant summary statistics that will indicate if the probability of purchasing these together are greater than the probability of purchasing one but not the other.
Along the way you should be asking yourself:  Do subgroups matter in the data? Do there appear to be data quality concerns? Are trends over time important? Could other variables be impacting my findings?

Regardless of the approach, your report should be a logical, cohesive story that addresses the business problem --- not simply a bunch of graphs created for the sake of making them. 

Also, simplicity is often the key to great analyses. Simple descriptive statistics can (and usually) yield more of an immediate impact than a complicated model. Brooke WatsonLinks to an external site. gave a compelling and enlightening presentation at the 2019 RStudio Conference on how the ACLU used various R packages to count and reunite families.

Data
You will be using the Complete Journey dataLinks to an external site. to answer your business problem. You are required to use the full data sets rather than the sampled data sets (i.e. get_transactions() rather than transactions_sample, get_promotions() rather than promotions_sample). At a minimum you should be using at least two different data sets to address your problem (in other words I expect you to have to join data sets in various ways). 
