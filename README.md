# Eii.GithubActions
A repo for CustomActions



## BuildCheckWindows
This is a custom action that builds the project using only the github-Official-EwE package source
It uses powershell (`pwsh`) to run the build script, and is designed to run on `windows-latest`.

| Input | Description | Required | Default |
|---|---|---|---|
| `dotnet-version` | Version of .NET to use | No | `10.0.x` |
| `solution-file` | Solution file to build | No | `''` |
| `run-tests` | Set to `true` to run the unit tests of the solution after building | No | `false` |

## BuildCheckUbuntuBSR
This is a custom action that builds the project using both the github-Official-EwE and BSR package sources
It uses bash (`bash`) to run the build script, and is designed to run on `ubuntu-latest`.
It accepts the same inputs as `BuildCheckWindows` (`dotnet-version`, `solution-file`, `run-tests`).

## ReleaseNuGetPackageWindows
This is a custom action that creates a nuget package.
It uses powershell (`pwsh`) to run the build script, and is designed to run on `windows-latest`.

## ReleaseNuGetPackageNet80
THis is a custom action that creates a nuget package.
It uses bash (`bash`) to run the build script, and is designed to run on `ubuntu-latest`.


## Legacy

The other Github actions in this repo are legacy actions that are no longer maintained. As soon as the new actions are fully functional, these will be removed from the repo.