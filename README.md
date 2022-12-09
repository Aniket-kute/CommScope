# CommScope Work Portfolio
### Analysis and Automation of tests defects using Python & Power Bi for One Cell product line at CommScope

**Dataset:** We have around 500 .csv files coming in every week(~2000 files every month) showing test results for varied tests for the part number for One Cell Product Line
          Every file had around 150 lines of output (Results of every test done for that part number)
          
**Issue:** Unable to track the root causes(which part number was failing which test), data was too complex, lot of manual work (6-hour analysis every week to report visuals in Excel)
 
 
_Possible solutions that I tried for this problem:_


**1. Excel:** We can run a VBA code to merge all these files and create a single .csv file and later push this file to a visualization tool (ex. PowerBi)
          _Disadvantage:_ Excel has a limitation of ~1mn rows, so it will be difficult to work with files that generate more than a million rows every month. Also, for data                             transformation and cleaning for every file using VBA, the computational time was really high to go through every file and make the changes. 
 
**2. Alteryx**: Alteryx was an excellent solution to this problem, but 
          a. It has limited functionalities with a free version  
          b. It is expensive. We might have to buy licenses for all the users. We were planning to implement a similar automation system to different product lines   within our Business unit, so getting permits for everyone would have cost our Business much money.

**3. Python**: Python is a free, open-source programming language. It has rich libraries which exactly suit our business needs. The code is readable. It can be easily implemented to other product lines within CommScope with just a bit of change within code. Data cleaning, and processing is very fast with Python. (It takes me seconds to run the complete models and to push the file to my visualization tool: Power Bi)

**My Contribution:**
1. I was able to automate this entire process using Python.  As a result, I saved 6 hours of weekly work along with being able to find out the root cause analysis.
Current workflow
<img src="commscope_work_portfolio/process.png">

**Impact of this project:** 
----
I could identify specific failures with the help of these dashboards and the results were further provided to the engineering team at the plant location. As a result, once the changes were made, we monitored the results for the next month, and we found out that the improvement in the yields were more than 90% and the repeat testing was reduced by 45%, which was a major breakthrough for us since we have a product line in its testing/pilot phase.
                    This dashboard is now used by the senior engineer to show the results for every weekly meeting.
                    
 People who will be using this dashboard:
 Senior Engineer,
 Principal Engineer- Test development,
 Quality Manager,
 Principal Manufacturing Engineer,
 Director- Quality,
 NPI Product Engineer.

**Dashboard:**

<img src="commscope_work_portfolio/AUTOMATION.png" WIDTH="1000">













 

