# CommScope work Portfolio
Analysis and automation of tests defects for One Cell product line

Dataset: We have around 500 .csv files coming in every week(~2000 files every month) showing test reaults for varied tests for the part number for One Cell product Line
          Every file had around 150 lines of output (Results of every test done for that part number)
          
Issue: Unable to track the root causes(which part number was failing which test), data was too complex, lot of manual work (6 hour analysis every week to report visuals in Excel)
 
Possible solutions that I tried for this problem:
1. Excel: We can run a VBA code to merge all these files together and create a single .csv file and later push this file to a visualizatio tool (ex. PowerBi)
          Disadvantage: Excel has a limitation of ~1mn rows, it will difficult to work with files that generates more than a million rows every month. Also, for data                             transformation and cleaning for every file using VBA, the computational time was be really high to go through every file and make the changes. 
 
2. Alteryx: Alteryx was a good solution to this problem, but 
             a. It has limited functionalities with free version 
             b. It is expensive. We might have to buy licenses to all the users and we were planning to implement a similar automation system to different product lines                 within our Business unit, so getting licenses for everyone would have cost out BU a lot of money.
 
My Contribution:
1. I was able to automate this entire process using Python

 

