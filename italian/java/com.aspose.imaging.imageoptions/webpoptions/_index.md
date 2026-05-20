---
title: "WebPOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Crea immagini raster WebP moderne utilizzando la nostra API, con un supporto robusto per la compressione lossless e lossy, nonché per i canali alfa e i cicli di animazione."
type: docs
weight: 53
url: /it/java/com.aspose.imaging.imageoptions/webpoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class WebPOptions extends ImageOptionsBase
```

Crea immagini raster WebP moderne utilizzando la nostra API, con un supporto robusto per la compressione lossless e lossy, nonché per i canali alfa e i cicli di animazione. Migliora i contenuti web con elementi visivi dinamici ottimizzando le dimensioni dei file per velocità di caricamento migliorate e un'esperienza utente più fluida.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WebPOptions()](#WebPOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLossless()](#getLossless--) | Ottiene o imposta un valore che indica se questo `WebPOptions` è lossless. |
| [setLossless(boolean value)](#setLossless-boolean-) | Ottiene o imposta un valore che indica se questo `WebPOptions` è lossless. |
| [getQuality()](#getQuality--) | Ottiene o imposta la qualità. |
| [setQuality(float value)](#setQuality-float-) | Ottiene o imposta la qualità. |
| [getAnimLoopCount()](#getAnimLoopCount--) | Ottiene o imposta il conteggio dei cicli di animazione. |
| [setAnimLoopCount(int value)](#setAnimLoopCount-int-) | Ottiene o imposta il conteggio dei cicli di animazione. |
| [getAnimBackgroundColor()](#getAnimBackgroundColor--) | Ottiene o imposta il colore dello sfondo dell'animazione. |
| [setAnimBackgroundColor(long value)](#setAnimBackgroundColor-long-) | Ottiene o imposta il colore dello sfondo dell'animazione. |

## Example: The following example shows how to convert a multipage vector image to WEBP format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.webp";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.WebPOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Esporta solo le prime due pagine. Queste pagine saranno presentate come fotogrammi animati nell'output WEBP.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage)image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
}
```

### WebPOptions() {#WebPOptions--}
```
public WebPOptions()
```


### getLossless() {#getLossless--}
```
public boolean getLossless()
```


Ottiene o imposta un valore che indica se questo `WebPOptions` è lossless.

**Returns:**
boolean - `true` se lossless; altrimenti, `false`.
### setLossless(boolean value) {#setLossless-boolean-}
```
public void setLossless(boolean value)
```


Ottiene o imposta un valore che indica se questo `WebPOptions` è lossless.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | `true` se lossless; altrimenti, `false`. |

### getQuality() {#getQuality--}
```
public float getQuality()
```


Ottiene o imposta la qualità.

**Returns:**
float - La qualità.
### setQuality(float value) {#setQuality-float-}
```
public void setQuality(float value)
```


Ottiene o imposta la qualità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | La qualità. |

### getAnimLoopCount() {#getAnimLoopCount--}
```
public int getAnimLoopCount()
```


Ottiene o imposta il conteggio dei cicli di animazione.

**Returns:**
int - Il conteggio dei cicli di animazione, 0 - infinito.
### setAnimLoopCount(int value) {#setAnimLoopCount-int-}
```
public void setAnimLoopCount(int value)
```


Ottiene o imposta il conteggio dei cicli di animazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il conteggio dei cicli di animazione, 0 - infinito. |

### getAnimBackgroundColor() {#getAnimBackgroundColor--}
```
public long getAnimBackgroundColor()
```


Ottiene o imposta il colore dello sfondo dell'animazione.

**Returns:**
long - Il colore dello sfondo dell'animazione.
### setAnimBackgroundColor(long value) {#setAnimBackgroundColor-long-}
```
public void setAnimBackgroundColor(long value)
```


Ottiene o imposta il colore dello sfondo dell'animazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long | Il colore dello sfondo dell'animazione. |

