---
title: "IMetadataContainer"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "واجهة حاوية بيانات تعريف الصورة."
type: docs
weight: 136
url: /ar/java/com.aspose.imaging/imetadatacontainer/
---
**All Implemented Interfaces:**
[com.aspose.imaging.exif.IHasExifData](../../com.aspose.imaging.exif/ihasexifdata), [com.aspose.imaging.xmp.IHasXmpData](../../com.aspose.imaging.xmp/ihasxmpdata)
```
public interface IMetadataContainer extends IHasExifData, IHasXmpData
```

واجهة حاوية بيانات تعريف الصورة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | يحاول تعيين كائن `metadata` إذا كان كائن [Image](../../com.aspose.imaging/image) هذا يدعم ويطبق كائن [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat). |
### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public abstract boolean trySetMetadata(IImageMetadataFormat metadata)
```


يحاول تعيين كائن `metadata` إذا كان كائن [Image](../../com.aspose.imaging/image) هذا يدعم ويطبق كائن [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | البيانات الوصفية. |

**Returns:**
boolean - صحيح إذا كان `metadata` غير فارغ وكان كائن [IMetadataContainer](../../com.aspose.imaging/imetadatacontainer) يدعم و/أو يطبق كائن [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)؛ وإلا، خطأ.
