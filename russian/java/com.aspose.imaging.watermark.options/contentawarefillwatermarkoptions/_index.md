---
title: "ContentAwareFillWatermarkOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Общие параметры алгоритма Content Aware Fill."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.watermark.options.WatermarkOptions](../../com.aspose.imaging.watermark.options/watermarkoptions)
```
public class ContentAwareFillWatermarkOptions extends WatermarkOptions
```

Общие параметры алгоритма Content Aware Fill.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ContentAwareFillWatermarkOptions(Point[] mask)](#ContentAwareFillWatermarkOptions-com.aspose.imaging.Point---) | Инициализирует новый экземпляр класса [ContentAwareFillWatermarkOptions](../../com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions). |
| [ContentAwareFillWatermarkOptions(GraphicsPath mask)](#ContentAwareFillWatermarkOptions-com.aspose.imaging.GraphicsPath-) | Инициализирует новый экземпляр класса [ContentAwareFillWatermarkOptions](../../com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getPatchSize()](#getPatchSize--) | Получает размер патча (должен быть нечётным). |
| [setPatchSize(byte value)](#setPatchSize-byte-) | Устанавливает размер патча (должен быть нечётным). |
| [getMaxPaintingAttempts()](#getMaxPaintingAttempts--) | Получает максимальное количество попыток рисования. |
| [setMaxPaintingAttempts(int value)](#setMaxPaintingAttempts-int-) | Устанавливает максимальное количество попыток рисования. |
| [getInterestArea()](#getInterestArea--) | Получает область для взятия патчей. |
| [setInterestArea(Rectangle value)](#setInterestArea-com.aspose.imaging.Rectangle-) | Устанавливает область для взятия патчей. |

## Example: The example shows how to remove any object from the image using Graphics Path with Content Aware fill algorithm.

``` java
String imageFilePath = "ball.png"; 
try (Image image = Image.load(imageFilePath))
{
    PngImage pngImage = (PngImage)image;

    GraphicsPath mask = new GraphicsPath();
    Figure firstFigure = new Figure();
    firstFigure.addShape(new EllipseShape(new RectangleF(350, 170, 570 - 350, 400 - 170)));
    mask.addFigure(firstFigure);

    ContentAwareFillWatermarkOptions options = new ContentAwareFillWatermarkOptions(mask);
    options.setMaxPaintingAttempts(4);
    try (Image result = WatermarkRemover.paintOver(pngImage, options))
    {
        result.Save(outputPath);
    }
}
```

### ContentAwareFillWatermarkOptions(Point[] mask) {#ContentAwareFillWatermarkOptions-com.aspose.imaging.Point---}
```
public ContentAwareFillWatermarkOptions(Point[] mask)
```


Инициализирует новый экземпляр класса [ContentAwareFillWatermarkOptions](../../com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mask | [Point\[\]](../../com.aspose.imaging/point) | Маска для неизвестной области. |

### ContentAwareFillWatermarkOptions(GraphicsPath mask) {#ContentAwareFillWatermarkOptions-com.aspose.imaging.GraphicsPath-}
```
public ContentAwareFillWatermarkOptions(GraphicsPath mask)
```


Инициализирует новый экземпляр класса [ContentAwareFillWatermarkOptions](../../com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mask | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Маска для неизвестной области. |

### getPatchSize() {#getPatchSize--}
```
public final byte getPatchSize()
```


Получает размер патча (должен быть нечётным).

Значение: Размер патча.

**Returns:**
byte - размер патча (должен быть нечётным).
### setPatchSize(byte value) {#setPatchSize-byte-}
```
public final void setPatchSize(byte value)
```


Устанавливает размер патча (должен быть нечётным).

Значение: Размер патча.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte | размер патча (должен быть нечётным). |

### getMaxPaintingAttempts() {#getMaxPaintingAttempts--}
```
public final int getMaxPaintingAttempts()
```


Получает максимальное количество попыток рисования. Алгоритм выберет лучший вариант.

Значение: Максимальное количество попыток рисования.

**Returns:**
int - максимальное количество попыток рисования.

**Example: The example shows how to remove any object from the image using Graphics Path with Content Aware fill algorithm.**

``` java
String imageFilePath = "ball.png"; 
try (Image image = Image.load(imageFilePath))
{
    PngImage pngImage = (PngImage)image;

    GraphicsPath mask = new GraphicsPath();
    Figure firstFigure = new Figure();
    firstFigure.addShape(new EllipseShape(new RectangleF(350, 170, 570 - 350, 400 - 170)));
    mask.addFigure(firstFigure);

    ContentAwareFillWatermarkOptions options = new ContentAwareFillWatermarkOptions(mask);
    options.setMaxPaintingAttempts(4);
    try (Image result = WatermarkRemover.paintOver(pngImage, options))
    {
        result.Save(outputPath);
    }
}
```

### setMaxPaintingAttempts(int value) {#setMaxPaintingAttempts-int-}
```
public final void setMaxPaintingAttempts(int value)
```


Устанавливает максимальное количество попыток рисования. Алгоритм выберет лучший вариант.

Значение: Максимальное количество попыток рисования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | максимальное количество попыток рисования. |


**Example: The example shows how to remove any object from the image using Graphics Path with Content Aware fill algorithm.**

``` java
String imageFilePath = "ball.png"; 
try (Image image = Image.load(imageFilePath))
{
    PngImage pngImage = (PngImage)image;

    GraphicsPath mask = new GraphicsPath();
    Figure firstFigure = new Figure();
    firstFigure.addShape(new EllipseShape(new RectangleF(350, 170, 570 - 350, 400 - 170)));
    mask.addFigure(firstFigure);

    ContentAwareFillWatermarkOptions options = new ContentAwareFillWatermarkOptions(mask);
    options.setMaxPaintingAttempts(4);
    try (Image result = WatermarkRemover.paintOver(pngImage, options))
    {
        result.Save(outputPath);
    }
}
```

### getInterestArea() {#getInterestArea--}
```
public final Rectangle getInterestArea()
```


Получает область для взятия патчей.

Значение: Область интереса для взятия патчей.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the area to take patches.
### setInterestArea(Rectangle value) {#setInterestArea-com.aspose.imaging.Rectangle-}
```
public final void setInterestArea(Rectangle value)
```


Устанавливает область для взятия патчей.

Значение: Область интереса для взятия патчей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) | область для взятия патчей. |

