# Pewlett-Hackard-Analysis
Report on "silver tsunami."

## Overview of the analysis: Explain the purpose of this analysis.
Manager noticed that this is going to be a "silver tsunami" as lot of people are going to get retired and team will lack experienced people. Manager found out the solution to introduce mentorship program. Retired employees will get a chance to work part time as a to mentor and train new employees.

Determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program.
 
## Results: Provide a bulleted list with four major points from the two analysis deliverables. Use images as support where needed.
1) Deliverable 1 - Gathered information about the Number of Retiring Employees by Title. The results is shown below. 
Fig: <img width="694" alt="Screen Shot 2022-07-25 at 11 43 51 PM" src="https://user-images.githubusercontent.com/106944351/180925015-cf801ad3-3124-495a-a2d8-381cb382b260.png">

2) Deliverable 1 - The above table gives duplicate values as employees have changed their teams or titles over the years. I used DISTINCT ON () to get unique values as in only most recent title of each employee.
Fig: <img width="516" alt="Screen Shot 2022-07-25 at 11 42 59 PM" src="https://user-images.githubusercontent.com/106944351/180924884-ce263e83-4f8b-4b6f-9b38-ce3cf456d06d.png">

3) Deliverable 2 - Determined The Employees Eligible for the Mentorship Program. 
Fig: <img width="827" alt="Screen Shot 2022-07-25 at 11 39 28 PM" src="https://user-images.githubusercontent.com/106944351/180924782-c40913cc-3abb-4fbe-ad0d-ce038e7e18ac.png">

4) Deliverable 2 - A query is written and executed to create a Mentorship Eligibility table for current employees who were born between January 1, 1965 and December 31, 1965.

## Summary: Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."
1) How many roles will need to be filled as the "silver tsunami" begins to make an impact?
Figure <img width="694" alt="Screen Shot 2022-07-25 at 11 43 51 PM" src="https://user-images.githubusercontent.com/106944351/180925015-cf801ad3-3124-495a-a2d8-381cb382b260.png"> shows that these many people are retiring and management should start the hiring people soon.

2) Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
Retirind title table  <img width="694" alt="Screen Shot 2022-07-25 at 11 43 51 PM" src="https://user-images.githubusercontent.com/106944351/180925015-cf801ad3-3124-495a-a2d8-381cb382b260.png"> explains how many employees are retiring and yes, there are enough qualified employees will be there to mentor the next generation.

### Additional queries - We can find out how many people are retiring from each and every department so that manager will have an idea about futrue resource management.
We can find out how many poeple are getting retired in next few years. So that,we use help of those soon to be retired people in mentorship or training program if we are lacking number of people in mentorship programs.
