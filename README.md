# NLP-Modeling-Senatorial-and-Presidential-Tweets

I obtained Twitter data from FiveThirtyEight containing all Tweets by President Trump, President Obama, and all current U.S. Senators. 

Using REGEX and lambda functions, I cleaned the text of the tweets. Using Pandas, I engineered and dropped features so the data frames could be merged and analyzed. 

Using NLP, I built predictive models answering 2 questions:
1.	Did President Barack Obama or President Trump publish a tweet?
  
  	Models used: 
     
         i.	Multinomial Naïve Bayes 
      
         ii.	Logistic Regression 
      
         iii.	Random Forest Classifier 
       
2.	Did a Republican or a Democrat publish a tweet?
  
  	Models used: 
      
          i.	Multinomial Naïve Bayes 
      
          ii.	Random Forest Classifier 

For both predictions, Counter Vectorizer performed better than TF-IDF.  
