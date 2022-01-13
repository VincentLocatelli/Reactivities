dotnet tool list --global liste les tools dotnet installer
dotnet tool install --global dotnet-ef --version 6.0.1 nugget gallery
dotnet ef migrations add InitialCreate -p Persistence -s API

-p Where finds DbContext
-s Startup project

dotnet ef migrations add InitialCreate -p Persistence -s API --context DataContext