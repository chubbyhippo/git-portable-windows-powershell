```
$WebClient=New-Object Net.WebClient
$Uri='https://raw.githubusercontent.com/chubbyhippo/ahk/master/CapsToChangeInputLanguage.ahk'
$WebClient.DownloadFile($Uri, "$Home\downloads\CapsToChangeInputLanguage.ahk")
```
