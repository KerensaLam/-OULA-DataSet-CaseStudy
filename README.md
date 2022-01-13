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

Step 7.
Using any varibles from any table look for a pattern that you think is interesting. Please show any code you utilize to investigate the tables.

Step 8.
Using whichever visualization software you are most comfortable with, please visualize the pattern you identified in the data and save the image.

Step 9.
Write a short explanation of the pattern you found and why you chose to visualize it the way you did.

Step 10.
Ensure that you have forked and cloned this repository. Upload your screenshot from step 3, your image from step 8, a text file including your explanation and a text file including all your SQL code. Please then pull request your work back to the main branch.

Good luck!
