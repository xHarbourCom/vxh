---
layout: default
title: Windows Shell API
---

<div class="sidenav">

<div markdown="1">

[DragAcceptFiles](#dragacceptfiles)
[DragFinish](#dragfinish)
[DragQueryFile](#dragqueryfile)
[DragQueryPoint](#dragquerypoint)
[ExtractIcon](#extracticon)
[SHAppBarMessage](#shappbarmessage)
[ShellExecute](#shellexecute)
[Shell_NotifyIcon](#shell_notifyicon)
[SHGetFileInfo](#shgetfileinfo)
[SHGetFolderPath](#shgetfolderpath)
[SHGetFolderPathAndSubDir](#shgetfolderpathandsubdir)
[SHILCreateFromPath](#shilcreatefrompath)

</div>

</div>


<div class="right_main">

<div markdown="1">

Windows Shell API
====================

---

<SECTION ID="dragacceptfiles"></SECTION>
## DragAcceptFiles
Registers whether a window accepts dropped files.

### Info
* **Category**: WS API
* **DLL**: Shell32.dll (version 4.0 or later)
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/shellapi/nf-shellapi-dragacceptfiles" target="_blank">here</a>

---

<SECTION ID="dragfinish"></SECTION>
## DragFinish
Releases memory that the system allocated for use in transferring file names to the application.

### Info
* **Category**: WS API
* **DLL**: Shell32.dll (version 4.0 or later)
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/shellapi/nf-shellapi-dragfinish" target="_blank">here</a>

---

<SECTION ID="dragqueryfile"></SECTION>
## DragQueryFile
Retrieves the names of dropped files that result from a successful drag-and-drop operation.

### Info
* **Category**: WS API
* **DLL**: Shell32.dll (version 4.0 or later)
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/shellapi/nf-shellapi-dragqueryfilea" target="_blank">here</a>

---

<SECTION ID="dragquerypoint"></SECTION>
## DragQueryPoint
Retrieves the position of the mouse pointer at the time a file was dropped during a drag-and-drop operation.

### Info
* **Category**: WS API
* **DLL**: Shell32.dll (version 4.0 or later)
* **MSDN link**: <a href="https://docs.microsoft.com/en-us/windows/win32/api/shellapi/nf-shellapi-dragquerypoint" target="_blank">here</a>

---

<SECTION ID="extracticon"></SECTION>
## Extracticon
Retrieves a handle to an icon from the specified executable file, DLL, or icon file. To retrieve an array of handles to large or small icons, use the ExtractIconEx function.

### Info
* **Category**: WS API
* **DLL**: Shell32.dll (version 4.0 or later)
* **MSDN link**: <a href="https://docs.microsoft.com/en-us/windows/win32/api/shellapi/nf-shellapi-extracticona" target="_blank">here</a>

---

<SECTION ID="shappbarmessage"></SECTION>
## SHAppBarMessage
Sends an appbar message to the system.

### Info
* **Category**: WS API
* **DLL**: Shell32.dll (version 4.0 or later)
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/shellapi/nf-shellapi-shappbarmessage" target="_blank">here</a>

---

<SECTION ID="shellexecute"></SECTION>
## ShellExecute
Performs an operation on a specified file.

### Info
* **Category**: WS API
* **DLL**: Shell32.dll (version 4.0 or later)
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/shellapi/nf-shellapi-shellexecutea" target="_blank">here</a>

---

<SECTION ID="shell_notifyicon"></SECTION>
## Shell_NotifyIcon
Sends a message to the taskbar's status area.

### Info
* **Category**: WS API
* **DLL**: Shell32.dll (version 4.0 or later)
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/shellapi/nf-shellapi-shell_notifyicona" target="_blank">here</a>

---

<SECTION ID="shgetfileinfo"></SECTION>
## SHGetFileInfo
Retrieves information about an object in the file system, such as a file, folder, directory, or drive root.

### Info
* **Category**: WS API
* **DLL**: Shell32.dll (version 4.0 or later)
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/shellapi/nf-shellapi-shgetfileinfoa" target="_blank">here</a>

---

<SECTION ID="shgetfolderpath"></SECTION>
## SHGetFolderPath
Deprecated. Gets the path of a folder identified by a CSIDL value.

*Note: As of Windows Vista, this function is merely a wrapper for SHGetKnownFolderPath. The CSIDL value is translated to its associated KNOWNFOLDERID and then SHGetKnownFolderPath is called. New applications should use the known folder system rather than the older CSIDL system, which is supported only for backward compatibility.*

### Info
* **Category**: WS API
* **DLL**: Shell32.dll (version 4.0 or later)
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/shlobj_core/nf-shlobj_core-shgetfolderpatha" target="_blank">here</a>

---

<SECTION ID="shgetfolderpathandsubdir"></SECTION>
## SHGetFolderPathAndSubDir
Gets the path of a folder and appends a user-provided subfolder path.

### Info
* **Category**: WS API
* **DLL**: Shell32.dll (version 4.0 or later)
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/shlobj_core/nf-shlobj_core-shgetfolderpathandsubdira" target="_blank">here</a>

---

<SECTION ID="shilcreatefrompath"></SECTION>
## SHILCreateFromPath
Creates a pointer to an item identifier list (PIDL) from a path.

### Info
* **Category**: WS API
* **DLL**: Shell32.dll (version 4.0 or later)
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/shlobj_core/nf-shlobj_core-shilcreatefrompath" target="_blank">here</a>

---

</div>

</div>
