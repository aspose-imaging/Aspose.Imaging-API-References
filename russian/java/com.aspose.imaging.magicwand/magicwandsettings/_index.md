---
title: "MagicWandSettings"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Класс настроек выбора magic wand."
type: docs
weight: 13
url: /ru/java/com.aspose.imaging.magicwand/magicwandsettings/
---
**Inheritance:**
java.lang.Object
```
public class MagicWandSettings
```

Класс настроек выбора magic wand.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MagicWandSettings(Point point)](#MagicWandSettings-com.aspose.imaging.Point-) | Инициализирует новый экземпляр класса [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings). |
| [MagicWandSettings(int x, int y)](#MagicWandSettings-int-int-) | Инициализирует новый экземпляр класса [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings). |
## Методы

| Метод | Описание |
| --- | --- |
| [getAreaOfInterest()](#getAreaOfInterest--) | Получает границы области для работы алгоритма. |
| [setAreaOfInterest(Rectangle value)](#setAreaOfInterest-com.aspose.imaging.Rectangle-) | Устанавливает границы области для работы алгоритма. |
| [getPoint()](#getPoint--) | Получает опорную точку для работы алгоритма. |
| [getThreshold()](#getThreshold--) | Получает уровень допуска для сравнения цветов пикселей. |
| [setThreshold(int value)](#setThreshold-int-) | Устанавливает уровень допуска для сравнения цветов пикселей. |
| [getContiguousMode()](#getContiguousMode--) | Получает значение, указывающее, будет ли magic wand определять только смежные пиксели. |
| [setContiguousMode(boolean value)](#setContiguousMode-boolean-) | Устанавливает значение, указывающее, будет ли волшебная палочка определять только смежные пиксели. |
| [getDirectionalMode()](#getDirectionalMode--) | Получает режим алгоритма поиска заливки: поиск в четырёх из восьми направлений. |
| [setDirectionalMode(int value)](#setDirectionalMode-int-) | Устанавливает режим алгоритма поиска заливки: поиск в четырёх из восьми направлений. |
| [getColorCompareMode()](#getColorCompareMode--) | Получает алгоритм сравнения цветов. |
| [setColorCompareMode(int value)](#setColorCompareMode-int-) | Устанавливает алгоритм сравнения цветов. |
| [getColorComparisonDelegate()](#getColorComparisonDelegate--) | Получает пользовательский алгоритм сравнения цветов, если `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) установлен в [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom). |
| [setColorComparisonDelegate(MagicWandSettings.ColorComparison value)](#setColorComparisonDelegate-com.aspose.imaging.magicwand.MagicWandSettings.ColorComparison-) | Устанавливает пользовательский алгоритм сравнения цветов, если `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) установлен в [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom). |

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

### MagicWandSettings(Point point) {#MagicWandSettings-com.aspose.imaging.Point-}
```
public MagicWandSettings(Point point)
```


Инициализирует новый экземпляр класса [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Опорная точка. |

### MagicWandSettings(int x, int y) {#MagicWandSettings-int-int-}
```
public MagicWandSettings(int x, int y)
```


Инициализирует новый экземпляр класса [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата X опорной точки. |
| y | int | Координата Y опорной точки. |

### getAreaOfInterest() {#getAreaOfInterest--}
```
public final Rectangle getAreaOfInterest()
```


Получает границы области для работы алгоритма.

Значение: Прямоугольник, представляющий границы области интереса.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the area for algorithm work.
### setAreaOfInterest(Rectangle value) {#setAreaOfInterest-com.aspose.imaging.Rectangle-}
```
public final void setAreaOfInterest(Rectangle value)
```


Устанавливает границы области для работы алгоритма.

Значение: Прямоугольник, представляющий границы области интереса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) | границы области для работы алгоритма. |

### getPoint() {#getPoint--}
```
public final Point getPoint()
```


Получает опорную точку для работы алгоритма.

Значение: Значение `Point`.

**Returns:**
[Point](../../com.aspose.imaging/point) - the reference point for algorithm work.
### getThreshold() {#getThreshold--}
```
public final int getThreshold()
```


Получает уровень допуска для сравнения цветов пикселей.

Значение: Порог сравнения цветов.

**Returns:**
int - уровень допуска для сравнения цвета пикселей.
### setThreshold(int value) {#setThreshold-int-}
```
public final void setThreshold(int value)
```


Устанавливает уровень допуска для сравнения цветов пикселей.

Значение: Порог сравнения цветов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | уровень допуска для сравнения цвета пикселей. |

### getContiguousMode() {#getContiguousMode--}
```
public final boolean getContiguousMode()
```


Получает значение, указывающее, будет ли magic wand определять только смежные пиксели.

Значение: `true`, если элемент включён; иначе `false`. Значение по умолчанию - `true`.

**Returns:**
boolean - значение, указывающее, будет ли волшебная палочка определять только смежные пиксели.
### setContiguousMode(boolean value) {#setContiguousMode-boolean-}
```
public final void setContiguousMode(boolean value)
```


Устанавливает значение, указывающее, будет ли волшебная палочка определять только смежные пиксели.

Значение: `true`, если элемент включён; иначе `false`. Значение по умолчанию - `true`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | значение, указывающее, будет ли волшебная палочка определять только смежные пиксели. |

### getDirectionalMode() {#getDirectionalMode--}
```
public final int getDirectionalMode()
```


Получает режим алгоритма поиска заливки: поиск в четырёх из восьми направлений.

Значение: Режим алгоритма поиска заливки.

**Returns:**
int - режим алгоритма поиска заливки: поиск в четырёх из восьми направлений.
### setDirectionalMode(int value) {#setDirectionalMode-int-}
```
public final void setDirectionalMode(int value)
```


Устанавливает режим алгоритма поиска заливки: поиск в четырёх из восьми направлений.

Значение: Режим алгоритма поиска заливки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | режим алгоритма поиска заливки: поиск в четырёх из восьми направлений. |

### getColorCompareMode() {#getColorCompareMode--}
```
public final int getColorCompareMode()
```


Получает алгоритм сравнения цветов.

Значение: Режим сравнения цветов.

**Returns:**
int - алгоритм сравнения цветов.
### setColorCompareMode(int value) {#setColorCompareMode-int-}
```
public final void setColorCompareMode(int value)
```


Устанавливает алгоритм сравнения цветов.

Значение: Режим сравнения цветов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | алгоритм сравнения цветов. |

### getColorComparisonDelegate() {#getColorComparisonDelegate--}
```
public final MagicWandSettings.ColorComparison getColorComparisonDelegate()
```


Получает пользовательский алгоритм сравнения цветов, если `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) установлен в [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom).

Значение: Делегат сравнения цвета.

**Returns:**
[ColorComparison](../../com.aspose.imaging.magicwand/colorcomparison) - the custom color comparison algorithm if `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) is set to [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom).
### setColorComparisonDelegate(MagicWandSettings.ColorComparison value) {#setColorComparisonDelegate-com.aspose.imaging.magicwand.MagicWandSettings.ColorComparison-}
```
public final void setColorComparisonDelegate(MagicWandSettings.ColorComparison value)
```


Устанавливает пользовательский алгоритм сравнения цветов, если `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) установлен в [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom).

Значение: Делегат сравнения цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ColorComparison](../../com.aspose.imaging.magicwand/colorcomparison) | пользовательский алгоритм сравнения цветов, если `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) установлен в [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom). |

