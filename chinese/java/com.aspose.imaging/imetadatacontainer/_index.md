---
title: "IMetadataContainer"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "图像元数据容器接口。"
type: docs
weight: 136
url: /zh/java/com.aspose.imaging/imetadatacontainer/
---
**All Implemented Interfaces:**
[com.aspose.imaging.exif.IHasExifData](../../com.aspose.imaging.exif/ihasexifdata), [com.aspose.imaging.xmp.IHasXmpData](../../com.aspose.imaging.xmp/ihasxmpdata)
```
public interface IMetadataContainer extends IHasExifData, IHasXmpData
```

图像元数据容器接口。
## 方法

| 方法 | 描述 |
| --- | --- |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | 尝试设置一个 `metadata` 实例，如果此 [Image](../../com.aspose.imaging/image) 实例支持并实现 [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) 实例。 |
### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public abstract boolean trySetMetadata(IImageMetadataFormat metadata)
```


尝试设置一个 `metadata` 实例，如果此 [Image](../../com.aspose.imaging/image) 实例支持并实现 [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) 实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | 元数据。 |

**Returns:**
boolean - 如果 `metadata` 不为 null 且 [IMetadataContainer](../../com.aspose.imaging/imetadatacontainer) 实例支持和/或实现 [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) 实例，则为 True；否则为 false。
