# Facebook-integration
Sign in with facebook integration

SQL 

Give Connection string :  <add name="DefaultConnection" connectionString="Data Source=localhost;Initial Catalog=DemoDB; Trusted_Connection=true; Integrated Security=True" providerName="System.Data.SqlClient" /> 

IIS config : Create website give name,binding,project path
IIS -> Application Pools -> ProjectName (LoginIntegration) -> rightclick -> advance setting -> Identity change into LocalSystem

Host website Name : Goto this path C:\Windows\System32\drivers\etc => In hosts file add follwing line (Ipaddress www.loginintegration.com)-> save



In visualStudio select roject -> properties - > web ->servers ( Local IIS) SET project URL http://www.loginintegration.com/
