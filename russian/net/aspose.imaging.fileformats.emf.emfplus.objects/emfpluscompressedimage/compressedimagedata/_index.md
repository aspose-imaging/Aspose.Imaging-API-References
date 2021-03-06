---
title: CompressedImageData
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает или задает массив байтов определяющих сжатое изображение. Тип сжатия ДОЛЖЕН быть определен из самих данных.
type: docs
weight: 20
url: /ru/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompressedimage/compressedimagedata/
---
## EmfPlusCompressedImage.CompressedImageData property

Получает или задает массив байтов, определяющих сжатое изображение. Тип сжатия ДОЛЖЕН быть определен из самих данных.

```csharp
public byte[] CompressedImageData { get; set; }
```

### Примечания

Растровые изображения задаются объектами EmfPlusBitmap (раздел 2.2.2.2). Объект EmfPlusCompressedImage ДОЛЖЕН присутствовать в поле BitmapData объекта EmfPlusBitmap, если в его поле Type указано BitmapDataTypeCompressed. Этот объект является универсальным и используется для различных типов сжатых данных, включая:  Формат файла обмениваемого изображения (EXIF), как указано в [EXIF];  Формат обмена графикой (GIF), как указано в [GIF];  Объединенная группа экспертов по фотографии (JPEG), как указано в [JFIF];  Переносимая сетевая графика (PNG), как указано в [RFC2083] и [W3C - PNG]; и  Формат файла изображения тега (TIFF), как указано в [RFC3302] и [TIFF].

### Смотрите также

* class [EmfPlusCompressedImage](../../emfpluscompressedimage)
* пространство имен [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../emfpluscompressedimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
