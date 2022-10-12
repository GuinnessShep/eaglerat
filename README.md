
# 
## Current features

* Clients written in C# and VB (32 and 64 bit) (dlls + exes)
* Passwords recovery
* History recovery
* Autofill recovery
* Keywords recovery
* Remote camera viewer (+ save pictures)
* Remote microphone (auto saved)
* Remote desktop control (+ save pictures)
* Remote keyboard
* Remote mouse
* Remote chat
* Remote DotNet Code Execution (VB + C#)
* Process manager 
* Kill process (native techniques)
* Suspend process (native techniques)
* Resume process (native techniques)
* ShellCode injection (NtWriteVirtualMemory + NtCreateThreadEx)
* ShellCode injection (NtMapViewOfSection + NtCreateThreadEx)
* Shutdown system
* Reboot system
* Suspend system
* Hibernate system
* Log out user
* BSOD
* Lock workstation
* Offline keylogger (automatically saved)
* Realtime keylogger (automatically saved)
* Managed pe execution (current process)
* Unmanaged pe execution (current process)
* Managed dll execution (current process)
* Unmanaged dll execution (current process)
* Shellcode execution (current process)
* Blur screenlocker
* Audio up
* Audio down
* Hide + show taskbar
* Hide + show desktop icons
* Set wallpaper
* File manager
* Delete file
* Download file
* Rename file
* Upload file
* Get information (CPU, hardware, system)
* Shortcuts (download, desktop and documents paths)
* Logs (automatically saved)

## External depencencies

* GunaUI 
* dnlib 
* Newtonsoft.Json
* NAudio

## Notes

* All saved stuff (logs, passwords...) are saved in csv format except offline keylogger
* All external dlls used are in folder "DLLs + Package"
* This remote access tool can also be used as stealer & payloads loader.
* Build the project in "release mode" only (change x64 bit for Server and clients)
* If you update with installer, you will have to backup your configs + logs (.dat, .json, Logs folder)
* Under license (AGPL)

## Technical information

* Communication encrypted with RSM encryption (https://bhf.im/threads/438711/)
* Packets compressed with QuickLZ (http://www.quicklz.com/download.html)
* Automation tasks saved with binary format
* Settings saved with JSON format
* Server .NET 4.8
* Client .NET 4.5
* Tested on freshly installed W10 & W11 VM

## DLLs

Dlls are same as exe. You have to change the config class.
The entrypoint should be called as follows :
