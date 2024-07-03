---
title: EmfGlsBoundedRecord
second_title: Aspose.Imaging for Java API Reference
description: The EMR_GLSBOUNDEDRECORD record specifies an OpenGL function with a bounding rectangle for output.
type: docs
weight: 63
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfOpenGlRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfopenglrecordtype)
```
public final class EmfGlsBoundedRecord extends EmfOpenGlRecordType
```

The EMR\_GLSBOUNDEDRECORD record specifies an OpenGL function with a bounding rectangle for output.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfGlsBoundedRecord(EmfRecord source)](#EmfGlsBoundedRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfGlsBoundedRecord` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines a bounding rectangle, in device units, for output produced by executing the OpenGL function. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines a bounding rectangle, in device units, for output produced by executing the OpenGL function. |
| [getCbData()](#getCbData--) | Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the Data field. |
| [setCbData(int value)](#setCbData-int-) | Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the Data field. |
| [getData()](#getData--) | Gets or sets an optional array of bytes of cbData length that specifies data for the OpenGL function. |
| [setData(byte[] value)](#setData-byte---) | Gets or sets an optional array of bytes of cbData length that specifies data for the OpenGL function. |
### EmfGlsBoundedRecord(EmfRecord source) {#EmfGlsBoundedRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfGlsBoundedRecord(EmfRecord source)
```


Initializes a new instance of the `EmfGlsBoundedRecord` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines a bounding rectangle, in device units, for output produced by executing the OpenGL function.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines a bounding rectangle, in device units, for output produced by executing the OpenGL function.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

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

