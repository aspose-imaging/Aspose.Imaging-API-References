---
title: "ColorPaletteHelper"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Вспомогательный класс для работы с палитрой цветов."
type: docs
weight: 29
url: /ru/java/com.aspose.imaging/colorpalettehelper/
---
**Inheritance:**
java.lang.Object
```
public final class ColorPaletteHelper
```

Вспомогательный класс для работы с палитрой цветов.
## Методы

| Метод | Описание |
| --- | --- |
| [createMonochrome()](#createMonochrome--) | Создаёт монохромную цветовую палитру, содержащую только 2 цвета. |
| [create4Bit()](#create4Bit--) | Создаёт 4‑битную цветовую палитру. |
| [create4BitGrayscale(boolean minIsWhite)](#create4BitGrayscale-boolean-) | Создаёт 4‑битную палитру оттенков серого. |
| [create8Bit()](#create8Bit--) | Создаёт 8‑битную цветовую палитру. |
| [create8BitGrayscale(boolean minIsWhite)](#create8BitGrayscale-boolean-) | Создаёт 8‑битную палитру оттенков серого. |
| [getCloseImagePalette(RasterImage image, int entriesCount)](#getCloseImagePalette-com.aspose.imaging.RasterImage-int-) | Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. |
| [getCloseTransparentImagePalette(RasterImage image, int entriesCount)](#getCloseTransparentImagePalette-com.aspose.imaging.RasterImage-int-) | Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. |
| [getCloseImagePalette(RasterImage image, int entriesCount, int paletteMiningMethod)](#getCloseImagePalette-com.aspose.imaging.RasterImage-int-int-) | Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-) | Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-) | Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-) | Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor, boolean keepTransparency)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-boolean-) | Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. |
| [getUniformColorPalette(RasterImage image)](#getUniformColorPalette-com.aspose.imaging.RasterImage-) | Получить однородную 256‑цветную палитру. |
| [getDownscalePalette(RasterImage image)](#getDownscalePalette-com.aspose.imaging.RasterImage-) | Получить 256‑цветную палитру, состоящую из старших битов исходных цветовых значений изображения. |
| [hasTransparentColors(IColorPalette palette)](#hasTransparentColors-com.aspose.imaging.IColorPalette-) | Определяет, содержит ли указанная палитра прозрачные цвета. |
| [createGrayscale(int bits)](#createGrayscale-int-) | Получает палитру оттенков серого заданного количества бит. |
### createMonochrome() {#createMonochrome--}
```
public static IColorPalette createMonochrome()
```


Создаёт монохромную цветовую палитру, содержащую только 2 цвета.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - Color palette for monochrome images.
### create4Bit() {#create4Bit--}
```
public static IColorPalette create4Bit()
```


Создаёт 4‑битную цветовую палитру.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 4 bit color palette.
### create4BitGrayscale(boolean minIsWhite) {#create4BitGrayscale-boolean-}
```
public static IColorPalette create4BitGrayscale(boolean minIsWhite)
```


Создаёт 4‑битную палитру оттенков серого.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| minIsWhite | boolean | если установить в `true`, палитра начинается с белого цвета, иначе — с чёрного цвета. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 4 bit grayscale palette.
### create8Bit() {#create8Bit--}
```
public static IColorPalette create8Bit()
```


Создаёт 8‑битную цветовую палитру.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 8bit color palette.
### create8BitGrayscale(boolean minIsWhite) {#create8BitGrayscale-boolean-}
```
public static IColorPalette create8BitGrayscale(boolean minIsWhite)
```


Создаёт 8‑битную палитру оттенков серого.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| minIsWhite | boolean | если установить в `true`, палитра начинается с белого цвета, иначе — с чёрного цвета. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 8 bit grayscale palette.

**Example: The following example creates a palettized grayscale BMP image and then saves it to a file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.BmpOptions createOptions = new com.aspose.imaging.imageoptions.BmpOptions();

// Сохранить в файл
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "output.palette8bit.bmp", false));

// Используйте 8 бит на пиксель, чтобы уменьшить размер выходного изображения.
createOptions.setBitsPerPixel(8);

// Установите стандартную 8‑битную палитру оттенков серого, охватывающую все оттенки серого.
// Если обработанное изображение содержит только оттенки серого, то его палетизированная версия
// визуально неотличима от непалетизированной.
createOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

// Сохранить без сжатия.
// Вы также можете использовать сжатие RLE-8, чтобы уменьшить размер выходного изображения.
createOptions.setCompression(com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb);

// Установите горизонтальное и вертикальное разрешение в 96 dpi.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

// Создайте BMP‑изображение размером 100 × 100 px и сохраните его в файл.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlack(),
            com.aspose.imaging.Color.getWhite());

    // Заполните изображение градиентом оттенков серого
    graphics.fillRectangle(gradientBrush, image.getBounds());

    image.save();
} finally {
    image.dispose();
}
```

### getCloseImagePalette(RasterImage image, int entriesCount) {#getCloseImagePalette-com.aspose.imaging.RasterImage-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, int entriesCount)
```


Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения расчётов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Растровое изображение. |
| entriesCount | int | Желаемое количество записей. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.

**Example: The following example shows how to palletize a BMP image to reduce its output size.**

``` java

// Создать BMP‑изображение размером 100 × 100 пикселей.
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Линейный градиент от левого верхнего до правого нижнего угла изображения.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Заполнить всё изображение кистью линейного градиента.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(bmpImage);
    gr.fillRectangle(brush, bmpImage.getBounds());

    // Получить ближайшую 8‑битную палитру цветов, покрывающую как можно больше пикселей, так чтобы палитровое изображение
    // было почти визуально неотличимо от непалитрового.
    com.aspose.imaging.IColorPalette palette = com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(bmpImage, 256);

    // 8‑битная палитра содержит не более 256 цветов.
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();
    saveOptions.setPalette(palette);
    saveOptions.setBitsPerPixel(8);

    java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
    try {
        bmpImage.save(stream, saveOptions);
        System.out.println("The palettized image size is " + stream.size() + " bytes.");
    } finally {
        stream.close();
    }

    stream = new java.io.ByteArrayOutputStream();
    try {
        bmpImage.save(stream);
        System.out.println("The non-palettized image size is " + stream.size() + " bytes.");
    } finally {
        stream.close();
    }
} finally {
    bmpImage.dispose();
}

// Вывод выглядит так:
// Размер палетизированного изображения составляет 11078 байт.
// Размер непалетизированного изображения составляет 40054 байт.
```

### getCloseTransparentImagePalette(RasterImage image, int entriesCount) {#getCloseTransparentImagePalette-com.aspose.imaging.RasterImage-int-}
```
public static IColorPalette getCloseTransparentImagePalette(RasterImage image, int entriesCount)
```


Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения расчётов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Растровое изображение. |
| entriesCount | int | Желаемое количество записей. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, int entriesCount, int paletteMiningMethod) {#getCloseImagePalette-com.aspose.imaging.RasterImage-int-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, int entriesCount, int paletteMiningMethod)
```


Получает цветовую палитру из растрового изображения (создаёт палитру изображения), если у изображения её нет. Палитра будет оптимизирована для лучшего качества индексированного изображения или взята "AS IS", когда используется PaletteMiningMethod.UseCurrentPalette.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Растровое изображение. |
| entriesCount | int | Желаемое количество записей. |
| paletteMiningMethod | int | Метод добычи палитры. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.

**Example: The following example shows how to compress a PNG image, using indexed color with best fit palette**

``` java

// Загружает PNG‑изображение        
String sourceFilePath = "OriginalRings.png";
String outputFilePath = "OriginalRingsOutput.png";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(sourceFilePath))
{
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    options.setProgressive(true);
    // Использовать индексированный тип цвета
    options.setColorType(com.aspose.imaging.fileformats.png.PngColorType.IndexedColor);
    // Использовать максимальное сжатие
    options.setCompressionLevel(9);
    // Получить ближайшую 8‑битную палитру цветов, покрывающую как можно больше пикселей, так чтобы палитровое изображение
    // было почти визуально неотличимо от непалитрового.
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// Размер выходного файла должен быть значительно уменьшен
```

### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)
```


Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения расчётов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Растровое изображение. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | Границы целевого изображения. |
| entriesCount | int | Желаемое количество записей. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)
```


Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения расчётов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Растровое изображение. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | Границы целевого изображения. |
| entriesCount | int | Желаемое количество записей. |
| useImagePalette | boolean | Если установлено, будет использовать собственную палитру изображения, если она доступна |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor)
```


Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения расчётов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Растровое изображение. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | Границы целевого изображения. |
| entriesCount | int | Желаемое количество записей. |
| useImagePalette | boolean | Если установлено, будет использовать собственную палитру изображения, если она доступна |
| alphaBlendInColor | [Color](../../com.aspose.imaging/color) | Цвет, который следует использовать в качестве фонового цвета для полупрозрачной замены альфа‑канала. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor, boolean keepTransparency) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor, boolean keepTransparency)
```


Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения расчётов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Растровое изображение. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | Границы целевого изображения. |
| entriesCount | int | Желаемое количество записей. |
| useImagePalette | boolean | Если установлено, будет использовать собственную палитру изображения, если она доступна |
| alphaBlendInColor | [Color](../../com.aspose.imaging/color) | Цвет, который следует использовать в качестве фонового цвета для полупрозрачной замены альфа‑канала. |
| keepTransparency | boolean | Если установлено, будут учитываться биты альфа‑канала цветов изображения. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getUniformColorPalette(RasterImage image) {#getUniformColorPalette-com.aspose.imaging.RasterImage-}
```
public static ColorPalette getUniformColorPalette(RasterImage image)
```


Получить однородную 256‑цветную палитру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Изображение. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The `ColorPalette`.
### getDownscalePalette(RasterImage image) {#getDownscalePalette-com.aspose.imaging.RasterImage-}
```
public static ColorPalette getDownscalePalette(RasterImage image)
```


Получить 256‑цветную палитру, состоящую из старших битов исходных цветовых значений изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Изображение. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The `ColorPalette`.
### hasTransparentColors(IColorPalette palette) {#hasTransparentColors-com.aspose.imaging.IColorPalette-}
```
public static boolean hasTransparentColors(IColorPalette palette)
```


Определяет, содержит ли указанная палитра прозрачные цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Палитра. |

**Returns:**
логический тип - `true`, если указанная палитра содержит прозрачные цвета; в противном случае `false`.
### createGrayscale(int bits) {#createGrayscale-int-}
```
public static IColorPalette createGrayscale(int bits)
```


Получает градационную палитру указанного количества бит. Допустимые значения бит: 1, 2, 4, 8.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bits | int | Количество бит. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - Grayscale palette.
