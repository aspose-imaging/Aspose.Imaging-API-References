---
title: "PathGradientBrush"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bir gradient ile Aspose.Imaging.Brush nesnesini kapsüller."
type: docs
weight: 14
url: /tr/java/com.aspose.imaging.brushes/pathgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.PathGradientBrushBase](../../com.aspose.imaging.brushes/pathgradientbrushbase)
```
public final class PathGradientBrush extends PathGradientBrushBase
```

Bir gradient ile `Aspose.Imaging.Brush` nesnesini kapsüller. Bu sınıf kalıtılamaz.

Merkez rengi varsayılan olarak beyazdır. Bir kullanıcı bu değeri istediği zaman daha sonra değiştirebilir.

Çevre renkleri dizisi varsayılan olarak beyaz renk içeren tek bir elemanla başlatılır. Çevre renkleri daha sonra değiştirilebilir, ancak çevre renklerini ayarlarken en az bir eleman gereklidir.

`Blend` hakkında daha fazla ayrıntı için bakın.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.imaging.PointF---) | Belirtilen noktalarla `PathGradientBrush` sınıfının yeni bir örneğini başlatır. |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.imaging.PointF---int-) | Belirtilen noktalar ve sarma modu ile `PathGradientBrush` sınıfının yeni bir örneğini başlatır. |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.imaging.Point---) | Belirtilen noktalarla `PathGradientBrush` sınıfının yeni bir örneğini başlatır. |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.imaging.Point---int-) | Belirtilen noktalar ve sarma modu ile `PathGradientBrush` sınıfının yeni bir örneğini başlatır. |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.imaging.GraphicsPath-) | Belirtilen yol ile `PathGradientBrush` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | Çok renkli doğrusal bir gradyanı tanımlayan bir `com.aspose.imaging.ColorBlend` alır. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | Çok renkli doğrusal bir gradyanı tanımlayan bir `com.aspose.imaging.ColorBlend` ayarlar. |
| [getCenterColor()](#getCenterColor--) | Yol gradyanının merkezindeki rengi alır. |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.imaging.Color-) | Yol gradyanının merkezindeki rengi ayarlar. |
| [getSurroundColors()](#getSurroundColors--) | `PathGradientBrush`'ın doldurduğu yoldaki noktalara karşılık gelen renkler dizisini alır. |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.imaging.Color---) | `PathGradientBrush`'ın doldurduğu yoldaki noktalara karşılık gelen renkler dizisini ayarlar. |
| [getBlend()](#getBlend--) | Degrenin özel bir düşüşünü tanımlayan konum ve faktörleri belirten bir `Aspose.Imaging.Blend` alır. |
| [setBlend(Blend value)](#setBlend-com.aspose.imaging.Blend-) | Degrenin özel bir düşüşünü tanımlayan konum ve faktörleri belirten bir `Aspose.Imaging.Blend` ayarlar. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Yolun merkezinden başlayarak yolun sınırına doğru renk değiştiren bir gradyan fırçası oluşturur. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Yolun merkezinden başlayarak yolun sınırına doğru renk değiştiren bir gradyan fırçası oluşturur. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Merkez rengi ve tek bir çevre rengine doğru lineer azalma içeren bir gradyan oluşturur. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Merkez rengi ve her bir çevre rengine doğru lineer azalma içeren bir gradyan oluşturur. |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.imaging.PointF---}
```
public PathGradientBrush(PointF[] points)
```


Belirtilen noktalarla `PathGradientBrush` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Yolun köşe noktalarını oluşturan noktaları temsil eden `Aspose.Imaging.PointF` yapılarını içeren bir dizi. |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.imaging.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


Belirtilen noktalar ve sarma modu ile `PathGradientBrush` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Yolun köşe noktalarını oluşturan noktaları temsil eden `Aspose.Imaging.PointF` yapılarını içeren bir dizi. |
| wrapMode | int | `PathGradientBrush` ile çizilen doldurmaların nasıl döşeneceğini belirten bir `Aspose.Imaging.WrapMode`. |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.imaging.Point---}
```
public PathGradientBrush(Point[] points)
```


Belirtilen noktalarla `PathGradientBrush` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | Yolun köşe noktalarını oluşturan noktaları temsil eden `Aspose.Imaging.Point` yapılarını içeren bir dizi. |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.imaging.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


Belirtilen noktalar ve sarma modu ile `PathGradientBrush` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | Yolun köşe noktalarını oluşturan noktaları temsil eden `Aspose.Imaging.Point` yapılarını içeren bir dizi. |
| wrapMode | int | `PathGradientBrush` ile çizilen doldurmaların nasıl döşeneceğini belirten bir `Aspose.Imaging.WrapMode`. |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.imaging.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


Belirtilen yol ile `PathGradientBrush` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Bu `PathGradientBrush` tarafından doldurulan alanı tanımlayan `GraphicsPath`. |

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

### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


Yol gradyanının merkezindeki rengi alır.

**Returns:**
[Color](../../com.aspose.imaging/color) - A `com.aspose.imaging.Color` that represents the color at the center of the path gradient.
### setCenterColor(Color value) {#setCenterColor-com.aspose.imaging.Color-}
```
public void setCenterColor(Color value)
```


Yol gradyanının merkezindeki rengi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Yol gradyanının merkezindeki rengi temsil eden bir `com.aspose.imaging.Color`. |

### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


`PathGradientBrush`'ın doldurduğu yoldaki noktalara karşılık gelen renkler dizisini alır.

**Returns:**
com.aspose.imaging.Color[] - `PathGradientBrush`'ın doldurduğu yoldaki her bir noktaya ilişkin renkleri temsil eden `com.aspose.imaging.Color` yapılarını içeren bir dizi.
### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.imaging.Color---}
```
public void setSurroundColors(Color[] value)
```


`PathGradientBrush`'ın doldurduğu yoldaki noktalara karşılık gelen renkler dizisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.imaging/color) | `PathGradientBrush`'ın doldurduğu yoldaki her bir noktaya ilişkin renkleri temsil eden `com.aspose.imaging.Color` yapılarını içeren bir dizi. |

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


Yolun merkezinden başlayarak yolun sınırına doğru renk değiştiren bir gradyan fırçası oluşturur. Bir renkten diğerine geçiş, çan şeklinde bir eğriye dayanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| odak | float | 0 ile 1 arasında bir değer, yolun merkezinden yolun sınırına doğru herhangi bir radyal boyunca merkez renginin en yüksek yoğunlukta olacağı yeri belirler. 1 değeri (varsayılan), en yüksek yoğunluğu yolun merkezine yerleştirir. |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Yolun merkezinden başlayarak yolun sınırına doğru renk değiştiren bir gradyan fırçası oluşturur. Bir renkten diğerine geçiş, çan şeklinde bir eğriye dayanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| odak | float | 0 ile 1 arasında bir değer, yolun merkezinden yolun sınırına doğru herhangi bir radyal boyunca merkez renginin en yüksek yoğunlukta olacağı yeri belirler. 1 değeri (varsayılan), en yüksek yoğunluğu yolun merkezine yerleştirir. |
| ölçek | float | 0 ile 1 arasında bir değer, merkez rengi ile sınır rengi karıştırıldığında merkez renginin maksimum yoğunluğunu belirler. 1 değeri, merkez renginin mümkün olan en yüksek yoğunluğunu sağlar ve bu varsayılan değerdir. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Merkez rengi ve tek bir çevre rengine doğru lineer azalma içeren bir gradyan oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| odak | float | 0 ile 1 arasında bir değer, yolun merkezinden yolun sınırına doğru herhangi bir radyal boyunca merkez renginin en yüksek yoğunlukta olacağı yeri belirler. 1 değeri (varsayılan), en yüksek yoğunluğu yolun merkezine yerleştirir. |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Merkez rengi ve her bir çevre rengine doğru lineer azalma içeren bir gradyan oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| odak | float | 0 ile 1 arasında bir değer, yolun merkezinden yolun sınırına doğru herhangi bir radyal boyunca merkez renginin en yüksek yoğunlukta olacağı yeri belirler. 1 değeri (varsayılan), en yüksek yoğunluğu yolun merkezine yerleştirir. |
| ölçek | float | 0 ile 1 arasında bir değer, merkez rengi ile sınır rengi karıştırıldığında merkez renginin maksimum yoğunluğunu belirler. 1 değeri, merkez renginin mümkün olan en yüksek yoğunluğunu sağlar ve bu varsayılan değerdir. |

