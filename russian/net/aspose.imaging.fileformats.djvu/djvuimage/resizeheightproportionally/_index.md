---
title: ResizeHeightProportionally
second_title: Справочник по Aspose.Imaging for .NET API
description: Изменяет ширину пропорционально.
type: docs
weight: 270
url: /ru/net/aspose.imaging.fileformats.djvu/djvuimage/resizeheightproportionally/
---
## DjvuImage.ResizeHeightProportionally method

Изменяет ширину пропорционально.

```csharp
public override void ResizeHeightProportionally(int newHeight, ResizeType resizeType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| newHeight | Int32 | Новая высота. |
| resizeType | ResizeType | Тип изменения размера. |

### Примеры

В этом примере загружается изображение DJVU и пропорционально изменяется его размер с использованием различных методов изменения размера. Задается только высота, ширина рассчитывается автоматически.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // Масштабирование в 2 раза с использованием передискретизации ближайших соседей.
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // Масштабирование в 2 раза с использованием передискретизации ближайших соседей.
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // Масштабируем в 2 раза, используя билинейную передискретизацию.
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // Уменьшить масштаб в 2 раза, используя билинейную передискретизацию.
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Смотрите также

* enum [ResizeType](../../../aspose.imaging/resizetype)
* class [DjvuImage](../../djvuimage)
* пространство имен [Aspose.Imaging.FileFormats.Djvu](../../djvuimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
