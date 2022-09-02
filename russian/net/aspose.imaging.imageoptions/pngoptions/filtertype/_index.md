---
title: FilterType
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает или задает тип фильтра используемый во время процесса сохранения файла png.
type: docs
weight: 50
url: /ru/net/aspose.imaging.imageoptions/pngoptions/filtertype/
---
## PngOptions.FilterType property

Получает или задает тип фильтра, используемый во время процесса сохранения файла png.

```csharp
public PngFilterType FilterType { get; set; }
```

### Примеры

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

В следующем примере показано, как различные типы фильтров влияют на размер выходного изображения PNG.

```csharp
[C#]

Aspose.Imaging.FileFormats.Png.PngFilterType[] filterTypes = new Aspose.Imaging.FileFormats.Png.PngFilterType[]
{
    Aspose.Imaging.FileFormats.Png.PngFilterType.None,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Up,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Sub,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Paeth,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Avg,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Adaptive,
};

foreach (Aspose.Imaging.FileFormats.Png.PngFilterType filterType in filterTypes)
{
    Aspose.Imaging.ImageOptions.PngOptions options = new Aspose.Imaging.ImageOptions.PngOptions();

    using (Aspose.Imaging.Image image = Image.Load("c:\\temp\\sample.png"))
    {
        // Установить тип фильтра
        options.FilterType = filterType;

        using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
        {
            image.Save(stream, options);
            System.Console.WriteLine("The filter type is {0}, the output image size is {1} bytes.", filterType, stream.Length);
        }
    }
}

//Вывод может выглядеть так:
//Тип фильтра None, размер выходного изображения 116845 байт.
//Тип фильтра Up, размер выходного изображения 86360 байт.
//Тип фильтра Sub, размер выходного изображения 94907 байт.
//Тип фильтра Paeth, размер выходного изображения 86403 байт.
//Тип фильтра Avg, размер выходного изображения 89956 байт.
//Тип фильтра Adaptive, размер выходного изображения 97248 байт.
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

* enum [PngFilterType](../../../aspose.imaging.fileformats.png/pngfiltertype)
* class [PngOptions](../../pngoptions)
* пространство имен [Aspose.Imaging.ImageOptions](../../pngoptions)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
