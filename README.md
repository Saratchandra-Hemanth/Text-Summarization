# Text-Summarization
1.Title of project
   Abstratice text Summarization using Recursive neural networks   
     
2.Project description  
   2.1 In the project we are trying to generate meaningfull and simple reviews from the big orginal reviews  
   2.2 Here we are using tensorflow, numpy, pandas, nltk libraries.  
   2.3 We didn't use complete dataset for traning our model due to lack of good hardware. We only used a subset of the complete dataset.  
       We hope to implement it with complete dataset.      
  
3.How to install and run the project  
   3.1 Download the code and dataset from the Kaggle  
   3.2 Replace the location of dataset in code with your dataset location.  
   3.3 keras does not officially support attention layers, so we are using attention layer from  
	https://github.com/thushv89/attention_keras/blob/master/src/layers/attention.py  
  
4. How to use project  
   4.1 Train the model with complete dataset if you have good hardware      
   4.2 Try to predict summaries for the reviews and see if they are relevent with the actual summaries.  
