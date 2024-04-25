---
title: ResizeHeightProportionally
second_title: Справочник по Aspose.Imaging for .NET API
description: Изменяет размер высоты пропорционально. По умолчаниюNearestNeighbourResample используется.
type: docs
weight: 210
url: /ru/aspose.imaging/image/resizeheightproportionally/
---
## ResizeHeightProportionally(int) {#resizeheightproportionally}

Изменяет размер высоты пропорционально. По умолчаниюNearestNeighbourResample используется.

```csharp
public void ResizeHeightProportionally(int newHeight)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| newHeight | Int32 | Новая высота. |

### Смотрите также

* class [Image](../../image)
* пространство имен [Aspose.Imaging](../../image)
* сборка [Aspose.Imaging](../../../)

---

## ResizeHeightProportionally(int, ResizeType) {#resizeheightproportionally_2}

Изменяет размер высоты пропорционально.

```csharp
public virtual void ResizeHeightProportionally(int newHeight, ResizeType resizeType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| newHeight | Int32 | Новая высота. |
| resizeType | ResizeType | Тип изменения размера. |

### Примеры

В этом примере загружается изображение и пропорционально изменяется его размер с использованием различных методов изменения размера. Задается только высота, ширина рассчитывается автоматически.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Масштабирование в 2 раза с использованием передискретизации ближайших соседей.
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Масштабирование в 2 раза с использованием передискретизации ближайших соседей.
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Масштабируем в 2 раза, используя билинейную передискретизацию.
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "upsample.bilinear.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Уменьшить масштаб в 2 раза, используя билинейную передискретизацию.
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "downsample.bilinear.gif");
}
```

Использование маски сегмента для ускорения процесса сегментации

```csharp
[C#]

// Маскировка опций экспорта
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
    
// Использовать кластеризацию GraphCut.
maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
maskingOptions.Decompose = false;
maskingOptions.Args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

// Цвет фона будет прозрачным.
maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Transparent;
maskingOptions.ExportOptions = exportOptions;

string dir = "c:\\temp\\";
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
{
    Aspose.Imaging.Size imageSize = image.Size;

    // Уменьшение размера изображения для ускорения процесса сегментации
    image.ResizeHeightProportionally(600, Aspose.Imaging.ResizeType.HighQualityResample);

    // Создаем экземпляр класса ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // Разделить исходное изображение на несколько кластеров (сегментов).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // Получение маски переднего плана
        using (Aspose.Imaging.RasterImage foregroundMask = maskingResult[1].GetMask()) 
        {
            // Увеличиваем размер маски до размера исходного изображения
            foregroundMask.Resize(imageSize.Width, imageSize.Height, Aspose.Imaging.ResizeType.NearestNeighbourResample);

            // Применение маски к исходному изображению для получения сегмента переднего плана
            using (Aspose.Imaging.RasterImage originImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
            {
                Aspose.Imaging.Masking.ImageMasking.ApplyMask(originImage, foregroundMask, maskingOptions);
                originImage.Save(dir + "BigImage_foreground.png", exportOptions);
            }
        }
    }
}
```

### Смотрите также

* enum [ResizeType](../../resizetype)
* class [Image](../../image)
* пространство имен [Aspose.Imaging](../../image)
* сборка [Aspose.Imaging](../../../)

---

## ResizeHeightProportionally(int, ImageResizeSettings) {#resizeheightproportionally_1}

Изменяет размер высоты пропорционально.

```csharp
public virtual void ResizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| newHeight | Int32 | Новая высота. |
| settings | ImageResizeSettings | Настройки изменения размера изображения. |

### Смотрите также

* class [ImageResizeSettings](../../imageresizesettings)
* class [Image](../../image)
* пространство имен [Aspose.Imaging](../../image)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
