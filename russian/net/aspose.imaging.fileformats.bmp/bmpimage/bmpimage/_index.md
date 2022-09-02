---
title: BmpImage
second_title: Справочник по Aspose.Imaging for .NET API
description: Инициализирует новый экземплярBmpImageaspose.imaging.fileformats.bmp/bmpimage класс.
type: docs
weight: 10
url: /ru/net/aspose.imaging.fileformats.bmp/bmpimage/bmpimage/
---
## BmpImage(string) {#constructor_7}

Инициализирует новый экземпляр[`BmpImage`](../../bmpimage) класс.

```csharp
public BmpImage(string path)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Путь для загрузки изображения и инициализации данных пикселей и палитры. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | растровое изображение равно null;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Высота должна быть положительной. |
| ArgumentException | Палитра должна быть указана для изображений с 8 битами на пиксель или меньше.;палитра |

### Примеры

В примере показано, как загрузить BmpImage из файла.

```csharp
[C#]

string dir = "c:\\temp\\";

// Загрузить изображение BMP из файла.
// При необходимости исходные пиксели будут преобразованы в 32-битный формат.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(dir + "sample.bmp"))
{
    // Выполнить некоторую обработку изображения.
    // Сохраняем в другой файл BMP.
    bmpImage.Save(dir + "sample.output.32bpp.bmp");
}
```

### Смотрите также

* class [BmpImage](../../bmpimage)
* пространство имен [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* сборка [Aspose.Imaging](../../../)

---

## BmpImage(string, ushort, BitmapCompression, double, double) {#constructor_8}

Инициализирует новый экземпляр[`BmpImage`](../../bmpimage) класс.

```csharp
public BmpImage(string path, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Путь для загрузки изображения и инициализации данных пикселей и палитры. |
| bitsPerPixel | UInt16 | Бит на пиксель. |
| compression | BitmapCompression | Используемое сжатие. |
| horizontalResolution | Double | Горизонтальное разрешение. Обратите внимание, что из-за округления результирующее разрешение может незначительно отличаться от переданного. |
| verticalResolution | Double | Вертикальное разрешение. Обратите внимание, что из-за округления результирующее разрешение может незначительно отличаться от переданного. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Растровое изображение не может быть нулевым; rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Высота должна быть положительной. |
| ArgumentException | Палитра должна быть указана для изображений с 8 битами на пиксель или меньше.;палитра |

### Примеры

В примере показано, как загрузить BmpImage из файла с указанной битовой глубиной и разрешением.

```csharp
[C#]

string dir = "c:\\temp\\";

// Загрузить изображение BMP из файла.
// При необходимости исходные пиксели будут преобразованы в 24-битный формат.
// Разрешение будет установлено на 96 dpi.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage =
    new Aspose.Imaging.FileFormats.Bmp.BmpImage(dir + "sample.bmp", 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
{
    // Выполнить некоторую обработку изображения.
    // Сохраняем в другой файл BMP.
    bmpImage.Save(dir + "sample.output.24bpp.96dpi.bmp");
}
```

### Смотрите также

* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* пространство имен [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* сборка [Aspose.Imaging](../../../)

---

## BmpImage(Stream) {#constructor_5}

Инициализирует новый экземпляр[`BmpImage`](../../bmpimage) класс.

```csharp
public BmpImage(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток для загрузки изображения и инициализации данных пикселей и палитры. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Растровое изображение не может быть нулевым; rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Высота должна быть положительной. |
| ArgumentException | Палитра должна быть указана для изображений с 8 битами на пиксель или меньше.;палитра |

### Примеры

В примере показано, как загрузить BmpImage из файлового потока.

```csharp
[C#]

string dir = "c:\\temp\\";

// Загружаем BMP-изображение из файлового потока.
// При необходимости исходные пиксели будут преобразованы в 32-битный формат.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(stream))
    {
        // Выполнить некоторую обработку изображения.
        // Сохраняем в другой файл BMP.
        bmpImage.Save(dir + "sample.output.32bpp.bmp");
    }
}
```

### Смотрите также

* class [BmpImage](../../bmpimage)
* пространство имен [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* сборка [Aspose.Imaging](../../../)

---

## BmpImage(Stream, ushort, BitmapCompression, double, double) {#constructor_6}

Инициализирует новый экземпляр[`BmpImage`](../../bmpimage) класс.

```csharp
public BmpImage(Stream stream, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток для загрузки изображения и инициализации данных пикселей и палитры. |
| bitsPerPixel | UInt16 | Бит на пиксель. |
| compression | BitmapCompression | Используемое сжатие. |
| horizontalResolution | Double | Горизонтальное разрешение. Обратите внимание, что из-за округления результирующее разрешение может незначительно отличаться от переданного. |
| verticalResolution | Double | Вертикальное разрешение. Обратите внимание, что из-за округления результирующее разрешение может незначительно отличаться от переданного. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Растровое изображение не может быть нулевым; rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Высота должна быть положительной. |
| ArgumentException | Палитра должна быть указана для изображений с 8 битами на пиксель или меньше.;палитра |

### Примеры

В примере показано, как загрузить BmpImage из файлового потока с указанной глубиной цвета и разрешением.

```csharp
[C#]

string dir = "c:\\temp\\";

// Загружаем BMP-изображение из файлового потока.
// При необходимости исходные пиксели будут преобразованы в 24-битный формат.
// Разрешение будет установлено на 96 dpi.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage =
        new Aspose.Imaging.FileFormats.Bmp.BmpImage(stream, 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
    {
        // Выполнить некоторую обработку изображения.
        // Сохраняем в другой файл BMP.
        bmpImage.Save(dir + "sample.output.24bpp.96dpi.bmp");
    }
}
```

### Смотрите также

* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* пространство имен [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* сборка [Aspose.Imaging](../../../)

---

## BmpImage(RasterImage) {#constructor}

Инициализирует новый экземпляр[`BmpImage`](../../bmpimage) класс.

```csharp
public BmpImage(RasterImage rasterImage)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rasterImage | RasterImage | Изображение для инициализации данных пикселей и палитры. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Растровое изображение не может быть нулевым; rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Высота должна быть положительной. |
| ArgumentException | Палитра должна быть указана для изображений с 8 битами на пиксель или меньше.;палитра |

### Примеры

В примере показано, как загрузить BmpImage из другого экземпляра RasterImage.

```csharp
[C#]

string dir = "c:\\temp\\";

// Создаем новое изображение PNG.
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // Заливаем все PNG-изображение красным цветом.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, rasterImage.Bounds);

    // Создаем изображение BMP на основе изображения PNG.
    // При необходимости исходные пиксели будут преобразованы в 32-битный формат.
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(rasterImage))
    {
        // Сохраняем в BMP файл
        bmpImage.Save(dir + "output.32bpp.bmp");
    }
}
```

### Смотрите также

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [BmpImage](../../bmpimage)
* пространство имен [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* сборка [Aspose.Imaging](../../../)

---

## BmpImage(RasterImage, ushort, BitmapCompression, double, double) {#constructor_1}

Инициализирует новый экземпляр[`BmpImage`](../../bmpimage) класс.

```csharp
public BmpImage(RasterImage rasterImage, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rasterImage | RasterImage | Изображение для инициализации данных пикселей и палитры. |
| bitsPerPixel | UInt16 | Бит на пиксель. |
| compression | BitmapCompression | Используемое сжатие. |
| horizontalResolution | Double | Горизонтальное разрешение. Обратите внимание, что из-за округления результирующее разрешение может незначительно отличаться от переданного. |
| verticalResolution | Double | Вертикальное разрешение. Обратите внимание, что из-за округления результирующее разрешение может незначительно отличаться от переданного. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Растровое изображение не может быть нулевым; rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Высота должна быть положительной. |
| ArgumentException | Палитра должна быть указана для изображений с 8 битами на пиксель или меньше.;палитра |

### Примеры

В примере показано, как загрузить BmpImage из другого экземпляра RasterImage с указанной глубиной цвета и сжатием.

```csharp
[C#]

string dir = "c:\\temp\\";

// Создаем новое изображение PNG.
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // Заливаем все PNG-изображение красным цветом.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, rasterImage.Bounds);

    // Создаем изображение BMP на основе изображения PNG.
    // При необходимости исходные пиксели будут преобразованы в 24-битный формат.
    // Разрешение будет установлено на 96 dpi.
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(rasterImage, 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
    {
        // Сохраняем в BMP файл
        bmpImage.Save(dir + "output.24bpp.96dpi.bmp");
    }
}
```

### Смотрите также

* class [RasterImage](../../../aspose.imaging/rasterimage)
* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* пространство имен [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* сборка [Aspose.Imaging](../../../)

---

## BmpImage(int, int) {#constructor_2}

Инициализирует новый экземпляр[`BmpImage`](../../bmpimage) класс.

```csharp
public BmpImage(int width, int height)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | Int32 | Ширина изображения. |
| height | Int32 | Высота изображения. |

### Исключения

| исключение | условие |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Высота должна быть положительной. |
| ArgumentException | Палитра должна быть указана для изображений с 8 битами на пиксель или меньше.;палитра |

### Примеры

В примере показано, как создать BmpImage указанного размера.

```csharp
[C#]

string dir = "c:\\temp\\";

// Создаем BMP-изображение 32 бита на пиксель размером 100 x 100 пикселей.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Заливаем все изображение красным.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // Сохраняем в BMP файл
    bmpImage.Save(dir + "output.bmp");
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

* class [BmpImage](../../bmpimage)
* пространство имен [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* сборка [Aspose.Imaging](../../../)

---

## BmpImage(int, int, ushort, IColorPalette) {#constructor_3}

Инициализирует новый экземпляр[`BmpImage`](../../bmpimage) класс.

```csharp
public BmpImage(int width, int height, ushort bitsPerPixel, IColorPalette palette)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | Int32 | Ширина изображения. |
| height | Int32 | Высота изображения. |
| bitsPerPixel | UInt16 | Бит на пиксель. |
| palette | IColorPalette | Цветовая палитра. |

### Исключения

| исключение | условие |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Высота должна быть положительной. |
| ArgumentException | Палитра должна быть указана для изображений с 8 битами на пиксель или меньше.;палитра |

### Примеры

В примере показано, как создать BmpImage указанного размера с указанной палитрой.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.Color[] paletterColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
};

// Создаем монохромную палитру, содержащую только красный и зеленый цвета.
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

// Создаем монохромное BMP-изображение 1 бит на пиксель размером 100 x 100 пикселей.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 1, palette))
{
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

    // Заливаем верхнюю половину изображения красным цветом.
    Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(redBrush, new Aspose.Imaging.Rectangle(0, 0, bmpImage.Width, bmpImage.Height / 2));

    // Заливаем нижнюю половину изображения зеленым цветом.
    Aspose.Imaging.Brushes.SolidBrush greenBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Green);
    gr.FillRectangle(greenBrush, new Aspose.Imaging.Rectangle(0, bmpImage.Height / 2, bmpImage.Width, bmpImage.Height / 2));

    // Сохраняем в BMP
    bmpImage.Save(dir + "output.monochrome.bmp");
}
```

### Смотрите также

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [BmpImage](../../bmpimage)
* пространство имен [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* сборка [Aspose.Imaging](../../../)

---

## BmpImage(int, int, ushort, IColorPalette, BitmapCompression, double, double) {#constructor_4}

Инициализирует новый экземпляр[`BmpImage`](../../bmpimage) класс.

```csharp
public BmpImage(int width, int height, ushort bitsPerPixel, IColorPalette palette, 
    BitmapCompression compression, double horizontalResolution, double verticalResolution)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | Int32 | Ширина изображения. |
| height | Int32 | Высота изображения. |
| bitsPerPixel | UInt16 | Бит на пиксель. |
| palette | IColorPalette | Цветовая палитра. |
| compression | BitmapCompression | Используемое сжатие. |
| horizontalResolution | Double | Горизонтальное разрешение. Обратите внимание, что из-за округления результирующее разрешение может незначительно отличаться от переданного. |
| verticalResolution | Double | Вертикальное разрешение. Обратите внимание, что из-за округления результирующее разрешение может незначительно отличаться от переданного. |

### Исключения

| исключение | условие |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Высота должна быть положительной. |
| ArgumentException | Палитра должна быть указана для изображений с 8 битами на пиксель или меньше.;палитра |

### Примеры

В примере показано, как создать BmpImage, используя различные параметры.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.Color[] paletterColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
};

// Создаем монохромную палитру, содержащую только красный и зеленый цвета.
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

// Создаем монохромное BMP-изображение 1 бит на пиксель размером 100 x 100 пикселей.
// Горизонтальное и вертикальное разрешение будет установлено на 96 dpi.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 1, palette, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
{
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

    // Заливаем верхнюю половину изображения красным цветом.
    Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(redBrush, new Aspose.Imaging.Rectangle(0, 0, bmpImage.Width, bmpImage.Height / 2));

    // Заливаем нижнюю половину изображения зеленым цветом.
    Aspose.Imaging.Brushes.SolidBrush greenBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Green);
    gr.FillRectangle(greenBrush, new Aspose.Imaging.Rectangle(0, bmpImage.Height / 2, bmpImage.Width, bmpImage.Height / 2));

    // Сохраняем в BMP файл
    bmpImage.Save(dir + "output.monochrome.96dpi.bmp");
}
```

### Смотрите также

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* пространство имен [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
