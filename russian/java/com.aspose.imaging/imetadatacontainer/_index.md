---
title: "IMetadataContainer"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Интерфейс контейнера метаданных изображения."
type: docs
weight: 136
url: /ru/java/com.aspose.imaging/imetadatacontainer/
---
**All Implemented Interfaces:**
[com.aspose.imaging.exif.IHasExifData](../../com.aspose.imaging.exif/ihasexifdata), [com.aspose.imaging.xmp.IHasXmpData](../../com.aspose.imaging.xmp/ihasxmpdata)
```
public interface IMetadataContainer extends IHasExifData, IHasXmpData
```

Интерфейс контейнера метаданных изображения.
## Методы

| Метод | Описание |
| --- | --- |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | Пытается установить экземпляр `metadata`, если данный экземпляр [Image](../../com.aspose.imaging/image) поддерживает и реализует экземпляр [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat). |
### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public abstract boolean trySetMetadata(IImageMetadataFormat metadata)
```


Пытается установить экземпляр `metadata`, если данный экземпляр [Image](../../com.aspose.imaging/image) поддерживает и реализует экземпляр [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | Метаданные. |

**Returns:**
boolean - Истина, если `metadata` не равно null и экземпляр [IMetadataContainer](../../com.aspose.imaging/imetadatacontainer) поддерживает и/или реализует экземпляр [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat); в противном случае — ложь.
