---
title: BinarizeFixed
second_title: Справочник по Aspose.Imaging for .NET API
description: Бинаризация изображения с заданным порогом
type: docs
weight: 60
url: /ru/net/aspose.imaging/rastercachedimage/binarizefixed/
---
## RasterCachedImage.BinarizeFixed method

Бинаризация изображения с заданным порогом

```csharp
public override void BinarizeFixed(byte threshold)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| threshold | Byte | Пороговое значение. Если соответствующее значение серого пикселя больше порогового значения, ему будет присвоено значение 255, в противном случае — 0. |

### Примеры

В следующем примере выполняется бинаризация кэшированного растрового изображения с предопределенным пороговым значением. Бинаризованные изображения содержат только 2 цвета — черный и белый.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    // Бинаризовать изображение с пороговым значением 127.
    // Если соответствующее значение серого пикселя больше 127, ему будет присвоено значение 255, иначе 0.
    rasterImage.BinarizeFixed(127);
    rasterImage.Save(dir + "sample.BinarizeFixed.png");
}
```

### Смотрите также

* class [RasterCachedImage](../../rastercachedimage)
* пространство имен [Aspose.Imaging](../../rastercachedimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
