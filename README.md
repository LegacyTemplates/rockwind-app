# rockwind-app

[![](https://raw.githubusercontent.com/ServiceStack/Assets/master/csharp-templates/rockwind-app.png)](http://rockwind-app.web-templates.io/)

> Browse [source code](https://github.com/NetCoreTemplates/rockwind-app), view live demo [rockwind-app.web-templates.io](http://rockwind-app.web-templates.io) and install with [dotnet-new](https://docs.servicestack.net/dotnet-new):

## Install

Run as a .NET Core Web App (Windows, macOS, Linux):

    $ dotnet tool install -g x

    $ x new LegacyTemplates/rockwind-app ProjectName
    $ cd ProjectName
    $ x

> To run in VS Code type `Ctrl+Shift+B` to run the configured `build` task.

Run as a Desktop App (Windows only):

    $ dotnet tool install -g x

    $ app LegacyTemplates/rockwind-app ProjectName
    $ cd ProjectName
    $ app

> Requires [.NET 5.0](https://dotnet.microsoft.com/download/).

## Learn

The [/support/northwind-data](https://github.com/ServiceStack/dotnet-app/tree/master/src/support/northwind-data) project lets you quickly try out Rockwind against your local RDBMS by populating it with a copy of the Northwind database using the same sqlserver identifier and connection string from the App, e.g:

    $ dotnet run sqlserver "Server=localhost;Database=northwind;User Id=test;Password=test;"

See [https://sharpscript.net/docs/sharp-apps](https://sharpscript.net/docs/sharp-apps) to learn about ServiceStack Sharp Apps.
