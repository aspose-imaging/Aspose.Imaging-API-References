---
title: ImageMetadata
second_title: Aspose.Imaging for Java API Reference
description: Image meta data class.
type: docs
weight: 10
url: /java/com.aspose.imaging.metadata/imagemetadata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public final class ImageMetadata implements IMetadataContainer
```

Image meta data class.
## Methods

| Method | Description |
| --- | --- |
| [getExifData()](#getExifData--) | Gets Exif data. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Sets Exif data. |
| [getXmpData()](#getXmpData--) | Gets Xmp data. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Sets Xmp data. |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | Tries to set a `metadata` instance, if this [Image](../../com.aspose.imaging/image) instance supports and implements [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) instance. |
### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Gets Exif data.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - Exif data.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Sets Exif data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Exif data. |

### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Gets Xmp data.

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) - Xmp data.
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Sets Xmp data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) | Xmp data. |

### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public boolean trySetMetadata(IImageMetadataFormat metadata)
```


Tries to set a `metadata` instance, if this [Image](../../com.aspose.imaging/image) instance supports and implements [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | The metadata. |

**Returns:**
boolean - True if `metadata` is not null and the [IMetadataContainer](../../com.aspose.imaging/imetadatacontainer) instance supports and/or implements [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) instance; otherwise, false.
