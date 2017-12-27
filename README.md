# Project: bike-share-rider - Deep Learning [Mohamed Ismail]

# Description
  
  - Simply , It acts as a Predictor for  bike ride sharing depend on data coming from [UCI Machine Learning Database](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset).
  - in this project, you'll get to build a neural network from scratch to carry out a prediction problem on a real dataset! By building a neural network from the ground up .
  - I used Algorith known as Stochastic Gradient Descent (SGD) to train the network.the idea is that for each training pass, you grab a random sample of the data instead of using the whole data set. You use many more training passes than with normal gradient descent, but each pass is much faster. This ends up training the network more efficiently. You'll learn more about SGD later.
  
  

  #### How  components do interact with each other:

```
APP.js
│     
│
└───BookShelf ( stateless function)
│   │  
│   └─── MyReads.js ( stateless function)
│          │        
│          └───  Book.js
│     
└───  Search.js   
        │
        └───  Book.js
    
 ``` 

# Required Libraries and Dependencies
   - install all required libraries umpy, matplotlib, pandas, and jupyter notebook using ` conda install numpy matplotlib pandas jupyter notebook `
   - Download Anaconda or miniconda .

# How to Run Project 
   1.  Download all Project files `https://github.com/ismail484/bike-share-rider.git` 
   2.  Create a new Conda environment:
   ```
   conda create --name dlnd python=3
   Enter your new environment:
   Mac/Linux: >> source activate dlnd
   Windows: >> activate dlnd
   
   ```
   3.   open up the notebook using:
     `jupyter notebook dlnd-your-first-neural-network.ipynb `

# Resources
 
   1. [Stochastic Gradient Descent](http://ufldl.stanford.edu/tutorial/supervised/OptimizationStochasticGradientDescent/)
   2. [Udacity](https://www.udacity.com/course/deep-learning-nanodegree-foundation--nd101) .
