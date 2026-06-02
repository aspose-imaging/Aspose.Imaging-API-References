---
title: "IMetadataContainer"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Görüntü meta verisi konteyner arayüzü."
type: docs
weight: 136
url: /tr/java/com.aspose.imaging/imetadatacontainer/
---
**All Implemented Interfaces:**
[com.aspose.imaging.exif.IHasExifData](../../com.aspose.imaging.exif/ihasexifdata), [com.aspose.imaging.xmp.IHasXmpData](../../com.aspose.imaging.xmp/ihasxmpdata)
```
public interface IMetadataContainer extends IHasExifData, IHasXmpData
```

Görüntü meta verisi konteyner arayüzü.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | Bu [Image](../../com.aspose.imaging/image) örneği destekliyor ve [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) örneğini uyguluyorsa, bir `metadata` örneği ayarlamaya çalışır. |
### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public abstract boolean trySetMetadata(IImageMetadataFormat metadata)
```


Bu [Image](../../com.aspose.imaging/image) örneği destekliyor ve [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) örneğini uyguluyorsa, bir `metadata` örneği ayarlamaya çalışır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | metadata. |

**Returns:**
boolean - `metadata` null değilse ve [IMetadataContainer](../../com.aspose.imaging/imetadatacontainer) örneği [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) örneğini destekliyor ve/veya uyguluyorsa; aksi takdirde false.
