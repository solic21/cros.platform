# EbolaAPI's SQL Server Database Provider

This project contains EbolaAPI's Microsoft SQL Server database provider.

## Migrations

Add a migration with:

```
dotnet ef migrations add MigrationName --context SqlServerContext --output-dir Migrations --startup-project ..\EbolaAPI\EbolaAPI.csproj

dotnet ef database update --context SqlServerContext
```
