---
title: "ImageMetadata"
second_title: "Aspose.Imaging for Java API 参考"
description: "图像元数据类。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.metadata/imagemetadata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public final class ImageMetadata implements IMetadataContainer
```

图像元数据类。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getExifData()](#getExifData--) | 获取 Exif 数据。 |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | 设置 Exif 数据。 |
| [getXmpData()](#getXmpData--) | 获取 Xmp 数据。 |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | 设置 Xmp 数据。 |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | 尝试设置一个 `metadata` 实例，如果此 [Image](../../com.aspose.imaging/image) 实例支持并实现 [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) 实例。 |
### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


获取 Exif 数据。

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - Exif data.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


设置 Exif 数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Exif 数据。 |

### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


获取 Xmp 数据。

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) - Xmp data.
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


设置 Xmp 数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) | Xmp 数据。 |

### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public boolean trySetMetadata(IImageMetadataFormat metadata)
```


尝试设置一个 `metadata` 实例，如果此 [Image](../../com.aspose.imaging/image) 实例支持并实现 [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) 实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | 元数据。 |

**Returns:**
boolean - 如果 `metadata` 不为 null 且 [IMetadataContainer](../../com.aspose.imaging/imetadatacontainer) 实例支持和/或实现 [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) 实例，则为 True；否则为 false。
