# **Neural Network Charity Analysis**

##**Overview of Project**

I am working with Becks, a data scientist and programmer for Alphabet Soup- a non-profit foundation dedicated to helping organizations that protect the environment, improve well-being and unify the world. During the past 20 years, Alphabet Soup has raised on donated over $10B for lifesaving technologies and reforestation groups around the world. 
Becks is responsible for data collection and analysis for the organization. She has been tasked with analyzing the impact of each donation and vetting potential recipients to be sure the foundation’s donations are being used effectively.  

###*Purpose of Analysis*

Andy Glad, President of Alphabet Soup, asked Becks to identify which organizations the foundation should support and which are too high risk. Using the knowledge Becks acquired during a 24-week Data Boot Camp, we will explore a mathematical, data-driven solution to accurately predict risk. We will use machine learning, specifically the Python Tensa Flow library to design and train a neural network model . 

####**Results**	

Data Preprocessing 
  •	Target Variable for Model: “IS_SUCCESSFUL” 
  •	Featured Variables for Model: 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS'
  •	Variables Removed from Input Data: 'EIN' and 'NAME'

Compiling, Training and Evaluating the Model
  •	Original Evaluation Accuracy: 73%

![Image OG Eval] [https://github.com/FeliciaGanthier/Neural_Network_Charity_Analysis/blob/main/OG%20Eval.png]

  •	Optimization Attempt 1 Evaluation Accuracy: 63%
    o	Since a Rule of Thumb is increase the number of neurons in the hidden layer by two – three times, we increased the number of input features by three. 

![Image Opt Attempt 1] [https://github.com/FeliciaGanthier/Neural_Network_Charity_Analysis/blob/main/Opt%20Attempt%201.png]

  •	Optimization Attempt 2 Evaluation Accuracy: 73%
    o	In this attempt, we increased the number of neurons in each hidden layer by 20

![Image Opt Attempt 2] [https://github.com/FeliciaGanthier/Neural_Network_Charity_Analysis/blob/main/Opt%20Attempt%202.png]

  •	Optimization Attempt 3 Evaluation Accuracy: 72%
    o In our final attempt, we added an additional hidden layer
       
![Image Opt Attempt 3] [https://github.com/FeliciaGanthier/Neural_Network_Charity_Analysis/blob/main/Opt%20Attempt%203.png]

#####**Summary**

The Rule of Thumb gave me the least accurate results but making small increases to the existing hidden layers and adding an additional layer gave us more consistent results. Unfortunately, our accuracy isn’t up to standard so we’ll need to continue working on the model to get a number in the accepted range.  
