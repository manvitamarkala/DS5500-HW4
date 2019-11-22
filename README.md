# Homework 4 Solutions 

## Problem 1

### Which districts will be affected by your budget cuts the most?

#### Problem 4 - HW3 - Recap
To balance out the difference and give equal importance to all the states interms of the funding, I feel the best way to do the 15% cost cutting for the federal revenue, is by checking which of the states have a surplus amount (Total Revenue - Total Expenditure) that is high enough and in turn also higher than the individual states' federal revenue itself and pull this amount worth the federal revenue from those states until we achieve 8340411300.0. We have captured roughly 5K districts.

The proportion of each district’s total funding that was estimated by dividing the funding amount with the total funding revenue for individual districts. To obtain a neat visualisation and a proper understanding, I aggregated the cuts across state level and then calculated the proportions.

Below are the top 10 states that have been affected the most because of the cuts. The top 2 states that are affected the most are Louisiana and Mississipi.

![P1[]{label="fig:P1"}](P1.png)
###### Figure 1: States with the most budget cuts


## Problem 2 

### Calculate the proportion of enrolled students by race for each district, then visualize the distributions of these for districts that received budget cuts versus districts that did not receive budget cuts

Below are the boxplots for the distribution of enrolled students across different races for the states that received budget cuts vs the states that did not receive budget cuts.

###### Figure 2: Plots showing the distribution across different races

![P2[]{label="fig:P2"}](P2.png)

![P2.2[]{label="fig:P2.2"}](P2.2.png)

![P2.3[]{label="fig:P2.3"}](P2.3.png)

![P2.4[]{label="fig:P2.4"}](P2.4.png)

![P2.5[]{label="fig:P2.5"}](P2.5.png)

![P2.6[]{label="fig:P2.6"}](P2.6.png)

![P2.7[]{label="fig:P2.7"}](P2.7.png)


Observation: The method that I have chosen doesnt seem to hide any bias or result in further disadvantage to groups that are already disadvantaged. Except for Asian race, all the other 6 races have either more number or equal number of students enrolled under the school districts that I have decided to cut funds from when compared to the districts with no cuts and they were not in minority already. However asian race shows a little different results, where it is already in minority and further cutting costs could be a diadvantage for the race.At an overall level, my decision is not having any hidden bias.

## Problem 3

### Calculate the proportion of enrolled students by disability status (students with an IEP under IDEA) for eachdistrict, then visualize the distributions of these proportions for districts that received budget cuts versus districts that did not receive budget cuts

Below is the boxplot for the distribution of enrolled students by disability status for the states that received budget cuts vs the states that did not receive budget cuts.

![P3[]{label="fig:P3"}](P3.png)
###### Figure 1: Boxplot of proportion of enrolled students by disability status

Observation: The method that I have chosen doesnt seem to hide any bias or result in further disadvantage to groups that are already disadvantaged. The enrollment for disabled students is high in the school districts that I have cut costs from and were not in minority in the first place. The results for districts with cuts and no cuts are very close as observed from the graph, with more median on the districts that have been cut funds from. At an overall level, my decision is not having any hidden bias.

## Problem 4

### Choose and critique one of your fellow classmates’ selection of schools for budget cuts in HW 3 Problem 4 and Problem 5. What was the justification of their selection? Discuss any advantages or disadvantages of their approach.

For this question I chose to critique Tian Sang's assignment to assess how he determined the selection of schools for budget cuts.
Link for the assignment : https://github.com/stiangithub/HW3

The author chose to cut 15% from every school district equally and he felt that this was the most fairest way of judgement even if its going to hurt the small school districts because otherwise he thinks if more is cut from big school districts budget, it would still be unfair for the students because some of them might need higher federal costs and cutting their budget may increase the gap between them and other districts.

I feel while this decision is very simple, naive and easy to understand and implement, it is going to have severe effects on school districts that are already in debts and that are funded lesser than what their actual expenses are and it will increase the gap between them and other districts to a very large extent. Maybe considering cutting costs from the schools that are receiving surplus amount of funds when compared to their expenses will help in balancing the gap and it would ideally be a case where each districts expense and funds are equally balanced out. The situation of my classmates decision would lead to poorer districts becoming even poorer and high funded districts still remaining high irrespective of any circumstances.

## Problem 5

### Summarize and comment on what you learned from one the special topics lectures (MapReduce + Hadoop,Visualization, Causal Inference, or the Industry Panel) of your choice.

The special topics lecture that I want to summarize is about Causal Inference. I have never heard a lot about Causal Inference before and its a completely new topic for me. This lecture has particularly excited me to learn more about this area of data science. The speaker has clearly first indicated how a causal inference problem is not a prediction problem but definitely a lot more different from a normal prediction problem (the problem definition itself varies).

The concept of randomized controlled trials and their applied methodology to solve causal inference problems and how they have become standard in solving this kind of problems is interesting.

The case study for kidney stone treatment and how the components X,Y,Z which are the basis of the equation relate to the outcome of prediction, treatment and stone size and how the concept of conditional independence for this case has been applied. Confounding and de-confounding was a totally new area and interesting topic too

Towards the end of the lecture, I got diverted(a bit confused) and found it a little bit difficult to understand the final topics and thats entirely because this area is completely new and statistically heavy and there was a lot to digest about an entire topic in a 3hour lecture, but im really happy to have got introduced to this topic and also get a gist of the concept and Sicheng has done a really good job in explaining the concepts.

