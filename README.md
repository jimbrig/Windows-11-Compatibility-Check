# Windows 11 Compatibility Check

![GitHub repo size](https://img.shields.io/github/repo-size/niklasrast/Windows-11-Compatibility-Check)

![GitHub issues](https://img.shields.io/github/issues-raw/niklasrast/Windows-11-Compatibility-Check)

![GitHub last commit](https://img.shields.io/github/last-commit/niklasrast/Windows-11-Compatibility-Check)

This repo contains an powershell scripts to check the compatibility from your device to run Windows 11. The result will be send to your Microsoft Teams Channel so you have to create an Webhook in your Team an add the Webhook URL in the script

## Run Script:
```powershell
PowerShell.exe -ExecutionPolicy Bypass -Command .\Get-Windows-Readiness.ps1 -TeamsChannelUrl "https://your-teams-channel.com/webhook-url"
```
The parameter TeamsChannelUrl is not mandatory to use the script. The external file processors.csv contains a list of supported processors for windows 11.
 
## Requirements:
- PowerShell 5.0
- Windows 10
- (optional) Microsoft Teams

# Feature requests
If you have an idea for a new feature in this repo, send me an issue with the subject Feature request and write your suggestion in the text. I will then check the feature and implement it if necessary.

Created by @niklasrast 