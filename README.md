java c
Response Sheet 
IFN554 Databases 
Semester 2 SEM5C 2024 
IFN 554 Assessment 2 
SQL 
Complete the following tasks and note your responses. Reminder – all snapshots must be clear and readable 
Task 1 [6 marks]In this task you are required to write an SQL script. that builds a database to match the relational model below. Your database should be named “Heavenly Department Store”.The SQL statements in the script. must be provided in the correct order.Heavenly Department Store relational model is as follows:Note: Primary keys are denoted by bold and underline and foreign keys are in italics · Supply (SupplierNr, ItemNr, QtyNr) · Use (ItemNr, DeptCode) · Item (ItemNr, ItemName, CountryMade)  Note: 1.1 ItemNr or Name both possible PK using ItemNr as preferred PK · Supplier (SupplierNr, SupplierName, FaxNr, SupplierCountry) Note: 1.1 SupplierNr or FaxNr or SupplierName are all possible PK using SupplierNr as preferred PK FOREIGN KEYS ·   Supply (SupplierNr) references Supplier (SupplierNr)·   Supply (ItemNr) references Item (ItemNr)·   Use (ItemNr) references Item (ItemNr)Other Constraints and Remarks ·   All primary and foreign key attributes that you use are strings (not text) comprising eight digits (8).·   INTEGER type must be used for QtyNr is mandatory and must be greater than 0.·   TEXT type must be used for all other attributes.·   SupplierName and ItemName must contain a value (you will need to add values to these attributes)(Insert snapshots of tables and values here) 
Task 2 [14 marks] 
We   have   provided   you with   the   Hotel   database   (Filename:   IFN554_5C_Hotels.sql   you   can   download   from Canvas) to be used with MySQL Workbench. You must use this database in MySQL Workbench to extract the necessary information as per the following query requirements.
Note: All tasks requiring SQL must provide as a screen snapshot of the execute SQL tab in MySQL Workbench that includes all sections. Snapshots must be readable o   SQL Query codeo   Result Grid (table, view, update, new information etc.). The teaching team must be able to see the successful execution of the codeo   Action Output resulto   Schemas (where necessary)
In your database - a booking commences at 2 pm (check in) and finishes at 10 am the following day (check out). Example: A booking for 3 nights is made on Tuesday 8th August with a check-in date of Thursday 10th August from 2pm and a check-out time of Sunday 13th August at 10 am. Write an SQL script for querying data for the following information. 2a. List the hotelNo which has 2 or more single rooms [2 marks] 
2a response Insert code and result snapshot here 
2b. How many different guests visited the Meriton Hotel? [2 marks] 
2b. response Insert code and result snapshot here 
2c. What is the total income from bookings for the Meriton Hotel?  [3 marks] 
2c. response Insert code and result snapshot here 
2d. List the guests’ names who have visited more than 2 times [3 marks] 
2d response Insert code and result snapshot here 
2e. For each hotel,   list the room type, for each room type list the number of each room type and the number with bookings [4 marks] 
2e. response Insert code and result snapshot here Task 3 [5 marks] – Individual 
Perform. the following tasks.
3a. 
Write a command to create an index on hotel nam代 写IFN554 Databases  Semester 2 SEM5C 2024SQL
代做程序编程语言e and show the results [1 mark] 
3a. response Insert code and result snapshot here 
3b. 
Create a user with the name ‘Mickey’ @ local host with password ‘iloveORM’ and force the user to update the password [01 mark].  
Show the results. [1 mark] 
3b. response Insert code and result snapshot here 
3c. Create a view called HotelSummaryView – list the hotelNo, type and price of each room. Order the result by hotelNo, room type and price [1 mark] 
3c. 
response Insert code and result snapshot here 
3d. Grant permissions to select and read this view . Show results[1 mark] 
3d. response Insert code and result snapshot here 
3e. Revoke permissions and show results [1 mark] 
3e. response Insert code and result snapshot here 
Task 4 [5 marks] 
Perform. the following tasks continue using the Hotel database provided.
4a. Update the prices of all single rooms by 5% and show results [1 mark] 
4a. response Insert code and result snapshot here 
4b. Insert 2 rows of new data in the table Guest and Booking [2 marks] 
4b. response Insert code and result snapshot here 
4c.  Delete one of the rows your inserted into the Guest table [2 marks] 
4c response (Insert snapshot here) 
Task 5 [10 marks]
Using the following table structure, identify all functional dependencies and then decompose this table into a set of 3NF relations. The table is in 0NF so please apply all rules accordingly.
Assumptions:·   Product Price is Per Unit·   There are not multi valuesOrder No Order Time (dd/mm/yyyy/hh:mm) Cust DOB (dd/mm/yyyy) Total (AUD$) Item # Order Prod Order Qty Customer No Customer Name Product No. Product Name Supplier Prod RRP (AUD$) Age 1 05/11/2023 15:00 01/11/1962 600 1 P4567 3 007 James Bond P4567 Wristwatch Seiko 200 62 23 05/12/2023 15:00 01/11/1950 360 1 T1245 1 024 Sean Connery T1245 Cufflinks Harrods 20 74 23 05/12/2023 15:00 01/11/1950 360 2 P1299 1 024 Sean Connery P1299 Tie Clip Harrods 120 74 23 05/12/2023 15:00 01/11/1950 360 3 T1304 1 024 Sean Connery T1304 Shoes Sketchers 220 74 
Insert response here All tables must be in 3NF. 
Task 6 [10 marks]The use of Generative AI such as ChatGPT is not permitted for this task. QUT policy states the following: “If you submit an assessment “that has been produced or modified, wholly or in part, by an artificial intelligence tool, algorithm, or computer generator where such actions are not authorised in the assessment task”, this may be treated as a breach of our Academic Integrity Policy and appropriate penalties imposed. This task is a reflective task. You are required to answer the question below in your own words. Your answer should be your opinions, experience and personal perspective. Your response should be supported by research to validate your viewpoints. Provide in text referencing where appropriate. Your response should be between 400 and 600 words not including references.Question:  How does the use of Electronic Health Records (EHRs) impact your privacy and confidentiality as a patient? What measures do you think modern EHealth should take to protect your information? How do you want your data managed?    What actions are taken or should be taken to ensure your data is protected and used in an appropriate and authorised manner? Insert response here



         
加QQ：99515681  WX：codinghelp
