---
title: "PngColorType"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет тип цвета PNG‑изображения."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.fileformats.png/pngcolortype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PngColorType extends System.Enum
```

Представляет тип цвета PNG‑изображения.
## Поля

| Поле | Описание |
| --- | --- |
| [Grayscale](#Grayscale) | Представляет тип цвета, где каждый пиксель является образцом оттенка серого. |
| [Truecolor](#Truecolor) | Представляет тип цвета, где каждый пиксель представляет собой тройку R,G,B. |
| [IndexedColor](#IndexedColor) | Представляет тип цвета, где каждый пиксель является индексом палитры; должен присутствовать блок PLTE. |
| [GrayscaleWithAlpha](#GrayscaleWithAlpha) | Представляет тип цвета, где каждый пиксель — образец оттенка серого, за которым следует альфа‑образец. |
| [TruecolorWithAlpha](#TruecolorWithAlpha) | Представляет тип цвета, где каждый пиксель — тройка R,G,B, за которой следует альфа‑образец. |

## Example: The following example shows how to compress a PNG image, using indexed color with best fit palette

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

### Grayscale {#Grayscale}
```
public static final int Grayscale
```


Представляет тип цвета, где каждый пиксель является образцом оттенка серого.

### Truecolor {#Truecolor}
```
public static final int Truecolor
```


Представляет тип цвета, где каждый пиксель представляет собой тройку R,G,B.

### IndexedColor {#IndexedColor}
```
public static final int IndexedColor
```


Представляет тип цвета, где каждый пиксель является индексом палитры; должен присутствовать блок PLTE.

### GrayscaleWithAlpha {#GrayscaleWithAlpha}
```
public static final int GrayscaleWithAlpha
```


Представляет тип цвета, где каждый пиксель — образец оттенка серого, за которым следует альфа‑образец.

### TruecolorWithAlpha {#TruecolorWithAlpha}
```
public static final int TruecolorWithAlpha
```


Представляет тип цвета, где каждый пиксель — тройка R,G,B, за которой следует альфа‑образец.

