---
title: EmfRop4
second_title: Aspose.Imaging for Java API Reference
description: A quaternary raster operation which specifies ternary raster operations for the foreground and background colors of a bitmap.
type: docs
weight: 107
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfrop4/
---
**Inheritance:**
java.lang.Object
```
public final class EmfRop4
```

A quaternary raster operation, which specifies ternary raster operations for the foreground and background colors of a bitmap. These values define how the color data of the source rectangle is to be combined with the color data of the destination rectangle.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfRop4(int dwordData)](#EmfRop4-int-) | Initializes a new instance of the `EmfRop4` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBackgroundRop3()](#getBackgroundRop3--) | Gets the background ROP3. |
| [getForegroundRop3()](#getForegroundRop3--) | Gets the foreground ROP3. |
### EmfRop4(int dwordData) {#EmfRop4-int-}
```
public EmfRop4(int dwordData)
```


Initializes a new instance of the `EmfRop4` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dwordData | int | The dword data. |

### getBackgroundRop3() {#getBackgroundRop3--}
```
public byte getBackgroundRop3()
```


Gets the background ROP3. The unsigned, most-significant 8 bits of a 24-bit ternary raster operation value from the WMF Ternary Raster Operation enumeration ([MS-WMF] section 2.1.1.31). This code defines how to combine the background color data of the source and destination bitmaps and brush pattern.

Value: The background ROP3.

**Returns:**
byte
### getForegroundRop3() {#getForegroundRop3--}
```
public byte getForegroundRop3()
```


Gets the foreground ROP3. The unsigned, most-significant 8 bits of a 24-bit ternary raster operation value from the WMF Ternary Raster Operation enumeration. This code defines how to combine the foreground color data of the source and destination bitmaps and brush pattern.

Value: The foreground ROP3.

**Returns:**
byte
