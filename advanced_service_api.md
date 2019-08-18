---
layout: default
title: Advanced service API
---

<div class="sidenav">

<div markdown="1">

[AdjustTokenPrivileges](#adjusttokenprivileges)
[CloseServiceHandle](#CloseServiceHandle)
[CreateService](#createservice)
[DeleteService](#deleteservice)
[GetUserName](#getusername)
[InitiateSystemShutdown](#initiatesystemshutdown)
[LookUpPrivilegeValue](#lookupprivilegevalue)
[OpenProcessToken](#openprocesstoken)
[OpenSCManager](#openscmanager)
[OpenService](#openservice)
[RegCloseKey](#regclosekey)
[RegCreateKey](#regcreatekey)
[RegCreateKeyEx](#regcreatekeyex)
[RegDeleteKey](#regdeletekey)
[RegDeleteValue](#regdeletevalue)
[RegEnumKey](#RegEnumKey)
[RegEnumKeyEx](#regenumkeyex)
[RegEnumValue](#regenumvalue)
[RegisterServiceCtrlHandler](#registerservicectrlhandler)
[RegOpenKeyEx](#regopenkeyex)
[RegQueryValueEx](#regqueryvalueex)
[RegSetValueEx](#regsetvalueex)
[SetServiceStatus](#setservicestatus)

</div>

</div>


<div class="right_main">

<div markdown="1">

Advanced Service API
====================

---


<SECTION ID="adjusttokenprivileges">
</SECTION>
## AdjustTokenPrivileges
The AdjustTokenPrivileges function enables or disables privileges in the specified access token. Enabling or disabling privileges in an access token requires TOKEN_ADJUST_PRIVILEGES access.<br>

### Info
* **Category**: adv api
* **DLL**: Advapi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/securitybaseapi/nf-securitybaseapi-adjusttokenprivileges" target="_blank">here</a>



---

<SECTION ID="closeservicehandle">
</SECTION>
## CloseServiceHandle
Closes a handle to a service control manager or service object.<br>

### Info
* **Category**: adv api
* **DLL**: Advapi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winsvc/nf-winsvc-closeservicehandle" target="_blank">here</a>


---

<SECTION ID="createservice">
</SECTION>
## CreateService
Creates a service object and adds it to the specified service control manager database.

### Info
* **Categor**y: adv api
* **DLL**: Advapi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winsvc/nf-winsvc-createservicea" target="_blank">here</a>


---

<SECTION ID="deleteservice">
</SECTION>
## DeleteService
Marks the specified service for deletion from the service control manager database.

### Info
* **Category**: adv api
* **DLL**: Advapi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-deleteservice" target="_blank">here</a>


---

<SECTION ID="getusername">
</SECTION>
## GetUserName
Retrieves the name of the user associated with the current thread. Use the GetUserNameEx function to retrieve the user name in a specified format. Additional information is provided by the IADsADSystemInfo interface.

### Info
* **Category**: adv api
* **DLL**: Advapi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-getusernamea" target="_blank">here</a>


---

<SECTION ID="initiatesystemshutdown">
</SECTION>
## InitiateSystemShutdown
Initiates a shutdown and optional restart of the specified computer. To record a reason for the shutdown in the event log, call the InitiateSystemShutdownEx function.

### Info
* **Category**: adv api
* **DLL**: Advapi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winreg/nf-winreg-initiatesystemshutdowna" target="_blank">here</a>


---

<SECTION ID="LookUpPrivilegeValue">
</SECTION>
## LookUpPrivilegeValue
The LookupPrivilegeValue function retrieves the locally unique identifier (LUID) used on a specified system to locally represent the specified privilege name.

### Info
* **Category**: adv api
* **DLL**: Advapi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-lookupprivilegevaluea" target="_blank">here</a>



---

<SECTION ID="openprocesstoken">
</SECTION>
## OpenProcessToken
The OpenProcessToken function opens the access token associated with a process.

### Info
* **Category**: adv api
* **DLL**: Advapi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/processthreadsapi/nf-processthreadsapi-openprocesstoken" target="_blank">here</a>

---

<SECTION ID="openscmanager">
</SECTION>
## OpenSCManager
Establishes a connection to the service control manager on the specified computer and opens the specified service control manager database.

### Info
* **Category**: adv api
* **DLL**: Advapi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winsvc/nf-winsvc-openscmanagera" target="_blank">here</a>


---

<SECTION ID="OpenService">
</SECTION>
## OpenService
Opens an existing service.

### Info
* **Category**: adv api
* **DLL**: Advapi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winsvc/nf-winsvc-openservicea" target="_blank">here</a>


---

<SECTION ID="regclosekey">
</SECTION>
## RegCloseKey
Closes a handle to the specified registry key.

### Info
* **Category**: adv api
* **DLL**: Advapi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winreg/nf-winreg-regclosekey" target="_blank">here</a>

---

<SECTION ID="regcreatekey">
</SECTION>
## RegCreateKey
Creates the specified registry key. If the key already exists in the registry, the function opens it.

### Description
Note This function is provided only for compatibility with 16-bit versions of Windows. Applications should use the RegCreateKeyEx function. However, applications that back up or restore system state including system files and registry hives should use the Volume Shadow Copy Service instead of the registry functions.

### Info
* **Category**: adv api
* **DLL**: Advapi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winreg/nf-winreg-regcreatekeya" target="_blank">here</a>


---

<SECTION ID="regcreatekeyex">
</SECTION>
## RegCreateKeyEx
Creates the specified registry key. If the key already exists, the function opens it. Note that key names are not case sensitive.

### Description
To perform transacted registry operations on a key, call the RegCreateKeyTransacted function.<br>
Applications that back up or restore system state including system files and registry hives should use the Volume Shadow Copy Service instead of the registry functions.

### Info
* **Category**: adv api
* **DLL**: Advapi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winreg/nf-winreg-regcreatekeyexa" target="_blank">here</a>


---

<SECTION ID="regcreatekeyex">
</SECTION>
## RegDeleteKey
Deletes a subkey and its values. Note that key names are not case sensitive.

### Description
64-bit Windows: On WOW64, 32-bit applications view a registry tree that is separate from the registry tree that 64-bit applications view. To enable an application to delete an entry in the alternate registry view, use the RegDeleteKeyEx function.

### Info
* **Category**: adv api
* **DLL**: Advapi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winreg/nf-winreg-regdeletekeya" target="_blank">here</a>


---

<SECTION ID="regdeletevalue">
</SECTION>
## RegDeleteValue
Removes a named value from the specified registry key. Note that value names are not case sensitive.

### Info
* **Category**: adv api
* **DLL**: Advapi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winreg/nf-winreg-regdeletevaluea" target="_blank">here</a>


---

<SECTION ID="regenumkey">
</SECTION>
## RegEnumKey
Enumerates the subkeys of the specified open registry key. The function retrieves the name of one subkey each time it is called.

### Description
Note This function is provided only for compatibility with 16-bit versions of Windows. Applications should use the [RegEnumKeyEx](#regenumkeyex "RegEnumKeyEx") function.

### Info
* **Category**: adv api
* **DLL**: Advapi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winreg/nf-winreg-regenumkeya" target="_blank">here</a>


---

<SECTION ID="regenumkeyex">
</SECTION>
## RegEnumKeyEx
Enumerates the subkeys of the specified open registry key. The function retrieves information about one subkey each time it is called.

### Info
* **Category**: adv api
* **DLL**: Advapi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winreg/nf-winreg-regenumkeyexa" target="_blank">here</a>

---

<SECTION ID="regenumvalue">
</SECTION>
## RegEnumValue
Enumerates the values for the specified open registry key. The function copies one indexed value name and data block for the key each time it is called.

### Info
* **Category**: adv api
* **DLL**: Advapi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winreg/nf-winreg-regenumvaluea" target="_blank">here</a>

---

<SECTION ID="registerservicectrlhandler">
</SECTION>
## RegisterServiceCtrlHandler
Registers a function to handle service control requests.

### Description
This function has been superseded by the RegisterServiceCtrlHandlerEx function. A service can use either function, but the new function supports user-defined context data, and the new handler function supports additional extended control codes.

### Info
* **Category**: adv api
* **DLL**: Advapi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winsvc/nf-winsvc-registerservicectrlhandlera" target="_blank">here</a>


---

<SECTION ID="regopenkeyex">
</SECTION>
## RegOpenKeyEx
Opens the specified registry key. Note that key names are not case sensitive. To perform transacted registry operations on a key, call the RegOpenKeyTransacted function.

### Info
* **Category**: adv api
* **DLL**: Advapi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winreg/nf-winreg-regopenkeyexa" target="_blank">here</a>


---

<SECTION ID="regqueryvalueex">
</SECTION>
## RegQueryValueEx
Retrieves the type and data for the specified value name associated with an open registry key.

### Description
To ensure that any string values (REG_SZ, REG_MULTI_SZ, and REG_EXPAND_SZ) returned are null-terminated, use the RegGetValue function.

### Info
* **Category**: adv api
* **DLL**: Advapi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winreg/nf-winreg-regqueryvalueexa" target="_blank">here</a>


---

<SECTION ID="regsetvalueex">
</SECTION>
## RegSetValueEx
Sets the data and type of a specified value under a registry key.

### Info
* **Category**: adv api
* **DLL**: Advapi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winreg/nf-winreg-regsetvalueexa" target="_blank">here</a>


---

<SECTION ID="setservicestatus">
</SECTION>
## SetServiceStatus
Updates the service control manager's status information for the calling service.

### Info
* **Category**: adv api
* **DLL**: Advapi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winsvc/nf-winsvc-setservicestatus" target="_blank">here</a>

---
</div>

</div>