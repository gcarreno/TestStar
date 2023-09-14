# Test 🌟

A directory of all my Object Pascal Test repositories.

I hope this will help someone with my captured knowledge on the below subjects.

## The List

### Application Demo

- [GitHub Repository](https://github.com/gcarreno/TestApplicationDemo)

A boiler plate on how to do Application config the "Lazarus Way ™".

It includes:

- Setting up what properties to save on `TForm.SessionProperties`
- `TINIPropStorage` for `TForm.SessionProperties` property storage
- `TFileExit` action with different shortcuts for Windows and Linux
- The use of `GetAppConfigFile()` to get the app's default file customised for Linux/Windows
- A way to have different short cuts for exit in Linux(CTRL+Q) and Windows(ALT+X)

### Download with Progress Bar

- [GitHub Repository](https://github.com/gcarreno/TestDownloadProgressBar)

Example of `fphttpclient` with a progress bar.

### Google Translate
[![Build Status](https://github.com/gcarreno/TestGoogleTranslate/workflows/build/badge.svg?branch=main)](https://github.com/gcarreno/TestGoogleTranslate/actions)
[![Supports Windows](https://img.shields.io/badge/support-Windows-blue?logo=Windows)](https://github.com/gcarreno/TestGoogleTranslate/releases/latest)
[![Supprts Linux](https://img.shields.io/badge/support-Linux-yellow?logo=Linux)](https://github.com/gcarreno/TestGoogleTranslate/releases/latest)
[![Supports macOS](https://img.shields.io/badge/support-macOS-black?logo=macOS)](https://github.com/gcarreno/TestGoogleTranslate/releases/latest)
[![License](https://img.shields.io/github/license/gcarreno/TestGoogleTranslate)](https://github.com/gcarreno/TestGoogleTranslate/blob/master/LICENSE)
[![Latest Release](https://img.shields.io/github/v/release/gcarreno/TestGoogleTranslate?label=latest%20release)](https://github.com/gcarreno/TestGoogleTranslate/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/gcarreno/TestGoogleTranslate/total)](https://github.com/gcarreno/TestGoogleTranslate/releases)

- [GitHub Repository](https://github.com/gcarreno/TestGoogleTranslate)


Testing Google Translate with Lazarus/FPC.

### Lazarus Logging

- [GitHub Repository](https://github.com/gcarreno/TestLazarusLogging)

Repository to test and learn how to use the many logging choices in Lazarus

#### List of options

Tested:
- LazLogger: https://wiki.freepascal.org/LazLogger (Comes with Lazarus)
- TEventLogger: https://wiki.lazarus.freepascal.org/TEventLog (Comes with `fcl-base` package)

Work in Progress:
- MultiLog: https://wiki.freepascal.org/MultiLog  (OPM)
  - GitHub: https://github.com/blikblum/multilog

Next:
- QuickLogger: https://github.com/exilon/QuickLogger
  - Depends on QuickLib: https://github.com/exilon/QuickLib

Maybe:
- ExceptionLogger: https://github.com/r3code/lazarus-exception-logger (OPM)
- Log4Delphi: https://wiki.freepascal.org/Log4Delphi
  - Author: http://log4delphi.sourceforge.net/index.html
  - Port for `FPC`: http://sourceforge.net/projects/lazarus-ccr/files/Log4Delphi
- Log4L: https://github.com/CynicRus/Log4L
- Renegade Logger: https://github.com/hiraethbbs/Renegade.Logger
- ooLog: https://github.com/VencejoSoftware/ooLog
- datalogger: https://github.com/dliocode/datalogger

#### LazLogger

pros:
- Part of the FCL
- Command line params
- User defined log groups

cons:
- Does not have multiple log providers

For more information on this option: [LazLogger README](https://github.com/gcarreno/TestLazarusLogging/blob/main/LazLogger/README.md)

#### TEventLog

pros:
- Part of the LCL
- Windows: Uses the system log

cons:
- Does not have multiple log providers

todo:
- Linux: Need to see if there is some difference geared towards a Linux system log

For more information on this option: [TEventLog README](https://github.com/gcarreno/TestLazarusLogging/blob/main/TEventLog/README.md)

### Linux Distribution Information

[![Build Status](https://github.com/gcarreno/TestLinuxDistInfo/workflows/build/badge.svg?branch=main)](https://github.com/gcarreno/TestLinuxDistInfo/actions)
[![Supports Linux](https://img.shields.io/badge/support-Linux-yellow?logo=Linux)](https://github.com/gcarreno/TestLinuxDistInfo/releases/latest)
[![License](https://img.shields.io/github/license/gcarreno/TestLinuxDistInfo)](https://github.com/gcarreno/TestLinuxDistInfo/blob/master/LICENSE)
[![Latest Release](https://img.shields.io/github/v/release/gcarreno/TestLinuxDistInfo?label=latest%20release)](https://github.com/gcarreno/TestLinuxDistInfo/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/gcarreno/TestLinuxDistInfo/total)](https://github.com/gcarreno/TestLinuxDistInfo/releases)

- [GitHub Repository](https://github.com/gcarreno/TestLinuxDistInfo)

Searches for the various methods to obtain information about the current installed distro.

Presents the options found and allows to query each one individually.

#### Screenshot

![Linux Dark Theme v0.1.1](https://github.com/gcarreno/TestLinuxDistInfo/blob/main/img/LinuxDarkTheme-v0.1.1.png)

### Markdown

[![Build Status](https://github.com/gcarreno/TestMarkdown/workflows/build/badge.svg?branch=main)](https://github.com/gcarreno/TestMarkdown/actions)
[![Supports Windows](https://img.shields.io/badge/support-Windows-blue?logo=Windows)](https://github.com/gcarreno/TestMarkdown/releases/latest)
[![Supprts Linux](https://img.shields.io/badge/support-Linux-yellow?logo=Linux)](https://github.com/gcarreno/TestMarkdown/releases/latest)
[![License](https://img.shields.io/github/license/gcarreno/TestMarkdown)](https://github.com/gcarreno/TestMarkdown/blob/master/LICENSE)
[![Latest Release](https://img.shields.io/github/v/release/gcarreno/TestMarkdown?label=latest%20release)](https://github.com/gcarreno/TestMarkdown/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/gcarreno/TestMarkdown/total)](https://github.com/gcarreno/TestMarkdown/releases)

- [GitHub Repository](https://github.com/gcarreno/TestMarkdown)

Program to test 2 Markdown libraries:

- [pasHTMLdown](https://github.com/BeRo1985/pashtmldown)
- [delphi-markdown](https://github.com/grahamegrieve/delphi-markdown)

### QR Code

- [GitHub Repository](https://github.com/gcarreno/TestQRCode)

Program to test two Lazarus QR Code generation libs, available on OPM:

* LazBarcodes
* QRCodeGenLib

### Resource Loading

[![Build Status](https://github.com/gcarreno/TestResourceLoading/workflows/build/badge.svg?branch=main)](https://github.com/gcarreno/TestResourceLoading/actions)
[![Supports Windows](https://img.shields.io/badge/support-Windows-blue?logo=Windows)](https://github.com/gcarreno/TestResourceLoading/releases/latest)
[![Supprts Linux](https://img.shields.io/badge/support-Linux-yellow?logo=Linux)](https://github.com/gcarreno/TestResourceLoading/releases/latest)
[![License](https://img.shields.io/github/license/gcarreno/TestResourceLoading)](https://github.com/gcarreno/TestResourceLoading/blob/master/LICENSE)
[![Latest Release](https://img.shields.io/github/v/release/gcarreno/TestResourceLoading?label=latest%20release)](https://github.com/gcarreno/TestResourceLoading/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/gcarreno/TestResourceLoading/total)](https://github.com/gcarreno/TestResourceLoading/releases)

- [GitHub Repository](https://github.com/gcarreno/TestResourceLoading)

A simple example on how to load a file from the binary resources onto a `TMemo`
