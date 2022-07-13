# Reducing-the-burden-of-data-creation-using-automation
Name : Nitansh Vishwakarma 
Student Number : 219042776

Review Version 1

Spread sheet name	content	review	Suggested solution
ILR file example	It contains the final XML file which will be generated after getting details from the learners.	From this sheet, it is evident that what will the final outcome expected from the proposed solution.


•	This sheet contains information related to the data which is fixed
•	The data which will be entered manually.
•	The data which will be selected from a drop down, which reflect that these information 
•	Also this sheet contains information about the validation required for the data which will be entered by the user ( either manually, or from drop down)	From this excel sheet we would like to propose a web app which will be able to take user input in the form of a webform and once the data is gathered it will generate an output in the form of XML.

Apart from this we will be creating a data model for show proper relationship between the data that is being collected.
Designation Outcome	This spread sheet contains a relationship between Outcome Type, Outcome Code, Designation Outcome	From this excel sheet we can  find the solution for the ILR  ( reference row 164 and 165 )
But this data is dependent on the value of aims ( row 59 ILR)	A proper database to store the relationship between these and in the ux/ui this data will be handled using conditional statement
Status 	This spreadsheet contains information about the status of the learner	The status of the learner is associated with the learning process	A proper relationship table to store status code
Outcome	This spreadsheet contains information about the final outcome for the learners.	The outcome for the learner whether they have completed the learning process or not.	A proper relationship table to store the outcome for learners

Benefit Status	This spreadsheet contains information about the benefits which the learner will receive	The benefits received by the learner whether they are getting any allowance based on what their career status is(job seeker, employee or university student)	A proper relation t store the benefit status to be displayed in the dropdown
Aims	This spread sheet contains information related to the aims of learner, learner aim reference, aim type, funding model,dellocpostcode,lsdpostcode	From this excel sheet it is quite clear that aim type will be listed, there will be aim reference too, dates will be entered manually, funding models will get data from here, also it is restricted to the aim list, lsdpost code will be copied from somewhere else, dellocpost code will be entered manually by the learner	A  proper relationship to store aim reference number , funding models will be stored in a list or array, dates will be entered manually with proper validation in the format of DD-MM-YYYY



Employment status	From this excel sheet it is clear that here we have status of employment of the learner	It stored a code for the employment status which will be stored in the final outcome of xml	A proper table to store code and employment status.
Prior attainment 	This sheet show the code for prior attainment of the learner.	It stores a code for prior attainment which represents prior level of the learner	A proper table to store code associated with prior attainment
Household Situation	It shows a relationship between hss,code and the title of the learner	HHS is the type and a code is associated with a title which is getting stored in the final output xml 	A proper table to store this code and title with type
sex	This sheet have information related to the gender/sex specification 	In this sheet it is evident that M and F is used for male and female	A select option / a tuple can be used for storing this
Ethnicity	This sheet contains a code and ethnicity 	A drop down will be created from this information to store ethnicity of the learner	A proper table to store ethnicity and it’s code
Academic Year	Information about the academic session, start, end and year 	This details is to be submitted by the learner	A proper table to store session details, start date, end date and year
Disability	In this sheet disability status of a learner as well as if disability is yes then type of disability is mentioned	From this is it clear that learner will have to select the disability information and based of the selection (yes) in this case, learner will have to enter type of disability from the drop down	A proper table for store disability type. And select options to choose disability status of learner. A condition which check for ‘yes’


![image](https://user-images.githubusercontent.com/109203560/178671282-814f1397-df9f-4d5c-9e19-4b7870a15064.png)
