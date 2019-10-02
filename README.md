
# Bobbybots
*by Bobby Digital Studios*

Backend assignment: Create a web API server for some super duper mega special robots.

### Instructions

The app is a http api server and should use [.NET-Core](https://docs.microsoft.com/en-us/dotnet/core/) as a framework with [Entity Framework Core](https://docs.microsoft.com/en-us/ef/core/) as ORM.

Any SQL-based database could be used, but we suggest SQLite for portability

Fork this repository. When you're done, send us a link to your fork.

#### Functionality
* On application start, if the database is empty seed it with the JSON data from the URL provided.
* Create a controller to Create, Read, Update and Delete bots.
* Create queries to do a case insensitive seach by name.
* By quering you should be able to 
  * sort the result by `name` or `score`, favourites should always be in the begining of the result.
  * filter by categories
