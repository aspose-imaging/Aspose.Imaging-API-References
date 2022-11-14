---
title: EmfSetRop2
second_title: Aspose.Imaging for Java API Reference
description: The EMR_SETROP2 record defines a binary raster operation mode.
type: docs
weight: 134
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfsetrop2/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetRop2 extends EmfStateRecordType
```

The EMR\_SETROP2 record defines a binary raster operation mode.

Binary raster operation mix modes define how to combine source and destination colors when drawing with the current pen. The mix modes are binary raster operation codes, representing all possible Boolean functions of two variables, using the binary operations AND, OR, and XOR (exclusive OR), and the unary operation NOT. The mix mode is for raster devices only; it is not available for vector devices.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfSetRop2(EmfRecord source)](#EmfSetRop2-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfSetRop2` class. |
| [EmfSetRop2()](#EmfSetRop2--) | Initializes a new instance of the `EmfSetRop2` class. |
## Methods

| Method | Description |
| --- | --- |
| [getRop2Mode()](#getRop2Mode--) | Gets or sets a 32-bit unsigned integer that specifies the raster operation mode and MUST be in the WMF Binary Raster Op enumeration ([MS-WMF] section 2.1.1.2). |
| [setRop2Mode(int value)](#setRop2Mode-int-) | Gets or sets a 32-bit unsigned integer that specifies the raster operation mode and MUST be in the WMF Binary Raster Op enumeration ([MS-WMF] section 2.1.1.2). |
### EmfSetRop2(EmfRecord source) {#EmfSetRop2-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetRop2(EmfRecord source)
```


Initializes a new instance of the `EmfSetRop2` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfSetRop2() {#EmfSetRop2--}
```
public EmfSetRop2()
```


Initializes a new instance of the `EmfSetRop2` class.

### getRop2Mode() {#getRop2Mode--}
```
public int getRop2Mode()
```


Gets or sets a 32-bit unsigned integer that specifies the raster operation mode and MUST be in the WMF Binary Raster Op enumeration ([MS-WMF] section 2.1.1.2).

**Returns:**
int
### setRop2Mode(int value) {#setRop2Mode-int-}
```
public void setRop2Mode(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the raster operation mode and MUST be in the WMF Binary Raster Op enumeration ([MS-WMF] section 2.1.1.2).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

