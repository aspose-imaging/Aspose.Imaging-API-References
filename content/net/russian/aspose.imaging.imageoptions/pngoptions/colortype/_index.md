---
title: ColorType
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает или задает тип цвета.
type: docs
weight: 30
url: /ru/aspose.imaging.imageoptions/pngoptions/colortype/
---
## PngOptions.ColorType property

Получает или задает тип цвета.

```csharp
public PngColorType ColorType { get; set; }
```

### Стоимость имущества

Тип цвета.

### Примеры

В следующем примере показано, как сжать изображение PNG с использованием индексированного цвета с палитрой наилучшего соответствия.

```csharp
[C#]

// Загружаем png изображение        
    string  sourceFilePath="OriginalRings.png";
    string  outputFilePath="OriginalRingsOutput.png";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new Aspose.Imaging.ImageOptions.PngOptions()
    {
         Progressive = true,
             // Использовать индексированный тип цвета
         ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.IndexedColor,
             // Использовать максимальное сжатие
         CompressionLevel = 9,
      // Получаем ближайшую 8-битную цветовую палитру, покрывающую максимально возможное количество пикселей, чтобы изображение с палитрой
         // визуально практически неотличим от не палетированного.
         Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette((Aspose.Imaging.RasterImage)image, 256, Aspose.Imaging.PaletteMiningMethod.Histogram)
    });
}
    // Размер выходного файла должен быть значительно уменьшен
```

В этом примере показано, как создать изображение PNG с указанными параметрами, заполнить его цветами линейного градиента и сохранить в файл.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();

// Количество бит на цветовой канал
createOptions.BitDepth = 8;

// Каждый пиксель представляет собой тройку (красный, зеленый, синий), за которой следует альфа-компонент.
createOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

// Максимальный уровень сжатия.
createOptions.CompressionLevel = 9;

// Использование фильтров позволяет более эффективно сжимать непрерывные тональные изображения.
createOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Sub;

// Использовать прогрессивную загрузку
createOptions.Progressive = true;

// Создаем изображение PNG с пользовательскими параметрами.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(createOptions, 100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Заливаем изображение полупрозрачным градиентом.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    // Сохраняем в файл.
    pngImage.Save(dir + "output.explicitoptions.png");
}
```

В следующем примере показано, как сохранить изображение в формате PNG с использованием различных параметров.

```csharp
[C#]

string dir = "c:\\temp\\";

// Создаем PNG-изображение размером 100x100 пикселей.
// Вы также можете загрузить изображение любого поддерживаемого формата из файла или потока.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Заливаем изображение сине-прозрачным градиентом.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    // Прогрессивная загрузка.
    saveOptions.Progressive = true;

    // Установите разрешение по горизонтали и вертикали на 96 пикселей на дюйм.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    // Каждый пиксель представляет собой тройку (красный, зеленый, синий), за которой следует альфа.
    saveOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

    // Установите максимальный уровень сжатия.
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

* enum [PngColorType](../../../aspose.imaging.fileformats.png/pngcolortype)
* class [PngOptions](../../pngoptions)
* пространство имен [Aspose.Imaging.ImageOptions](../../pngoptions)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
