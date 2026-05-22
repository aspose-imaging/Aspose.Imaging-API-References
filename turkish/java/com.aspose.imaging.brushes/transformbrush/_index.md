---
title: "TransformBrush"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Dönüştürme yeteneklerine sahip bir fırça."
type: docs
weight: 19
url: /tr/java/com.aspose.imaging.brushes/transformbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush)
```
public abstract class TransformBrush extends Brush
```

Dönüştürme yeteneklerine sahip bir `Brush`.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TransformBrush()](#TransformBrush--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getWrapMode()](#getWrapMode--) | Bu `TransformBrush` için sarma modunu belirten bir `Aspose.Imaging.WrapMode` enum'ını alır veya ayarlar. |
| [setWrapMode(int value)](#setWrapMode-int-) | Bu `TransformBrush` için sarma modunu belirten bir `Aspose.Imaging.WrapMode` enum'ını alır veya ayarlar. |
| [getTransform()](#getTransform--) | Bu `TransformBrush` için yerel geometrik dönüşümü tanımlayan bir `Aspose.Imaging.Matrix` kopyasını alır veya ayarlar. |
| [setTransform(Matrix value)](#setTransform-com.aspose.imaging.Matrix-) | Bu `TransformBrush` için yerel geometrik dönüşümü tanımlayan bir `Aspose.Imaging.Matrix` kopyasını alır veya ayarlar. |
| [isTransformChanged()](#isTransformChanged--) | Dönüşümlerin bir şekilde değişip değişmediğini gösteren bir değeri alır. |
| [resetTransform()](#resetTransform--) | `TransformBrush.Transform` özelliğini birim (identity) haline sıfırlar. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.imaging.Matrix-) | Bu `LinearGradientBrush` nesnesinin yerel geometrik dönüşümünü temsil eden `Aspose.Imaging.Matrix`'i, belirtilen `Aspose.Imaging.Matrix` ile ön ekleyerek çarpar. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.imaging.Matrix-int-) | Bu `LinearGradientBrush` nesnesinin yerel geometrik dönüşümünü temsil eden `Aspose.Imaging.Matrix`'i, belirtilen sırada belirtilen `Aspose.Imaging.Matrix` ile çarpar. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Yerel geometrik dönüşümü belirtilen boyutlarla çevirir. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Yerel geometrik dönüşümü belirtilen boyutlarla belirtilen sırada çevirir. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Yerel geometrik dönüşümü belirtilen miktarlarla ölçeklendirir. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Yerel geometrik dönüşümü belirtilen miktarlarla belirtilen sırada ölçeklendirir. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Yerel geometrik dönüşümü belirtilen miktarda döndürür. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Yerel geometrik dönüşümü belirtilen miktarda belirtilen sırada döndürür. |
### TransformBrush() {#TransformBrush--}
```
public TransformBrush()
```


### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Bu `TransformBrush` için sarma modunu belirten bir `Aspose.Imaging.WrapMode` enum'ını alır veya ayarlar.

**Returns:**
int - Bu `TransformBrush` ile çizilen doldurmaların nasıl döşeneceğini belirten bir `Aspose.Imaging.WrapMode`.
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Bu `TransformBrush` için sarma modunu belirten bir `Aspose.Imaging.WrapMode` enum'ını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Bu `TransformBrush` için yerel geometrik dönüşümü tanımlayan bir `Aspose.Imaging.Matrix` kopyasını alır veya ayarlar.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - A copy of the `Aspose.Imaging.Matrix` that defines a geometric transform that applies only to fills drawn with this `TransformBrush`.
### setTransform(Matrix value) {#setTransform-com.aspose.imaging.Matrix-}
```
public void setTransform(Matrix value)
```


Bu `TransformBrush` için yerel geometrik dönüşümü tanımlayan bir `Aspose.Imaging.Matrix` kopyasını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### isTransformChanged() {#isTransformChanged--}
```
public boolean isTransformChanged()
```


Dönüşümlerin bir şekilde değişip değişmediğini gösteren bir değeri alır. Örneğin dönüşüm matrisini ayarlamak veya dönüşüm matrisini değiştiren herhangi bir yöntemi çağırmak. Özellik, GDI+ ile geriye dönük uyumluluk sağlamak için eklenmiştir.

Değer: dönüşüm değiştiyse `True`; aksi takdirde `false`.

**Returns:**
boolean
### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


`TransformBrush.Transform` özelliğini birim (identity) haline sıfırlar.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.imaging.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Bu `LinearGradientBrush` nesnesinin yerel geometrik dönüşümünü temsil eden `Aspose.Imaging.Matrix`'i, belirtilen `Aspose.Imaging.Matrix` ile ön ekleyerek çarpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Geometrik dönüşümü çarpmak için kullanılacak `Aspose.Imaging.Matrix`. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.imaging.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Bu `LinearGradientBrush` nesnesinin yerel geometrik dönüşümünü temsil eden `Aspose.Imaging.Matrix`'i, belirtilen sırada belirtilen `Aspose.Imaging.Matrix` ile çarpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Geometrik dönüşümü çarpmak için kullanılacak `Aspose.Imaging.Matrix`. |
| sıra | int | İki matrisi hangi sırada çarpacağını belirten bir `Aspose.Imaging.MatrixOrder`. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Yerel geometrik dönüşümü belirtilen boyutlarla çevirir. Bu yöntem çeviriyi dönüşüme ön ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dx | float | x eksenindeki çevirinin değeri. |
| dy | float | y eksenindeki çevirinin değeri. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Yerel geometrik dönüşümü belirtilen boyutlarla belirtilen sırada çevirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dx | float | x eksenindeki çevirinin değeri. |
| dy | float | y eksenindeki çevirinin değeri. |
| sıra | int | Çevirinin uygulanacağı sıra (ön ekleme veya ekleme). |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Yerel geometrik dönüşümü belirtilen miktarlarla ölçeklendirir. Bu yöntem ölçekleme matrisini dönüşüme ön ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sx | float | Dönüşümün x ekseni yönünde ölçekleneceği miktar. |
| sy | float | Dönüşümün y ekseni yönünde ölçekleneceği miktar. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Yerel geometrik dönüşümü belirtilen miktarlarla belirtilen sırada ölçeklendirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sx | float | Dönüşümün x ekseni yönünde ölçekleneceği miktar. |
| sy | float | Dönüşümün y ekseni yönünde ölçekleneceği miktar. |
| sıra | int | Ölçekleme matrisini ekleyecek mi yoksa ön ekleyecek mi olduğunu belirten bir `Aspose.Imaging.MatrixOrder`. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Yerel geometrik dönüşümü belirtilen miktarda döndürür. Bu yöntem rotasyonu dönüşüme ön ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| angle | float | Dönüş açısı. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Yerel geometrik dönüşümü belirtilen miktarda belirtilen sırada döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| angle | float | Dönüş açısı. |
| sıra | int | Rotasyon matrisini ekleyecek mi yoksa ön ekleyecek mi olduğunu belirten bir `Aspose.Imaging.MatrixOrder`. |

