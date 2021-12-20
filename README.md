# Credit_Risk_Analysis
## Overview of Project
### Purpose
###### Jill wants our help in seeing if we can more accurately predict credit card risk. She wants us to use all methods that we've covered regarding machine learning to see if there is a preferred method moving forward.
## Results
* ###### There are over 90,000 employees coming up on retirement age, 90,398 to be exact. While every employee will most likely not retire when they immediately hit that age, this is a significant number. If hiring measures don't start taking place to ensure that there is an adequate number of employees trained & working by the time this set of employees do start retiring, the company is going to be hit hard.

![2017 original script run time](https://github.com/liabrooke/Pewlett-Hackard-Analysis/blob/main/Unique_titles_count.png) 

* ###### Considering a majority of these employees have most likely been at the company for 10+ years or have been in this field their whole life, many of the retiring employees have been promoted/assigned to senior roles. The biggest hit role is "senior engineer" with 29,414 employees coming up on that retirement age, with "senior staff" hit second at 28,254. Management needs to look at their employee database to see which "engineers" and "staff" can be promoted to "senior engineers" and "senior staff".
* ###### Only 1,549 retiring employees are eligible to participate in the mentorship program which would train the next generation of Pewlett Hackard employees. This is not a signicant number of employees and could significantly impact the company.

![2017 original script run time](https://github.com/liabrooke/Pewlett-Hackard-Analysis/blob/main/Mentorship_eligibility_count.png) 

* ###### The original count of employees from the "retirement_titles.csv" showed 133,776 which was then shorted to 90,398 through the "unique_titles.csv" once we took out the employees who changed titles/got promoted. Over 43k employees were either promoted/changed titles which shows good growth at the company & further proves the point to promote from within, not necessarily hire new employees to automatically fit the senior roles.

![2017 original script run time](https://github.com/liabrooke/Pewlett-Hackard-Analysis/blob/main/Retirement_titles_count.png) 

## Summary
### How many roles will need to be filled as the "silver tsunami" begins to make an impact?
###### There is the potential of 90,398 roles needing to be filled. Almost 60,000 of these 90,398 appear to be senior staff, which is a big hit to the company. Management needs to start identifying which of these senior staff are most likely to immediately retire, and whether they're going to promote internally to fill these senior roles or hire from the outside. Will promoting or hiring from the outside be more cost-efficient, and even if one outweighs the other, is there still inherent benefit in promoting from within? Also, current employees in lower-ranked roles need to be analyzed to see which would even be eligible for promotion. Is there any adequate amount of eligible employees to even fill 60,000 senior roles, and if not, when should management start hiring?
### Are there enough qualified, retirement-ready employees to mentor the next generation of Pewlett Hackard Employees?
###### There are only 1,549 employees elibile to mentor the next generation according to the requirements given to us, which is not nearly enough. However, there is not a clear reason given as to why only employees born in 1965 would be eligible to mentor. Instead of filtering by birth_date, there are different factors to consider, such as job title, whether they had been promoted, and how long they had been at the company. The whole mentorship_eligibility table needs to be re-analyzed to come up with a more accurate, and probably higher number of employees, that would be eligible to mentor. Identifying the proper employees eligible to mentor could greatly save the company in time & money spent training new hires or current employees soon to be promoted.
### Two more queries or tables to analyze?
###### While we see the "titles" of employees that are being hit, we don't see which of the nine departments they're associated with. Doing a join analysis of the "departments", "dept_emp", and "unique_titles" table could determine which departments are being hit the hardest. Another aspect that could hit the company is money lost from salaries. Doing an analysis of the salaries of the employees retiring, and gathering data about inflation for those salaries/roles, could determine if the company will have to start offering hiring salaries to the next generation of senior staff. This is because employees working at a company longer/being promoted internally may make less/expect less than new hires. The first step would be joining the "unique_titles" and "salaries" tables, and then importing inflation data.
