# Windows Tools: Self extracting .EXE archive with 7-zip

<b>Downloads:</b>

 * [7-zip download page](https://www.7-zip.org/download.html)

<b>Objectives:</b>

* Create simple self extracting .EXE archive that contains random files
* Create silent self extracting Office 2016 Installation

<b>Extract via command line:</b>

```batch
cmd /c files.exe -y -o"C:\Windows\Temp\Files"
```
<b>Create self extracting installation executable:</b>

```batch
copy /b 7zS.sfx + config.txt + office.7z Office.exe
```

### Related videos

[Silent software installation: Microsoft Office 2016 VL](https://youtu.be/a2k2bTDR_KE)