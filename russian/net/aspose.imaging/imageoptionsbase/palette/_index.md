---
title: Palette
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает или задает цветовую палитру.
type: docs
weight: 40
url: /ru/net/aspose.imaging/imageoptionsbase/palette/
---
## ImageOptionsBase.Palette property

Получает или задает цветовую палитру.

```csharp
public virtual IColorPalette Palette { get; set; }
```

### Стоимость имущества

Цветовая палитра.

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

В следующем примере показано, как разместить изображение BMP на поддонах, чтобы уменьшить его выходной размер.

```csharp
[C#]

// Создаем BMP-изображение 100 x 100 пикселей.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Линейный градиент от левого верхнего до правого нижнего угла изображения.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(bmpImage.Width, bmpImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Залейте все изображение кистью линейного градиента.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // Получаем ближайшую 8-битную цветовую палитру, покрывающую максимально возможное количество пикселей, чтобы изображение с палитрой
    // визуально практически неотличим от не палетированного.
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(bmpImage, 256);

    // 8-битная палитра содержит не более 256 цветов.
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
    saveOptions.Palette = palette;
    saveOptions.BitsPerPixel = 8;

    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        bmpImage.Save(stream, saveOptions);
        System.Console.WriteLine("The palettized image size is {0} bytes.", stream.Length);
    }

    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        bmpImage.Save(stream);
        System.Console.WriteLine("The non-palettized image size is {0} bytes.", stream.Length);
    }
}

// Вывод выглядит так:
// Размер изображения с палитрой составляет 11078 байт.
// Размер изображения без палитры составляет 40054 байта.
```

### Смотрите также

* interface [IColorPalette](../../icolorpalette)
* class [ImageOptionsBase](../../imageoptionsbase)
* пространство имен [Aspose.Imaging](../../imageoptionsbase)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
