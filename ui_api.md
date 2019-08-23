---
layout: default
title: User Interface API
---


<div class="sidenav">

<div markdown="1">

[AnimateWindow](#animatewindow)
[AppendMenu](#appendmenu)
[BeginPaint](#beginpaint)
[BeginUpdateResource](#beginupdateresource)
[BringWindowToTop](#bringwindowtotop)
[CallNextHookEx](#callnexthookex)
[CallWindowProc](#callwindowproc)
[CheckDlgButton](#checkdlgbutton)
[CheckMenuItem](#checkmenuitem)
[CheckRadioButton](#checkradiobutton)
[ChildWindowFromPoint](#childwindowfrompoint)
[ChildWindowFromPointEx](#childwindowfrompointex)
[ClientToScreen](#clienttoscreen)
[ClipCursor](#clipcursor)
[CloseClipboard](#closeclipboard)
[CopyIcon](#copyicon)
[CopyImage](#copyimage)
[CreateAcceleratorTable](#createacceleratortable)
[CreateCaret](#createcaret)
[CreateDialog](#createdialog)
[CreateDialogIndirect](#createdialogindirect)
[CreateMDIWindow](#createmdiwindow)
[CreateMenu](#createmenu)
[CreatePopupMenu](#createpopupmenu)
[CreateWindow](#createwindow)
[CreateWindowEx](#createwindowex)
[DefDlgProc](#defdlgproc)
[DefDlgProcPointer](#defdlgprocpointer)
[DeferWindowPos](#deferwindowpos)
[DefFrameProcAddress](#defframeprocaddress)
[DefMDIChildProc](#defmdichildproc)
[DefWindowProc](#defwindowproc)
[DeleteMenu](#deletemenu)
[DestroyAcceleratorTable](#destroyacceleratortable)
[DestroyCaret](#destroycaret)
[DestroyIcon](#destroyicon)
[DestroyMenu](#destroymenu)
[DestroyWindow](#destroywindow)
[DialogBox](#dialogbox)
[DialogBoxIndirect](#dialogboxindirect)
[DispatchMessage](#dispatchmessage)
[DrawCaption](#drawcaption)
[DrawEdge](#drawedge)
[DrawFocusRect](#drawfocusrect)
[DrawFrameControl](#drawframecontrol)
[DrawIcon](#drawicon)
[DrawIconEx](#drawiconex)
[DrawState](#drawstate)
[DrawText](#drawtext)
[EmptyClipboard](#emptyclipboard)
[EnableMenuItem](#enablemenuitem)
[EnableWindow](#enablewindow)
[EndDeferWindowPos](#enddeferwindowpos)
[EndDialog](#enddialog)
[EndMenu](#endmenu)
[EndPaint](#endpaint)
[EndTask](#endtask)
[EnumChildWindows](#enumchildwindows)
[ExitWindowsEx](#exitwindowsex)
[FillRect](#fillrect)
[FindWindow](#findwindow)
[FindWindowEx](#findwindowex)
[FrameRect](#framerect)
[GetActiveWindow](#getactivewindow)
[GetAncestor](#getancestor)
[GetASyncKeyState](#getasynckeystate)
[GetCapture](#getcapture)
[GetCaretPos](#getcaretpos)
[GetClassInfo](#getclassinfo)
[GetClassLong](#getclasslong)
[GetClassName](#getclassname)
[GetClientRect](#getclientrect)
[GetClipboardData](#getclipboarddata)
[GetCursor](#getcursor)
[GetCursorPos](#getcursorpos)
[GetDC](#getdc)
[GetDCEx](#getdcex)
[GetDesktopWindow](#getdesktopwindow)
[GetDialogBaseUnits](#getdialogbaseunits)
[GetDlgCtrlID](#getdlgctrlid)
[GetDlgItem](#getdlgitem)
[GetDlgItemInt](#getdlgitemint)
[GetDlgItemText](#getdlgitemtext)
[GetFocus](#getfocus)
[GetForegroundWindow](#getforegroundwindow)
[GetIconInfo](#geticoninfo)
[GetKeyState](#getkeystate)
[GetMenu](#getmenu)
[GetMenuInfo](#getmenuinfo)
[GetMenuItemCount](#getmenuitemcount)
[GetMenuItemID](#getmenuitemid)
[GetMenuItemInfo](#getmenuiteminfo)
[GetMenuState](#getmenustate)
[GetMenuString](#getmenustring)
[GetMessage](#getmessage)
[GetMessagePos](#getmessagepos)
[GetMonitorInfo](#getmonitorinfo)
[GetNextDlgTabItem](#getnextdlgtabitem)
[GetOpenClipboardWindow](#getopenclipboardwindow)
[GetParent](#getparent)
[GetProp](#getprop)
[GetScrollBarInfo](#getscrollbarinfo)
[GetScrollInfo](#getscrollinfo)
[GetSubMenu](#getsubmenu)
[GetSysColor](#getsyscolor)
[GetSysColorBrush](#getsyscolorbrush)
[GetSystemMenu](#getsystemmenu)
[GetSystemMetrics](#getsystemmetrics)
[GetWindow](#getwindow)
[GetWindowDC](#getwindowdc)
[GetWindowInfo](#getwindowinfo)
[GetWindowLong](#getwindowlong)
[GetWindowLongPtr](#getwindowlongptr)
[GetWindowPlacement](#getwindowplacement)
[GetWindowRect](#getwindowrect)
[GetWindowText](#getwindowtext)
[GetWindowTextLength](#getwindowtextlength)
[HideCaret](#hidecaret)
[HiliteMenuItem](#hilitemenuitem)
[InflateRect](#inflaterect)
[InsertMenu](#insertmenu)
[InsertMenuItem](#insertmenuitem)
[InvalidateRect](#invalidaterect)
[InvertRect](#invertrect)
[IsChild](#ischild)
[IsClipboardFormatAvailable](#isclipboardformatavailable)
[IsDialogMessage](#isdialogmessage)
[IsDlgButtonChecked](#isdlgbuttonchecked)
[IsHungAppWindow](#ishungappwindow)
[IsIconic](#isiconic)
[IsMenu](#ismenu)
[IsWindow](#iswindow)
[IsWindowEnabled](#iswindowenabled)
[IsWindowVisible](#iswindowvisible)
[KeyBD_Event](#keybd_event)
[KillTimer](#killtimer)
[LoadBitmap](#loadbitmap)
[LoadCursor](#loadcursor)
[LoadIcon](#loadicon)
[LoadImage](#loadimage)
[LoadMenu](#loadmenu)
[LockWindowUpdate](#lockwindowupdate)
[MapDialogRect](#mapdialogrect)
[MapVirtualKey](#mapvirtualkey)
[MapWindowPoints](#mapwindowpoints)
[MenuItemFromPoint](#menuitemfrompoint)
[MessageBeep](#messagebeep)
[MessageBox](#messagebox)
[ModifyMenu](#modifymenu)
[MoveWindow](#movewindow)
[OemToChar](#oemtochar)
[OffsetRect](#offsetrect)
[OpenClipboard](#openclipboard)
[PeekMessage](#peekmessage)
[PostMessage](#postmessage)
[PostQuitMessage](#postquitmessage)
[PtInRect](#ptinrect)
[RealChildWindowFromPoint](#realchildwindowfrompoint)
[RedrawWindow](#redrawwindow)
[RegisterClass](#registerclass)
[RegisterClassEx](#registerclassex)
[RegisterHotkey](#registerhotkey)
[RegisterWindowMessage](#registerwindowmessage)
[ReleaseCapture](#releasecapture)
[ReleaseDC](#releasedc)
[RemoveMenu](#removemenu)
[RemoveProp](#removeprop)
[ScreenToClient](#screentoclient)
[ScrollWindow](#scrollwindow)
[ScrollWindowEx](#scrollwindowex)
[SendDlgItemMessage](#senddlgitemmessage)
[SendMessage](#sendmessage)
[SendMessageCallBack](#sendmessagecallback)
[SendMessageTimeout](#sendmessagetimeout)
[SetActiveWindow](#setactivewindow)
[SetCapture](#setcapture)
[SetCaretPos](#setcaretpos)
[SetClassLong](#setclasslong)
[SetClipboardData](#setclipboarddata)
[SetCursor](#setcursor)
[SetCursorPos](#setcursorpos)
[SetDlgItemInt](#setdlgitemint)
[SetDlgItemText](#setdlgitemtext)
[SetFocus](#setfocus)
[SetForegroundWindow](#setforegroundwindow)
[SetLayeredWindowAttributes](#setlayeredwindowattributes)
[SetMenu](#setmenu)
[SetMenuDefaultItem](#setmenudefaultitem)
[SetMenuInfo](#setmenuinfo)
[SetMenuItemBitmaps](#setmenuitembitmaps)
[SetMenuItemInfo](#setmenuiteminfo)
[SetParent](#setparent)
[SetProp](#setprop)
[SetScrollInfo](#setscrollinfo)
[SetTimer](#settimer)
[SetWindowLong](#setwindowlong)
[SetWindowLongPtr](#setwindowlongptr)
[SetWindowPlacement](#setwindowplacement)
[SetWindowPos](#setwindowpos)
[SetWindowRgn](#setwindowrgn)
[SetWindowText](#setwindowtext)
[ShowCaret](#showcaret)
[ShowWindow](#showwindow)
[SwitchToThisWindow](#switchtothiswindow)
[SystemParametersInfo](#systemparametersinfo)
[TrackMouseEvent](#trackmouseevent)
[TrackPopupMenu](#trackpopupmenu)
[TranslateAccelerator](#translateaccelerator)
[TranslateMDISysAccel](#translatemdisysaccel)
[TranslateMessage](#translatemessage)
[UnRegisterClass](#unregisterclass)
[UpdateWindow](#updatewindow)
[ValidateRect](#validaterect)
[WindowFromDC](#windowfromdc)
[WindowFromPoint](#windowfrompoint)

</div>

</div>


<div class="right_main">

<div markdown="1">




User Interface API
====================

---

<SECTION ID="animatewindow"></SECTION>
## AnimateWindow
Enables you to produce special effects when showing or hiding windows. There are four types of animation: roll, slide, collapse or expand, and alpha-blended fade.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-animatewindow" target="_blank">here</a>

---

<SECTION ID="appendmenu"></SECTION>
## AppendMenu
Appends a new item to the end of the specified menu bar, drop-down menu, submenu, or shortcut menu. You can use this function to specify the content, appearance, and behavior of the menu item.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-appendmenua" target="_blank">here</a>

---

<SECTION ID="beginpaint"></SECTION>
## BeginPaint
The BeginPaint function prepares the specified window for painting and fills a PAINTSTRUCT structure with information about the painting.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-beginpaint" target="_blank">here</a>

---

<SECTION ID="beginupdateresource"></SECTION>
## BeginUpdateResource
Retrieves a handle that can be used by the UpdateResource function to add, delete, or replace resources in a binary module.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winbase/nf-winbase-beginupdateresourcea" target="_blank">here</a>

---

<SECTION ID="bringwindowtotop"></SECTION>
## BringWindowToTop
Brings the specified window to the top of the Z order. If the window is a top-level window, it is activated. If the window is a child window, the top-level parent window associated with the child window is activated.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-bringwindowtotop" target="_blank">here</a>

---

<SECTION ID="callnexthookex"></SECTION>
## CallNextHookEx
Passes the hook information to the next hook procedure in the current hook chain. A hook procedure can call this function either before or after processing the hook information.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-callnexthookex" target="_blank">here</a>

---

<SECTION ID="callwindowproc"></SECTION>
## CallWindowProc
Passes message information to the specified window procedure.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-callwindowproca" target="_blank">here</a>

---

<SECTION ID="checkdlgbutton"></SECTION>
## CheckDlgButton
Changes the check state of a button control.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-checkdlgbutton" target="_blank">here</a>

---

<SECTION ID="checkmenuitem"></SECTION>
## CheckMenuItem
Sets the state of the specified menu item's check-mark attribute to either selected or clear.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-checkmenuitem" target="_blank">here</a>

---

<SECTION ID="checkradiobutton"></SECTION>
## CheckRadioButton
Adds a check mark to (checks) a specified radio button in a group and removes a check mark from (clears) all other radio buttons in the group.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-checkradiobutton" target="_blank">here</a>

---

<SECTION ID="childwindowfrompoint"></SECTION>
## ChildWindowFromPoint
Determines which, if any, of the child windows belonging to a parent window contains the specified point. The search is restricted to immediate child windows. Grandchildren, and deeper descendant windows are not searched.

### Description
To skip certain child windows, use the ChildWindowFromPointEx function.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-childwindowfrompoint" target="_blank">here</a>

---

<SECTION ID="childwindowfrompointex"></SECTION>
## ChildWindowFromPointEx
Determines which, if any, of the child windows belonging to the specified parent window contains the specified point. The function can ignore invisible, disabled, and transparent child windows. The search is restricted to immediate child windows. Grandchildren and deeper descendants are not searched.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-childwindowfrompointex" target="_blank">here</a>

---

<SECTION ID="clienttoscreen"></SECTION>
## ClientToScreen
The ClientToScreen function converts the client-area coordinates of a specified point to screen coordinates.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-clienttoscreen" target="_blank">here</a>

---

<SECTION ID="clipcursor"></SECTION>
## ClipCursor
Confines the cursor to a rectangular area on the screen. If a subsequent cursor position (set by the SetCursorPos function or the mouse) lies outside the rectangle, the system automatically adjusts the position to keep the cursor inside the rectangular area.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-clipcursor" target="_blank">here</a>

---

<SECTION ID="closeclipboard"></SECTION>
## CloseClipboard
Closes the clipboard.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-closeclipboard" target="_blank">here</a>

---

<SECTION ID="copyicon"></SECTION>
## CopyIcon
Copies the specified icon from another module to the current module.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-copyicon" target="_blank">here</a>

---

<SECTION ID="copyimage"></SECTION>
## CopyImage
Creates a new image (icon, cursor, or bitmap) and copies the attributes of the specified image to the new one. If necessary, the function stretches the bits to fit the desired size of the new image.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-copyimage" target="_blank">here</a>

---

<SECTION ID="createacceleratortable"></SECTION>
## CreateAcceleratorTable
Creates an accelerator table.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-createacceleratortablea" target="_blank">here</a>

---

<SECTION ID="CreateCaret"></SECTION>
## CreateCaret
Creates a new shape for the system caret and assigns ownership of the caret to the specified window. The caret shape can be a line, a block, or a bitmap.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-createcaret" target="_blank">here</a>

---

<SECTION ID="createdialog"></SECTION>
## CreateDialog
Creates a modeless dialog box from a dialog box template resource. The CreateDialog macro uses the CreateDialogParam function.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-createdialoga" target="_blank">here</a>

---

<SECTION ID="createdialogindirect"></SECTION>
## CreateDialogIndirect
Creates a modeless dialog box from a dialog box template in memory. The CreateDialogIndirect macro uses the CreateDialogIndirectParam function.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-createdialogindirecta" target="_blank">here</a>

---

<SECTION ID="createmdiwindow"></SECTION>
## CreateMDIWindow
Creates a multiple-document interface (MDI) child window.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-createmdiwindowa" target="_blank">here</a>

---

<SECTION ID="createmenu"></SECTION>
## CreateMenu
Creates a menu. The menu is initially empty, but it can be filled with menu items by using the InsertMenuItem, AppendMenu, and InsertMenu functions.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-createmenu" target="_blank">here</a>

---

<SECTION ID="createpopupmenu"></SECTION>
## CreatePopupMenu
Creates a drop-down menu, submenu, or shortcut menu. The menu is initially empty. You can insert or append menu items by using the InsertMenuItem function. You can also use the InsertMenu function to insert menu items and the AppendMenu function to append menu items.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-createpopupmenu" target="_blank">here</a>

---

<SECTION ID="createwindow"></SECTION>
## CreateWindow
Creates an overlapped, pop-up, or child window. It specifies the window class, window title, window style, and (optionally) the initial position and size of the window. The function also specifies the window's parent or owner, if any, and the window's menu.

### Description
To use extended window styles in addition to the styles supported by CreateWindow, use the CreateWindowEx function.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-createwindowa" target="_blank">here</a>

---

<SECTION ID="createwindowex"></SECTION>
## CreateWindowEx
Creates an overlapped, pop-up, or child window with an extended window style; otherwise, this function is identical to the CreateWindow function. For more information about creating a window and for full descriptions of the other parameters of CreateWindowEx, see CreateWindow.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-createwindowexa" target="_blank">here</a>

---

<SECTION ID="defdlgproc"></SECTION>
## DefDlgProc
Calls the default dialog box window procedure to provide default processing for any window messages that a dialog box with a private window class does not process.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-defdlgprocw" target="_blank">here</a>

---

<SECTION ID="defdlgprocpointer"></SECTION>
## DefDlgProcPointer
Application-defined callback function used with the CreateDialog and DialogBox families of functions. It processes messages sent to a modal or modeless dialog box. The DLGPROC type defines a pointer to this callback function. DialogProc is a placeholder for the application-defined function name.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-us/windows/win32/api/winuser/nc-winuser-dlgproc" target="_blank">here</a>

---

<SECTION ID="deferwindowpos"></SECTION>
## DeferWindowPos
Updates the specified multiple-window – position structure for the specified window. The function then returns a handle to the updated structure. The EndDeferWindowPos function uses the information in this structure to change the position and size of a number of windows simultaneously. The BeginDeferWindowPos function creates the structure.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-deferwindowpos" target="_blank">here</a>

---

<SECTION ID="defframeprocaddress"></SECTION>
## DefFrameProcAddress
Provides default processing for any window messages that the window procedure of a multiple-document interface (MDI) frame window does not process. All window messages that are not explicitly processed by the window procedure must be passed to the DefFrameProc function, not the DefWindowProc function.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-defframeproca" target="_blank">here</a>

---

<SECTION ID="defmdichildproc"></SECTION>
## DefMDIChildProc
Provides default processing for any window message that the window procedure of a multiple-document interface (MDI) child window does not process. A window message not processed by the window procedure must be passed to the DefMDIChildProc function, not to the DefWindowProc function.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-defmdichildproca" target="_blank">here</a>

---

<SECTION ID="defwindowproc"></SECTION>
## DefWindowProc
Calls the default window procedure to provide default processing for any window messages that an application does not process. This function ensures that every message is processed. DefWindowProc is called with the same parameters received by the window procedure.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-defwindowproca" target="_blank">here</a>

---

<SECTION ID="deletemenu"></SECTION>
## DeleteMenu
Deletes an item from the specified menu. If the menu item opens a menu or submenu, this function destroys the handle to the menu or submenu and frees the memory used by the menu or submenu.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-deletemenu" target="_blank">here</a>

---

<SECTION ID="destroyacceleratortable"></SECTION>
## DestroyAcceleratorTable
Destroys an accelerator table.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-destroyacceleratortable" target="_blank">here</a>

---

<SECTION ID="destroycaret"></SECTION>
## DestroyCaret
Destroys the caret's current shape, frees the caret from the window, and removes the caret from the screen.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-destroycaret" target="_blank">here</a>

---

<SECTION ID="destroyicon"></SECTION>
## DestroyIcon
Destroys an icon and frees any memory the icon occupied.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-destroyicon" target="_blank">here</a>

---

<SECTION ID="destroymenu"></SECTION>
## DestroyMenu
Destroys the specified menu and frees any memory that the menu occupies.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-destroymenu" target="_blank">here</a>

---

<SECTION ID="destroywindow"></SECTION>
## DestroyWindow
Destroys the specified window. The function sends WM_DESTROY and WM_NCDESTROY messages to the window to deactivate it and remove the keyboard focus from it. The function also destroys the window's menu, flushes the thread message queue, destroys timers, removes clipboard ownership, and breaks the clipboard viewer chain (if the window is at the top of the viewer chain).

### Description 
If the specified window is a parent or owner window, DestroyWindow automatically destroys the associated child or owned windows when it destroys the parent or owner window. The function first destroys child or owned windows, and then it destroys the parent or owner window.<br>
DestroyWindow also destroys modeless dialog boxes created by the CreateDialog function.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-destroywindow" target="_blank">here</a>

---

<SECTION ID="dialogbox"></SECTION>
## DialogBox
Creates a modal dialog box from a dialog box template resource. DialogBox does not return control until the specified callback function terminates the modal dialog box by calling the EndDialog function. DialogBox is implemented as a call to the DialogBoxParam function.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-dialogboxa" target="_blank">here</a>

---

<SECTION ID="dialogboxindirect"></SECTION>
## DialogBoxIndirect
Creates a modal dialog box from a dialog box template in memory. DialogBoxIndirect does not return control until the specified callback function terminates the modal dialog box by calling the EndDialog function. DialogBoxIndirect is implemented as a call to the DialogBoxIndirectParam function.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-dialogboxindirecta" target="_blank">here</a>

---

<SECTION ID="dispatchmessage"></SECTION>
## DispatchMessage
Dispatches a message to a window procedure. It is typically used to dispatch a message retrieved by the GetMessage function.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-dispatchmessage" target="_blank">here</a>

---

<SECTION ID="drawcaption"></SECTION>
## DrawCaption
The DrawCaption function draws a window caption.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-drawcaption" target="_blank">here</a>

---

<SECTION ID="drawedge"></SECTION>
## DrawEdge
The DrawEdge function draws one or more edges of rectangle.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-drawedge" target="_blank">here</a>

---

<SECTION ID="drawfocusrect"></SECTION>
## DrawFocusRect
The DrawFocusRect function draws a rectangle in the style used to indicate that the rectangle has the focus.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-drawfocusrect" target="_blank">here</a>

---

<SECTION ID="drawframecontrol"></SECTION>
## DrawFrameControl
The DrawFrameControl function draws a frame control of the specified type and style.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-drawframecontrol" target="_blank">here</a>

---

<SECTION ID="drawicon"></SECTION>
## DrawIcon
Draws an icon or cursor into the specified device context. To specify additional drawing options, use the DrawIconEx function.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-drawicon" target="_blank">here</a>

---

<SECTION ID="drawiconex"></SECTION>
## DrawIconEx
Draws an icon or cursor into the specified device context, performing the specified raster operations, and stretching or compressing the icon or cursor as specified.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-drawiconex" target="_blank">here</a>

---

<SECTION ID="drawstate"></SECTION>
## DrawState
The DrawState function displays an image and applies a visual effect to indicate a state, such as a disabled or default state.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-drawstatea" target="_blank">here</a>

---

<SECTION ID="drawtext"></SECTION>
## DrawText
The DrawText function draws formatted text in the specified rectangle. It formats the text according to the specified method (expanding tabs, justifying characters, breaking lines, and so forth).

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-drawtext" target="_blank">here</a>

---

<SECTION ID="emptyclipboard"></SECTION>
## EmptyClipboard
Empties the clipboard and frees handles to data in the clipboard. The function then assigns ownership of the clipboard to the window that currently has the clipboard open.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-emptyclipboard" target="_blank">here</a>

---

<SECTION ID="enablemenuitem"></SECTION>
## EnableMenuItem
Enables, disables, or grays the specified menu item.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-enablemenuitem" target="_blank">here</a>

---

<SECTION ID="enablewindow"></SECTION>
## EnableWindow
Enables or disables mouse and keyboard input to the specified window or control. When input is disabled, the window does not receive input such as mouse clicks and key presses. When input is enabled, the window receives all input.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-enablewindow" target="_blank">here</a>

---

<SECTION ID="enddeferwindowpos"></SECTION>
## EndDeferWindowPos
Simultaneously updates the position and size of one or more windows in a single screen-refreshing cycle.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-enddeferwindowpos" target="_blank">here</a>

---

<SECTION ID="enddialog"></SECTION>
## EndDialog
Destroys a modal dialog box, causing the system to end any processing for the dialog box.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-enddialog" target="_blank">here</a>

---

<SECTION ID="endmenu"></SECTION>
## EndMenu
Ends the calling thread's active menu.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-endmenu" target="_blank">here</a>

---

<SECTION ID="endpaint"></SECTION>
## EndPaint
The EndPaint function marks the end of painting in the specified window. This function is required for each call to the BeginPaint function, but only after painting is complete.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-endpaint" target="_blank">here</a>

---

<SECTION ID="endtask"></SECTION>
## EndTask
\[This function is not intended for general use. It may be altered or unavailable in subsequent versions of Windows.\]
Forcibly closes the specified window.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-endtask" target="_blank">here</a>

---

<SECTION ID="enumchildwindows"></SECTION>
## EnumChildWindows
Enumerates the child windows that belong to the specified parent window by passing the handle to each child window, in turn, to an application-defined callback function. EnumChildWindows continues until the last child window is enumerated or the callback function returns FALSE.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-enumchildwindows" target="_blank">here</a>

---

<SELECT ID="enumdisplaymonitors"></SELECT>
## EnumDisplayMonitors
The EnumDisplayMonitors function enumerates display monitors (including invisible pseudo-monitors associated with the mirroring drivers) that intersect a region formed by the intersection of a specified clipping rectangle and the visible region of a device context. EnumDisplayMonitors calls an application-defined MonitorEnumProc callback function once for each monitor that is enumerated. Note that GetSystemMetrics (SM_CMONITORS) counts only the display monitors.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-enumdisplaymonitors" target="_blank">here</a>

---

<SECTION ID="exitwindowex"></SECTION>
## ExitWindowEx
Logs off the interactive user, shuts down the system, or shuts down and restarts the system. It sends the WM_QUERYENDSESSION message to all applications to determine if they can be terminated.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-exitwindowsex" target="_blank">here</a>

---

<SECTION ID="fillrect"></SECTION>
## FillRect
The FillRect function fills a rectangle by using the specified brush. This function includes the left and top borders, but excludes the right and bottom borders of the rectangle.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-fillrect" target="_blank">here</a>

---

<SECTION ID="findwindow"></SECTION>
## FindWindow
Retrieves a handle to the top-level window whose class name and window name match the specified strings. This function does not search child windows. This function does not perform a case-sensitive search. To search child windows, beginning with a specified child window, use the FindWindowEx function.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-findwindowa" target="_blank">here</a>

---

<SECTION ID="findwindowex"></SECTION>
## FindWindowEx
Retrieves a handle to a window whose class name and window name match the specified strings. The function searches child windows, beginning with the one following the specified child window. This function does not perform a case-sensitive search.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-findwindowexa" target="_blank">here</a>

---

<SECTION ID="framerect"></SECTION>
## FrameRect
The FrameRect function draws a border around the specified rectangle by using the specified brush. The width and height of the border are always one logical unit.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-framerect" target="_blank">here</a>

---
 
<SECTION ID="getactivewindow"></SECTION>
## GetActiveWindow
Retrieves the window handle to the active window attached to the calling thread's message queue.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getactivewindow" target="_blank">here</a>

---

<SECTION ID="getancestor"></SECTION>
## GetAncestor
Retrieves the handle to the ancestor of the specified window.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getancestor" target="_blank">here</a>

---

<SECTION ID="getasynckeystate"></SECTION>
## GetASyncKeyState
Determines whether a key is up or down at the time the function is called, and whether the key was pressed after a previous call to GetAsyncKeyState.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getasynckeystate" target="_blank">here</a>

---

<SECTION ID="getcapture"></SECTION>
## GetCapture
Retrieves a handle to the window (if any) that has captured the mouse. Only one window at a time can capture the mouse; this window receives mouse input whether or not the cursor is within its borders.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getcapture" target="_blank">here</a>

---

<SECTION ID="getcaretpos"></SECTION>
## GetCaretPos
Copies the caret's position to the specified POINT structure.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getcaretpos" target="_blank">here</a>

---

<SECTION ID="getclassinfo"></SECTION>
## GetClassInfo
Retrieves information about a window class. Note The GetClassInfo function has been superseded by the GetClassInfoEx function. You can still use GetClassInfo, however, if you do not need information about the class small icon.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getclassinfoa" target="_blank">here</a>

---

<SECTION ID="getclasslong"></SECTION>
## GetClassLong
Retrieves the specified 32-bit (DWORD) value from the WNDCLASSEX structure associated with the specified window. Note If you are retrieving a pointer or a handle, this function has been superseded by the GetClassLongPtr function. (Pointers and handles are 32 bits on 32-bit Windows and 64 bits on 64-bit Windows.)

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getclasslonga" target="_blank">here</a>

---

<SECTION ID="getclassname"></SECTION>
## GetClassName
Retrieves the name of the class to which the specified window belongs.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getclassname" target="_blank">here</a>

---

<SECTION ID="getclientrect"></SECTION>
## GetClientRect
Retrieves the coordinates of a window's client area. The client coordinates specify the upper-left and lower-right corners of the client area. Because client coordinates are relative to the upper-left corner of a window's client area, the coordinates of the upper-left corner are (0,0).

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getclientrect" target="_blank">here</a>

---

<SECTION ID="getclipboarddata"></SECTION>
## GetClipboardData
Retrieves data from the clipboard in a specified format. The clipboard must have been opened previously.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getclipboarddata" target="_blank">here</a>

---

<SECTION ID="getcursor"></SECTION>
## GetCursor
Retrieves a handle to the current cursor. To get information on the global cursor, even if it is not owned by the current thread, use GetCursorInfo.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getcursor" target="_blank">here</a>

---

<SECTION ID="getcursorpos"></SECTION>
## GetCursorPos
Retrieves the cursor's position, in screen coordinates.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getcursorpos" target="_blank">here</a>

---

<SECTION ID="getdc"></SECTION>
## GetDC
The GetDC function retrieves a handle to a device context (DC) for the client area of a specified window or for the entire screen. You can use the returned handle in subsequent GDI functions to draw in the DC. The device context is an opaque data structure, whose values are used internally by GDI. The GetDCEx function is an extension to GetDC, which gives an application more control over how and whether clipping occurs in the client area.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getdc" target="_blank">here</a>

---

<SECTION ID="getdcex"></SECTION>
## GetDCEx
The GetDCEx function retrieves a handle to a device context (DC) for the client area of a specified window or for the entire screen. You can use the returned handle in subsequent GDI functions to draw in the DC. The device context is an opaque data structure, whose values are used internally by GDI. This function is an extension to the GetDC function, which gives an application more control over how and whether clipping occurs in the client area.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getdcex" target="_blank">here</a>

---

<SECTION ID="getdesktopwindow"></SECTION>
## GetDesktopWindow
Retrieves a handle to the desktop window. The desktop window covers the entire screen. The desktop window is the area on top of which other windows are painted.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getdesktopwindow" target="_blank">here</a>

---

<SECTION ID="getdialogbaseunits"></SECTION>
## GetDialogBaseUnits
Retrieves the system's dialog base units, which are the average width and height of characters in the system font. For dialog boxes that use the system font, you can use these values to convert between dialog template units, as specified in dialog box templates, and pixels. For dialog boxes that do not use the system font, the conversion from dialog template units to pixels depends on the font used by the dialog box. For either type of dialog box, it is easier to use the MapDialogRect function to perform the conversion. MapDialogRect takes the font into account and correctly converts a rectangle from dialog template units into pixels.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getdialogbaseunits" target="_blank">here</a>

---

<SECTION ID="getdlgctrlid"></SECTION>
## GetDlgCtrlID
Retrieves the identifier of the specified control.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getdlgctrlid" target="_blank">here</a>

---

<SECTION ID="GetDlgItem"></SECTION>
### GetDlgItem
Retrieves a handle to a control in the specified dialog box.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getdlgitem" target="_blank">here</a>

---

<SECTION ID="getdlgitemint"></SECTION>
## GetDlgitemint
Translates the text of a specified control in a dialog box into an integer value.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getdlgitemint" target="_blank">here</a>

---

<SECTION ID="getdlgitemtext"></SECTION>
## GetDlgItemText
Retrieves the title or text associated with a control in a dialog box.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getdlgitemtexta" target="_blank">here</a>

---

<SECTION ID="getfocus"></SECTION>
## GetFocus
Retrieves the handle to the window that has the keyboard focus, if the window is attached to the calling thread's message queue.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getfocus" target="_blank">here</a>

---

<SECTION ID="getforegroundwindow"></SECTION>
## GetForegroundWindow
Retrieves a handle to the foreground window (the window with which the user is currently working). The system assigns a slightly higher priority to the thread that creates the foreground window than it does to other threads.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getforegroundwindow" target="_blank">here</a>

---

<SECTION ID="geticoninfo"></SECTION>
## GetIconInfo
Retrieves information about the specified icon or cursor.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-geticoninfo" target="_blank">here</a>

---

<SECTION ID="getkeystate"></SECTION>
## GetKeyState
Retrieves the status of the specified virtual key. The status specifies whether the key is up, down, or toggled (on, off—alternating each time the key is pressed).

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getkeystate" target="_blank">here</a>

---

<SECTION ID="getmenu"></SECTION>
## GetMenu
Retrieves a handle to the menu assigned to the specified window.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getmenu" target="_blank">here</a>

---

<SECTION ID="getmenuinfo"></SECTION>
## GetMenuInfo
Retrieves information about a specified menu.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getmenuinfo" target="_blank">here</a>

---

<SECTION ID="getmenuitemcount"></SECTION>
## GetMenuItemCount
Determines the number of items in the specified menu.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getmenuitemcount" target="_blank">here</a>

---

<SECTION ID="getmenuitemid"></SECTION>
## GetMenuItemID
Retrieves the menu item identifier of a menu item located at the specified position in a menu.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getmenuitemid" target="_blank">here</a>

---

<SECTION id="getmenuiteminfo"></SECTION>
## GetMenuItemInfo
Retrieves information about a menu item.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getmenuiteminfoa" target="_blank">here</a>

---

<SECTION ID="getmenustate"></SECTION>
## GetMenuState
Retrieves the menu flags associated with the specified menu item. If the menu item opens a submenu, this function also returns the number of items in the submenu. Note The GetMenuState function has been superseded by the GetMenuItemInfo. You can still use GetMenuState, however, if you do not need any of the extended features of GetMenuItemInfo.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getmenustate" target="_blank">here</a>

---

<SECTION ID="getmenustring"></SECTION>
## GetMenuString
Copies the text string of the specified menu item into the specified buffer. Note The GetMenuString function has been superseded. Use the GetMenuItemInfo function to retrieve the menu item text

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getmenustringa" target="_blank">here</a>

---

<SECTION ID="getmesssage"></SECTION>
## GetMesssage
Retrieves a message from the calling thread's message queue. The function dispatches incoming sent messages until a posted message is available for retrieval. Unlike GetMessage, the PeekMessage function does not wait for a message to be posted before returning.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getmessage" target="_blank">here</a>

---

<SECTION ID="getmessagepos"></SECTION>
## GetMessagePos
Retrieves the cursor position for the last message retrieved by the GetMessage function. To determine the current position of the cursor, use the GetCursorPos function.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getmessagepos" target="_blank">here</a>

---

<SECTION ID="getmonitorinfo"></SECTION>
## GetMonitorInfo
The GetMonitorInfo function retrieves information about a display monitor.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getmonitorinfoa" target="_blank">here</a>

---

<SECTION ID="getnextdlgtabitem"></SECTION>
## GetNextDlgTabItem
Retrieves a handle to the first control that has the WS_TABSTOP style that precedes (or follows) the specified control.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getnextdlgtabitem" target="_blank">here</a>

---

<SECTION ID="getopenclipboardwindow"></SECTION>
## GetOpenClipboardWindow
Retrieves the handle to the window that currently has the clipboard open.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getopenclipboardwindow" target="_blank">here</a>

---

<SECTION ID="getparent"></SECTION>
## GetParent
Retrieves a handle to the specified window's parent or owner. To retrieve a handle to a specified ancestor, use the GetAncestor function.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getparent" target="_blank">here</a>

---

<SECTION ID="getprop"></SECTION>
## GetProp
Retrieves a data handle from the property list of the specified window. The character string identifies the handle to be retrieved. The string and handle must have been added to the property list by a previous call to the SetProp function.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getpropa" target="_blank">here</a>

---

<SECTION ID="getscrollbarinfo"></SECTION>
## GetScrollBarInfo
The GetScrollBarInfo function retrieves information about the specified scroll bar.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getscrollbarinfo" target="_blank">here</a>

---

<SECTION ID="getscrollinfo"></SECTION>
## GetScrollInfo
The GetScrollInfo function retrieves the parameters of a scroll bar, including the minimum and maximum scrolling positions, the page size, and the position of the scroll box (thumb).

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getscrollinfo" target="_blank">here</a>

---

<SECTION ID="getsubmenu"></SECTION>
## GetSubMenu
Retrieves a handle to the drop-down menu or submenu activated by the specified menu item.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getsubmenu" target="_blank">here</a>

---

<SECTION ID="getsyscolor"></SECTION>
## GetSysColor
Retrieves the current color of the specified display element. Display elements are the parts of a window and the display that appear on the system display screen.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getsyscolor" target="_blank">here</a>

---

<SECTION ID="GetSysColorBrush"></SECTION>
## GetSysColorBrush
The GetSysColorBrush function retrieves a handle identifying a logical brush that corresponds to the specified color index.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getsyscolorbrush" target="_blank">here</a>

---

<SECTION ID="getsystemmenu"></SECTION>
## GetSystemMenu
Enables the application to access the window menu (also known as the system menu or the control menu) for copying and modifying.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getsystemmenu" target="_blank">here</a>

---

<SECTION ID="getsystemmetrics"></SECTION>
## GetSystemMetrics
Retrieves the specified system metric or system configuration setting. Note that all dimensions retrieved by GetSystemMetrics are in pixels.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getsystemmetrics" target="_blank">here</a>

---

<SECTION ID="getwindow"></SECTION>
## GetWindow
Retrieves a handle to a window that has the specified relationship (Z-Order or owner) to the specified window.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getwindow" target="_blank">here</a>

---

<SECTION ID="getwindowdc"></SECTION>
## GetWindowDC
The GetWindowDC function retrieves the device context (DC) for the entire window, including title bar, menus, and scroll bars. A window device context permits painting anywhere in a window, because the origin of the device context is the upper-left corner of the window instead of the client area. GetWindowDC assigns default attributes to the window device context each time it retrieves the device context. Previous attributes are lost.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getwindowdc" target="_blank">here</a>

---

<SECTION ID="getwindowinfo"></SECTION>
## GetWindowInfo
Retrieves information about the specified window.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getwindowinfo" target="_blank">here</a>

---

<SECTION ID="getwindowlong"></SECTION>
## GetWindowLong
Retrieves information about the specified window. The function also retrieves the 32-bit (DWORD) value at the specified offset into the extra window memory.
Note If you are retrieving a pointer or a handle, this function has been superseded by the GetWindowLongPtr function. (Pointers and handles are 32 bits on 32-bit Windows and 64 bits on 64-bit Windows.) To write code that is compatible with both 32-bit and 64-bit versions of Windows, use GetWindowLongPtr.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getwindowlonga" target="_blank">here</a>

---

<SECTION ID="getwindowlongptr"></SECTION>
## GetWindowLongPtr
Retrieves information about the specified window. The function also retrieves the value at a specified offset into the extra window memory. Note To write code that is compatible with both 32-bit and 64-bit versions of Windows, use GetWindowLongPtr. When compiling for 32-bit Windows, GetWindowLongPtr is defined as a call to the GetWindowLong function.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getwindowlongptra" target="_blank">here</a>

---
 
<SECTION ID="getwindowplacement"></SECTION>
## GetWindowPlacement
Retrieves the show state and the restored, minimized, and maximized positions of the specified window.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getwindowplacement" target="_blank">here</a>

---

<SECTION ID="getwindowrect"></SECTION>
## GetWindowRect
Retrieves the dimensions of the bounding rectangle of the specified window. The dimensions are given in screen coordinates that are relative to the upper-left corner of the screen.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getwindowrect" target="_blank">here</a>

---

<SECTION ID="getwindowtext"></SECTION>
## GetWindowText
Copies the text of the specified window's title bar (if it has one) into a buffer. If the specified window is a control, the text of the control is copied. However, GetWindowText cannot retrieve the text of a control in another application.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getwindowtexta" target="_blank">here</a>

---

<SECTION ID="getwindowtextlength"></SECTION>
## GetWindowTextLength
Retrieves the length, in characters, of the specified window's title bar text (if the window has a title bar). If the specified window is a control, the function retrieves the length of the text within the control. However, GetWindowTextLength cannot retrieve the length of the text of an edit control in another application.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-getwindowtextlengtha" target="_blank">here</a>

---

<SECTION ID="hidecaret"></SECTION>
## HideCaret
Removes the caret from the screen. Hiding a caret does not destroy its current shape or invalidate the insertion point.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-hidecaret" target="_blank">here</a>

---

<SECTION ID="hilitemenuitem"></SECTION>
## HiliteMenuItem
Adds or removes highlighting from an item in a menu bar.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-hilitemenuitem" target="_blank">here</a>

---

<SECTION ID="inflaterect"></SECTION>
## InflateRect
The InflateRect function increases or decreases the width and height of the specified rectangle. The InflateRect function adds dx units to the left and right ends of the rectangle and dy units to the top and bottom. The dx and dy parameters are signed values; positive values increase the width and height, and negative values decrease them.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-inflaterect" target="_blank">here</a>

---

<SECTION ID="insertmenu"></SECTION>
## InsertMenu
Inserts a new menu item into a menu, moving other items down the menu. Note The InsertMenu function has been superseded by the InsertMenuItem function. You can still use InsertMenu, however, if you do not need any of the extended features of InsertMenuItem.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-insertmenua" target="_blank">here</a>

---

<SECTION ID="insertmenuitem"></SECTION>
## InsertMenuItem
Inserts a new menu item at the specified position in a menu.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-insertmenuitema" target="_blank">here</a>

---

<SECTION ID="invalidaterect"></SECTION>
## InvalidateRect
The InvalidateRect function adds a rectangle to the specified window's update region. The update region represents the portion of the window's client area that must be redrawn.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-invalidaterect" target="_blank">here</a>

---

<SECTION ID="invertrect"></SECTION>
## InvertRect
The InvertRect function inverts a rectangle in a window by performing a logical NOT operation on the color values for each pixel in the rectangle's interior.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-invertrect" target="_blank">here</a>

---

<SECTION ID="IsChild"></SECTION>
## IsChild
Determines whether a window is a child window or descendant window of a specified parent window. A child window is the direct descendant of a specified parent window if that parent window is in the chain of parent windows; the chain of parent windows leads from the original overlapped or pop-up window to the child window.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-ischild" target="_blank">here</a>

---

<SECTION ID="isclipboardformatavailable"></SECTION>
## IsClipboardFormatAvailable
Determines whether the clipboard contains data in the specified format.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-isclipboardformatavailable" target="_blank">here</a>

---

<SECTION ID="isdialogmessage"></SECTION>
## IsDialogMessage
Determines whether a message is intended for the specified dialog box and, if it is, processes the message.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-isdialogmessagea" target="_blank">here</a>

---

<SECTION ID="isdlgbuttonchecked"></SECTION>
## IsDlgButtonChecked
The IsDlgButtonChecked function determines whether a button control is checked or whether a three-state button control is checked, unchecked, or indeterminate.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-isdlgbuttonchecked" target="_blank">here</a>

---

<SECTION ID="ishungammwindow"></SECTION>
## IsHungAmmWindow
\[This function is not intended for general use. It may be altered or unavailable in subsequent versions of Windows.\] Determines whether the system considers that a specified application is not responding. An application is considered to be not responding if it is not waiting for input, is not in startup processing, and has not called PeekMessage within the internal timeout period of 5 seconds.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-ishungappwindow" target="_blank">here</a>

---

<SECTION ID="isiconic"></SECTION>
## IsIconic
Determines whether the specified window is minimized (iconic).

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-isiconic" target="_blank">here</a>

---

<SECTION ID="ismenu"></SECTION>
## IsMenu
Determines whether a handle is a menu handle.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-ismenu" target="_blank">here</a>

---

<SECTION ID="iswindow"></SECTION>
## IsWindow
Determines whether the specified window handle identifies an existing window.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-iswindow" target="_blank">here</a>

---

<SECTION ID="iswindowenabled"></SECTION>
## IsWindowEnabled
Determines whether the specified window is enabled for mouse and keyboard input.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-iswindowenabled" target="_blank">here</a>

---

<SECTION ID="iswindowvisible"></SECTION>
## IsWindowVisible
Determines the visibility state of the specified window.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-iswindowvisible" target="_blank">here</a>

---

<SECTION ID="keybd_event"></SECTION>
## KeyBD_Event
Synthesizes a keystroke. The system can use such a synthesized keystroke to generate a WM_KEYUP or WM_KEYDOWN message. The keyboard driver's interrupt handler calls the keybd_event function. Note This function has been superseded. Use SendInput instead.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-keybd_event" target="_blank">here</a>

---

<SECTION ID="killtimer"></SECTION>
## KillTimer
Destroys the specified timer.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-killtimer" target="_blank">here</a>

---

<SECTION ID="loadbitmap"></SECTION>
## LoadBitmap
\[LoadBitmap is available for use in the operating systems specified in the Requirements section. It may be altered or unavailable in subsequent versions. Instead, use LoadImage and DrawFrameControl.\] The LoadBitmap function loads the specified bitmap resource from a module's executable file.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-loadbitmapa" target="_blank">here</a>

---

<SECTION ID="loadcursor"></SECTION>
## LoadCursor
Loads the specified cursor resource from the executable (.EXE) file associated with an application instance. Note This function has been superseded by the LoadImage function.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-loadcursora" target="_blank">here</a>

---

<SECTION ID="loadicon"></SECTION>
## LoadIcon
Loads the specified icon resource from the executable (.exe) file associated with an application instance. Note This function has been superseded by the LoadImage function.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-loadicona" target="_blank">here</a>

---
 
<SECTION ID="loadimage"></SECTION>
## LoadImage
Loads an icon, cursor, animated cursor, or bitmap.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-loadimagea" target="_blank">here</a>

---

<SECTION ID="loadmenu"></SECTION>
## LoadMenu
Loads the specified menu resource from the executable (.exe) file associated with an application instance.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-loadmenua" target="_blank">here</a>

---

<SECTION ID="lockwindowupdate"></SECTION>
## LockWindowUpdate
The LockWindowUpdate function disables or enables drawing in the specified window. Only one window can be locked at a time.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-lockwindowupdate" target="_blank">here</a>

---

<SECTION ID="mapdialogrect"></SECTION>
## MapDialogRect
Converts the specified dialog box units to screen units (pixels). The function replaces the coordinates in the specified RECT structure with the converted coordinates, which allows the structure to be used to create a dialog box or position a control within a dialog box.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-mapdialogrect" target="_blank">here</a>

---

<SECTION ID="mapvirtualkey"></SECTION>
## MapVirtualKey
Translates (maps) a virtual-key code into a scan code or character value, or translates a scan code into a virtual-key code. To specify a handle to the keyboard layout to use for translating the specified code, use the MapVirtualKeyEx function.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-mapvirtualkeya" target="_blank">here</a>

---

<SECTION ID="mapwindowpointS"></SECTION>
## MapWindowPointS
The MapWindowPoints function converts (maps) a set of points from a coordinate space relative to one window to a coordinate space relative to another window.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-mapwindowpoints" target="_blank">here</a>

---

<SECTION ID="messagebeep"></SECTION>
## MessageBeep
Plays a waveform sound. The waveform sound for each sound type is identified by an entry in the registry.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-messagebeep" target="_blank">here</a>

---

<SECTION ID="messagebox"></SECTION>
## MessageBox
Displays a modal dialog box that contains a system icon, a set of buttons, and a brief application-specific message, such as status or error information. The message box returns an integer value that indicates which button the user clicked.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-messagebox" target="_blank">here</a>

---

<SECTION ID="modifymenu"></SECTION>
## ModifyMenu
Changes an existing menu item. This function is used to specify the content, appearance, and behavior of the menu item. Note The ModifyMenu function has been superseded by the SetMenuItemInfo function. You can still use ModifyMenu, however, if you do not need any of the extended features of SetMenuItemInfo.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-modifymenua" target="_blank">here</a>

---

<SECTION ID="movewindow"></SECTION>
## MoveWindow
Changes the position and dimensions of the specified window. For a top-level window, the position and dimensions are relative to the upper-left corner of the screen. For a child window, they are relative to the upper-left corner of the parent window's client area.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-movewindow" target="_blank">here</a>

---

<SECTION ID="oemtochar"></SECTION>
## OemToChar
Translates a string from the OEM-defined character set into either an ANSI or a wide-character string. Warning Do not use. See Security Considerations.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-oemtochara" target="_blank">here</a>

---

<SECTION ID="offsetrect"></SECTION>
## OffsetRect
The OffsetRect function moves the specified rectangle by the specified offsets.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-offsetrect" target="_blank">here</a>

---

<SECTION ID="openclipboard"></SECTION>
## OpenClipboard
Opens the clipboard for examination and prevents other applications from modifying the clipboard content.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-openclipboard" target="_blank">here</a>

---

<SECTION ID="peekmessage"></SECTION>
## PeekMessage
Dispatches incoming sent messages, checks the thread message queue for a posted message, and retrieves the message (if any exist).

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-peekmessagea" target="_blank">here</a>

---

<SECTION ID="postmessage"></SECTION>
## PostMessage
Places (posts) a message in the message queue associated with the thread that created the specified window and returns without waiting for the thread to process the message. To post a message in the message queue associated with a thread, use the PostThreadMessage function.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-postmessagea" target="_blank">here</a>

---

<SECTION ID="postquitmessage"></SECTION>
## PostQuitMessage
Indicates to the system that a thread has made a request to terminate (quit). It is typically used in response to a WM_DESTROY message.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-postquitmessage" target="_blank">here</a>

---

<SECTION ID="ptinrect"></SECTION>
## PtInRect
The PtInRect function determines whether the specified point lies within the specified rectangle. A point is within a rectangle if it lies on the left or top side or is within all four sides. A point on the right or bottom side is considered outside the rectangle.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-ptinrect" target="_blank">here</a>

---

<SECTION ID="realchildwindowfrompoint"></SECTION>
## RealChildWindowFromPoint
Retrieves a handle to the child window at the specified point. The search is restricted to immediate child windows; grandchildren and deeper descendant windows are not searched.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-realchildwindowfrompoint" target="_blank">here</a>

---

<SECTION ID="redrawwindow"></SECTION>
## RedrawWindow
The RedrawWindow function updates the specified rectangle or region in a window's client area.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-redrawwindow" target="_blank">here</a>

---

<SECTION ID="registerclass"></SECTION>
## RegisterClass
Registers a window class for subsequent use in calls to the CreateWindow or CreateWindowEx function. Note The RegisterClass function has been superseded by the RegisterClassEx function. You can still use RegisterClass, however, if you do not need to set the class small icon.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-registerclassa" target="_blank">here</a>

---

<SECTION ID="registerclassex"></SECTION>
## RegisterClassEx
Registers a window class for subsequent use in calls to the CreateWindow or CreateWindowEx function.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-registerclassexa" target="_blank">here</a>

---

<SECTION ID="registerhotkey"></SECTION>
## RegisterHotKey
Defines a system-wide hot key.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-registerhotkey" target="_blank">here</a>

---

<SECTION ID="registerwindowmessage"></SECTION>
## RegisterWindowMessage
Defines a new window message that is guaranteed to be unique throughout the system. The message value can be used when sending or posting messages.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-registerwindowmessagea" target="_blank">here</a>

---

<SECTION ID="releasecapture"></SECTION>
## ReleaseCapture
Releases the mouse capture from a window in the current thread and restores normal mouse input processing. A window that has captured the mouse receives all mouse input, regardless of the position of the cursor, except when a mouse button is clicked while the cursor hot spot is in the window of another thread.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-releasecapture" target="_blank">here</a>

---

<SECTION ID="releasedc"></SECTION>
## ReleaseDC
The ReleaseDC function releases a device context (DC), freeing it for use by other applications. The effect of the ReleaseDC function depends on the type of DC. It frees only common and window DCs. It has no effect on class or private DCs.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-releasedc" target="_blank">here</a>

---

<SECTION ID="removemenu"></SECTION>
## RemoveMenu
Deletes a menu item or detaches a submenu from the specified menu. If the menu item opens a drop-down menu or submenu, RemoveMenu does not destroy the menu or its handle, allowing the menu to be reused. Before this function is called, the GetSubMenu function should retrieve a handle to the drop-down menu or submenu.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-removemenu" target="_blank">here</a>

---

<SECTION ID="removeprop"></SECTION>
## RemoveProp
Removes an entry from the property list of the specified window. The specified character string identifies the entry to be removed.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-removepropa" target="_blank">here</a>

---

<SECTION ID="screentoclient"></SECTION>
## ScreenToClient
The ScreenToClient function converts the screen coordinates of a specified point on the screen to client-area coordinates.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-screentoclient" target="_blank">here</a>

---

<SECTION ID="ScrollWindow"></SECTION>
## ScrollWindow
The ScrollWindow function scrolls the contents of the specified window's client area. Note The ScrollWindow function is provided for backward compatibility. New applications should use the ScrollWindowEx function

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-scrollwindow" target="_blank">here</a>

---

<SECTION ID="scrollwindowex"></SECTION>
## ScrollWindowEx
The ScrollWindowEx function scrolls the contents of the specified window's client area.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-scrollwindowex" target="_blank">here</a>

---

<SECTION ID="senddlgitemmessage"></SECTION>
## SendDlgItemMessage
Sends a message to the specified control in a dialog box.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-senddlgitemmessagea" target="_blank">here</a>

---

<SECTION ID="sendmessage"></SECTION>
## SendMessage
Sends the specified message to a window or windows. The SendMessage function calls the window procedure for the specified window and does not return until the window procedure has processed the message. To send a message and return immediately, use the SendMessageCallback or SendNotifyMessage function. To post a message to a thread's message queue and return immediately, use the PostMessage or PostThreadMessage function.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-sendmessage" target="_blank">here</a>

---

<SECTION ID="sendmessagecallback"></SECTION>
## SendMessageCallBack
Sends the specified message to a window or windows. It calls the window procedure for the specified window and returns immediately if the window belongs to another thread. After the window procedure processes the message, the system calls the specified callback function, passing the result of the message processing and an application-defined value to the callback function.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-sendmessagecallbacka" target="_blank">here</a>

---

<SECTION ID="sendmessagetimeout"></SECTION>
## SendMessageTimeOut
Sends the specified message to one or more windows.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-sendmessagetimeouta" target="_blank">here</a>

---

<SECTION ID="setactivewindow"></SECTION>
## SetActiveWindow
Activates a window. The window must be attached to the calling thread's message queue.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-setactivewindow" target="_blank">here</a>

---

<SECTION ID="setcapture"></SECTION>
## SetCapture
Sets the mouse capture to the specified window belonging to the current thread.SetCapture captures mouse input either when the mouse is over the capturing window, or when the mouse button was pressed while the mouse was over the capturing window and the button is still down. Only one window at a time can capture the mouse. If the mouse cursor is over a window created by another thread, the system will direct mouse input to the specified window only if a mouse button is down.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-setcapture" target="_blank">here</a>

---

<SECTION ID="setcarepos"></SECTION>
## SetCarePos
Moves the caret to the specified coordinates. If the window that owns the caret was created with the CS_OWNDC class style, then the specified coordinates are subject to the mapping mode of the device context associated with that window.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-setcaretpos" target="_blank">here</a>

---

<SECTION ID="setclipboarddata"></SECTION>
## SetClipboardData
Places data on the clipboard in a specified clipboard format. The window must be the current clipboard owner, and the application must have called the OpenClipboard function. (When responding to the WM_RENDERFORMAT and WM_RENDERALLFORMATS messages, the clipboard owner must not call OpenClipboard before calling SetClipboardData.)

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-setclipboarddata" target="_blank">here</a>

---

<SECTION ID="setcursor"></SECTION>
## SetCursor
Sets the cursor shape

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-setcursor" target="_blank">here</a>

---

<SECTION ID="setcursorpos"></SECTION>
## SetCursorPos
Moves the cursor to the specified screen coordinates. If the new coordinates are not within the screen rectangle set by the most recent ClipCursor function call, the system automatically adjusts the coordinates so that the cursor stays within the rectangle.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-setcursorpos" target="_blank">here</a>

---

<SECTION ID="setdlgitemint"></SECTION>
## SetDlgItemInt
Sets the text of a control in a dialog box to the string representation of a specified integer value.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-setdlgitemint" target="_blank">here</a>

---

<SECTION ID="setdlgitemtext"></SECTION>
## SetDlgItemText
Sets the title or text of a control in a dialog box.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-setdlgitemtexta" target="_blank">here</a>

---

<SECTION ID="setfocus"></SECTION>
## SetFocus
Sets the keyboard focus to the specified window. The window must be attached to the calling thread's message queue.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-setfocus" target="_blank">here</a>

---

<SECTION ID="setforegroundwindow"></SECTION>
## SetForegroundWindow
Brings the thread that created the specified window into the foreground and activates the window. Keyboard input is directed to the window, and various visual cues are changed for the user. The system assigns a slightly higher priority to the thread that created the foreground window than it does to other threads.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-setforegroundwindow" target="_blank">here</a>

---

<SECTION ID="setlayeredwindowattributes"></SECTION>
## SetLayeredWindowAttributes
Sets the opacity and transparency color key of a layered window.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-setlayeredwindowattributes" target="_blank">here</a>

---

<SECTION ID="setmenu"></SECTION>
## SetMenu
Assigns a new menu to the specified window.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-setmenu" target="_blank">here</a>

---

<SECTION ID="setmenudefaultitem"></SECTION>
## SetMenuDefaultItem
Sets the default menu item for the specified menu.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-setmenudefaultitem" target="_blank">here</a>

---

<SECTION ID="setmenuinfo"></SECTION>
## SetMenuInfo
Sets information for a specified menu.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-setmenuinfo" target="_blank">here</a>

---

<SECTION ID="setparent"></SECTION>
## SetParent
Changes the parent window of the specified child window.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-setparent" target="_blank">here</a>

---

<SECTION ID="setprop"></SECTION>
## SetProp
Adds a new entry or changes an existing entry in the property list of the specified window. The function adds a new entry to the list if the specified character string does not exist already in the list. The new entry contains the string and the handle. Otherwise, the function replaces the string's current handle with the specified handle.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-setpropa" target="_blank">here</a>

---

<SECTION ID="setscrollinfo"></SECTION>
## SetScrollInfo
The SetScrollInfo function sets the parameters of a scroll bar, including the minimum and maximum scrolling positions, the page size, and the position of the scroll box (thumb). The function also redraws the scroll bar, if requested.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-setscrollinfo" target="_blank">here</a>

---

<SECTION ID="settimer"></SECTION>
## SetTimer
Creates a timer with the specified time-out value.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-settimer" target="_blank">here</a>

---

<SECTION ID="setwindowlong"></SECTION>
## SetWindowLong
Changes an attribute of the specified window. The function also sets the 32-bit (long) value at the specified offset into the extra window memory. Note This function has been superseded by the SetWindowLongPtr function. To write code that is compatible with both 32-bit and 64-bit versions of Windows, use the SetWindowLongPtr function.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-setwindowlonga" target="_blank">here</a>

---

<SECTION ID="setwindowlongptr"></SECTION>
## SetWindowLongPtr
Changes an attribute of the specified window. The function also sets a value at the specified offset in the extra window memory. Note To write code that is compatible with both 32-bit and 64-bit versions of Windows, use SetWindowLongPtr. When compiling for 32-bit Windows, SetWindowLongPtr is defined as a call to the SetWindowLong function.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-setwindowlongptra" target="_blank">here</a>

---

<SECTION ID="setwindowplacement"></SECTION>
## SetWindowPlacement
Sets the show state and the restored, minimized, and maximized positions of the specified window.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-setwindowplacement" target="_blank">here</a>

---

<SECTION ID="setwindowpos"></SECTION>
## SetWindowPos
Changes the size, position, and Z order of a child, pop-up, or top-level window. These windows are ordered according to their appearance on the screen. The topmost window receives the highest rank and is the first window in the Z order.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-setwindowpos" target="_blank">here</a>

---

<SECTION ID="setwindowrgn"></SECTION>
## SetWindowRgn
The SetWindowRgn function sets the window region of a window. The window region determines the area within the window where the system permits drawing. The system does not display any portion of a window that lies outside of the window region

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-setwindowrgn" target="_blank">here</a>

---

<SECTION ID="setwindowtext"></SECTION>
## SetWindowText
Changes the text of the specified window's title bar (if it has one). If the specified window is a control, the text of the control is changed. However, SetWindowText cannot change the text of a control in another application.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-setwindowtexta" target="_blank">here</a>

---

<SECTION ID="showcaret"></SECTION>
## ShowCaret
Makes the caret visible on the screen at the caret's current position. When the caret becomes visible, it begins flashing automatically.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-showcaret" target="_blank">here</a>

---

<SECTION ID="showwindow"></SECTION>
## ShowWindow
Sets the specified window's show state

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-showwindowt" target="_blank">here</a>

---

<SECTION ID="switchtothiswindow"></SECTION>
## SwitchToThisWindow
\[This function is not intended for general use. It may be altered or unavailable in subsequent versions of Windows.\]
Switches focus to the specified window and brings it to the foreground.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-switchtothiswindow" target="_blank">here</a>

---

<SECTION ID="systemparametersinfo"></SECTION>
## SystemParametersInfo
Retrieves or sets the value of one of the system-wide parameters. This function can also update the user profile while setting a parameter.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-systemparametersinfoa" target="_blank">here</a>

---

<SECTION ID="trackmouseevent"></SECTION>
## TrackMouseEvent
Posts messages when the mouse pointer leaves a window or hovers over a window for a specified amount of time. Note The TrackMouseEvent function calls TrackMouseEvent if it exists, otherwise _TrackMouseEvent emulates TrackMouseEvent.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-trackmouseevent" target="_blank">here</a>

---

<SECTION ID="trackpopupmenu"></SECTION>
## TrackPopupMenu
Displays a shortcut menu at the specified location and tracks the selection of items on the menu. The shortcut menu can appear anywhere on the screen.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-trackpopupmenu" target="_blank">here</a>

---

<SECTION ID="translateaccelerator"></SECTION>
## TranslateAccelerator
Processes accelerator keys for menu commands. The function translates a WM_KEYDOWN or WM_SYSKEYDOWN message to a WM_COMMAND or WM_SYSCOMMAND message (if there is an entry for the key in the specified accelerator table) and then sends the WM_COMMAND or WM_SYSCOMMAND message directly to the specified window procedure. TranslateAccelerator does not return until the window procedure has processed the message.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-translateacceleratora" target="_blank">here</a>

---

<SECTION ID="translatemdisysaccel"></SECTION>
## TranslateMDISysAccel
Processes accelerator keystrokes for window menu commands of the multiple-document interface (MDI) child windows associated with the specified MDI client window. The function translates WM_KEYUP and WM_KEYDOWN messages to WM_SYSCOMMAND messages and sends them to the appropriate MDI child windows.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-translatemdisysaccel" target="_blank">here</a>

---

<SECTION ID="translatemessage"></SECTION>
## TranslateMessage
Translates virtual-key messages into character messages. The character messages are posted to the calling thread's message queue, to be read the next time the thread calls the GetMessage or PeekMessage function.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-translatemessage" target="_blank">here</a>

---

<SECTION ID="unregisterclass"></SECTION>
## UnRegisterClass
Unregisters a window class, freeing the memory required for the class.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-unregisterclassa" target="_blank">here</a>

---

<SECTION ID="updatewindow"></SECTION>
## UpdateWindow
The UpdateWindow function updates the client area of the specified window by sending a WM_PAINT message to the window if the window's update region is not empty. The function sends a WM_PAINT message directly to the window procedure of the specified window, bypassing the application queue. If the update region is empty, no message is sent.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-updatewindow" target="_blank">here</a>

---

<SECTION ID="validaterect"></SECTION>
## ValidateRect
The ValidateRect function validates the client area within a rectangle by removing the rectangle from the update region of the specified window.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-validaterect" target="_blank">here</a>

---

<SECTION ID="windowfromdc"></SECTION>
## WindowFromDC
The WindowFromDC function returns a handle to the window associated with the specified display device context (DC). Output functions that use the specified device context draw into this window.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-windowfromdc" target="_blank">here</a>

---

<SECTION ID="windowfrompoint"></SECTION>
## WindowFromPoint
Retrieves a handle to the window that contains the specified point.

### Info
* **Category**: UI API
* **DLL**: User32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/winuser/nf-winuser-windowfrompoint" target="_blank">here</a>

---

</div>

</div>
