# Advance-excel-project

Sport Data Analysis

Objective:
We are a part of XYZ Co Pvt Ltd company who is in the business of organizing the sports events at international level. Countries nominate sportsmen from different departments and our team has been given the responsibility to systematize the membership roster and generate different reports as per business requirements.

Dataset:
We are given data that are present in 3 sheets with the name -

Sportsmen: It contains information about sportsmen member id, full name, birthdate, gender, country code, country name, email, salary, blood group, sport location , weight, etc.
Sport: It contains information about type of sport and sport location.
Location: It contains information about country code,country name and language of sportsmen.
Tools Used:
Excel

Summary:
This project is done in three stages:

Data Cleaning: Data cleansing is performed by using excel functions. For example we created a new column with the name of full name from 3 existing columns prefix, firstname and lastname, got the COUNTRY NAME to which these sportsmen belongs to by making use of location sheet, populated the LANGUAGE spoken by the sportsmen by making use of location sheet, generated the EMAIL ADDRESS for those members, who speak English, in the prescribed format : lastname.firstname@xyz.org (Note: All lowercase) and for all other members, format was the lastname.firstname@xyz.com (Note: All lowercase).
Then some data formatting is performed. Example- formatted the BIRTHDATE as dd mmm' yyyy (Prescribed format example: 09 May' 1986), formatted the SALARY to show the data in thousands. If SALARY is less than 100,000 then display data with 2 decimal places else display data with one decimal place. In both cases units should be thousands (k).

Data Analysis: Data is analyzed by using pivot table and excel functions.

Generate Report: A report is created as per the business requirements.
