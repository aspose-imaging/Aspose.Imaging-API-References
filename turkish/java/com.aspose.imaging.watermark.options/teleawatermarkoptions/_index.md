---
title: "TeleaWatermarkOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Ortak Telea Algoritması seçenekleri."
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.watermark.options/teleawatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.watermark.options.WatermarkOptions](../../com.aspose.imaging.watermark.options/watermarkoptions)
```
public class TeleaWatermarkOptions extends WatermarkOptions
```

Ortak Telea Algoritması seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TeleaWatermarkOptions(Point[] mask)](#TeleaWatermarkOptions-com.aspose.imaging.Point---) | Yeni bir [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions) sınıfının bir örneğini başlatır. |
| [TeleaWatermarkOptions(GraphicsPath mask)](#TeleaWatermarkOptions-com.aspose.imaging.GraphicsPath-) | Yeni bir [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions) sınıfının bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getHalfPatchSize()](#getHalfPatchSize--) | Yarı yama boyutunu alır. |
| [setHalfPatchSize(int value)](#setHalfPatchSize-int-) | Yarı yama boyutunu ayarlar. |

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


Yeni bir [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions) sınıfının bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mask | [Point\[\]](../../com.aspose.imaging/point) | Bilinmeyen alan için maske. |

### TeleaWatermarkOptions(GraphicsPath mask) {#TeleaWatermarkOptions-com.aspose.imaging.GraphicsPath-}
```
public TeleaWatermarkOptions(GraphicsPath mask)
```


Yeni bir [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions) sınıfının bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mask | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Bilinmeyen alan için maske. |

### getHalfPatchSize() {#getHalfPatchSize--}
```
public final int getHalfPatchSize()
```


Yarı yama boyutunu alır.

Değer: Yama boyutu.

**Returns:**
int - yarı yama boyutu.
### setHalfPatchSize(int value) {#setHalfPatchSize-int-}
```
public final void setHalfPatchSize(int value)
```


Yarı yama boyutunu ayarlar.

Değer: Yama boyutu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | yarı yama boyutu. |

