---
title: "BigTiffImage"
second_title: "Aspose.Imaging for Java API 参考"
description: "使用  类，您可以轻松操作 BigTiff 图像格式文件。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.fileformats.bigtiff/bigtiffimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage), [com.aspose.imaging.fileformats.tiff.TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage)
```
public final class BigTiffImage extends TiffImage
```

使用 [BigTiffImage](../../com.aspose.imaging.fileformats.bigtiff/bigtiffimage) 类，您可以轻松操作 BigTiff 图像格式文件。我们的 API 提供无缝的处理和自定义选项，确保对大规模图像数据进行最佳处理，并具备针对您特定需求量身定制的多功能特性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BigTiffImage(TiffFrame frame)](#BigTiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame-) | 通过使用 TiffFrame 参数初始化，创建 [BigTiffImage](../../com.aspose.imaging.fileformats.bigtiff/bigtiffimage) 类的新实例。 |
| [BigTiffImage(TiffFrame[] frames)](#BigTiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame---) | 通过使用 TiffFrames 列表参数初始化新实例，开始无缝使用 [BigTiffImage](../../com.aspose.imaging.fileformats.bigtiff/bigtiffimage) 类。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | 获取此 [Image](../../com.aspose.imaging/image) 实例的文件格式。 |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | 使用此直观方法，轻松通过添加新页面来扩展您的 BigTiff 图像。 |
### BigTiffImage(TiffFrame frame) {#BigTiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public BigTiffImage(TiffFrame frame)
```


通过使用 TiffFrame 参数初始化，创建 [BigTiffImage](../../com.aspose.imaging.fileformats.bigtiff/bigtiffimage) 类的新实例。该方式非常适合希望以便捷方式使用 BigTiffImage 对象的开发者，确保灵活性并易于集成到其项目中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | 用于初始化图像的 tiff 帧。 |

### BigTiffImage(TiffFrame[] frames) {#BigTiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame---}
```
public BigTiffImage(TiffFrame[] frames)
```


通过使用包含 TiffFrames 列表参数的构造函数来无缝开始使用 [BigTiffImage](../../com.aspose.imaging.fileformats.bigtiff/bigtiffimage) 类。非常适合希望以简便方式处理包含多个帧的 BigTiffImage 对象的开发者，从而确保项目的高效性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| frames | [TiffFrame\[\]](../../com.aspose.imaging.fileformats.tiff/tiffframe) | 帧列表。 |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


获取此 [Image](../../com.aspose.imaging/image) 实例的文件格式。

**Returns:**
long - 此 [Image](../../com.aspose.imaging/image) 实例的文件格式。
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


使用此直观方法轻松通过添加新页面来扩展您的 BigTiff 图像。非常适合希望动态增强多页图像内容的开发者。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | 要添加的页面。 |

