---
title: "ImageMetadata"
second_title: "Aspose.Imaging för Java API-referens"
description: "Bildmetadata‑klass."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.metadata/imagemetadata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public final class ImageMetadata implements IMetadataContainer
```

Bildmetadata‑klass.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getExifData()](#getExifData--) | Hämtar Exif-data. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Ställer in Exif-data. |
| [getXmpData()](#getXmpData--) | Hämtar Xmp-data. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Ställer in Xmp-data. |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | Försöker att sätta en `metadata`‑instans, om detta [Image](../../com.aspose.imaging/image)‑objekt stödjer och implementerar en [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)‑instans. |
### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Hämtar Exif-data.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - Exif data.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Ställer in Exif-data.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Exif‑data. |

### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Hämtar Xmp-data.

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) - Xmp data.
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Ställer in Xmp-data.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) | Xmp-data. |

### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public boolean trySetMetadata(IImageMetadataFormat metadata)
```


Försöker att sätta en `metadata`‑instans, om detta [Image](../../com.aspose.imaging/image)‑objekt stödjer och implementerar en [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)‑instans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | Metadatan. |

**Returns:**
boolean - Sant om `metadata` inte är null och [IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)-instansen stödjer och/eller implementerar en [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)-instans; annars falskt.
