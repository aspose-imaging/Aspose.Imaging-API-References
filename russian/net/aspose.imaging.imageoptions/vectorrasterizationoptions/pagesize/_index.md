---
title: PageSize
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает или задает размер страницы.
type: docs
weight: 80
url: /ru/net/aspose.imaging.imageoptions/vectorrasterizationoptions/pagesize/
---
## VectorRasterizationOptions.PageSize property

Получает или задает размер страницы.

```csharp
public SizeF PageSize { get; set; }
```

### Примеры

В этом примере показано, как загрузить изображение WMF из файла и преобразовать его в SVG с помощью WmfRasterizationOptions.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Использование Aspose.Imaging.Image.Load — это унифицированный способ загрузки изображения.
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = (Aspose.Imaging.FileFormats.Svg.SvgImage)Aspose.Imaging.Image.Load(dir + "test.svg"))
{
     // Чтобы растеризовать SVG, нам нужно указать параметры растеризации.
    Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();

     // Установить цвет фона по умолчанию для изображения. Значение по умолчанию — белый.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.Gray;

     // Установить размер страницы
    rasterizationOptions.PageSize = svgImage.Size;

     // Сглаживание применяется к линиям и кривым, а также к краям заполненных областей.
    rasterizationOptions.SmoothingMode = Aspose.Imaging.SmoothingMode.AntiAlias;

     // Каждый символ рисуется с использованием сглаженного растрового изображения глифа без хинтинга.
    rasterizationOptions.TextRenderingHint = Aspose.Imaging.TextRenderingHint.AntiAlias;

     // Уменьшаем размер изображения в 10 раз, т.е. выходной размер будет 10% от исходного размера.
    rasterizationOptions.ScaleX = 0.1f;
    rasterizationOptions.ScaleY = 0.1f;

    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    saveOptions.VectorRasterizationOptions = rasterizationOptions;

     // Сохранить в PNG file
    svgImage.Save(dir + "test.output.png", saveOptions);
}
```

В этом примере показано, как загрузить изображение EMF из файла и преобразовать его в SVG с помощью EmfRasterizationOptions.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Использование Aspose.Imaging.Image.Load — это унифицированный способ загрузки изображения.
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = (Aspose.Imaging.FileFormats.Svg.SvgImage)Aspose.Imaging.Image.Load(dir + "test.svg"))
{
     // Чтобы растеризовать SVG, нам нужно указать параметры растеризации.
    Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();

     // Установить цвет фона по умолчанию для изображения. Значение по умолчанию — белый.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.Gray;

     // Установить размер страницы
    rasterizationOptions.PageSize = svgImage.Size;

     // Сглаживание применяется к линиям и кривым, а также к краям заполненных областей.
    rasterizationOptions.SmoothingMode = Aspose.Imaging.SmoothingMode.AntiAlias;

     // Каждый символ рисуется с использованием сглаженного растрового изображения глифа без хинтинга.
    rasterizationOptions.TextRenderingHint = Aspose.Imaging.TextRenderingHint.AntiAlias;

     // Уменьшаем размер изображения в 10 раз, т.е. выходной размер будет 10% от исходного размера.
    rasterizationOptions.ScaleX = 0.1f;
    rasterizationOptions.ScaleY = 0.1f;

    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    saveOptions.VectorRasterizationOptions = rasterizationOptions;

     // Сохранить в PNG file
    svgImage.Save(dir + "test.output.png", saveOptions);
}
```

В этом примере показано, как загрузить изображение SVG из файла и растрировать его в PNG, используя различные параметры.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Использование Aspose.Imaging.Image.Load — это унифицированный способ загрузки изображения.
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = (Aspose.Imaging.FileFormats.Svg.SvgImage)Aspose.Imaging.Image.Load(dir + "test.svg"))
{
     // Чтобы растеризовать SVG, нам нужно указать параметры растеризации.
    Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();

     // Установить цвет фона по умолчанию для изображения. Значение по умолчанию — белый.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.Gray;

     // Установить размер страницы
    rasterizationOptions.PageSize = svgImage.Size;

     // Сглаживание применяется к линиям и кривым, а также к краям заполненных областей.
    rasterizationOptions.SmoothingMode = Aspose.Imaging.SmoothingMode.AntiAlias;

     // Каждый символ рисуется с использованием сглаженного растрового изображения глифа без хинтинга.
    rasterizationOptions.TextRenderingHint = Aspose.Imaging.TextRenderingHint.AntiAlias;

     // Уменьшаем размер изображения в 10 раз, т.е. выходной размер будет 10% от исходного размера.
    rasterizationOptions.ScaleX = 0.1f;
    rasterizationOptions.ScaleY = 0.1f;

    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    saveOptions.VectorRasterizationOptions = rasterizationOptions;

     // Сохранить в PNG file
    svgImage.Save(dir + "test.output.png", saveOptions);
}
```

### Смотрите также

* struct [SizeF](../../../aspose.imaging/sizef)
* class [VectorRasterizationOptions](../../vectorrasterizationoptions)
* пространство имен [Aspose.Imaging.ImageOptions](../../vectorrasterizationoptions)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
