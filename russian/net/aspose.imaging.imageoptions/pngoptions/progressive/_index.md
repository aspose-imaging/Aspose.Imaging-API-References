---
title: Progressive
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает или задает значение указывающее является ли этотPngOptionsaspose.imaging.imageoptions/pngoptionsпрогрессивным.
type: docs
weight: 60
url: /ru/net/aspose.imaging.imageoptions/pngoptions/progressive/
---
## PngOptions.Progressive property

Получает или задает значение, указывающее, является ли этот[`PngOptions`](../../pngoptions)прогрессивным.

```csharp
public bool Progressive { get; set; }
```

### Стоимость имущества

` true` если прогрессивный; в противном случае` false` .

### Примеры

В следующем примере показано, как сжать изображение PNG, используя индексированный цвет с палитрой наилучшего соответствия

```csharp
[C#]

string dir = "c:\\temp\\";

 // Создаем изображение PNG размером 100x100 px.
 // Вы также можете загрузить изображение любого поддерживаемого формата из файла или потока.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

     // Заливаем изображение голубо-прозрачным градиентом.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();

     // Прогрессивная загрузка.
    saveOptions.Progressive = true;

    // Установите разрешение по горизонтали и вертикали на 96 пикселей на дюйм.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

     // Каждый пиксель представляет собой тройку (красный, зеленый, синий), за которой следует alpha.
    saveOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

     // Установить максимальный уровень сжатия.
    saveOptions.CompressionLevel = 9;

     // Это лучшее сжатие, но самое медленное время выполнения.
     // Адаптивная фильтрация означает, что процесс сохранения выберет наиболее подходящий фильтр для каждой строки данных.
    saveOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Adaptive;

     // Количество бит на канал.
    saveOptions.BitDepth = 8;

     // Сохраняем в файл.
    pngImage.Save(dir + "output.png", saveOptions);
}
```

В этом примере показано, как создать изображение PNG с указанными параметрами, заполнить его цветами линейного градиента и сохранить в файл.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Создаем изображение PNG размером 100x100 px.
 // Вы также можете загрузить изображение любого поддерживаемого формата из файла или потока.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

     // Заливаем изображение голубо-прозрачным градиентом.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();

     // Прогрессивная загрузка.
    saveOptions.Progressive = true;

    // Установите разрешение по горизонтали и вертикали на 96 пикселей на дюйм.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

     // Каждый пиксель представляет собой тройку (красный, зеленый, синий), за которой следует alpha.
    saveOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

     // Установить максимальный уровень сжатия.
    saveOptions.CompressionLevel = 9;

     // Это лучшее сжатие, но самое медленное время выполнения.
     // Адаптивная фильтрация означает, что процесс сохранения выберет наиболее подходящий фильтр для каждой строки данных.
    saveOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Adaptive;

     // Количество бит на канал.
    saveOptions.BitDepth = 8;

     // Сохраняем в файл.
    pngImage.Save(dir + "output.png", saveOptions);
}
```

В следующем примере показано, как сохранить изображение в формате PNG с использованием различных параметров.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Создаем изображение PNG размером 100x100 px.
 // Вы также можете загрузить изображение любого поддерживаемого формата из файла или потока.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

     // Заливаем изображение голубо-прозрачным градиентом.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();

     // Прогрессивная загрузка.
    saveOptions.Progressive = true;

    // Установите разрешение по горизонтали и вертикали на 96 пикселей на дюйм.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

     // Каждый пиксель представляет собой тройку (красный, зеленый, синий), за которой следует alpha.
    saveOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

     // Установить максимальный уровень сжатия.
    saveOptions.CompressionLevel = 9;

     // Это лучшее сжатие, но самое медленное время выполнения.
     // Адаптивная фильтрация означает, что процесс сохранения выберет наиболее подходящий фильтр для каждой строки данных.
    saveOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Adaptive;

     // Количество бит на канал.
    saveOptions.BitDepth = 8;

     // Сохраняем в файл.
    pngImage.Save(dir + "output.png", saveOptions);
}
```

### Смотрите также

* class [PngOptions](../../pngoptions)
* пространство имен [Aspose.Imaging.ImageOptions](../../pngoptions)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
