---
title: "IMetadataContainer"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Interfaz del contenedor de metadatos de la imagen."
type: docs
weight: 136
url: /es/java/com.aspose.imaging/imetadatacontainer/
---
**All Implemented Interfaces:**
[com.aspose.imaging.exif.IHasExifData](../../com.aspose.imaging.exif/ihasexifdata), [com.aspose.imaging.xmp.IHasXmpData](../../com.aspose.imaging.xmp/ihasxmpdata)
```
public interface IMetadataContainer extends IHasExifData, IHasXmpData
```

Interfaz del contenedor de metadatos de la imagen.
## Métodos

| Método | Descripción |
| --- | --- |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | Intenta establecer una instancia `metadata`, si esta instancia [Image](../../com.aspose.imaging/image) admite e implementa una instancia [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat). |
### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public abstract boolean trySetMetadata(IImageMetadataFormat metadata)
```


Intenta establecer una instancia `metadata`, si esta instancia [Image](../../com.aspose.imaging/image) admite e implementa una instancia [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | Los metadatos. |

**Returns:**
boolean - Verdadero si `metadata` no es nulo y la instancia [IMetadataContainer](../../com.aspose.imaging/imetadatacontainer) admite y/o implementa una instancia [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat); de lo contrario, falso.
