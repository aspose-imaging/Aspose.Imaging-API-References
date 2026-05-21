---
title: "ImageExtensions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Содержит методы расширения для преобразований, основанных на System.Drawing.Image и Image."
type: docs
weight: 18
url: /ru/java/com.aspose.imaging.extensions/imageextensions/
---
**Inheritance:**
java.lang.Object
```
public final class ImageExtensions
```

Содержит методы-расширения для преобразований, основанных на `System.Drawing.Image` и `Image`.
## Методы

| Метод | Описание |
| --- | --- |
| [fromJava(BufferedImage image, Rectangle rect)](#fromJava-java.awt.image.BufferedImage-com.aspose.imaging.Rectangle-) | Преобразует `BufferedImage` в `PngImage`. |
| [fromJava(BufferedImage image)](#fromJava-java.awt.image.BufferedImage-) | Преобразует `BufferedImage` в `PngImage`. |
| [toJava(Image image)](#toJava-com.aspose.imaging.Image-) | Преобразует `Image` в `BufferedImage` с TYPE\_INT\_ARGB. |
| [toJava(Image image, int bufferedImageType)](#toJava-com.aspose.imaging.Image-int-) | Преобразует `Image` в `BufferedImage` с bufferedImageType. |
| [toJava(Image image, Rectangle subImageRect)](#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-) | Берёт подизображение из `Image` и преобразует его в `BufferedImage` с BufferedImage.TYPE\_INT\_ARGB. |
| [wrap(BufferedImage image)](#wrap-java.awt.image.BufferedImage-) | Создаёт оболочку над BufferedImage без копирования данных пикселей. |
| [toJava(Image image, Rectangle subImageRect, int bufferedImageType)](#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-int-) | Берёт подизображение из `Image` и преобразует его в `BufferedImage` с bufferedImageType. |
| [toJava(Image image, Rectangle subImageRect, BufferedImage dstImage)](#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-java.awt.image.BufferedImage-) | Берёт подизображение из `Image` и преобразует его в `BufferedImage` с bufferedImageType. |
### fromJava(BufferedImage image, Rectangle rect) {#fromJava-java.awt.image.BufferedImage-com.aspose.imaging.Rectangle-}
```
public static RasterImage fromJava(BufferedImage image, Rectangle rect)
```


Преобразует `BufferedImage` в `PngImage`.

Предупреждение: изображение GDI может иметь меньшие границы, чем у `image`. Чтобы получить все части изображения, используйте более безопасный метод расширения ToGdiImageFull.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | `BufferedImage` для конвертации. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Требуемый прямоугольник. |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The converted `PngImage`.
### fromJava(BufferedImage image) {#fromJava-java.awt.image.BufferedImage-}
```
public static RasterImage fromJava(BufferedImage image)
```


Преобразует `BufferedImage` в `PngImage`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | `BufferedImage` для конвертации. |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The converted `PngImage`.
### toJava(Image image) {#toJava-com.aspose.imaging.Image-}
```
public static BufferedImage toJava(Image image)
```


Преобразует `Image` в `BufferedImage` с TYPE\_INT\_ARGB.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | `Image` для конвертации. |

**Returns:**
java.awt.image.BufferedImage - Преобразованный `BufferedImage`.
### toJava(Image image, int bufferedImageType) {#toJava-com.aspose.imaging.Image-int-}
```
public static BufferedImage toJava(Image image, int bufferedImageType)
```


Преобразует `Image` в `BufferedImage` с использованием bufferedImageType. Пожалуйста, выберите `bufferedImageType` из java.awt.image.BufferedImage\#TYPE\_\*\*\*\*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | `Image` для конвертации. |
| bufferedImageType | int |  |

**Returns:**
java.awt.image.BufferedImage - Преобразованный `BufferedImage`.
### toJava(Image image, Rectangle subImageRect) {#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-}
```
public static BufferedImage toJava(Image image, Rectangle subImageRect)
```


Берёт подизображение из `Image` и преобразует его в `BufferedImage` с BufferedImage.TYPE\_INT\_ARGB.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | `Image` для конвертации. |
| subImageRect | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник подизображения для конвертации. |

**Returns:**
java.awt.image.BufferedImage - Преобразованный `BufferedImage` содержит подизображение, взятое из `Image`.
### wrap(BufferedImage image) {#wrap-java.awt.image.BufferedImage-}
```
public static RasterImage wrap(BufferedImage image)
```


Создайте оболочку над BufferedImage без копирования данных пикселей. Она использует исходный `image` под капотом, но позволяет работать с ним так же, как с [RasterImage](../../com.aspose.imaging/rasterimage).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | Исходное изображение. |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The wrapper RasterImage.
### toJava(Image image, Rectangle subImageRect, int bufferedImageType) {#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-int-}
```
public static BufferedImage toJava(Image image, Rectangle subImageRect, int bufferedImageType)
```


Берёт подизображение из `Image` и преобразует его в `BufferedImage` с использованием bufferedImageType. Пожалуйста, выберите `bufferedImageType` из java.awt.image.BufferedImage\#TYPE\_\*\*\*\*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | `Image` для конвертации. |
| subImageRect | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник подизображения для конвертации. |
| bufferedImageType | int |  |

**Returns:**
java.awt.image.BufferedImage - Преобразованный `BufferedImage` содержит подизображение, взятое из `Image`.
### toJava(Image image, Rectangle subImageRect, BufferedImage dstImage) {#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-java.awt.image.BufferedImage-}
```
public static BufferedImage toJava(Image image, Rectangle subImageRect, BufferedImage dstImage)
```


Берёт подизображение из `Image` и преобразует его в `BufferedImage` с использованием bufferedImageType. Пожалуйста, выберите `bufferedImageType` из java.awt.image.BufferedImage\#TYPE\_\*\*\*\*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | `Image` для конвертации. |
| subImageRect | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник подизображения для конвертации. Если `subImageRect.isEmpty()`, будет взято всё изображение. |
| dstImage | java.awt.image.BufferedImage | Изображение назначения. |

**Returns:**
java.awt.image.BufferedImage - Преобразованный `BufferedImage` содержит подизображение, взятое из `Image`.
