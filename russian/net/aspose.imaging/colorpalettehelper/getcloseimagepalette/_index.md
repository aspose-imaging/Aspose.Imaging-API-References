---
title: GetCloseImagePalette
second_title: Справочник по Aspose.Imaging for .NET API
description: Получает цветовую палитру из растрового изображения палетизирует изображение если у изображения его нет. Если палитра существует она будет использоваться вместо выполнения вычислений.
type: docs
weight: 60
url: /ru/net/aspose.imaging/colorpalettehelper/getcloseimagepalette/
---
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_3}

Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения его нет. Если палитра существует, она будет использоваться вместо выполнения вычислений.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | RasterImage | Растровое изображение. |
| entriesCount | Int32 | Количество требуемых записей. |

### Возвращаемое значение

Цветовая палитра, которая начинается с наиболее часто встречающихся цветов из*изображения*и содержит*entriesCount*записей.

### Примеры

В следующем примере загружается изображение BMP и сохраняется обратно в BMP с использованием различных параметров сохранения.

```csharp
[C#]

 // Создаем изображение BMP 100 x 100 px.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
     // Линейный градиент от левого верхнего до правого нижнего угла изображения.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(bmpImage.Width, bmpImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

     // Заливаем всё изображение кистью линейного градиента.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    gr.FillRectangle(brush, bmpImage.Bounds);

     // Получить ближайшую 8-битную цветовую палитру, покрывающую максимально возможное количество пикселей, чтобы палитра image
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

 // Вывод выглядит следующим образом: 
 // Размер палетированного изображения 11078 байт.
// Размер изображения без палитры составляет 40054 байта.
```

В следующем примере показано, как разместить изображение BMP на поддонах, чтобы уменьшить его выходной размер.

```csharp
[C#]

 // Создаем изображение BMP 100 x 100 px.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
     // Линейный градиент от левого верхнего до правого нижнего угла изображения.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(bmpImage.Width, bmpImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

     // Заливаем всё изображение кистью линейного градиента.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    gr.FillRectangle(brush, bmpImage.Bounds);

     // Получить ближайшую 8-битную цветовую палитру, покрывающую максимально возможное количество пикселей, чтобы палитра image
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

 // Вывод выглядит следующим образом: 
 // Размер палетированного изображения 11078 байт.
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

Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения его нет. Палитра будет оптимизирована для лучшего качества индексированного изображения или будет взята «КАК ЕСТЬ» при использовании PaletteMiningMethod.UseCurrentPalette.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount, 
    PaletteMiningMethod paletteMiningMethod)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | RasterImage | Растровое изображение. |
| entriesCount | Int32 | Количество требуемых записей. |
| paletteMiningMethod | PaletteMiningMethod | Метод извлечения палитры. |

### Возвращаемое значение

Цветовая палитра, которая начинается с наиболее часто встречающихся цветов из*изображения*и содержит*entriesCount*записей.

### Примеры

В следующем примере показано, как сжать изображение PNG с использованием индексированного цвета с палитрой наилучшего соответствия

```csharp
[C#]

 // Загружает png изображение 
    string  sourceFilePath="OriginalRings.png";
    string  outputFilePath="OriginalRingsOutput.png";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new Aspose.Imaging.ImageOptions.PngOptions()
    {
         Progressive = true,
              // Использовать индексированный цвет type
         ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.IndexedColor,
              // Использовать максимальное сжатие
         CompressionLevel = 9,
       // Получить ближайшую 8-битную цветовую палитру, покрывающую максимально возможное количество пикселей, чтобы палитра image
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

Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения его нет. Если палитра существует, она будет использоваться вместо выполнения вычислений.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | RasterImage | Растровое изображение. |
| destBounds | Rectangle | Границы целевого изображения. |
| entriesCount | Int32 | Количество требуемых записей. |

### Возвращаемое значение

Цветовая палитра, которая начинается с наиболее часто встречающихся цветов из*изображения*и содержит*entriesCount*записей.

### Смотрите также

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* class [ColorPaletteHelper](../../colorpalettehelper)
* пространство имен [Aspose.Imaging](../../colorpalettehelper)
* сборка [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения его нет. Если палитра существует, она будет использоваться вместо выполнения вычислений.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | RasterImage | Растровое изображение. |
| destBounds | Rectangle | Границы целевого изображения. |
| entriesCount | Int32 | Количество требуемых записей. |
| useImagePalette | Boolean | Если установлено, будет использоваться собственная палитра изображений, если она доступна |

### Возвращаемое значение

Цветовая палитра, которая начинается с наиболее часто встречающихся цветов из*image*и содержит элементы*entriesCount*.

### Смотрите также

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* class [ColorPaletteHelper](../../colorpalettehelper)
* пространство имен [Aspose.Imaging](../../colorpalettehelper)
* сборка [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool, Color) {#getcloseimagepalette_2}

Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения его нет. Если палитра существует, она будет использоваться вместо выполнения вычислений.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette, Color alphaBlendInColor)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | RasterImage | Растровое изображение. |
| destBounds | Rectangle | Границы целевого изображения. |
| entriesCount | Int32 | Количество требуемых записей. |
| useImagePalette | Boolean | Если установлено, будет использоваться собственная палитра изображений, если она доступна |
| alphaBlendInColor | Color | Цвет который следует использовать в качестве цвета фона для полупрозрачной альфа-замены. |

### Возвращаемое значение

Цветовая палитра, которая начинается с наиболее часто встречающихся цветов из*изображения*и содержит*entriesCount*записей.

### Смотрите также

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* struct [Color](../../color)
* class [ColorPaletteHelper](../../colorpalettehelper)
* пространство имен [Aspose.Imaging](../../colorpalettehelper)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
