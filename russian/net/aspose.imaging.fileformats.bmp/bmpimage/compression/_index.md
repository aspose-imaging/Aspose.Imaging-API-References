---
title: Compression
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает сжатие изображения.
type: docs
weight: 40
url: /ru/net/aspose.imaging.fileformats.bmp/bmpimage/compression/
---
## BmpImage.Compression property

Получает сжатие изображения.

```csharp
public BitmapCompression Compression { get; }
```

### Стоимость имущества

Сжатие изображения.

### Примеры

Следующий пример получает общую информацию об изображении, включая формат пикселей, размер изображения, разрешение, сжатие и т. д.

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
     // Создаем 8-битное BMP-изображение размером 100 x 100 пикселей.
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

 // Вывод выглядит следующим образом: 
 // ------------------------------------------------------------
 // Сжатие = Rgb
 // Количество бит на пиксель = 8
 // Размеры изображения = 100 x 100
 // Необработанный размер строки = 100
 // Размер вывода в байтах = 11078
 // ------------------------------------------------------------
 // Сжатие = Rle8
 // Количество бит на пиксель = 8
 // Размеры изображения = 100 x 100
 // Необработанный размер строки = 100
// Размер вывода в байтах = 856
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
     // Создаем 8-битное BMP-изображение размером 100 x 100 пикселей.
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

 // Вывод выглядит следующим образом: 
 // ------------------------------------------------------------
 // Сжатие = Rgb
 // Количество бит на пиксель = 8
 // Размеры изображения = 100 x 100
 // Необработанный размер строки = 100
 // Размер вывода в байтах = 11078
 // ------------------------------------------------------------
 // Сжатие = Rle8
 // Количество бит на пиксель = 8
 // Размеры изображения = 100 x 100
 // Необработанный размер строки = 100
// Размер вывода в байтах = 856
```

### Смотрите также

* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* пространство имен [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
