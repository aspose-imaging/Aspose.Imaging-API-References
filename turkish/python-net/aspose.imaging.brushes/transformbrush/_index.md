---
title: "TransformBrush Sınıfı"
type: docs
weight: 100
url: /tr/python-net/aspose.imaging.brushes/transformbrush/
---

**Summary:** A [Brush](/imaging/python-net/aspose.imaging/brush/) with transform capabilities.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.TransformBrush

**Inheritance:** Brush

## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| dağıtıldı | bool | r | Bu örneğin dağıtılıp dağıtılmadığını gösteren bir değer alır. |
| is_transform_changed | bool | r | Dönüşümlerin bir şekilde değişip değişmediğini gösteren bir değeri alır. Örneğin dönüşüm matrisini ayarlamak veya<br/>            dönüşüm matrisini değiştiren herhangi bir yöntemi çağırmak. Özellik, GDI+ ile geriye uyumluluk sağlamak için eklenmiştir. |
| opacity | float | r/w | Fırça opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri fırçanın tamamen görünür olduğu, 1 değeri ise fırçanın tamamen opak olduğu anlamına gelir. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Bu [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/) için yerel bir geometrik dönüşüm tanımlayan bir kopya [Matrix](/imaging/python-net/aspose.imaging/matrix/) alır veya ayarlar. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | Bu [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/) için sarma modunu gösteren bir [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) enumerasyonunu alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Mevcut [Brush](/imaging/python-net/aspose.imaging/brush/) nesnesinin yeni bir derin kopyasını oluşturur. |
| [multiply_transform(matrix)](#multiply_transform_matrix_2) | Bu [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) nesnesinin yerel geometrik dönüşümünü temsil eden [Matrix](/imaging/python-net/aspose.imaging/matrix/) belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) ile çarpar ve belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) ön eklenir. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_3) | Bu [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) nesnesinin yerel geometrik dönüşümünü temsil eden [Matrix](/imaging/python-net/aspose.imaging/matrix/) belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) ile belirtilen sırada çarpar. |
| reset_transform() | [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) özelliğini birim matrisine sıfırlar. |
| [rotate_transform(angle)](#rotate_transform_angle_4) | Yerel geometrik dönüşümü belirtilen miktarda döndürür. Bu yöntem döndürmeyi dönüşüme ön ekler. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_5) | Yerel geometrik dönüşümü belirtilen miktarda, belirtilen sırada döndürür. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_6) | Yerel geometrik dönüşümü belirtilen değerlerle ölçeklendirir. Bu yöntem ölçekleme matrisini dönüşüme ön ekler. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_7) | Yerel geometrik dönüşümü belirtilen değerlerle, belirtilen sırada ölçeklendirir. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | Yerel geometrik dönüşümü belirtilen boyutlarla çevirir. Bu yöntem çeviriyi dönüşüme ön ekler. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | Yerel geometrik dönüşümü belirtilen boyutlarla, belirtilen sırada çevirir. |


### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Mevcut [Brush](/imaging/python-net/aspose.imaging/brush/) nesnesinin yeni bir derin kopyasını oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | Bu [Brush](/imaging/python-net/aspose.imaging/brush/) örneğinin derin kopyası olan yeni bir [Brush](/imaging/python-net/aspose.imaging/brush/). |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_2}


```
 multiply_transform(matrix) 
```

Bu [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) nesnesinin yerel geometrik dönüşümünü temsil eden [Matrix](/imaging/python-net/aspose.imaging/matrix/) belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) ile çarpar ve belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) ön eklenir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Geometrik dönüşümü çarpmak için kullanılacak [Matrix](/imaging/python-net/aspose.imaging/matrix/). |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_3}


```
 multiply_transform(matrix, order) 
```

Bu [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) nesnesinin yerel geometrik dönüşümünü temsil eden [Matrix](/imaging/python-net/aspose.imaging/matrix/) belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) ile belirtilen sırada çarpar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Geometrik dönüşümü çarpmak için kullanılacak [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | İki matrisi hangi sırada çarpacağını belirten bir [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/). |

### Method: rotate_transform(angle) {#rotate_transform_angle_4}


```
 rotate_transform(angle) 
```

Yerel geometrik dönüşümü belirtilen miktarda döndürür. Bu yöntem döndürmeyi dönüşüme ön ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| angle | float | Dönüş açısı. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_5}


```
 rotate_transform(angle, order) 
```

Yerel geometrik dönüşümü belirtilen miktarda, belirtilen sırada döndürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| angle | float | Dönüş açısı. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Dönüşüm matrisini ekleyecek mi yoksa ön ekleyecek mi olduğunu belirten bir [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/). |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_6}


```
 scale_transform(sx, sy) 
```

Yerel geometrik dönüşümü belirtilen değerlerle ölçeklendirir. Bu yöntem ölçekleme matrisini dönüşüme ön ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| sx | float | Dönüşümün x ekseni yönündeki ölçekleme miktarı. |
| sy | float | Dönüşümün y ekseni yönündeki ölçekleme miktarı. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_7}


```
 scale_transform(sx, sy, order) 
```

Yerel geometrik dönüşümü belirtilen değerlerle, belirtilen sırada ölçeklendirir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| sx | float | Dönüşümün x ekseni yönündeki ölçekleme miktarı. |
| sy | float | Dönüşümün y ekseni yönündeki ölçekleme miktarı. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Ölçekleme matrisini ekleme ya da başına ekleme belirten bir [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/). |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

Yerel geometrik dönüşümü belirtilen boyutlarla çevirir. Bu yöntem çeviriyi dönüşüme ön ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dx | float | x eksenindeki çevirmenin değeri. |
| dy | float | y eksenindeki çevirmenin değeri. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


```
 translate_transform(dx, dy, order) 
```

Yerel geometrik dönüşümü belirtilen boyutlarla, belirtilen sırada çevirir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dx | float | x eksenindeki çevirmenin değeri. |
| dy | float | y eksenindeki çevirmenin değeri. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Çevirmenin uygulanacağı sıra (başına ekleme ya da ekleme). |

