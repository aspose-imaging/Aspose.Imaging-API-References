---
title: EmfCreateBrushIndirect
second_title: Aspose.Imaging for Java API Reference
description: The EMR_CREATEBRUSHINDIRECT record defines a logical brush for graphics operations.
type: docs
weight: 34
url: /com.aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateBrushIndirect extends EmfObjectCreationRecordType
```

The EMR\_CREATEBRUSHINDIRECT record defines a logical brush for graphics operations.

The logical brush object defined by this record can be selected into the playback device context by an EMR\_SELECTOBJECT record (section 2.3.8.5), which specifies the logical brush to use in subsequent graphics operations.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfCreateBrushIndirect(EmfRecord source)](#EmfCreateBrushIndirect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfCreateBrushIndirect` class. |
| [EmfCreateBrushIndirect()](#EmfCreateBrushIndirect--) | Initializes a new instance of the `EmfCreateBrushIndirect` class. |
## Methods

| Method | Description |
| --- | --- |
| [getIhBrush()](#getIhBrush--) | Gets or sets A 32-bit unsigned integer that specifies the index of the logical brush object in the EMF Object Table (section 3.1.1.1). |
| [setIhBrush(int value)](#setIhBrush-int-) | Gets or sets A 32-bit unsigned integer that specifies the index of the logical brush object in the EMF Object Table (section 3.1.1.1). |
| [getLogBrush()](#getLogBrush--) | Gets or sets A LogBrushEx object (section 2.2.12) that specifies the style, color, and pattern of the logical brush. |
| [setLogBrush(EmfLogBrushEx value)](#setLogBrush-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogBrushEx-) | Gets or sets A LogBrushEx object (section 2.2.12) that specifies the style, color, and pattern of the logical brush. |
### EmfCreateBrushIndirect(EmfRecord source) {#EmfCreateBrushIndirect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateBrushIndirect(EmfRecord source)
```


Initializes a new instance of the `EmfCreateBrushIndirect` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfCreateBrushIndirect() {#EmfCreateBrushIndirect--}
```
public EmfCreateBrushIndirect()
```


Initializes a new instance of the `EmfCreateBrushIndirect` class.

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


Gets or sets A 32-bit unsigned integer that specifies the index of the logical brush object in the EMF Object Table (section 3.1.1.1). This index MUST be saved so that this object can be reused or modified.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Gets or sets A 32-bit unsigned integer that specifies the index of the logical brush object in the EMF Object Table (section 3.1.1.1). This index MUST be saved so that this object can be reused or modified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLogBrush() {#getLogBrush--}
```
public EmfLogBrushEx getLogBrush()
```


Gets or sets A LogBrushEx object (section 2.2.12) that specifies the style, color, and pattern of the logical brush. The BrushStyle field in this object MUST be BS\_SOLID, BS\_HATCHED, or BS\_NULL.

**Returns:**
[EmfLogBrushEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex)
### setLogBrush(EmfLogBrushEx value) {#setLogBrush-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogBrushEx-}
```
public void setLogBrush(EmfLogBrushEx value)
```


Gets or sets A LogBrushEx object (section 2.2.12) that specifies the style, color, and pattern of the logical brush. The BrushStyle field in this object MUST be BS\_SOLID, BS\_HATCHED, or BS\_NULL.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfLogBrushEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex) |  |

