# Registering AdsOcx.ocx on Windows

## Disclaimer

This is a personal guide not a peer reviewed journal or a sponsored publication. We make
no representations as to accuracy, completeness, correctness, suitability, or validity of any
information and will not be liable for any errors, omissions, or delays in this information or any
losses injuries, or damages arising from its display or use. All information is provided on an as
is basis. It is the reader’s responsibility to verify their own facts.

The views and opinions expressed in this guide are those of the authors and do not
necessarily reflect the official policy or position of any other agency, organization, employer or
company. Assumptions made in the analysis are not reflective of the position of any entity
other than the author(s) and, since we are critically thinking human beings, these views are
always subject to change, revision, and rethinking at any time. Please do not hold us to them
in perpetuity.

## Overview

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
