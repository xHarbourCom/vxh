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
The animation control's most frequent use is to indicate system activity background process is in progress.  
Limitations for the AVI clip format: It should not contain sound \(according to earlier Microsoft specifications\), it should be uncompressed or compressed using "run-length" encoding \(BI_RLE8\).  
The AVI clip can be placed near the executable, or it can be added to the executable as resource \(in the VXH IDE's Project menu choose "Resource Manager", and use the name displayed in the "Name" column as its resource name\).  


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
See also Project, IniFile and Form. The first form in the Object View is always the Main Form - which is acting at run-time as a gateway between the local OS and our software.  
The Application's Company, CopyRight, Description and Version properties are holding strings, which are build in the output file, and can be consulted by right-clicking the file and then choosing "Properties".  
The Application's "Set" property group offers the possibility of configurating interactively most properties, which are set via the "SET ..." commands, or the Set\(...\) function, when developing procedural \[x\]Harbour code build with xBuilder.  
The Application's object reference is available from inside all Form objects \- as the value of the Application property of the current Form object.  

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
A Band control can hold a control by setting its BandChild property accordingly. A Band control typically holds a CoolBar or ToolBar control, and when its Grippers property is set to "true", its postion over the menu system can be adjusted visually.  
The right way to delete a Band control: Slect it, right-click on it, and choose the "Remove Band" menu option.  
When using directly the "Delete" button of the VXH\-IDE \(or the keyboard\) for deleting a Band, the control set as BandChild control is also deleted from the current From \- this is a documented Windows limitation.  

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
The Button controls \- also referred as "command buttons" are the most widely used object in visual programming, even if their presence on a Form is not evident, being masked by custom images \(referred as owner drawn controls\).  

### Info
* **Category**: vxh class
* **LIB**: vxh.lib



<SECTION ID="checkbox">
</SECTION>
## CheckBox
The CheckBox controls are widely used for setting and getting boolean data, in generl answers to yes-no questions, when the answer to the question presumably won't get more diversified in time.  

### Properties
* AutoSize
* BackColor
* Border
* Caption
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



## CMenuItem

## ColorDialog

## ColorPicker

## ComboBox

## ComboBoxEx

## ContextMenu

## CoolBar

## CoolBarBand

## CoolMenu

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

