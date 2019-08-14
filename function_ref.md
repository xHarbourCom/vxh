---
layout: default
---
Function Reference
====================

<SECTION ID="adsconnect101">
</SECTION>
## AdsConnect101()
Connects to the given server or to a database in an Advantage Data Dictionary using a connection string.<br>

Please check [here](https://devzone.advantagedatabase.com/dz/webhelp/Advantage11/index.html?ace_adsconnect101.htm) for more details.<br>



<SECTION ID="adsddcreate101">
</SECTION>
## AdsDDCreate101()
Creates a data dictionary using a connection string.<br>

Please check [here](https://devzone.advantagedatabase.com/dz/webhelp/Advantage11/index.html?ace_adsddcreate101.htm) for more details.<br>



<SECTION ID="adsdddeleteindex">
</SECTION>
## AdsDDDeleteIndex()
Delete an index order associated with a table in the data dictionary.<br>

Please check [here](https://devzone.advantagedatabase.com/dz/webhelp/Advantage11/index.html?ace_adsdddeleteindex.htm) for more details.<br>



<SECTION ID="adsddexecutesqldirect">
</SECTION>
## AdsDDexecuteSQLDirect()



<SECTION ID="adsddfindobject">
</SECTION>
## AdsDDFindObject()



<SECTION ID="adsddfirstobject">
</SECTION>
## AdsDDFirstObject()



<SECTION ID="adsddfreetable">
</SECTION>
## AdsDDFreeTable()
Alters an ADT table and makes it a free Advantage table file. A free Advantage table file can be used without the need of an Advantage Data Dictionary.<br>

Please check [here](https://devzone.advantagedatabase.com/dz/webhelp/Advantage11/ace_adsddfreetable.htm) for more details.




<SECTION ID="adsddgetdatabaseproperty">
</SECTION>
## AdsDDGetDatabaseProperty()
Retrieves one database property from the data dictionary into the supplied buffer.<br>

Please check [here](https://devzone.advantagedatabase.com/dz/webhelp/Advantage11/index.html?ace_adsddgetdatabaseproperty.htm) for more details.



<SECTION ID="adsddgetindexfileproperty">
</SECTION>
## AdsDDGetIndexFileProperty()
Retrieves a property of an index file of a database table from the data dictionary.<br>

Please check [here](https://devzone.advantagedatabase.com/dz/webhelp/Advantage11/index.html?ace_adsddgetindexfileproperty.htm) for more details.




<SECTION ID="adsddgetindexproperty">
</SECTION>
## AdsDDGetIndexProperty()
Retrieves a property of an index of a database table from the data dictionary.<br>

Please check [here](https://devzone.advantagedatabase.com/dz/webhelp/Advantage11/index.html?ace_adsddgetindexproperty.htm) for more details.





<SECTION ID="adsddgrantpermission">
</SECTION>
## AdsDDGrantPermission()
Grants to a user or a user group one or more permissions to a database object.<br>

Please check [here](https://devzone.advantagedatabase.com/dz/webhelp/Advantage11/index.html?ace_adsddgrantpermission.htm) for more details.




<SECTION ID="adsddremoveindexfile">
</SECTION>
## AdsDDRemoveIndexFile()
Disassociates an index file with a database table and optionally deletes the index file permanently.<br>

Please check [here](https://devzone.advantagedatabase.com/dz/webhelp/Advantage11/index.html?ace_adsddremoveindexfile.htm) for more details.




<SECTION ID="adsddrevokepermission">
</SECTION>
## AdsDDRevokePermission()
Remove a user’s or a user group’s permissions to a database object.<br>

Please check [here](https://devzone.advantagedatabase.com/dz/webhelp/Advantage11/index.html?ace_adsddrevokepermission.htm) for more details.




<SECTION ID="adsddsetdatabaseproperty">
</SECTION>
## AdsDDSetDatabaseProperty()
Sets one database property in the data dictionary.<br>

Please check [here](https://devzone.advantagedatabase.com/dz/webhelp/Advantage11/index.html?ace_adsddsetdatabaseproperty.htm) for more details.




<SECTION ID="adsddsettableproperty">
</SECTION>
## AdsDDSetTableProperty()
Sets one table property in the data dictionary.<br>

Please check [here](https://devzone.advantagedatabase.com/dz/webhelp/Advantage11/index.html?ace_adsddsettableproperty.htm) for more details.




<SECTION ID="adsnull2blank">
</SECTION>
## AdsNull2Blank()

### Syntax
```
AdsNull2Blank( <lAnyRDD> )
```


<SECTION ID="ftsvalidatephrase">
</SECTION>
## FTSValidatePhrase()

### Syntax
```
FTSValidatePhrase( <cSearch>, <aFldList> )
```



<SECTION ID="getregole">
</SECTION>
##GetRegOle()

### Syntax
```
GetRegOle() --> aOle
```

<SECTION ID="getregolebmp">
</SECTION>
## GetRegOleBmp()

### Syntax
```
GetRegOleBmp ( <cID> ) --> hBmp
```

### Arguments
```
<cID>
```


<SECTION ID="getshortpathname">
</SECTION>
## GetShortPathName()
Retrieves the short path form of the specified path.

Please check [here](https://docs.microsoft.com/en-in/windows/win32/api/fileapi/nf-fileapi-getshortpathnamew) for more details.



<SECTION ID="iscomobject">
</SECTION>
## IsComObject()

### Syntax
```
IsComObject( < cProgId > ) --> Logical
```

### Arguments
```
<cProgId>
```



<SECTION ID="isdotnet">
</SECTION>
## IsDotNet()

### Syntax
```
IsDotNet( [<cFrameWorkPath>] , [ <cVersion> ] ) --> Logical
```

### Arguments
```
<cFrameworkPath>
Default is "c:\WINDOWS\Microsoft.NET\Framework\v2.0.50727"

<cVersion>
Defaults is ""
```



<SECTION ID="registerdotnetcomponent">
</SECTION>
## RegisterDotNetComponent()

### Syntax
```
RegisterDotNetComponent( <cDotNetDLL> , <cProgId> , <cError> )  --> Logical
```

### Arguments
```
<cDotNetDLL>

<cProgId>

<cError>
```


<SECTION ID="setsystemcursor">
</SECTION>
## SetSystemCursor()
From MSDN: "Enables an application to customize the system cursors. It replaces the contents of the system cursor specified by the id parameter with the contents of the cursor specified by the hcur parameter and then destroys hcur."
