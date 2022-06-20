---
title: BinarizeBradley
second_title: Справочник по Aspose.Imaging for .NET API
description: Бинаризация изображения с использованием алгоритма адаптивной пороговой обработки Брэдли с использованием интегральной пороговой обработки изображения
type: docs
weight: 50
url: /ru/net/aspose.imaging/rastercachedimage/binarizebradley/
---
## BinarizeBradley(double, int) {#binarizebradley_1}

Бинаризация изображения с использованием алгоритма адаптивной пороговой обработки Брэдли с использованием интегральной пороговой обработки изображения

```csharp
public override void BinarizeBradley(double brightnessDifference, int windowSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| brightnessDifference | Double | Разница яркости между пикселем и средним значением пикселей в окне sxs с центром вокруг этого пикселя. |
| windowSize | Int32 | Размер окна sxs в пикселях с центром вокруг этого пикселя |

### Примеры

В следующем примере растровое кэшированное изображение с адаптивным пороговым алгоритмом Брэдли с заданным размером окна. Бинаризованные изображения содержат только 2 цвета — черный и белый.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

     // Бинаризуем изображение с разницей яркости 5.
     // Яркость — это разница между пикселем и средним значением окна 10 x 10 пикселей, центрированного вокруг этого пикселя.
    rasterImage.BinarizeBradley(5, 10);
    rasterImage.Save(dir + "sample.BinarizeBradley5_10x10.png");
}
```

### Смотрите также

* class [RasterCachedImage](../../rastercachedimage)
* пространство имен [Aspose.Imaging](../../rastercachedimage)
* сборка [Aspose.Imaging](../../../)

---

## BinarizeBradley(double) {#binarizebradley}

Бинаризация изображения с использованием алгоритма адаптивной пороговой обработки Брэдли с использованием интегральной пороговой обработки изображения

```csharp
public override void BinarizeBradley(double brightnessDifference)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| brightnessDifference | Double | Разница яркости между пикселем и средним значением пикселей в окне sxs с центром вокруг этого пикселя. |

### Примеры

В следующем примере выполняется бинаризация кэшированного растрового изображения с помощью алгоритма адаптивного порогового значения Брэдли. Бинаризованные изображения содержат только 2 цвета — черный и белый.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

     // Бинаризация изображения с разницей яркости 5. 
    // Яркость — это разница между пикселем и средним значением пикселей в окне sxs, центрированных вокруг этого пикселя.
     // Размер окна будет откалиброван автоматически.
    rasterImage.BinarizeBradley(5);
    rasterImage.Save(dir + "sample.BinarizeBradley5.png");
}
```

### Смотрите также

* class [RasterCachedImage](../../rastercachedimage)
* пространство имен [Aspose.Imaging](../../rastercachedimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->