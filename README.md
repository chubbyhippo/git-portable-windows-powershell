```powershell
$WebClient=New-Object Net.WebClient
$Uri='https://github.com/git-for-windows/git/releases/download/v2.47.1.windows.2/PortableGit-2.47.1.2-64-bit.7z.exe'
$WebClient.DownloadFile($Uri, "$Home/downloads/PortableGit.exe")
```
