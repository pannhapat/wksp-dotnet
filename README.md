# wksp-dotnet
asp.net c# .net

## Visual Studio Code 
## ASP.NET 6.0
## 

In Visual Studio Code, select File > Open Folder.

Create a new folder named <ProjectName> in the location of your choice, and then click Select Folder.

Open the integrated terminal from Visual Studio Code by selecting View > Terminal from the main menu.

In the terminal window, copy and paste the following command:

>  dotnet new webapi -f net6.0

Web API projects are secured with https by default. If you have problems, configure the ASP.NET Core HTTPS development certificate.

> dotnet dev-certs https --trust
