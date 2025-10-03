---
title: IMetadataContainer
second_title: Aspose.Imaging for Java API Reference
description: Image metadata container interface.
type: docs
weight: 136
url: /java/com.aspose.imaging/imetadatacontainer/
---
**All Implemented Interfaces:**
[com.aspose.imaging.exif.IHasExifData](../../com.aspose.imaging.exif/ihasexifdata), [com.aspose.imaging.xmp.IHasXmpData](../../com.aspose.imaging.xmp/ihasxmpdata)
```
public interface IMetadataContainer extends IHasExifData, IHasXmpData
```

Image metadata container interface.
## Methods

| Method | Description |
| --- | --- |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | Tries to set a `metadata` instance, if this [Image](../../com.aspose.imaging/image) instance supports and implements [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) instance. |
### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public abstract boolean trySetMetadata(IImageMetadataFormat metadata)
```


Tries to set a `metadata` instance, if this [Image](../../com.aspose.imaging/image) instance supports and implements [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | The metadata. |

**Returns:**
boolean - True if `metadata` is not null and the [IMetadataContainer](../../com.aspose.imaging/imetadatacontainer) instance supports and/or implements [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) instance; otherwise, false.
