---
title: Create8BitGrayscale
second_title: Справочник по Aspose.Imaging for .NET API
description: Создает 8-битную палитру оттенков серого.
type: docs
weight: 40
url: /ru/net/aspose.imaging/colorpalettehelper/create8bitgrayscale/
---
## ColorPaletteHelper.Create8BitGrayscale method

Создает 8-битную палитру оттенков серого.

```csharp
public static IColorPalette Create8BitGrayscale(bool minIsWhite)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| minIsWhite | Boolean | если установлено`истинный` палитра начинается с белого цвета, в противном случае она начинается с черного цвета. |

### Возвращаемое значение

8-битная палитра оттенков серого.

### Примеры

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

### Смотрите также

* interface [IColorPalette](../../icolorpalette)
* class [ColorPaletteHelper](../../colorpalettehelper)
* пространство имен [Aspose.Imaging](../../colorpalettehelper)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
