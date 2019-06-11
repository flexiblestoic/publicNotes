# Chocolatey

`choco feature enable -n=allowGlobalConfirmation`  
`choco install GoogleChrome speccy todobackup treesizefree vlc winrar pdfcreator adobereader goodsync notepadplusplus`

Manual:
Bitdefender

# Start Windows in safe mode

Method 1: Shift + Restart Option

Press the Power button from Start menu, or at Windows login screen. Then, press and hold the SHIFT key on your keyboard and click Restart.

Method 2: Shift+F8 

Hold the Shift button and mash the F8 key when Windows starts. This will sometimes boot you into the new advanced repair options. 



# Uninstall a file in Windows in safe mode

**if in safe mode**  
`REG ADD "HKLM\SYSTEM\CurrentControlSet\Control\SafeBoot\Minimal\MSIServer" /VE /T REG_SZ /F /D "Service"`  
`net start msiserver`

**if in safe mode with networking**  
`REG ADD "HKLM\SYSTEM\CurrentControlSet\Control\SafeBoot\Network\MSIServer" /VE /T REG_SZ /F /D "Service"`  
`net start msiserver`
