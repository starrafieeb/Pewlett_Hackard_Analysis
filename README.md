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

