### Overview of Project:
-
- The purpose of this analysis was to see what the total volume and return percentage was for certain stocks. By analyzing the return on investment for given stocks we can provide Steve with actionable insights as to which stocks are worth investing into. In order to run this analysis for Steve and his family a VBA script must be coded to show actual volume and return percentage. The return column represtn the return on investment. For example if tikcer XYZ had a return of 20%, for every $100 dollars invested the profit would be $20. After seeing the retuns on the  Tickers Steve can help his clients make a business decision as to which stocks are the most profitable in 2017 and 2018. 
[]()



### Results:
-
-	In 2017, all Stocks in the data set yielded a profit besides ticker TERP which had a return of -7.2%. Ticker DQ yielded an impressive return of 199.4%. However, in 2017 DQ had the lowest volume. Meaning this stock is not being traded as much as the other typically for a good reason. The price can be easily manipulated if the volume is low and can sometimes be a red flag. If Steve's client are looking for a long term investment then low volume should be taken into consideration. In 2018 only ENPH and RUN yielded retuns with 81.9% and 84%. We can see DQ was indeed not stable because it yielded the lowest retun at 62.6% return. Analysis was done to see if there is any trend between volume and return but there is no correlation as seen on the graph below. Based on this analysis ENPH and RUN seem to only two stocks Steve's clients should invest in.

 ![alt text](https://github.com/ArshiSingh95/Stock-Analysis/blob/master/Resources/2017VR.png?raw=True)
 ![](resources/2018VR.png)
 
 
 
 ## Refactored Code & Run time
 	
 	
 	![](resources/2017VR.png)
 ![](resources/Code_Refactored1.png)
 ![](resources/Code_Refactored2.png)
 	
 	
 	
 	Attached is the refactored code used to run the volume and return analysis for 2017 and 2018 tickers.
 	In the refactored code  we define two more for loop to have to seperate iterations as opposed to having a nested loop. This allows for more effeiceny and run times are located below. 
 
 
 
 - After the code was refactored the efficiency inceased drastically. For example, the 2017 code improved by 100% from .17 seconds to .0859 seconds.
 
 
 
 ![](resources/VBA_Challenge_2017.png)
 ![](resources/VBA_Challenge_2018.png)



###Summary: 
-  Generally refactoring code comes with advantages and disadvantages. If one is not an adept coder a refactored code may be beneficial since majority of code is provided. A disadvantge might be if a code has an error prior to the refactoring. 

-  In regards to VBA script refactoring code was helpful because most of the code was provided and we simply had to adjust the for loops.
