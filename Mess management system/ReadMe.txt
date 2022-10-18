## Project
         
         The project name is Mess management system (With a unique name  BACHELORHUB) . 

##Tools used
     To develop this project , the following tools are used:
           =>Microsoft Visual Studio 2019 Community Edition
           =>Microsoft SQL Server 2014 Express
           =>Banifu Framework 1.11.5.1
           =>Microsoft Report Viewer

##Installation

       Use sql server query ,"BECHELOR_HUB_DB" to create database.
       After creating database ,replace the connection string from appconfig.
 
       select 'Data Connection ' from solution explorer of the project visual studio
       and go to properties.    
    Then copy the full path of Connection server   amd replace inside the ConnectionStrins class
   => <connectionStrings>
		<add name=" @paste your full path here  " providerName=" @write provider name  "/>
	</connectionStrings> 



##Initial Login 
  
 For the initial log in for admin ,
            * Username: ADMIN
            *Password: admin

also a another  username & password already insert in sql server with 
the name Homeowner table( Username: HomeOwner  Password:home)
After a sucessful login both user can access each and everything inside the
project we made.

 

##Function 

1.login
2.Register 
3. Admin
4. Find home
5. Addroom
6. Bachelor Detail 
7. Homeowner

##Feature 

1.longin by role(Admin,Homeowner,Bachelor)
2.Registered by Bachelor
3. Add room by admin
4. Find home by admin
5. Show bachelor details.
6.login as homeowner  abn Add room by homeowner
7. Homeowner can shoe Bachelor details.
8. Bachelor can login in as bachelor and find home.
9. Bachelor's are also saw the register bachlor details
       
       
       