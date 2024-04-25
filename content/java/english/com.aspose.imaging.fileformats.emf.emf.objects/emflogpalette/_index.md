---
title: EmfLogPalette
second_title: Aspose.Imaging for Java API Reference
description: The LogPalette object specifies a logical_palette that contains device-independent color definitions.
type: docs
weight: 26
url: /com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfLogPalette extends EmfObject
```

The LogPalette object specifies a logical\_palette that contains device-independent color definitions.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfLogPalette()](#EmfLogPalette--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) | Gets or sets a 16-bit unsigned integer that specifies the version number of the system. |
| [setVersion(short value)](#setVersion-short-) | Gets or sets a 16-bit unsigned integer that specifies the version number of the system. |
| [getPaletteArgb32Entries()](#getPaletteArgb32Entries--) | Gets or sets an array of 32-bit ARGB colors. |
| [setPaletteArgb32Entries(int[] value)](#setPaletteArgb32Entries-int---) | Gets or sets an array of 32-bit ARGB colors. |
### EmfLogPalette() {#EmfLogPalette--}
```
public EmfLogPalette()
```


### getVersion() {#getVersion--}
```
public short getVersion()
```


Gets or sets a 16-bit unsigned integer that specifies the version number of the system. This MUST be 0x0300.

**Returns:**
short
### setVersion(short value) {#setVersion-short-}
```
public void setVersion(short value)
```


Gets or sets a 16-bit unsigned integer that specifies the version number of the system. This MUST be 0x0300.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getPaletteArgb32Entries() {#getPaletteArgb32Entries--}
```
public int[] getPaletteArgb32Entries()
```


Gets or sets an array of 32-bit ARGB colors.

**Returns:**
int[]
### setPaletteArgb32Entries(int[] value) {#setPaletteArgb32Entries-int---}
```
public void setPaletteArgb32Entries(int[] value)
```


Gets or sets an array of 32-bit ARGB colors.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

