---
title: BinarizeBradley
second_title: Справочник по Aspose.Imaging for .NET API
description: Бинаризация изображения с использованием алгоритма адаптивной пороговой обработки Брэдли с использованием интегральной пороговой обработки изображения
type: docs
weight: 180
url: /ru/net/aspose.imaging.fileformats.djvu/djvuimage/binarizebradley/
---
## DjvuImage.BinarizeBradley method

Бинаризация изображения с использованием алгоритма адаптивной пороговой обработки Брэдли с использованием интегральной пороговой обработки изображения

```csharp
public override void BinarizeBradley(double brightnessDifference, int windowSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| brightnessDifference | Double | Разница яркости между пикселем и средним значением пикселей в окне sxs вокруг этого пикселя. |
| windowSize | Int32 | Размер окна sxs в пикселях с центром вокруг этого пикселя |

### Примеры

В следующем примере Изображение DJVU с адаптивным алгоритмом пороговой обработки Брэдли с заданным размером окна. Бинаризованные изображения содержат только 2 цвета — черный и белый.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

     // Бинаризация изображения с разницей яркости 5. Яркость — это разница между пикселем и средним значением окна 10 x 10 пикселей, центрированного вокруг этого пикселя.
    djvuImage.BinarizeBradley(5, 10);
    djvuImage.Save(dir + "sample.BinarizeBradley5_10x10.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Смотрите также

* class [DjvuImage](../../djvuimage)
* пространство имен [Aspose.Imaging.FileFormats.Djvu](../../djvuimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->