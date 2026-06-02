---
title: "LinearMulticolorGradientBrush"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Birden fazla renk ve uygun konumlarla tanımlanmış lineer degrade içeren bir Brush'ı temsil eder."
type: docs
weight: 13
url: /tr/java/com.aspose.imaging.brushes/linearmulticolorgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.LinearGradientBrushBase](../../com.aspose.imaging.brushes/lineargradientbrushbase)
```
public final class LinearMulticolorGradientBrush extends LinearGradientBrushBase
```

Birden fazla renk ve uygun konumlarla tanımlanmış lineer degrade içeren bir `Brush`'ı temsil eder. Bu sınıf miras alınamaz.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [LinearMulticolorGradientBrush()](#LinearMulticolorGradientBrush--) | Varsayılan parametrelerle `LinearMulticolorGradientBrush` sınıfının yeni bir örneğini başlatır. |
| [LinearMulticolorGradientBrush(Point point1, Point point2)](#LinearMulticolorGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Belirtilen noktalarla `LinearMulticolorGradientBrush` sınıfının yeni bir örneğini başlatır. |
| [LinearMulticolorGradientBrush(PointF point1, PointF point2)](#LinearMulticolorGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Belirtilen noktalarla `LinearMulticolorGradientBrush` sınıfının yeni bir örneğini başlatır. |
| [LinearMulticolorGradientBrush(Rectangle rect, float angle)](#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-) | `LinearMulticolorGradientBrush` sınıfının yeni bir örneğini bir dikdörtgen ve bir yön açısına göre başlatır. |
| [LinearMulticolorGradientBrush(RectangleF rect, float angle)](#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-) | `LinearMulticolorGradientBrush` sınıfının yeni bir örneğini bir dikdörtgen ve bir yön açısına göre başlatır. |
| [LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable)](#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-boolean-) | `LinearMulticolorGradientBrush` sınıfının yeni bir örneğini bir dikdörtgen ve bir yön açısına göre başlatır. |
| [LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable)](#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-boolean-) | `LinearMulticolorGradientBrush` sınıfının yeni bir örneğini bir dikdörtgen ve bir yön açısına göre başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | Çok renkli doğrusal bir gradyanı tanımlayan bir `com.aspose.imaging.ColorBlend` alır. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | Çok renkli doğrusal bir gradyanı tanımlayan bir `com.aspose.imaging.ColorBlend` ayarlar. |
### LinearMulticolorGradientBrush() {#LinearMulticolorGradientBrush--}
```
public LinearMulticolorGradientBrush()
```


`LinearMulticolorGradientBrush` sınıfının yeni bir örneğini varsayılan parametrelerle başlatır. Başlangıç rengi siyahtır, bitiş rengi beyazdır, açı 45 derecedir ve dikdörtgen (0,0) konumunda, (1,1) boyutundadır.

### LinearMulticolorGradientBrush(Point point1, Point point2) {#LinearMulticolorGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public LinearMulticolorGradientBrush(Point point1, Point point2)
```


Belirtilen noktalarla `LinearMulticolorGradientBrush` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Doğrusal gradyanın başlangıç noktasını temsil eden bir `Aspose.Imaging.Point` yapısı. |
| point2 | [Point](../../com.aspose.imaging/point) | Doğrusal gradyanın bitiş noktasını temsil eden bir `Aspose.Imaging.Point` yapısı. |

### LinearMulticolorGradientBrush(PointF point1, PointF point2) {#LinearMulticolorGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public LinearMulticolorGradientBrush(PointF point1, PointF point2)
```


Belirtilen noktalarla `LinearMulticolorGradientBrush` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | Doğrusal gradyanın başlangıç noktasını temsil eden bir `Aspose.Imaging.PointF` yapısı. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | Doğrusal gradyanın bitiş noktasını temsil eden bir `Aspose.Imaging.PointF` yapısı. |

### LinearMulticolorGradientBrush(Rectangle rect, float angle) {#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-}
```
public LinearMulticolorGradientBrush(Rectangle rect, float angle)
```


`LinearMulticolorGradientBrush` sınıfının yeni bir örneğini bir dikdörtgen ve bir yön açısına göre başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Doğrusal gradyanın sınırlarını belirten bir `Aspose.Imaging.RectangleF` yapısı. |
| angle | float | Gradyanın yön çizgisinin, x ekseninden saat yönünde derece cinsinden ölçülen açısı. |

### LinearMulticolorGradientBrush(RectangleF rect, float angle) {#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-}
```
public LinearMulticolorGradientBrush(RectangleF rect, float angle)
```


`LinearMulticolorGradientBrush` sınıfının yeni bir örneğini bir dikdörtgen ve bir yön açısına göre başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Doğrusal gradyanın sınırlarını belirten bir `Aspose.Imaging.RectangleF` yapısı. |
| angle | float | Gradyanın yön çizgisinin, x ekseninden saat yönünde derece cinsinden ölçülen açısı. |

### LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable) {#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-boolean-}
```
public LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable)
```


`LinearMulticolorGradientBrush` sınıfının yeni bir örneğini bir dikdörtgen ve bir yön açısına göre başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Doğrusal gradyanın sınırlarını belirten bir `Aspose.Imaging.RectangleF` yapısı. |
| angle | float | Gradyanın yön çizgisinin, x ekseninden saat yönünde derece cinsinden ölçülen açısı. |
| isAngleScalable | boolean | `true` olarak ayarlanırsa, bu `LinearMulticolorGradientBrush` ile dönüşümler sırasında açı değişir. |

### LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable) {#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-boolean-}
```
public LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable)
```


`LinearMulticolorGradientBrush` sınıfının yeni bir örneğini bir dikdörtgen ve bir yön açısına göre başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Doğrusal gradyanın sınırlarını belirten bir `Aspose.Imaging.RectangleF` yapısı. |
| angle | float | Gradyanın yön çizgisinin, x ekseninden saat yönünde derece cinsinden ölçülen açısı. |
| isAngleScalable | boolean | `true` olarak ayarlanırsa, bu `LinearMulticolorGradientBrush` ile dönüşümler sırasında açı değişir. |

### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Çok renkli doğrusal bir gradyanı tanımlayan bir `com.aspose.imaging.ColorBlend` alır.

**Returns:**
[ColorBlend](../../com.aspose.imaging/colorblend) - A `com.aspose.imaging.ColorBlend` that defines a multicolor linear gradient.
### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.imaging.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Çok renkli doğrusal bir gradyanı tanımlayan bir `com.aspose.imaging.ColorBlend` ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.imaging/colorblend) | Çok renkli doğrusal bir gradyanı tanımlayan bir `com.aspose.imaging.ColorBlend`. |

