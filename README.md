# Credit_Risk_Analysis
## Overview of Project
### Purpose
###### Jill wants our help in seeing if we can more accurately predict credit card risk. She wants us to use all methods that we've covered regarding machine learning to see if there is a preferred method moving forward.
## Results
###### {Before we get started - I didn't fully finish the first deliverable before moving on to the next deliverable, since resampling using SMOTEEN took my computer a great deal of time. With the second deliverable, I had to uninstall SciKit 1.0.1 and install 1.0.0, which meant I had to restart Jupyter. Now when I try to run the resampling deliverable, it won't go past the ClusterCentroids line, which is not an issue I was having before. I attached a picture of the error but even though the code is there, the kernel keeps dying and I can't see the output. Which is obviously going to affect this analysis. Curtis recommended I download "pyenv" environment so I'm going to try that and hopefully get my whole code to run.}
######

![2017 original script run time](https://github.com/liabrooke/Pewlett-Hackard-Analysis/blob/main/Unique_titles_count.png) 

* ###### Considering a majority of these employees have most likely been at the company for 10+ years or have been in this field their whole life, many of the retiring employees have been promoted/assigned to senior roles. The biggest hit role is "senior engineer" with 29,414 employees coming up on that retirement age, with "senior staff" hit second at 28,254. Management needs to look at their employee database to see which "engineers" and "staff" can be promoted to "senior engineers" and "senior staff".
* ###### Only 1,549 retiring employees are eligible to participate in the mentorship program which would train the next generation of Pewlett Hackard employees. This is not a signicant number of employees and could significantly impact the company.

![2017 original script run time](https://github.com/liabrooke/Pewlett-Hackard-Analysis/blob/main/Mentorship_eligibility_count.png) 

* ###### The original count of employees from the "retirement_titles.csv" showed 133,776 which was then shorted to 90,398 through the "unique_titles.csv" once we took out the employees who changed titles/got promoted. Over 43k employees were either promoted/changed titles which shows good growth at the company & further proves the point to promote from within, not necessarily hire new employees to automatically fit the senior roles.

![2017 original script run time](https://github.com/liabrooke/Pewlett-Hackard-Analysis/blob/main/Retirement_titles_count.png) 

## Summary
###### I agree with Jill in the fact that even a small improvement is very important, so identifying the best approach is key. 
