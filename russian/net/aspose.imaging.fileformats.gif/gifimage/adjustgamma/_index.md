---
title: AdjustGamma
second_title: Справочник по Aspose.Imaging for .NET API
description: Гамма-коррекция изображения.
type: docs
weight: 250
url: /ru/net/aspose.imaging.fileformats.gif/gifimage/adjustgamma/
---
## AdjustGamma(float) {#adjustgamma}

Гамма-коррекция изображения.

```csharp
public override void AdjustGamma(float gamma)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| gamma | Single | Коэффициент гаммы для красного, зеленого и синего каналов |

### Примеры

В следующем примере выполняется гамма-коррекция изображения GIF.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // Установите коэффициент гаммы для красного, зеленого и синего каналов.
    gifImage.AdjustGamma(2.5f);
    gifImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Смотрите также

* class [GifImage](../../gifimage)
* пространство имен [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* сборка [Aspose.Imaging](../../../)

---

## AdjustGamma(float, float, float) {#adjustgamma_1}

Гамма-коррекция изображения.

```csharp
public override void AdjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| gammaRed | Single | Гамма для коэффициента красного канала |
| gammaGreen | Single | Гамма коэффициента зеленого канала |
| gammaBlue | Single | Гамма коэффициента синего канала |

### Примеры

В следующем примере выполняется гамма-коррекция изображения GIF с применением различных коэффициентов для компонентов цвета.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // Установить индивидуальные гамма-коэффициенты для красного, зеленого и синего каналов.
    gifImage.AdjustGamma(1.5f, 2.5f, 3.5f);
    gifImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Смотрите также

* class [GifImage](../../gifimage)
* пространство имен [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
