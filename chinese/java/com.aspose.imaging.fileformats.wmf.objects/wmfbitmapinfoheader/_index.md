---
title: "WmfBitmapInfoHeader"
second_title: "Aspose.Imaging for Java API 参考"
description: "BitmapInfoHeader 对象包含关于设备无关位图（DIB）尺寸和颜色格式的信息。"
type: docs
weight: 16
url: /zh/java/com.aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfBitmapBaseHeader](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader)
```
public class WmfBitmapInfoHeader extends WmfBitmapBaseHeader
```

BitmapInfoHeader 对象包含有关设备无关位图 (DIB) 的尺寸和颜色格式的信息。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WmfBitmapInfoHeader()](#WmfBitmapInfoHeader--) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
| [STRUCTURE_SIZE](#STRUCTURE-SIZE) | 结构大小 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getWidth()](#getWidth--) | 获取或设置一个 32 位有符号整数，定义 DIB 的宽度（以像素为单位）。 |
| [setWidth(int value)](#setWidth-int-) | 获取或设置一个 32 位有符号整数，定义 DIB 的宽度（以像素为单位）。 |
| [getHeight()](#getHeight--) | 获取或设置 32 位有符号整数，定义 DIB 的高度（以像素为单位）。 |
| [setHeight(int value)](#setHeight-int-) | 获取或设置 32 位有符号整数，定义 DIB 的高度（以像素为单位）。 |
| [getCompression()](#getCompression--) | 获取或设置一个 32 位无符号整数，定义 DIB 的压缩模式。 |
| [setCompression(int value)](#setCompression-int-) | 获取或设置一个 32 位无符号整数，定义 DIB 的压缩模式。 |
| [getImageSize()](#getImageSize--) | 获取或设置一个 32 位无符号整数，定义图像的大小（以字节为单位）。 |
| [setImageSize(int value)](#setImageSize-int-) | 获取或设置一个 32 位无符号整数，定义图像的大小（以字节为单位）。 |
| [getXPelsPerMeter()](#getXPelsPerMeter--) | 获取或设置一个 32 位有符号整数，定义 DIB 目标设备的水平分辨率（每米像素）。 |
| [setXPelsPerMeter(int value)](#setXPelsPerMeter-int-) | 获取或设置一个 32 位有符号整数，定义 DIB 目标设备的水平分辨率（每米像素）。 |
| [getYPelsPerMeter()](#getYPelsPerMeter--) | 获取或设置一个 32 位有符号整数，定义 DIB 目标设备的垂直分辨率（每米像素）。 |
| [setYPelsPerMeter(int value)](#setYPelsPerMeter-int-) | 获取或设置一个 32 位有符号整数，定义 DIB 目标设备的垂直分辨率（每米像素）。 |
| [getColorUsed()](#getColorUsed--) | 获取或设置一个 32 位无符号整数，指定 DIB 使用的颜色表中的索引数量，规则如下：如果该值为 0，DIB 使用与 BitCount 值对应的最大颜色数。 |
| [setColorUsed(int value)](#setColorUsed-int-) | 获取或设置一个 32 位无符号整数，指定 DIB 使用的颜色表中的索引数量，规则如下：如果该值为 0，DIB 使用与 BitCount 值对应的最大颜色数。 |
| [getColorImportant()](#getColorImportant--) | 获取或设置一个 32 位无符号整数，定义显示 DIB 所需的颜色索引数量。 |
| [setColorImportant(int value)](#setColorImportant-int-) | 获取或设置一个 32 位无符号整数，定义显示 DIB 所需的颜色索引数量。 |
### WmfBitmapInfoHeader() {#WmfBitmapInfoHeader--}
```
public WmfBitmapInfoHeader()
```


### STRUCTURE_SIZE {#STRUCTURE-SIZE}
```
public static final int STRUCTURE_SIZE
```


结构大小

### getWidth() {#getWidth--}
```
public int getWidth()
```


获取或设置一个 32 位有符号整数，定义 DIB 的宽度（以像素为单位）。此值必须为正。如果 Compression 值指定 JPEG 或 PNG 格式，则该字段应指定解压缩后图像文件的宽度。

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


获取或设置一个 32 位有符号整数，定义 DIB 的宽度（以像素为单位）。此值必须为正。如果 Compression 值指定 JPEG 或 PNG 格式，则该字段应指定解压缩后图像文件的宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


获取或设置一个 32 位有符号整数，定义 DIB 的高度（以像素为单位）。此值不得为零。如果该值为正，DIB 为自底向上位图，原点位于左下角；如果该值为负，DIB 为自顶向下位图，原点位于左上角。自顶向下位图不支持压缩。如果 Compression 值指定 JPEG 或 PNG 格式，则该字段应指定解压缩后图像文件的高度。

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


获取或设置一个 32 位有符号整数，定义 DIB 的高度（以像素为单位）。此值不得为零。如果该值为正，DIB 为自底向上位图，原点位于左下角；如果该值为负，DIB 为自顶向下位图，原点位于左上角。自顶向下位图不支持压缩。如果 Compression 值指定 JPEG 或 PNG 格式，则该字段应指定解压缩后图像文件的高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getCompression() {#getCompression--}
```
public int getCompression()
```


获取或设置一个 32 位无符号整数，定义 DIB 的压缩模式。此值必须属于 Compression 枚举（第 2.1.1.7 节）。如果 DIB 为自顶向下位图（由 Height 值指示），此值不得指定压缩格式。

**Returns:**
int
### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


获取或设置一个 32 位无符号整数，定义 DIB 的压缩模式。此值必须属于 Compression 枚举（第 2.1.1.7 节）。如果 DIB 为自顶向下位图（由 Height 值指示），此值不得指定压缩格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getImageSize() {#getImageSize--}
```
public int getImageSize()
```


获取或设置一个 32 位无符号整数，定义图像的大小（以字节为单位）。如果 Compression 值为 BI_RGB，则该值应为 0 并必须被忽略。如果 Compression 值为 BI_JPEG 或 BI_PNG，则该值必须指定相应的 JPEG 或 PNG 图像缓冲区的大小。

**Returns:**
int
### setImageSize(int value) {#setImageSize-int-}
```
public void setImageSize(int value)
```


获取或设置一个 32 位无符号整数，定义图像的大小（以字节为单位）。如果 Compression 值为 BI_RGB，则该值应为 0 并必须被忽略。如果 Compression 值为 BI_JPEG 或 BI_PNG，则该值必须指定相应的 JPEG 或 PNG 图像缓冲区的大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getXPelsPerMeter() {#getXPelsPerMeter--}
```
public int getXPelsPerMeter()
```


获取或设置一个 32 位有符号整数，定义 DIB 目标设备的水平分辨率（每米像素）。

**Returns:**
int
### setXPelsPerMeter(int value) {#setXPelsPerMeter-int-}
```
public void setXPelsPerMeter(int value)
```


获取或设置一个 32 位有符号整数，定义 DIB 目标设备的水平分辨率（每米像素）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getYPelsPerMeter() {#getYPelsPerMeter--}
```
public int getYPelsPerMeter()
```


获取或设置一个 32 位有符号整数，定义 DIB 目标设备的垂直分辨率（每米像素）。

**Returns:**
int
### setYPelsPerMeter(int value) {#setYPelsPerMeter-int-}
```
public void setYPelsPerMeter(int value)
```


获取或设置一个 32 位有符号整数，定义 DIB 目标设备的垂直分辨率（每米像素）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getColorUsed() {#getColorUsed--}
```
public int getColorUsed()
```


获取或设置一个 32 位无符号整数，指定 DIB 使用的颜色表中的索引数量，规则如下：如果该值为 0，DIB 使用与 BitCount 值对应的最大颜色数；如果该值非 0 且 BitCount 值小于 16，则该值指定 DIB 使用的颜色数量；如果该值非 0 且 BitCount 值大于等于 16，则该值指定用于优化系统调色板性能的颜色表大小。注意：如果该值非 0 且大于基于 BitCount 值的颜色表最大可能大小，则应假设为最大颜色表大小。

**Returns:**
int
### setColorUsed(int value) {#setColorUsed-int-}
```
public void setColorUsed(int value)
```


获取或设置一个 32 位无符号整数，指定 DIB 使用的颜色表中的索引数量，规则如下：如果该值为 0，DIB 使用与 BitCount 值对应的最大颜色数；如果该值非 0 且 BitCount 值小于 16，则该值指定 DIB 使用的颜色数量；如果该值非 0 且 BitCount 值大于等于 16，则该值指定用于优化系统调色板性能的颜色表大小。注意：如果该值非 0 且大于基于 BitCount 值的颜色表最大可能大小，则应假设为最大颜色表大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getColorImportant() {#getColorImportant--}
```
public int getColorImportant()
```


获取或设置一个 32 位无符号整数，定义显示 DIB 所需的颜色索引数量。如果该值为 0，则需要所有颜色索引。

**Returns:**
int
### setColorImportant(int value) {#setColorImportant-int-}
```
public void setColorImportant(int value)
```


获取或设置一个 32 位无符号整数，定义显示 DIB 所需的颜色索引数量。如果该值为 0，则需要所有颜色索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

