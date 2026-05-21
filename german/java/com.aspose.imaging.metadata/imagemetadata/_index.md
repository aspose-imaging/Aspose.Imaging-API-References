---
title: "ImageMetadata"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Bild-Metadatenklasse."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.metadata/imagemetadata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public final class ImageMetadata implements IMetadataContainer
```

Bild-Metadatenklasse.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getExifData()](#getExifData--) | Liest Exif-Daten. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Setzt Exif‑Daten. |
| [getXmpData()](#getXmpData--) | Liest Xmp-Daten. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Setzt Xmp-Daten. |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | Versucht, eine `metadata`-Instanz zu setzen, falls diese [Image](../../com.aspose.imaging/image)-Instanz unterstützt und eine [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)-Instanz implementiert. |
### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Liest Exif-Daten.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - Exif data.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Setzt Exif‑Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Exif-Daten. |

### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Liest Xmp-Daten.

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) - Xmp data.
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Setzt Xmp-Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) | Xmp-Daten. |

### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public boolean trySetMetadata(IImageMetadataFormat metadata)
```


Versucht, eine `metadata`-Instanz zu setzen, falls diese [Image](../../com.aspose.imaging/image)-Instanz unterstützt und eine [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)-Instanz implementiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | Die Metadaten. |

**Returns:**
boolean - Wahr, wenn `metadata` nicht null ist und die [IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)-Instanz unterstützt und/oder eine [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)-Instanz implementiert; andernfalls falsch.
