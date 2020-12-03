It is common to develop on macOS.

## Steps prepared to develop on macOS

1. install .net Core SDK 3.1+

   [click here to download SDK](https://dotnet.microsoft.com/download)

2. install dev app "Rider"

   [click here to download Rider](https://www.jetbrains.com/rider/)

3. install Avalonia Template

   `git clone https://github.com/AvaloniaUI/avalonia-dotnet-templates --recursive`
   
   `dotnet new --install [path-to-repository]`

4. install Rider plugin

   [repo](https://plugins.jetbrains.com/plugins/dev/14839)
   
   
   After above steps, you can open the Rider IDE to enjoy Avalonia!

## Another Question

 We can not input Chinese words into TextBox or it can not present properly.

 Just fix it by following code to set the font family of the textbox:

 `public const string FontFamily = "Microsoft YaHei,Simsun,苹方-简,宋体-简";`
