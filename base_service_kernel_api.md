---
layout: default
title: Base Service API
---



<div class="sidenav">

<div markdown="1">

[Beep](#beep)
[BeginDeferWindowPos](#begindeferwindowpos)
[CloseHandle](#closehandle)
[CopyFile](#copyfile)
[CopyFileEx](#copyfileex)
[CreateEvent](#createevent)
[CreateFile](#createfile)
[CreateMutex](#createmutex)
[EndUpdateResource](#endupdateresource)
[EnumResourceTypes](#enumresourcetypes)
[FindFirstFile](#findfirstfile)
[FindResource](#findresource)
[FindResourceEx](#findresourceex)
[FormatMessage](#formatmessage)
[FreeLibrary](#freelibrary)
[GetCommState](#getcommstate)
[GetComputername](#getcomputername)
[GetCurrentProcess](#getcurrentprocess)
[GetCurrentThreadId](#getcurrentthreadid)
[GetLastError](#getlasterror)
[GetLocalTime](#getlocaltime)
[GetLogicalDriveStrings](#getlogicaldrivestrings)
[GetModuleFilename](#getmodulefilename)
[GetModuleHandle](#getmodulehandle)
[GetPrivateProfileInt](#getprivateprofileint)
[GetPrivateProfileSection](#getprivateprofilesection)
[GetPrivateProfileString](#getprivateprofilestring)
[GetProfileInt](#getprofileint)
[GetProfileString](#getprofilestring)
[GetShortPathName](#getshortpathname)
[GetSystemDirectory](#getsystemdirectory)
[GetSystemTime](#getsystemtime)
[GetTempFilename](#gettempfilename)
[GetTempPath](#gettemppath)
[GetTickCount](#gettickcount)
[GetVersionEx](#getversionex)
[GetWindowsDirectory](#getwindowsdirectory)
[GlobalFree](#globalfree)
[GlobalLock](#globallock)
[GlobalMemoryStatus](#globalmemorystatus)
[GlobalUnlock](#globalunlock)
[LoadLibraryA](#loadlibrarya)
[LoadLibraryEx](#loadlibraryex)
[LoadResource](#loadresource)
[LockResource](#lockresource)
[MoveFile](#movefile)
[OpenFile](#openfile)
[OpenMutex](#openmutex)
[OutputDebugString](#outputdebugstring)
[PurgeComm](#purgecomm)
[ReleaseMutex](#releasemutex)
[RemoveDirectory](#removedirectory)
[SetCommState](#setcommstate)
[SetCommTimeouts](#setcommtimeouts)
[SetEnvironmentVariable](#setenvironmentvariable)
[SetEvent](#setevent)
[SetSystemTime](#setsystemtime)
[SizeofResource](#sizeofresource)
[Sleep](#sleep)
[TransmitCommChar](#transmitcommchar)
[UpdateResource](#updateresource)
[WaitCommEvent](#waitcommevent)
[WaitForSingleObject](#waitforsingleobject)
[WinExec](#winexec)
[WritePrivateProfileSection](#writeprivateprofilesection)
[WritePrivateProfileString](#writeprivateprofilestring)
[WriteProfileString](#writeprofilestring)


</div>

</div>


<div class="right_main">

<div markdown="1">






Base Service (Kernel) API
====================

---

<SECTION ID="beep">
</SECTION>
## Beep
Generates simple tones on the speaker. The function is synchronous; it performs an alertable wait and does not return control to its caller until the sound finishes.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/utilapiset/nf-utilapiset-beep" target="_blank">here</a>


---

<SECTION ID="begindeferwindowpos">
</SECTION>
## BeginDeferWindowPos
Allocates memory for a multiple-window- position structure and returns the handle to the structure.

### Info
* **Category**: bsk api
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-begindeferwindowpos" target="_blank">here</a>



---

<SECTION ID="closehandle">
</SECTION>
## CloseHandle
Closes an open object handle.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/handleapi/nf-handleapi-closehandle" target="_blank">here</a>



---

<SECTION ID="copyfile">
</SECTION>
## CopyFile
Copies an existing file to a new file.

### Description
The CopyFileEx function provides two additional capabilities. CopyFileEx can call a specified callback function each time a portion of the copy operation is completed, and CopyFileEx can be canceled during the copy operation.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-copyfile" target="_blank">here</a>


---

<SECTION ID="copyfileex">
</SECTION>
## CopyFileEx
Copies an existing file to a new file, notifying the application of its progress through a callback function.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-copyfileexa" target="_blank">here</a>


---

<SECTION ID="createevent">
</SECTION>
## CreateEvent
Creates or opens a named or unnamed event object.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/synchapi/nf-synchapi-createeventa" target="_blank">here</a>


---

<SECTION ID="createfile">
</SECTION>
## CreateFile
Creates or opens a file or I/O device. The most commonly used I/O devices are as follows: file, file stream, directory, physical disk, volume, console buffer, tape drive, communications resource, mailslot, and pipe.

### Description
The function returns a handle that can be used to access the file or device for various types of I/O depending on the file or device and the flags and attributes specified.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/fileapi/nf-fileapi-createfilea" target="_blank">here</a>


---

<SECTION ID="createmutex">
</SECTION>
## CreateMutex
Creates or opens a named or unnamed mutex object.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/synchapi/nf-synchapi-createmutexa" target="_blank">here</a>


---

<SECTION ID="endupdateresource">
</SECTION>
## EndUpdateResource
Commits or discards changes made prior to a call to UpdateResource.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-endupdateresourcea" target="_blank">here</a>



---

<SECTION ID="enumresourcetypes">
</SECTION>
## EnumResourceTypes
Enumerates resource types within a binary module.

### Description
Starting with Windows Vista, this is typically a language-neutral Portable Executable (LN file), and the enumeration also includes resources from one of the corresponding language-specific resource files (.mui files)—if one exists—that contain localizable language resources. It is also possible to use hModule to specify a .mui file, in which case only that file is searched for resource types.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-enumresourcetypesa" target="_blank">here</a>



---

<SECTION ID="findfirstfile">
</SECTION>
## FindFirstFile
Searches a directory for a file or subdirectory with a name that matches a specific name (or partial name if wildcards are used).

### Description
To specify additional attributes to use in a search, use the FindFirstFileEx function.<br>
To perform this operation as a transacted operation, use the FindFirstFileTransacted function.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/fileapi/nf-fileapi-findfirstfilea" target="_blank">here</a>



---

<SECTION ID="findresource">
</SECTION>
## FindResource
Determines the location of a resource with the specified type and name in the specified module. To specify a language, use the FindResourceEx function.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-findresourcea" target="_blank">here</a>



---

<SECTION ID="findresourceex">
</SECTION>
## FindResourceEx
Determines the location of the resource with the specified type, name, and language in the specified module.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-findresourceexa" target="_blank">here</a>



---

<SECTION ID="formatmessage">
</SECTION>
## FormatMessage
Formats a message string. The function requires a message definition as input.

### Description
The message definition can come from a buffer passed into the function. It can come from a message table resource in an already-loaded module. Or the caller can ask the function to search the system's message table resource(s) for the message definition. The function finds the message definition in a message table resource based on a message identifier and a language identifier. The function copies the formatted message text to an output buffer, processing any embedded insert sequences if requested.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-formatmessage" target="_blank">here</a>



---

<SECTION ID="freelibrary">
</SECTION>
## FreeLibrary
Frees the loaded dynamic-link library (DLL) module and, if necessary, decrements its reference count. When the reference count reaches zero, the module is unloaded from the address space of the calling process and the handle is no longer valid.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/libloaderapi/nf-libloaderapi-freelibrary" target="_blank">here</a>



---

<SECTION ID="getcommstate">
</SECTION>
## GetCommState
Retrieves the current control settings for a specified communications device.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-getcommstate" target="_blank">here</a>


---

<SECTION ID="getcomputername">
</SECTION>
## GetComputername
Retrieves the NetBIOS name of the local computer. This name is established at system startup, when the system reads it from the registry.

### Description
GetComputerName retrieves only the NetBIOS name of the local computer. To retrieve the DNS host name, DNS domain name, or the fully qualified DNS name, call the GetComputerNameEx function. Additional information is provided by the IADsADSystemInfo interface.<br>
The behavior of this function can be affected if the local computer is a node in a cluster. For more information, see ResUtilGetEnvironmentWithNetName and UseNetworkName.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-getcomputernamea" target="_blank">here</a>


---

<SECTION ID="getcurrentprocess">
</SECTION>
## GetCurrentProcess
Retrieves a pseudo handle for the current process.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/processthreadsapi/nf-processthreadsapi-getcurrentprocess" target="_blank">here</a>



---

<SECTION ID="getcurrentthreadid">
</SECTION>
## GetCurrentThreadId
Retrieves the thread identifier of the calling thread.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/processthreadsapi/nf-processthreadsapi-getcurrentthreadid" target="_blank">here</a>



---

<SECTION ID="getlasterror">
</SECTION>
## GetLastError
Retrieves the calling thread's last-error code value. The last-error code is maintained on a per-thread basis. Multiple threads do not overwrite each other's last-error code.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/errhandlingapi/nf-errhandlingapi-getlasterror" target="_blank">here</a>



---

<SECTION ID="getlocaltime">
</SECTION>
## GetLocalTime
Retrieves the current local date and time. To retrieve the current date and time in Coordinated Universal Time (UTC) format, use the GetSystemTime function.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/sysinfoapi/nf-sysinfoapi-getlocaltime" target="_blank">here</a>



---

<SECTION ID="getlogicaldrivestrings">
</SECTION>
## GetLogicalDriveStrings
Fills a buffer with strings that specify valid drives in the system.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/fileapi/nf-fileapi-getlogicaldrivestringsw" target="_blank">here</a>



---

<SECTION ID="getmodulefilename">
</SECTION>
## GetModuleFilename
Retrieves the fully-qualified path for the file that contains the specified module.

### Description
The module must have been loaded by the current process. To locate the file for a module that was loaded by another process, use the GetModuleFileNameEx function.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/libloaderapi/nf-libloaderapi-getmodulefilenamea" target="_blank">here</a>



---

<SECTION ID="getmodulehandle">
</SECTION>
## GetModuleHandle
Retrieves a module handle for the specified module. The module must have been loaded by the calling process. To avoid the race conditions described in the Remarks section, use the GetModuleHandleEx function.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/libloaderapi/nf-libloaderapi-getmodulehandlea" target="_blank">here</a>


---

<SECTION ID="getprivateprofileint">
</SECTION>
## GetPrivateProfileInt
Retrieves an integer associated with a key in the specified section of an initialization file.

### Description
Note This function is provided only for compatibility with 16-bit Windows-based applications. Applications should store initialization information in the registry.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-getprivateprofileint" target="_blank">here</a>




---

<SECTION ID="getprivateprofilesection">
</SECTION>
## GetPrivateProfileSection
Retrieves all the keys and values for the specified section of an initialization file.

### Description
Note This function is provided only for compatibility with 16-bit applications written for Windows. Applications should store initialization information in the registry.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-getprivateprofilesection" target="_blank">here</a>



---

<SECTION ID="getprivateprofilestring">
</SECTION>
## GetPrivateProfileString
Retrieves a string from the specified section in an initialization file.

### Description
Note This function is provided only for compatibility with 16-bit Windows-based applications. Applications should store initialization information in the registry.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-getprivateprofilestring" target="_blank">here</a>




---

<SECTION ID="getprofileint">
</SECTION>
## GetProfileInt
Retrieves an integer from a key in the specified section of the Win.ini file.

### Description
Note This function is provided only for compatibility with 16-bit Windows-based applications. Applications should store initialization information in the registry.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-getprofileinta" target="_blank">here</a>




---

<SECTION ID="getprofilestring">
</SECTION>
## GetProfileString
Retrieves the string associated with a key in the specified section of the Win.ini file.

### Description
Note This function is provided only for compatibility with 16-bit Windows-based applications, therefore this function should not be called from server code. Applications should store initialization information in the registry.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-getprofilestringa" target="_blank">here</a>



---

<SECTION ID="getshortpathname">
</SECTION>
## GetShortPathName
Retrieves the short path form of the specified path. For more information about file and path names, see Naming Files, Paths, and Namespaces.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/fileapi/nf-fileapi-getshortpathnamew" target="_blank">here</a>



---

<SECTION ID="getsystemdirectory">
</SECTION>
## GetSystemDirectory
Retrieves the path of the system directory. The system directory contains system files such as dynamic-link libraries and drivers.

### Description
This function is provided primarily for compatibility. Applications should store code in the Program Files folder and persistent data in the Application Data folder in the user's profile.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/sysinfoapi/nf-sysinfoapi-getsystemdirectorya" target="_blank">here</a>


---

<SECTION ID="getsystemtime">
</SECTION>
## GetSystemTime
Retrieves the current system date and time. The system time is expressed in Coordinated Universal Time (UTC).

### Description
To retrieve the current system date and time in local time, use the GetLocalTime function.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/sysinfoapi/nf-sysinfoapi-getsystemtime" target="_blank">here</a>


---

<SECTION ID="gettempfilename">
</SECTION>
## GetTempFilename
Creates a name for a temporary file. If a unique file name is generated, an empty file is created and the handle to it is released; otherwise, only a file name is generated.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/fileapi/nf-fileapi-gettempfilenamea" target="_blank">here</a>


---

<SECTION ID="gettemppath">
</SECTION>
## GetTempPath
Retrieves the path of the directory designated for temporary files.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/fileapi/nf-fileapi-gettemppatha" target="_blank">here</a>


---

<SECTION ID="gettickcount">
</SECTION>
## GetTickCount
Retrieves the number of milliseconds that have elapsed since the system was started, up to 49.7 days.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/sysinfoapi/nf-sysinfoapi-gettickcount" target="_blank">here</a>



---

<SECTION ID="getversionex">
</SECTION>
## GetVersionEx
Retrieves information about the current operating system.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/sysinfoapi/nf-sysinfoapi-getversionexa" target="_blank">here</a>



---

<SECTION ID="getwindowsdirectory">
</SECTION>
## GetWindowsDirectory
Retrieves the path of the Windows directory.

### Description
This function is provided primarily for compatibility with legacy applications. New applications should store code in the Program Files folder and persistent data in the Application Data folder in the user's profile

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/sysinfoapi/nf-sysinfoapi-getwindowsdirectorya" target="_blank">here</a>




---

<SECTION ID="globalfree">
</SECTION>
## GlobalFree
Frees the specified global memory object and invalidates its handle.

### Description
Note The global functions have greater overhead and provide fewer features than other memory management functions. New applications should use the <a href="https://docs.microsoft.com/en-in/windows/win32/memory/heap-functions" target="_blank">heap functions</a> unless documentation states that a global function should be used. For more information, see <a href="https://docs.microsoft.com/en-in/windows/win32/memory/global-and-local-functions"  target="_blank">Global and Local Functions</a>.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-globalfree" target="_blank">here</a>



---

<SECTION ID="globallock">
</SECTION>
## GlobalLock
Locks a global memory object and returns a pointer to the first byte of the object's memory block.

### Description
Note The global functions have greater overhead and provide fewer features than other memory management functions. New applications should use the  <a href="https://docs.microsoft.com/en-in/windows/win32/memory/heap-functions" target="_blank">heap functions</a> unless documentation states that a global function should be used. For more information, see <a href="https://docs.microsoft.com/en-in/windows/win32/memory/global-and-local-functions"  target="_blank">Global and Local Functions</a>.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-globallock" target="_blank">here</a>


---

<SECTION ID="globalmemorystatus">
</SECTION>
## GlobalMemoryStatus
[GlobalMemoryStatus can return incorrect information. Use the GlobalMemoryStatusEx function instead. ] Retrieves information about the system's current usage of both physical and virtual memory.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-globalmemorystatus" target="_blank">here</a>




---

<SECTION ID="globalunlock">
</SECTION>
## GlobalUnlock
Decrements the lock count associated with a memory object that was allocated with GMEM_MOVEABLE. This function has no effect on memory objects allocated with GMEM_FIXED.

### Description
Note The global functions have greater overhead and provide fewer features than other memory management functions. New applications should use the <a href="https://docs.microsoft.com/en-in/windows/win32/memory/heap-functions" target="_blank">heap functions</a> unless documentation states that a global function should be used. For more information, see <a href="https://docs.microsoft.com/en-in/windows/win32/memory/global-and-local-functions"  target="_blank">Global and Local Functions</a>.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-globalunlock" target="_blank">here</a>


---

<SECTION ID="loadlibrarya">
</SECTION>
## LoadLibraryA
Loads the specified module into the address space of the calling process. The specified module may cause other modules to be loaded.

### Description
For additional load options, use the [LoadLibraryEx](#loadlibraryex) function.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/libloaderapi/nf-libloaderapi-loadlibrarya" target="_blank">here</a>



---

<SECTION ID="loadlibraryex">
</SECTION>
## LoadLibraryEx
Loads the specified module into the address space of the calling process. The specified module may cause other modules to be loaded.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/libloaderapi/nf-libloaderapi-loadlibraryexa" target="_blank">here</a>


---

<SECTION ID="loadresource">
</SECTION>
## LoadResource
Retrieves a handle that can be used to obtain a pointer to the first byte of the specified resource in memory.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/libloaderapi/nf-libloaderapi-loadresource" target="_blank">here</a>


---

<SECTION ID="lockresource">
</SECTION>
## LockResource
Retrieves a pointer to the specified resource in memory.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/libloaderapi/nf-libloaderapi-lockresource" target="_blank">here</a>



---

<SECTION ID="movefile">
</SECTION>
## MoveFile
Moves an existing file or a directory, including its children.

### Description
To specify how to move the file, use the MoveFileEx or MoveFileWithProgress function.<br>
To perform this operation as a transacted operation, use the MoveFileTransacted function.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-movefile" target="_blank">here</a>




---

<SECTION ID="openfile">
</SECTION>
## OpenFile
Creates, opens, reopens, or deletes a file. Note This function has limited capabilities and is not recommended. For new application development, use the CreateFile function.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-openfile" target="_blank">here</a>




---

<SECTION ID="openmutex">
</SECTION>
## OpenMutex
Opens an existing named mutex object.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/synchapi/nf-synchapi-openmutexw" target="_blank">here</a>




---

<SECTION ID="outputdebugstring">
</SECTION>
## OutputDebugString
Sends a string to the debugger for display.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/debugapi/nf-debugapi-outputdebugstringa" target="_blank">here</a>



---

<SECTION ID="purgecomm">
</SECTION>
## PurgeComm
Discards all characters from the output or input buffer of a specified communications resource. It can also terminate pending read or write operations on the resource.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-purgecomm" target="_blank">here</a>



---

<SECTION ID="releasemutex">
</SECTION>
## ReleaseMutex
Releases ownership of the specified mutex object.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/synchapi/nf-synchapi-releasemutex" target="_blank">here</a>



---

<SECTION ID="removedirectory">
</SECTION>
## RemoveDirectory
Deletes an existing empty directory. To perform this operation as a transacted operation, use the RemoveDirectoryTransacted function.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/fileapi/nf-fileapi-removedirectorya" target="_blank">here</a>



---

<SECTION ID="setcommstate">
</SECTION>
## SetCommState
Configures a communications device according to the specifications in a device-control block (a DCB structure). The function reinitializes all hardware and control settings, but it does not empty output or input queues.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-setcommstate" target="_blank">here</a>



---

<SECTION ID="setcommtimeouts">
</SECTION>
## SetCommTimeouts
Sets the time-out parameters for all read and write operations on a specified communications device.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-setcommtimeouts" target="_blank">here</a>



---

<SECTION ID="setenvironmentvariable">
</SECTION>
## SetEnvironmentVariable
Sets the contents of the specified environment variable for the current process.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/processenv/nf-processenv-setenvironmentvariablea" target="_blank">here</a>




---

<SECTION ID="setevent">
</SECTION>
## SetEvent
Sets the specified event object to the signaled state.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/synchapi/nf-synchapi-setevent" target="_blank">here</a>




---

<SECTION ID="setsystemtime">
</SECTION>
## SetSystemTime
Sets the current system time and date. The system time is expressed in Coordinated Universal Time (UTC).

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/sysinfoapi/nf-sysinfoapi-setsystemtime" target="_blank">here</a>



---

<SECTION ID="sizeofresource">
</SECTION>
## SizeofResource
Retrieves the size, in bytes, of the specified resource.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/libloaderapi/nf-libloaderapi-sizeofresource" target="_blank">here</a>




---

<SECTION ID="sleep">
</SECTION>
## Sleep
Suspends the execution of the current thread until the time-out interval elapses. To enter an alertable wait state, use the SleepEx function.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/synchapi/nf-synchapi-sleep" target="_blank">here</a>



---

<SECTION ID="tranmitcommchar">
</SECTION>
## TranmitCommChar
Transmits a specified character ahead of any pending data in the output buffer of the specified communications device.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-transmitcommchar" target="_blank">here</a>




---

<SECTION ID="updateresource">
</SECTION>
## UpdateResource
Adds, deletes, or replaces a resource in a portable executable (PE) file. There are some restrictions on resource updates in files that contain Resource Configuration (RC Config) data: language-neutral (LN) files and lan.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-updateresourcea" target="_blank">here</a>



---

<SECTION ID="waitcommevent">
</SECTION>
## WaitCommEvent
Waits for an event to occur for a specified communications device. The set of events that are monitored by this function is contained in the event mask associated with the device handle.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-waitcommevent" target="_blank">here</a>


---

<SECTION ID="waitforsingleobject">
</SECTION>
## WaitForSingleObject
Waits until the specified object is in the signaled state or the time-out interval elapses.

### Description
To enter an alertable wait state, use the WaitForSingleObjectEx function. To wait for multiple objects, use the WaitForMultipleObjects.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/synchapi/nf-synchapi-waitforsingleobject" target="_blank">here</a>



---

<SECTION ID="winexec">
</SECTION>
## WinExec
Runs the specified application. Note This function is provided only for compatibility with 16-bit Windows. Applications should use the CreateProcess function.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-winexec" target="_blank">here</a>


---

<SECTION ID="writeprivateprofilesection">
</SECTION>
## WritePrivateProfileSection
Replaces the keys and values for the specified section in an initialization file.

### Description
Note This function is provided only for compatibility with 16-bit versions of Windows. Applications should store initialization information in the registry.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-writeprivateprofilesectiona" target="_blank">here</a>



---


<SECTION ID="writeprivateprofilestring">
</SECTION>
## WritePrivateProfileString
Copies a string into the specified section of an initialization file.

### Description
Note This function is provided only for compatibility with 16-bit versions of Windows. Applications should store initialization information in the registry.

### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-writeprivateprofilestringa" target="_blank">here</a>



---

<SECTION ID="writeprofilestring">
</SECTION>
## WriteProfileString
Copies a string into the specified section of the Win.ini file. If Win.ini uses Unicode characters, the function writes Unicode characters to the file. Otherwise, the function writes ANSI characters.

### Description
Note This function is provided only for compatibility with 16-bit versions of Windows. Applications should store initialization information in the registry.


### Info
* **Category**: bsk api
* **DLL**: Kernel32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-writeprofilestringa" target="_blank">here</a>

---

</div>

</div>
