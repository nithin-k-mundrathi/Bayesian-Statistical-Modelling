# Bayesian-Statistical-Modelling

## Model-2- Too good to be True
### Bayesian Network to identify Bias in the Judgement
![image](https://user-images.githubusercontent.com/47551095/123717503-e681bc00-d874-11eb-8a7c-8d1e8c052cd2.png)
### The Node Probability Tables of Gulit and Bias 
![image](https://user-images.githubusercontent.com/47551095/123718265-9e639900-d876-11eb-8ee5-5d34532435e6.png)

Let’s say an exam is being conducted and evaluated later. Suppose we could assume the Hypothesis as P(Student mark >90) is True (What is the probability that student will get a marks greater than 90) and False which is like the verdict guilt and whether the student understood the concept as hypothesis which is Student Learning(What is the probability that Student understood the concept) is True and False. 

####  When we check the observations, which are Student mark >90, as more and more students get a mark>90, the Probability P(student learning =True) increases if there is no bias. The bias could be where the students collaborated to write the exam. 

But, if we do not ignore the bias and consider the bias that students collaborated, then 	P(student learning =True) increases until few observations and tends to decrease for greater observations. The Bias would increase as a greater number of students get (Student mark >90 = True) but this bias will influence the P(Student Learning = True). We want the students to be independent when they write their exam and get a certain student mark. But If check the observations and the student mark’s and if more and more observations are True, this leads to increase in bias and decrease in P(student Learning = True).Finally, we come to a conclusion that Student’s didn’t learn much and we can confirm it using Bias and observations. So, this the case where there is near unanimity of opinion(result’s) but where a suspicion of systematic bias might be reasonably entertained.

![image](https://user-images.githubusercontent.com/47551095/123718975-5e051a80-d878-11eb-9505-c22b62d41afd.png)
### Calculations of Prior and Posterior of Guilt and Bias
![image](https://user-images.githubusercontent.com/47551095/123718297-afaca580-d876-11eb-9784-6297ff0e625e.png)
![image](https://user-images.githubusercontent.com/47551095/123718320-be935800-d876-11eb-97ff-e55e6ec32bb3.png)





