---
title: ColorPalette
second_title: Aspose.Imaging for Java API Reference
description: Defines an array of colors that make up a color palette.
type: docs
weight: 28
url: /java/com.aspose.imaging/colorpalette/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.IColorPalette](../../com.aspose.imaging/icolorpalette)
```
public final class ColorPalette implements IColorPalette
```

Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable.
## Constructors

| Constructor | Description |
| --- | --- |
| [ColorPalette(int[] argb32Entries, boolean isCompactPalette)](#ColorPalette-int---boolean-) | Initializes a new instance of the `ColorPalette` class. |
| [ColorPalette(int[] argb32Entries)](#ColorPalette-int---) | Initializes a new instance of the `ColorPalette` class and IsCompactPalette is false. |
| [ColorPalette(Color[] entries, boolean isCompactPalette)](#ColorPalette-com.aspose.imaging.Color---boolean-) | Initializes a new instance of the `ColorPalette` class. |
| [ColorPalette(Color[] entries)](#ColorPalette-com.aspose.imaging.Color---) | Initializes a new instance of the `ColorPalette` class and IsCompactPalette is false. |
## Methods

| Method | Description |
| --- | --- |
| [getEntriesCount()](#getEntriesCount--) | Gets the entries count. |
| [getArgb32Entries()](#getArgb32Entries--) | Gets an array of 32-bit ARGB structures. |
| [getEntries()](#getEntries--) | Gets an array of `com.aspose.imaging.Color` structures. |
| [isCompactPalette()](#isCompactPalette--) | Gets or sets a value indicating whether compact palette is used. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.imaging.IColorPalette-boolean-) | Copies the palette. |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.imaging.IColorPalette-) | Copies the palette. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Gets the index of the nearest color. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.imaging.Color-) | Gets the index of the nearest color. |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Gets the 32-bit ARGB palette color by index. |
| [getColor(int index)](#getColor-int-) | Gets the palette color by index. |
### ColorPalette(int[] argb32Entries, boolean isCompactPalette) {#ColorPalette-int---boolean-}
```
public ColorPalette(int[] argb32Entries, boolean isCompactPalette)
```


Initializes a new instance of the `ColorPalette` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| argb32Entries | int[] | The 32-bit ARGB color palette entries. |
| isCompactPalette | boolean | Indicating whether compact it palette. |

### ColorPalette(int[] argb32Entries) {#ColorPalette-int---}
```
public ColorPalette(int[] argb32Entries)
```


Initializes a new instance of the `ColorPalette` class and IsCompactPalette is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| argb32Entries | int[] | The 32-bit ARGB color palette entries. |

### ColorPalette(Color[] entries, boolean isCompactPalette) {#ColorPalette-com.aspose.imaging.Color---boolean-}
```
public ColorPalette(Color[] entries, boolean isCompactPalette)
```


Initializes a new instance of the `ColorPalette` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.imaging/color) | The color palette entries. |
| isCompactPalette | boolean | Indicating whether compact it palette. |

### ColorPalette(Color[] entries) {#ColorPalette-com.aspose.imaging.Color---}
```
public ColorPalette(Color[] entries)
```


Initializes a new instance of the `ColorPalette` class and IsCompactPalette is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.imaging/color) | The color palette entries. |

### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


Gets the entries count.

**Returns:**
int - The entries count.
### getArgb32Entries() {#getArgb32Entries--}
```
public int[] getArgb32Entries()
```


Gets an array of 32-bit ARGB structures.

**Returns:**
int[] - The entries. The copy of array of the 32-bit ARGB values that make up this [ColorPalette](../../com.aspose.imaging/colorpalette).
### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


Gets an array of `com.aspose.imaging.Color` structures.

**Returns:**
com.aspose.imaging.Color[] - The entries. The copy of array of the [Color](../../com.aspose.imaging/color) structures that make up this [ColorPalette](../../com.aspose.imaging/colorpalette).
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


Gets or sets a value indicating whether compact palette is used.

**Returns:**
boolean - `true` if compact palette is used; otherwise, `false`.

Compact palette means that image will contain only the specified palette entries if possible or in other words the image will be more compact and occupy less space; otherwise there will be 2^BitsPerPixel entries and image will reserve more space for all possible palette entries. Setting this value to true and changing palette entries may cause performance penalty since data movement may occur so use it carefully.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


Copies the palette.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | The color palette. |
| useCompactPalette | boolean | Indicating whether compact palette. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.imaging.IColorPalette-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette)
```


Copies the palette.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | The color palette. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The newly created and copied palette or null if null palette passed.
### getNearestColorIndex(int argb32Color) {#getNearestColorIndex-int-}
```
public int getNearestColorIndex(int argb32Color)
```


Gets the index of the nearest color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| argb32Color | int | The 32-bit ARGB color. |

**Returns:**
int - The index of the nearest color.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.imaging.Color-}
```
public int getNearestColorIndex(Color color)
```


Gets the index of the nearest color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | The color. |

**Returns:**
int - The index of the nearest color.
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public int getArgb32Color(int index)
```


Gets the 32-bit ARGB palette color by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The 32-bit ARGB palette color index. |

**Returns:**
int - The color palette entry specified by the `index`.
### getColor(int index) {#getColor-int-}
```
public Color getColor(int index)
```


Gets the palette color by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The palette color index. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color palette entry specified by the `index`.
