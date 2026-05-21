---
title: "WmfBitmapBaseHeader"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "基础位图头类。"
type: docs
weight: 14
url: /zh/java/com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public abstract class WmfBitmapBaseHeader extends MetaObject
```

基础位图头类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WmfBitmapBaseHeader()](#WmfBitmapBaseHeader--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getHeaderSize()](#getHeaderSize--) | 获取或设置一个 32 位无符号整数，定义此对象的大小（单位为字节）。 |
| [setHeaderSize(int value)](#setHeaderSize-int-) | 获取或设置一个 32 位无符号整数，定义此对象的大小（单位为字节）。 |
| [getPlanes()](#getPlanes--) | 获取或设置一个 16 位无符号整数，定义目标设备的 `planes` 数量。 |
| [setPlanes(short value)](#setPlanes-short-) | 获取或设置一个 16 位无符号整数，定义目标设备的 `planes` 数量。 |
| [getBitCount()](#getBitCount--) | 获取或设置一个 16 位无符号整数，定义每个像素的格式以及 DIB 中的最大颜色数。 |
| [setBitCount(short value)](#setBitCount-short-) | 获取或设置一个 16 位无符号整数，定义每个像素的格式以及 DIB 中的最大颜色数。 |
### WmfBitmapBaseHeader() {#WmfBitmapBaseHeader--}
```
public WmfBitmapBaseHeader()
```


### getHeaderSize() {#getHeaderSize--}
```
public int getHeaderSize()
```


获取或设置一个 32 位无符号整数，定义此对象的大小（单位为字节）。

**Returns:**
int
### setHeaderSize(int value) {#setHeaderSize-int-}
```
public void setHeaderSize(int value)
```


获取或设置一个 32 位无符号整数，定义此对象的大小（单位为字节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 一个 16 位无符号整数，定义目标设备的 `planes` 数量。该值必须为 0x0001。 |

### getPlanes() {#getPlanes--}
```
public short getPlanes()
```


获取或设置一个 16 位无符号整数，定义目标设备的 `planes` 数量。此值必须为 0x0001。

**Returns:**
short - 一个 16 位无符号整数，定义目标设备的 `planes` 数量。
### setPlanes(short value) {#setPlanes-short-}
```
public void setPlanes(short value)
```


获取或设置一个 16 位无符号整数，定义目标设备的 `planes` 数量。此值必须为 0x0001。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short | 一个 16 位无符号整数，定义目标设备的 `planes` 数量。此值必须为 \* 0x0001。 |

### getBitCount() {#getBitCount--}
```
public short getBitCount()
```


获取或设置一个 16 位无符号整数，定义每个像素的格式以及 DIB 中的最大颜色数。此值必须位于 `BitCount` 枚举中（第 2.1.1.3 节）。

**Returns:**
short - 一个 16 位无符号整数，定义每个像素的格式以及 DIB 中的最大颜色数。
### setBitCount(short value) {#setBitCount-short-}
```
public void setBitCount(short value)
```


获取或设置一个 16 位无符号整数，定义每个像素的格式以及 DIB 中的最大颜色数。此值必须位于 `BitCount` 枚举中（第 2.1.1.3 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short | 一个 16 位无符号整数，定义每个像素的格式以及 DIB 中的最大颜色数。 |

