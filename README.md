# Terminal-Config
This project is my personal  terminal configuration PowerShell 7.5.4

## install Nerd Font
```powershell
Install-PSResource -Name NerdFonts
Import-Module -Name NerdFonts
```
- to install specific font. You can see all font here https://www.nerdfonts.com/font-downloads (Gohu)
```powershell
Install-NerdFont -Name # to specific font
```
- to install all Nerd Font
```powershell
Install-NerdFont -All
```
## Intsall Icons

```powershell
Install-Module -Name Terminal-Icons -Repository PSGallery
```
## Install OhMyPosh 
```powershell
winget install JanDeDobbeleer.OhMyPosh --source winget
```
- Edit your PowerShell profile script, you can find its location under the $PROFILE variable in your preferred PowerShell version. For example, using notepad:

```powershell
notepad $PROFILE
```
or vscode
```powershell
code $PROFILE
```
- add this into the $PROFILE file (en in ps1):
  add the code into config.ps1
