---
title: Width
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает ширину изображения.
type: docs
weight: 110
url: /ru/net/aspose.imaging.fileformats.bmp/bmpimage/width/
---
## BmpImage.Width property

Получает ширину изображения.

```csharp
public override int Width { get; }
```

### Стоимость имущества

Ширина изображения.

### Примеры

Следующий пример получает общую информацию об изображении, включая формат пикселей, размер изображения, разрешение, сжатие и т. д.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;                

    System.Console.WriteLine("The pixel format: {0}", bmpImage.RawDataFormat);                
    System.Console.WriteLine("The raw line size in bytes: {0}", bmpImage.RawLineSize);
    System.Console.WriteLine("The bitmap compression: {0}", bmpImage.Compression);
    System.Console.WriteLine("The bitmap width: {0}", bmpImage.Width);
    System.Console.WriteLine("The bitmap height: {0}", bmpImage.Height);
    System.Console.WriteLine("The number of bits per pixel: {0}", bmpImage.BitsPerPixel);

    double hres = bmpImage.HorizontalResolution;
    double vres = bmpImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", hres);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", vres);

    if (hres != 96.0 || vres != 96.0)
    {
        // Вы можете использовать метод SetResolution для обновления обоих значений разрешения в одном вызове.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        bmpImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", bmpImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", bmpImage.VerticalResolution);
    }

    //Вывод может выглядеть так:
    // Формат пикселей: Rgb24Bpp, используемые каналы: 8,8,8
    //Необработанный размер строки в байтах: 1500
    //Сжатие растрового изображения: Rgb
    //Ширина растрового изображения: 500
    //Высота растрового изображения: 375
    //Количество бит на пиксель: 24
    //Горизонтальное разрешение, в пикселях на дюйм: 0
    // Вертикальное разрешение, в пикселях на дюйм: 0
    //Установите значения разрешения на 96 dpi
    //Горизонтальное разрешение, в пикселях на дюйм: 96,012
    // Вертикальное разрешение, в пикселях на дюйм: 96,012
}
```

В следующем примере показано, как сжатие растрового изображения влияет на размер выходного изображения.

```csharp
[C#]

Aspose.Imaging.FileFormats.Bmp.BitmapCompression[] compressions = new Aspose.Imaging.FileFormats.Bmp.BitmapCompression[]
{
    Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb,
    Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rle8,
};

Aspose.Imaging.Color[] paletterColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
};

// Создаем монохромную палитру, содержащую только красный и зеленый цвета.
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

foreach (Aspose.Imaging.FileFormats.Bmp.BitmapCompression compression in compressions)
{
    // Создаем BMP-изображение 8 бит/пиксель размером 100 x 100 пикселей.
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 8, palette, compression, 0.0, 0.0))
    {
        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

        // Заливаем все изображение красным.
        Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
        gr.FillRectangle(redBrush, bmpImage.Bounds);

        // Сохраняем изображение в поток, чтобы получить выходной размер изображения.
        using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
        {
            bmpImage.Save(stream);

            System.Console.WriteLine("---------------------------------------------");
            System.Console.WriteLine("The compression={0}", bmpImage.Compression);
            System.Console.WriteLine("The number of bits per pixel={0}", bmpImage.BitsPerPixel);
            System.Console.WriteLine("The image dimensions={0} x {1}", bmpImage.Width, bmpImage.Height);
            System.Console.WriteLine("The raw line size={0}", bmpImage.RawLineSize);
            System.Console.WriteLine("The output size in bytes={0}", stream.Length);
        }
    }
}

// Вывод выглядит так:
// ---------------------------------------------------------------------------
// Сжатие = RGB
// Количество бит на пиксель = 8
// Размеры изображения = 100 х 100
// Необработанный размер строки = 100
// Размер вывода в байтах = 11078
// ---------------------------------------------------------------------------
// Сжатие = Rle8
// Количество бит на пиксель = 8
// Размеры изображения = 100 х 100
// Необработанный размер строки = 100
// Размер вывода в байтах = 856
```

### Смотрите также

* class [BmpImage](../../bmpimage)
* пространство имен [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
