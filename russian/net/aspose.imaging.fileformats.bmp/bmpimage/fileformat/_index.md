---
title: FileFormat
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает значение формата файла
type: docs
weight: 50
url: /ru/net/aspose.imaging.fileformats.bmp/bmpimage/fileformat/
---
## BmpImage.FileFormat property

Получает значение формата файла

```csharp
public override FileFormat FileFormat { get; }
```

### Примеры

В следующем примере показано, как извлечь информацию о формате необработанных данных и альфа-канале из изображения BMP.

```csharp
[C#]

// Создаем BMP-изображение 32 бита на пиксель размером 100 x 100 пикселей.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 32, null))
{
    System.Console.WriteLine("FileFormat={0}, RawDataFormat={1}, HasAlpha={2}", bmpImage.FileFormat, bmpImage.RawDataFormat, bmpImage.HasAlpha);
};

// Создаем BMP-изображение 24 бита на пиксель размером 100 x 100 пикселей.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 24, null))
{
    System.Console.WriteLine("FileFormat={0}, RawDataFormat={1}, HasAlpha={2}", bmpImage.FileFormat, bmpImage.RawDataFormat, bmpImage.HasAlpha);
};

// Как правило, BMP не поддерживает альфа-канал, поэтому вывод будет выглядеть так:
// FileFormat = Bmp, RawDataFormat = Rgb32Bpp, используемые каналы: 8,8,8,8, HasAlpha = False
// FileFormat = Bmp, RawDataFormat = Rgb24Bpp, используемые каналы: 8,8,8, HasAlpha = False
```

### Смотрите также

* enum [FileFormat](../../../aspose.imaging/fileformat)
* class [BmpImage](../../bmpimage)
* пространство имен [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
