---
title: EmfSetPaletteEntries
second_title: Aspose.Imaging for Java API Reference
description: The EMR_SETPALETTEENTRIES record defines RGB color values in a range of entries for an existing LogPalette section 2.2.17 object.
type: docs
weight: 131
url: /com.aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfSetPaletteEntries extends EmfObjectManipulationRecordType
```

The EMR\_SETPALETTEENTRIES record defines RGB color values in a range of entries for an existing LogPalette (section 2.2.17) object.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfSetPaletteEntries(EmfRecord source)](#EmfSetPaletteEntries-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfSetPaletteEntries` class. |
## Methods

| Method | Description |
| --- | --- |
| [getIhPal()](#getIhPal--) | Gets or sets a 32-bit unsigned integer that specifies the palette EMF Object Table index. |
| [setIhPal(int value)](#setIhPal-int-) | Gets or sets a 32-bit unsigned integer that specifies the palette EMF Object Table index. |
| [getStart()](#getStart--) | Gets or sets a 32-bit unsigned integer that specifies the index of the first entry to set. |
| [setStart(int value)](#setStart-int-) | Gets or sets a 32-bit unsigned integer that specifies the index of the first entry to set. |
| [getNumberofEntries()](#getNumberofEntries--) | Gets or sets a 32-bit unsigned integer that specifies the number of entries. |
| [setNumberofEntries(int value)](#setNumberofEntries-int-) | Gets or sets a 32-bit unsigned integer that specifies the number of entries. |
| [getArgb32PalEntries()](#getArgb32PalEntries--) | Gets or sets an array of LogPaletteEntry (section 2.2.18) objects, of NumberOfEntries length, which specifies the palette entry data. |
| [setArgb32PalEntries(int[] value)](#setArgb32PalEntries-int---) | Gets or sets an array of LogPaletteEntry (section 2.2.18) objects, of NumberOfEntries length, which specifies the palette entry data. |
### EmfSetPaletteEntries(EmfRecord source) {#EmfSetPaletteEntries-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetPaletteEntries(EmfRecord source)
```


Initializes a new instance of the `EmfSetPaletteEntries` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


Gets or sets a 32-bit unsigned integer that specifies the palette EMF Object Table index.

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the palette EMF Object Table index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getStart() {#getStart--}
```
public int getStart()
```


Gets or sets a 32-bit unsigned integer that specifies the index of the first entry to set.

**Returns:**
int
### setStart(int value) {#setStart-int-}
```
public void setStart(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the index of the first entry to set.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getNumberofEntries() {#getNumberofEntries--}
```
public int getNumberofEntries()
```


Gets or sets a 32-bit unsigned integer that specifies the number of entries.

**Returns:**
int
### setNumberofEntries(int value) {#setNumberofEntries-int-}
```
public void setNumberofEntries(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the number of entries.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getArgb32PalEntries() {#getArgb32PalEntries--}
```
public int[] getArgb32PalEntries()
```


Gets or sets an array of LogPaletteEntry (section 2.2.18) objects, of NumberOfEntries length, which specifies the palette entry data. The Values members do not contain any values.

**Returns:**
int[]
### setArgb32PalEntries(int[] value) {#setArgb32PalEntries-int---}
```
public void setArgb32PalEntries(int[] value)
```


Gets or sets an array of LogPaletteEntry (section 2.2.18) objects, of NumberOfEntries length, which specifies the palette entry data. The Values members do not contain any values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

