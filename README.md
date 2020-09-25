# Jonesing4SportsSln

This is a student demo based on Adam Freeman's PRO ASP.NET core 3 book.

***
***

# Chapter 7

### Create Solution and Projects;

    dotnet new globaljson --sdk-version 3.1.302 --output OutdoorProductsSln/OutdoorProducts
    dotnet new web --no-https --output OutdoorProductsSln/OutdoorProducts --framework netcoreapp3.1
    dotnet new sln -o OutdoorProductsSln
    dotnet sln OutdoorProductsSln add OutdoorProductsSln/OutdoorProducts 
    dotnet new xunit -o OutdoorProductsSln/OutdoorProducts.Tests --framework netcoreapp3.1
    dotnet sln OutdoorProductsSln add OutdoorProductsSln/OutdoorProducts.Tests 
    dotnet add OutdoorProductsSln/OutdoorProducts.Tests reference OutdoorProductsSln/OutdoorProducts


![SportsStore](https://github.com/JacobJones6154/Jonesing4SportsSln/blob/master/Clips/Sportsstore.PNG)


* What is Entity Framework?
    * Entity Framework is an object-relational mapper that is aimed at increasing developers productivity. Entity framework eliminates the need for most of the access code that developers need to write. 

* What is a Connection String?
    * A connection string provides the information that a provider need to communicate with a particular database. 

* What is a Database Context?
    * DbContext is a class provided by entity framework to establish connection to a database.

* What is a Model Repository?
    * The Model repository is a relational database that stores the metadata for projects and folders.

* Migration vs Scaffolding?
    * Migration is a way to keep the database schema in sync with the EF Core model by preserving data.  Scaffolding a database produces an Entity Framework model from an existing database
    
* Seeding the database

![Progressimage](https://github.com/JacobJones6154/Jonesing4SportsSln/blob/master/Clips/7-9.PNG)

***
***
***

# Chapter 8

**8-5**

![Progress](https://github.com/JacobJones6154/Jonesing4SportsSln/blob/master/Clips/8-5.PNG)

**8-10**

![Progress](https://github.com/JacobJones6154/Jonesing4SportsSln/blob/master/Clips/8-10.PNG)

**8-11**

![Progress](https://github.com/JacobJones6154/Jonesing4SportsSln/blob/master/Clips/8-11.PNG)

**TestCases**

![Progress](https://github.com/JacobJones6154/Jonesing4SportsSln/blob/master/Clips/TestCases.PNG)

***
***
***

# Chapter 9

**9-4**

![9-4](https://github.com/JacobJones6154/Jonesing4SportsSln/blob/master/Clips/9-4.PNG)

**9-5**

![9-5](https://github.com/JacobJones6154/Jonesing4SportsSln/blob/master/Clips/9-5.PNG)

**9-6**

![9-6](https://github.com/JacobJones6154/Jonesing4SportsSln/blob/master/Clips/9-6.PNG)

**TestCases**

![TestCases](https://github.com/JacobJones6154/Jonesing4SportsSln/blob/master/Clips/TestCasesCh9.PNG)


