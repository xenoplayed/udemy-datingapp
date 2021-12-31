# udemy-datingapp

Build an app with ASPNET Core and Angular from scratch
A practical example of how to build an application with ASP.NET Core API and Angular from start to finish 

URL: https://www.udemy.com/course/build-an-app-with-aspnet-core-and-angular-from-scratch/

## useful CLI commands 
### dotnet commands
`dotnet --info`

`dotnet new -h`

`dotnet new webapi -h`

`dotnet new webapi -n projectname`

`dotnet watch run`

`dotnet tool install --global dotnet-ef`

`dotnet ef -h`

`dotnet ef migrations -h`

`dotnet ef migrations add InitialCreate -o Data/Migrations`

`dotnet ef database update`

`dotnet user-secrets set "AppSettings:Token" "super secret key"`

`dotnet user-secrets list`


### angular commands
`ng new projectname`

`ng serve`

`ng g guard auth --skipTests`

### git commands
`git rev-parse --show-toplevel`

`git rm file_to_remove.json`

`git rm file_to_remove.json --cached`

Shows the changes between the Working Directory and the Staging Area

    git diff

Shows the changes between the Staging Area and the HEAD

    git diff --staged
    - or -
    git diff --cached
    - or -
    git status -v



### postman commands
To display an HTML-formatted response, set the Accept HTTP request header to the text/html media type. For example:
`curl -i -H "Accept: text/html" https://localhost:5001/weatherforecast/chicago`


## Useful web tools
https://randomuser.me/

https://www.json-generator.com/

https://jwt.io/


## Downloads
https://dotnet.microsoft.com/download/dotnet-core

https://nodejs.org/en/

https://www.postman.com/downloads/

https://docs.microsoft.com/en-us/powershell/scripting/components/vscode/using-vscode?view=powershell-7

https://sqlitebrowser.org/dl/

## Extensions

### VS Code Addons for .NET
https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp

https://marketplace.visualstudio.com/items?itemName=kreativ-software.csharpextensions

https://marketplace.visualstudio.com/items?itemName=jmrog.vscode-nuget-package-manager

### VS Code Addons for Angular
https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2

https://marketplace.visualstudio.com/items?itemName=alexiv.vscode-angular2-files

https://marketplace.visualstudio.com/items?itemName=Angular.ng-template

https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag

https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2

https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme

https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode

https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-tslint-plugin

https://marketplace.visualstudio.com/items?itemName=infinity1207.angular2-switcher

https://marketplace.visualstudio.com/items?itemName=RedVanWorkshop.explorer-exclude-vscode-extension

## Links
https://code.visualstudio.com/docs/remote/containers

https://github.com/Microsoft/vscode-remote-try-dotnetcore (Container with .NET (including https) and Node)