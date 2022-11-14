---
title: EmfPlusPalette
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusPalette object specifies the colors that make up a palette.
type: docs
weight: 57
url: /java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPalette extends EmfPlusStructureObjectType
```

The EmfPlusPalette object specifies the colors that make up a palette.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusPalette()](#EmfPlusPalette--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getPaletteStyleFlags()](#getPaletteStyleFlags--) | Gets or sets the palette style flags. |
| [setPaletteStyleFlags(int value)](#setPaletteStyleFlags-int-) | Gets or sets the palette style flags. |
| [getArgb32Entries()](#getArgb32Entries--) | Gets or sets the palette entries. |
| [setArgb32Entries(int[] value)](#setArgb32Entries-int---) | Gets or sets the palette entries. |
### EmfPlusPalette() {#EmfPlusPalette--}
```
public EmfPlusPalette()
```


### getPaletteStyleFlags() {#getPaletteStyleFlags--}
```
public int getPaletteStyleFlags()
```


Gets or sets the palette style flags.

Value: PaletteStyleFlags (4 bytes): A 32-bit unsigned integer that specifies the attributes of data in the palette. This value MUST be composed of `EmfPlusPaletteStyleFlags` flags.

**Returns:**
int
### setPaletteStyleFlags(int value) {#setPaletteStyleFlags-int-}
```
public void setPaletteStyleFlags(int value)
```


Gets or sets the palette style flags.

Value: PaletteStyleFlags (4 bytes): A 32-bit unsigned integer that specifies the attributes of data in the palette. This value MUST be composed of `EmfPlusPaletteStyleFlags` flags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getArgb32Entries() {#getArgb32Entries--}
```
public int[] getArgb32Entries()
```


Gets or sets the palette entries.

Value: PaletteEntries (variable): An array of PaletteCount 32-bit ARGB objects that specify the data in the palette.

**Returns:**
int[]
### setArgb32Entries(int[] value) {#setArgb32Entries-int---}
```
public void setArgb32Entries(int[] value)
```


Gets or sets the palette entries.

Value: PaletteEntries (variable): An array of PaletteCount 32-bit ARGB objects that specify the data in the palette.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

