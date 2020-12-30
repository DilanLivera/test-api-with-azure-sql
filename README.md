#### How to create an Azure SQL Database
1. Goto `Create Resource -> SQL Database`
2. Create a `Resource Group`
3. Create a `Database name`
4. Create a `New Server`
    - `Server Name` - Set to the `Database name`
    - `Server admin login` - Eg. azuresql
    - Create a password and select a location
5. Set `Want to use SQL elastic pool?` to `No`
6. Set `Compute + storage` to `General purpose`
7. In `Networking` tab
    - Set `Connectivity method` to `Public endpoint`
    - Set `Allow Azure services and resources to access this server` to `Yes`
    - Set `Add current client IP address` to `Yes`
8. In `Review + create` tab, Select `Create`, and wait for the server and database to be created before you continue.

#### Links
- [Develop and configure an ASP.NET application that queries an Azure SQL database](https://docs.microsoft.com/en-us/learn/modules/develop-app-that-queries-azure-sql/)
- [Deploy an ASP.NET Core App with EF Core and SQL Server to Azure](https://medium.com/net-core/deploy-an-asp-net-core-app-with-ef-core-and-sql-server-to-azure-e11df41a4804)