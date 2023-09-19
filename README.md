#  Test 🌟

A directory of all my Object Pascal Test repositories.

I hope this will help someone with my captured knowledge on the below subjects.

## ✨ Test Application Demo

> [GitHub Repository](https://github.com/gcarreno/TestApplicationDemo)


A boiler plate on how to do Application config the "Lazarus Way (tm)".

It includes:

- Setting up what properties to save on `TForm.SessionProperties`
- `TINIPropStorage` for `TForm.SessionProperties` property storage
- `TFileExit` action with different shortcuts for Windows and Linux
- The use of `GetAppConfigFile()` to get the app's default file customised for Linux/Windows
- A way to have different short cuts for exit in Linux(CTRL+Q) and Windows(ALT+X)

## ✨ Test Download with Progress Bar

> [GitHub Repository](https://github.com/gcarreno/TestDownloadProgressBar)


Example of `fphttpclient` with a progress bar.

## ✨ Test Google Translate

> [GitHub Repository](https://github.com/gcarreno/TestGoogleTranslate)


[![Build Status](https://github.com/gcarreno/TestGoogleTranslate/workflows/build/badge.svg?branch=main)](https://github.com/gcarreno/TestGoogleTranslate/actions)
[![Supports Windows](https://img.shields.io/badge/support-Windows-blue?logo=Windows)](https://github.com/gcarreno/TestGoogleTranslate/releases/latest)
[![Supprts Linux](https://img.shields.io/badge/support-Linux-yellow?logo=Linux)](https://github.com/gcarreno/TestGoogleTranslate/releases/latest)
[![Supports macOS](https://img.shields.io/badge/support-macOS-black?logo=macOS)](https://github.com/gcarreno/TestGoogleTranslate/releases/latest)
[![License](https://img.shields.io/github/license/gcarreno/TestGoogleTranslate)](https://github.com/gcarreno/TestGoogleTranslate/blob/master/LICENSE)
[![Latest Release](https://img.shields.io/github/v/release/gcarreno/TestGoogleTranslate?label=latest%20release)](https://github.com/gcarreno/TestGoogleTranslate/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/gcarreno/TestGoogleTranslate/total)](https://github.com/gcarreno/TestGoogleTranslate/releases)

Testing Google Translate with Lazarus/FPC.

## ✨ Test HTML Viewers

> [GitHub Repository](https://github.com/gcarreno/TestHTML)

[![Supports Windows](https://img.shields.io/badge/support-Windows-blue?logo=Windows)](https://github.com/gcarreno/TestHTML/releases/latest)
[![Supprts Linux](https://img.shields.io/badge/support-Linux-yellow?logo=Linux)](https://github.com/gcarreno/TestHTML/releases/latest)
[![License](https://img.shields.io/github/license/gcarreno/TestHTML)](https://github.com/gcarreno/TestHTML/blob/master/LICENSE)

Program to test HTML Viewers.

I'm using the latest version available on the GitHub repository of [Bernd Gabriel](https://github.com/BerndGabriel/HtmlViewer) and have it included in this repository.

But you can install the needed components from the Online Package Manager(OPM).

## ✨ Test Lazarus Logging

> [GitHub Repository](https://github.com/gcarreno/TestLazarusLogging)


Repository to test and learn how to use the many logging choices in Lazarus

### List of options

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

### LazLogger

pros:
- Part of the FCL
- Command line params
- User defined log groups

cons:
- Does not have multiple log providers

For more information on this option: [LazLogger README](LazLogger/README.md)

### TEventLog

pros:
- Part of the LCL
- Windows: Uses the system log

cons:
- Does not have multiple log providers

todo:
- Linux: Need to see if there is some difference geared towards a Linux system log

For more information on this option: [TEventLog README](TEventLog/README.md)

## ✨ Test Linux Distribution Information

> [GitHub Repository](https://github.com/gcarreno/TestLinuxDistInfo)

[![Build Status](https://github.com/gcarreno/TestLinuxDistInfo/workflows/build/badge.svg?branch=main)](https://github.com/gcarreno/TestLinuxDistInfo/actions)
[![Supports Linux](https://img.shields.io/badge/support-Linux-yellow?logo=Linux)](https://github.com/gcarreno/TestLinuxDistInfo/releases/latest)
[![License](https://img.shields.io/github/license/gcarreno/TestLinuxDistInfo)](https://github.com/gcarreno/TestLinuxDistInfo/blob/master/LICENSE)
[![Latest Release](https://img.shields.io/github/v/release/gcarreno/TestLinuxDistInfo?label=latest%20release)](https://github.com/gcarreno/TestLinuxDistInfo/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/gcarreno/TestLinuxDistInfo/total)](https://github.com/gcarreno/TestLinuxDistInfo/releases)

Searches for the various methods to obtain information about the current installed distro.

Presents the options found and allows to query each one individually.

### Screenshot

![Linux Dark Theme v0.1.1](https://github.com/gcarreno/TestLinuxDistInfo/raw/main/img/LinuxDarkTheme-v0.1.1.png)

## ✨ Test Markdown

> [GitHub Repository](https://github.com/gcarreno/TestMarkdown)


[![Build Status](https://github.com/gcarreno/TestMarkdown/workflows/build/badge.svg?branch=main)](https://github.com/gcarreno/TestMarkdown/actions)
[![Supports Windows](https://img.shields.io/badge/support-Windows-blue?logo=Windows)](https://github.com/gcarreno/TestMarkdown/releases/latest)
[![Supprts Linux](https://img.shields.io/badge/support-Linux-yellow?logo=Linux)](https://github.com/gcarreno/TestMarkdown/releases/latest)
[![License](https://img.shields.io/github/license/gcarreno/TestMarkdown)](https://github.com/gcarreno/TestMarkdown/blob/master/LICENSE)
[![Latest Release](https://img.shields.io/github/v/release/gcarreno/TestMarkdown?label=latest%20release)](https://github.com/gcarreno/TestMarkdown/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/gcarreno/TestMarkdown/total)](https://github.com/gcarreno/TestMarkdown/releases)

Program to test 2 Markdown libraries:

- [pasHTMLdown](https://github.com/BeRo1985/pashtmldown)
- [delphi-markdown](https://github.com/grahamegrieve/delphi-markdown)

## ✨ Test QR Code

> [GitHub Repository](https://github.com/gcarreno/TestQRCode)


Program to test two Lazarus QR Code generation libs, available on OPM:

* LazBarcodes
* QRCodeGenLib

## ✨ Test Resource Loading

> [GitHub Repository](https://github.com/gcarreno/TestResourceLoading)

[![Build Status](https://github.com/gcarreno/TestResourceLoading/workflows/build/badge.svg?branch=main)](https://github.com/gcarreno/TestResourceLoading/actions)
[![Supports Windows](https://img.shields.io/badge/support-Windows-blue?logo=Windows)](https://github.com/gcarreno/TestResourceLoading/releases/latest)
[![Supprts Linux](https://img.shields.io/badge/support-Linux-yellow?logo=Linux)](https://github.com/gcarreno/TestResourceLoading/releases/latest)
[![License](https://img.shields.io/github/license/gcarreno/TestResourceLoading)](https://github.com/gcarreno/TestResourceLoading/blob/master/LICENSE)
[![Latest Release](https://img.shields.io/github/v/release/gcarreno/TestResourceLoading?label=latest%20release)](https://github.com/gcarreno/TestResourceLoading/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/gcarreno/TestResourceLoading/total)](https://github.com/gcarreno/TestResourceLoading/releases)

A simple example on how to load a file from the binary resources onto a `TMemo`

## ✨ Test Restart Application

> [GitHub Repository](https://github.com/gcarreno/TestRestartApplication)

[![Build Status](https://github.com/gcarreno/TestRestartApplication/workflows/build/badge.svg?branch=main)](https://github.com/gcarreno/TestRestartApplication/actions)
[![Supports Windows](https://img.shields.io/badge/support-Windows-blue?logo=Windows)](https://github.com/gcarreno/TestRestartApplication/releases/latest)
[![Supprts Linux](https://img.shields.io/badge/support-Linux-yellow?logo=Linux)](https://github.com/gcarreno/TestRestartApplication/releases/latest)
[![License](https://img.shields.io/github/license/gcarreno/TestRestartApplication)](https://github.com/gcarreno/TestRestartApplication/blob/master/LICENSE)
[![Latest Release](https://img.shields.io/github/v/release/gcarreno/TestRestartApplication?label=latest%20release)](https://github.com/gcarreno/TestRestartApplication/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/gcarreno/TestRestartApplication/total)](https://github.com/gcarreno/TestRestartApplication/releases)

Program to test a cross platform way of doing application restarting itself.

## ✨ Test Thread Pool

> [GitHub Repository](https://github.com/gcarreno/TestThreadPool)

[![Supports Windows](https://img.shields.io/badge/support-Windows-blue?logo=Windows)](https://github.com/gcarreno/TestThreadPool/releases/latest)
[![Supports Linux](https://img.shields.io/badge/support-Linux-yellow?logo=Linux)](https://github.com/gcarreno/TestThreadPool/releases/latest)
[![Supports macOS](https://img.shields.io/badge/support-macOS-black?logo=macOS)](https://github.com/gcarreno/TestThreadPool/releases/latest)
[![License](https://img.shields.io/github/license/gcarreno/TestThreadPool)](https://github.com/gcarreno/TestThreadPool/blob/master/LICENSE)
[![Latest Release](https://img.shields.io/github/v/release/gcarreno/TestThreadPool?label=latest%20release)](https://github.com/gcarreno/TestThreadPool/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/gcarreno/TestThreadPool/total)](https://github.com/gcarreno/TestThreadPool/releases)

Example of how to use the Class `TThread` with a pool manager.

### Credits

Original Code: Andrew Thomas Brunner (http://www.aurawin.com)

Correcting Critical Section Lock: paweld (https://github.com/paweld)

## ✨ Test Threading

> [GitHub Repository](https://github.com/gcarreno/TestThreading)

[![Build Status](https://github.com/gcarreno/TestThreading/actions/workflows/main.lazarus.yml/badge.svg?branch=main)](https://github.com/gcarreno/TestThreading/actions)
[![Supports Windows](https://img.shields.io/badge/support-Windows-blue?logo=Windows)](https://github.com/gcarreno/TestThreading/releases/latest)
[![Supports Linux](https://img.shields.io/badge/support-Linux-yellow?logo=Linux)](https://github.com/gcarreno/TestThreading/releases/latest)
[![Supports macOS](https://img.shields.io/badge/support-macOS-black?logo=macOS)](https://github.com/gcarreno/TestThreading/releases/latest)
[![License](https://img.shields.io/github/license/gcarreno/TestThreading)](https://github.com/gcarreno/TestThreading/blob/master/LICENSE)
[![Latest Release](https://img.shields.io/github/v/release/gcarreno/TestThreading?label=latest%20release)](https://github.com/gcarreno/TestThreading/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/gcarreno/TestThreading/total)](https://github.com/gcarreno/TestThreading/releases)

Example of how to use the Class `TThread` and all of the threading tools available with Free Pascal.

### Single Thread, Single Instance

This exemplifies the most basic use of a thread.

It declares an event to hook into the main form.

This is a single shot use because we set the thread's `FreeOnTerminate` property to True.

### Single Thread, Many Instances

The example above isn't of much use if we just run a single instance.

In this example we create multiple instances of the same thread and we start them concurrently.

This is, **also**, a single shot use because we set the thread's `FreeOnTerminate` property to True.

