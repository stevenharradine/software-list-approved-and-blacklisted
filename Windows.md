# Windows
The vain of my existance.  If you must use this aweful operating system you need be [smart when using the Internet]().

and also follow these tips:
 * should be using 7, 8 or 8.1 (10 you cannot disable telemetry data in the consumer product and as a result is blacklisted)
 * [disable telemetry data collection](http://superuser.com/questions/972501/how-to-stop-microsoft-from-gathering-telemetry-data-from-windows-7-8-and-8-1)
 * enable User Access Controls UAC
 
 ```C:\Windows\System32\cmd.exe /k %windir%\System32\reg.exe ADD HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System /v EnableLUA /t REG_DWORD /d 1 /f```
 * For Windows 7 install [Microsoft Security Essentials](http://www.microsoft.com/security/pc-security/mse.aspx)
 * For Windows 8 install [Windows Defender](http://www.microsoft.com/security/pc-security/windows8.aspx#antivirus)
 * do not install 3rd party antivirus software from Symantic, Intel Security (formerly Mcafee), etc
 * ALWAYS keep your system and software updated.
