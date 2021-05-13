# AB-testing
In this project we are analysing the results of A/B testing for an ecommerce website.   
The ecommerce company is planning to make some changes to their landing page with the assumption that this new page will increase the rate of conversions from its current rate.
A landing page conversion rate actually helps companies understand how well their landing page is performing. It refers to the percentage of how many people actually take the desired action, which usually is either make a purchase, watch a demo, or start a free trial of a service or product.For the A/B test, a sample of their users were randomly divided into two groups. The first group of users would continue to see the old landing page and therefore, they are the 'Control' group. The second group of users will receive the new landing page and therefore fall in the 'Treatment' group. Our goal is to analyse whether, the average conversion rate for the Treatment group is significantly larger than the average conversion rate of the control group. If so, we can then say that our new landing page would drive higher number of conversions.

For this statistical analysis, there are 3 steps that we need to follow and they are as follows:
1. Formulating a hypothesis: In this case, our Null Hypothesis(or status quo, if you will) is that the average conversion rate for the Control Group is higher than or equal to that of the Treatment Group. The Alternative Hypothesis is that the average conversion rate of the Treatment group is higher than that of the Control group. For us to verify if the ecommerce company's assumption is correct, we should be able to reject the Null Hypothesis.   
2. Once we form our hypotheses, we collect data samples or create a bootstrap sample using the given sample data set and plot the probability distribution under the Null Hypothesis. 
3. We then perform a one-sided t-test to understand if we have enough evidence to reject the Null Hypothesis. 

We also performed a Logistic Regression based analysis to see whether there was enough evidence against our  Null Hypothesis that average conversion rate for Control group is equal to that of the Treatment Group.  

With both these approaches, we come to the conclusion that we do not have enough evidence to reject the Null Hypothesis.



