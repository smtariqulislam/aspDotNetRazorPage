## How to I do this project?
# Steps to Create the Project

1. **Select Project**  
   First, select **ASP.NET Razor Page** and create a new project.  
   
2. **Next Step**  
   Then, click **Next**.  

3. **Install NuGet Packages**  
   Install the following NuGet packages:  
   - `Microsoft.EntityFrameworkCore`  
   - `Microsoft.EntityFrameworkCore.SqlServer`  
   - `Microsoft.EntityFrameworkCore.Tools`
   - `bootstrap` 
 
4. **Create Model**  
   Create a model to represent your data.  

5. **Add Connection String**  
   Add a connection string in the `appsettings.json` file.  

6. **Configure Program.cs**  
   In the `Program.cs` file, add services for the database context.  

7. **Run Commands**  
   Run the following commands: tools option(NuGet package manager -> package manager console) 
   - `add-migration "Init"`  
   - `update-database`  

9. **Create Razor Files**  
   Create Razor files and write Razor HTML with Bootstrap.  

10. **Use `_Layout.cshtml`**  
    In the `Shared` folder, use `_Layout.cshtml` for routes.



