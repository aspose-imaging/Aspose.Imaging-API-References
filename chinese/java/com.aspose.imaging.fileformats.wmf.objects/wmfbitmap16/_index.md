---
title: "WmfBitmap16"
second_title: "Aspose.Imaging for Java API 参考"
description: "Bitmap16 对象指定有关位图尺寸和颜色格式的信息。"
type: docs
weight: 13
url: /zh/java/com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfBitmap16 extends MetaObject
```

Bitmap16 对象指定有关位图尺寸和颜色格式的信息。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WmfBitmap16()](#WmfBitmap16--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 获取或设置类型。 |
| [setType(short value)](#setType-short-) | 获取或设置类型。 |
| [getWidth()](#getWidth--) | 获取或设置宽度。 |
| [setWidth(short value)](#setWidth-short-) | 获取或设置宽度。 |
| [getHeight()](#getHeight--) | 获取或设置高度。 |
| [setHeight(short value)](#setHeight-short-) | 获取或设置高度。 |
| [getWidthBytes()](#getWidthBytes--) | 获取或设置宽度字节数。 |
| [setWidthBytes(short value)](#setWidthBytes-short-) | 获取或设置宽度字节数。 |
| [getPlanes()](#getPlanes--) | 获取或设置平面数。 |
| [setPlanes(byte value)](#setPlanes-byte-) | 获取或设置平面数。 |
| [getBitsPixel()](#getBitsPixel--) | 获取或设置每像素位数。 |
| [setBitsPixel(byte value)](#setBitsPixel-byte-) | 获取或设置每像素位数。 |
| [getBits()](#getBits--) | 获取或设置位数。 |
| [setBits(byte[] value)](#setBits-byte---) | 获取或设置位数。 |
### WmfBitmap16() {#WmfBitmap16--}
```
public WmfBitmap16()
```


### getType() {#getType--}
```
public short getType()
```


获取或设置类型。

值：位图类型。

**Returns:**
短
### setType(short value) {#setType-short-}
```
public void setType(short value)
```


获取或设置类型。

值：位图类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

### getWidth() {#getWidth--}
```
public short getWidth()
```


获取或设置宽度。

值：位图的宽度（以像素为单位）

**Returns:**
短
### setWidth(short value) {#setWidth-short-}
```
public void setWidth(short value)
```


获取或设置宽度。

值：位图的宽度（以像素为单位）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

### getHeight() {#getHeight--}
```
public short getHeight()
```


获取或设置高度。

值：位图的高度（以扫描行数为单位）。

**Returns:**
短
### setHeight(short value) {#setHeight-short-}
```
public void setHeight(short value)
```


获取或设置高度。

值：位图的高度（以扫描行数为单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

### getWidthBytes() {#getWidthBytes--}
```
public short getWidthBytes()
```


获取或设置宽度字节数。

值：每扫描行的字节数。

**Returns:**
短
### setWidthBytes(short value) {#setWidthBytes-short-}
```
public void setWidthBytes(short value)
```


获取或设置宽度字节数。

值：每扫描行的字节数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |

### getPlanes() {#getPlanes--}
```
public byte getPlanes()
```


获取或设置平面数。

值：此字段的值必须为 0x01。

**Returns:**
byte
### setPlanes(byte value) {#setPlanes-byte-}
```
public void setPlanes(byte value)
```


获取或设置平面数。

值：此字段的值必须为 0x01。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getBitsPixel() {#getBitsPixel--}
```
public byte getBitsPixel()
```


获取或设置每像素位数。

值：每个平面上相邻的颜色位数。

**Returns:**
byte
### setBitsPixel(byte value) {#setBitsPixel-byte-}
```
public void setBitsPixel(byte value)
```


获取或设置每像素位数。

值：每个平面上相邻的颜色位数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getBits() {#getBits--}
```
public byte[] getBits()
```


获取或设置位数。

值：位图像素数据。此字段的字节长度可按如下方式计算。

**Returns:**
byte[]
### setBits(byte[] value) {#setBits-byte---}
```
public void setBits(byte[] value)
```


获取或设置位数。

值：位图像素数据。此字段的字节长度可按如下方式计算。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

