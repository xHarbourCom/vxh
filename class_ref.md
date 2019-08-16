---
layout: default
title: Class Reference
---


<div class="sidenav">
      <a href="#activex">ActiveX</a>
      <a href="#adsdatatable">AdsDataTable</a>
      <a href="#adsserver">AdsServer</a>
      <a href="#advantage">Advantage</a>
      <a href="#anchor">Anchor</a>
      <a href="#animation">Animation</a>
      <a href="#application">Application</a>
      <a href="#backgroundimage">BackgroundImage</a>
      <a href="#band">Band</a>
      <a href="#button">Button</a>
      <a href="#checkbox">CheckBox</a>
      <a href="#cmenuitem">CMenuItem</a>
      <a href="#colordialog">ColorDialog></a>
      <a href="#colorpicker">ColorPicker</a>
      <a href="#combobox">ComboBox</a>
      <a href="#comboboxex">ComboBoxEx</a>
      <a href="#contextmenu">ContextMenu</a>
      <a href="#coolbar">CoolBar</a>
      <a href="#coolbarband">CoolBarBand</a>
      <a href="#coolmenu">CoolMenu></a>
      <a href="#coolmenuitem">CoolMenuItem</a>
      <a href="#cursorcombobox">CursorComboBox</a>
      <a href="#data">Data</a>
      <a href="#dataconnector">DataConnector</a>
      <a href="#datagrid">DataGrid</a>
      <a href="#datasource">DataSource</a>
      <a href="#datatable">DataTable</a>
      <a href="#datetimepicker">DateTimePicker</a>
      <a href="#dock">Dock</a>
      <a href="#drawing">Drawing</a>
      <a href="#drivecombobox">DriveComboBox</a>
      <a href="#editbox">EditBox</a>
      <a href="#expando">Expando</a>
      <a href="#exprorerbar">ExplorerBar</a>
      <a href="#fields">Fields</a>
      <a href="#folderbrowsedialog">FolderBrowseDialog</a>
</div>

<div class="right_main">

<div markdown="1">
Class Reference
=================

---

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
* **Category** : VXH Class
* **LIB** : vxh.lib

---

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
* **Category**: VXH Class
* **LIB**: vxh.lib


---

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
* **Category**: VXH Class
* **LIB**: vxh.lib

## Advantage
### Properties
* xDriver

### Methods

