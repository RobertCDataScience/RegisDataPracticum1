# Robert Carter Data Science Practicum - Jane Street

Link to Presentation: https://youtu.be/BR-uO3K9CY4

Link To Data: https://www.kaggle.com/c/jane-street-market-prediction/data

**Jane Street Dataset**
The data comes from a Kaggle competition Jane Street Market Prediction. It includes over 2 million rows of data and more than 130 columns of data accross 4 spread sheets. I mainly worked in the Train data set as hit had all of the information that applied to the competition.

As far as clening the data there wasn't much to clean. The data came in pretty good condition. The only thing that I adjusted was the removing rows were the predicted variable was set to zero because Jane Street placed a 0 in the column to fill the data.

**Modleing**
I choose to use Linear and Logistic Modeling for the data. Logistic worked best becuase it had better predicting power when it came to predicting holding or selling .
**Results and Conclusion**
I ran two models One with all of the included fields above and one with only those variables that were significant in the first model and I was able to get about 51% accuracy. Also, I used the AUC score to determine if the model is usuable.
The data was hard to wrangle because of its size and my experience. It was definitely eye-opening and a great learning experience.

