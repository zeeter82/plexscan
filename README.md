**zeeter82**  
**powershell_plexscan.reg**  
<br />

This reg file can be used for right click shell options in Windows for scanning Plex content into  
their respective libraries.  It takes advantage of PowerShell and [Plex's URL command options][2].  
This seems to be a lot more stable and consistent than using the normal 'Plex Media Scanner.exe'  
command line options.  
<br />

This is a sample reg file and needs to be configured for your setup/environment before merging.  
<br />

- Please update the [Plex-Token][1] with your unique token. Replace `aaabbbccc111222333` with your own  
- Please update the text for how you would like the right click options to appear  
- Please update the sections with your correct library ID's  

[1]: https://support.plex.tv/articles/204059436-finding-an-authentication-token-x-plex-token/
[2]: https://support.plex.tv/articles/201638786-plex-media-server-url-commands/
