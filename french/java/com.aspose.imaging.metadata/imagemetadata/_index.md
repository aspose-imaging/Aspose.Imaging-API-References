---
title: "ImageMetadata"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Classe de métadonnées d'image."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.metadata/imagemetadata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public final class ImageMetadata implements IMetadataContainer
```

Classe de métadonnées d'image.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getExifData()](#getExifData--) | Obtient les données Exif. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Définit les données Exif. |
| [getXmpData()](#getXmpData--) | Obtient les données Xmp. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Définit les données Xmp. |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | Essaie de définir une instance `metadata`, si cette instance [Image](../../com.aspose.imaging/image) prend en charge et implémente une instance [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat). |
### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Obtient les données Exif.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - Exif data.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Définit les données Exif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Données Exif. |

### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Obtient les données Xmp.

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) - Xmp data.
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Définit les données Xmp.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) | Données Xmp. |

### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public boolean trySetMetadata(IImageMetadataFormat metadata)
```


Essaie de définir une instance `metadata`, si cette instance [Image](../../com.aspose.imaging/image) prend en charge et implémente une instance [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | Les métadonnées. |

**Returns:**
boolean - Vrai si `metadata` n'est pas nul et que l'instance [IMetadataContainer](../../com.aspose.imaging/imetadatacontainer) prend en charge et/ou implémente une instance [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) ; sinon, faux.
