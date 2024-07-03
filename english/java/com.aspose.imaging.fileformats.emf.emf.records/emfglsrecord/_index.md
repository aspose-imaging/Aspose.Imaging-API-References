---
title: EmfGlsRecord
second_title: Aspose.Imaging for Java API Reference
description: The EMR_GLSRECORD record specifies an OpenGL function.
type: docs
weight: 64
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfglsrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfOpenGlRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfopenglrecordtype)
```
public final class EmfGlsRecord extends EmfOpenGlRecordType
```

The EMR\_GLSRECORD record specifies an OpenGL function.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfGlsRecord(EmfRecord source)](#EmfGlsRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfGlsRecord` class. |
## Methods

| Method | Description |
| --- | --- |
| [getCbData()](#getCbData--) | Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the Data field. |
| [setCbData(int value)](#setCbData-int-) | Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the Data field. |
| [getData()](#getData--) | Gets or sets an optional array of bytes of cbData length that specifies data for the OpenGL function. |
| [setData(byte[] value)](#setData-byte---) | Gets or sets an optional array of bytes of cbData length that specifies data for the OpenGL function. |
### EmfGlsRecord(EmfRecord source) {#EmfGlsRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfGlsRecord(EmfRecord source)
```


Initializes a new instance of the `EmfGlsRecord` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the Data field. If this value is zero, no data is attached to this record.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the Data field. If this value is zero, no data is attached to this record.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Gets or sets an optional array of bytes of cbData length that specifies data for the OpenGL function.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Gets or sets an optional array of bytes of cbData length that specifies data for the OpenGL function.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

