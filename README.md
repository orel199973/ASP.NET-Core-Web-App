# BootCampProject (Week 3).

## Part I

## 1 - My project in ASP.NET-Core-Web-App.
 ![image](https://user-images.githubusercontent.com/47865329/135423364-a5d79c90-9fd5-4d61-a256-b202ccc45b9c.png)

## 2 - Add “Newtonsoft.Json”.
![image](https://user-images.githubusercontent.com/47865329/135424865-8cec0478-e387-4d5a-ab88-2488b0cb5a31.png)

## 3 - Checked csproj again, what changed.
![image](https://user-images.githubusercontent.com/47865329/135426408-cf7ca759-b464-4bd6-81d3-a4f8654d9b96.png)

## 4 - I did restore nugget packages.
## 5 - I have published your application.

## 6 - Indeed these are the files we received:
![image](https://user-images.githubusercontent.com/47865329/135427843-e91608c3-cd87-4e1a-a683-d409f477bd58.png)

## 7 - And when I run the app this is the result:
![image](https://user-images.githubusercontent.com/47865329/135428326-4547e9c8-139d-4834-8d17-e48b738d423c.png)


## Part II

* Enter to RDP in your computer 
* Add IIS Manager to your Windows server.
* Create new application pool by right-clicking Application Pools.
* For .NET 5 choose No Managed and Integrated.
* Create new website by right-clicking Sites.
* Give your site a name, press SELECT and choose the application pool that you created.
* On physical path insert: C:/inetpub/wwwroot.
* In wwwroot directory press Make New Folder and create a folder for your website.
* In Binding insert the port for your website (for example: 5100) and press OK.
* Right-click on your website and press Explore.
* Copy your publish folder (PART I) to the folder you created.
* Your website has been created so refresh it and browse on http://localhost:[your port].
* There is an ERROR (500.29).
* Download ASP.NET Core Hosting Bundle and install it on your windows server machine (https://dotnet.microsoft.com/download/dotnet/thank-you/runtime-aspnetcore-5.0.10-windows-* hosting-bundle-installer).
* Refresh your website and press Browse*:[your port](http).
