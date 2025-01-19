# QOA-blazor

Blazor GUI for QOA ([Quite OK Audio Format](https://qoaformat.org/)) encoding/decoding that you can run in your browser

## Web link

[qoa-blazor.raiha.rocks](https://qoa-blazor.raiha.rocks/)

## Requirements (end user)

You have to have newish [internet browser](https://docs.microsoft.com/en-us/aspnet/core/blazor/supported-platforms?view=aspnetcore-9.0)

## How to run / develop

### Requirements

You have to have [.NET 9 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/9.0) installed,

### Actual run

Run
```
cd src
dotnet run
```
  
And then you can open http://localhost:5117 in your browser

## How to publish

### Requirements

You have to have **wasm-tools** workload installed, before you you can do publish. You can install it with following command
```
dotnet workload install wasm-tools
```

### Actual publish

Run
```
cd src
dotnet publish -c Release
```
  
and content should be in **src\bin\Release\net9.0\publish\wwwroot** folder.

## Licenses

All code files (*.cs, *.razor) and HTML files (*.html) are under [MIT](https://opensource.org/licenses/MIT) license, because QOA and [MVP.css](https://github.com/andybrewer/mvp/) use that license

Icon file is modified emoji from [Twitter Emoji](https://github.com/jdecked/twemoji) (Twemoji) project. Their license is also [MIT](https://github.com/jdecked/twemoji/blob/main/LICENSE)