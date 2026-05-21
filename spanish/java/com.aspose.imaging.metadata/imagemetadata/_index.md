---
title: "ImageMetadata"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Clase de metadatos de imagen."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.metadata/imagemetadata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public final class ImageMetadata implements IMetadataContainer
```

Clase de metadatos de imagen.
## Métodos

| Método | Descripción |
| --- | --- |
| [getExifData()](#getExifData--) | Obtiene los datos Exif. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Establece los datos Exif. |
| [getXmpData()](#getXmpData--) | Obtiene datos Xmp. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Establece datos Xmp. |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | Intenta establecer una instancia `metadata`, si esta instancia [Image](../../com.aspose.imaging/image) admite e implementa una instancia [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat). |
### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Obtiene los datos Exif.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - Exif data.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Establece los datos Exif.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Datos Exif. |

### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Obtiene datos Xmp.

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) - Xmp data.
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Establece datos Xmp.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) | Datos Xmp. |

### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public boolean trySetMetadata(IImageMetadataFormat metadata)
```


Intenta establecer una instancia `metadata`, si esta instancia [Image](../../com.aspose.imaging/image) admite e implementa una instancia [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | Los metadatos. |

**Returns:**
boolean - Verdadero si `metadata` no es nulo y la instancia [IMetadataContainer](../../com.aspose.imaging/imetadatacontainer) admite y/o implementa una instancia [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat); de lo contrario, falso.
