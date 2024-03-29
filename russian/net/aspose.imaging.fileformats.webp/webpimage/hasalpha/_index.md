---
title: HasAlpha
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает альфа-канал.
type: docs
weight: 30
url: /ru/net/aspose.imaging.fileformats.webp/webpimage/hasalpha/
---
## WebPImage.HasAlpha property

Получает альфа-канал.

```csharp
public override bool HasAlpha { get; }
```

### Стоимость имущества

Имеет альфа-канал.

### Примеры

В следующем примере загружается изображение WEBP и выводится информация о формате необработанных данных и альфа-канале.

```csharp
[C#]

string dir = "c:\\temp\\";

string fileName = dir + "sample.webp";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(fileName))
{
    Aspose.Imaging.FileFormats.Webp.WebPImage webpImage = (Aspose.Imaging.FileFormats.Webp.WebPImage)image;

    // Если активный кадр TIFF имеет альфа-канал, то считается, что все изображение TIFF имеет альфа-канал.
    System.Console.WriteLine("ImageFile={0}, FileFormat={1}, HasAlpha={2}", fileName, webpImage.RawDataFormat, webpImage.HasAlpha);

    int i = 0;
    foreach (Aspose.Imaging.FileFormats.Webp.IFrame frame in webpImage.Blocks)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock frameBlock = frame as Aspose.Imaging.FileFormats.Webp.WebPFrameBlock;
        if (frameBlock != null)
        {
            System.Console.WriteLine("Frame={0}, FileFormat={1}, HasAlpha={2}", i++, frameBlock.RawDataFormat, frameBlock.HasAlpha);
        }
    }
}

// Вывод может выглядеть так:
// ImageFile=c:\temp\sample.webp, FileFormat=RgbIndexed1Bpp, используемые каналы: 1, HasAlpha=False
// Frame=0, FileFormat=RgbIndexed1Bpp, используемые каналы: 1, HasAlpha=False
```

### Смотрите также

* class [WebPImage](../../webpimage)
* пространство имен [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
