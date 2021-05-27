# BloodBank_Management_Application_Java

A console based app using OOPS, Core Java and Java Database Connectivity concepts. Provides options for donor registration, eligibility check, seeker demand check and staff member activities.

The project is made using Netbeans 8.2 IDE. The database used is Oracle XE 18.0. The project is developed and compiled using jdk 8.

Following tables have been used:-

Donor table - It contains the information of all registered donors.
Seeker table - It contains the information of all registered seekers
BloodInv table - It contains stock information of each blood group packet.
The src folder contains the source code. It contains 15 files:-

AddDonor.java - for Adding a donor ecord in the database
AddSeeker.java - for Adding a seeker ecord in the database
Client.java - the main user interface
Create_Inv.java - for Creating Blood Inventory table
CreateDonor.java - for Creating Donor table
CreateSeeker.java - for Creating Seeker table
Delete.java - for deleting a record from the database
Display.java - to display eligibility conditions for Blood Donation in India
Donor_Reg.java - for registering a new potential donor
GenerateUID.java - to generate unique identification number for donors and seekers
Inv_Init.java - to Initialize the Blood Inventory.
MedCheck.java - to verify medical details in order to identify eligible donors
Search.java - to search the Blood Inventory for requested blood packets
Seeker_Reg.java - for registering all seekers
Update - to Update details of donor/seeker
To run the code:-

Clone the github repo to your local machine
Extract the BloodBank.rar file
Open Netbeans IDE 8.2
Go to File > Open Project and go to the location where you have extracted your BloodBank.rar file and select BloodBank folder and select open.
First of all go to run and build the application. Then open CreateDonor.java and click on run and run this file. Repeat the same for CreateSeeker.java, Create_Inv.java and Inv_Init.java
Now, run the Client.java file.
NOTE:

The BLOOD BANK APP.pptx powerpoint presentation conatins useful information such as the class diagrams, use cases, database design and flow diagram.



