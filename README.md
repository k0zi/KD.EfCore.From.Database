[![CI]](https://github.com/k0zi/KD.EfCore.From.Database/actions/workflows/ci.yml)
[![NuGet]](https://www.nuget.org/packages/KD.EfCore.From.Database/)

### What is this?

This is a simple tool that generates C# code from a database schema. It uses the [Entity Framework Core](https://docs.microsoft.com/en-us/ef/core/) and the ErikEJ's [EF Core Power Tools](https://github.com/ErikEJ/EFCorePowerTools) to generate the code. The Sql template is based on [Microsoft's DacFx](https://github.com/microsoft/DacFx/tree/main/src/Microsoft.Build.Sql.Templates) template.

### How to install?

Simply use the dotnet new command to install the template. The template is available on [NuGet](https://www.nuget.org/packages/KD.EfCore.From.Database/).

```dotnet new install KD.EfCore.From.Database```

### How to use it?

Just create sql objects, import database into the project and build it. After build, the C# project and code will be generated (and added to the solution if it's not already there).

You can create your project in command line, with the following command:

```dotnet new autodbef --name MyProject```