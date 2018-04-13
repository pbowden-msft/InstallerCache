# InstallerCache
<b>Microsoft Office Installer Cache</b>

Purpose: Downloads Office installer packages from the Office CDN to a shared folder<br/>
Usage: `InstallerCache --CachePath:<path> [--CheckInterval:<minutes>] [--PurgeOldInstallers]`<br/>
Example: `InstallerCache --CachePath:/Volumes/web --CheckInterval:60`<br/>
  
The shared folder path needs to be exposed as a web folder, such as http://webserver/folder<br/>
Clients can install packages by navigating to a URL, such as http://webserver/folder/InstallWord<br/>
Web install points created by the tool:</br>
 - /InstallMAU
 - /InstallOffice
 - /InstallWord
 - /InstallExcel
 - /InstallPowerPoint
 - /InstallOutlook
 - /InstallOneNote
 - /InstallOneDrive
 - /InstallSkypeBusiness
 - /InstallCompanyPortal
 - /InstallRemoteDesktop
