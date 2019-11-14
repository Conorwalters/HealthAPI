# HealthAPI


This is my first .netCore WebAPI

TOOLS:
To install all tools needed to build and run this project please run the following commands

>dotnet tool install --global dotnet-ef --version 3.0.0-*
dotnet tool install -g dotnet-aspnet-codegenerator


To build the SQL Database run the following commands:

### In root folder run:
>- docker-compose up -d
>- database-ef database update
>- dotnet watch run


To log-in to SQL Database use

Database=sql-serve
UID= sa
Password: SqlExpress!
