# Pewlett_Hackard_Analysis

## Overview

In the module I was manipulating and querying the data to find employees eligible for retirement. In the challenge, I was tasked with determing eligible retires by department and to identify those that are eligible for the mentorship program.

## Results

* The total number of employees eligible for retirement is 33,118 based on the parameters I was given. Those were found using the following code:

![unique_titles_code](https://user-images.githubusercontent.com/81715217/122688635-09600080-d1e3-11eb-9c58-0d1fd18b9b42.png)

* Of the employees left, only 1,549 are eligible for the mentorship program based on the parameters given. The folowing code demonstrates those:

![mentoriship_eligibility_code](https://user-images.githubusercontent.com/81715217/122688668-47f5bb00-d1e3-11eb-8eac-57fc3c03d2f7.png)

* The Senior engineers and senior staff are losing the most.

![retiring_count](https://user-images.githubusercontent.com/81715217/122688700-783d5980-d1e3-11eb-997a-f59e0ce93061.png)

* The count for each title retiring doesn't match the total eligible for retirement. I delivered the expected result in the module but the numbers are an inaccurate when compared to the unique_titles.csv when filtered. Further analysis needs to be done to determine an accurate number.


## Summary

There are two questions to answer.

* How many roles will need to be filled as the "silver tsunami" begins to make an impact?
    *According to the retiring_titles count information we put together, 90398 are eligible to 
    *retire.

![retiring total](https://user-images.githubusercontent.com/81715217/122697572-33c5b400-d20b-11eb-9ea1-a0347c6d8191.png)

* Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
  *I refactored the codes used to find the retirement totals to look at employees born between January 1, 1956 and December 31, 1960. With those parameters the availble mentors are higher than number retiring. If you combine that with reformatting the company, there will plenty available to mentor.
  
  ![unique_mentor_counts](https://user-images.githubusercontent.com/81715217/122698569-2f01ff80-d20d-11eb-810f-045404b3c865.png)

