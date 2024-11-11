# Wednesday, 30 October 2024
Objectives for this week are to get caught up on what this project is about. Stuff to read on:
- Globular clusters
- Open clusters
- What is a star cluster
- How do we classify star clusters i.e. what features do both of these clusters have?
- How do we create a ML model to classify these?  What features are we looking for?
- Data? Where do we get it? How do we train the AI from this data?

Main goal for this week: Find a good dataset that we can work with.

# Monday, 4 November 2024
We found two data sets for open and globular clusters. We chose two features to plot and classify:
- the B-V index
- the true diameter

We calculate the true diameter by using the angular size, in rad, and distance to the Sun, in any distance unit and apply the following formula:

actual diameter = angular size * distance to sun

The next step is to download all the data, caculate the true diameter for each cluster, then plot these features to see if we can apply a logistic regression or perceptron model. 

# Monday, 11 November 2024
Since the rubric requires collaborative work and it requires us to test multiple models, we should split the work into two groups (2 ppl per). 
- **Logitistics regression model**: One group conducts a logistic regression on the data and present their findings.
- **Linear regression/ any other OLS or data analysis model**: Another group does ML on this different model and present their findings.
- One last person will compile BOTH these models and do a comparison of the pros and cons of each, comparing how they both performed.
