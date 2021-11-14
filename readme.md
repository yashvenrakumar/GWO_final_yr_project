![alt text](http://recabn.ac.in/wp-content/themes/pradeep/new-images/logo.png)  
## राजकीय इंजीनियरिंग कॉलेज, अम्बेडकर नगरRAJKIYA ENGINEERING COLLEGE, AMBEDKAR NAGAR
 
# Project : Clustering in Medical Using Quantum inspired by grey wolf  optimizer
<img src="https://miro.medium.com/max/700/1*-G5OG46a9bXzldEeE5nDUQ.png" width="1250" height="400"> 


## Content :
- ### Introduction
- ### What is medical diagnosis clustering
- ### What Is Grey wolf Optimizer
- ### Why it is used
- ###  Algorithm
- ### Comparison 

 




## Introduction: 
### In order to make the best medical decisions, medical diagnosis plays a very important role for medical institutions. As everyone knows, false medical diagnoses will lead to incorrect medical decisions, which are likely to cause delays in medical treatment or even loss of patients’ life. Recently, a number of computer aided models have been proposed for diagnosing different kinds of diseases, such as diagnostic models for Parkinson’s disease , breast cancer , heart disease , and Alzheimer’s disease .
 

## What is medical Diagnosis clustering
### As a matter of fact, medical diagnosis could be treated as a problem of classification. In the medical diagnosis field, datasets usually contain a large number of features. For example, colorectal microarray dataset  contains two thousand features with highest minimal intensity across sixty-two samples. However, there are irrelevant/redundant features in dataset which may reduce the classification accuracy.
 
##  Why it is used
### GWO mimics the social hierarchy and hunting behavior of grey wolves in nature. Due to its excellent search capacity, it has been successfully applied to many real-world problems since its introduction, like optimal reactive power dispatch problem , parameter estimation in surface waves , static VAR compensator controller design , blackout risk prevention in a smart grid , capacitated vehicle routing problem , non-convex economic load dispatch problem , and so on.
 
 
## What is Grey wolf optimizer
### The GWO is a new meta-heuristic algorithm proposed by S Mirjalili  , which mimics the social hierarchy and hunting mechanism of grey wolves in nature and is based on three main steps: encircling prey, hunting, and attacking prey. In order to mathematically model the leadership hierarchy of wolves, assume the best solution as alpha, and the second and third best solutions are named as beta and delta, respectively. The rest of the candidate solutions are assumed to be omega. The strict social dominant hierarchy of grey wolves as shown in figure. Social Hierarchy of Grey wolves
 
 ## Fitness values of hierarchy
###  consider the fittest solution as the alpha (α). 
### the second and third best solutions are named beta (β) and delta (δ) respectively 
### rest of the candidate solutions are assumed to be omega (ω). 
### In the GWO algorithm the hunting (optimization) is guided by α, β, and δ. 
### The ω wolves follow these three wolves

## Main Steps involved in GWO 
### Searching(exploration):
### Encircling:
### Attacking of prey: 
### Attacking position Updating Of grey wolf 


 





| col 1      | col 2      |
|------------|------------|
| <img src="http://recabn.ac.in/wp-content/themes/pradeep/new-images/logo.png" width="250"> |## राजकीय इंजीनियरिंग कॉलेज, अम्बेडकर नगरRAJKIYA ENGINEERING COLLEGE, AMBEDKAR NAGAR | 
 
In his beard lived three <span style="color:red">cardinals</span>
Some basic Git commands are:

```
git status
git add
git commit
```

### Algorithm  of GWO

```
Initialize the grey wolf population Xi (I = 1, 2, .... n) 
Initialize a, A, and C . 
 Calculate the fitness of each search agent 
 X α=the best search agent 
 X β=the second best search agent 
 X λ =the third best search agent 
 Effects of A on the exploration and 
 while (t< Max number of iterations) exploitation of GWO 
 for each search agent 
Update the position of the current search agent by above equations 
 end for 
Update a, A, and C 
Calculate the fitness of all search agents 
Update X α, X β, and X λ 
 t=t+1 
 end while 
 return X α
 
```


# Medical Diagnisis Analysis
 
 ## 1. Breast cancer diagnosis dataset    
 <img src="https://miro.medium.com/max/906/1*a0jj-vw8mtj3UeQjdkvP9g.png"> 
 
| Graph 1     | Graph 3   |
|------------|------------|
| <img src="https://miro.medium.com/max/383/1*J4jDIrWwj8ZI8SdckiHEmA.png" width="600"> | <img src="https://miro.medium.com/max/390/1*QeJgQ1K44qFU1jdO5NvFgQ.png" width="600">  | 
 
| Graph 3     | Graph 4   |
|------------|------------|
| <img src="https://miro.medium.com/max/393/1*7FjN7mdDXDWLDVi-OOK1Wg.png" width="600"> | <img src="https://miro.medium.com/max/396/1*WCanypnZuKs1aUfEwiIeYw.png" width="600">  | 

## 2. diabetes dataset 
 <img src="https://miro.medium.com/max/1000/1*UPaSQRjvsYXKR965rqt3Yw.png"> 
 
| Graph 1     | Graph 3   |
|------------|------------|
| <img src="https://miro.medium.com/max/520/1*OUR4NqduPqrtWaIr8YIFkg.png" width="600"> | <img src="https://miro.medium.com/max/565/1*GowVHPXbBxKXYzNx-hwQmA.png" width="600">  | 
 
| Graph 3    |
|------------|
| <img src="https://miro.medium.com/max/697/1*7cyBFiBE_LWSLOarwG4f5A.png" width="1200"> |  


 
