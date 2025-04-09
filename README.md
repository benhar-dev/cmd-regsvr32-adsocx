To manually register AdsOcx files on Windows, you can use the command-line. 

Open the Command Prompt with administrative privileges. To do this, press the Windows key, type "cmd," right-click on "Command Prompt," and select "Run as administrator."

## For TwinCAT 4026 - 64bit

Navigate to the directory ```cd C:\Program Files (x86)\Beckhoff\TwinCAT\Common64```

To register the OCX, type the following.
```regsvr32 AdsOcx.ocx```

## For TwinCAT 4026 - 32bit

Navigate to the directory ```cd C:\Program Files (x86)\Beckhoff\TwinCAT\Common32```

To register the OCX, type the following.
```%SystemRoot%\SysWOW64\regsvr32 AdsOcx.ocx```