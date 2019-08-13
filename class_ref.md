---
layout: default
---
Class Reference
====================

<SECTION ID="activex">
</SECTION>
## ActiveX

### Properties
* BackColor
* Constants
* Cursor
* Font
* ForeColor
* hEventHandler
* oTypeLib
* ToolTip

### Methods
* AxGet()
* AxSet()
* Configure()
* Create()
* Init()
* IsRegistered()
* LinkEvents()
* OnDestroy()
* OnGetDlgCode()
* SetStyle()
* ShowPropertiesDialog()
* Translate

### Info
* **Category** : vxh class
* **LIB** : vxh.lib


<SECTION ID="adsdatatable">
</SECTION>
## AdsDataTable
The AdsDataTable component inherits the DataTable component, being customized to use one of the Advantage RDD\-s.

### Properties
* EnumTableType
* ServerType
* Driver

### Methods
* AdsSetServerType()
* Append()
* Blob2File()
* BlobGet()
* BlobImport()
* Create()
* CreateFTSOrder()
* CreateOrder()
* CreateTable()
* DecryptTable()
* DeleteOrder()
* EnableEncryption()
* EncryptTable()
* FieldPut()
* File2Blob()
* GetLockOwner()
* IsTableEncrypted()
* MemoExt()
* NewInstance()
* RecLock()
* Save()
* SetAOF()
* SetData()
* SetIndexDirection()
* Unlock()

### Description
Most properties and methods of the DataTable can be used in conjunction with AdsDataTable.

### Info
* **Category**: vxh class
* **LIB**: vxh.lib

<SECTION ID="adsserver">
</SECTION>
## AdsServer
### Properties
* EnumFileType
* EnumType
* hConnection

### Methods
* Create()
* Init()

### Info
* **Category**: vxh class
* **LIB**: vxh.lib

## Advantage
### Properties
* xDriver

### Methods

