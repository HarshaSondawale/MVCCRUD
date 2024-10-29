# Web app with CRUD & REST operations with UI 
Created a sample employee management portal web app with CRUD & REST operations with UI using C#, MVC and ASP.net
This project interacts with the SQL Server Database using ADO.NET and performs all the basic CRUD operations. 


# Setup the Database:
This will create the Employee table with the corresponding fields with the following query

CREATE TABLE Employee(
	id int IDENTITY(1,1) NOT NULL,
	name varchar](100) NULL,
	age int NULL
)

#Change the connection String in Web.Config:
Replace the below query to the connection string used in local server

add name="EmpConnection" connectionString="Data Source=ServerName;Initial Catalog=DataBaseName;Integrated Security=True"
     providerName="System.Data.SqlClient" 

ServerName: Local Name of the server to be added

DataBaseName: Database name for which the script was executed

