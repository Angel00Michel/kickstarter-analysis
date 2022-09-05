# Kickstarting with Excel
    ## Overview of Project
        ### Purpose
        
            *The purpose of this analysis is to give more insight for Louise when it comes to planning her campaign in hopes of achieving success. Louise is aiming to raise a minimum budget of $10,000 for her crowdfunding campaign in order to fund her play titled, "Fever". This analysis that I have made has given guidance for when, how, and where to plan her intial campaign date. I am confident that Louise is able to define this organized, sorted, & analyzed crowdfunding data to determine if there are consistencies or inconsistencies when launching successful campaign projects.

    ## Analysis and Challenges
        ### Analysis of Outcomes Based on Launch Date
            =HYPERLINK("[Kickstarter_Challenge.xlsx], Theater Outcomes by Launch Date!")
            
            * My analysis of Outcomes Based on Launch Date is relying on the amount of theater campaigns that were created in the Years dating back to 2009, including the amount of theater campaigns throughout the month of each year. I didn't seem to use any functions, but I did make numerous graphs & 1 table to form a proper analysis of data dating back to the Year of 2009. One depiction I am able to make, with the table/graphs I created, would be that about two-thirds (66.7%) of the campaigns that were launched from June-August were deemed successful; these months have the most potential to reach, or even exceed, the desired goal amount. 
            
            
            /Users/angelmichel/Desktop/Resources/Theater_Outcomes_vs_Launch.jpg
            /Users/angelmichel/Desktop/Resources/Theater_Outcomes_vs_Launch.png
            
            
        ### Analysis of Outcomes Based on Goals
        
            =HYPERLINK("[Kickstarter_Challenge.xlsx], Outcomes Based on Goals!")
            
            * My analysis of Outcomes Based on Goals is dependent on the goal amount for plays in the successful, failed, & canceled categories. I also calculated the likelihood (percentage) of the total projects for each given goal amount (ranging from less than $1000 all the way to $50,000+) comparable to the success rate, failed rate, & canceled rate of each play campaign. The formula that I used for succcesful campaigns that are '50,000 or more': =COUNTIFS(KICKSTARTER!D:D, "=50000", KICKSTARTER!F:F, "successful", KICKSTARTER!D:D, ">50000", KICKSTARTER!R:R, "plays"). I also use the same formula for each desired row/column that is necessary when tweaking the goal amounts (to fit incriments of about $5,000) for the number of successful, failed, & canceled campaigns. When I went to calculate the probablities of campaigns either being successful, failing, or canceling. The formula I used for this chart in the 'Percentage Successful' (failed & canceled columns, as well) column was: =IFERROR(B2/E2,"0.00%"). I used an 'IFERROR' statement to work around any misdirection that Excel may throw at us, due to us being unable to divide 0/0. The percentage calculations were just fractions at the end of the day. 
            
            
            /Users/angelmichel/Desktop/Resources/Outcomes Based on Goals.jpg
            /Users/angelmichel/Desktop/Resources/Outcomes Based on Goals.png
            
            
        ### Challenges and Difficulties Encountered
        
            *The challenges that I have encountered were pretty mind-boggling, if I do say so myself. It was for the worksheet titled "Outcomes Based on Goals", I had an encounter with a graph that wasn't being displayed correctly. This graph trouble stemmed from me selecting Columns (A,F,G) and initially tried to scan (using "CMD") the column to its entirety. It seemed to have worked the first time trying it, then, I started switching the positioning of the entire data sheet; by accident. Finally, when I went to just scan (using "CMD") the columns of desired data; it seemed to have populated another set of data for some weird reason. I was then able to graph the chart correctly by using the select data option when I double clicked on my mouse, then I was able to select and eliminate the data of the desired columns just by manipulating the chart to its entirety. I honestly had no idea what I was doing at first because the ASKBCS (Laanu, whom was of great assistance) made me share my screen and then I just followed instructions. In conclusion, after the Zoom call was finished, I opened a new worksheet and started hacking away at it and NOW I seem to fully understand how to insert/manipulate/depict charts and turn them into graphs for each set of data. 

- What are two conclusions you can draw about the Theater Outcomes by Launch Date?

    * One proper conclusion that I am able to depict from the 'Theater Outcomes by Launch Date' worksheet, is that there seems to be a successful pattern & a pattern of failure happening in the months of June/July/August. There is a trend in successful & failed campaigns due to a majority of them thriving with success for the months of June - August. 
    * Another conclusion that I am able to make is that all of the successful campaigns that were launched, dating back to 2009, have the potential to succeed if it were to be labeled as a Theater campaign. If the intention was to launch Theater campaign in June/July/August, the statistics state a campaign would be successful; if it fit a reasonable goal amount of about <$5,000 - $5,600>. 
            
- What can you conclude about the Outcomes Based on Goals?

    * The conclusion for 'Outcomes Based on Goals' worsheet, is that all of successful campaigns that are plays tend to thrive due to the goal amount of the entire play being less than <$5,000>. Any play that had a goal amount of <$5,000 or more> had the expectation to fail less than 50% of the time due to the budget of plays being substantially greater than <$5,000>. Which then allows us to believe that any campaign with a goal amount exceeding <$5,000> will most likely fail. 

- What are some limitations of this dataset?

    * Some limitations of this dataset would consist of some of my graphs being 'incomplete' due to one of the rows being unable to be identified correctly, which leads me to believe that when I selected the desired rows or columns it misrepresented my graph. What I learned was that the limitations of data involved in my work, I actually came to a proper conclusion that resembled the graphs in Module 1 Challenge. With some limitations involved, I came to the conclusion that if this data sheet displayed whole numbers, rather than just "0", it would resemble my graph correctly. So, when I didn't scan all of the zeros in my chart it gave me the correct graph but I could see how checking for limitations on date could be imporatant. You obviously don't want a misinterpreted analysis, unless some limtations of the data are necessary for your end goal. 

- What are some other possible tables and/or graphs that we could create?

    * One possibility to create interpretative tables/graphs would be to create a Paleto Chart. Which is basically a boxplot that catergorizes your data from the first row to the last row of desired data, this enables you to see a skewed graph that prioritizes the largest number of any column/row to give you a more accurate representation of the largest 'outcome' from the data. Another recommendation for a well articulated graph would be a Funnel chart. This shows the extent of how big a set of data can be represented, in a vertically downward position; such as a funnel for oil. 
