**CHAPTER 1:INTRODUCTION**
==========================

BACKGROUND
----------
A standard report is a manually designed report that presents data in a manually specified layout. it can be based either on report tables or SQL queries.
Currently in DHIS2 for one to create a standard report a series of steps are to be
followed:
	
-A report table must be created in DHIS2 with the indicators/data elements/datasets to be used in the report.

-You have to run the report table and download the design file (Click the "Download as JRXML" button).

-Open the downloaded .jrxml file using the free software Jasper iReport Designer to edit the layout of the report.

-The edited report can then be uploaded to DHIS2 to be used as a standard report.

A user is expected to have knowledge on jasper to be able to design how he/she would like to display their report and each time they want to view the report the design file has to be uploaded into DHIS2.

PROBLEM STATEMENT
-----------------
In the DHIS2 system, the existing functionality on designing a standard report is limited to technical knowledge on various technologies eg jasper or html reports hence the reports are not customizable and the user has less functionality of designing the report in terms of look and feel. 
This calls for development of a report designer application that will provide the user with an interface of designing customizable and highly configurable reports.

OBJECTIVES
----------
To develop an application which will help users to customize and configure their reports in a desired format.

PROPOSED SOLUTION
-----------------
To create a dynamic editor that will allow any user within dhis2 to create standard reports without neccesarily having to have any technical knowledge.