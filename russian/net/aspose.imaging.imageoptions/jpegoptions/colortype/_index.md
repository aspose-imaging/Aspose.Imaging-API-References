---
title: ColorType
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает или задает тип цвета для изображения jpeg.
type: docs
weight: 40
url: /ru/net/aspose.imaging.imageoptions/jpegoptions/colortype/
---
## JpegOptions.ColorType property

Получает или задает тип цвета для изображения jpeg.

```csharp
public JpegCompressionColorMode ColorType { get; set; }
```

### Примеры

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

В следующем примере загружается PNG и сохраняется в формате CMYK JPEG с использованием пользовательского профиля ICC. Затем загружает CMYK JPEG и сохраняет его обратно в PNG. Преобразование цветов из RGB в CMYK и из CMYK в RGB выполняется с использованием пользовательских профилей ICC.

```csharp
[C#]

string dir = "c:\\temp\\";

// Загружаем PNG и сохраняем в CMYK JPEG
using (Aspose.Imaging.FileFormats.Png.PngImage image = (Aspose.Imaging.FileFormats.Png.PngImage)Image.Load(dir + "sample.png"))
{
    using (System.IO.Stream rgbProfileStream = System.IO.File.OpenRead(dir + "eciRGB_v2.icc"))
    using (System.IO.Stream cmykProfileStream = System.IO.File.OpenRead(dir + "ISOcoated_v2_FullGamut4.icc"))
    {
        Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();
        saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Cmyk;

        // Использовать пользовательские профили ICC
        saveOptions.RgbColorProfile = new Aspose.Imaging.Sources.StreamSource(rgbProfileStream);
        saveOptions.CmykColorProfile = new Aspose.Imaging.Sources.StreamSource(cmykProfileStream);

        image.Save(dir + "output.cmyk.jpg", saveOptions);
    }
}

// Загружаем CMYK JPEG и сохраняем в PNG
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage image = (Aspose.Imaging.FileFormats.Jpeg.JpegImage)Image.Load(dir + "output.cmyk.jpg"))
{
    using (System.IO.Stream rgbProfileStream = System.IO.File.OpenRead(dir + "eciRGB_v2.icc"))
    using (System.IO.Stream cmykProfileStream = System.IO.File.OpenRead(dir + "ISOcoated_v2_FullGamut4.icc"))
    {
        // Использовать пользовательские профили ICC
        image.RgbColorProfile = new Aspose.Imaging.Sources.StreamSource(rgbProfileStream);
        image.CmykColorProfile = new Aspose.Imaging.Sources.StreamSource(cmykProfileStream);

        Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
        image.Save(dir + "output.rgb.png", saveOptions);
    }
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

* enum [JpegCompressionColorMode](../../../aspose.imaging.fileformats.jpeg/jpegcompressioncolormode)
* class [JpegOptions](../../jpegoptions)
* пространство имен [Aspose.Imaging.ImageOptions](../../jpegoptions)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
