---
title: "MagicWandTool"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Класс, содержащий основную логику алгоритма magic wand."
type: docs
weight: 14
url: /ru/java/com.aspose.imaging.magicwand/magicwandtool/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader)
```
public class MagicWandTool implements IPartialArgb32PixelLoader
```

Класс, содержащий основную логику алгоритма magic wand.
## Методы

| Метод | Описание |
| --- | --- |
| [select(RasterImage source, MagicWandSettings settings)](#select-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Создает новый [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) на основе [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) и исходного [RasterImage](../../com.aspose.imaging/rasterimage). |
| [process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#process-com.aspose.imaging.Rectangle-int---com.aspose.imaging.Point-com.aspose.imaging.Point-) | Обрабатывает загруженные пиксели. |

## Example: The example shows how to select a simple area of an image based on tone and color of any pixel using Magic Wand tool.

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // Создайте новую маску с помощью инструмента magic wand, основанную на тоне и цвете пикселя (120, 100) с пользовательским порогом, равным 150.
    MagicWandTool
            .select(image, new MagicWandSettings(120, 100) {{ setThreshold(150); }})
            // Примените маску к изображению
            .apply();

    // Сохраните изображение с принудительным параметром типа прозрачного цвета
    image.save(outputFilePath, new PngOptions()
    {{
        setColorType(PngColorType.TruecolorWithAlpha);
    }});
}

```


## Example: The example shows how to select a complicated area of an image using Magic Wand tool and the ability to interact with masks (invert, union, subtract).

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked-complex.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // Создайте новую маску с помощью инструмента magic wand, основанную на тоне и цвете пикселя (845, 128).
    MagicWandTool.select(image, new MagicWandSettings(845, 128))
            // Объедините существующую маску с указанной, созданной инструментом magic wand.
            .union(new MagicWandSettings(416, 387))
            // Инвертируйте существующую маску
            .invert()
            // Вычтите указанную маску, созданную инструментом magic wand с заданным порогом, из существующей.
            .subtract(new MagicWandSettings(1482, 346) {{ setThreshold(69); }})
            // Вычтите четыре указанных прямоугольных маски из существующей маски одну за другой.
            .subtract(new RectangleMask(0, 0, 800, 150))
            .subtract(new RectangleMask(0, 380, 600, 220))
            .subtract(new RectangleMask(930, 520, 110, 40))
            .subtract(new RectangleMask(1370, 400, 120, 200))
            // Смягчите маску с указанными настройками.
            .getFeathered(new FeatheringSettings() {{ setSize(3); }})
            // Примените маску к изображению
            .apply();

    // Сохранить изображение
    image.save(outputFilePath);
}

```

### select(RasterImage source, MagicWandSettings settings) {#select-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public static ImageBitMask select(RasterImage source, MagicWandSettings settings)
```


Создает новый [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) на основе [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) и исходного [RasterImage](../../com.aspose.imaging/rasterimage).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) | Растровое изображение, над которым работает алгоритм. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Настройки алгоритма magic wand, используемые при создании маски. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#process-com.aspose.imaging.Rectangle-int---com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public final void process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


Обрабатывает загруженные пиксели.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник пикселей. |
| пиксели | int[] | 32-битные пиксели ARGB. |
| start | [Point](../../com.aspose.imaging/point) | Точка начала пикселей. Если она не равна (left,top), это означает, что у нас не полный прямоугольник. |
| end | [Point](../../com.aspose.imaging/point) | Точка конца пикселей. Если она не равна (right,bottom), это означает, что у нас не полный прямоугольник. |

