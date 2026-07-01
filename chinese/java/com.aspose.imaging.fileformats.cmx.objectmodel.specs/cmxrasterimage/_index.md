---
title: "CmxRasterImage"
second_title: "Aspose.Imaging for Java API 参考"
description: "表示为光栅图像指定的数据。"
type: docs
weight: 15
url: /zh/java/com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxrasterimage/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.objectmodel.specs.ICmxObjectSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/icmxobjectspec)
```
public class CmxRasterImage implements ICmxObjectSpec
```

表示为光栅图像指定的数据。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CmxRasterImage()](#CmxRasterImage--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 获取图像的类型。 |
| [setType(int value)](#setType-int-) | 设置图像的类型。 |
| [getCompression()](#getCompression--) | 获取压缩。 |
| [setCompression(int value)](#setCompression-int-) | 设置压缩。 |
| [getSize()](#getSize--) | 获取图像的大小。 |
| [setSize(long value)](#setSize-long-) | 设置图像的大小。 |
| [getCompressedSize()](#getCompressedSize--) | 获取图像的压缩大小。 |
| [setCompressedSize(long value)](#setCompressedSize-long-) | 设置图像的压缩大小。 |
| [isMask()](#isMask--) | 获取指示此实例是否为掩码的值。 |
| [setMask(boolean value)](#setMask-boolean-) | 设置指示此实例是否为掩码的值。 |
| [getColorModel()](#getColorModel--) | 获取颜色模型。 |
| [setColorModel(long value)](#setColorModel-long-) | 设置颜色模型。 |
| [getWidth()](#getWidth--) | 获取图像的宽度。 |
| [setWidth(long value)](#setWidth-long-) | 设置图像的宽度。 |
| [getHeight()](#getHeight--) | 获取图像的高度。 |
| [setHeight(long value)](#setHeight-long-) | 设置图像的高度。 |
| [getBitsPerPixel()](#getBitsPerPixel--) | 获取每像素位数。 |
| [setBitsPerPixel(long value)](#setBitsPerPixel-long-) | 设置每像素位数。 |
| [getBytesPerLine()](#getBytesPerLine--) | 获取线的大小。 |
| [setBytesPerLine(long value)](#setBytesPerLine-long-) | 设置线的大小。 |
| [getColorPalette()](#getColorPalette--) | 获取颜色调色板数组。 |
| [setColorPalette(int[] value)](#setColorPalette-int---) | 设置颜色调色板数组。 |
| [getRawData()](#getRawData--) | 获取图像的原始字节数据。 |
| [setRawData(byte[] value)](#setRawData-byte---) | 设置图像的原始字节数据。 |
| [toString()](#toString--) | 返回表示此实例的字符串。 |
| [equals(Object o)](#equals-java.lang.Object-) | 检查对象是否相等。 |
| [hashCode()](#hashCode--) | 获取当前对象的哈希码。 |
### CmxRasterImage() {#CmxRasterImage--}
```
public CmxRasterImage()
```


### getType() {#getType--}
```
public final int getType()
```


获取图像的类型。

**Returns:**
int - 图像的类型。
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


设置图像的类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 图像的类型。 |

### getCompression() {#getCompression--}
```
public final int getCompression()
```


获取压缩。

**Returns:**
int - 压缩。
### setCompression(int value) {#setCompression-int-}
```
public final void setCompression(int value)
```


设置压缩。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 压缩。 |

### getSize() {#getSize--}
```
public final long getSize()
```


获取图像的大小。以字节为单位。

**Returns:**
long - 图像的大小。
### setSize(long value) {#setSize-long-}
```
public final void setSize(long value)
```


设置图像的大小。单位为字节。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long | 图像的大小。 |

### getCompressedSize() {#getCompressedSize--}
```
public final long getCompressedSize()
```


获取图像的压缩大小。单位为字节。

**Returns:**
long - 图像的压缩大小。
### setCompressedSize(long value) {#setCompressedSize-long-}
```
public final void setCompressedSize(long value)
```


设置图像的压缩大小。单位为字节。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long | 图像的压缩大小。 |

### isMask() {#isMask--}
```
public final boolean isMask()
```


获取指示此实例是否为掩码的值。

**Returns:**
boolean - 指示此实例是否为掩码的值。
### setMask(boolean value) {#setMask-boolean-}
```
public final void setMask(boolean value)
```


设置指示此实例是否为掩码的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean | 指示此实例是否为掩码的值。 |

### getColorModel() {#getColorModel--}
```
public final long getColorModel()
```


获取颜色模型。

**Returns:**
long - 颜色模型。
### setColorModel(long value) {#setColorModel-long-}
```
public final void setColorModel(long value)
```


设置颜色模型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long | 颜色模型。 |

### getWidth() {#getWidth--}
```
public final long getWidth()
```


获取图像的宽度。单位为像素。

**Returns:**
long - 图像的宽度。
### setWidth(long value) {#setWidth-long-}
```
public final void setWidth(long value)
```


设置图像的宽度。单位为像素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long | 图像的宽度。 |

### getHeight() {#getHeight--}
```
public final long getHeight()
```


获取图像的高度。单位为像素。

**Returns:**
long - 图像的高度。
### setHeight(long value) {#setHeight-long-}
```
public final void setHeight(long value)
```


设置图像的高度。单位为像素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long | 图像的高度。 |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public final long getBitsPerPixel()
```


获取每像素位数。

**Returns:**
long - 每像素位数。
### setBitsPerPixel(long value) {#setBitsPerPixel-long-}
```
public final void setBitsPerPixel(long value)
```


设置每像素位数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long | 每像素位数。 |

### getBytesPerLine() {#getBytesPerLine--}
```
public final long getBytesPerLine()
```


获取行的大小。单位为字节。

**Returns:**
long - 行的大小。
### setBytesPerLine(long value) {#setBytesPerLine-long-}
```
public final void setBytesPerLine(long value)
```


设置行的大小。单位为字节。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long | 行的大小。 |

### getColorPalette() {#getColorPalette--}
```
public final int[] getColorPalette()
```


获取颜色调色板数组。元素是以 `int` 表示的 ARGB 颜色值

**Returns:**
int[] - 颜色调色板数组。
### setColorPalette(int[] value) {#setColorPalette-int---}
```
public final void setColorPalette(int[] value)
```


设置颜色调色板数组。元素是以 `int` 表示的 ARGB 颜色值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int[] | 颜色调色板数组。 |

### getRawData() {#getRawData--}
```
public final byte[] getRawData()
```


获取图像的原始字节数据。

**Returns:**
byte[] - 图像的原始字节数据。
### setRawData(byte[] value) {#setRawData-byte---}
```
public final void setRawData(byte[] value)
```


设置图像的原始字节数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte[] | 图像的原始字节数据。 |

### toString() {#toString--}
```
public String toString()
```


返回表示此实例的字符串。

**Returns:**
java.lang.String - 表示此实例的字符串。
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


检查对象是否相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| o | java.lang.Object | 其他对象。 |

**Returns:**
boolean - 相等比较结果。
### hashCode() {#hashCode--}
```
public int hashCode()
```


获取当前对象的哈希码。

**Returns:**
int - 哈希码。
