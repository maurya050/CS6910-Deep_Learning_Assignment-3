# CS6910-Deep_Learning_Assignment-3
Assignment_3 submission for the course Fundamentals of Deep Learning (CS6910).


- *This repository contains the implementation of a Recurrent Neural Network (RNN) based sequence-to-sequence transliteration model , We have used Telugu language dataset from the  Aksharantar dataset and here we are concern more with Word Accuracy rather than character accuracy and We are getting Validation Word Accuracy as 56.4 %.*

- *Our focus mainly on word correctness. so, we picked our best model to  maximize validation word accuracy.*

- *Also, after some manual testing , we found Adam algorithm effective. So, the optimizer was fixed as Adam.*

## Jupyter Notebook files
1. [A3_Q1toQ3.ipynb](https://github.com/maurya050/CS6910-Deep_Learning_Assignment-3/blob/main/A3_Q1toQ3.ipynb "Code for Question 1 to 3")
    <kbd>
    <div class="my-section" style= border: 1px solid #e1e4e8; "background-color: #f1f1f1; padding: 10px;">
        
         * This file contains the code for Question 1 to Question 3
        
         * In this .ipynb file , i have trained the vanilla model and then run sweeps.
        
         * To run the file on Google Collab at TA end, import the file and then,  change the wandb login key.
         
         * And also change the google drive dataset link.
                            
         * Now, just run the file from the start you will get all the results mentioned.
        
    </div>
    </kbd>
 
 2. [A3_BestModel_Q4(a).ipynb](https://github.com/maurya050/CS6910-Deep_Learning_Assignment-3/blob/main/A3_BestModel_Q4(a).ipynb "Best Vanilla Model")
    <kbd>
    <div class="my-section" style= border: 1px solid #e1e4e8; "background-color: #f1f1f1; padding: 10px;">
        
         * This file contains the code for Question 4
        
         * In this .ipynb file , i have trained the vanilla model on best parameter.
        
         * I found LSTM as my best model, where we got the Highest Validation Accuracy of 56.4%.
        
         * And For Test Dataset we got the Accuracy of 50.8%.
    </div>
    </kbd>
        
   
 3. [A3_Q5.ipynb](https://github.com/maurya050/CS6910-Deep_Learning_Assignment-3/blob/main/A3_Q5.ipynb "Model with Attention")
    <kbd>
    <div class="my-section" style= border: 1px solid #e1e4e8; "background-color: #f1f1f1; padding: 10px;">
        
         * This file contains the code for Question 5
        
         * In this .ipynb file , i have trained the model with attention and then run sweeps.
        
         * To run the file on Google Collab at TA end, import the file and then,  change the wandb login key.
         
         * And also change the google drive dataset link.
        
         * Now, just run the file from the start you will get all the results mentioned.
    </div>
    </kbd>
    
 4. [A3_Q5_BestModel_prediction.ipynb](https://github.com/maurya050/CS6910-Deep_Learning_Assignment-3/blob/main/A3_Q5_BestModel_prediction.ipynb "Best Attention Model")
    <kbd>
    <div class="my-section" style= border: 1px solid #e1e4e8; "background-color: #f1f1f1; padding: 10px;">
        
         * This file contains the code for Question 5(c)
        
         * In this .ipynb file , i have trained the model with attention on the best parameter.
        
         * I found GRU as my best attention model, where we got the Highest Validation Accuracy of 54.7%.
        
         * And For Test Dataset we got the Accuracy of 48.4%.
        
         * If we try to run it for more counts , it might give better results than vanilla because, 
           it identifies many words which we couldn't identify in vanilla model.
    </div>
    </kbd>
    
    
 5. [A3_Q5_HeatMap.ipynb](https://github.com/maurya050/CS6910-Deep_Learning_Assignment-3/blob/main/A3_Q5_HeatMap.ipynb "HeatMaps")
    <kbd>
    <div class="my-section" style= border: 1px solid #e1e4e8; "background-color: #f1f1f1; padding: 10px;">
        
         * This file contains the code for Question 5(d)
        
         * In this .ipynb file , i have trained the best model(GRU) with attention on the best parameters fro Heatmaps
        
         * Selecting randomly 10 inputs from the Test Dataset for generating HeatMaps(shown in Wandb report)
           
    </div>
    </kbd>
    
 #### [predictions_vanilla](https://github.com/maurya050/CS6910-Deep_Learning_Assignment-3/tree/main/predictions_vanilla "Vanilla Prediction on Test Dataset") contains the file 'Van_Pred.csv' with  model's predictions on all the test dataset.
 
 #### [predictions_attention](https://github.com/maurya050/CS6910-Deep_Learning_Assignment-3/tree/main/predictions_attention "Attention Prediction on Test Dataset") contains the file 'att_predict.csv' with  attention model's predictions on all the test dataset.
 
 ## Report Link: https://api.wandb.ai/links/cs22m083/hbxl9nod
 
