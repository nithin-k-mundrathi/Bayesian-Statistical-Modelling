# Bayesian-Statistical-Modelling

## Model-3.1-Event Tree Gas Leak accident
![image](https://user-images.githubusercontent.com/47551095/123717627-1f219580-d875-11eb-8672-2ffed848ed28.png)

We can solve it using two Models, but if we solve it using Model-1 in which we consider all the accidents as Same-Node, we have many Unknown parent states like P(accident= No/Gas=No,alarm_Sound=yes,operator_acts=yes). We don't know the probabilities of such states and there are many states like this for the accident Node.Instead we can model this as a multiple accidents occurring as in the example of train derailing.In this Model we consider all the unknown states to be equal.In the below Model we don't face any problem with Node Probability Tables with many states.

## Model-3.2-Event Tree Gas Leak accident(Modelling different types of Accident)
![image](https://user-images.githubusercontent.com/47551095/123717666-32346580-d875-11eb-9ccf-8a58374d9ae9.png)

In the Model-2 if we model accident as three separate nodes then we dont have the problem of difficulty to find the Node Probability tables. The accident is okay(ok) means that there is no accident occuring if operator operates when alarm sounds.P(accident=True,operates=Yes) = 0,There will be no accident occurring of operator operates.Check and please understand the below Calculations.

![image](https://user-images.githubusercontent.com/47551095/123717693-41b3ae80-d875-11eb-9f6b-8d878bd64120.png)
