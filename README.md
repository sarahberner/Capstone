Alright!

We need to figure out a data science problem. What should it be?

EDA steps:
look at the deck archetypes, and plot things! 
 - histogram of types of cards in each deck
 - overall win rate
 - most popular cards


 
 Data science problem:
  1.  Unsupervised learning - what is going on in the current meta? What can we determine about card popularity?
       - clustering this... isnt anything visual!? data much larger than 2D. What can we even do with it?
       - PCA?
  
  2.  Supervised learning - can we accurately predict:
       - the enemies deck archetype given the hero class?
       - given the first card played?
       - given the first three cards played?
       - have a live update on the percent 'chance' you have of winning for all of the above?
       - real challenge: can our model predict OTHER CARDS in the deck?
       
       I JUST REALIZED THIS IS NOT A MODEL. THIS IS JUST PERCENTAGE STUFF.
       
       Can we accurately predict the TYPE of deck (aggro, control, etc).(I would need more data for this :/)
       
       If a deck will succeed in the meta? HOW to do this - need clustering and NLP stuff....
       
       
       
       DO popular/successful decks have the "Best" cards?
       
       can we predict rarity of cards in the deck from deck performance? * get dust info 
       
       
       target variable is rarity of a card *** based on what deck its in/ win rate
       
       
       
       
 Awesome future ideas:
 https://www.andronio.me/2018/08/19/building-hearthstone-decks-with-word-embeddings/
       
       
    
  
  
    
