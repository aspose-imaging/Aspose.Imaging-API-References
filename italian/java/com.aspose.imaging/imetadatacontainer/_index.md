---
title: "IMetadataContainer"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Interfaccia del contenitore dei metadati dell'immagine."
type: docs
weight: 136
url: /it/java/com.aspose.imaging/imetadatacontainer/
---
**All Implemented Interfaces:**
[com.aspose.imaging.exif.IHasExifData](../../com.aspose.imaging.exif/ihasexifdata), [com.aspose.imaging.xmp.IHasXmpData](../../com.aspose.imaging.xmp/ihasxmpdata)
```
public interface IMetadataContainer extends IHasExifData, IHasXmpData
```

Interfaccia del contenitore dei metadati dell'immagine.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | Cerca di impostare un'istanza `metadata`, se questa istanza [Image](../../com.aspose.imaging/image) supporta e implementa l'istanza [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat). |
### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public abstract boolean trySetMetadata(IImageMetadataFormat metadata)
```


Cerca di impostare un'istanza `metadata`, se questa istanza [Image](../../com.aspose.imaging/image) supporta e implementa l'istanza [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | I metadati. |

**Returns:**
boolean - True se `metadata` non è null e l'istanza [IMetadataContainer](../../com.aspose.imaging/imetadatacontainer) supporta e/o implementa l'istanza [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat); altrimenti, false.
