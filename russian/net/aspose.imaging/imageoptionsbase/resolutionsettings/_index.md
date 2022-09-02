---
title: ResolutionSettings
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает или задает параметры разрешения.
type: docs
weight: 60
url: /ru/net/aspose.imaging/imageoptionsbase/resolutionsettings/
---
## ImageOptionsBase.ResolutionSettings property

Получает или задает параметры разрешения.

```csharp
public virtual ResolutionSetting ResolutionSettings { get; set; }
```

### Примеры

В следующем примере загружается изображение BMP и сохраняется обратно в BMP с использованием различных параметров сохранения.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Создать BmpOptions
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Используйте 8 бит на пиксель, чтобы уменьшить размер выходного изображения.
    saveOptions.BitsPerPixel = 8;

    // Устанавливаем ближайшую 8-битную цветовую палитру, которая покрывает максимальное количество пикселей изображения, чтобы изображение с палитрой
    // визуально практически неотличим от не палетированного.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(rasterImage, 256);

    // Сохранить без сжатия.
    // Вы также можете использовать сжатие RLE-8, чтобы уменьшить размер выходного изображения.
    saveOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

    // Установите разрешение по горизонтали и вертикали на 96 dpi.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    image.Save(dir + "sample.bmpoptions.bmp", saveOptions);
}
```

В следующем примере загружается изображение BMP и сохраняется в формате JPEG с использованием различных параметров сохранения.

```csharp
[C#]

string dir = "c:\\temp\\";

// Загрузить изображение BMP из файла.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Выполнить некоторую обработку изображения.

    // Используйте дополнительные опции, чтобы указать нужные параметры изображения.
    Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

    // Количество бит на канал равно 8.
    // Когда используется палитра, индекс цвета сохраняется в данных изображения вместо самого цвета.
    saveOptions.BitsPerChannel = 8;

    // Установить прогрессивный тип сжатия.
    saveOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

    // Установить качество изображения. Это значение от 1 до 100.
    saveOptions.Quality = 100;

    // Установите разрешение по горизонтали/вертикали на 96 точек на дюйм.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
    saveOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

    // Если исходное изображение цветное, оно будет преобразовано в оттенки серого.
    saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Grayscale;

    // Используйте палитру, чтобы уменьшить размер вывода.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

    image.Save(dir + "sample.palettized.jpg", saveOptions);
}
```

В следующем примере создается изображение BMP с палитрой оттенков серого, а затем сохраняется в файл.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.BmpOptions createOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

// Сохраняем в файл
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "output.palette8bit.bmp", false);
    
// Используйте 8 бит на пиксель, чтобы уменьшить размер выходного изображения.
createOptions.BitsPerPixel = 8;

// Установите стандартную 8-битную цветовую палитру оттенков серого, которая охватывает все цвета оттенков серого.
// Если обработанное изображение содержит только оттенки серого, то его версия с палитрой
// визуально неотличим от не палетированного.
createOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

// Сохранить без сжатия.
// Вы также можете использовать сжатие RLE-8, чтобы уменьшить размер выходного изображения.
createOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

// Установите разрешение по горизонтали и вертикали на 96 dpi.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

// Создаем BMP-изображение размером 100 x 100 пикселей и сохраняем его в файл.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(image.Width, image.Height),
        Aspose.Imaging.Color.Black,
        Aspose.Imaging.Color.White);

    // Заливаем изображение градиентом в градациях серого
    graphics.FillRectangle(gradientBrush, image.Bounds);

    image.Save();
}
```

В следующем примере показано, как создать изображение JPEG указанного размера с указанными параметрами.

```csharp
[C#]

string dir = "c:\\temp\\";

// Создаем изображение в формате JPEG размером 100x100 пикселей.
// Используйте дополнительные опции, чтобы указать нужные параметры изображения.
Aspose.Imaging.ImageOptions.JpegOptions createOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

// Количество бит на канал 8, 8, 8 для компонентов Y, Cr, Cb соответственно.
createOptions.BitsPerChannel = 8;

// Установить прогрессивный тип сжатия.
createOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

// Установить качество изображения. Это значение от 1 до 100.
createOptions.Quality = 100;

// Установите разрешение по горизонтали/вертикали на 96 точек на дюйм.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
createOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

// Это стандартная опция для изображений JPEG.
// Два компонента цветности (Cb и Cr) могут быть подвергнуты уменьшению пропускной способности, субдискретизации, сжатию.
createOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr;

using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpegImage);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(jpegImage.Width, jpegImage.Height),
        Aspose.Imaging.Color.Yellow,
        Aspose.Imaging.Color.Blue);

    // Заливаем изображение градиентом в градациях серого
    graphics.FillRectangle(gradientBrush, jpegImage.Bounds);

    // Сохраняем в файл.
    jpegImage.Save(dir + "output.explicitoptions.jpg");
}
```

### Смотрите также

* class [ResolutionSetting](../../resolutionsetting)
* class [ImageOptionsBase](../../imageoptionsbase)
* пространство имен [Aspose.Imaging](../../imageoptionsbase)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
