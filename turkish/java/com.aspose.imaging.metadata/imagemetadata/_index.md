---
title: "ImageMetadata"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Görüntü meta veri sınıfı."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.metadata/imagemetadata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public final class ImageMetadata implements IMetadataContainer
```

Görüntü meta veri sınıfı.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getExifData()](#getExifData--) | Exif verilerini alır. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Exif verisini ayarlar. |
| [getXmpData()](#getXmpData--) | Xmp verilerini alır. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Xmp verilerini ayarlar. |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | Bu [Image](../../com.aspose.imaging/image) örneği destekliyor ve [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) örneğini uyguluyorsa, bir `metadata` örneği ayarlamaya çalışır. |
### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Exif verilerini alır.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - Exif data.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Exif verisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Exif verileri. |

### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Xmp verilerini alır.

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) - Xmp data.
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Xmp verilerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) | Xmp verileri. |

### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public boolean trySetMetadata(IImageMetadataFormat metadata)
```


Bu [Image](../../com.aspose.imaging/image) örneği destekliyor ve [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) örneğini uyguluyorsa, bir `metadata` örneği ayarlamaya çalışır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | metadata. |

**Returns:**
boolean - `metadata` null değilse ve [IMetadataContainer](../../com.aspose.imaging/imetadatacontainer) örneği [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) örneğini destekliyor ve/veya uyguluyorsa; aksi takdirde false.
