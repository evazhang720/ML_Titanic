
# Predict Survival On the Titanic

## Introduction

>This is our final project. We worked with the training set within Titanic data that is from Kaggle after spending time finding. The sinking of the Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, causing 1502 death out of 2224 passengers and crew.  
 
>This dataset contains the data of 891 Titanic passengers. Specifically, there are 577 females, and 314 males in this dataset.  

## Data Source

>Download the dataset from Kaggle, the link as following: 
       
>https://www.kaggle.com/c/3136/download/train.csv

# Limitation
Due to the fact that there are too many missing values(177/891) in the variable “Age”, it is unlikely to make a perfect imputation, which might affect the prediction. 

## Setup
* **Platform：** Anaconda-Juypter( Download from following link:https://www.anaconda.com/download/)
* **Dependencies:** Python 3.6
* **Modules：**        
>* Numpy             
>* Pandas  
>* Seaborn 
>* Matplotlib 
>* Scikit-learn  

# Project Files
>* **README.md:** Describing the project and how to run the code 
>* **train.csv:** The dataset that we used for this project
>* **Code_Final_ML1_Group16.ipynb:** Code of our project
>* **Report_Final_ML1_Group16.pdf:** The report of our project

# Installation

**To run this notebook:**  
**1. Download the file**  
>For Windows Users:  
* 1).Download git from the following link: https://git-scm.com/download/win and install it by simple click "Next" command 
* 2).Go to your Desktop, and right click left-click the mouse, and type, then choose "Git Bush Here 
* 3).In the git, type 'cd ~/Downloads'
* 4).Then, type 'git clone https://github.com/evazhang720/Tatanic.git'
> For Mac Users:
* 1).Open the 'Spotlight Search'
* 2).Type the'terminal' in the 'Spotlight Search'
* 3).In the terminal, type 'cd Downloads'
* 4). Then, type 'git clone https://github.com/evazhang720/Tatanic.git'
 
**2. Open the file**
>* 1).Open the 'Anaconda', then click launch 'Juypter'
>* 2).Click 'Downloads', then click 'Tatanic', then click 'Code_Final_ML1_Group16.ipynb'

**3. Run each chunk：**  
>* Shift + Enter

# Goal 

>In this project, we will apply machine learning techniques to build the optimal model, find the most valuable predicators, and predict the probability of survival on the Titanic. 

### This notebook will show basc example of:


>* **Importing data with pandas** 
>* **Data overview** 
>* **Initinal data analysis** 
>* **Data cleaning** 
>* **Encoding**
>* **Build model**

# Conclusion

>Overall, the last model we made has came up with a very high AUC value, which we believe it will give a relatively accurate prediction on the survival probability on the Titanic. 
