---
title: Framework Versions Support
page_title: .NET Framework Versions Support
description: List of the supported .NET Core framework versions and the UI for Blazor versions that work on them.
slug: framework-versions-support
tags: framework,version,support,list
published: True
position: 5
---

# Framework Versions Support

This article lists the .NET Core versions supported by the UI for Blazor suite, and which versions of the Telerik UI for Blazor work under which framework versions.

>note Telerik supports only the latest available version of UI for Blazor (**{{site.uiForBlazorLatestVersion}}**).

Telerik UI for Blazor targets `netstandard2.1`. Thus, apps/libraries that reference our package must target `netstandard2.1`, `netcoreapp3.1` or `net5.0`. Razor Class Libraries may target `netstandard2.0` by default so you would need to update that.



## .NET 5

Telerik UI for Blazor supports .NET 5 since its `2.19.0` release.

| .NET 5     | Telerik UI for Blazor version                          |
|------------|--------------------------------------------------------|
| .NET 5 RTM | 2.19.0 - {{site.uiForBlazorLatestVersion}}             |




## .NET Core 3.1

### Server-side Blazor

>caption Telerik UI for Blazor versions per framework version for the server-side flavor


| .NET version              | Telerik UI for Blazor version |
|---------------------------|-------------------------------|
| .NET Core 3.1.x           | 2.5.0 - {{site.uiForBlazorLatestVersion}}                 |
| .NET Core 3.1 preview 3   | 2.4.0                         |
| .NET Core 3.1 preview 2   | 2.3.0                         |
| .NET Core 3.1 preview 1   | 2.2.0, 2.2.1                  |
| .NET Core 3.0 RTM         | 2.1.0, 2.1.1                  |


### Client-side Blazor

The client-side (WebAssembly) flavor of Blazor is a set of separate NuGet packages whose version may not match the .NET Core version they run on.

>caption Telerik UI for Blazor versions per WebAssembly packages version

| WebAssembly version                  | Telerik UI for Blazor version      |
|--------------------------------------|-------------------------------     |
| 3.2.x RTM                            | 2.14.0 - {{site.uiForBlazorLatestVersion}}  |



>caption Telerik UI for Blazor versions per WebAsembly Preview version

| WASM Preview version                 | Telerik UI for Blazor version |
|--------------------------------------|-------------------------------|
| 3.2 RC1 (3.2.0-rc1.20223.4)          | 2.12.0 - 2.13.0               |
| 3.2 preview 4 (3.2.0-preview4.20210.8)         | 2.11.0              |
| 3.2 preview 3 (3.2.0-preview3.20168.3)         | 2.10.0              |
| 3.2 preview 2 (3.2.0-preview2.20160.5)         | 2.9.0               |
| 3.2 preview 1 (3.2.0-preview1.20073.1)         | 2.7.0 - 2.8.0       |
| preview 4 (3.1.0-preview4.19579.2)   | 2.5.0 - 2.6.1                 |
| preview 3 (3.1.0-preview3.19555.2)   | 2.4.0                         |
| preview 2 (3.1.0-preview2.19528.8)   | 2.3.0                         |
| preview 1 (3.1.0-preview1.19506.1)   | 2.2.0, 2.2.1                  |



## See Also

  * [Old Versions Support Policy]({%slug old_versions_support_policy%})
