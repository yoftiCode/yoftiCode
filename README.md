used software for implementation
   1. SQLserver 2014 for data storage and store procedure
   2. python 3.8 for implementaion
   3. maltigo open source library for analysis and user interface design

steps to operate

1. unzip all folders
2. attach AMLProject.mdf file on sqlserver
3. unzip the tranform_master file 
4. open the file from tranform_master\transform\ataSource_Connector.py  check and customize your connection string( server = 'localhost'
        						     database = 'AMLProject'
                                               username = ''
                                               password = '') 

 
   note: if your SQL server window authentication mode no need to change the server name, database, username, and password
5. the project is already an executable file so just run OSINTS.bat file from the tranform_master folder
6. end of configration
