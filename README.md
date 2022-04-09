# web.components
A collection of general web components provided as a NuGet package.

## Updating the package repository

- The GITHUB_TOKEN environment variable is required to update the package repository.
- Remember to update the version

```
dotnet nuget push "Solarisin.Web.Components/bin/Release/Solarisin.Web.Components.6.0.0-alpha.nupkg" --api-key %GITHUB_TOKEN% --source "github"
```