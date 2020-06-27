# DAP-Group-Project

*****************************************************************
                                Read_Me file for DAP                     
*****************************************************************
 
  #-----------------------------------------------------------#  
Title : \
DAP(Davids Automotive Parts) info\
Authors : \
Jonathan Roddy\
Dylan Cummins\
Tomas Bunevicius\
Alex Ipsalat\
  #-----------------------------------------------------------#  
 
 
 
+   DESCRIPTION                                                  
This file is to help anyone who would like to log into DAP
project.

-User type and their log ins.

	Type : Manager
	UserID : Emp001 (set as default on login)
	password : password

	Type : Superviors 
	UserID : Emp003 
	password : password

	Type : Operator
	UserID : Emp00100 
	password : password

-If you would like to use the installer we have included, it will
 only work if installing onto the colleges network as the database's
 connection string is hardcorded.

	Todo : copy the contents on the folder "College" onto your 
	desktop and run the 'setup' icon.

-If running the dacbac you may need to change the database connection
 string in the code. 

	Todo: open 'Database.cs' in DataLayer and go to 
	'connection methods'.

	You will need to change connecting to the database under 
	'WindowsClientExperimental'->'App.config' under the heading,
	<!-- This is the writing to databse appender--> .
	Add your new <connectionstring value= 
and your good to go!
