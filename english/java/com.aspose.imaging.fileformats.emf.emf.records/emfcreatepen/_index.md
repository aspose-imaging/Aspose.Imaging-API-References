---
title: EmfCreatePen
second_title: Aspose.Imaging for Java API Reference
description: The EMR_CREATEPEN record defines a logical pen for graphics operations.
type: docs
weight: 41
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatepen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreatePen extends EmfObjectCreationRecordType
```

The EMR\_CREATEPEN record defines a logical pen for graphics operations.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfCreatePen(EmfRecord source)](#EmfCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfCreatePen` class. |
| [EmfCreatePen()](#EmfCreatePen--) | Initializes a new instance of the `EmfCreatePen` class. |
## Methods

| Method | Description |
| --- | --- |
| [getIhPen()](#getIhPen--) | Gets or sets a 32-bit unsigned integer that specifies the index of the logical pen object in the EMF Object Table (section 3.1.1.1). |
| [setIhPen(int value)](#setIhPen-int-) | Gets or sets a 32-bit unsigned integer that specifies the index of the logical pen object in the EMF Object Table (section 3.1.1.1). |
| [getLogPen()](#getLogPen--) | Gets or sets a LogPen object (section 2.2.19) that specifies the style, width, and color of the logical pen. |
| [setLogPen(EmfLogPen value)](#setLogPen-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPen-) | Gets or sets a LogPen object (section 2.2.19) that specifies the style, width, and color of the logical pen. |
### EmfCreatePen(EmfRecord source) {#EmfCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreatePen(EmfRecord source)
```


Initializes a new instance of the `EmfCreatePen` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfCreatePen() {#EmfCreatePen--}
```
public EmfCreatePen()
```


Initializes a new instance of the `EmfCreatePen` class.

### getIhPen() {#getIhPen--}
```
public int getIhPen()
```


Gets or sets a 32-bit unsigned integer that specifies the index of the logical pen object in the EMF Object Table (section 3.1.1.1). This index MUST be saved so that this object can be reused or modified.

**Returns:**
int
### setIhPen(int value) {#setIhPen-int-}
```
public void setIhPen(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the index of the logical pen object in the EMF Object Table (section 3.1.1.1). This index MUST be saved so that this object can be reused or modified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLogPen() {#getLogPen--}
```
public EmfLogPen getLogPen()
```


Gets or sets a LogPen object (section 2.2.19) that specifies the style, width, and color of the logical pen.

**Returns:**
[EmfLogPen](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpen)
### setLogPen(EmfLogPen value) {#setLogPen-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPen-}
```
public void setLogPen(EmfLogPen value)
```


Gets or sets a LogPen object (section 2.2.19) that specifies the style, width, and color of the logical pen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfLogPen](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpen) |  |

