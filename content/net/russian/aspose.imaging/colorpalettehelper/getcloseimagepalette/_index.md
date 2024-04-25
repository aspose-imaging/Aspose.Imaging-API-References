---
title: GetCloseImagePalette
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает цветовую палитру из растрового изображения палетизирует изображение если у изображения ее нет. Если палитра существует она будет использоваться вместо выполнения вычислений.
type: docs
weight: 60
url: /ru/aspose.imaging/colorpalettehelper/getcloseimagepalette/
---
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_3}

Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения ее нет. Если палитра существует, она будет использоваться вместо выполнения вычислений.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | RasterImage | Растровое изображение. |
| entriesCount | Int32 | Желаемые записи учитываются. |

### Возвращаемое значение

Цветовая палитра, которая начинается с наиболее часто встречающихся цветов из*image* и содержит*entriesCount* записи.

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
* class [RasterImage](../../rasterimage)
* class [ColorPaletteHelper](../../colorpalettehelper)
* пространство имен [Aspose.Imaging](../../colorpalettehelper)
* сборка [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, int, PaletteMiningMethod) {#getcloseimagepalette_4}

Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения его нет. Палитра будет оптимизирована для лучшего качества индексированного изображения или будет взята «КАК ЕСТЬ», когда используется PaletteMiningMethod.UseCurrentPalette.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount, 
    PaletteMiningMethod paletteMiningMethod)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | RasterImage | Растровое изображение. |
| entriesCount | Int32 | Желаемые записи учитываются. |
| paletteMiningMethod | PaletteMiningMethod | Метод добычи палитры. |

### Возвращаемое значение

Цветовая палитра, которая начинается с наиболее часто встречающихся цветов из*image* и содержит*entriesCount* записи.

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

### Смотрите также

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* enum [PaletteMiningMethod](../../paletteminingmethod)
* class [ColorPaletteHelper](../../colorpalettehelper)
* пространство имен [Aspose.Imaging](../../colorpalettehelper)
* сборка [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения ее нет. Если палитра существует, она будет использоваться вместо выполнения вычислений.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | RasterImage | Растровое изображение. |
| destBounds | Rectangle | Границы целевого изображения. |
| entriesCount | Int32 | Желаемые записи учитываются. |

### Возвращаемое значение

Цветовая палитра, которая начинается с наиболее часто встречающихся цветов из*image* и содержит*entriesCount* записи.

### Смотрите также

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* class [ColorPaletteHelper](../../colorpalettehelper)
* пространство имен [Aspose.Imaging](../../colorpalettehelper)
* сборка [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения ее нет. Если палитра существует, она будет использоваться вместо выполнения вычислений.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | RasterImage | Растровое изображение. |
| destBounds | Rectangle | Границы целевого изображения. |
| entriesCount | Int32 | Желаемые записи учитываются. |
| useImagePalette | Boolean | Если установлено, будет использоваться собственная палитра изображений, если она доступна. |

### Возвращаемое значение

Цветовая палитра, которая начинается с наиболее часто встречающихся цветов из*image* и содержит*entriesCount* записи.

### Смотрите также

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* class [ColorPaletteHelper](../../colorpalettehelper)
* пространство имен [Aspose.Imaging](../../colorpalettehelper)
* сборка [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool, Color) {#getcloseimagepalette_2}

Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения ее нет. Если палитра существует, она будет использоваться вместо выполнения вычислений.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette, Color alphaBlendInColor)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | RasterImage | Растровое изображение. |
| destBounds | Rectangle | Границы целевого изображения. |
| entriesCount | Int32 | Желаемые записи учитываются. |
| useImagePalette | Boolean | Если установлено, будет использоваться собственная палитра изображений, если она доступна. |
| alphaBlendInColor | Color | Цвет, который следует использовать в качестве цвета фона для полупрозрачной альфа-замены. |

### Возвращаемое значение

Цветовая палитра, которая начинается с наиболее часто встречающихся цветов из*image* и содержит*entriesCount* записи.

### Смотрите также

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* struct [Color](../../color)
* class [ColorPaletteHelper](../../colorpalettehelper)
* пространство имен [Aspose.Imaging](../../colorpalettehelper)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
