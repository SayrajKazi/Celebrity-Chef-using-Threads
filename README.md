# Celebrity-Chef-using-Threads

Two (well NUM_CHEFS) chefs, Gordon "Hittite-smiter" Ramesses II, and Mrs Nellie Lovett want to create NUM_DISHES_TO_DO interesting dishes each. How fortuitous! 

NUM_CHEFS gourmands, Wimpy and Jughead are extra hungry. They both want to eat NUM_DISHES_TO_DO. (A "gourmet" likes fine food. A "gourmand" just likes food, and

lots of it.)  There is one teeny-tiny problem: There is only one table instance, and it can only hold one dish at a time! All four people run in their own threads

and keep cook()ing or eat()ing, disregarding the other three.  That means that the table has to be made thread-safe!

