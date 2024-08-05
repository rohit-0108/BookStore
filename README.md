# YtBookStore

Now upgraded to .net 8.0

# How to run it
1. clone the project
2. open `appsettings.json` file and update connection string's `data source=your server name`
   
   ``` "ConnectionStrings": { "conn": "data source=your server name;initial catalog=BookStore;integrated security=true;encrypt=false" }```
4. Delete `Migrations` folder
5. Open Tools > Package Manager > Package manager console
6. Run these 2 commands
    ```
     (i) add-migration init
     (ii) update-database
     ````
7. Now you can run this project
   
