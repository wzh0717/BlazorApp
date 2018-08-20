# BlzaorApp
asp.net in webAssembly

1、WebAssembly是什么？
WebAssembly 是一种能把除了JavaScript以外的编程语言编写的代码经过编译器编译转换为能在现代浏览器中运行的代码的技术。
众所周知，JavaScript在 Web 中的地位一直独步天下，无 yan 能敌，所以WebAssembly所指的性能优势，是针对 JavaScript 而言的。
WebAssembly并不是为了替代 JavaScript 出现的，而是希望与 JavaScript 并驾齐驱共同开发出性能更高的应用。

入门介绍： https://blog.csdn.net/frank_yll/article/details/79661285

2、Blazor？
Blazor 是一个 Web UI 框架，可通过 WebAssembly 在任意浏览器中运行.Net代码 。也就说，你可以用C# 写前端。可以理解为，这是一个C#语言的Vue, Angular, React等。
Blazor 拥有现代 Web 框架具备的所有功能，包括：

    用于构建 composable UI 的组件模型
    路由
    布局
    表格和验证
    依赖注入
    JavaScript 互操作
    开发期间在浏览器中实时重新加载
    服务器端渲染
    在浏览器和 IDE 中全面调试 .NET
    能够通过 asm.js 在较早版本的（非 WebAssembly ）浏览器上运行

Blazor GitHub 地址：https://github.com/aspnet/blazor
Blazor 文档地址： https://blazor.net/

开发环境
   安装 .NET Core 2.1 SDK 或更高版本
   安装 Visual Studio 2017 15.7 或更高版本
   安装最新的 Blazor Language Services extension
   

 3、VS2017 创建项目 
 参考文案：
    https://www.jianshu.com/p/8add0c628ff3
    https://www.cnblogs.com/Gerryz/p/get-start-with-dotnet-blazor.html
 
 4、命令行创建项目
    dotnet new -i Microsoft.AspNetCore.Blazor.Templates
    dotnet new blazor -o BlazorApp
    cd BlazorApp
    dotnet run
  

