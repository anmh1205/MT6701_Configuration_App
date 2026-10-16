# MT6701 Configuration App

A Windows installer distribution for a configuration utility associated with the **MT6701 magnetic rotary position sensor**.

## Overview

The MT6701 is a magnetic angle-sensing IC used in encoder and motor-position applications. This repository currently serves as a distribution point for the AML MT6701 configuration tool installer. It does **not** contain the application's source code or a reproducible build project.

## Download and install

The repository includes the Windows installer:

**[`AML_MT6701_Config_Tool_Setup.exe`](AML_MT6701_Config_Tool_Setup.exe)**

1. Download the installer from this repository.
2. Check that the file came from the intended repository and scan it according to your system's security policy.
3. Run it on a Windows machine using the permissions requested by the installer.
4. Connect compatible hardware only after confirming its electrical interface, power requirements, and connection method.

Because no hardware connection manual or supported adapter list is published in this repository, **compatibility with a particular board, USB adapter, or firmware revision has not been verified here**.

## Repository contents

| File | Purpose |
| --- | --- |
| [`AML_MT6701_Config_Tool_Setup.exe`](AML_MT6701_Config_Tool_Setup.exe) | Windows application installer |
| [`README.md`](README.md) | Distribution and usage context |
| [`.gitattributes`](.gitattributes) | Git file attributes |

## Limitations

This repository is a **binary distribution**, not a complete open-source SDK. The source code, change history for the installer, supported operating-system versions, and full wiring instructions are not provided here. There is no repository-wide license declaration. Consult the sensor's official documentation and the maintainer before attempting hardware-level changes or redistribution.
