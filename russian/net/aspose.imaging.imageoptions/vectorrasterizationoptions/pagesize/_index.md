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

// Использование Aspose.Imaging.Image.Load — это унифицированный способ загрузки всех типов изображений, включая WMF.
using (Aspose.Imaging.FileFormats.Wmf.WmfImage wmfImage = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "test.wmf"))
{
    Aspose.Imaging.ImageOptions.SvgOptions saveOptions = new Aspose.Imaging.ImageOptions.SvgOptions();
        
    // Текст будет преобразован в фигуры.
    saveOptions.TextAsShapes = true;

    Aspose.Imaging.ImageOptions.WmfRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions();

    // Цвет фона поверхности рисования.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.WhiteSmoke;

    // Размер страницы.
    rasterizationOptions.PageSize = wmfImage.Size;

    // Если встроенная ЭДС существует, то визуализировать ЭДС; в противном случае визуализируйте wmf.
    rasterizationOptions.RenderMode = Aspose.Imaging.FileFormats.Wmf.WmfRenderMode.Auto;

    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    wmfImage.Save(dir + "test.output.svg", saveOptions);
}
```

В этом примере показано, как загрузить изображение EMF из файла и преобразовать его в SVG с помощью EmfRasterizationOptions.

```csharp
[C#]

string dir = "c:\\temp\\";

// Использование Aspose.Imaging.Image.Load — это унифицированный способ загрузки всех типов изображений, включая EMF.
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
    Aspose.Imaging.ImageOptions.SvgOptions saveOptions = new Aspose.Imaging.ImageOptions.SvgOptions();

    // Текст будет преобразован в фигуры.
    saveOptions.TextAsShapes = true;

    Aspose.Imaging.ImageOptions.EmfRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions();

    // Цвет фона поверхности рисования.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.WhiteSmoke;

    // Размер страницы.
    rasterizationOptions.PageSize = emfImage.Size;

    // Если встроенная ЭДС существует, то визуализировать ЭДС; в противном случае визуализируйте wmf.
    rasterizationOptions.RenderMode = Aspose.Imaging.FileFormats.Emf.EmfRenderMode.Auto;

    // Установить горизонтальное поле
    rasterizationOptions.BorderX = 50;

    // Установить вертикальное поле
    rasterizationOptions.BorderY = 50;

    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    emfImage.Save(dir + "test.output.svg", saveOptions);
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

    // Каждый символ рисуется с использованием своего сглаженного растрового изображения глифа без подсказок.
    rasterizationOptions.TextRenderingHint = Aspose.Imaging.TextRenderingHint.AntiAlias;

    // Уменьшить размер изображения в 10 раз, т.е. выходной размер будет 10% от исходного размера.
    rasterizationOptions.ScaleX = 0.1f;
    rasterizationOptions.ScaleY = 0.1f;

    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    // Сохраняем в файл PNG
    svgImage.Save(dir + "test.output.png", saveOptions);
}
```

### Смотрите также

* struct [SizeF](../../../aspose.imaging/sizef)
* class [VectorRasterizationOptions](../../vectorrasterizationoptions)
* пространство имен [Aspose.Imaging.ImageOptions](../../vectorrasterizationoptions)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
