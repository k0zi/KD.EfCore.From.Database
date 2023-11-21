### How to install?

Simply use the dotnet new command to install the template. The template is available on [NuGet](https://www.nuget.org/packages/KD.EfCore.From.Database/).

```dotnet new install KD.EfCore.From.Database```

### How to use it?

Just create sql objects, import database into the project and build it. After build, the C# project and code will be generated (and added to the solution if it's not already there).

You can create your project in command line, with the following command:

```dotnet new autodbef --name MyProject```