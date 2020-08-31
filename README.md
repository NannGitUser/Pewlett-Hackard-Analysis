# Pewlett-Hackard-Analysis (Taken in the late 1970s?)

## Our Aging Engineer Workforce

Our company is aging rapidly. Overall, we have approximately 65 thousand employees born between 1952 and 1955. Over half of those employees (33 thousand) are in Engineering, ranging from Assistant all the way to Senior Engineer. They are overdue to retire and I am surprised they haven't retired already. It is imperative that we replace these employees as effectively as possible in the next few years. 
![Retirement Age Employees by Title](https://github.com/NannGitUser/Pewlett-Hackard-Analysis/blob/master/retirement%20age%20by%20title.png)

Pewlett-Hackard has a very limited mentorship program. Employees who born in 1965 are eligible for this program. That totals to about 3,100 employees. We believe we should increase the eligibility for mentorship in order to effectively replace our aging workforce. If we expand the eligibility to Employees born 1963 and 1964, we would increase the eligibility by over 40 thousand. That is more than enough to cover our future retirees. We need new employees and new ideas. 

## What we addressed
* The overall numbers of our aging boomer workforce.
* We are set to lose our core engineers within the next few years.
* Our mentorship program can help alleviate this.
* We need to expand the eligibility of this mentorship program. 

## Further analysis
Our database is very limited. This is likely due to the fractured nature of adding data. Here is how is looks right now. 
![Employee Database Structure](https://github.com/NannGitUser/Pewlett-Hackard-Analysis/blob/master/Employee%20Database.png)

This works, but could be simplified. We have not went in and created a simpler database structure for more popular queries. I had to submit tiered SQL query to attain the latest job title for each employee. It would be much simpler to scrub the title database of past employee titles and put that into another database for historic queries. We really only need to know there current title 99% of the time. We can always do a special query if we want to know an employee's past title. 
