```
$WebClient=New-Object Net.WebClient
$Uri='https://github.com/git-for-windows/git/releases/download/v2.42.0.windows.2/PortableGit-2.42.0.2-64-bit.7z.exe'
$WebClient.DownloadFile($Uri, "$Home/downloads/PortableGit-2.42.0.2-64-bit.7z.exe")
```
