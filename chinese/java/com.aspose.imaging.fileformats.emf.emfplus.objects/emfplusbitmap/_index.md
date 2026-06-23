---
title: "EmfPlusBitmap"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmfPlusBitmap 对象指定包含图形图像的位图。"
type: docs
weight: 14
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata)
```
public final class EmfPlusBitmap extends EmfPlusBaseImageData
```

EmfPlusBitmap 对象指定包含图形图像的位图。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusBitmap()](#EmfPlusBitmap--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBitmapData()](#getBitmapData--) | 获取或设置位图数据 BitmapData（可变长度）：定义 Type 字段中指定的位图数据对象的可变长度数据。 |
| [setBitmapData(EmfPlusBaseBitmapData value)](#setBitmapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData-) | 获取或设置位图数据 BitmapData（可变长度）：定义 Type 字段中指定的位图数据对象的可变长度数据。 |
| [getHeight()](#getHeight--) | 获取或设置位图高度 Height（4 字节）：一个 32 位有符号整数，指定位图占用区域的像素高度。 |
| [setHeight(int value)](#setHeight-int-) | 获取或设置位图高度 Height（4 字节）：一个 32 位有符号整数，指定位图占用区域的像素高度。 |
| [getPixelFormat()](#getPixelFormat--) | 获取或设置像素格式 PixelFormat（4 字节）：一个 32 位无符号整数，指定构成位图图像的像素格式。 |
| [setPixelFormat(int value)](#setPixelFormat-int-) | 获取或设置像素格式 PixelFormat（4 字节）：一个 32 位无符号整数，指定构成位图图像的像素格式。 |
| [getStride()](#getStride--) | 获取或设置图像的跨距 Stride（4 字节）：一个 32 位有符号整数，指定一行扫描线起始位置与下一行之间的字节偏移量。 |
| [setStride(int value)](#setStride-int-) | 获取或设置图像的跨距 Stride（4 字节）：一个 32 位有符号整数，指定一行扫描线起始位置与下一行之间的字节偏移量。 |
| [getType()](#getType--) | 获取或设置图像类型 Type（4 字节）：一个 32 位无符号整数，指定 BitmapData 字段中数据的类型。 |
| [setType(int value)](#setType-int-) | 获取或设置图像类型 Type（4 字节）：一个 32 位无符号整数，指定 BitmapData 字段中数据的类型。 |
| [getWidth()](#getWidth--) | 获取或设置图像宽度 Width（4 字节）：一个 32 位有符号整数，指定位图占用区域的像素宽度。 |
| [setWidth(int value)](#setWidth-int-) | 获取或设置图像宽度 Width（4 字节）：一个 32 位有符号整数，指定位图占用区域的像素宽度。 |
### EmfPlusBitmap() {#EmfPlusBitmap--}
```
public EmfPlusBitmap()
```


### getBitmapData() {#getBitmapData--}
```
public EmfPlusBaseBitmapData getBitmapData()
```


获取或设置位图数据 BitmapData（可变长度）：定义 Type 字段中指定的位图数据对象的可变长度数据。该数据的内容和格式可能因位图类型而异。

值：位图数据。

**Returns:**
[EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata)
### setBitmapData(EmfPlusBaseBitmapData value) {#setBitmapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData-}
```
public void setBitmapData(EmfPlusBaseBitmapData value)
```


获取或设置位图数据 BitmapData（可变长度）：定义 Type 字段中指定的位图数据对象的可变长度数据。该数据的内容和格式可能因位图类型而异。

值：位图数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata) |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


获取或设置位图高度 Height (4 bytes)：一个 32 位有符号整数，指定位图占用区域的像素高度。如果图像已压缩，根据 Type 字段，此值未定义，MUST 被忽略。

值：高度。

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


获取或设置位图高度 Height (4 bytes)：一个 32 位有符号整数，指定位图占用区域的像素高度。如果图像已压缩，根据 Type 字段，此值未定义，MUST 被忽略。

值：高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


获取或设置像素格式 PixelFormat (4 bytes)：一个 32 位无符号整数，指定构成位图图像的像素格式。支持的像素格式在 `EmfPlusPixelFormat` 枚举（第 2.1.1.25 节）中指定。如果图像已压缩，根据 Type 字段，此值未定义，MUST 被忽略。

值：像素格式。

**Returns:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public void setPixelFormat(int value)
```


获取或设置像素格式 PixelFormat (4 bytes)：一个 32 位无符号整数，指定构成位图图像的像素格式。支持的像素格式在 `EmfPlusPixelFormat` 枚举（第 2.1.1.25 节）中指定。如果图像已压缩，根据 Type 字段，此值未定义，MUST 被忽略。

值：像素格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getStride() {#getStride--}
```
public int getStride()
```


获取或设置图像的跨距 Stride (4 bytes)：一个 32 位有符号整数，指定一条扫描线起始位置与下一条之间的字节偏移量。该值等于每像素字节数（在 PixelFormat 字段中指定）乘以像素宽度（在 Width 字段中指定）。此字段的值 MUST 为四的倍数。如果图像已压缩，根据 Type 字段，此值未定义，MUST 被忽略。

值：跨距。

**Returns:**
int
### setStride(int value) {#setStride-int-}
```
public void setStride(int value)
```


获取或设置图像的跨距 Stride (4 bytes)：一个 32 位有符号整数，指定一条扫描线起始位置与下一条之间的字节偏移量。该值等于每像素字节数（在 PixelFormat 字段中指定）乘以像素宽度（在 Width 字段中指定）。此字段的值 MUST 为四的倍数。如果图像已压缩，根据 Type 字段，此值未定义，MUST 被忽略。

值：跨距。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getType() {#getType--}
```
public int getType()
```


获取或设置图像类型 Type (4 bytes)：一个 32 位无符号整数，指定 BitmapData 字段中的数据类型。此值 MUST 在 `EmfPlusBitmapDataType` 枚举（第 2.1.1.2 节）中定义。

值：类型。

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


获取或设置图像类型 Type (4 bytes)：一个 32 位无符号整数，指定 BitmapData 字段中的数据类型。此值 MUST 在 `EmfPlusBitmapDataType` 枚举（第 2.1.1.2 节）中定义。

值：类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


获取或设置图像宽度 Width (4 bytes)：一个 32 位有符号整数，指定位图占用区域的像素宽度。如果图像已压缩，根据 Type 字段，此值未定义，MUST 被忽略。

值：宽度。

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


获取或设置图像宽度 Width (4 bytes)：一个 32 位有符号整数，指定位图占用区域的像素宽度。如果图像已压缩，根据 Type 字段，此值未定义，MUST 被忽略。

值：宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

