

![alt text](http://recabn.ac.in/wp-content/themes/pradeep/new-images/logo.png)  
## राजकीय इंजीनियरिंग कॉलेज, अम्बेडकर नगरRAJKIYA ENGINEERING COLLEGE, AMBEDKAR NAGAR ( affiliated to Dr. APJAKTU, Lucknow. (College Code 737)
 
# Project : Clustering in Medical Using Quantum inspired by grey wolf  optimizer
### Project Group :No. 9 allotted project no.29  (2022 passout )
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
<img src="https://miro.medium.com/max/216/1*e1C3VXb0avoKJaeMzE7d9A.jpeg" width="1250" height="400"> 

## Main Steps involved in GWO 
### Searching(exploration):
### Encircling:
### Attacking of prey: 
### Attacking position Updating Of grey wolf 

 
<img src="https://miro.medium.com/max/378/1*jbxQg6k5izt3JrTasC_fMw.jpeg" width="1250" height="500"> 

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


# [Medical Diagnisis Analysis](https://github.com/yashvenrakumar/GWO_final_yr_project/tree/main/dataset)
 
 ## [1. Breast cancer diagnosis dataset  ](https://github.com/yashvenrakumar/GWO_final_yr_project/blob/main/dataset/Breast_cancer_data.csv) 
 
 <img src="https://miro.medium.com/max/906/1*a0jj-vw8mtj3UeQjdkvP9g.png"> 
 
| Graph 1     | Graph 3   |
|------------|------------|
| <img src="https://miro.medium.com/max/383/1*J4jDIrWwj8ZI8SdckiHEmA.png" width="600"> | <img src="https://miro.medium.com/max/390/1*QeJgQ1K44qFU1jdO5NvFgQ.png" width="600">  | 
 
| Graph 3     | Graph 4   |
|------------|------------|
| <img src="https://miro.medium.com/max/393/1*7FjN7mdDXDWLDVi-OOK1Wg.png" width="600"> | <img src="https://miro.medium.com/max/396/1*WCanypnZuKs1aUfEwiIeYw.png" width="600">  | 

## [2. diabetes dataset ](https://github.com/yashvenrakumar/GWO_final_yr_project/blob/main/dataset/diabetes.csv)
 <img src="https://miro.medium.com/max/1000/1*UPaSQRjvsYXKR965rqt3Yw.png"> 
 
| Graph 1     | Graph 3   |
|------------|------------|
| <img src="https://miro.medium.com/max/520/1*OUR4NqduPqrtWaIr8YIFkg.png" width="600"> | <img src="https://miro.medium.com/max/565/1*GowVHPXbBxKXYzNx-hwQmA.png" width="600">  | 
 
| Graph 3    |
|------------|
| <img src="https://miro.medium.com/max/697/1*7cyBFiBE_LWSLOarwG4f5A.png" width="1200"> |  



## List of references:
[ data set] (https://github.com/yashvenrakumar/GWO_final_yr_project/blob/main/dataset/Breast_cancer_data.csv)

[	https://www.researchgate.net/publication/260010809_Grey_Wolf_Optimizer](	https://www.researchgate.net/publication/260010809_Grey_Wolf_Optimizer)

[https://en.wikiversity.org/wiki/Algorithm_models/Grey_Wolf_Optimizer](https://en.wikiversity.org/wiki/Algorithm_models/Grey_Wolf_Optimizer)

[https://ieeexplore.ieee.org/document/7867415](https://ieeexplore.ieee.org/document/7867415)

[https://www.nature.com/articles/s41598-019-43546-3](https://www.nature.com/articles/s41598-019-43546-3)

[https://www.kaggle.com/search?q=medical+disease+data+analysis](https://www.kaggle.com/search?q=medical+disease+data+analysis)

[https://www.kaggle.com/search?q=medical+disease+data+analysis](https://www.kaggle.com/search?q=medical+disease+data+analysis ) 
 
 ## Some Useful Code: 
 
 ```
import random
import numpy
import math
#from solution import solution
import time


    

def GWO(Max_iter,SearchAgents_no,n_cluster,dim):
    
   
    ggnn=0
    data=np.array(x)

    levy=np.zeros(SearchAgents_no)
    
    # initialize alpha, beta, and delta_pos
    Alpha_pos=np.zeros((n_cluster,dim))
    Alpha_score=float("inf")
    
    Beta_pos=np.zeros((n_cluster,dim))
    Beta_score=float("inf")
    
    Delta_pos=np.zeros((n_cluster,dim))
    Delta_score=float("inf")
    
    #Initialize the positions of search agents
    Positions=init_pop(SearchAgents_no,n_cluster,dim)
    
    Convergence_curve=numpy.zeros(Max_iter)
    sol=solution()

    # Loop counter
    #print("GWO is optimizing  \""+objf.__name__+"\"")    
    
    timerStart=time.time() 
    sol.startTime=time.strftime("%Y-%m-%d-%H-%M-%S")
    
    
    #sol=solution()

    # Loop counter
    #print("GWO is optimizing  \""+objf.__name__+"\"")    
    
    #timerStart=time.time() 
    #sol.startTime=time.strftime("%Y-%m-%d-%H-%M-%S")
    # Main loop
    for l in range(0,Max_iter):
        for i in range(0,SearchAgents_no):
            
            # Return back the search agents that go beyond the boundaries of the search space
            #Positions[i,:]=numpy.clip(Positions[i,:], lb, ub)

            # Calculate objective function for each search agent
            
            current_centers=pd.DataFrame(Positions[i])
            current_labels = assign_cluster_label(data,Positions[i])
            current_centers.columns=[ 'a','b','c','d','e', ]
            

            fitness1=fitness(data,Positions,current_labels,i)
            
            # Update Alpha, Beta, and Delta
            if fitness1<Alpha_score :
                Alpha_score=fitness1; # Update alpha
                Alpha_pos=Positions[i,:].copy()
            
            
            if (fitness1>Alpha_score and fitness1<Beta_score ):
                Beta_score=fitness1  # Update beta
                Beta_pos=Positions[i,:].copy()
            
            
            if (fitness1>Alpha_score and fitness1>Beta_score and fitness1<Delta_score): 
                Delta_score=fitness1 # Update delta
                Delta_pos=Positions[i,:].copy()
            
        
        #z=numpy.random.uniform()
        #z=4*z*(1-z)
        
        
        a=2-l*((2)/Max_iter); # a decreases linearly fron 2 to 0
        
        beta=0.5
        sigma=(math.gamma(1+beta)*math.sin(math.pi*beta/2)/(math.gamma((1+beta)/2)*beta*2**((beta-1)/2)))**(1/beta);
        
        for i in range(0,SearchAgents_no):
            for j in range (0,n_cluster):     
                           
                r1=random.random() # r1 is a random number in [0,1]
                r2=random.random() # r2 is a random number in [0,1]
                
                A1=2*a*r1-a; # Equation (3.3)
                C1=2*r2; # Equation (3.4)
                
                D_alpha=abs(C1*Alpha_pos[j]-Positions[i,j]); # Equation (3.5)-part 1
                X1=Alpha_pos[j]-A1*D_alpha; # Equation (3.6)-part 1
                           
                r1=random.random()
                r2=random.random()
                
                A2=2*a*r1-a; # Equation (3.3)
                C2=2*r2; # Equation (3.4)
                D_beta=abs(C2*Beta_pos[j]-Positions[i,j]); # Equation (3.5)-part 2
                X2=Beta_pos[j]-A2*D_beta; # Equation (3.6)-part 2
                
                r1=random.random()
                r2=random.random() 
                
                A3=2*a*r1-a; # Equation (3.3)
                C3=2*r2; # Equation (3.4)
                
                D_delta=abs(C3*Delta_pos[j]-Positions[i,j]); # Equation (3.5)-part 3
                X3=Delta_pos[j]-A3*D_delta; # Equation (3.5)-part 3             
                
                Positions[i,j]=(X1+X2+X3)/3  # Equation (3.7)
            
            s=Positions[i,:]
            
            u=numpy.random.uniform(size=dim)*sigma
            v=numpy.random.uniform(size=dim)
            step=u*abs(v)**(1/beta)
            stepsize=0.1*step*(s-Alpha_pos) #s-alpha_pos
            s=s+stepsize*numpy.random.uniform(size=dim)
            Positions[i]=s
        Convergence_curve[l]=Alpha_score

    timerEnd=time.time()  
    sol.endTime=time.strftime("%Y-%m-%d-%H-%M-%S")
    sol.executionTime=timerEnd-timerStart
    sol.convergence=Convergence_curve
    sol.optimizer="GWO"
    
    sol.no_of_iterations=l  
    print(Alpha_pos)
    return Alpha_pos,current_labels,sol
```
