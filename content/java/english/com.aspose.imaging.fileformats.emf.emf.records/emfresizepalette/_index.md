---
title: EmfResizePalette
second_title: Aspose.Imaging for Java API Reference
description: The EMR_RESIZEPALETTE record increases or decreases the size of an existing LogPalette object section 2.2.17.
type: docs
weight: 105
url: /com.aspose.imaging.fileformats.emf.emf.records/emfresizepalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfResizePalette extends EmfObjectManipulationRecordType
```

The EMR\_RESIZEPALETTE record increases or decreases the size of an existing LogPalette object (section 2.2.17).

The new size of the LogPalette object MUST be reflected in the NumberOfEntries field in that structure.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfResizePalette(EmfRecord source)](#EmfResizePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfResizePalette` class. |
## Methods

| Method | Description |
| --- | --- |
| [getIhPal()](#getIhPal--) | Gets or sets a 32-bit unsigned integer that specifies the index of the palette object in the EMF Object Table (section 3.1.1.1). |
| [setIhPal(int value)](#setIhPal-int-) | Gets or sets a 32-bit unsigned integer that specifies the index of the palette object in the EMF Object Table (section 3.1.1.1). |
### EmfResizePalette(EmfRecord source) {#EmfResizePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfResizePalette(EmfRecord source)
```


Initializes a new instance of the `EmfResizePalette` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


Gets or sets a 32-bit unsigned integer that specifies the index of the palette object in the EMF Object Table (section 3.1.1.1).

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the index of the palette object in the EMF Object Table (section 3.1.1.1).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

