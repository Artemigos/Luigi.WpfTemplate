# Luigi.WpfTemplate

VSCode-debuggable WPF project template.

[NuGet package](https://www.nuget.org/packages/Luigi.WpfTemplate)

## How to use

Prerequisites:

- .NET Core 2.0 SDK
- .NET Framework 4.6.2
- C# extension in VS Code
- MSBuild 15.0 available in the `PATH` environment variable

From command line install the template:

```cmd
dotnet new -i Luigi.WpfTemplate
```

Then create a project:

```cmd
dotnet new wpf -o MyWpfProject
```

Open it in VS Code:

```cmd
code MyWpfProject
```

Run the project in VS Code by pressing F5. Voila, you're debugging a WPF application inside VS Code!

## But it's not working :(

Make sure you have all the prerequisites above. If it's still not working create an issue and detail the problem as well as possible - I can try to help.

## Using with full Visual Studio

Long story short... don't. The csproj file is tailored to work with VS Code and unfortunately things that are convinient for it don't work with Visual Studio all that well.
