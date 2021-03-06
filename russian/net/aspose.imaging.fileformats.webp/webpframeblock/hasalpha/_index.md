---
title: HasAlpha
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает значение указывающее имеет ли этот экземпляр альфа-канал.
type: docs
weight: 80
url: /ru/net/aspose.imaging.fileformats.webp/webpframeblock/hasalpha/
---
## WebPFrameBlock.HasAlpha property

Получает значение, указывающее, имеет ли этот экземпляр альфа-канал.

```csharp
public override bool HasAlpha { get; }
```

### Стоимость имущества

` true` если у этого экземпляра есть альфа; в противном случае` false` .

### Примеры

В следующем примере загружается изображение WEBP и выводится информация о формате необработанных данных и альфа-канале.

```csharp
[C#]

string dir = "c:\\temp\\";

string fileName = dir + "sample.webp";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(fileName))
{
    Aspose.Imaging.FileFormats.Webp.WebPImage webpImage = (Aspose.Imaging.FileFormats.Webp.WebPImage)image;

     // Если активный кадр TIFF имеет альфа-канал, то все изображение TIFF считается имеющим альфа-канал.
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

* class [WebPFrameBlock](../../webpframeblock)
* пространство имен [Aspose.Imaging.FileFormats.Webp](../../webpframeblock)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
