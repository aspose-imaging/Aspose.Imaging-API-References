---
title: "IMetadataContainer"
second_title: "Aspose.Imaging för Java API-referens"
description: "Gränssnitt för bildmetadata-behållare."
type: docs
weight: 136
url: /sv/java/com.aspose.imaging/imetadatacontainer/
---
**All Implemented Interfaces:**
[com.aspose.imaging.exif.IHasExifData](../../com.aspose.imaging.exif/ihasexifdata), [com.aspose.imaging.xmp.IHasXmpData](../../com.aspose.imaging.xmp/ihasxmpdata)
```
public interface IMetadataContainer extends IHasExifData, IHasXmpData
```

Gränssnitt för bildmetadata-behållare.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | Försöker att sätta en `metadata`‑instans, om detta [Image](../../com.aspose.imaging/image)‑objekt stödjer och implementerar en [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)‑instans. |
### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public abstract boolean trySetMetadata(IImageMetadataFormat metadata)
```


Försöker att sätta en `metadata`‑instans, om detta [Image](../../com.aspose.imaging/image)‑objekt stödjer och implementerar en [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)‑instans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | Metadatan. |

**Returns:**
boolean - Sant om `metadata` inte är null och [IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)-instansen stödjer och/eller implementerar en [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)-instans; annars falskt.
