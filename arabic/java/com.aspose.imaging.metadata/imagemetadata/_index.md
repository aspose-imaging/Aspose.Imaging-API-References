---
title: "ImageMetadata"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "فئة البيانات الوصفية للصورة."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.metadata/imagemetadata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public final class ImageMetadata implements IMetadataContainer
```

فئة البيانات الوصفية للصورة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getExifData()](#getExifData--) | يحصل على بيانات Exif. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | يضبط بيانات Exif. |
| [getXmpData()](#getXmpData--) | يحصل على بيانات Xmp. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | يضبط بيانات Xmp. |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | يحاول تعيين كائن `metadata` إذا كان كائن [Image](../../com.aspose.imaging/image) هذا يدعم ويطبق كائن [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat). |
### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


يحصل على بيانات Exif.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - Exif data.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


يضبط بيانات Exif.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | بيانات Exif. |

### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


يحصل على بيانات Xmp.

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) - Xmp data.
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


يضبط بيانات Xmp.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) | بيانات Xmp. |

### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public boolean trySetMetadata(IImageMetadataFormat metadata)
```


يحاول تعيين كائن `metadata` إذا كان كائن [Image](../../com.aspose.imaging/image) هذا يدعم ويطبق كائن [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | البيانات الوصفية. |

**Returns:**
boolean - صحيح إذا كان `metadata` غير فارغ وكان كائن [IMetadataContainer](../../com.aspose.imaging/imetadatacontainer) يدعم و/أو يطبق كائن [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)؛ وإلا، خطأ.
