---
title: "PaletteMiningMethod"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Метод извлечения палитры изображения"
type: docs
weight: 79
url: /ru/java/com.aspose.imaging/paletteminingmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PaletteMiningMethod extends System.Enum
```

Метод извлечения палитры изображения
## Поля

| Поле | Описание |
| --- | --- |
| [UseCurrentPalette](#UseCurrentPalette) | Использовать существующую палитру изображения. |
| [ColorClustering](#ColorClustering) | Метод кластеризации цветов. |
| [Histogram](#Histogram) | Метод гистограммы. |

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

### UseCurrentPalette {#UseCurrentPalette}
```
public static final int UseCurrentPalette
```


Использовать существующую палитру изображения.

### ColorClustering {#ColorClustering}
```
public static final int ColorClustering
```


Метод кластеризации цветов.

### Histogram {#Histogram}
```
public static final int Histogram
```


Метод гистограммы.

