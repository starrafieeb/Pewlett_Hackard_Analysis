# Pewlett_Hackard_Analysis
The goal of this project was to act as a Human Resources Analyst to determine who will be retiring in the next few years and how many positions (and titles) will Pewlett Hackard need to fill. By doing this I helped future-proof PH by generating a list of all employees eligible for the retirement package and a list of how many job titles are going to be open after that generation of employees retires.

Here is employee database relationship diagram for Pewlett Hackard: 


![EmployeeDB](https://user-images.githubusercontent.com/100812201/164980245-17291d92-0e7c-49e9-b937-ac65926069b0.png)


# Results
1- With the first review of creating a list of potential "silver tsunamis," the query resulted in many duplicates due having multiple positions. 

<img width="615" alt="title" src="https://user-images.githubusercontent.com/100812201/164980520-cae1acdd-155e-410f-b29f-07267e9704c6.png">

2- Using the 'distinct on' SQL script, the duplicates were removed leaving the most recent job title to create a unique list of retiring employees.

<img width="472" alt="uniquetitle" src="https://user-images.githubusercontent.com/100812201/164980538-f40f127c-2967-46f4-8088-6fd31cee5fe6.png">

3- Retiring Counts by Title for a total of 90,398 potential retirees.

<img width="206" alt="retireingcount" src="https://user-images.githubusercontent.com/100812201/164980563-15bc7130-cea2-4550-94b6-ed024c826d91.png">

4- Mentor Eligibility List of 1549 employees born in 1965.

<img width="627" alt="mentor" src="https://user-images.githubusercontent.com/100812201/164980640-ef968a8b-38a3-4fda-981e-82dbac372e71.png">

In conclusion, it all depends on how many retiring employees are willing to stay and mentor others. Nevertheless, a good mentor to mentee ratio I would say is 1:3. That is one mentor for 3 new employees. Assuming each year there are more or less 13,000 employees retiring and 13,000 new employees entering, we would need 3,000-4,000 mentors distributed proportionally in all the departments. We would need that in order for every department to stay put, at least 25% of the retirees accept the mentorship program because that would leave PH witha a 1:3 ratio.

We can see that there is an explicit pattern in the results. There is one group consisting of the first three departments with more than 2000 employees leaving on each of them, and there is another group with the rest of the departments with around 700 to 800 employees leaving on each of them. In order for this to work, 25% of retiring employees should be able to stay mentoring (1:3 ratio) that would be somewhat like 188 mentors for each Marketing, Finance, HR, Research, Quality Mgtm, and Customer service and around 625 mentors for Development, Production, and Sales.
