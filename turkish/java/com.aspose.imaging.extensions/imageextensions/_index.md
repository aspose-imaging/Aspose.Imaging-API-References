---
title: "ImageExtensions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "System.Drawing.Image ve Image tabanlı dönüşümler için uzantı yöntemlerini içerir."
type: docs
weight: 18
url: /tr/java/com.aspose.imaging.extensions/imageextensions/
---
**Inheritance:**
java.lang.Object
```
public final class ImageExtensions
```

`System.Drawing.Image` ve `Image` temelli dönüşümler için uzantı metodlarını içerir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [fromJava(BufferedImage image, Rectangle rect)](#fromJava-java.awt.image.BufferedImage-com.aspose.imaging.Rectangle-) | `BufferedImage`'i `PngImage`'a dönüştürür. |
| [fromJava(BufferedImage image)](#fromJava-java.awt.image.BufferedImage-) | `BufferedImage`'i `PngImage`'a dönüştürür. |
| [toJava(Image image)](#toJava-com.aspose.imaging.Image-) | `Image`'ı TYPE\_INT\_ARGB ile `BufferedImage`'e dönüştürür. |
| [toJava(Image image, int bufferedImageType)](#toJava-com.aspose.imaging.Image-int-) | `Image`'ı bufferedImageType ile `BufferedImage`'e dönüştürür. |
| [toJava(Image image, Rectangle subImageRect)](#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-) | `Image`'den alt görüntüyü alır ve BufferedImage.TYPE\_INT\_ARGB ile `BufferedImage`'e dönüştürür. |
| [wrap(BufferedImage image)](#wrap-java.awt.image.BufferedImage-) | Piksel verilerini kopyalamadan BufferedImage üzerinde bir sarmalayıcı oluştur. |
| [toJava(Image image, Rectangle subImageRect, int bufferedImageType)](#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-int-) | `Image`'den alt görüntüyü alır ve bufferedImageType ile `BufferedImage`'e dönüştürür. |
| [toJava(Image image, Rectangle subImageRect, BufferedImage dstImage)](#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-java.awt.image.BufferedImage-) | `Image`'den alt görüntüyü alır ve bufferedImageType ile `BufferedImage`'e dönüştürür. |
### fromJava(BufferedImage image, Rectangle rect) {#fromJava-java.awt.image.BufferedImage-com.aspose.imaging.Rectangle-}
```
public static RasterImage fromJava(BufferedImage image, Rectangle rect)
```


`BufferedImage`'i `PngImage`'a dönüştürür.

Uyarı, GDI görüntüsü `image`'ın sahip olduğundan daha düşük sınırlar alabilir. Görüntünün tüm bölümlerini elde etmek için daha güvenli uzantı yöntemi ToGdiImageFull'ı kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | Dönüştürülecek `BufferedImage`. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Gerekli dikdörtgen. |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The converted `PngImage`.
### fromJava(BufferedImage image) {#fromJava-java.awt.image.BufferedImage-}
```
public static RasterImage fromJava(BufferedImage image)
```


`BufferedImage`'i `PngImage`'a dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | Dönüştürülecek `BufferedImage`. |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The converted `PngImage`.
### toJava(Image image) {#toJava-com.aspose.imaging.Image-}
```
public static BufferedImage toJava(Image image)
```


`Image`'ı TYPE\_INT\_ARGB ile `BufferedImage`'e dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Dönüştürülecek `Image`. |

**Returns:**
java.awt.image.BufferedImage - Dönüştürülmüş `BufferedImage`.
### toJava(Image image, int bufferedImageType) {#toJava-com.aspose.imaging.Image-int-}
```
public static BufferedImage toJava(Image image, int bufferedImageType)
```


`Image`'i `BufferedImage`'e bufferedImageType ile dönüştürür. Lütfen `bufferedImageType`'ı java.awt.image.BufferedImage\#TYPE\_\*\*\*\* içinden seçin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Dönüştürülecek `Image`. |
| bufferedImageType | int |  |

**Returns:**
java.awt.image.BufferedImage - Dönüştürülmüş `BufferedImage`.
### toJava(Image image, Rectangle subImageRect) {#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-}
```
public static BufferedImage toJava(Image image, Rectangle subImageRect)
```


`Image`'den alt görüntüyü alır ve BufferedImage.TYPE\_INT\_ARGB ile `BufferedImage`'e dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Dönüştürülecek `Image`. |
| subImageRect | [Rectangle](../../com.aspose.imaging/rectangle) | Dönüştürülecek alt görüntünün dikdörtgeni. |

**Returns:**
java.awt.image.BufferedImage - Dönüştürülmüş `BufferedImage`, `Image`'den alınan alt görüntüyü içerir.
### wrap(BufferedImage image) {#wrap-java.awt.image.BufferedImage-}
```
public static RasterImage wrap(BufferedImage image)
```


Piksel verilerini kopyalamadan BufferedImage üzerinde bir sarmalayıcı oluşturun. Altında kaynak `image`'ı kullanır ancak onu bir [RasterImage](../../com.aspose.imaging/rasterimage) gibi manipüle etmenize izin verir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | The source image. |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The wrapper RasterImage.
### toJava(Image image, Rectangle subImageRect, int bufferedImageType) {#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-int-}
```
public static BufferedImage toJava(Image image, Rectangle subImageRect, int bufferedImageType)
```


`Image`'den alt görüntüyü alır ve bufferedImageType ile `BufferedImage`'e dönüştürür. Lütfen `bufferedImageType`'ı java.awt.image.BufferedImage\#TYPE\_\*\*\*\* içinden seçin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Dönüştürülecek `Image`. |
| subImageRect | [Rectangle](../../com.aspose.imaging/rectangle) | Dönüştürülecek alt görüntünün dikdörtgeni. |
| bufferedImageType | int |  |

**Returns:**
java.awt.image.BufferedImage - Dönüştürülmüş `BufferedImage`, `Image`'den alınan alt görüntüyü içerir.
### toJava(Image image, Rectangle subImageRect, BufferedImage dstImage) {#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-java.awt.image.BufferedImage-}
```
public static BufferedImage toJava(Image image, Rectangle subImageRect, BufferedImage dstImage)
```


`Image`'den alt görüntüyü alır ve bufferedImageType ile `BufferedImage`'e dönüştürür. Lütfen `bufferedImageType`'ı java.awt.image.BufferedImage\#TYPE\_\*\*\*\* içinden seçin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Dönüştürülecek `Image`. |
| subImageRect | [Rectangle](../../com.aspose.imaging/rectangle) | Dönüştürülecek alt görüntünün dikdörtgeni. Eğer `subImageRect.isEmpty()` ise tüm görüntü alınır. |
| dstImage | java.awt.image.BufferedImage | Hedef görüntü. |

**Returns:**
java.awt.image.BufferedImage - Dönüştürülmüş `BufferedImage`, `Image`'den alınan alt görüntüyü içerir.
