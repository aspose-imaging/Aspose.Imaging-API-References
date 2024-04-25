---
title: BitsPerPixel
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает или задает количество бит изображения на пиксель.
type: docs
weight: 20
url: /ru/aspose.imaging.imageoptions/bmpoptions/bitsperpixel/
---
## BmpOptions.BitsPerPixel property

Получает или задает количество бит изображения на пиксель.

```csharp
public int BitsPerPixel { get; set; }
```

### Стоимость имущества

Количество бит изображения на пиксель.

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

* class [BmpOptions](../../bmpoptions)
* пространство имен [Aspose.Imaging.ImageOptions](../../bmpoptions)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
