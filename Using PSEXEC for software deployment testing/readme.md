## PSEXEC
Download: [PSEXEC](https://learn.microsoft.com/en-us/sysinternals/downloads/psexec)

## Commands
To start CMD as SYSTEM user
```powershell
PsExec.exe -i -s cmd
```

To start telegram installation using SYSTEM user
```powershell
PsExec.exe -i -s "C:\Users\admin\Desktop\Software\tsetup-x64.4.9.2.exe" /VERYSILENT /NORESTART
```

PsExec help menu
```powershell
PsExec.exe /?
```