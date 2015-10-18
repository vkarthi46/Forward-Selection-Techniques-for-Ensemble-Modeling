# Forward-Selection-Techniques-for-Ensemble-Modeling

Ensemble methods have the ability to provide much needed robustness and accuracy to both supervised and unsupervised problems. Machine learning is going to evolve more and more and computations power becomes cheap and the volume of data continues to increase. In such a scenario, there is a limit to the improvement you can achieve by using a single framework and attempting to improve its predictive power (using modification in variables}

Ensemble Modeling follows the philosophy of ‘Unity in Strength’ i.e. combination of diversified base models strengthens weak models. The success of ensemble techniques spreads across multiple disciplines like recommendation systems, anomaly detection, stream mining, and web applications where the need for combination of competing models is ubiquitous.

# Principles involved in the Process

Forward Selection of learners : 

Imagine a scenario where we have 1000 learner outputs. We start with an empty bag and then in every iteration we add a new learner which benefits the bag on performance metric.

Selection with Replacement :

To select a new addition for the bag, we put our hand in the stack of 1000 leaner and pull out the best of the lot. Even if a learner is found to be a good fit, we’ll still use this learner in the next iteration stack

Bagging of Ensemble Models : 

Ensemble learners are prone to over-fitting. To avoid this, we take a sample to try ensembling. Once we are done, we again use another sample. Finally, we bag all these models together using simple average of predictions or maximum votes.
