---
title: "LinearGradientBrush"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bir Aspose.Imaging.Brush nesnesini lineer bir degrade ile kapsar."
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.brushes/lineargradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.LinearGradientBrushBase](../../com.aspose.imaging.brushes/lineargradientbrushbase)
```
public final class LinearGradientBrush extends LinearGradientBrushBase
```

Bir `Aspose.Imaging.Brush` nesnesini lineer bir degrade ile kapsar. Bu sınıf miras alınamaz.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-) | Yeni bir [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) sınıfı örneği başlatır. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-) | Yeni bir [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) sınıfı örneği başlatır. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-) | Yeni bir [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) sınıfı örneği başlatır. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-) | Yeni bir [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) sınıfı örneği başlatır. |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.Color-com.aspose.imaging.Color-) | Yeni bir [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) sınıfı örneği başlatır. |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Color-com.aspose.imaging.Color-) | Yeni bir [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) sınıfı örneği başlatır. |
| [LinearGradientBrush()](#LinearGradientBrush--) | Yeni bir [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) sınıfı örneğini varsayılan parametrelerle başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | Çok renkli doğrusal bir gradyanı tanımlayan bir `com.aspose.imaging.ColorBlend` alır. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | Çok renkli doğrusal bir gradyanı tanımlayan bir `com.aspose.imaging.ColorBlend` ayarlar. |
| [getLinearColors()](#getLinearColors--) | Degrenin başlangıç ve bitiş renklerini alır. |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.imaging.Color---) | Degrenin başlangıç ve bitiş renklerini ayarlar. |
| [getStartColor()](#getStartColor--) | Başlangıç degrade rengini alır. |
| [setStartColor(Color value)](#setStartColor-com.aspose.imaging.Color-) | Başlangıç degrade rengini ayarlar. |
| [getEndColor()](#getEndColor--) | Bitiş degrade rengini alır. |
| [setEndColor(Color value)](#setEndColor-com.aspose.imaging.Color-) | Bitiş degrade rengini ayarlar. |
| [getBlend()](#getBlend--) | Degrenin özel bir düşüşünü tanımlayan konum ve faktörleri belirten bir `Aspose.Imaging.Blend` alır. |
| [setBlend(Blend value)](#setBlend-com.aspose.imaging.Blend-) | Degrenin özel bir düşüşünü tanımlayan konum ve faktörleri belirten bir `Aspose.Imaging.Blend` ayarlar. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Çan şeklinde bir eğriye dayalı bir degrade düşüşü oluşturur. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Çan şeklinde bir eğriye dayalı bir degrade düşüşü oluşturur. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Ortadaki renk ve her iki uçta tek bir renge doğru lineer bir düşüşe sahip bir lineer degrade oluşturur. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Ortadaki renk ve her iki uçta tek bir renge doğru lineer bir düşüşe sahip bir lineer degrade oluşturur. |
### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Yeni bir [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Dikdörtgen. |
| color1 | [Color](../../com.aspose.imaging/color) | Renk1. |
| color2 | [Color](../../com.aspose.imaging/color) | Renk2. |
| angle | float | Bu açı. |
| isAngleScalable | boolean | eğer `true` olarak ayarlanırsa [açı ölçeklenebilir]. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Yeni bir [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Dikdörtgen. |
| color1 | [Color](../../com.aspose.imaging/color) | Renk1. |
| color2 | [Color](../../com.aspose.imaging/color) | Renk2. |
| angle | float | Bu açı. |
| isAngleScalable | boolean | eğer `true` olarak ayarlanırsa [açı ölçeklenebilir]. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


Yeni bir [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Dikdörtgen. |
| color1 | [Color](../../com.aspose.imaging/color) | Renk1. |
| color2 | [Color](../../com.aspose.imaging/color) | Renk2. |
| angle | float | Bu açı. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


Yeni bir [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Dikdörtgen. |
| color1 | [Color](../../com.aspose.imaging/color) | Renk1. |
| color2 | [Color](../../com.aspose.imaging/color) | Renk2. |
| angle | float | Bu açı. |

### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.Color-com.aspose.imaging.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


Yeni bir [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | Nokta1. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | Nokta2. |
| color1 | [Color](../../com.aspose.imaging/color) | Renk1. |
| color2 | [Color](../../com.aspose.imaging/color) | Renk2. |

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Color-com.aspose.imaging.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


Yeni bir [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Nokta1. |
| point2 | [Point](../../com.aspose.imaging/point) | Nokta2. |
| color1 | [Color](../../com.aspose.imaging/color) | Renk1. |
| color2 | [Color](../../com.aspose.imaging/color) | Renk2. |

### LinearGradientBrush() {#LinearGradientBrush--}
```
public LinearGradientBrush()
```


Yeni bir [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) sınıfı örneğini varsayılan parametrelerle başlatır. Başlangıç rengi siyahtır, bitiş rengi beyazdır, açı 45 derecedir ve dikdörtgen (0,0) konumunda, (1,1) boyutundadır.

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

### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


Degrenin başlangıç ve bitiş renklerini alır.

**Returns:**
com.aspose.imaging.Color[] - Degrenin başlangıç ve bitiş renklerini temsil eden iki `Color` yapısının bir dizisi.
### setLinearColors(Color[] value) {#setLinearColors-com.aspose.imaging.Color---}
```
public void setLinearColors(Color[] value)
```


Degrenin başlangıç ve bitiş renklerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.imaging/color) | Degrenin başlangıç ve bitiş renklerini temsil eden iki `Color` yapısının bir dizisi. |

### getStartColor() {#getStartColor--}
```
public Color getStartColor()
```


Başlangıç degrade rengini alır.

**Returns:**
[Color](../../com.aspose.imaging/color) - The starting gradient color.
### setStartColor(Color value) {#setStartColor-com.aspose.imaging.Color-}
```
public void setStartColor(Color value)
```


Başlangıç degrade rengini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Başlangıç degrade rengi. |

### getEndColor() {#getEndColor--}
```
public Color getEndColor()
```


Bitiş degrade rengini alır.

**Returns:**
[Color](../../com.aspose.imaging/color) - The ending gradient color.
### setEndColor(Color value) {#setEndColor-com.aspose.imaging.Color-}
```
public void setEndColor(Color value)
```


Bitiş degrade rengini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Bitiş degrade rengi. |

### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Degrenin özel bir düşüşünü tanımlayan konum ve faktörleri belirten bir `Aspose.Imaging.Blend` alır.

**Returns:**
[Blend](../../com.aspose.imaging/blend) - A `Aspose.Imaging.Blend` that represents a custom falloff for the gradient.
### setBlend(Blend value) {#setBlend-com.aspose.imaging.Blend-}
```
public void setBlend(Blend value)
```


Degrenin özel bir düşüşünü tanımlayan konum ve faktörleri belirten bir `Aspose.Imaging.Blend` ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Blend](../../com.aspose.imaging/blend) | Bir `Aspose.Imaging.Blend` nesnesi, degrade için özel bir düşüşü temsil eder. |

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Çan şeklinde bir eğriye dayalı bir degrade düşüşü oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| odak | float | 0 ile 1 arasında bir değer, degrade merkezini (başlangıç rengi ile bitiş renginin eşit şekilde karıştığı nokta) belirtir. |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Çan şeklinde bir eğriye dayalı bir degrade düşüşü oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| odak | float | 0 ile 1 arasında bir değer, degrade merkezini (degrade sadece bitiş renginden oluştuğu nokta) belirtir. |
| ölçek | float | 0 ile 1 arasında bir değer, renklerin `focus` noktasından ne kadar hızlı azaldığını belirtir. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Ortadaki renk ve her iki uçta tek bir renge doğru lineer bir düşüşe sahip bir lineer degrade oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| odak | float | 0 ile 1 arasında bir değer, degrade merkezini (degrade sadece bitiş renginden oluştuğu nokta) belirtir. |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Ortadaki renk ve her iki uçta tek bir renge doğru lineer bir düşüşe sahip bir lineer degrade oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| odak | float | 0 ile 1 arasında bir değer, degrade merkezini (degrade sadece bitiş renginden oluştuğu nokta) belirtir. |
| ölçek | float | 0 ile 1 arasında bir değer, renklerin başlangıç renginden `focus` (bitiş rengi) noktasına ne kadar hızlı azaldığını belirtir. |

