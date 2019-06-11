# Chocolatey

`choco feature enable -n=allowGlobalConfirmation`  
`choco install GoogleChrome speccy todobackup treesizefree vlc winrar pdfcreator adobereader goodsync notepadplusplus`

Manual:
Bitdefender

# Uninstall a file in Windows in safe mode

**if in safe mode**  
`REG ADD "HKLM\SYSTEM\CurrentControlSet\Control\SafeBoot\Minimal\MSIServer" /VE /T REG_SZ /F /D "Service"`  
`net start msiserver`

**if in safe mode with networking**  
`REG ADD "HKLM\SYSTEM\CurrentControlSet\Control\SafeBoot\Network\MSIServer" /VE /T REG_SZ /F /D "Service"`  
`net start msiserver`
