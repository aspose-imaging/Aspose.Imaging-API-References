---
title: WmfBitmapBaseHeader
second_title: Aspose.Imaging for Java API Reference
description: The base bitmap header class.
type: docs
weight: 14
url: /com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public abstract class WmfBitmapBaseHeader extends MetaObject
```

The base bitmap header class.
## Constructors

| Constructor | Description |
| --- | --- |
| [WmfBitmapBaseHeader()](#WmfBitmapBaseHeader--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getHeaderSize()](#getHeaderSize--) | Gets or sets a 32-bit unsigned integer that defines the size of this object, in bytes. |
| [setHeaderSize(int value)](#setHeaderSize-int-) | Gets or sets a 32-bit unsigned integer that defines the size of this object, in bytes. |
| [getPlanes()](#getPlanes--) | Gets or sets a 16-bit unsigned integer that defines the number of `planes` for the target device. |
| [setPlanes(short value)](#setPlanes-short-) | Gets or sets a 16-bit unsigned integer that defines the number of `planes` for the target device. |
| [getBitCount()](#getBitCount--) | Gets or sets a 16-bit unsigned integer that defines the format of each pixel, and the maximum number of colors in the DIB. |
| [setBitCount(short value)](#setBitCount-short-) | Gets or sets a 16-bit unsigned integer that defines the format of each pixel, and the maximum number of colors in the DIB. |
### WmfBitmapBaseHeader() {#WmfBitmapBaseHeader--}
```
public WmfBitmapBaseHeader()
```


### getHeaderSize() {#getHeaderSize--}
```
public int getHeaderSize()
```


Gets or sets a 32-bit unsigned integer that defines the size of this object, in bytes.

**Returns:**
int
### setHeaderSize(int value) {#setHeaderSize-int-}
```
public void setHeaderSize(int value)
```


Gets or sets a 32-bit unsigned integer that defines the size of this object, in bytes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a 16-bit unsigned integer that defines the number of `planes` for the target device. This value MUST be 0x0001. |

### getPlanes() {#getPlanes--}
```
public short getPlanes()
```


Gets or sets a 16-bit unsigned integer that defines the number of `planes` for the target device. This value MUST be 0x0001.

**Returns:**
short - a 16-bit unsigned integer that defines the number of `planes` for the target device.
### setPlanes(short value) {#setPlanes-short-}
```
public void setPlanes(short value)
```


Gets or sets a 16-bit unsigned integer that defines the number of `planes` for the target device. This value MUST be 0x0001.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short | a 16-bit unsigned integer that defines the number of `planes` for the target device. This value MUST be \* 0x0001. |

### getBitCount() {#getBitCount--}
```
public short getBitCount()
```


Gets or sets a 16-bit unsigned integer that defines the format of each pixel, and the maximum number of colors in the DIB. This value MUST be in the `BitCount` Enumeration (section 2.1.1.3).

**Returns:**
short - a 16-bit unsigned integer that defines the format of each pixel, and the maximum number of colors in the DIB.
### setBitCount(short value) {#setBitCount-short-}
```
public void setBitCount(short value)
```


Gets or sets a 16-bit unsigned integer that defines the format of each pixel, and the maximum number of colors in the DIB. This value MUST be in the `BitCount` Enumeration (section 2.1.1.3).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short | a 16-bit unsigned integer that defines the format of each pixel, and the maximum number of colors in the DIB. |

