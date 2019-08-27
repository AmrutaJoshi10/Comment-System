# Comment-System

Developed a commenting system using ASP.NET MVC5.  
In this system you can create your comments, and reply for the specific comments.


# Install this project in your system

You will need Visual studio 2017.
Since we are using the Entity Framework you will not need any external database like MongoDB, SQL .
You will have to create your database by using following commands :
From the Tools menu, select NuGet Package Manager > Package Manager Console.
 Write these commands in the package manager console :
enable-migrations
add-migration InitialCreate
Similarly, if you want to update your DB you will have to write :
update-database
Each time you add any new entry in your database you will have to update your database.

To understand this project properly, you will have to see my previous project named CourseApp which is based on ASP.NET core MVC. 
