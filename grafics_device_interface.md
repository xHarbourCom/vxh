---
layout: default
title: Graphic Device Interface
---



<div class="sidenav">

<div markdown="1">

[AddFontResource](#addfontresource)
[AnimatePalette](#animatepalette)
[BitBlt](#bitblt)
[CreateBitmap](#createbitmap)
[CreateCompatibleBitmap](#createcompatiblebitmap)
[CreateCompatibleDC](#createcompatibledc)
[CreateDC](#createdc)
[CreateDIBitmap](#createdibitmap)
[CreateFont](#createfont)
[CreateFontIndirect](#createfontindirect)
[CreateHalftonePalette](#createhalftonepalette)
[CreatePalette](#createpalette)
[CreatePatternBrush](#createpatternbrush)
[CreatePen](#createpen)
[CreateRectRgn](#createrectrgn)
[CreateSolidBrush](#createsolidbrush)
[DeleteDC](#deletedc)
[DeleteObject](#deleteobject)
[DPtoLP](#dptolp)
[EnumFontFamilies](#enumfontfamilies)
[EnumFonts](#enumfonts)
[ExtTextOut](#exttextout)
[GetBkColor](#getbkcolor)
[GetClipBox](#getclipbox)
[GetDCBrushColor](#getdcbrushcolor)
[GetDCOrgEx](#getdcorgex)
[GetDeviceCaps](#getdevicecaps)
[GetMapMode](#getmapmode)
[GetNearestColor](#getnearestcolor)
[GetNearestPaletteIndex](#getnearestpaletteindex)
[GetObject](#getobject)
[GetPixel](#getpixel)
[GetStockObject](#getstockobject)
[GetTextColor](#gettextcolor)
[GetTextExtentPont32](#gettextextentpont32)
[GetTextMetrics](#gettextmetrics)
[LineTo](#lineto)
[LPtoDP](#lptodp)
[MoveToEx](#movetoex)
[PatBlt](#patblt)
[Polygon](#polygon)
[Polyline](#polyline)
[RealizePalette](#realizepalette)
[Rectangle](#rectangle)
[RemoveFontResource](#removefontresource)
[ResetDC](#resetdc)
[ResizePalette](#resizepalette)
[RestoreDC](#restoredc)
[SaveDC](#savedc)
[SelectObject](#selectobject)
[SelectPalette](#selectpalette)
[SetBkColor](#setbkcolor)
[SetBkMode](#setbkmode)
[SetBrushOrgEx](#setbrushorgex)
[SetMapMode](#setmapmode)
[SetPixel](#setpixel)
[SetROP2](#setrop2)
[SetTextAlign](#settextalign)
[SetTextColor](#settextcolor)
[SetViewPortExtEx](#setviewportextex)
[TextOut](#textout)
[UnrealizeObject](#unrealizeobject)
[UpdateColors](#updatecolors)

</div>

</div>


<div class="right_main">

<div markdown="1">


Graphic Device Interface
====================

---

<SECTION ID="addfontresource"></SECTION>
## AddFontResource
The AddFontResource function adds the font resource from the specified file to the system font table. The font can subsequently be used for text output by any application.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-addfontresourcea" target="_blank">here</a>


---

<SECTION ID="animatepalette"></SECTION>
## AnimatePalette
The AnimatePalette function replaces entries in the specified logical palette.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-animatepalette" target="_blank">here</a>


---

<SECTION ID="bitblt"></SECTION>
## BitBlt
The BitBlt function performs a bit-block transfer of the color data corresponding to a rectangle of pixels from the specified source device context into a destination device context.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-bitblt" target="_blank">here</a>


---

<SECTION ID="createbitmap"></SECTION>
## CreateBitmap
The CreateBitmap function creates a bitmap with the specified width, height, and color format (color planes and bits-per-pixel).

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-createbitmap" target="_blank">here</a>



---

<SECTION ID="createcompatiblebitmap"></SECTION>
## CreateCompatibleBitmap
The CreateCompatibleBitmap function creates a bitmap compatible with the device that is associated with the specified device context.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-createcompatiblebitmap" target="_blank">here</a>


---


<SECTION ID="createcompatibledc"></SECTION>
## CreateCompatibleDC
The CreateCompatibleDC function creates a memory device context (DC) compatible with the specified device.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-createcompatibledc" target="_blank">here</a>


---

<SECTION ID="createdc"></SECTION>
## CreateDC
The CreateDC function creates a device context (DC) for a device using the specified name.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-createdca" target="_blank">here</a>



---

<SECTION ID="createdibitmap"></SECTION>
## CreateDIBitmap
The CreateDIBitmap function creates a compatible bitmap (DDB) from a DIB and, optionally, sets the bitmap bits.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-createdibitmap" target="_blank">here</a>


---

<SECTION ID="createfont"></SECTION>
## CreateFont
The CreateFont function creates a logical font with the specified characteristics. The logical font can subsequently be selected as the font for any device.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-createfonta" target="_blank">here</a>



---

<SECTION ID="createfontindirect"></SECTION>
## CreateFontIndirect
The CreateFontIndirect function creates a logical font that has the specified characteristics. The font can subsequently be selected as the current font for any device context.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-createfontindirecta" target="_blank">here</a>


---

<SECTION ID="createhalftonepalette"></SECTION>
## CreateHalftonePalette
The CreateHalftonePalette function creates a halftone palette for the specified device context (DC).

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-createhalftonepalette" target="_blank">here</a>



---

<SECTION ID="createpalette"></SECTION>
## CreatePalette
The CreatePalette function creates a logical palette.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-createpalette" target="_blank">here</a>



---

<SECTION ID="createhalftonepalette"></SECTION>
## CreateHalftonePalette
The CreatePatternBrush function creates a logical brush with the specified bitmap pattern. The bitmap can be a DIB section bitmap, which is created by the CreateDIBSection function, or it can be a device-dependent bitmap

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-createpatternbrush" target="_blank">here</a>



---

<SECTION ID="createpen"></SECTION>
## CreatePen
The CreatePen function creates a logical pen that has the specified style, width, and color. The pen can subsequently be selected into a device context and used to draw lines and curves.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-createpen" target="_blank">here</a>




---


<SECTION ID="createrectrgn"></SECTION>
## CreateRectRgn
he CreateRectRgn function creates a rectangular region.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-createrectrgn" target="_blank">here</a>



---


<SECTION ID="createsolidbrush"></SECTION>
## CreateSolidBrush
The CreateSolidBrush function creates a logical brush that has the specified solid color.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-createrectrgn" target="_blank">here</a>




---

<SECTION ID="deletedc"></SECTION>
## DeleteDC
The DeleteDC function deletes the specified device context (DC).

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-deletedc" target="_blank">here</a>



---

<SECTION ID="deleteobject"></SECTION>
## DeleteObject
The DeleteObject function deletes a logical pen, brush, font, bitmap, region, or palette, freeing all system resources associated with the object. After the object is deleted, the specified handle is no longer valid.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-deleteobject" target="_blank">here</a>



---

<SECTION ID="dptolp"></SECTION>
## DPtoLP
The DPtoLP function converts device coordinates into logical coordinates. The conversion depends on the mapping mode of the device context, the settings of the origins and extents for the window and viewport, and the world transformation.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-dptolp" target="_blank">here</a>


---

<SECTION ID="enumfontfamilies"></SECTION>
## EnumFontFamilies
The EnumFontFamilies function enumerates the fonts in a specified font family that are available on a specified device.

### Description
Note This function is provided only for compatibility with 16-bit versions of Windows. Applications should use the EnumFontFamiliesEx function.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-enumfontfamiliesa" target="_blank">here</a>



---

<SECTION ID="enumfonts"></SECTION>
## EnumFonts
The EnumFonts function enumerates the fonts available on a specified device. For each font with the specified typeface name, the EnumFonts function retrieves information about that font and passes it to the application defined callback function.

### Description
This callback function can process the font information as desired. Enumeration continues until there are no more fonts or the callback function returns zero.<br> 
Note This function is provided only for compatibility with 16-bit versions of Windows. Applications should use the EnumFontFamiliesEx function.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-enumfontsa" target="_blank">here</a>



---

<SECTION ID="exttextout"></SECTION>
## ExtTextOut
The ExtTextOut function draws text using the currently selected font, background color, and text color. You can optionally provide dimensions to be used for clipping, opaquing, or both.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-exttextouta" target="_blank">here</a>



---

<SECTION ID="getbkcolor"></SECTION>
## GetBkColor
The GetBkColor function returns the current background color for the specified device context.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-getbkcolor" target="_blank">here</a>

---

<SECTION ID="getclipbox"></SECTION>
## GetClipBox
The GetClipBox function retrieves the dimensions of the tightest bounding rectangle that can be drawn around the current visible area on the device.

### Description
The visible area is defined by the current clipping region or clip path, as well as any overlapping windows.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-getclipbox" target="_blank">here</a>



---

<SECTION ID="getdcbrushcolor"></SECTION>
## GetDCBrushColor
The GetDCBrushColor function retrieves the current brush color for the specified device context (DC).

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-getdcbrushcolor" target="_blank">here</a>



---

<SECTION ID="getdcorgex"></SECTION>
## GetDCOrgEx
The GetDCOrgEx function retrieves the final translation origin for a specified device context (DC).

### Description
The final translation origin specifies an offset that the system uses to translate device coordinates into client coordinates (for coordinates in an application's window).

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-getdcorgex" target="_blank">here</a>




---

<SECTION ID="getdevicecaps"></SECTION>
## GetDeviceCaps
The GetDeviceCaps function retrieves device-specific information for the specified device.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-getdevicecaps" target="_blank">here</a>





---

<SECTION ID="getmapmode"></SECTION>
## GetMapMode
The GetMapMode function retrieves the current mapping mode.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-getmapmode" target="_blank">here</a>




---

<SECTION ID="getnearestcolor"></SECTION>
## GetNearestColor
The GetNearestColor function retrieves a color value identifying a color from the system palette that will be displayed when the specified color value is used.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-getnearestcolor" target="_blank">here</a>



---

<SECTION ID="getnearestpaletteindex"></SECTION>
## GetNearestPaletteIndex
The GetNearestPaletteIndex function retrieves the index for the entry in the specified logical palette most closely matching a specified color value.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-us/previous-versions//dd144903(v=vs.85)" target="_blank">here</a>



---

<SECTION ID="getobject"></SECTION>
## GetObject
The GetObject function retrieves information for the specified graphics object.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-getobject" target="_blank">here</a>



---

<SECTION ID="getpixel"></SECTION>
## GetPixel
The GetPixel function retrieves the red, green, blue (RGB) color value of the pixel at the specified coordinates.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-getpixel" target="_blank">here</a>




---

<SECTION ID="getstockobject"></SECTION>
## GetStockObject
The GetStockObject function retrieves a handle to one of the stock pens, brushes, fonts, or palettes.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-getstockobject" target="_blank">here</a>





---

<SECTION ID="GetTextColor"></SECTION>
## GetTextColor
The GetTextColor function retrieves the current text color for the specified device context.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-gettextcolor" target="_blank">here</a>



---

<SECTION ID="gettextextentpont32"></SECTION>
## GetTextExtentPont32
The GetTextExtentPoint32 function computes the width and height of the specified string of text.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-gettextextentpoint32a" target="_blank">here</a>




---

<SECTION ID="gettextmetrics"></SECTION>
## GetTextMetrics
The GetTextMetrics function fills the specified buffer with the metrics for the currently selected font.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-gettextmetrics" target="_blank">here</a>




---

<SECTION ID="lineto"></SECTION>
## LineTo
The LineTo function draws a line from the current position up to, but not including, the specified point.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-lineto" target="_blank">here</a>



---

<SECTION ID="lptodp"></SECTION>
## LPtoDP
The LPtoDP function converts logical coordinates into device coordinates.

### Description
The conversion depends on the mapping mode of the device context, the settings of the origins and extents for the window and viewport, and the world transformation.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-lptodp" target="_blank">here</a>




---

<SECTION ID="movetoex"></SECTION>
## MoveToEx
The MoveToEx function updates the current position to the specified point and optionally returns the previous position.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-movetoex" target="_blank">here</a>



---

<SECTION ID="patblt"></SECTION>
## PatBlt
The PatBlt function paints the specified rectangle using the brush that is currently selected into the specified device context. The brush color and the surface color or colors are combined by using the specified raster operation.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-patblt" target="_blank">here</a>




---

<SECTION ID="polygon"></SECTION>
## Polygon
The Polygon function draws a polygon consisting of two or more vertices connected by straight lines. The polygon is outlined by using the current pen and filled by using the current brush and polygon fill mode.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-polygon" target="_blank">here</a>




---

<SECTION ID="polyline"></SECTION>
## Polyline
The Polyline function draws a series of line segments by connecting the points in the specified array.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-polyline" target="_blank">here</a>



---

<SECTION ID="realizepalette"></SECTION>
## RealizePalette
The RealizePalette function maps palette entries from the current logical palette to the system palette.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-realizepalette" target="_blank">here</a>



---

<SECTION ID="rectangle"></SECTION>
## Rectangle
The Rectangle function draws a rectangle. The rectangle is outlined by using the current pen and filled by using the current brush.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-rectangle" target="_blank">here</a>



---

<SECTION ID="removefontresource"></SECTION>
## RemoveFontResource
The RemoveFontResource function removes the fonts in the specified file from the system font table.

### Description
If the font was added using the AddFontResourceEx function, you must use the RemoveFontResourceEx function.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-removefontresourcea" target="_blank">here</a>



---

<SECTION ID="restdc"></SECTION>
## RestDC
The ResetDC function updates the specified printer or plotter device context (DC) using the specified information.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-resetdca" target="_blank">here</a>



---

<SECTION ID="removefontresource"></SECTION>
## RemoveFontResource
The RemoveFontResource function removes the fonts in the specified file from the system font table.

### Description
If the font was added using the AddFontResourceEx function, you must use the RemoveFontResourceEx function.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-removefontresourcea" target="_blank">here</a>



---

<SECTION ID="resetdc"></SECTION>
## ResetDC
The ResetDC function updates the specified printer or plotter device context (DC) using the specified information.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-resetdca" target="_blank">here</a>


---

<SECTION ID="resizepalette"></SECTION>
## ResizePalette## 
The ResizePalette function increases or decreases the size of a logical palette based on the specified value.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-resizepalette" target="_blank">here</a>


---

<SECTION ID="restoredc"></SECTION>
## RestoreDC
The RestoreDC function restores a device context (DC) to the specified state. The DC is restored by popping state information off a stack created by earlier calls to the SaveDC function.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-restoredc" target="_blank">here</a>


---

<SECTION ID="savedc"></SECTION>
## SaveDC
The SaveDC function saves the current state of the specified device context (DC) by copying data describing selected objects and graphic modes (such as the bitmap, brush, palette, font, pen, region, drawing mode, and mapping mode) to a context stack.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-savedc" target="_blank">here</a>



---

<SECTION ID="selectobject"></SECTION>
## SelectObject
The SelectObject function selects an object into the specified device context (DC). The new object replaces the previous object of the same type.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-selectobject" target="_blank">here</a>


---

<SECTION ID="selectpalette"></SECTION>
## SelectPalette
The SelectPalette function selects the specified logical palette into a device context.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-selectpalette" target="_blank">here</a>


---

<SECTION ID="setbkcolor"></SECTION>
## SetBkColor
The SetBkColor function sets the current background color to the specified color value, or to the nearest physical color if the device cannot represent the specified color value.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-setbkcolor" target="_blank">here</a>


---

<SECTION ID="setbkmode"></SECTION>
## SetBkMode
The SetBkMode function sets the background mix mode of the specified device context. The background mix mode is used with text, hatched brushes, and pen styles that are not solid lines.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-setbkmode" target="_blank">here</a>


--

<SECTION ID="setbrushorgex"></SECTION>
## SetBrushOrgEx
The SetBrushOrgEx function sets the brush origin that GDI assigns to the next brush an application selects into the specified device context.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-setbrushorgex" target="_blank">here</a>


---

<SECTION ID="setmapmode"></SECTION>
## SetMapMode
The SetMapMode function sets the mapping mode of the specified device context.

### Description
The mapping mode defines the unit of measure used to transform page-space units into device-space units, and also defines the orientation of the device's x and y axes.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-setmapmode" target="_blank">here</a>


---

<SECTION ID="setpixel"></SECTION>
## SetPixel
The SetPixel function sets the pixel at the specified coordinates to the specified color.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-setpixel" target="_blank">here</a>


---

<SECTION ID="setrop2"></SECTION>
## SetROP2
The SetROP2 function sets the current foreground mix mode. GDI uses the foreground mix mode to combine pens and interiors of filled objects with the colors already on the screen.

### Description
The foreground mix mode defines how colors from the brush or pen and the colors in the existing image are to be combined.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-setrop2" target="_blank">here</a>


---

<SECTION ID="settextalign"></SECTION>
## SetTextAlign
The SetTextAlign function sets the text-alignment flags for the specified device context.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-settextalign" target="_blank">here</a>


---

<SECTION ID="settextcolor"></SECTION>
## SetTextColor
The SetTextColor function sets the text color for the specified device context to the specified color.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-settextcolor" target="_blank">here</a>


---

<SECTION ID="setviewportextex"></SECTION>
## SetViewPortExtEx
The SetViewportExtEx function sets the horizontal and vertical extents of the viewport for a device context by using the specified values.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-setviewportextex" target="_blank">here</a>


---

<SECTION ID="textout"></SECTION>
## TextOut
The TextOut function writes a character string at the specified location, using the currently selected font, background color, and text color.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-textouta" target="_blank">here</a>


---

<SECTION ID="unrealizeobject"></SECTION>
## UnrealizeObject
The UnrealizeObject function resets the origin of a brush or resets a logical palette. If the hgdiobj parameter is a handle to a brush, UnrealizeObject directs the system to reset the origin of the brush the next time it is selected.

### Description
If the hgdiobj parameter is a handle to a logical palette, UnrealizeObject directs the system to realize the palette as though it had not previously been realized. The next time the application calls the RealizePalette function for the specified palette, the system completely remaps the logical palette to the system palette.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-unrealizeobject" target="_blank">here</a>


---

<SECTION ID="updatecolors"></SECTION>
## UpdateColors
The UpdateColors function updates the client area of the specified device context by remapping the current colors in the client area to the currently realized logical palette.

### Info
* **Category**: gdi
* **DLL**: Gdi32.dll
* **MSDN link**: <a href="https://docs.microsoft.com/en-in/windows/win32/api/wingdi/nf-wingdi-updatecolors" target="_blank">here</a>


---

</div>

</div>