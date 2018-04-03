# Powershell Music Player
Invoke-MusicPlayer automates Windows Media Player, to play songs in Background with a set of user preferences available as a 'switch' in the cmdlet.

## Features and Benefits
*  Plays all audio in background on a hidden Media player instance
    <img src="https://raw.githubusercontent.com/PrateekKumarSingh/MusicPlayer/master/media/default.jpg">

*  Filter Audio Files
    <img src="https://raw.githubusercontent.com/PrateekKumarSingh/MusicPlayer/master/media/filter.jpg">

*  Randomly shuffles your play list
    <img src="https://raw.githubusercontent.com/PrateekKumarSingh/MusicPlayer/master/media/shuffle.jpg">

*  Runs your playlist in a never ending loop
    <img src="https://raw.githubusercontent.com/PrateekKumarSingh/MusicPlayer/master/media/shuffleandloop.jpg">

*  Stop the playing audio on demand
    <img src="https://raw.githubusercontent.com/PrateekKumarSingh/MusicPlayer/master/media/stop.jpg">

*  Stores\Caches last accessed directory
    <img src="https://raw.githubusercontent.com/PrateekKumarSingh/MusicPlayer/master/media/cached.jpg">

*  Displays information and user preferences
    <img src="https://raw.githubusercontent.com/PrateekKumarSingh/MusicPlayer/master/media/output.jpg">

*  Popup a balloon notification in bottom Right corner of the screen, whenever a new song starts playing and continues to do that until manually stopped or it completes playing all songs.
    <img src="https://raw.githubusercontent.com/PrateekKumarSingh/MusicPlayer/master/media/stop.jpg">

*  Support Switch aliases
    <img src="https://raw.githubusercontent.com/PrateekKumarSingh/MusicPlayer/master/media/switchalias.jpg">


 Installation
 -
 #### [PowerShell V5](https://www.microsoft.com/en-us/download/details.aspx?id=50395) and Later
 You can install the `MusicPlayer` module directly from the PowerShell Gallery

 * [Recommended] Install to your personal PowerShell Modules folder
 ```PowerShell
 Install-Module MusicPlayer -scope CurrentUser
 ```

 <img src="https://raw.githubusercontent.com/PrateekKumarSingh/MusicPlayer/master/media/Installation_v5.jpg">

 * [Requires Elevation] Install for Everyone (computer PowerShell Modules folder)
 ```PowerShell
 Install-Module MusicPlayer
 ```

 #### PowerShell V4 and Earlier
 To install to your personal modules folder run:

 ```PowerShell
 iex (new-object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/PrateekKumarSingh/MusicPlayer/master/Install.ps1')
 ```

Help Information
-
Run below commands to see some examples
```PowerShell
Get-Help Set-GridLayout -Examples
```
