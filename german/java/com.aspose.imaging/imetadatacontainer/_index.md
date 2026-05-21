---
title: "IMetadataContainer"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Schnittstelle für Bild-Metadaten-Container."
type: docs
weight: 136
url: /de/java/com.aspose.imaging/imetadatacontainer/
---
**All Implemented Interfaces:**
[com.aspose.imaging.exif.IHasExifData](../../com.aspose.imaging.exif/ihasexifdata), [com.aspose.imaging.xmp.IHasXmpData](../../com.aspose.imaging.xmp/ihasxmpdata)
```
public interface IMetadataContainer extends IHasExifData, IHasXmpData
```

Schnittstelle für Bild-Metadaten-Container.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | Versucht, eine `metadata`-Instanz zu setzen, falls diese [Image](../../com.aspose.imaging/image)-Instanz unterstützt und eine [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)-Instanz implementiert. |
### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public abstract boolean trySetMetadata(IImageMetadataFormat metadata)
```


Versucht, eine `metadata`-Instanz zu setzen, falls diese [Image](../../com.aspose.imaging/image)-Instanz unterstützt und eine [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)-Instanz implementiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | Die Metadaten. |

**Returns:**
boolean - Wahr, wenn `metadata` nicht null ist und die [IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)-Instanz unterstützt und/oder eine [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)-Instanz implementiert; andernfalls falsch.
