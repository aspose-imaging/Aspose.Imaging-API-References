---
title: IColorPalette
second_title: Aspose.Imaging for Java API Reference
description: The color palette interface.
type: docs
weight: 127
url: /java/com.aspose.imaging/icolorpalette/
---```
public interface IColorPalette
```

The color palette interface.
## Methods

| Method | Description |
| --- | --- |
| [getEntriesCount()](#getEntriesCount--) | Gets the entries count. |
| [getArgb32Entries()](#getArgb32Entries--) | Gets an array of 32-bit ARGB structures. |
| [getEntries()](#getEntries--) | Gets an array of `com.aspose.imaging.Color` structures. |
| [isCompactPalette()](#isCompactPalette--) | Gets a value indicating whether compact palette is used. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Gets the index of the nearest 32-bit ARGB color. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.imaging.Color-) | Gets the index of the nearest color. |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Gets the 32-bit ARGB palette color by index. |
| [getColor(int index)](#getColor-int-) | Gets the palette color by index. |
### getEntriesCount() {#getEntriesCount--}
```
public abstract int getEntriesCount()
```


Gets the entries count.

**Returns:**
int - The entries count.
### getArgb32Entries() {#getArgb32Entries--}
```
public abstract int[] getArgb32Entries()
```


Gets an array of 32-bit ARGB structures.

**Returns:**
int[] - The copy of array of the 32-bit ARGB values that make up this [ColorPalette](../../com.aspose.imaging/colorpalette).
### getEntries() {#getEntries--}
```
public abstract Color[] getEntries()
```


Gets an array of `com.aspose.imaging.Color` structures.

**Returns:**
com.aspose.imaging.Color[] - The copy of array of the [Color](../../com.aspose.imaging/color) structures that make up this [ColorPalette](../../com.aspose.imaging/colorpalette).
### isCompactPalette() {#isCompactPalette--}
```
public abstract boolean isCompactPalette()
```


Gets a value indicating whether compact palette is used.

Compact palette means that image will contain only the specified palette entries if possible or in other words the image will be more compact and occupy less space; otherwise there will be 2^BitsPerPixel entries and image will reserve more space for all possible palette entries. Setting this value to true and changing palette entries may cause performance penalty since data movement may occur so use it carefully.

**Returns:**
boolean - `true` if compact palette is used; otherwise, `false`.
### getNearestColorIndex(int argb32Color) {#getNearestColorIndex-int-}
```
public abstract int getNearestColorIndex(int argb32Color)
```


Gets the index of the nearest 32-bit ARGB color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| argb32Color | int | The 32-bit ARGB color. |

**Returns:**
int - The index of the nearest color.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.imaging.Color-}
```
public abstract int getNearestColorIndex(Color color)
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
public abstract int getArgb32Color(int index)
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
public abstract Color getColor(int index)
```


Gets the palette color by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The palette color index. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The color palette entry specified by the `index`.
