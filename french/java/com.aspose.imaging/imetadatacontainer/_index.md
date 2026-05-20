---
title: "IMetadataContainer"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Interface du conteneur de métadonnées d'image."
type: docs
weight: 136
url: /fr/java/com.aspose.imaging/imetadatacontainer/
---
**All Implemented Interfaces:**
[com.aspose.imaging.exif.IHasExifData](../../com.aspose.imaging.exif/ihasexifdata), [com.aspose.imaging.xmp.IHasXmpData](../../com.aspose.imaging.xmp/ihasxmpdata)
```
public interface IMetadataContainer extends IHasExifData, IHasXmpData
```

Interface du conteneur de métadonnées d'image.
## Méthodes

| Méthode | Description |
| --- | --- |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | Essaie de définir une instance `metadata`, si cette instance [Image](../../com.aspose.imaging/image) prend en charge et implémente une instance [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat). |
### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public abstract boolean trySetMetadata(IImageMetadataFormat metadata)
```


Essaie de définir une instance `metadata`, si cette instance [Image](../../com.aspose.imaging/image) prend en charge et implémente une instance [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | Les métadonnées. |

**Returns:**
boolean - Vrai si `metadata` n'est pas nul et que l'instance [IMetadataContainer](../../com.aspose.imaging/imetadatacontainer) prend en charge et/ou implémente une instance [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) ; sinon, faux.
