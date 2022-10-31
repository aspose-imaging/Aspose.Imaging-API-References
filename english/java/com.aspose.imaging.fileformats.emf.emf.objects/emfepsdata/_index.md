---
title: EmfEpsData
second_title: Aspose.Imaging for Java API Reference
description: The EpsData object is a container for EPS data
type: docs
weight: 14
url: /java/com.aspose.imaging.fileformats.emf.emf.objects/emfepsdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfEpsData extends EmfObject
```

The EpsData object is a container for EPS data
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfEpsData()](#EmfEpsData--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getSizeData()](#getSizeData--) | Gets or sets a 32-bit unsigned integer that specifies the total size of this object, in bytes |
| [setSizeData(int value)](#setSizeData-int-) | Gets or sets a 32-bit unsigned integer that specifies the total size of this object, in bytes |
| [getVersion()](#getVersion--) | Gets or sets a 32-bit unsigned integer that specifies the PostScript language level. |
| [setVersion(int value)](#setVersion-int-) | Gets or sets a 32-bit unsigned integer that specifies the PostScript language level. |
| [getPoints()](#getPoints--) | Gets or sets an array of three Point28\_4 objects (section 2.2.23) that defines the coordinates of the output parallelogram using 28.4 bit FIX notation |
| [setPoints(EmfPoint28To4[] value)](#setPoints-com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4---) | Gets or sets an array of three Point28\_4 objects (section 2.2.23) that defines the coordinates of the output parallelogram using 28.4 bit FIX notation |
| [getPostScriptData()](#getPostScriptData--) | Gets or sets an array of bytes of PostScript data. |
| [setPostScriptData(byte[] value)](#setPostScriptData-byte---) | Gets or sets an array of bytes of PostScript data. |
### EmfEpsData() {#EmfEpsData--}
```
public EmfEpsData()
```


### getSizeData() {#getSizeData--}
```
public int getSizeData()
```


Gets or sets a 32-bit unsigned integer that specifies the total size of this object, in bytes

**Returns:**
int
### setSizeData(int value) {#setSizeData-int-}
```
public void setSizeData(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the total size of this object, in bytes

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Gets or sets a 32-bit unsigned integer that specifies the PostScript language level. This value MUST be 0x00000001

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the PostScript language level. This value MUST be 0x00000001

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPoints() {#getPoints--}
```
public EmfPoint28To4[] getPoints()
```


Gets or sets an array of three Point28\_4 objects (section 2.2.23) that defines the coordinates of the output parallelogram using 28.4 bit FIX notation

The upper-left corner of the parallelogram is the first point in this array, the upper-right corner is the second point, and the lower-left corner is the third point. The lower-right corner of the parallelogram is computed from the first three points (A, B, and C) by treating them as vectors.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4[]
### setPoints(EmfPoint28To4[] value) {#setPoints-com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4---}
```
public void setPoints(EmfPoint28To4[] value)
```


Gets or sets an array of three Point28\_4 objects (section 2.2.23) that defines the coordinates of the output parallelogram using 28.4 bit FIX notation

The upper-left corner of the parallelogram is the first point in this array, the upper-right corner is the second point, and the lower-left corner is the third point. The lower-right corner of the parallelogram is computed from the first three points (A, B, and C) by treating them as vectors.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPoint28To4\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpoint28to4) |  |

### getPostScriptData() {#getPostScriptData--}
```
public byte[] getPostScriptData()
```


Gets or sets an array of bytes of PostScript data. The length of this array can be computed from the SizeData field. This data MAY be used to render an image.

**Returns:**
byte[]
### setPostScriptData(byte[] value) {#setPostScriptData-byte---}
```
public void setPostScriptData(byte[] value)
```


Gets or sets an array of bytes of PostScript data. The length of this array can be computed from the SizeData field. This data MAY be used to render an image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

