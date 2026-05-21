---
title: "TeleaWatermarkOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Le comuni opzioni dell'algoritmo Telea."
type: docs
weight: 11
url: /it/java/com.aspose.imaging.watermark.options/teleawatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.watermark.options.WatermarkOptions](../../com.aspose.imaging.watermark.options/watermarkoptions)
```
public class TeleaWatermarkOptions extends WatermarkOptions
```

Le comuni opzioni dell'algoritmo Telea.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TeleaWatermarkOptions(Point[] mask)](#TeleaWatermarkOptions-com.aspose.imaging.Point---) | Inizializza una nuova istanza della classe [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions). |
| [TeleaWatermarkOptions(GraphicsPath mask)](#TeleaWatermarkOptions-com.aspose.imaging.GraphicsPath-) | Inizializza una nuova istanza della classe [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHalfPatchSize()](#getHalfPatchSize--) | Ottiene la dimensione metà del patch. |
| [setHalfPatchSize(int value)](#setHalfPatchSize-int-) | Imposta la dimensione metà del patch. |

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


Inizializza una nuova istanza della classe [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mask | [Point\[\]](../../com.aspose.imaging/point) | La maschera per l'area sconosciuta. |

### TeleaWatermarkOptions(GraphicsPath mask) {#TeleaWatermarkOptions-com.aspose.imaging.GraphicsPath-}
```
public TeleaWatermarkOptions(GraphicsPath mask)
```


Inizializza una nuova istanza della classe [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mask | [GraphicsPath](../../com.aspose.imaging/graphicspath) | La maschera per l'area sconosciuta. |

### getHalfPatchSize() {#getHalfPatchSize--}
```
public final int getHalfPatchSize()
```


Ottiene la dimensione metà del patch.

Valore: La dimensione del patch.

**Returns:**
int - la dimensione metà del patch.
### setHalfPatchSize(int value) {#setHalfPatchSize-int-}
```
public final void setHalfPatchSize(int value)
```


Imposta la dimensione metà del patch.

Valore: La dimensione del patch.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | la dimensione metà del patch. |