### Info
* **See also**: [ActiveX](#activex "ActiveX")
* **Category**: vxh class
* **LIB**: vxh.lib


<SECTION ID="anchor">
</SECTION>
## Anchor
Setting this object property - present in controls - does take sense when having a form with thick frame, and willing to manage the distance between the Form's frame and some of its child controls

### Properties
* Bottom
* Center
* Left
* Right
* Top

### Methods

### Info
* **Category**: vxh class


<SECTION ID="animation">
</SECTION>
## Animation
VXH's Animation control implements the standard Windows Animation control - a child window displaying a video clip in AVI format \(a series of bitmap frames\).

### Properties
* AutoPlay
* BackColor
* Centered
* FromFrame
* ImageName
* Repeat
* ToFrame
* Transparent
* Visible

### Methods
* Close()
* Open()
* Play()
* Stop()

### Description
The animation control's most frequent use is to indicate system activity background process is in progress.<br>
Limitations for the AVI clip format: It should not contain sound \(according to earlier Microsoft specifications\), it should be uncompressed or compressed using "run-length" encoding \(BI_RLE8\).<br>
The AVI clip can be placed near the executable, or it can be added to the executable as resource \(in the VXH IDE's Project menu choose "Resource Manager", and use the name displayed in the "Name" column as its resource name\).<br>


<SECTION ID="application">
</SECTION>
## Application
The Application class is an abstraction of a VXH software module as a collection of Form. In the VXH IDE in the Object Manager's "Object View" tab the Application node is listed as the root of the Form objects.

### Properties
* IniFile
* Instance
* MainForm
* Name
* OsVersion
* Params
* Path
* Resources
* Running
* Version

### Methods
* DoEvents()
* Exit()
* RestorePrevInstance()
* SaveResource()
* Yield()

### Description
See also Project, IniFile and Form. The first form in the Object View is always the Main Form - which is acting at run-time as a gateway between the local OS and our software.<br>
The Application's Company, CopyRight, Description and Version properties are holding strings, which are build in the output file, and can be consulted by right-clicking the file and then choosing "Properties".<br>
The Application's "Set" property group offers the possibility of configurating interactively most properties, which are set via the "SET ..." commands, or the Set\(...\) function, when developing procedural \[x\]Harbour code build with xBuilder.<br>
The Application's object reference is available from inside all Form objects \- as the value of the Application property of the current Form object.<br>

### Info
* **Category**: vxh class
* **LIB**: vxh.lib


<SECTION ID="backgroundimage">
</SECTION>
## BackgroundImage
As object property of containers like forms of TabPages it offers the possibility of displaying an image in the client area of the container object.

### Properties
* Alignment
* ImageName
* KeepAspectRatio
* Margins
* Opacity

### Methods

### Info
* **Category**: vxh class


<SECTION ID="band">
</SECTION>
## Band
The Band control is always created as a child control of a CoolBar, and consequently it's deleted, when its parent is deleted \(See also the CoolBar control\).

### properties
* BandChild
* Break
* Chevron
* FixedSize
* Grippers
* MinHeight
* MinWidth
* Width

### Methods

### Description
A Band control can hold a control by setting its BandChild property accordingly. A Band control typically holds a CoolBar or ToolBar control, and when its Grippers property is set to "true", its postion over the menu system can be adjusted visually.<br>
The right way to delete a Band control: Slect it, right-click on it, and choose the "Remove Band" menu option.<br>
When using directly the "Delete" button of the VXH\-IDE \(or the keyboard\) for deleting a Band, the control set as BandChild control is also deleted from the current From \- this is a documented Windows limitation.<br>

### Info
* **Category**: vxh class

<SECTION ID="button">
</SECTION>
## Button
The Button controls \- also referred as "command buttons" or "push buttons" are the most widely used objects in visual programming, even if their presence on a Form is not evident.

### Properties
* Alignment
* BackColor
* Border
* Text
* DefaultButton
* ForeColor
* Group
* ImageAlign
* ImageIndex
* ImageList
* MenuArrow
* MultiLine
* OwnerDraw
* ShortCutKey
* TabOrder
* TabStop
* Visible

### Methods
* Click()
* IsPushed()
* Push()
* Release()


### Description
The Button controls \- also referred as "command buttons" are the most widely used object in visual programming, even if their presence on a Form is not evident, being masked by custom images \(referred as owner drawn controls\).<br>

### Info
* **Category**: vxh class
* **LIB**: vxh.lib



<SECTION ID="checkbox">
</SECTION>
## CheckBox
The CheckBox controls are widely used for setting and getting boolean data, in generl answers to yes-no questions, when the answer to the question presumably won't get more diversified in time.<br>

### Properties
* AutoSize
* BackColor
* Border
* Text
* CheckStyle
* ForeColor
* Group
* RightButton
* State
* Visible
* WrapText

### Methods
* Check()
* Checked()
* Interdeterminate()
* SetState()
* UnCheck()

### Info
* **Category**: vxh class
* **LIB**: vxh.lib


<SECTION ID="cmenuitem">
</SECTION>
## CMenuItem
The CoolMenuItem always appears as a child control of a CoolMenu, or ContextMenu. Its role is to act as a menu item, offering a selectable option for the user \(see also enabled property\).

### Properties
* Text
* Enabled
* Font
* ForeColor
* RadioCheck
* Separator
* ShortCutKey
* ShortCutText
* Theming

### Methods
* Check()
* IsChecked()
* SetText()
* Uncheck()

### Description
We have two different categories of menu items: placed directly on a CoolMenu, respectively included in sublists.

### Info
* **Category**: vxh class
* **LIB**: vxh.lib



<SECTION ID="colordialog">
</SECTION>
## ColorDialog
ColorDialog is a common control, it implements the standard Windows Color Dialog, designed for interactive color selection.

### Properties
* Color
* FullOpen
* PreventFullOpen
* ShowHelp

### Methods
* Show()

### Description
The dialog window has a mandatory zone, which includes a set of basic colors and buttons, and an optional zone, which includes the custom color selection - see the FullOpen and PreventFullopen properties.<br>
The ColorDialog is displayed by Using its Show method, and its Color property contains the color value selected by the user.

### Info
* **Category**: vxh class
* **LIB**: vxh.lib


<SECTION ID="colorpicker">
</SECTION>
## ColorPicker
The ColorPicker inherits the ComboBox control, and it's dedicated to offer the user the possibility of selecting a color from its drop-down list.

### Properties
* AddEditHorzScroll
* Border
* DropDownStyle
* Enabled
* Font
* Height
* HorzScroll
* ItemHeight
* LowerCase
* NoIntegralHeight
* SlelectionHeight
* UpperCase
* Width

### Methods

### Info
* **Category**: vxh class
* **LIB**: vxh.lib


<SECTION ID="combobox">
</SECTION>
<SECTION ID="combobox">
</SECTION>
## ComboBox
The ComboBox control is a combination of an EditBox \(also referred as current selection\), a ListBox \(also referred as dropdown list\) and an arrow image.

### Properties
* AutoEditHorzScroll
* Border
* DisableNoScroll
* DropDwonStyle
* Font
* HasStrings
* Height
* HorzScroll
* ItemHeight
* OemConvert
* OwnerDrawFixed
* OwnerDrawVariable
* SlectionHeight
* Sort
* UpperCase
* VertScroll
* Visible
* Width

### Methods
* AddItem()
* AddString()
* DeleteString()
* FindString()
* FindStringExact()
* GetCount()
* GetCureSel()
* GetDroppedState()
* GetLocale()
* GetString()
* HideDropDown()
* InsertString()
* ResetContent()
* SelectString()
* SetCureSel()
* SetLocale()
* ShowDropDown()

### Description
When the user clicks on the arrow image, the dropdown list is displayed.<br>
The control manages a list of text strings \(also referred as items\), shown in the ListBox. The ListBox might have a unique selected item. The EditBox does display the corrently selected list item \- if any. The EditBox may or may not accept user input.<br>
The control's DropDownStyle property value defines its behaviour. When this is set to "DropDownList" \(by default\), the EditBox does not accept user input. When DropDownStyle is set to "Simple", the ListBox is always visible.<br>
When a list item is selected (\set as current selection\), its text content is displayed in the edit box, and the list box is scrolled accordingly.

### Info
* **category**: vxh class
* **LIB**: vxh.lib


<SECTION ID="comboboxex">
</SECTION>
## ComboBoxEx
The ComboBoxEx control inherits the ComboBox control, and additionally it can have an ImageList, which serves for decorating the items in the drop-down list. For more methods see [ComboBox](#combobox "ComboBox") control.

### Properties
* AutoEditHorScroll
* DropDownStyle
* Enabled
* Font
* Height
* ImageList
* NotIntegralHeight
* Visible
* Width

### Method
* AddItem()

### Info
* **Category**: vxh class
* **LIB**: vxh.lib



<SECTION ID="contextmenu">
</SECTION>
## ContextMenu
ContextMenu components are widely used in Windows applications. In the VXH IDE they can be created visually by dropping from the ToolBox on the current Form, and then clicking the appropiate.

### Properties
* ImageList

### Methods

### Description
"\[Add New Item\]" positions for configuring the new object.<br>
In VXH the ContextMenu objects \(displayed on the current Form's Component Bar\) are collections of CoolMenuItem objects \(or menu items\), which can be organized in lists on multiple levels.<br>
We can add new menu items to a ContextMenu as needed \- just select the ContextMenu in the VXH IDE, and click on the appropiate "\[Add New Item\]" positons.<br>
The ContextMenus created in the application's Man Form are available in all the other Forms of the application.<br>
Each control having the ContextMenu property can be set with one of the ContextMenu objects offered by the VXH IDE.

### Info
* **Category**: vxh class
* **LIB**: vxh.lib




<SECTION ID="coolbar">
</SECTION>
## CoolBar
The CoolBar control implements the Wndows Rebar control. It can include one or more Band controls, acting as a container control for feature\-rich, advanced menu systems. A From schould not have more than a CoolBar.

### Properties
* Vertical

### Methods

### Description
When dropping a CoolBar on the current Form, it includes a single Band control \(click on it to refresh the Object Manager\). For adding a new Band: select the CoolBar, right-click on it, and choose the "Add CoolBar Band" menu option.<br>
Each Band control can hold a control \(typically a MenuBar or a ToolBar\) \- its BandChild property will be set accordingly. The Band's MinHeight property should be adjusted to vover at least the BandChild control's height.<br>
The right way to delete a CoolBar control is to remove the Band controls one by one: select a Band control, right-click on it, and choose the "Reove Band" menu option.<br>
When using directly the "Delete" button of the VXH IDE \(or the keyboard\) for deleting a Band or the entire ToolBar, all the controls set as BandChild controls are also deleted from the current Form \- this is a documented Windows limitation.

### Info
* **Category**: vxh class
* **LIB**: vxh.lib


<SECTION ID="coolbarband">
</SECTION>
## CoolBarBand

### Properties

### Methods

### Info
* **Category**: vxh class
* **LIB**: vxh.lib


<SECTION ID="coolmenu">
</SECTION>
## CoolMenu
The CoolMenu is a container control holding CoolMenuItem controls \- visually represented by horizontal bar with simple menu items. Both the bar and the menu items can be transparent \- in VXH this is the default CoolMenu setup.

### Properties
* Enabled
* Flat
* HorzPadding
* ImageList
* Transparent
* Visible

### Methods

### Description
When the CoolMenu control is a good choice when we need a classic, simple, horizontal menu bar. The CoolMenu can be used in combination with a CoolBar control, by setting it as BandChild to a Band of the CoolBar.<br>
We can add new CoolMenuItems directly onto a CoolMenu bar in this way: select the CoolMenu control, increase its width until an "\[Add New Item\]" label is appearing over the bar, and now click on the label. The other menu items are organized in sublists.<br>
In order to add a new menu item into a sublist: highlight a CoolMenuItem over the bar, click on it to display further "\[Add New Item\]" labels, and now click where inserting a new CoolMenuItem is appropiate.

### Info
* **Category**: vxh class
* **LIB**: vxh.lib






## CoolMenuItem

## CursorComboBox

## Data

## DataConnector

## DataGrid

## DataSource

## DataTable

## DateTimePicker

## Dock

## Drawing

## DriveComboBox

## EditBox

## Expando

## ExploreBar

## Fields

## FolderBrowseDialog

## FolderTree

## FontComboBox

## Form

## FreeImage

## FtpClient

## GridColumn

## GroupBox

## HeaderItem

## HeaderStrip

## ImageList

## IniFile

## Label

## LinkLabel

## ListBox

## ListView

## ListViewColumn

## ListViewGroup

## MaskEdit

## MdiClient

## MemData

## MemoryTable

## MenuStrip

## MenuStripItem

## MessageWait

## MonthCalendar

## NotifyIcon

## OpenFileDialog

## OptionBarButton

## OptionBar

## PageScroller

## Panel

## PictureBox

## ProgressBar

## Project

## RadioButton

## RichTextBox

## SaveFileDialog

## SerialPort

## Service

## ShortCutKey

## Splitter

## SqlConnector

## StatusBar

## StatusBarPanel

## System

## TabCloseButton

## TabControl

## TabPage

## TabPinButton

## TabStrip

## Timer

## ToolBar

## ToolButton

## ToolStrip

## ToolStripButton

## ToolStripComboBox

## ToolStripContainer

## ToolStripLabel

## ToolTip

## TreeListView

## TreeView

## TreeViewItem

## WebBrowser

## WinPrint

## WinSock

## Zip

