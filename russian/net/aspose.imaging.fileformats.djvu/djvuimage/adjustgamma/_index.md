---
title: AdjustGamma
second_title: Справочник по Aspose.Imaging for .NET API
description: Гамма-коррекция изображения.
type: docs
weight: 170
url: /ru/net/aspose.imaging.fileformats.djvu/djvuimage/adjustgamma/
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

В следующем примере выполняется гамма-коррекция изображения DJVU.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // Установите коэффициент гаммы для красного, зеленого и синего каналов.
    djvuImage.AdjustGamma(2.5f);
    djvuImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Смотрите также

* class [DjvuImage](../../djvuimage)
* пространство имен [Aspose.Imaging.FileFormats.Djvu](../../djvuimage)
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

В следующем примере выполняется гамма-коррекция изображения DJVU с применением различных коэффициентов для компонентов цвета.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // Установить индивидуальные гамма-коэффициенты для красного, зеленого и синего каналов.
    djvuImage.AdjustGamma(1.5f, 2.5f, 3.5f);
    djvuImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Смотрите также

* class [DjvuImage](../../djvuimage)
* пространство имен [Aspose.Imaging.FileFormats.Djvu](../../djvuimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
