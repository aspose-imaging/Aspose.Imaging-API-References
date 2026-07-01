---
title: "EmfPlusCompressedImage"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmfPlusCompressedImage 对象指定带有压缩数据的图像。"
type: docs
weight: 31
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompressedimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata)
```
public final class EmfPlusCompressedImage extends EmfPlusBaseBitmapData
```

EmfPlusCompressedImage 对象指定带有压缩数据的图像。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusCompressedImage()](#EmfPlusCompressedImage--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCompressedImageData()](#getCompressedImageData--) | 获取或设置指定压缩图像的字节数组。 |
| [setCompressedImageData(byte[] value)](#setCompressedImageData-byte---) | 获取或设置指定压缩图像的字节数组。 |
### EmfPlusCompressedImage() {#EmfPlusCompressedImage--}
```
public EmfPlusCompressedImage()
```


### getCompressedImageData() {#getCompressedImageData--}
```
public byte[] getCompressedImageData()
```


获取或设置指定压缩图像的字节数组。压缩类型必须从数据本身确定。

位图由 EmfPlusBitmap 对象（第 2.2.2.2 节）指定。如果在其 Type 字段中指定了 BitmapDataTypeCompressed，则 EmfPlusBitmap 对象的 BitmapData 字段中必须存在 EmfPlusCompressedImage 对象。此对象是通用的，用于不同类型的压缩数据，包括：\\uf0a7 交换图像文件格式（EXIF），如 [EXIF] 中所述；\\uf0a7 图形交换格式（GIF），如 [GIF] 中所述；\\uf0a7 联合图像专家组（JPEG），如 [JFIF] 中所述；\\uf0a7 可移植网络图形（PNG），如 [RFC2083] 和 [W3C - PNG] 中所述；以及\\uf0a7 标签图像文件格式（TIFF），如 [RFC3302] 和 [TIFF] 中所述。

**Returns:**
byte[]
### setCompressedImageData(byte[] value) {#setCompressedImageData-byte---}
```
public void setCompressedImageData(byte[] value)
```


获取或设置指定压缩图像的字节数组。压缩类型必须从数据本身确定。

位图由 EmfPlusBitmap 对象（第 2.2.2.2 节）指定。如果在其 Type 字段中指定了 BitmapDataTypeCompressed，则 EmfPlusBitmap 对象的 BitmapData 字段中必须存在 EmfPlusCompressedImage 对象。此对象是通用的，用于不同类型的压缩数据，包括：\\uf0a7 交换图像文件格式（EXIF），如 [EXIF] 中所述；\\uf0a7 图形交换格式（GIF），如 [GIF] 中所述；\\uf0a7 联合图像专家组（JPEG），如 [JFIF] 中所述；\\uf0a7 可移植网络图形（PNG），如 [RFC2083] 和 [W3C - PNG] 中所述；以及\\uf0a7 标签图像文件格式（TIFF），如 [RFC3302] 和 [TIFF] 中所述。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

