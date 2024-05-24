# My Developer Machine Setup

WinGet (Run from Any Prompt)

``` PowerShell
winget install "Git.Git" --silent
winget install "Chocolatey.Chocolatey" --silent
winget install "Microsoft.VisualStudio.2022.Enterprise" --silent
winget install "Microsoft.VisualStudioCode" --silent
winget install "Microsoft.DotNet.SDK.8 8.0.105" --silent
winget install "Microsoft.WindowsTerminal" --silent
winget install "Microsoft.PowerShell" --silent
winget install "JanDeDobbeleer.OhMyPosh" --silent
winget install "GoLang.Go" --silent
winget install "Microsoft.RemoteDesktop_8wekyb3d8bbwe" --silent
winget install "Discord.Discord" --silent
winget install "GoodGameMods.Minion" --silent
winget install "dotPDNLLC.paint.net_h55e3w7q8jbva" --silent
winget install "Valve.Steam" --silent
winget install "Microsoft.Teams" --silent
winget install "Microsoft.Office" --silent
winget install "Microsoft.OneDrive" --silent
winget install "Microsoft.YourPhone_8wekyb3d8bbwe" --silent
winget install "WinSCP" --silent
winget install "TIDALMusicAS.TIDAL" --silent
```

Chocolatey (Run from Admin)

``` PowerShell
choco install cascadiacode -y
choco install cascadia-code-nerd-font -y
choco install nerd-fonts-cascadiacode -y
choco install ludusavi -y
choco install occt -y
```

Terminal Icons

``` PowerShell
Install-Module -Name Terminal-Icons -Repository PSGallery
Import-Module -Name Terminal-Icons
```

ReadLines

``` PowerShell
Set-PSReadLineOption -PredictionSource History
Set-PSReadLineOption -PredictionViewStyle InlineView 
Set-PSReadLineOption -EditMode Windows
Set-PSReadLineOption -HistorySearchCursorMovesToEnd
Set-PSReadlineKeyHandler -Key UpArrow -Function HistorySearchBackward
Set-PSReadlineKeyHandler -Key DownArrow -Function HistorySearchForward
```

Oh My POSH

Segments:
https://ohmyposh.dev/docs/segments/git
https://ohmyposh.dev/docs/segments/az
https://ohmyposh.dev/docs/segments/kubectl
https://gist.github.com/shanselman/1f69b28bfcc4f7716e49eb5bb34d7b2c?WT.mc_id=-blog-scottha


