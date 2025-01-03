# Kernel-Tools
Kernel-Tools is an Ark tool on the Windows platform          
It's a completely free tool                
support Windows 10 - Windows11          


### Features

1. View Process\Drivers\SystemCallBacks\SystemNotifys\MiniFilters\IDT\SSDT\IoTimer.....
2. Hide Process
3. Force Hide Process(Erase PspCidTable\Set Pid To 0 ...)
4. TerminateProcess(ZwTerminateProcess)
5. ForceTerminateProcess(Ignore any process protections)
6. SetProcessPP(L)s
7. SetProcessPid
8. Set Process To System Critical Process
9. SuspendProcess
10. ResumeProcess
11. ProtectProcess
12. DIKS/FSD/ScSi/Acpi/AtApi/KeyBoard/Mouse/PartMgr Hook Scan/Remove
13. Prohibit CreateProcess/LoadDriver/Edit Registry/CreateFile/READ WRITE Disk BOOT Sector
14. Dynamic Disable Driver Signature Enforcement / Enable Driver Signature Enforcement
15. ForceDeleteFile(Ignore Irp Occupation/HardLink/Handle Occupation)
16. FastShutDown
17. FastReboot


### Commandline

1. "Kernel Tools.exe" -ddse (Dynamic Disable Driver Signature Enforcement)
2. "Kernel Tools.exe" -edse (Dynamic Enable Driver Signature Enforcement)
3. "Kernel Tools.exe" -reboot (fastreboot)
4. "Kernel Tools.exe" -shutdown (fastshutdown)
5. "Kernel Tools.exe" -prohibitcreatefile (prohibitcreatefile)
6. "Kernel Tools.exe" -disabledprohibitcreatefile (disabledprohibitcreatefile)
7. "Kernel Tools.exe" -forcedeletefile (forcedeletefile(The only entry point for ForceDeleteFile))


### How to use

1. Disabled HVCI
2. Open Kernel Tools.exe
3. Select No in the pop-up selection box
4. Wait to enter