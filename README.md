[![CI/CD]](https://github.com/k0zi/KD.EfCore.From.Database/actions/workflows/cicd.yml)

### What is this?

This is a simple tool that generates C# code from a database schema. It uses the [Entity Framework Core](https://docs.microsoft.com/en-us/ef/core/) and the ErikEJ's [EF Core Power Tools](https://github.com/ErikEJ/EFCorePowerTools) to generate the code.

### How to install?

```
dotnet new install KD.EfCore.From.Database
```

### How to use it?

Just create sql objects, import database into the project and build it. After build, the C# project and code will be generated.