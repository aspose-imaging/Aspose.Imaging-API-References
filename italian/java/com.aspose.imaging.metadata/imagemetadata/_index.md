---
title: "ImageMetadata"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Classe dei metadati immagine."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.metadata/imagemetadata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public final class ImageMetadata implements IMetadataContainer
```

Classe dei metadati immagine.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getExifData()](#getExifData--) | Ottiene i dati Exif. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Imposta i dati Exif. |
| [getXmpData()](#getXmpData--) | Ottiene i dati Xmp. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Imposta i dati Xmp. |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | Cerca di impostare un'istanza `metadata`, se questa istanza [Image](../../com.aspose.imaging/image) supporta e implementa l'istanza [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat). |
### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Ottiene i dati Exif.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - Exif data.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Imposta i dati Exif.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Dati Exif. |

### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Ottiene i dati Xmp.

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) - Xmp data.
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Imposta i dati Xmp.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) | Dati Xmp. |

### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public boolean trySetMetadata(IImageMetadataFormat metadata)
```


Cerca di impostare un'istanza `metadata`, se questa istanza [Image](../../com.aspose.imaging/image) supporta e implementa l'istanza [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | I metadati. |

**Returns:**
boolean - True se `metadata` non è null e l'istanza [IMetadataContainer](../../com.aspose.imaging/imetadatacontainer) supporta e/o implementa l'istanza [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat); altrimenti, false.
