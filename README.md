# rockwind-webapp

[![](https://raw.githubusercontent.com/ServiceStack/Assets/master/csharp-templates/rockwind-webapp.png)](http://rockwind-webapp.web-templates.io/)

> Browse [source code](https://github.com/NetCoreTemplates/rockwind-webapp), view live demo [rockwind-webapp.web-templates.io](http://rockwind-webapp.web-templates.io) and install with [dotnet-new](http://docs.servicestack.net/dotnet-new):

## Install

Run as a .NET Core Web App (Windows, macOS, Linux):

    $ npm install -g @servicestack/cli
    $ dotnet tool install -g web

    $ dotnet-new rockwind-webapp ProjectName
    $ cd ProjectName
    $ web

> To run in VS Code type `Ctrl+Shift+B` to run the configured `build` task.

Run as a Desktop App (Windows only):

    $ npm install -g @servicestack/cli
    $ dotnet tool install -g app

    $ dotnet-new rockwind-webapp ProjectName
    $ cd ProjectName
    $ app

> Requires [.NET Core 2.1](https://www.microsoft.com/net/download/dotnet-core/2.1).

## Learn

The [/support/northwind-data](https://github.com/NetCoreWebApps/WebApp/tree/master/src/support/northwind-data) project lets you quickly try out Rockwind against your local RDBMS by populating it with a copy of the Northwind database using the same sqlserver identifier and connection string from the App, e.g:

    $ dotnet run sqlserver "Server=localhost;Database=northwind;User Id=test;Password=test;"

See [templates.servicestack.net/docs/web-apps](http://templates.servicestack.net/docs/web-apps) to learn about ServiceStack .NET Core 2.1 Web Apps.
