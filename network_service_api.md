---
layout: default
title: Network Service API
---

<div class="sidenav">

<div markdown="1">

[NetGroupEnum](#netgroupenum)
[NetGroupGetUsers](#netgroupgetusers)
[NetUserGetLocalGroups](#netusergetlocalgroups)

</div>

</div>


<div class="right_main">

<div markdown="1">


Network Service API
====================

---

<SECTION ID="netgroupenum"></SECTION>
## NetGroupEnum
The NetGroupEnum function retrieves information about each global group in the security database, which is the security accounts manager (SAM) database or, in the case of domain controllers, the Active Directory.

### Description
The NetQueryDisplayInformation function provides an efficient mechanism for enumerating global groups. When possible, it is recommended that you use NetQueryDisplayInformation instead of the NetGroupEnum function.

### Info
* **Category**: NS API
* **DLL**: Netapi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/lmaccess/nf-lmaccess-netgroupenum" target="_blank">here</a>

---

<SECTION ID="netgroupgetusers"></SECTION>
## NetGroupGetUsers
The NetGroupGetUsers function retrieves a list of the members in a particular global group in the security database, which is the security accounts manager (SAM) database or, in the case of domain controllers, the Active Directory.

### Info
* **Category**: NS API
* **DLL**: Netapi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/lmaccess/nf-lmaccess-netgroupgetusers" target="_blank">here</a>

---

<SECTION ID="netusergetlocalgroups"></SECTION>
## NetUserGetLocalGroups
The NetUserGetLocalGroups function retrieves a list of local groups to which a specified user belongs.

### Info
* **Category**: NS API
* **DLL**: Netapi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/lmaccess/nf-lmaccess-netusergetlocalgroups" target="_blank">here</a>

---

</div>

</div>
