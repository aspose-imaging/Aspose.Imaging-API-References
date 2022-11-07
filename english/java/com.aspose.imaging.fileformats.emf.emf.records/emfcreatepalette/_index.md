---
title: EmfCreatePalette
second_title: Aspose.Imaging for Java API Reference
description: The EMR_CREATEPALETTE record defines a logical palette for graphics operations.
type: docs
weight: 39
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreatePalette extends EmfObjectCreationRecordType
```

The EMR\_CREATEPALETTE record defines a logical palette for graphics operations.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfCreatePalette(EmfRecord source)](#EmfCreatePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfCreatePalette` class. |
## Methods

| Method | Description |
| --- | --- |
| [getIhPal()](#getIhPal--) | Gets or sets a 32-bit unsigned integer that specifies the index of the logical palette object in the EMF Object Table (section 3.1.1.1). |
| [setIhPal(int value)](#setIhPal-int-) | Gets or sets a 32-bit unsigned integer that specifies the index of the logical palette object in the EMF Object Table (section 3.1.1.1). |
| [getLogPalette()](#getLogPalette--) | Gets or sets a LogPalette object (section 2.2.17). |
| [setLogPalette(EmfLogPalette value)](#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-) | Gets or sets a LogPalette object (section 2.2.17). |
### EmfCreatePalette(EmfRecord source) {#EmfCreatePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreatePalette(EmfRecord source)
```


Initializes a new instance of the `EmfCreatePalette` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


Gets or sets a 32-bit unsigned integer that specifies the index of the logical palette object in the EMF Object Table (section 3.1.1.1). This index MUST be saved so that this object can be reused or modified.

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the index of the logical palette object in the EMF Object Table (section 3.1.1.1). This index MUST be saved so that this object can be reused or modified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLogPalette() {#getLogPalette--}
```
public EmfLogPalette getLogPalette()
```


Gets or sets a LogPalette object (section 2.2.17). The Version field of this object MUST be set to 0x0300. If the NumberOfEntries value in this object is zero, processing of this record MUST fail.

**Returns:**
[EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette)
### setLogPalette(EmfLogPalette value) {#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-}
```
public void setLogPalette(EmfLogPalette value)
```


Gets or sets a LogPalette object (section 2.2.17). The Version field of this object MUST be set to 0x0300. If the NumberOfEntries value in this object is zero, processing of this record MUST fail.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette) |  |

