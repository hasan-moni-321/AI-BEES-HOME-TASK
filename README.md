# AI-BEES-HOME-TASK

### What Transformer Models I Used 
1. T5 Model 
2. BERT Model 

### Why T5? 
I used T5 for generating summary of the text. Those summary will be used as an comment but it is not a good practive counting summary as a comment. For this I used BERT for generating Name Entity and then generating comment based on name entity. 

### Why BERT? 
BERT for generating Name Entity. Those entity will help for generating commment because comments must be based on entity. 


## Example of Generated Comments from text based on anme entity

##### Text 


##### Generated Name Entity
Iranian officials , surveillance system

##### Generated 5 Comments from one text  
1. 'Iranian officials, surveillance system and other services have been infiltrated or used for a variety of cyber activities to compromise the U.S. and to influence'
2. 'Iranian officials, surveillance system experts and technology specialists say that Iran "does not have a nuclear weapon right now." The Iranian claims were repeated by the White House on Tuesday, as the president sought to'
3. "Iranian officials, surveillance system that allowed it to monitor emails of thousands of Iranian citizens, and Iranian bank's ability to launder millions of dollars via its secret connections with rogue entities.\n\n\nOn Monday, President Barack Obama made the most dramatic U"
4. 'Iranian officials, surveillance system, and the Iranian nuclear program, a former CIA official with knowledge of the case said. He declined to be identified because he was not authorized to talk to the media.\n\nThe former agent said that while Iranian officials have been "very aggressive, and I\'ve seen'
5. 'Iranian officials, surveillance system to collect data of emails and phone calls through the private, encrypted network\n\n, surveillance system to collect data of emails and phone calls through the private, encrypted network Iran says its spies will intercept phone calls and emails of American citizens\n\nAccording to The New York Times, it did so earlier this year in the operation'


### How to Improve Performance 
1. Use hyperparameter tuning and increase the nuber of training epoch for BERT model. I used only 3 epochs due to GPU shortage. 
2. Choose the best parameters for the GPT model and use GPT3 model instead of GPT2 for better comment generation. 


### Note 
I build a simple database and app due to time shortage. 
