# reading-notes-401


## Reading 14

ASP.NET routing is an important feature. The ASP.NET routing module is responsible for mapping incoming browser requests to particular MVC controller actions.

When the application starts the Application_Start() method is called which then calls the RegisterRoutes() method. This method then creates the route table. 
The default route will be controll=Home, action=index, id=3.

When no controller is supplied then it will default to Home.

The home controller class includes a method named Index that accepts a single parameter named id. Basically all of this is just ASP.NET's way of allowing you to use CRUD operations with routes.

[Table Of Contents](README.md)