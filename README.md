# OULA-DataSet-CaseStudy
### DFI Data Analyst Task

***Data Source:***

Open University Learning Analytics dataset (OULAD)
https://analyse.kmi.open.ac.uk/open_dataset

***Data Description:***

It contains data about courses, students and their interactions with Virtual Learning Environment (VLE) for seven selected courses (called modules). Presentations of courses start in February and October - they are marked by “B” and “J” respectively. The dataset consists of tables connected using unique identifiers. All tables are stored in the csv format.

***Tables:***
- courses
- assessments
- vle
- studentInfo
- studentRegistration
- studentAssessment
- studentVle

***Screenshot of Intersurface (Any two tables)***

:star:Table 01:

![Table01-studentVle](https://user-images.githubusercontent.com/83144665/149256358-2ceeef46-aae7-4122-aa2b-d000e4c67516.png)

:star:Table 02:

![Table02-studentInfo](https://user-images.githubusercontent.com/83144665/149256386-5ac3decc-7874-4f31-99a4-89446447bb9d.png)

***SQL***

- Step 4 & Step 5

Using SQL join the studentAssessment and studentInfo tables by the id_student variable.
Create a summary of the mean score, summarized according to region.

![SQL step 4 5](https://user-images.githubusercontent.com/83144665/149257940-ef8479a1-1f55-445c-a362-f5b33da67277.png)

** Because of limited space, only first 12 results are shown. 

- Step 6

Select all students from the studentInfo table who live in a region that has a name where the letter 'c' is the second letter

![SQL step 6](https://user-images.githubusercontent.com/83144665/149258174-831422f8-3392-4a8f-b57b-a7f34f12c4be.png)

** Because of limited space, only first 14 results are shown. 

***Any investigation***

- 7.1 Find the number of withdrawn registration per region

![image](https://user-images.githubusercontent.com/83144665/149400534-d72725b5-eb7a-4888-9ba1-cf31b6ce1b44.png)

** London Region is the region has the highest student withdrawn from registration


- 7.2 Find the number of students passing different assessments type in different semester

![image](https://user-images.githubusercontent.com/83144665/149400895-8f10949d-f5a5-41f2-91b0-d20bb4bd738f.png)

** CMA assessment has the highest number of students passed the assessment among all the presentation


- 7.3 Find the average number of times a students interacts with the material in region contains "u"

![image](https://user-images.githubusercontent.com/83144665/149401239-72b1adce-3f15-4056-9820-8596b10e3d5e.png)

** The average number of times a students interacts with the material in region contains "u" are between 3.59 and 3.78


***Visualization - Tableau

Step 9.
Write a short explanation of the pattern you found and why you chose to visualize it the way you did.

Step 10.
Ensure that you have forked and cloned this repository. Upload your screenshot from step 3, your image from step 8, a text file including your explanation and a text file including all your SQL code. Please then pull request your work back to the main branch.

Good luck!
