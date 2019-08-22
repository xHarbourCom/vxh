---
layout: default
title: Mail API
---

<div class="sidenav">

<div markdown="1">

[MAPISendDocuments](#mapisenddocuments)
[MAPISendMail](#mapisendmail)

</div>

</div>


<div class="right_main">

<div markdown="1">


Mail API
====================

---

<SECTION ID="mapisenddocuments"></SECTION>
## MAPISendDocuments
The use of this function is discouraged. It may be altered or unavailable in subsequent versions of Windows.

### Description
The MAPISendDocuments function sends a standard message with one or more attached files and a cover note. The cover note is a dialog box that allows the user to enter a list of recipients and an optional message. MAPISendDocuments differs from the MAPISendMail function in that it allows less flexibility in message generation.

### Info
* **Category**: vxh mail
* **DLL**: Mapi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/mapi/nc-mapi-mapisenddocuments" target="_blank">here</a>

---

<SECTION ID="mapisendmail"></SECTION>
## MAPISendMail
The MAPISendMail function sends a message. This function differs from the MAPISendDocuments function in that it allows greater flexibility in message generation.

### Info
* **Category**: vxh mail
* **DLL**: Mapi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/mapi/nc-mapi-mapisendmail" target="_blank">here</a>

---

</div>

</div>
