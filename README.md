# Kernel-Tools
Kernel-Tools is an Ark tool on the Windows platform          
It's a completely free tool                
support Windows 10 - Windows11          


### Features

1. View Process\Drivers\SystemCallBacks\SystemNotifys\MiniFilters\IDT\SSDT\SSSDT\IoTimer.....
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
18. Disable PatchGuard
19. Disable Hvci and DSE
20. Hide Driver


### Commandline

1. "Kernel Tools.exe" -ddse (Dynamic Disable Driver Signature Enforcement)
2. "Kernel Tools.exe" -edse (Dynamic Enable Driver Signature Enforcement)
3. "Kernel Tools.exe" -reboot (fastreboot)
4. "Kernel Tools.exe" -shutdown (fastshutdown)
5. "Kernel Tools.exe" -prohibitcreatefile (prohibitcreatefile)
6. "Kernel Tools.exe" -disabledprohibitcreatefile (disabledprohibitcreatefile)
7. "Kernel Tools.exe" -forcedeletefile (forcedeletefile(The only entry point for ForceDeleteFile))
8. "Kernel Tools.exe" -irpdeletefile(deletefile(The only entry point for DeleteFile))


### How to use

1. Disabled HVCI
2. Open Kernel Tools.exe
3. Select No in the pop-up selection box
4. Wait to enter


# Kernel-Views
### Drivers
Enum                  
1. Driver Name
2. Driver Base
3. Driver Object
4. Driver Path

Features:                    
ForceUnloadDriver   
Hidden Driver                                                


### System Callbacks/Notifys
Enum       
1. PsSetCreateProcessNotifyRoutine
2. PsSetCreateProcessNotifyRoutineEx
3. PsSetCreateProcessNotifyRoutineEx2
4. PsSetCreateThreadNotifyRoutine
5. PsSetCreateThreadNotifyRoutineEx
6. PsSetLoadImageNotifyRoutine
7. PsSetLoadImageNotifyRoutineEx
8. KeRegisterBugCheckCallback
9. KeRegisterBugCheckReasonCallback
10. CmRegisterCallback
11. CmRegisterCallbackEx
12. IoRegisterShutdownNotification
13. IoRegisterLastChanceShutdownNotification
14. PoRegisterPowerSettingCallback
15. IoRegisterFsRegistrationChange
16. KeRegisterNmiCallback
17. SeCiCallbacks
18. PoRegisterCoalescingCallback
19. IoRegisterPriorityCallback
20. PsRegisterAltSystemCallHandler
21. DbgSetDebugPrintCallback
22. ObRegisterCallBacks

Features:

Enum Type/Entry Address/Module  
Disabled Callback/Notify    



### MiniFiler
Enum      
1. Filter
2. Pre Operation
3. Post Operation
4. Module

Features:
Remove MiniFilter                 


### SSDT
Enum                 
1. Function Name
2. Function Address
3. Module

Features:

SSDT Hook Scan

### IDT
Enum         
1. IDT Function Address
2. Module


### IoTimer
Enum           
1. IoTimer Object Address
2. IoTimer Entry Address
3. Module
