---
title: "ImageMetadata"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Класс метаданных изображения."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.metadata/imagemetadata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public final class ImageMetadata implements IMetadataContainer
```

Класс метаданных изображения.
## Методы

| Метод | Описание |
| --- | --- |
| [getExifData()](#getExifData--) | Получает данные Exif. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Устанавливает данные Exif. |
| [getXmpData()](#getXmpData--) | Получает данные Xmp. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Устанавливает данные Xmp. |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | Пытается установить экземпляр `metadata`, если данный экземпляр [Image](../../com.aspose.imaging/image) поддерживает и реализует экземпляр [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat). |
### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Получает данные Exif.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - Exif data.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Устанавливает данные Exif.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Данные Exif. |

### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Получает данные Xmp.

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) - Xmp data.
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Устанавливает данные Xmp.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) | Данные Xmp. |

### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public boolean trySetMetadata(IImageMetadataFormat metadata)
```


Пытается установить экземпляр `metadata`, если данный экземпляр [Image](../../com.aspose.imaging/image) поддерживает и реализует экземпляр [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | Метаданные. |

**Returns:**
boolean - Истина, если `metadata` не равно null и экземпляр [IMetadataContainer](../../com.aspose.imaging/imetadatacontainer) поддерживает и/или реализует экземпляр [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat); в противном случае — ложь.
