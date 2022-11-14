---
title: EmfPlusPathPointType
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusPathPointType object specifies a type value associated with a point on a graphics
type: docs
weight: 61
url: /java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype)
```
public final class EmfPlusPathPointType extends EmfPlusBasePointType
```

The EmfPlusPathPointType object specifies a type value associated with a point on a graphics
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusPathPointType()](#EmfPlusPathPointType--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getData()](#getData--) | Gets or sets the data. |
| [setData(int value)](#setData-int-) | Gets or sets the data. |
| [getType()](#getType--) | Gets or sets 4-bit unsigned integer path point type. |
| [setType(int value)](#setType-int-) | Gets or sets 4-bit unsigned integer path point type. |
| [getFlags()](#getFlags--) | Gets or sets 4-bit flag field that specifies properties of the path point. |
| [setFlags(int value)](#setFlags-int-) | Gets or sets 4-bit flag field that specifies properties of the path point. |
### EmfPlusPathPointType() {#EmfPlusPathPointType--}
```
public EmfPlusPathPointType()
```


### getData() {#getData--}
```
public int getData()
```


Gets or sets the data.

Value: The data.

**Returns:**
int
### setData(int value) {#setData-int-}
```
public void setData(int value)
```


Gets or sets the data.

Value: The data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public int getType()
```


Gets or sets 4-bit unsigned integer path point type. This value MUST be defined in the PathPointType enumeration (section 2.1.1.23).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Gets or sets 4-bit unsigned integer path point type. This value MUST be defined in the PathPointType enumeration (section 2.1.1.23).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFlags() {#getFlags--}
```
public int getFlags()
```


Gets or sets 4-bit flag field that specifies properties of the path point. This value MUST be one or more of the PathPointType flags (section 2.1.2.6).

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Gets or sets 4-bit flag field that specifies properties of the path point. This value MUST be one or more of the PathPointType flags (section 2.1.2.6).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

