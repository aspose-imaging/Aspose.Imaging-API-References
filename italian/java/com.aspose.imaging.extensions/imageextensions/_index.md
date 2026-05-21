---
title: "ImageExtensions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Contiene metodi di estensione per conversioni basate su System.Drawing.Image e Image."
type: docs
weight: 18
url: /it/java/com.aspose.imaging.extensions/imageextensions/
---
**Inheritance:**
java.lang.Object
```
public final class ImageExtensions
```

Contiene metodi di estensione per conversioni basate su `System.Drawing.Image` e `Image`.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [fromJava(BufferedImage image, Rectangle rect)](#fromJava-java.awt.image.BufferedImage-com.aspose.imaging.Rectangle-) | Converte il `BufferedImage` in `PngImage`. |
| [fromJava(BufferedImage image)](#fromJava-java.awt.image.BufferedImage-) | Converte il `BufferedImage` in `PngImage`. |
| [toJava(Image image)](#toJava-com.aspose.imaging.Image-) | Converte l'`Image` in `BufferedImage` con TYPE\_INT\_ARGB. |
| [toJava(Image image, int bufferedImageType)](#toJava-com.aspose.imaging.Image-int-) | Converte l'`Image` in `BufferedImage` con bufferedImageType. |
| [toJava(Image image, Rectangle subImageRect)](#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-) | Estrae la sottoimmagine da `Image` e la converte in `BufferedImage` con BufferedImage.TYPE\_INT\_ARGB. |
| [wrap(BufferedImage image)](#wrap-java.awt.image.BufferedImage-) | Crea un wrapper su BufferedImage senza copiare i dati dei pixel. |
| [toJava(Image image, Rectangle subImageRect, int bufferedImageType)](#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-int-) | Estrae la sottoimmagine da `Image` e la converte in `BufferedImage` con bufferedImageType. |
| [toJava(Image image, Rectangle subImageRect, BufferedImage dstImage)](#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-java.awt.image.BufferedImage-) | Estrae la sottoimmagine da `Image` e la converte in `BufferedImage` con bufferedImageType. |
### fromJava(BufferedImage image, Rectangle rect) {#fromJava-java.awt.image.BufferedImage-com.aspose.imaging.Rectangle-}
```
public static RasterImage fromJava(BufferedImage image, Rectangle rect)
```


Converte il `BufferedImage` in `PngImage`.

Attenzione, l'immagine GDI potrebbe avere limiti inferiori rispetto a `image`. Per ottenere tutte le parti dell'immagine, usa il metodo di estensione più sicuro ToGdiImageFull.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | Il `BufferedImage` da convertire. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo richiesto. |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The converted `PngImage`.
### fromJava(BufferedImage image) {#fromJava-java.awt.image.BufferedImage-}
```
public static RasterImage fromJava(BufferedImage image)
```


Converte il `BufferedImage` in `PngImage`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | Il `BufferedImage` da convertire. |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The converted `PngImage`.
### toJava(Image image) {#toJava-com.aspose.imaging.Image-}
```
public static BufferedImage toJava(Image image)
```


Converte l'`Image` in `BufferedImage` con TYPE\_INT\_ARGB.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | L'`Image` da convertire. |

**Returns:**
java.awt.image.BufferedImage - Il `BufferedImage` convertito.
### toJava(Image image, int bufferedImageType) {#toJava-com.aspose.imaging.Image-int-}
```
public static BufferedImage toJava(Image image, int bufferedImageType)
```


Converte l'`Image` in `BufferedImage` con bufferedImageType. Si prega di scegliere `bufferedImageType` da java.awt.image.BufferedImage\#TYPE\_\*\*\*\*

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | L'`Image` da convertire. |
| bufferedImageType | int |  |

**Returns:**
java.awt.image.BufferedImage - Il `BufferedImage` convertito.
### toJava(Image image, Rectangle subImageRect) {#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-}
```
public static BufferedImage toJava(Image image, Rectangle subImageRect)
```


Estrae la sottoimmagine da `Image` e la converte in `BufferedImage` con BufferedImage.TYPE\_INT\_ARGB.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | L'`Image` da convertire. |
| subImageRect | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo della sottoimmagine da convertire. |

**Returns:**
java.awt.image.BufferedImage - Il `BufferedImage` convertito contiene la sottoimmagine presa da `Image`.
### wrap(BufferedImage image) {#wrap-java.awt.image.BufferedImage-}
```
public static RasterImage wrap(BufferedImage image)
```


Crea un wrapper sul BufferedImage senza copiare i dati dei pixel. Utilizza l'`image` di origine internamente ma consente di manipolarlo come un [RasterImage](../../com.aspose.imaging/rasterimage).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | L'immagine di origine. |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The wrapper RasterImage.
### toJava(Image image, Rectangle subImageRect, int bufferedImageType) {#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-int-}
```
public static BufferedImage toJava(Image image, Rectangle subImageRect, int bufferedImageType)
```


Prende la sottoimmagine da `Image` e la converte in `BufferedImage` con bufferedImageType. Si prega di scegliere `bufferedImageType` da java.awt.image.BufferedImage\#TYPE\_\*\*\*\*

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | L'`Image` da convertire. |
| subImageRect | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo della sottoimmagine da convertire. |
| bufferedImageType | int |  |

**Returns:**
java.awt.image.BufferedImage - Il `BufferedImage` convertito contiene la sottoimmagine presa da `Image`.
### toJava(Image image, Rectangle subImageRect, BufferedImage dstImage) {#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-java.awt.image.BufferedImage-}
```
public static BufferedImage toJava(Image image, Rectangle subImageRect, BufferedImage dstImage)
```


Prende la sottoimmagine da `Image` e la converte in `BufferedImage` con bufferedImageType. Si prega di scegliere `bufferedImageType` da java.awt.image.BufferedImage\#TYPE\_\*\*\*\*

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | L'`Image` da convertire. |
| subImageRect | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo della sotto-immagine da convertire. Se `subImageRect.isEmpty()` verrà presa l'intera immagine. |
| dstImage | java.awt.image.BufferedImage | L'immagine di destinazione. |

**Returns:**
java.awt.image.BufferedImage - Il `BufferedImage` convertito contiene la sotto-immagine presa da `Image`.
