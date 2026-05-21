---
title: "ImageExtensions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Contiene métodos de extensión para conversiones basadas en System.Drawing.Image e Image."
type: docs
weight: 18
url: /es/java/com.aspose.imaging.extensions/imageextensions/
---
**Inheritance:**
java.lang.Object
```
public final class ImageExtensions
```

Contiene métodos de extensión para conversiones basadas en `System.Drawing.Image` e `Image`.
## Métodos

| Método | Descripción |
| --- | --- |
| [fromJava(BufferedImage image, Rectangle rect)](#fromJava-java.awt.image.BufferedImage-com.aspose.imaging.Rectangle-) | Convierte el `BufferedImage` a `PngImage`. |
| [fromJava(BufferedImage image)](#fromJava-java.awt.image.BufferedImage-) | Convierte el `BufferedImage` a `PngImage`. |
| [toJava(Image image)](#toJava-com.aspose.imaging.Image-) | Convierte el `Image` a `BufferedImage` con TYPE\_INT\_ARGB. |
| [toJava(Image image, int bufferedImageType)](#toJava-com.aspose.imaging.Image-int-) | Convierte el `Image` a `BufferedImage` con bufferedImageType. |
| [toJava(Image image, Rectangle subImageRect)](#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-) | Obtiene la subimagen de `Image` y la convierte a `BufferedImage` con BufferedImage.TYPE\_INT\_ARGB. |
| [wrap(BufferedImage image)](#wrap-java.awt.image.BufferedImage-) | Crea un contenedor sobre el BufferedImage sin copiar los datos de los píxeles. |
| [toJava(Image image, Rectangle subImageRect, int bufferedImageType)](#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-int-) | Obtiene la subimagen de `Image` y la convierte a `BufferedImage` con bufferedImageType. |
| [toJava(Image image, Rectangle subImageRect, BufferedImage dstImage)](#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-java.awt.image.BufferedImage-) | Obtiene la subimagen de `Image` y la convierte a `BufferedImage` con bufferedImageType. |
### fromJava(BufferedImage image, Rectangle rect) {#fromJava-java.awt.image.BufferedImage-com.aspose.imaging.Rectangle-}
```
public static RasterImage fromJava(BufferedImage image, Rectangle rect)
```


Convierte el `BufferedImage` a `PngImage`.

Advertencia, la imagen GDI puede obtener límites inferiores a los que tiene `image`. Para obtener todas las partes de la imagen, use el método de extensión más seguro ToGdiImageFull.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imagen | java.awt.image.BufferedImage | El `BufferedImage` a convertir. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo requerido. |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The converted `PngImage`.
### fromJava(BufferedImage image) {#fromJava-java.awt.image.BufferedImage-}
```
public static RasterImage fromJava(BufferedImage image)
```


Convierte el `BufferedImage` a `PngImage`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imagen | java.awt.image.BufferedImage | El `BufferedImage` a convertir. |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The converted `PngImage`.
### toJava(Image image) {#toJava-com.aspose.imaging.Image-}
```
public static BufferedImage toJava(Image image)
```


Convierte el `Image` a `BufferedImage` con TYPE\_INT\_ARGB.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | La `Image` a convertir. |

**Returns:**
java.awt.image.BufferedImage - El `BufferedImage` convertido.
### toJava(Image image, int bufferedImageType) {#toJava-com.aspose.imaging.Image-int-}
```
public static BufferedImage toJava(Image image, int bufferedImageType)
```


Convierte la `Image` al `BufferedImage` con bufferedImageType. Por favor elija `bufferedImageType` de java.awt.image.BufferedImage\#TYPE\_\*\*\*\*

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | La `Image` a convertir. |
| bufferedImageType | int |  |

**Returns:**
java.awt.image.BufferedImage - El `BufferedImage` convertido.
### toJava(Image image, Rectangle subImageRect) {#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-}
```
public static BufferedImage toJava(Image image, Rectangle subImageRect)
```


Obtiene la subimagen de `Image` y la convierte a `BufferedImage` con BufferedImage.TYPE\_INT\_ARGB.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | La `Image` a convertir. |
| subImageRect | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo de subimagen a convertir. |

**Returns:**
java.awt.image.BufferedImage - El `BufferedImage` convertido contiene la subimagen tomada de `Image`.
### wrap(BufferedImage image) {#wrap-java.awt.image.BufferedImage-}
```
public static RasterImage wrap(BufferedImage image)
```


Cree un contenedor sobre el BufferedImage sin copiar los datos de los píxeles. Utiliza la `image` fuente internamente pero permite manipularla como con un [RasterImage](../../com.aspose.imaging/rasterimage).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imagen | java.awt.image.BufferedImage | La imagen fuente. |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The wrapper RasterImage.
### toJava(Image image, Rectangle subImageRect, int bufferedImageType) {#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-int-}
```
public static BufferedImage toJava(Image image, Rectangle subImageRect, int bufferedImageType)
```


Toma la subimagen de `Image` y la convierte al `BufferedImage` con bufferedImageType. Por favor elija `bufferedImageType` de java.awt.image.BufferedImage\#TYPE\_\*\*\*\*

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | La `Image` a convertir. |
| subImageRect | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo de subimagen a convertir. |
| bufferedImageType | int |  |

**Returns:**
java.awt.image.BufferedImage - El `BufferedImage` convertido contiene la subimagen tomada de `Image`.
### toJava(Image image, Rectangle subImageRect, BufferedImage dstImage) {#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-java.awt.image.BufferedImage-}
```
public static BufferedImage toJava(Image image, Rectangle subImageRect, BufferedImage dstImage)
```


Toma la subimagen de `Image` y la convierte al `BufferedImage` con bufferedImageType. Por favor elija `bufferedImageType` de java.awt.image.BufferedImage\#TYPE\_\*\*\*\*

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | La `Image` a convertir. |
| subImageRect | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo de sub‑imagen a convertir. Si `subImageRect.isEmpty()` se tomará la imagen completa. |
| dstImage | java.awt.image.BufferedImage | La imagen de destino. |

**Returns:**
java.awt.image.BufferedImage - El `BufferedImage` convertido contiene la sub‑imagen tomada de `Image`.
