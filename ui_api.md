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
[DefMDIChildProcAddress](#defmdichildprocaddress)
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

<SECTION ID="animatewindow"></SECTION>
**AnimateWindow**


<SECTION ID="appendmenu"></SECTION>
**AppendMenu**


<SECTION ID="beginpaint"></SECTION>
**BeginPaint**


<SECTION ID="beginupdateresource"></SECTION>
**BeginUpdateResource**


<SECTION ID="bringwindowtotop"></SECTION>
**BringWindowToTop**


<SECTION ID="callnexthookex"></SECTION>
**CallNextHookEx**


<SECTION ID="callwindowproc"></SECTION>
**CallWindowProc**


<SECTION ID="checkdlgbutton"></SECTION>
**CheckDlgButton**


<SECTION ID="checkmenuitem"></SECTION>
**CheckMenuItem**


<SECTION ID="checkradiobutton"></SECTION>
**CheckRadioButton**


<SECTION ID="childwindowfrompoint"></SECTION>
**ChildWindowFromPoint**


<SECTION ID="childwindowfrompointex"></SECTION>
**ChildWindowFromPointEx**


<SECTION ID="clienttoscreen"></SECTION>
**ClientToScreen**


<SECTION ID="clipcursor"></SECTION>
**ClipCursor**


<SECTION ID="closeclipboard"></SECTION>
**CloseClipboard**


<SECTION ID="copyicon"></SECTION>
**CopyIcon**


<SECTION ID="copyimage"></SECTION>
**CopyImage**


<SECTION ID="createacceleratortable"></SECTION>
**CreateAcceleratorTable**


<SECTION ID="CreateCaret"></SECTION>
**CreateCaret**


<SECTION ID="createdialog"></SECTION>
**CreateDialog**


<SECTION ID="createdialogindirect"></SECTION>
**CreateDialogIndirect**


<SECTION ID="createmdiwindow"></SECTION>
**CreateMDIWindow**


<SECTION ID="createmenu"></SECTION>
**CreateMenu**


<SECTION ID="createpopupmenu"></SECTION>
**CreatePopupMenu**


<SECTION ID="createwindow"></SECTION>
**CreateWindow**


<SECTION ID="createwindowex"></SECTION>
**CreateWindowEx**


<SECTION ID="defdlgproc"></SECTION>
**DefDlgProc**


<SECTION ID="defdlgprocpointer"></SECTION>
**DefDlgProcPointer**


<SECTION ID="deferwindowpos"></SECTION>
**DeferWindowPos**


<SECTION ID="defframeprocaddress"></SECTION>
**DefFrameProcAddress**


<SECTION ID="defmdichildprocaddress"></SECTION>
**DefMDIChildProcAddress**


<SECTION ID="defwindowproc"></SECTION>
**DefWindowProc**


<SECTION ID="deletemenu"></SECTION>
**DeleteMenu**


<SECTION ID="destroyacceleratortable"></SECTION>
**DestroyAcceleratorTable**


<SECTION ID="destroycaret"></SECTION>
**DestroyCaret**


<SECTION ID="destroyicon"></SECTION>
**DestroyIcon**


<SECTION ID="destroymenu"></SECTION>
**DestroyMenu**


<SECTION ID="destroywindow"></SECTION>
**DestroyWindow**


<SECTION ID="dialogbox"></SECTION>
**DialogBox**


<SECTION ID="dialogboxindirect"></SECTION>
**DialogBoxIndirect**


<SECTION ID="dispatchmessage"></SECTION>
**DispatchMessage**


<SECTION ID="drawcaption"></SECTION>
**DrawCaption**


<SECTION ID="drawedge"></SECTION>
**DrawEdge**


<SECTION ID="drawfocusrect"></SECTION>
**DrawFocusRect**


<SECTION ID="drawframecontrol"></SECTION>
**DrawFrameControl**


<SECTION ID="drawicon"></SECTION>
**DrawIcon**


<SECTION ID="drawiconex"></SECTION>
**DrawIconEx**


<SECTION ID="drawstate"></SECTION>
**DrawState**


<SECTION ID="drawtext"></SECTION>
**DrawText**


<SECTION ID="emptyclipboard"></SECTION>
**EmptyClipboard**


<SECTION ID="enablewindow"></SECTION>
**EnableWindow**


<SECTION ID="enddeferwindowpos"></SECTION>
**EndDeferWindowPos**


<SECTION ID="enddialog"></SECTION>
**EndDialog**


<SECTION ID="endmenu"></SECTION>
**EndMenu**


<SECTION ID="endprint"></SECTION>
**EndPrint**


<SECTION ID="endtask"></SECTION>
**EndTask**


<SECTION ID="enumchildwindows"></SECTION>
**EnumChildWindows**


<SECTION ID="exitwindowex"></SECTION>
**ExitWindowEx**


<SECTION ID="fillrect"></SECTION>
**FillRect**


<SECTION ID="findwindow"></SECTION>
**FindWindow**


<SECTION ID="findwindowex"></SECTION>
**FindWindowEx**


<SECTION ID="framerect"></SECTION>
**FrameRect**


<SECTION ID="getactivewindow"></SECTION>
**GetActiveWindow**


<SECTION ID="getancestor"></SECTION>
**GetAncestor**


<SECTION ID="getasynckeystate"></SECTION>
**GetASyncKeyState**


<SECTION ID="getcapture"></SECTION>
**GetCapture**


<SECTION ID="getcaretpos"></SECTION>
**GetCaretPos**


<SECTION ID="getclassinfo"></SECTION>
**GetClassInfo**


<SECTION ID="getclasslong"></SECTION>
**GetClassLong**


<SECTION ID="getclassname"></SECTION>
**GetClassName**


<SECTION ID="getclientrect"></SECTION>
**GetClientRect**


<SECTION ID="getclipboarddata"></SECTION>
**GetClipboardData**


<SECTION ID="getcursor"></SECTION>
**GetCursor**


<SECTION ID="getcursorpos"></SECTION>
**GetCursorPos**


<SECTION ID="getdc"></SECTION>
**GetDC**


<SECTION ID="getdcex"></SECTION>
**GetDCEx**


<SECTION ID="getdesktopwindow"></SECTION>
**GetDesktopWindow**


<SECTION ID="getdialogbaseunits"></SECTION>
**GetDialogBaseUnits**


<SECTION ID="getdlgctrlid"></SECTION>
**GetDlgCtrlID**


<SECTION ID="getdlgitemint"></SECTION>
**GetDlgitemint**


<SECTION ID="getdlgitemtext"></SECTION>
**GetDlgItemText**


<SECTION ID="getfocus"></SECTION>
**GetFocus**


<SECTION ID="getforegroundwindow"></SECTION>
**GetForegroundWindow**


<SECTION ID="geticoninfo"></SECTION>
**GetIconInfo**


<SECTION ID="getkeystate"></SECTION>
**GetKeyState**


<SECTION ID="getmenu"></SECTION>
**GetMenu**


<SECTION ID="getmenuinfo"></SECTION>
**GetMenuInfo**


<SECTION ID="getmenuitemcount"></SECTION>
**GetMenuItemCount**


<SECTION ID="getmenuitemid"></SECTION>
**GetMenuItemID**


<SECTION ID="getmenustate"></SECTION>
**GetMenuState**


<SECTION ID="getmenustring"></SECTION>
**GetMenuString**


<SECTION ID="getmesssage"></SECTION>
**GetMesssage**


<SECTION ID="getmessagepos"></SECTION>
**GetMessagePos**


<SECTION ID="getmonitorinfo"></SECTION>
**GetMonitorInfo**


<SECTION ID="getnextdlgtabitem"></SECTION>
**GetNextDlgTabItem**


<SECTION ID="getopenclipboardwindow"></SECTION>
**GetOpenClipboardWindow**


<SECTION ID="getparent"></SECTION>
**GetParent**


<SECTION ID="getprop"></SECTION>
**GetProp**


<SECTION ID="getscrollbarinfo"></SECTION>
**GetScrollBarInfo**


<SECTION ID="getscrollinfo"></SECTION>
**GetScrollInfo**


<SECTION ID="getsubmenu"></SECTION>
**GetSubMenu**


<SECTION ID="getsyscolor"></SECTION>
**GetSysColor**


<SECTION ID="getsystemmenu"></SECTION>
**GetSystemMenu**


<SECTION ID="getsystemmetrics"></SECTION>
**GetSystemMetrics**


<SECTION ID="getwindow"></SECTION>
**GetWindow**


<SECTION ID="getwindowdc"></SECTION>
**GetWindowDC**


<SECTION ID="getwindowinfo"></SECTION>
**GetWindowInfo**


<SECTION ID="getwindowlong"></SECTION>
**GetWindowLong**


<SECTION ID="getwindowlongptr"></SECTION>
**GetWindowLongPtr**


<SECTION ID="getwindowplacement"></SECTION>
**GetWindowPlacement**


<SECTION ID="getwindowrect"></SECTION>
**GetWindowRect**


<SECTION ID="getwindowtext"></SECTION>
**GetWindowText**


<SECTION ID="getwindowtextlength"></SECTION>
**GetWindowTextLength**


<SECTION ID="hidecaret"></SECTION>
**HideCaret**


<SECTION ID="hilitemenuitem"></SECTION>
**HiliteMenuItem**


<SECTION ID="inflaterect"></SECTION>
**InflateRect**


<SECTION ID="insertmenuitem"></SECTION>
**InsertMenuItem**


<SECTION ID="invalidaterect"></SECTION>
**InvalidateRect**


<SECTION ID="invertrect"></SECTION>
**InvertRect**


<SECTION ID="IsChild"></SECTION>
**IsChild**


<SECTION ID="isclipboardformatavailable"></SECTION>
**IsClipboardFormatAvailable**


<SECTION ID="isdialogmessage"></SECTION>
**IsDialogMessage**


<SECTION ID="isdlgbuttonchecked"></SECTION>
**IsDlgButtonChecked**


<SECTION ID="ishungammwindow"></SECTION>
**IsHungAmmWindow**


<SECTION ID="isiconic"></SECTION>
**IsIconic**


<SECTION ID="ismenu"></SECTION>
**IsMenu**


<SECTION ID="iswindow"></SECTION>
**IsWindow**


<SECTION ID="iswindowenabled"></SECTION>
**IsWindowEnabled**


<SECTION ID="iswindowvisible"></SECTION>
**IsWindowVisible**


<SECTION ID="keybd_event"></SECTION>
**KeyBD_Event**


<SECTION ID="killtimer"></SECTION>
**KillTimer**


<SECTION ID="loadbitmap"></SECTION>
**LoadBitmap**


<SECTION ID="loadcursor"></SECTION>
**LoadCursor**


<SECTION ID="loadicon"></SECTION>
**LoadIcon**


<SECTION ID="loadimage"></SECTION>
**LoadImage**


<SECTION ID="loadmenu"></SECTION>
**LoadMenu**


<SECTION ID="lockwindowupdate"></SECTION>
**LockWindowUpdate**


<SECTION ID="mapdialogrect"></SECTION>
**MapDialogRect**


<SECTION ID="mapvirtualkey"></SECTION>
**MapVirtualKey**


<SECTION ID="mapwindowpoint"></SECTION>
**MapWindowPoint**


<SECTION ID="messagebeep"></SECTION>
**MessageBeep**


<SECTION ID="messagebox"></SECTION>
**MessageBox**


<SECTION ID="modifymenu"></SECTION>
**ModifyMenu**


<SECTION ID="movewindow"></SECTION>
**MoveWindow**


<SECTION ID="oemtochar"></SECTION>
**OemToChar**


<SECTION ID="offsetrect"></SECTION>
**OffsetRect**


<SECTION ID="openclipboard"></SECTION>
**OpenClipboard**


<SECTION ID="peekmessage"></SECTION>
**PeekMessage**


<SECTION ID="postmessage"></SECTION>
**PostMessage**


<SECTION ID="postquitmessage"></SECTION>
**PostQuitMessage**


<SECTION ID="ptinrect"></SECTION>
**PtInRect**


<SECTION ID="realchildwindowfrompoint"></SECTION>
**RealChildWindowFromPoint**


<SECTION ID="redrawwindow"></SECTION>
**RedrawWindow**


<SECTION ID="registerclass"></SECTION>
**RegisterClass**


<SECTION ID="registerclassex"></SECTION>
**RegisterClassEx**


<SECTION ID="registerhotkey"></SECTION>
**RegisterHotKey**


<SECTION ID="registerwindowmessage"></SECTION>
**RegisterWindowMessage**


<SECTION ID="releasecapture"></SECTION>
**ReleaseCapture**


<SECTION ID="releasedc"></SECTION>
**ReleaseDC**


<SECTION ID="removemenu"></SECTION>
**RemoveMenu**


<SECTION ID="removeprop"></SECTION>
**RemoveProp**


<SECTION ID="screentoclient"></SECTION>
**ScreenToClient**


<SECTION ID="scrollwindowex"></SECTION>
**ScrollWindowEx**


<SECTION ID="senddlgitemmessage"></SECTION>
**SendDlgItemMessage**


<SECTION ID="sendmessage"></SECTION>
**SendMessage**


<SECTION ID="sendmessagecallback"></SECTION>
**SendMessageCallBack**


<SECTION ID="sendmessagetimeout"></SECTION>
**SendMessageTimeOut**


<SECTION ID="setactivewindow"></SECTION>
**SetActiveWindow**


<SECTION ID="setcapture"></SECTION>
**SetCapture**


<SECTION ID="setcarepos"></SECTION>
**SetCarePos**


<SECTION ID="setclipboarddata"></SECTION>
**SetClipboardData**


<SECTION ID="setcursor"></SECTION>
**SetCursor**


<SECTION ID="setcursorpos"></SECTION>
**SetCursorPos**


<SECTION ID="setdlgitemint"></SECTION>
**SetDlgItemInt**


<SECTION ID="setdlgitemtext"></SECTION>
**SetDlgItemText**


<SECTION ID="setfocus"></SECTION>
**SetFocus**


<SECTION ID="setforegroundwindow"></SECTION>
**SetForegroundWindow**


<SECTION ID="setlayeredwindowattributes"></SECTION>
**SetLayeredWindowAttributes**


<SECTION ID="setmenu"></SECTION>
**SetMenu**


<SECTION ID="setmenudefaultitem"></SECTION>
**SetMenuDefaultItem**


<SECTION ID="setmenuinfo"></SECTION>
**SetMenuInfo**


<SECTION ID="setparent"></SECTION>
**SetParent**


<SECTION ID="setprop"></SECTION>
**SetProp**


<SECTION ID="setscrollinfo"></SECTION>
**SetScrollInfo**


<SECTION ID="settimer"></SECTION>
**SetTimer**


<SECTION ID="setwindowlong"></SECTION>
**SetWindowLong**


<SECTION ID="setwindowlongptr"></SECTION>
**SetWindowLongPtr**


<SECTION ID="setwindowplacement"></SECTION>
**SetWindowPlacement**


<SECTION ID="setwindowpos"></SECTION>
**SetWindowPos**


<SECTION ID="setwindowrgn"></SECTION>
**SetWindowRgn**


<SECTION ID="setwindowtext"></SECTION>
**SetWindowText**


<SECTION ID="showcaret"></SECTION>
**ShowCaret**


<SECTION ID="showwindow"></SECTION>
**ShowWindow**


<SECTION ID="switchtothiswindow"></SECTION>
**SwitchToThisWindow**


<SECTION ID="systemparametersinfo"></SECTION>
**SystemParametersInfo**


<SECTION ID="trackmouseevent"></SECTION>
**TrackMouseEvent**


<SECTION ID="trackpopupmenu"></SECTION>
**TrackPopupMenu**


<SECTION ID="translatemdisysaccel"></SECTION>
**TranslateMDISysAccel**


<SECTION ID="translatemessage"></SECTION>
**TranslateMessage**


<SECTION ID="unregisterclass"></SECTION>
**UnRegisterClass**


<SECTION ID="updatewindow"></SECTION>
**UpdateWindow**


<SECTION ID="validaterect"></SECTION>
**ValidateRect**


<SECTION ID="windowfromdc"></SECTION>
**WindowFromDC**


<SECTION ID="windowfrompoint"></SECTION>
**WindowFromPoint**


</div>

</div>
