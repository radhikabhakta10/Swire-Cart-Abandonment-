Business Problem:

This project involved using Google Analytics, sales, financial, and order history data for MyCoke360: a platform for business customers to shop coca-cola products, in order to identify behaviors that influence cart abandonment and recovery. 

S.T.A.R Analytics Solution to the Business Problem:

The solution to identify these patterns, a logistic regression model was used to see whether that was a sufficient model to predict cart abandonment and recovery. This model was subpar as it gave an accuracy of 59% for abandonment and 77% for recovered. After this, a text-analytics approach was used which allowed the group to treat event sequences like documents, build a TF-IDF feature matrix, and identify behavioral patterns and clusters associated with abandonment. The findings show that the company should invest in UI especially during cart refinement and payment steps. The frequent events of update_cart, remove_from_cart, and update_payment signaled customer confusion and difficulty. This is especially true for mobile and tablet users as they had a higher rate of abandonment than desktop users. 

My Contribution:

My contribution included doing EDA with helping define abandoned carts through flagging and adjusting timestamps on the Google Analytics dataset. This was accompanied by doing EDA revolving around user experience and product/event breakdowns. I was also in charge of doing the initial logistic regression model. 

The Business Value of the Solution:

This analysis provides clear, data-driven direction for reducing cart abandonment which will increase revenue from sales. By improving the UI/UX, Swire Coca-Cola can streamline the customer journey, see a potential reduction in abandonment rates and an increase in recovery rates, and enhance satisfaction across users. 

Difficulties Encountered:

It was difficult to understand how to initially combine all these datasets to obtain the information we needed. We spent a lot of time trying to understand how all the datasets are related and what dataset should be used to answer the questions Swire Coca-Cola was interested in. Another big hurdle was identifying how to define abandoned and recovered carts. This definition was the foundation of the analysis, so it was important to ensure that it aligned with our steps we took to identify behavioral patterns that led to abandonment and recovery. 

What I Learned From this Project:

I learned that data is very messy in the real world, and there is never going to be one right answer. It was interesting to see how our recommendations varied from other groups, and I found myself wanting to test out the methods of other groups when I was watching presentations. This project taught me that a lot of trial and error is usually what data scientists have to do in order to obtain any significant results. It also taught me to think outside the box of what is normally done and that creativity is rewarded. 
