# Eii.GithubActions
A repo for CustomActions



## BuildCheckWindows
This is a custom action that builds the project using only the github-Official-EwE package source
It uses powershell (`pwsh`) to run the build script, and is designed to run on `windows-latest`.

## BuildCheckUbuntuBSR
This is a custom action that builds the project using both the github-Official-EwE and BSR package sources
It uses bash (`bash`) to run the build script, and is designed to run on `ubuntu-latest`.

## ReleaseNuGetPackageWindows
This is a custom action that creates a nuget package.
It uses powershell (`pwsh`) to run the build script, and is designed to run on `windows-latest`.

## ReleaseNuGetPackageNet80
THis is a custom action that creates a nuget package.
It uses bash (`bash`) to run the build script, and is designed to run on `ubuntu-latest`.


## Legacy

The other Github actions in this repo are legacy actions that are no longer maintained. As soon as the new actions are fully functional, these will be removed from the repo.