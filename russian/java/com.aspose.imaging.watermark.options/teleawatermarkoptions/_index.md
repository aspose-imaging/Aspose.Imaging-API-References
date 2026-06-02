---
title: "TeleaWatermarkOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Общие параметры алгоритма Telea."
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.watermark.options/teleawatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.watermark.options.WatermarkOptions](../../com.aspose.imaging.watermark.options/watermarkoptions)
```
public class TeleaWatermarkOptions extends WatermarkOptions
```

Общие параметры алгоритма Telea.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TeleaWatermarkOptions(Point[] mask)](#TeleaWatermarkOptions-com.aspose.imaging.Point---) | Инициализирует новый экземпляр класса [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions). |
| [TeleaWatermarkOptions(GraphicsPath mask)](#TeleaWatermarkOptions-com.aspose.imaging.GraphicsPath-) | Инициализирует новый экземпляр класса [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getHalfPatchSize()](#getHalfPatchSize--) | Получает половину размера патча. |
| [setHalfPatchSize(int value)](#setHalfPatchSize-int-) | Устанавливает половину размера патча. |

## Example: The example shows how to remove any object from the image using Graphics Path with Telea algorithm.

``` java
String imageFilePath = "ball.png";
String outputPath = "no-watermark.png";
try (Image image = Image.load(imageFilePath))
{
    PngImage pngImage = (PngImage) image;
    GraphicsPath mask = new GraphicsPath();
    Figure firstFigure = new Figure();
    firstFigure.addShape(new EllipseShape(new RectangleF(350, 170, 570 - 350, 400 - 170)));
    mask.addFigure(firstFigure);

    TeleaWatermarkOptions options = new TeleaWatermarkOptions(mask);

    try (RasterImage result = WatermarkRemover.paintOver(pngImage, options))
    {
        result.save(outputPath);
    }
}

```

### TeleaWatermarkOptions(Point[] mask) {#TeleaWatermarkOptions-com.aspose.imaging.Point---}
```
public TeleaWatermarkOptions(Point[] mask)
```


Инициализирует новый экземпляр класса [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mask | [Point\[\]](../../com.aspose.imaging/point) | Маска для неизвестной области. |

### TeleaWatermarkOptions(GraphicsPath mask) {#TeleaWatermarkOptions-com.aspose.imaging.GraphicsPath-}
```
public TeleaWatermarkOptions(GraphicsPath mask)
```


Инициализирует новый экземпляр класса [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mask | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Маска для неизвестной области. |

### getHalfPatchSize() {#getHalfPatchSize--}
```
public final int getHalfPatchSize()
```


Получает половину размера патча.

Значение: Размер патча.

**Returns:**
int - половина размера патча.
### setHalfPatchSize(int value) {#setHalfPatchSize-int-}
```
public final void setHalfPatchSize(int value)
```


Устанавливает половину размера патча.

Значение: Размер патча.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | половина размера патча. |

