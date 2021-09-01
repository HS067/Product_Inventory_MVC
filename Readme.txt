

1. Open the Solution in Visual Studio
2. Build the project 
3. Navigate to tools ans select Nuget Package manager -> Package Manager Console (PMC)
4. On the console execute the following command

Add-Migration Anyname -Context Product_Inventory_MVCIdentityContext
 Update-Database  -Context Product_Inventory_MVCIdentityContext



5. On the console execute the following command
Add-Migration anyname -Context Product_Inventory_MVCContext

Update-Database  -Context Product_Inventory_MVCContext


