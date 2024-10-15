# local-nuget
MSBuild target for publishing NuGet packages locally and automatically deleting cached copies.

### Prerequisites

* NuGet 4.0 or higher
* Projects must use the newer [SDK-style format](https://docs.microsoft.com/nuget/resources/check-project-format)
* The `dotnet` tool (part of the .NET SDK) must be on the PATH

### Instructions

Simply add this NuGet package reference to your .csproj file.

```xml
<PackageReference Include="LocalNuGet" Version="1.0.*" PrivateAssets="All" />
```
