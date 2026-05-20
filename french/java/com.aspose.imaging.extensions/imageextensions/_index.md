---
title: "ImageExtensions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Contient des méthodes d'extension pour les conversions basées sur System.Drawing.Image et Image."
type: docs
weight: 18
url: /fr/java/com.aspose.imaging.extensions/imageextensions/
---
**Inheritance:**
java.lang.Object
```
public final class ImageExtensions
```

Contient des méthodes d'extension pour les conversions basées sur `System.Drawing.Image` et `Image`.
## Méthodes

| Méthode | Description |
| --- | --- |
| [fromJava(BufferedImage image, Rectangle rect)](#fromJava-java.awt.image.BufferedImage-com.aspose.imaging.Rectangle-) | Convertit le `BufferedImage` en `PngImage`. |
| [fromJava(BufferedImage image)](#fromJava-java.awt.image.BufferedImage-) | Convertit le `BufferedImage` en `PngImage`. |
| [toJava(Image image)](#toJava-com.aspose.imaging.Image-) | Convertit le `Image` en `BufferedImage` avec TYPE\_INT\_ARGB. |
| [toJava(Image image, int bufferedImageType)](#toJava-com.aspose.imaging.Image-int-) | Convertit le `Image` en `BufferedImage` avec bufferedImageType. |
| [toJava(Image image, Rectangle subImageRect)](#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-) | Prend la sous-image de `Image` et la convertit en `BufferedImage` avec BufferedImage.TYPE\_INT\_ARGB. |
| [wrap(BufferedImage image)](#wrap-java.awt.image.BufferedImage-) | Crée un wrapper sur le BufferedImage sans copier les données des pixels. |
| [toJava(Image image, Rectangle subImageRect, int bufferedImageType)](#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-int-) | Prend la sous-image de `Image` et la convertit en `BufferedImage` avec bufferedImageType. |
| [toJava(Image image, Rectangle subImageRect, BufferedImage dstImage)](#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-java.awt.image.BufferedImage-) | Prend la sous-image de `Image` et la convertit en `BufferedImage` avec bufferedImageType. |
### fromJava(BufferedImage image, Rectangle rect) {#fromJava-java.awt.image.BufferedImage-com.aspose.imaging.Rectangle-}
```
public static RasterImage fromJava(BufferedImage image, Rectangle rect)
```


Convertit le `BufferedImage` en `PngImage`.

Attention, l'image GDI peut avoir des limites inférieures à celles de `image`. Pour obtenir toutes les parties de l'image, utilisez la méthode d'extension plus sûre ToGdiImageFull.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | Le `BufferedImage` à convertir. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle requis. |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The converted `PngImage`.
### fromJava(BufferedImage image) {#fromJava-java.awt.image.BufferedImage-}
```
public static RasterImage fromJava(BufferedImage image)
```


Convertit le `BufferedImage` en `PngImage`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | Le `BufferedImage` à convertir. |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The converted `PngImage`.
### toJava(Image image) {#toJava-com.aspose.imaging.Image-}
```
public static BufferedImage toJava(Image image)
```


Convertit le `Image` en `BufferedImage` avec TYPE\_INT\_ARGB.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | L'`Image` à convertir. |

**Returns:**
java.awt.image.BufferedImage - Le `BufferedImage` converti.
### toJava(Image image, int bufferedImageType) {#toJava-com.aspose.imaging.Image-int-}
```
public static BufferedImage toJava(Image image, int bufferedImageType)
```


Convertit l'`Image` en `BufferedImage` avec bufferedImageType. Veuillez choisir `bufferedImageType` parmi java.awt.image.BufferedImage\#TYPE\_\*\*\*\*

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | L'`Image` à convertir. |
| bufferedImageType | int |  |

**Returns:**
java.awt.image.BufferedImage - Le `BufferedImage` converti.
### toJava(Image image, Rectangle subImageRect) {#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-}
```
public static BufferedImage toJava(Image image, Rectangle subImageRect)
```


Prend la sous-image de `Image` et la convertit en `BufferedImage` avec BufferedImage.TYPE\_INT\_ARGB.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | L'`Image` à convertir. |
| subImageRect | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle de la sous-image à convertir. |

**Returns:**
java.awt.image.BufferedImage - Le `BufferedImage` converti contient la sous-image prise de l'`Image`.
### wrap(BufferedImage image) {#wrap-java.awt.image.BufferedImage-}
```
public static RasterImage wrap(BufferedImage image)
```


Créez un wrapper autour du BufferedImage sans copier les données des pixels. Il utilise l'`image` source en interne mais permet de la manipuler comme avec un [RasterImage](../../com.aspose.imaging/rasterimage).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | L'image source. |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The wrapper RasterImage.
### toJava(Image image, Rectangle subImageRect, int bufferedImageType) {#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-int-}
```
public static BufferedImage toJava(Image image, Rectangle subImageRect, int bufferedImageType)
```


Prend la sous-image de l'`Image` et la convertit en `BufferedImage` avec bufferedImageType. Veuillez choisir `bufferedImageType` parmi java.awt.image.BufferedImage\#TYPE\_\*\*\*\*

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | L'`Image` à convertir. |
| subImageRect | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle de la sous-image à convertir. |
| bufferedImageType | int |  |

**Returns:**
java.awt.image.BufferedImage - Le `BufferedImage` converti contient la sous-image prise de l'`Image`.
### toJava(Image image, Rectangle subImageRect, BufferedImage dstImage) {#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-java.awt.image.BufferedImage-}
```
public static BufferedImage toJava(Image image, Rectangle subImageRect, BufferedImage dstImage)
```


Prend la sous-image de l'`Image` et la convertit en `BufferedImage` avec bufferedImageType. Veuillez choisir `bufferedImageType` parmi java.awt.image.BufferedImage\#TYPE\_\*\*\*\*

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | L'`Image` à convertir. |
| subImageRect | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle de la sous-image à convertir. Si `subImageRect.isEmpty()` l'image entière sera prise. |
| dstImage | java.awt.image.BufferedImage | L'image de destination. |

**Returns:**
java.awt.image.BufferedImage - Le `BufferedImage` converti contient la sous-image prise de l'`Image`.
