---
title: AdjustContrast
second_title: Справочник по Aspose.Imaging for .NET API
description: Регулирует контрастность.
type: docs
weight: 240
url: /ru/net/aspose.imaging.fileformats.gif/gifimage/adjustcontrast/
---
## GifImage.AdjustContrast method

Регулирует контрастность.

```csharp
public override void AdjustContrast(float contrast)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| contrast | Single | Значение контраста (в диапазоне [-100; 100]) |

### Исключения

| исключение | условие |
| --- | --- |
| [ImageException](../../../aspose.imaging.coreexceptions/imageexception) | Не могу изменить контраст. Индекс кадра: "+frameIndex |

### Примеры

В следующем примере выполняется коррекция контраста изображения GIF.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // Установить значение контраста. Принятые значения контраста находятся в диапазоне [-100f, 100f].
    gifImage.AdjustContrast(50f);
    gifImage.Save(dir + "sample.AdjustContrast.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Смотрите также

* class [GifImage](../../gifimage)
* пространство имен [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
