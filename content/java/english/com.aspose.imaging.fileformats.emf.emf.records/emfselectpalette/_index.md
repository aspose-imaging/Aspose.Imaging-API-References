---
title: EmfSelectPalette
second_title: Aspose.Imaging for Java API Reference
description: The EMR_SELECTPALETTE record specifies a logical palette for the playback device context.
type: docs
weight: 114
url: /com.aspose.imaging.fileformats.emf.emf.records/emfselectpalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfSelectPalette extends EmfObjectManipulationRecordType
```

The EMR\_SELECTPALETTE record specifies a logical palette for the playback device context.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfSelectPalette(EmfRecord source)](#EmfSelectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfSelectPalette` class. |
## Methods

| Method | Description |
| --- | --- |
| [getIhPal()](#getIhPal--) | Gets or sets a 32-bit unsigned integer that specifies either the index of a LogPalette object (section 2.2.17) in the EMF Object Table or the value DEFAULT\_PALETTE, which is the index of a stock object palette from the StockObject enumeration (section 2.1.31). |
| [setIhPal(int value)](#setIhPal-int-) | Gets or sets a 32-bit unsigned integer that specifies either the index of a LogPalette object (section 2.2.17) in the EMF Object Table or the value DEFAULT\_PALETTE, which is the index of a stock object palette from the StockObject enumeration (section 2.1.31). |
### EmfSelectPalette(EmfRecord source) {#EmfSelectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSelectPalette(EmfRecord source)
```


Initializes a new instance of the `EmfSelectPalette` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


Gets or sets a 32-bit unsigned integer that specifies either the index of a LogPalette object (section 2.2.17) in the EMF Object Table or the value DEFAULT\_PALETTE, which is the index of a stock object palette from the StockObject enumeration (section 2.1.31).

This value MUST NOT be zero or the index of any other stock object.

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


Gets or sets a 32-bit unsigned integer that specifies either the index of a LogPalette object (section 2.2.17) in the EMF Object Table or the value DEFAULT\_PALETTE, which is the index of a stock object palette from the StockObject enumeration (section 2.1.31).

This value MUST NOT be zero or the index of any other stock object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