### Info
* **See also**: [ActiveX](#activex "ActiveX")
* **Category**: VXH Class
* **LIB**: vxh.lib


---


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
* **Category**: VXH Class


---


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


---

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
* **Category**: VXH Class
* **LIB**: vxh.lib


---


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
* **Category**: VXH Class


---


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
* **Category**: VXH Class


---

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
* **Category**: VXH Class
* **LIB**: vxh.lib


---


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
* **Category**: VXH Class
* **LIB**: vxh.lib


---

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
* **Category**: VXH Class
* **LIB**: vxh.lib


---


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
* **Category**: VXH Class
* **LIB**: vxh.lib


---


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
* **Category**: VXH Class
* **LIB**: vxh.lib


---

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
* **category**: VXH Class
* **LIB**: vxh.lib


---

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
* **Category**: VXH Class
* **LIB**: vxh.lib


---

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
* **Category**: VXH Class
* **LIB**: vxh.lib


---

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
* **Category**: VXH Class
* **LIB**: vxh.lib


---


<SECTION ID="coolbarband">
</SECTION>
## CoolBarBand

### Properties

### Methods

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib


---


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
* **Category**: VXH Class
* **LIB**: vxh.lib



---


<SECTION ID="coolmenu">
</SECTION>
## CoolMenuItem
The CoolMenuItem always appears as a child control of a CoolMenu, or ContextMenu. Its role is to act as menu item, offering a selectable option for the user \(see also the Enabled property\).

### Properties
* Text
* Enabled
* Font
* ForeColor
* ImageIndex
* RadioCheck
* Separator
* ShortCutKey
* ShortCutText
* Theming

### Methods

### Description
The CoolMenuItem always appears as a child control of a CoolMenu, or ContextMenu. Its role is to act as menu item, offering a selectable option for the user \(see also the Enabled property\).<br>
We have two different categories of menu items: placed directly on a CoolMenu, respectively includes in bublists.

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib


---


<SECTION ID="cursorcombobox">
</SECTION>
## CursorComboBox

### Properties
### Methods
### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---


<SECTION ID="data">
</SECTION>
## Data

### Properties
### Methods
### Info
* **Category**: VXH Class
* **LIB**: vxh.lib


---


<SECTION ID="dataconnector">
</SECTION>
## DataConnector

### Properties
### Methods
### Info
* **Category**: VXH Class
* **LIB**: vxh.lib


---


<SECTION ID="datagrid">
</SECTION>
## DataGrid
The DataGrid is the most complex control of VXH, serving as a user interface for data organized in a two\-dimensional array\- associated to the DataGrid as DataSource object property.

### Properties
* AllowDragRecords
* AnchorColumn
* aSelected
* AutoHorzScroll
* AutoVertScroll
* BackColor
* Border
* Text
* ColCount
* ColPos
* Columns
* ConvertOem
* DataSource
* Enabled
* ExtVertScrollBar
* Font
* ForeColor
* FreezeColumn
* FullRowSelect
* GridColor
* HeaderHeight
* HighLightTextColor
* HigtLightCapton
* ImageList
* ImageHeight
* MenuArrow
* Multiple Selection
* RowPos
* ShadowRow
* ShowGrid
* ShowSelection
* ShowSelectionBorder
* Striping
* Visible

### Method
* ArrowLeft()
* ArrowRight()
* AutoAddColumns()
* DeleteColumn()
* Edit()
* GetItemRect()
* Refresh()
* RestoreLayout()
* Update()
* UpdateRow()

### Description
The DataGrid control consists of a rectangular panel, which can hold collection of GridColumn objects, an optional horizontal band for column headers, and an optional small title bar.<br>
The DataGrid is comparable with a set of images arranged in lines \(data rows\) and columns, each image displaying a cell with textual data content and optionally a decoration from the ImageList set for the DataGrid.<br>
The DataSource set for the DataGrid does always have a currently selected row \(pointed by the record pointer\) which might be positioned inside or outside the row set currently displayed by the DataGrid.<br>
The user can select a particular cell by clicking on it and // or using the scrollbars, the arrow and page movement keys, in this case the cell becomes the currently selected cell, and its row the currently selected row.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---


<SECTION ID="datasource">
</SECTION>
## DataSource
As object property of DataGrid controls, the DataSource reprents as abstract two-dimensional array, holding data, which is being displayed by the associated DataGrid in sequential chunks.

### Properties
* Fields

### Methods

### Description
The DataGrid can be considered an array of small images, which are not aware of their data contents \- the data content can be get or set via the Fields object property of the DataSource.<br>
In VXH we can use as DataSource for DataGrid \(or orther control\) one of the following objects: MemoryTable, DataTable, MemoryDataTable.<br>
The DataSource object during its lifetime always has a "current row" or "current record" \- corresponding to the currently selected row it the DataGrid sourced by the DataSource.<br>
The DataSource object during its lifetime always has a "current row" or "current record" \- corresponding to the currently selected row in the DataGrid sourced by the DataSource.<br>
A DataSource can be associated to other controls, like ListView.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib


---


<SECTION ID="datatable">
</SECTION>
## DataTable
The DataTable component represents an abstract two-dimension array of data, which is physically stored in a permanent file.

### Properties
* Alias
* Area
* aScatter
* AutoOpen
* CodePage
* Driver
* Fields
* FileName
* IsOpen
* Path
* ReadOnly
* ReIndex
* Shared
* SqlConnector
* Structure

### Methods
* Append()
* Bof()
* Close()
* Commit()
* CreateIndex()
* CreateOrder()
* DbEval()
* Delete()
* Eof()
* FileLock()
* Found()
* Gather()
* GoBottom()
* GoTo()
* GoTop()
* IndexOrd()
* KillScope()
* Open()
* OrdDescend()
* OrdKey()
* OrdKeyCount()
* OrdKeyGoTo()
* OrdKeyNo()
* OrdKeyRelPos()
* OrdKeyVal()
* OrdName()
* OrdSetFocus()
* Recall()
* RecCount()
* RecLock()
* RecNo()
* Scatter()
* Seek()
* Select()
* SelectArea()
* SetBottomScope()
* SetDriver()
* SetFileName()
* SetFilter()
* SetIndex()
* SetOrder()
* SetRelation()
* SetTopScope()
* Skip()
* Struct()
* UnLock()
* UnLockAll()
* Used()
* Zap()

### Description
In VXH a DataTable can refer data stored in free tables or a managed tables, using one of the RDD-s offered by the xHarbour language \- see the Driver and Fields properties.<br>
In most cases the DataTable is used in association with a DataGrid control, being set as the DataSource \(property\) of the DataGrid.<br>
When a DataTable is using SQLRDD, firstly a corresponding SqlConnector component needs to be set up in the VXH IDE, in order to assure a connection to the database engine, which is managing the table.<br>
While the DataTable is opened \(crated and not closed\), it always has a current row, pointed by the record pointer, and optionally an active index order as well.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib


---

<SECTION ID="datetimepicker">
</SECTION>
## DateTimePicker
The DateTimePicker control consists of an EditBox and alternatively a dropdown calender or an UpDown object.

### Properties
* Border
* CustomFormat
* Date
* Enabled
* Font
* Format
* Parse
* Time
* UpDown
* Visible

### Methods

### Description
The DateTimePicker is suitable for displaying and collecting calender date or time values, when a Form contains numerous controls.<br>
Clicking on the arrow symbol opens the dropdown calender, and then choosing a date, or clicking outside the calender will close it.<br>
The highligted numeric data in the EditBox can be incremented or decremented by clicking the corresponding arrow on the updown object.<br>
The control's behaviour depends on the value set for the Format property. The default date format depends on the local system setup \- see the "Regional and Language Options" on the Windows Control Panel.

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib


---

<SECTION ID="dock">
</SECTION>
## Dock
Setting this object property - present in controls - does take sense when having a Form with tich frame and // or splitter(s)

### Properties
* Bottom
* Left
* Margins
* Right
* Top

### Methods

### Description
"Docing" our controls does keep them positioned near the frames of the parent Form and // or other sibling controls chosen as reference.

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="drawing">
</SECTION>
## Drawing
A Drawing is always created as a child of a Form  or a Form, being an abstraction of the visual interface of its parent object.

### Properties
* hDC
* Parent

### Methods
* GetDeviceCaps()
* DrawText()
* EnumFonts()
* ExtTextOut()
* FillRect()
* GetPixel()
* GetTextExtentPoint32()
* GetTextMetrics()
* PolyLine()
* Rectangle()
* SetBkModel()
* SetPixel()
* SetTextColor()

### Description
The Drawing's device context \(see hDC property\) is serving as support for the painting operations.<br>
Each form or control has a Drawing property, holding the object reference of its Drawing object, respectively each Drawing object has a Parent property, holding the object reference of its parent object.<br>
The Drawing's method calls related to painting operations should be placed inside the OnPaint method of its parent object \(form or control\) \- for example SetTextColor, SetBkColor, DrawText, PolyLine.<br>
Method calls like SetPixel, Rectangle, GetDeviceCaps, EnumFonts will work as extected when being done inside methods as well.<br>
A general presentation of Windows GDI is available [here](https://docs.microsoft.com/en-in/windows/win32/gdi/windows-gdi).



---

<SECTION ID="drawing">
</SECTION>
## DriveComboBox
The DriveComboBox inherits the ComboBox control, being dedicated to list the disk drives currently available on the local system, offering for the user the possibility of selecting from the drop-down list.

### Properties
* AutoEditHorzScroll
* Border
* DropDownStyle
* Enabled
* Font
* LowerCase
* OnCBNSelEndOk
* SelectionHeight
* UpperCase
* Visible
* Width

### Methods

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib


---

<SECTION ID="editbox">
</SECTION>
## EditBox
It can be used as single line text box or multi line edit box.


### Syntax
```
::EditBox1:Text := <cText>
```

### Properties
* CueBanner
* EnterNext
* FullSelectOnClick
* MenuArrow
* Password
* Text

### Methods

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib


---

<SECTION ID="expando">
</SECTION>
## Expando
The Expando is always created as a child dontrol of an ExplorerBar. The Expando consists of a header band and a pane.<br>

### Properties
* Enabled
* Expanded
* Fond
* Height
* ImageIndex
* ImageList
* Special
* Text

### Methods

### Description
The header band has a caption text, and a mandatory button symbol on its right side \(a double arrow for toggling between the control's expanded and collapsed state\), and optionally it can have and image on its left side.<br>
Each Expando is a container control \- its pane can hold other various stand controls like Labels, Buttons, EditBoxes.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib


---

<SECTION ID="explorerbar">
</SECTION>
## ExplorerBar
The ExplorerBar control can hold zero or more Expando controls, which can be expanded and collapsed indivitually. Each Expando can hold various simple controls.<br>

### Properties
* Border
* Enabled
* ImageList
* Visible

### Methods

### Description 
Add a new [Expando](#expando "Expando") to an ExplorerBar, right-click on it, and choose "Add Expando".<br>


### Info
* **Category**: VXH Class
* **LIB**: vxh.lib


---

<SECTION ID="fields">
</SECTION>
## Fields
The Fields object property represents an abstract cell of a DataSource. Fields provides methods for reading and writing values in the abstract two-dimensional table represented by the [DataSource](#datasource "DataSource").<br>

### Properties
* Parent

### Methods
* FieldGet()
* FieldName()
* FieldPut()
* FieldType()
* Put()

### Description
The Parent property of the Fields object contains the object reference of the [DataSource](#datasource "DataSource").<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib


---

<SECTION ID="folderbrowsedialog">
</SECTION>
## FolderBrowseDialog
FolderBrowserDialog is a common control, it implements the standard Windows Browse For Folder Dialog Box. The dialog can be used for selecting a single folder \- also referred as directory or file path.<br>

### Properties
* Description
* RootFolder
* SelectedPath
* ShowNewFolderButton

### Methods

### Description
FolderBrowseDialog is opened by invoking its Show method, and the program execution continues with the next instruction, after the user has completed the folder selection, or has cancelled the dialog.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib


---

<SECTION ID="folderlist">
</SECTION>
## FolderList
The FolderList control inherists the [ListView](#listview "ListView") control, being dedicated to offer for user the possibility of selecting a file from a folder \- see the Folder and SysFolder properties.<br>

### Methods

### Description
The FolderList control's properties in most cases are working like the [ListView](#listview "ListView") control's properties - here are going to be described the properties specific to the FolderList control.<br>
*The following properties should not be altered: OwnerData, DataSource, ImageList, ImageListSmall*.


---

<SECTION ID="foldertree">
</SECTION>
## FolderTree
The FolderTree class inherits the [TreeView](#treeview "TreeView") class, and it's dedicated to display a tree of folders, offering for the user the possibility of selectting a folder \- an absolute file path.<br>

### Properties
* Folder
* SysFolder

### Methods
* GetPath()

### Description
Most properties and methods of the [TreeView](#treeview "TreeView") are available for the FolderTree \- here are going to be listed the differences.<br>
The Folder and SysFolder properties support the control's initialization, respectively the GetPath method retrieves the user selection.<br>
The ImageList property does not need and should not be set.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="fontcombobox">
</SECTION>
## FontComboBox
As object property \- present in containers and controls \- it defines the style of the text displayed in the object.<br>


### Properties
* Bold
* Escapement
* FaceName
* FileName
* Italic
* Orientation
* PointSize
* StrikeOut
* UnderLine
* Width

### Methods
When the specified font is not present on the local machine, the OS loads another font with appropiate features, or the system's default font.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib


---

<SECTION ID="form">
</SECTION>
## Form
The Forms are the fundamental building blocks of Windows GUI applications. All VXH applications must have a Main Form \- visible or not \- and optionally other Forms.

### Properties
* AcceptFiles
* ActiveForm
* AlwaysOnTop
* AnimationStyle
* Application
* BackColor
* BitMapMask
* BitMapMaskColor
* Text
* CaptionBar
* Center
* Children
* ChildrenEdge
* ClipChildren
* ClipSiblings
* ContextMenu
* ControlParent
* DisableParent
* DlgModalFrame
* Enabled
* ForeColor
* FrameStyle
* GnerateMember
* HasFocus
* Height
* HorzScroll
* HorzScrollPos
* HorzScrollSize
* hWnd
* Icon
* Id
* ImageList
* IParam
* IsContainer
* Left
* MaxHeight
* MaximizeBox
* MaxWidth
* MdiChild
* MdiContainer
* MinHeight
* MinHeight
* MinimizeBox
* MinWidth
* Modal
* Msg
* Name
* NoActivate
* Opacity
* OriginalRect
* Params
* Property
* Resizable
* ShowInTaskBar
* ShowMode
* StaticEdge
* SysMenu
* System
* Theming
* ThickFrame
* ToolWindow
* Top
* UserVariables
* VertScroll
* VertScrollPos
* VertScrollSize
* VertScrollTopMargin
* Width
* wParam

### Methods
* BringWindowToTop()
* CenterWindow()
* ClientToScreen()
* Close()
* GetRect()
* GetStyle()
* HasProperty()
* Hide()
* InvalidateRect()
* IsWindow()
* Maximize()
* MessageBox()
* Minimize()
* MoveWindow()
* Refresh()
* Restore()
* RestoreLayout()
* SaveLayout()
* ScreenToClient()
* SetActiveWindow()
* SetActiveWindow()
* SetExStyle()
* SetFocus()
* SetParent()
* SetStyle()
* SetWindowPos()
* Show()
* UpdateWindowPos()
* Show()
* UpdateWindow()
* ValidateRect()

### Description
The Main Form is acting like a gateway between the application and the OS.<br>
In VXH the Main Form is always the first Form added to a new project, and its object reference **::Application:MainForm** is available all methods and event handlers inside the project.<br>
VXH can generate SDI or MDI applications. In case of VXH projects implementing the MDI design pattern, the Main Form's MdiContainer property needs to be set to "true", in order to generate the MDICLIENT window \(see also MdiClient Object\).
The properties set for a VXH Form in the Object Manager are shaping the concrete MFC window class, which is going to be instatiated at runtime.<br>
When having a complex Form with numerous controls, the Panel and GroupBox controls can act as building blocks inside the Form.<br>
The ImageList components are functional building blocks, as they support decorating almost all controls.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="fields">
</SECTION>
## FreeImage
The FreeImage control has many common features with PictureBox control, being meant to complement each other.<br>

### Properties
* Alignment
* BackColor
* Text
* Enabled
* Font
* HorzScroll
* ImageList
* KeepAspectRatio
* Margins
* Opacity
* SmallCaption
* VertScroll

### Methods
* LoadFromString()
* LoadResource()
* Refresh()

### Description
The FreeImage control is based on xHarbour's implementation of the FreeImage library; it can handle numerous image formats, and it's suitable in cases when one need to display images stored in formats, which cannot be handled by the PictureBox control.

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="ftpclient">
</SECTION>
## FtpClient
The FtpClient component offers a set of methods for handling event-driven communication through the Internet, using the FTP or HTTP protocol. VXH's FtpClient class is implemented by using WinApi\(WinInet\) functions.

### Properties
* hFtp
* hHandle
* OpenType
* Operation
* Passive
* Password
* Port
* Server
* UserName

### Methods
* Connect()
* CreateDirectory()
* DeleteFile()
* Disconnect()
* GetCurrentDirectory()
* GetDirectory()
* GetFile()
* GetLastResponseInfo()
* PutFile()
* RemoveDirectory()
* RenameFile()
* SetCurrentDirectory()

### Description
Due to WinInet limitations, applications using the FtpClient component should not be set up as services, and a FtpClient component should be placed as much as possible in a module built as .EXE file, not as .DLL file.

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib


---

<SECTION ID="gridcolumn">
</SECTION>
## GridColumn
A GridColumn is always created as a child object of a DataGrid control \- as a member of the column collection of the DataGrid - its event handlers being fired by its parent.

### Properties
* Alignment
* AllowDrag
* AllowSize
* AutoEdit
* BackColor
* ButtonMenu
* ButtonText
* Text
* ContextMenu
* Data
* ForeColor
* HeaderBackColor
* HeaderFont
* HeaderForeColor
* HeaderImageIndex
* HeaderMenu
* ImageAlignment
* ImageIndex
* Locked
* Picture
* Representation
* SelOnlyRep
* SortArrow
* Width

### Methods
* GetEditValue()
* Refresh()

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="groupbox">
</SECTION>
## GroupBox
When having numerous controls over a Form, they need to be grouped. The GroupBox is a container control designed to hold a number of controls, placed over its surface surrounded by a thin contour line.<br>

### Products
* BackColor
* Border
* Text
* Enabled
* Font
* ForeColor
* ImageList
* VertScrollPos
* Visible

### Methods

### Description
Both GroupBox and [Panel](#panel "Panel") controls make easier the maintenance of the visual design of Forms with complex contents. These container controls can be moved around their parent Forms like building blocks.<br>
Despite of Panels supporting physical modularization, the GroupBox control, with its driversified styling options, is thought for data grouping on logical level \(data organized around topics, which are familiar for the users\).<br>
As a rule of thumb: a Form should not contain more than 6-7 groups \(tabs, menus etc\), and a group should not include more than 6-7 editable and / or selectable items - otherwise the Form gets overwhelming for the user.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="headeritem">
</SECTION>
## HeaderItem
A HeaderItem is always created as a child control of a HeaderStrip.<br>

### Properties
* Alignment
* Text
* ImageIndex
* Position
* Width

### Methods
* GetRect()
* GetRectangle()


### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="headerstrip">
</SECTION>
## HeaderStrip
The HeaderStrip is a container control, which is holding HeaderItem controls.

### Properties
* Border
* Enabled
* Font
* Height
* ImageList
* ImageMargin
* Visible

### Methods
* DeleteItem()
* GetItemRect()
* InsertItem()
* SetArrow()
* SetItemCaption()
* SetItemWidth()

### Description
The HeaderStrip is a solution for advanced level applications, offering the user the possibility to handle a set adherent windows, behaving likewise the columns of a table.<br>
The HeaderItem controls can be decorated with images from the HeaderStrip's ImageList, respectively an arrow can be set for one of them at a time - see the SetArrow method.<br>
We can add new HeaderItem controls onto a HeaderStrip in this way: select the HeaderStrip control, right-click on it, and now click on "Add New HeaderItem".<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="imagelist">
</SECTION>
## ImageList
The ImageList class is designed to hold a collection of images with similar technical parameters, and serving for decorating a number of controls placed over a common container control, or advanced controls including CoolMenu.

### Properties
* Count
* Handle
* IconHeight
* IconWidth
* Images
* MaskColor
* Palette

### Methods
* GetImage()
* RemoveAll()
* SaveImage()

### Description
The images held by an ImageList are identified by their positions in the list. VXH's image Manager dialogue is a visual tool for creating and maintaining our ImageList components - it can be opened by clicking on "Collection" at the Images property.<br>
Container objects like [Forms](#form "Form"), [Panels](#panel "Panel") and [GroupBoxes](#groupbox "GroupBox") have their own ImageList properties, which can be set for decorating controls held by them. [CoolMenus](#coolmenu "CoolMenu"), [ToolBars](#toolbar "ToolBar"), [ListViews](#listview "ListView") etc., can also be decorated with images from ImageLists.<br>
In VXH each Form can include one of more ImageList components. They are listed over the Componet Bar (at the bottom of the Design Area) and selectable by clicking on them - inorder to be set up in Object Manager.<br>
The desired image postion inside an ImageList can be set by using the ImageIndex property of a control. In VXH the ImageIndex is one-based, and when set to 0, it indicatetes that the object has no image set for decoration.

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="inifile">
</SECTION>
## IniFile
The IniFile class supports creating, consulting and updating INI files. Each Application object in the VXH IDE has an implicit IniFile object \- the object reference being held by the Application's IniFile property.<br>

### Properties
* Name

### Methods
* DelEntry()
* DelSection()
* Flush()
* GetEntries()
* GetSections()
* Read()
* Write()

### Description
The Application's IniFile object refers a file with predefined name: the path and name are the same as the string values of the Application object's Path and Name properties, respectively the extension is "ini".<br>
When we need to work with other INI file\(s\) then the implicit one, we can instantiate explicitly an IniFile object by invoking **IniFile(cFile)** \- where cFile is the fully qualified file name of the desired INI file.<br>
The file referred by the IniFile object \(instantiated implicitly or explicitly\) is created only when our code does at least an IniFile method call meant to update the file. When the INI file is updated, its new content is flushed on the hard disk.<br>
An explicitly instatiated IniFile object \- for example MyObj - will be marked for deletion \(garbage collection\) by the following command:<br>
```
MyObj := NIL
```

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="label">
</SECTION>
## Label
Label controls support displaying informative inscriptions \- mostly sttic text strings \- without input focus.<br>

### Properties
* Alignment
* AutoSize
* BackColor
* BackColor
* Border
* Text
* CenterText
* Enabled
* Font
* ForeColor
* NoPrefix
* RightAlign
* Simple
* Sunken
* TabStop
* VertCenter
* Visible
* WrapText

### Methods

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="linklabel">
</SECTION>
## LinkLabel
A LinkLabel control consists of a mandatory text area and an optional image. It supports displaying text strings, formatted and behaving as web links, and optionally visiting web sites.<br>

### Properties
* ActiveLinkColor
* Alignment
* AutoSize
* BackColor
* Border
* Text
* Enabled
* FocusRect
* Font
* ImageIndex
* LinkColor
* LinkVisited
* SelBackColor
* Url
* Visible
* VisitedColor

### Methods

### Description
The programmer is free to associate LinkLabel controls with various tasks or processes \- specific to the application's business logic. For example, when the user is clicking on a LinkLabel, a document can be opened, or a program can be started etc. Following codes will open the URL:
```
METHOD LinkLabel1_OnClick( Sender ) CLASS Form1
   ShellExecute( ::hWnd, 'open', Sender:Url, , , SW_SHOW )
RETURN Self
```

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="listbox">
</SECTION>
## ListBox
The ListBox control is designed to display a list of items, from which the user can choose one or more items. In most cases the list items are text strings. The control consists of a mandatory list area and an optional caption bar.

### Properties
* BackColor
* Border
* Text
* DisableNoScroll
* Enabled
* ExtendedSel
* Font
* ForeColor
* HasStrings
* HighLightCaption
* HorzScroll
* IntegralHeight
* MultiColumn
* NoRedraw
* Notify
* OwnerDraw
* SmallCaption
* Sort
* UseTabStops
* VertScroll
* Visible
* WantKeyboardInput

### Methods
* AddString()
* DeleteString()
* FindString()
* GetCount()
* GetCurSel()
* GetLocale()
* GetString()
* GetTextLen()
* GetTopIndex()
* InsertString()
* SelectString()
* SetColumnWidth()
* SetCurSel()
* SetLocale()
* SetTopIndex()

### Description
The ListBox control can be of single selection or of multiple selection - see the ExtendedSel property for setting this feature.<br>
The list items can be organized and displayed in a single column, or in multiple columns - see the MultiColumn property for setting this feature.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="listview">
</SECTION>
## ListView
ListView implements the standard Windows ListView control, designed to display the items of a list in various formats ( see ViewStyle ). The control includes a rectangular panel for list items, an optional small title bar, and scroll bars as needed.

### Properties
* AlignLeft
* AlignTop
* BackColor
* Border
* DataSource
* Enabled
* FlatScrollBar
* Font
* ForeColor
* FullRowSelect
* GridLines
* HighLightCaption
* ImageList
* ImageListSmall
* NoColumnHeader
* NoLabelWrap
* NoScroll
* NoSortHeader
* OwnerData
* Text
* ViewStyle
* Visible

### Methods
* AddColumn()
* DeleteColumn()
* EnsureVisible()
* FindItem()
* GetCurPos()
* GetHotItem()
* Refresh()
* ResetContent()
* SetCureSel()
* SetDataSource()
* SetItemText()
* SetLVExStyle()

### Description
The ListView can manage directly the list items \- in this case its OwnerData property should be set to "false" ( by default ) and its DataSource property should not be set \(NIL by default\). This setup is suitable for small lists - up to dozens of items.<br>
The ListView can act act as a virtual control when being set up with a DataSource \(MemoryTable, DataTable etc.\) \- in this case the OwnerData property should be set to "true".<br>
In case of a virtual ListView the data holden by the list items can be updated by using methods proper to the DataSource object, and then the ListView's Refresh method should be called to sync the user interface with the new data content.<br>
Each list item has a label ( column 0 in "report" view ), an optional ImageIndex \(see ImageList and SmallImageList\), and optionally one or more subitems \(column 1, 2 etc. in "report" view).<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="listviewcolumn">
</SECTION>
## ListViewColumn

### Properties
### Methods
### Info
* **Category**: VXH Class
* **LIB**: vxh.lib




---

<SECTION ID="listviewgroup">
</SECTION>
## ListViewGroup

### Properties
### Methods
### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="maskedit">
</SECTION>
## MaskEdit
The MaskEdit control is designed to receive formatted user input like numbers, date, or a text string respecting a custom picture mask. The control consists of a mandatory text area, an optional image and an optional arrow symbol.


### Properties
* Alignment
* BackColor
* Border
* Caption
* Case
* Enabled
* Font
* ForeColor
* FullSelectOnClick
* ImageIndex
* Layout
* NoHideSel
* OemConvert
* Password
* Picture
* SelBackColor
* SelForeColor
* Visible

### Methods

### Description
In case of MaskEdit the EnterNext property is enforced to "true" \- when the user presses keyboard key "Enter", the input focus leaves the control. Consequently MaskEdit is not suitable for storing multiple text paragraphs.<br>
The user input is limited as number of characters to the length of the mask ( set by the Picture property ), respectively the length of the string used to initialize the Caption property ( the smaller one is used as upper limit ).<br>


### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="mdiclient">
</SECTION>
## MdiClient
MDIClient is an object property listed in application Main Forms with MDIContainer property set to "true". Visually it represents the rectangular surface serving as a container for the Forms set up with MDIChild property turned "true".


### Properties
* AlignBottom
* AlignLeft
* AlignRight
* AlignTop
* BackColor
* ClientEdge
* WindowsMenu

### Methods


### Description
When designing a MDI application, first time the Main Form's MDIContainer property needs to be set to "true", and after selecting a different Form, the Main Form should be selected again.<br>
In this way the UI of the Main Form is refreshed in the Object Manager, respectively the MDIClient property becomes visible and ready to support the MDI design, even if the application originally has been started and developed as a SDI application.<br>
By default the MDIClient does visually cover the entire client area of the Main Form. In order to bound the MDIClient, by objects like [CoolMenu](#coolmenu "CoolMenu") present on the application's Main Form, the AlignLeft, AlignTop etc. properties should be set accordingly.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="memorydatatable">
</SECTION>
## MemoryDataTable
The MemoryDataTable component is very similar to the DataTable component, the main difference being that it's holding temporary data, which is stored in the local computer's memory.<br>

### Properties
* Structure

### Methods

### Description
The MemoryDataTable class inherits the DataTable class, consequently the properties, methods and event handlers listed for the DataTable can be used in similar manner.<br>
MemoryDataTable is suitable for working with volatile data - the indexes created for the table being also stored in the local computer's memory.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="memorytable">
</SECTION>
## MemoryTable
The MemoryTable component is an abstract two-dimensional array ( see Table property ), designed to serve as a DataSource ( see DataSource object property ) for a DataGrid or other control.<br>

### Properties
* Alias
* Fields
* IsOpen
* Structure
* Table

### Methods
* Append()
* Bof()
* Delete()
* Eof()
* FieldPos()
* GoBottom()
* GoTo()
* GoTop()
* Insert()
* RecLock()
* RecNo()
* Skip()
* UnLock()
* Zap()

### Description
While a MemoryTable's Structure property is an empty array, the component is only initialized, but not created, and its IsOpen property returns boolean .F. Recommended data types for being used as column types are "C", "N", "D", "L".<br>
During the MemoryTable's lifetime it always has a "record pointer" \(or current row, or current record\), the concrete numeric value being returned by calling the RecNo\(\) method.<br>
While a MemoryTable is sourcing a control, whenever its record pointer or data content are altered, the sourced control's visual interface needs to be updated by program code.<br>
In the VXH IDE's Object Manager use the "Edit Structure" dialog for defining the Table structure, respectively the "DataSource Editor" for initializing the table content interactively \(the table's reference is the Table property's value\).<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib


---

<SECTION ID="menustrip">
</SECTION>
## MenuStrip
The MenuStrip control is always created as a child control of a ToolStripContainer, and it's designed to serve as a module of a menu system.<br>

### Properties
* Enabled
* Font
* ImageList
* Row
* Showgrip
* Theming

### Methods

### Description
A MenuStrip can hold a set of objects, instances of the following classes: [MenuStripItem](#menustripitem "MenuStripItem"), [ToolStripLabel](#toolstriplabel, "ToolStripLabel"), [ToolStripComboBox](#toolstripcombobox "ToolStripComboBox").<br>
Adding a new object to a MenuStrip can be done in this way: select the MenuStrip, right\-click on it, and now choose the appropiate option.<br>
Each [MenuStripItem](#menustripitem "MenuStripItem") over a MenuStrip can own a submenu, extendable in this way: click on the desired MenuStripItem over the MenuStrip, and now click on the appropiate "Add New Item" label.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib


---

<SECTION ID="menustripitem">
</SECTION>
## MenuStripItem
A MenuStripItem is always created as a child control of a MenuStrip, respectively an item in a submenu of a MenuStripItem or a ToolStripButton.<br>

### Properties
* BeginGroup
* Checked
* Enabled
* Font
* ImageAlign
* ImageIndex
* ImageList
* ShortCutKey
* ShortCutText
* Text

### Methods

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib


---

<SECTION ID="messagewait">
</SECTION>
## MessageWait
Shows message box with different options.<br>

### Syntax
```
oWait := MessageWait():New( [<cText>], [<cTitle>], [<lProgress>], [<cCancel>], [<lMarquee>], [<hParent>], [<nMaxRange>] )
```

### Arguments
```
<cText> is the text to be displayed in the message box. It is optional.
<cTitle> is the title of the message box window. It is optional.
<lProgress> is used to show progress bar or not. It is optional. Default value .F.. Progress bar will be shown, if Marquee isn't .T.
<cCancel> is the text to be displayed for cancel button. It is optional. Cancel button won't be displayed if it is not given.
<lMarque> is used to show the marque or not. It is optional.
<hParent> is used for parent window handle. It is optional.
<nMaxRange> is used for maximum range of the progress bar. It is optional.
```

### Properties

### Methods
* AdjustSize()
* AutoClose()
* IsWindow()
* Marquee()
* Position()
* SetPosition()
* SetText()
* Text()

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="monthcalender">
</SECTION>
## MonthCalendar
The MonthCalendar control is a feature-rich user interface for displaying and collecting calendar dates. The control consists of a calendar sheet placed over a Panel with optional small caption bar.<br>

### Properties
* BackColor
* Border
* Date
* Daystate
* Enabled
* Font
* ForeColor
* HighLightCaption
* Multiselect
* NoToday
* NoTodayCircle
* SmallCaption
* Text
* Theming
* TilteForeColor
* TitleBackColor
* Today
* TrailingTextColor
* Visible
* WeekNumbers

### Methods

### Description
The date formatting rules and language respect the local system settings for the current user. By default the control's Theming property is set to "true", thus the calendar sheet's Font and color settings will respect the current system settings.<br>
The control can hold a "today" value in the Today property, and a "currently selected day" in the Date property, indicating the latest user selection.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="notifyicon">
</SECTION>
## NotifyIcon
The NotifyIcon component is managing an icon in the local system tray, in order to signal the current status and important events related to its parent Form and owner Application.<br>

### Properties
* BalloonTipIcon
* BalloonTipTitle
* ContextMenu
* Icon
* Text
* Visible

### Methods

### Description
The NotifyIcon component can display an icon in a tray \(hiding, showing, changing the icon is possible\); it shows a balloon whenever the icon is set as visible, respectively it shows a tip text, when the mouse is hovering over the icon.<br>
In a given moment of time the NotifyIcon's owner Application, more precisely the main window can be visible or not. A ContextMenu can be associated to the NotifyIcon to serve as alternative user interface for the owner Application.<br>
In order to set one or more of these properties: **BalloonTipIcon, BalloonTipText, BalloonTipTitle** \- first set the Visible property to boolean .F., then do the desired updates, and finally set the Visible property to boolean .T.

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib


---

<SECTION ID="openfiledialog">
</SECTION>
## OpenFileDialog
OpenFileDialog is a common control, it implements the standard Windows Open Dialog Box. The dialog can be used for selecting one or more files \- see the MultiSelect property.<br>

### Properties
* AddExtension
* CheckFileExists
* CheckPathExists
* DefaultExt
* DeferenceLinks
* FileName
* Filter
* FilterIndex
* InitialDirectory
* MultiSelect
* ReadOnlyChecked
* RestoreDirectory
* ShowHelp
* ShowPlacesBar
* ShowReadOnly
* Title

### Methods
* Show()

### Description
OpenFileDialog is opened by invoking its Show method, and the program execution continues with the next instruction, after the user has completed the file selection, or has cancelled the dialog.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="optionbarbutton">
</SECTION>
## OptionBarButton
The OptionBarButton is always created as a child control of an [OptionBar](#optionbar "OptionBar").

Properties
* Enabled
* ImageIndex
* Message
* ToolTip
* Text
* Visible

### Methods

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib


---

<SECTION ID="optionbarbutton">
</SECTION>
## OptionBar
The Optionbar control behaves like a vertical ToolBar, with all its child controls \- the [OptionBarButtons](#optionbarbutton "OptionBarButton") \- belonigng to a single group. OptionBar is a suitable choice, when a very simple, classic menu system is needed.<br>

### Properties
* BackColor
* Border
* CheckGroup
* Enabled
* Font
* HighLightCaption
* HotImageList
* ImageList
* List
* SmallCaption
* Text
* Theming
* Visible

### Methods

### Description
Add new [OptionBarButtons](#optionbarbutton "OptionBarButton") to the OptionBar in this way: select the Optionbar, right-click on it, and choose "Add Button".

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="pagescroller">
</SECTION>
## PageScroller

### Properties
### Methods

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="panel">
</SECTION>
## Panel
The Panel control consists of a rectangular surface and a small caption bar over its top margin. By default the control's margins are not visible at run-time, and the presence of the small caption bar is optional.<br>

### Properties
* BackColor
* Enabled
* Font
* HorzScroll
* ImageList
* SmallCaption
* Text
* Theming
* VertScroll
* VertScrollPos

### Methods

### Description
The Panel is a container control, designed to act as a building block inside the [Form](#form "Form"), by holding a number of other controls. It supports the physical modularization of the Form's content; it makes easier the maintenance of a Form with numerous contrrols.

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="picturebox">
</SECTION>
## PictureBox
The PictureBox control consists of a rectangular surface with an optional image, and an optional caption bar over its top border.<br>

### Properties
* Alignment
* BackColor
* BlackAndWhite
* Enabled
* Font
* HorzScroll
* ImageList
* ImageName
* InvertedColors
* KeepAspectRatio
* Opacity
* PictureHeight
* PictureWidth
* SmallCaption
* Stretch
* Text
* TransparencyByPixel
* Transparent
* VertScroll
* VertScrollPos
* Visible

### Methods
* Update()

### Description
The PictureBox controls are widely used for displaying image data, and decorative purposes as well. VXH's PictureBox implementation supports transparency, alpha channel \(see the Opacity property\), image redimensioning and many other features.<br>
VXH's PictureBox is a container control, it can hold a number of other controls, just like a [Panel](#panel "Panel") or a [GroupBox](#groupbox "GroupBox").<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="printdialog">
</SECTION>
## PrintDialog

### Properties

### Methods

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib


---

<SECTION ID="progressbar">
</SECTION>
## ProgressBar
The ProgressBar control is used in conjuction with lenghty processes - it can be configured as a horizontal or vertical bar.<br>

### Properties
* BackColor
* Border
* ForeColor
* Height
* MaxRange
* MinRange
* Position
* Smooth
* StatusPanelMargin
* Step
* Theming
* Vertical
* Visible
* Width

### Methods
* DeltaPos()
* StepIt()

### Description
The MinRange and MaxRange properties indicate the minimum and maximum values \(an interval\) specific to the process, which is going to be tracked by the ProgressBar. The Position property represents the current value displayed by the control.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="project">
</SECTION>
## Project
The Project class is an abstraction of the main organizational unit of software managed by the VXH IDE. See also the [Application](#application "Application") class.

### Properties
* Binary
* CleanBuild
* CompilerFlags
* Definitions
* Name
* Parameters
* Path
* TargetName
* TargetType

### Methods

### Description
When opening a VXH project, a Project object is created in the IDE, which can be accessed by clicking on the root node of the Object View in the Object Manager, and then clicking on the "Properties" tab.<br>
When a new project is created in the VXH IDE, a corresponding Project object is created as well. In the Object View we can always consult the object tree of the Project, which consists of an [Application](#application "Application") object as root node of one or more [Form](#form "Form") objects.<br>
A VXH project might include external references to LIB files, OBJ files, other resources added by using the IDE's "File" menu and "Add to project" submenu.<br>
These external files can be consulted in the Object Manager's "File View" tab \- they are used in the linking phase, when the currently loaded project is built.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib


---

<SECTION ID="radiobutton">
</SECTION>
## RadioButton
The RadioButton controls are designed to be used in groups \- a group representing a question, and each RadioButton in the group indicating a possible answer. The user can choose only a single RadioButton from a group.<br>

### Properties
* BackColor
* Border
* Enabled
* Font
* ForeColor
* Group
* InitialState
* OwnerDraw
* Text
* Visible

### Methods
* GetState()
* SetState()

### Description
When RadioButton controls are added to a [Form](#form "Form"), and none of them is set with its Group property to "true", then all of them are supposed to belong to the same group.<br>
When setting up a RadioButton group in the VXH IDE or by program code, only one of the group members should be set with its InitialState property to "Checked", otherwise at run-time the Form will behave erroneously.<br>
As a rule of thumb: when a question addressed to the user could have more than 5\-8 alternative answers \(in time most things get more and more diversified\), then using a [ComboBox](#combobox "ComboBox") instead of a RadioButton group might be of better help.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib


---

<SECTION ID="richtextbox">
</SECTION>
## RichTextBox
RichTextBox inherits [EditBox](#editbox "EditBox") and it supports displaying formatted text \- for example text snippets copied and pasted into the control. RichEditBox also supports text editing.

### Properties
* Alignment
* Border
* Enabled
* EnterNext
* Font
* FullSelectOnClick
* HorzScroll
* NoHideSel
* ReadOnly
* Text
* VertScroll
* Visible

### Methods

### Description
The text content without character formatting can be extracted from the control by using its Text property.<br>
The control is created with MultiLine and WantReturn properties enforced to "true", and its ClientEdge property is enforced to "false".<br>
Most [EditBox](#editbox "EditBox") methods can be used in conjunction with RichTextBox.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib


---

<SECTION ID="savefiledialog">
</SECTION>
## SaveFileDialog
SaveFileDialog is a common control, it implements the standard Windows Save Dialog Box. The dialog can be used for selecting a single file name.

### Properties
* AddExtension
* CheckPathExists
* CreatePrompt
* DefaultExt
* DeferenceLinks
* FileName
* Filter
* FilterIndex
* InitialDirectory
* ShowHelp
* ShowPlacesBar
* Title

### Methods
* Show()

### Description
SaveFileDialog is opened by invoking its Show method, and the program execution continues with the next instruction, after the user has closed or cancelled the dialog.<br>
Technically the [OpenFileDialog](#openfiledialog "SaveFileDialog") and the SaveFileDialog use the same memory structure for storing their internal data, and their behaviour shows many common features.

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib


---

<SECTION ID="serialport">
</SECTION>
## SerialPort
The SerialPort component offers a set of methods for handling event driven communication with a device connected to a serial port. VXH's SerialPort class is implemented by using WinApi functions.

### Properties
* BaudRate
* Cts
* DataBits
* Dsr
* DtrEnabled
* Handle
* HandShake
* IsOpen
* Parity
* PortName
* ReadBufferSize
* ReadTimeOut
* Ring
* Rlsd
* RtsEnabled
* StopBits

### Methods
* Clear()
* Close()
* CountIn()
* CountOut()
* Escape()
* Listen()
* Open()

### Description
The serial port is identified by the PortName property.<br>
When a communication port is opened, it's associated with a receive buffer and a transmit buffer. The Read\(\) method can get the incoming data bytes from the receive buffer, respectively the Write\(\) method can send data via the transmit buffer.<br>
The incoming communication is tracked by Listen\(\) method calls, respectively the custom code placed in the OnDataReceived\(\) event handler.<br>
Use the Close\(\) method to terminate in good conditions the usage of the communication port.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib


---

<SECTION ID="service">
</SECTION>
## Service

### Properties

### Methods

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="shortcutkey">
</SECTION>
## ShortCutKey
ShortCutKey As object property it serves for defining keyboard key combinations acting as shortcuts. It's used by controls like [Button](#button "Button"), [CoolMenuItem](#coolmenuitem "CoolMenuItem"), [ToolStripButton](#toolstripbutton "ToolStripButton") and [MenuStripItem](#menustripbutton "MenuStripButton").<br>

### Properties
* Alt
* Ctrl
* Key
* Shift

### Methods

### Description
The shortcuts of a given Windows application do work when the application has input focus, or one of its [Forms](#form "Form") has been activated.

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib


---

<SECTION ID="splitter">
</SECTION>
## Splitter
A Splitter control always appears as a child control of a [Panel](#panel "Panel"), [TreeView](#treeview "TreeView"), [PictureBox](#picturebox "PictureBox") or other control. The Splitters support the interactive redimensioning of their parent controls at run-time - by dragging the parent's

### Properties
* Position
* ShowDragging

### Methods

### Description
A control can hold four splitters: one over each of its margins. For adding a Splitter: select the control, drag a Splitter from the ToolBox over the control's desired margin, and drop it when a flashing red bar is displayed over that margin.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib


---

<SECTION ID="sqlconnector">
</SECTION>
## SqlConnector
The SqlConnector component is designed to ensure the connection needed by a sql engine \(server\) to manage a [DataTable](#datatable "DataTable") component - see also the SqlConnection property of the DataTable.

### Properties
* AutoConnect
* Connected
* ConnectionID
* ConnectionString
* Server
* Sql

### Methods
* Connect()
* DisConnect()

### Description
VXH's SqlConnector class is implemented by using SQLRDD functions, and its main role is automating the connecting and disconnecting operations between a [DataTable](#datatable "DataTable") and a sql engine, when these operations are necessary due to the program context.<br>
Using VXH's DataTable component in combination with the SqlConnector component makes possible to access data managed by a sql engine in pure visual manner.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib


---

<SECTION ID="statusbar">
</SECTION>
## StatusBar
The StatusBar serves informative purposes on [Form](#form "Form") level, and is always displayed on the bottom margin of its parent Form. Only one StatusBar control can be added to a Form.

### Properties
* Font
* ImageIndex
* ImageList
* Text
* Visible

### Methods

### Description
A StatusBar control can have its own caption text and image decoration, or alternatively it can hold [StatusBarPanel](#statusbarpanel "StatusBarPanel") controls, when more different informations need to be displayed dynamically at run-time.<br>
Add a new StatusBarPanel to a StatusBar in this way: select the StatusBar, right-click on it, and choose "Add Panel".<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="statusbarpanel">
</SECTION>
## StatusBarPanel
A StatusBarPanel control is always created as a child control of a [StatusBar](#statusbar "StatusBar"), and it serves informative purposes.

### Properties
* ImageIndex
* Text
* Width

### Methods

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="system">
</SECTION>
## System
The System object is holding in its properties useful informations related to the local computer system, and it's available as a property in each [Form](#form "Form").

### Properties
* Color
* Folders
* LocalTime
* OsVersion
* Time

### Methods
* GetPathFromFolder()

### Description
All the hash tables available as properties of the System object are set to use case-insensitive key search.

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="tabclosebutton">
</SECTION>
## TabCloseButton

### Properties

### Methods

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="tabcontrol">
</SECTION>
## TabControl
VXH's TabControl implements the standard Windows Tab Control. It's designed to manage a set of [TabPage](#tabpage "TabPage") objects, by showing and hiding them in a manner, that only one of the TabPages is visible at a time.<br>

### Properties
* BackColor
* Border
* Enabled
* FixedWidth
* Flat
* FocusNever
* Font
* ImageList
* MultiLine
* ShowTabs
* TabPosition
* Visible

### Methods
* DeleteTab()
* GetCurFocus()
* GetCurSel()
* GetItemCount()
* GetItemRect()
* GetItemText()
* GetRowCount()
* GetTabPosByName()
* Refresh()
* SetCurFocus()
* SetCurSel()
* SetItem()
* SetMinTabWidth()

### Description
The TabControl consists of a tab panel, zero or more adjacent Tab objects displayed over a tab band, and an up-down control \(shown when all Tab objects cannot be displayed at once\). Each Tab object is created in association with a [TabPage](#tabpage "TabPage") object.<br>
The tab band can be of a single line, or of multiple lines, displayed over one of the tab panel's margins \- see the MultiLine and the TabPosition properties.<br>
New Tab objects can be added to a TabControl in this way: select the control \(click on the band - near the existing Tab objects, or click on the TabControl in the Object Manager\), right-click on it, and now choose "Add TabPage".<br>
An individual Tab object cannot be disabled, however the corresponding TabPage can be disabled \- this is a documented limitation of the standard Windows Tab Control. Deleting a Tab object is possible by deleting its associated TabPage.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="tabpage">
</SECTION>
## TabPage
A TabPage object always appears in association with a Tab object of a [TabControl](#tabcontrol "TabControl") or a [TabStrip](#tabstrip "TabStrip").<br>

### Properties
* BackColor
* BottomMargin
* Enabled
* ForeColor
* HorzScroll
* ImageIndex
* ImageList
* LeftMargin
* Position
* RightMargin
* Text
* Theming
* TopMargin
* VertScroll

### Methods
* Delete()
* Select()

### Description
Each Tab object is created in association with a TabPage object, and by deleting the TabPage object, its corresponding Tab object will be deleted too.<br>
When the current selection has changed, the TabPage corresponding to the previously selected Tab object is hidden, and the TabPage corresponding to the currently selected Tab object is shown.<br>
Each TabPage can be set with left, top, right and / or bottom margins, relative to the [TabControl](#tabcontrol "TabControl") or a [TabStrip](#tabstrip "TabStrip"). The background color of a TabPage is not applied for its margins.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib





---

<SECTION ID="tabpinbutton">
</SECTION>
## TabPinButton

### Properties

### Methods

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="tabstrip">
</SECTION>
## TabStrip
VXH's TabStrip implements the standard Windows Tab Control. The main difference between VXH's [TabControl](#tabcontrol "TabControl") and TabStrip is that the TabStrip control's styling is targeted to modern user interfaces - see the ColorScheme property.

### Properties
* BackColor
* ColorInactiveHeader
* ColorScheme
* Enabled
* FixedWidth
* Font
* ImageList
* MultiLine
* ShowTabs
* TabPosition
* Visible

### Methods

### Description
The [TabControl](#tabcontrol "TabControl") and the TabStrip controls are very similar \- see the TabControl's general presentation for the control's structure, respectively adding, deleting or disabling Tab objects.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="timer">
</SECTION>
## Timer
Implements a timer which raises an event at pre-defined intervals.<br>

### Properties
* AutoRun
* Delay
* IRunning

### Methods
* SetDelay()
* Start()
* Stop()

### Description
The timer object is used when a procedure needs to be executed at a user\-defined interval. The timer will keep running until it is stopped by the user.<br>
It is possible to start the timer by default \(without user interaction\) using the AutoRun property. Main properties are Delay and AutoRun. Frequently used methods in this class are: Start() and Stop() and OnTimeOut().<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="toolbar">
</SECTION>
## ToolBar
The ToolBar is a container control holding [ToolButton](#toolbutton "ToolButton") controls \- its visual interface is usually a horizontal bar with buttons. Both the bar and the buttons can be transparent - in VXH this is the default ToolBar setup.<br>

### Properties
* BackColor
* BitMapHeight
* BitMapWidth
* Border
* DrawArrows
* Enabled
* Flat
* Font
* ForeColor
* HideClippedButtons
* HorzPadding
* HotImageList
* ImageList
* List
* MixedButtons
* Transparent
* VertPadding
* Visible

### Methods

### Description
When the ToolBar's Theming property and the Flat property are set to "false", the [ToolButton](#toolbutton "ToolButton") control has classic styling.<br>
Each ToolButton can have a sublist - an associated [ContextMenu](#contextmenu "ContextMenu"). The ToolBar's DrawArrows property in combination with the ToolButton's DropDown and WholeDropDown properties defines the visual interface for accessing the sublists.<br>
Using a ToolBar control is a good choice when we need a modern, feature-rich menu bar. The ToolBar can be used in combination with a [CoolBar](#coolbar "CoolBar") control, by setting it as BandChild to a Band of the CoolBar.<br>
We can add new ToolButtons onto the ToolBar in this way: select the control, right-click on it, and click the "Add Button" menu option. For sublists see the ToolButton control's ContextMenu property.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="toolbutton">
</SECTION>
## ToolButton
The ToolButton always appears as a child control of a [ToolBar](#toolbar "ToolBar"). Its role is to offer a selectable option for the user \(see also the Enabled property\).<br>

### Properties
* AutoSize
* BtnCheck
* Check
* CheckGroup
* ContextMenu
* DropDown
* Enabled
* ImageIndex
* Message
* Separator
* ShowText
* Text
* Theming
* ToolTip
* Visible
* WholeDropDown
* Width
* Wrap

### Methods

### Description
The control consists of a caption text, an optional image, and an optional dropdown arrow.<br>
A ToolButton can have an associated sublist. The sublist can be chosen by setting the control's ContextMenu property, respectively one of the DropDown or WholeDropDown properties.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="toolstrip">
</SECTION>
## ToolStrip
The ToolStrip control can be used as a stand-alone control, or as a child control of a [ToolStripContainer](#toolstripcontainer "ToolStipContainer"), being designed for serving as a menu system, respectively a module of a menu system.<br>

### Properties
* Enabled
* Font
* Height
* ImageList
* ImagePadding
* Row
* ShowChevron
* ShowGrip
* Theming

### Methods

### Description
A ToolStrip can hold a set of objects, instances of the following classes: [ToolStripButton](#toolstripbutton "ToolStripButton"), [ToolStripLabel](#toolstriplabel "ToolStripLabel"), [ToolStripComboBox](#toolstripcombobox "ToolStripComboBox"). Each ToolStripButton over a ToolStrip can own a submenu.<br>
Adding a new object to a ToolStrip can be done in this way: select the ToolStrip, right-click on it, and now choose the appropiate option.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="toolstripbutton">
</SECTION>
## ToolStripButton
The ToolStripButton is always created as a child control of a [ToolStrip](#toolstip "ToolStrip"), and it can serve as a [command button](#button "Button") and//or it can own a submenu.<br>

### Properties
BeginGroup
* Checked
* DropDown
* Enabled
* Font
* ImageAlign
* ImageIndex
* ImageList
* Role
* ShortCutKey
* Text

### Methods
* AfterCloseMenu()
* BeforeOpenMenu()
* Click()

### Description
In order to create a submenu for a ToolStripButton, first set its DropDown property to "Partial" or "Full", then click on it in VXH's design area, and click the appropiate "Add New Item" label.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="toolstripcombobox">
</SECTION>
## ToolStripComboBox
The ToolStripComboBox is always created as a child control of a [ToolStrip](#toolstrip "ToolStrip") or a [MenuStrip](#menustrip "MenuStrip"), and it behaves like a [ComboBox](#combobox "ComboBox") \- it inherits most properties and methods of the ComboBox control.<br>

###Properties
* AutoEditHorzScroll
* BeginGroup
* DropDownStyle
* Enabled
* Font
* LowerCase
* NoIntegralHeight
* OemConvert
* SelectionHeight
* Sort
* UpperCase
* Width

### Methods

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="toolstripcontainer">
</SECTION>
## ToolStripContainer
The ToolStripContainer is a container control designed for holding [ToolStrip](#toolstrip "ToolStrip") and // or [MenuStrip](#menustrip "MenuStrip") child controls organized in rows, as modules of a feature-rich, modern menu system.<br>

### Properties
* Enabled
* Font
* Position
* Theming

### Methods

### Description
The [ToolStrips](#toolstrip "ToolStrip") and [MenuStrips](#menustrip "MenuStrip") hold by the ToolStripContainer can have grips, and the user can move the ToolStrips around their parent - horizontally, or even vertically, into a different row.<br>
A ToolStripContainer should not be associated with a [CoolBar](#coolbar "CoolBar"). The CoolBar offers a different solution for creating a menu system, when used in combination with [CoolMenu](#coolmenu "CoolMenu") and // or [ToolBar](#toolbar "ToolBar") controls.<br>
By default the ToolStripContainer is created with a ToolStrip. Add a new ToolStrip or MenuStrip in this way: select the ToolStripContainer, right-click on it, and now choose the appropiate option, and then set the Row property of the new child control.<br>
Deleting a ToolStrip or MenuStrip is done as in case of other controls: select the control, and then press keyboard key "Del", or click on the corresponding tool button in the VXH IDE.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="toolstriplabel">
</SECTION>
## ToolStripLabel
The ToolStripLabel is always created as a child control of a [ToolStrip](#toolstrip "ToolStrip") or [MenuStrip](#menustrip "MenuStrip"), and it serves informative and // or decorative purposes /- for example as a caption text for a [ToolStripComboBox](#toolstripcombobox "ToolStripComboBox").<br>

### Properties
* Enabled
* Font
* ImageAlign
* ImageIndex
* Text

### Methods

### Description
The ToolStripLabel and the [ToolstripButton](#toolstripbutton "ToolStripButton") have similar user interfaces.

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="tooltip">
</SECTION>
## ToolTip
As object property - present in controls \- it shows brief context\-sensitive messages, when the user is hovering with the mouse cursor over the object.<br>

### Properties
* Balloon
* CenterTip
* CloseButton
* CloseOnClick
* Icon
* Text
* Title
* Track
* Transparent

### Methods

### Description
The messages are visible for few seconds, the duration being dependent on the local mouse double-click speed setting.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="treelistview">
</SECTION>
## TreeListView

### Properties

### Methods

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="treeview">
</SECTION>
## TreeView
The TreeView control represents the user interface for an abstract tree structure \(a hierarchy\) \- it's displaying and managing a collection of [TreeViewItem](#treeviewitem "TreeViewItem") objects as nodes.<br>

### Properties
* BackColor
* Border
* CheckBoxes
* ClickedItem
* Enabled
* Font
* ForeColor
* FullRowSelect
* HasButtons
* HasLines
* HighLightCaption
* ImageList
* Items
* Level
* LinesAtRoot
* NoHScroll
* NoToolTips
* PreviousItem
* SelectedItem
* ShowSelAlways
* SingleExpand
* SmallCaption
* Text
* TrackSelect
* Visible

### Methods
* AddItem()
* EditLabel()
* EnsureVisible()
* Expand()
* ExpandAll()
* GetChild()
* GetCount()
* GetFirstVisibleItem()
* GetItem()
* GetNextItem()
* GetRoot()
* GetSelText()
* GetVisibleCount()
* ResetCount()
* SelectItem()
* SetImageList()
* SetIndent()
* SetItemHeight()
* SetTextColor()
* Toggle()

### Description
VXH's TreeView control implements the standard Windows TreeView control.<br>
The TreeView control consists of a rectangular panel holding zero or more [TreeViewItem](#treeviewitem "TreeViewItem") objects, an optional small title bar, and scroll bars as needed.<br>
Each TreeViewItem has a label \(text caption\), an optional image from the TreeView's [ImageList](#imagelist "ImageList"), and a list of zero or more child items \- see the Items property. The items, which have child items, can have buttons \- see the HasButtons property.<br>
TreeViewItems having child items can be expanded or collapsed by double-clicking on them, or clicking on their buttons \(if present\).<br>
The user selections can be tracked by consulting the following properties: SelectedItem, ClickedItem, PreviousItem.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="treeviewitem">
</SECTION>
## TreeViewItem
A TreeViewItem is always created as a child object of a [TreeView](#treeview "TreeView") control, representing a node ( or item ) of the abstract tree structure holden by the TreeView.<br>

### Properties
* Expanded
* hItem
* ImageIndex
* Items
* Level
* Parent
* Text

### Methods
* AddItem()
* Delete()
* EditLabel()
* EnsureVisible()
* Expand()
* ExpandAll()
* GetChild()
* GetItemRect()
* GetNextItem()
* Select()
* SetItemState()
* SetItemText()
* SortChildren()
* Toggle()

### Description
A TreeViewItem consists of a label, an optional image decoration belonging to the [ImageList](#imagelist "ImageList") set for the parent [TreeView](#treeview "TreeView"), and a list with zero or more child items \(see the Items property\).<br>
A TreeViewItem can be described by a set of state attributes: currently selected or not \(see Select method\); expanded or collapsed, when it has at least a child item \(see Expand and Toggle methods\).<br>
A TreeViewItem can be made visible in the parent TreeView's panel by using the EnsureVisible method.<br>
AddItem, Delete, SetItemText, SortChildren are the most frequently used methods for managing TreeViewItem objects.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="webbrowser">
</SECTION>
## WebBrowser
VXH's WebBrowser control implements Microsoft's WebBrowser control, using the Shell.Explorer class via the ActiveX technology.<br>

### Properties
* Border
* Enabled
* ProgID
* Url
* Visible

### Methods

### Description
The WebBrowser control is essentially a client module, which is sending requests to a web server, manages the events produced during navigation and the server's responses, respectively renders the documents received from the server.<br>
In the Object Manager, when possible, the event handlers in the DWebBrowserEvents2 group should be used, because the corresponding interface is newer.<br>
[Here](https://docs.microsoft.com/en-us/previous-versions/windows/internet-explorer/ie-developer/platform-apis/aa752043(v=vs.85)) is a detailed description of the original class.

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="winprint">
</SECTION>
## WinPrint
WinPrint class makes printing easy and it can also generate EMF files for Preview with PrintPreview.exe<br>

### Syntax
```
oPrn := WinPrint():New( [<lPreview>] )
```

### Arguments
```
<lPreview> is .T. for Preview and .F. for printing. It's optional. Default value is .F.
```

### Properties
* cFormType
* cHexShadowColor
* cPrinter
* lAskProperties
* lBestQuality
* lDuplex
* lGrayScale
* lLandscape
* lLatePrn
* lPreview
* nBottomMargin
* nCharHeight
* nCopies
* nLeftMargin
* nPage
* nPageHeight
* nPageWidth
* nRightMargin
* nTopMargin
* oPrinter

### Methods
* Box()
* Close()
* Create()
* GetJustifiedString()
* GetPageHeight()
* GetPageWidth()
* GetTextArray()
* GetTextHeightMM()
* GetTextWidthMM()
* Image()
* Line()
* mm2ActX()
* mm2ActY()
* mm2X()
* mm2Y()
* PageBreak()
* Preview()
* Say()
* SetFont()
* SetFontArray()
* SetPenWidth()
* Shadow()
* x2mm()
* Y2mm()

### Description
WinPrint class makes printing easier. It uses xHarbour Win32Prn() class with added more functionalities. It can also create EMF files for Preview with PrintPreview.exe.<br>

### Example
```
// Following function will test WinPrint class

FUNCTION WinPrintTest(lPreview)

   LOCAL oPrn,nLineWidth,cText,cPath

   DEFAULT lPreview TO .T.
   
   oPrn:=WinPrint():New(lPreview)  

   IF oPrn=NIL
      MsgAlert("Can't create WinPrint object")
      RETURN NIL
   ENDIF
   
   WITH OBJECT oPrn
      :nTopMargin:=10
      :nLeftMargin:=10
      :nRightMargin:=10
      :nBottomMargin:=10

      :cPrinter:=GetDefaultPrinter()
      :cFormType:="9" // A4 page

      IF !:Create()
         MsgAlert("Can't create "+:cPrinter+" object")
         RETURN NIL
      ENDIF

   ENDIF

   nLineWidth:=oPrn:nPageWidth-oPrn:nLeftMargin-oPrn:nRightMargin
  
   oPrn:SetPenWidth(0.1)
   
   oPrn:SetFont("Times New Roman",10,.F.,.F.,.F.,.F.,0)
   
   cText:="Hello world with WinPrn class for VXH!"   
   oPrn:Say(oPrn:nLeftMargin,20,cText,1,nLineWidth,oPrn:GetTextHeightMM(cText,nLineWidth))
   cText:="This is page 1 test."   
   oPrn:Say(oPrn:nLeftMargin,120,cText,1,nLineWidth,oPrn:GetTextHeightMM(cText,nLineWidth))   
   oPrn:PageBreak()

   cText:="Page 2"   
   oPrn:Say(oPrn:nLeftMargin,20,cText,1,nLineWidth,oPrn:GetTextHeightMM(cText,nLineWidth))
   oPrn:PageBreak()

   cText:="Page 3"   
   oPrn:Say(oPrn:nLeftMargin,20,cText,1,nLineWidth,oPrn:GetTextHeightMM(cText,nLineWidth))
   //oPrn:PageBreak()

   IF lPreview
      oPrn:Preview(Self)
   ENDIF
   
   oPrn:Close()
   
RETURN NIL
```
### Info
* **Category**: VXH Class
* **LIB**: vxh.lib



---

<SECTION ID="winsock">
</SECTION>
## WinSock
The WinSock class is VXH's Windows Sockets implementation, based on xHarbour's Inet* functions, providing the means for receiving or transmitting data from socket to socket \- designed to support event-driven programming style.<br>

### Properties
* Handle
* LocalPort
* Protocol
* RecData
* RemoteHandle
* RemoteIP
* RemotePort
* Status

### Methods
* Close()
* Connect()
* Listen()
* Send()

### Description
When a WinSock object is being created, a raw socket is created and associated with the object \(also referred as local socket\), and the Connect method establishes the communication with a remote socket.<br>
A WinSock object in a VXH application can act as a client or as a server; the timeout intrevals are defaulting to 250 milliseconds.<br>
When the connection is no more needed, it should be closed by a Close method call.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib


---

<SECTION ID="zip">
</SECTION>
## Zip
The ZIP class has the common zip functionalities with ease.<br>

### Syntax
```
Zip:New( <cFile> )
```
### Arguments
```
<cFile> Zip file name to be created. If <cFile> already exits, it will be deleted and a new file with the same name will be created.
```

### Properties
* aExclude
* bProgress
* CompressLevel
* Error
* File
* FullPath
* Password

### Methods
* AddFile()
* Close()

### Description
The Zip class creates a zip file, adds files to it along with common Zip functionalities.<br>

### Info
* **Category**: VXH Class
* **LIB**: vxh.lib

---
</div>

</div>