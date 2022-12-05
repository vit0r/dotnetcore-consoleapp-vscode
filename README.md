# DOTNET 7

1. [doc](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-sln)
2. [debug](https://learn.microsoft.com/en-us/dotnet/core/tutorials/debugging-with-visual-studio-code?pivots=dotnet-7-0)

## Create project and sln

```console
dotnet new sln --name DotnetcoreConsoleAppVscode
cd DotnetcoreConsoleAppVscode
dotnet new console --framework net7.0
dotnet add reference DotnetcoreConsoleAppVscode/DotnetcoreConsoleAppVscode.csproj
```
