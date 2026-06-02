---
title: "LinearMulticolorGradientBrush Sınıfı"
type: docs
weight: 40
url: /tr/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/
---

**Summary:** Represents a [Brush](/imaging/python-net/aspose.imaging/brush/) with linear gradient defined by multiple colors and appropriate positions. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.LinearMulticolorGradientBrush

**Inheritance:** LinearGradientBrushBase

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [LinearMulticolorGradientBrush()](#LinearMulticolorGradientBrush__1) | Yeni bir [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) sınıfının varsayılan parametrelerle bir örneğini başlatır.<br/>            Başlangıç rengi siyah, bitiş rengi beyaz, açı 45 derecedir ve dikdörtgen (0,0) konumunda, (1,1) boyutunda bulunur. |
| [LinearMulticolorGradientBrush(point1, point2)](#LinearMulticolorGradientBrush_point1_point2_2) | Belirtilen noktalarla yeni bir [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) sınıfının bir örneğini başlatır. |
| [LinearMulticolorGradientBrush(point1, point2)](#LinearMulticolorGradientBrush_point1_point2_3) | Belirtilen noktalarla yeni bir [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) sınıfının bir örneğini başlatır. |
| [LinearMulticolorGradientBrush(rect, angle)](#LinearMulticolorGradientBrush_rect_angle_4) | Bir dikdörtgen ve yön açısına dayalı olarak yeni bir [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) sınıfının bir örneğini başlatır. |
| [LinearMulticolorGradientBrush(rect, angle)](#LinearMulticolorGradientBrush_rect_angle_5) | Bir dikdörtgen ve yön açısına dayalı olarak yeni bir [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) sınıfının bir örneğini başlatır. |
| [LinearMulticolorGradientBrush(rect, angle, is_angle_scalable)](#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_6) | Bir dikdörtgen ve yön açısına dayalı olarak yeni bir [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) sınıfının bir örneğini başlatır. |
| [LinearMulticolorGradientBrush(rect, angle, is_angle_scalable)](#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_7) | Bir dikdörtgen ve yön açısına dayalı olarak yeni bir [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) sınıfının bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| angle | float | r/w | Gradyan açısını alır veya ayarlar. |
| dağıtıldı | bool | r | Bu örneğin dağıtılıp dağıtılmadığını gösteren bir değer alır. |
| gamma_correction | bool | r/w | Bu [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/) için gama düzeltmesinin etkin olup olmadığını gösteren bir değeri alır veya ayarlar. |
| interpolation_colors | [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | r/w | Çok renkli doğrusal bir gradyan tanımlayan bir [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) alır veya ayarlar. |
| is_angle_scalable | bool | r/w | Bu [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/) ile yapılan dönüşümler sırasında [LinearGradientBrushBase.angle](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/) değiştirildiğini gösteren bir değeri alır veya ayarlar. |
| is_transform_changed | bool | r | Dönüşümlerin bir şekilde değişip değişmediğini gösteren bir değeri alır. Örneğin dönüşüm matrisini ayarlamak veya<br/>            dönüşüm matrisini değiştiren herhangi bir yöntemi çağırmak. Özellik, GDI+ ile geriye uyumluluk sağlamak için eklenmiştir. |
| opacity | float | r/w | Fırça opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri fırçanın tamamen görünür olduğu, 1 değeri ise fırçanın tamamen opak olduğu anlamına gelir. |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Gradyanın başlangıç ve bitiş noktalarını tanımlayan bir dikdörtgen bölgeyi alır veya ayarlar. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Bu [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/) için yerel bir geometrik dönüşüm tanımlayan bir kopya [Matrix](/imaging/python-net/aspose.imaging/matrix/) alır veya ayarlar. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | Bu [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/) için sarma modunu gösteren bir [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) enumerasyonunu alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_with_points(point1, point2)](#create_with_points_point1_point2_1) | Belirtilen noktalarla yeni bir [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) sınıfının bir örneğini başlatır. |
| [create_with_points_f(point1, point2)](#create_with_points_f_point1_point2_2) | Belirtilen noktalarla yeni bir [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) sınıfının bir örneğini başlatır. |
| [create_with_rect(rect, angle)](#create_with_rect_rect_angle_3) | Bir dikdörtgen ve yön açısına dayalı olarak yeni bir [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) sınıfının bir örneğini başlatır. |
| [create_with_rect_angle_scalable(rect, angle, is_angle_scalable)](#create_with_rect_angle_scalable_rect_angle_is_angle_scalable_4) | Bir dikdörtgen ve yön açısına dayalı olarak yeni bir [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) sınıfının bir örneğini başlatır. |
| [create_with_rect_f(rect, angle)](#create_with_rect_f_rect_angle_5) | Bir dikdörtgen ve yön açısına dayalı olarak yeni bir [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) sınıfının bir örneğini başlatır. |
| [create_with_rect_f_angle_scalable(rect, angle, is_angle_scalable)](#create_with_rect_f_angle_scalable_rect_angle_is_angle_scalable_6) | Bir dikdörtgen ve yön açısına dayalı olarak yeni bir [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) sınıfının bir örneğini başlatır. |
| [deep_clone()](#deep_clone__7) | Mevcut [Brush](/imaging/python-net/aspose.imaging/brush/) nesnesinin yeni bir derin kopyasını oluşturur. |
| [multiply_transform(matrix)](#multiply_transform_matrix_8) | Bu [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) nesnesinin yerel geometrik dönüşümünü temsil eden [Matrix](/imaging/python-net/aspose.imaging/matrix/) belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) ile çarpar ve belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) ön eklenir. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_9) | Bu [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) nesnesinin yerel geometrik dönüşümünü temsil eden [Matrix](/imaging/python-net/aspose.imaging/matrix/) belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) ile belirtilen sırada çarpar. |
| reset_transform() | [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) özelliğini birim matrisine sıfırlar. |
| [rotate_transform(angle)](#rotate_transform_angle_10) | Yerel geometrik dönüşümü belirtilen miktarda döndürür. Bu yöntem döndürmeyi dönüşüme ön ekler. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_11) | Yerel geometrik dönüşümü belirtilen miktarda, belirtilen sırada döndürür. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_12) | Yerel geometrik dönüşümü belirtilen değerlerle ölçeklendirir. Bu yöntem ölçekleme matrisini dönüşüme ön ekler. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_13) | Yerel geometrik dönüşümü belirtilen değerlerle, belirtilen sırada ölçeklendirir. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_14) | Yerel geometrik dönüşümü belirtilen boyutlarla çevirir. Bu yöntem çeviriyi dönüşüme ön ekler. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_15) | Yerel geometrik dönüşümü belirtilen boyutlarla, belirtilen sırada çevirir. |


### Constructor: LinearMulticolorGradientBrush() {#LinearMulticolorGradientBrush__1}


```
 LinearMulticolorGradientBrush() 
```

Yeni bir [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) sınıfının varsayılan parametrelerle bir örneğini başlatır.<br/>            Başlangıç rengi siyah, bitiş rengi beyaz, açı 45 derecedir ve dikdörtgen (0,0) konumunda, (1,1) boyutunda bulunur.

### Constructor: LinearMulticolorGradientBrush(point1, point2) {#LinearMulticolorGradientBrush_point1_point2_2}


```
 LinearMulticolorGradientBrush(point1, point2) 
```

Belirtilen noktalarla yeni bir [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | Doğrusal degrade'nin başlangıç noktasını temsil eden bir [Point](/imaging/python-net/aspose.imaging/point/) yapısı. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | Doğrusal degrade'nin bitiş noktasını temsil eden bir [Point](/imaging/python-net/aspose.imaging/point/) yapısı. |

### Constructor: LinearMulticolorGradientBrush(point1, point2) {#LinearMulticolorGradientBrush_point1_point2_3}


```
 LinearMulticolorGradientBrush(point1, point2) 
```

Belirtilen noktalarla yeni bir [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Doğrusal degrade'nin başlangıç noktasını temsil eden bir [Point](/imaging/python-net/aspose.imaging/point/) yapısı. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Doğrusal degrade'nin bitiş noktasını temsil eden bir [Point](/imaging/python-net/aspose.imaging/point/) yapısı. |

### Constructor: LinearMulticolorGradientBrush(rect, angle) {#LinearMulticolorGradientBrush_rect_angle_4}


```
 LinearMulticolorGradientBrush(rect, angle) 
```

Bir dikdörtgen ve yön açısına dayalı olarak yeni bir [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Doğrusal degrade'nin sınırlarını belirten bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı. |
| angle | float | Degrade yön çizgisinin, x ekseninden saat yönünde derece cinsinden ölçülen açısı. |

### Constructor: LinearMulticolorGradientBrush(rect, angle) {#LinearMulticolorGradientBrush_rect_angle_5}


```
 LinearMulticolorGradientBrush(rect, angle) 
```

Bir dikdörtgen ve yön açısına dayalı olarak yeni bir [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Doğrusal degrade'nin sınırlarını belirten bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı. |
| angle | float | Degrade yön çizgisinin, x ekseninden saat yönünde derece cinsinden ölçülen açısı. |

### Constructor: LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) {#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_6}


```
 LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) 
```

Bir dikdörtgen ve yön açısına dayalı olarak yeni bir [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Doğrusal degrade'nin sınırlarını belirten bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı. |
| angle | float | Degrade yön çizgisinin, x ekseninden saat yönünde derece cinsinden ölçülen açısı. |
| is_angle_scalable | bool | eğer <c>true</c> olarak ayarlanırsa açı, bu [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) ile yapılan dönüşümler sırasında değiştirilir. |

### Constructor: LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) {#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_7}


```
 LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) 
```

Bir dikdörtgen ve yön açısına dayalı olarak yeni bir [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Doğrusal degrade'nin sınırlarını belirten bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı. |
| angle | float | Degrade yön çizgisinin, x ekseninden saat yönünde derece cinsinden ölçülen açısı. |
| is_angle_scalable | bool | eğer <c>true</c> olarak ayarlanırsa açı, bu [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) ile yapılan dönüşümler sırasında değiştirilir. |

### Method: create_with_points(point1, point2)  [static] {#create_with_points_point1_point2_1}


```
 create_with_points(point1, point2) 
```

Belirtilen noktalarla yeni bir [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | Doğrusal degrade'nin başlangıç noktasını temsil eden bir [Point](/imaging/python-net/aspose.imaging/point/) yapısı. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | Doğrusal degrade'nin bitiş noktasını temsil eden bir [Point](/imaging/python-net/aspose.imaging/point/) yapısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) |  |


### Method: create_with_points_f(point1, point2)  [static] {#create_with_points_f_point1_point2_2}


```
 create_with_points_f(point1, point2) 
```

Belirtilen noktalarla yeni bir [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Doğrusal degrade'nin başlangıç noktasını temsil eden bir [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Doğrusal degrade'nin bitiş noktasını temsil eden bir [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) |  |


### Method: create_with_rect(rect, angle)  [static] {#create_with_rect_rect_angle_3}


```
 create_with_rect(rect, angle) 
```

Bir dikdörtgen ve yön açısına dayalı olarak yeni bir [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Doğrusal degrade'nin sınırlarını belirten bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı. |
| angle | float | Degrade yön çizgisinin, x ekseninden saat yönünde derece cinsinden ölçülen açısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) |  |


### Method: create_with_rect_angle_scalable(rect, angle, is_angle_scalable)  [static] {#create_with_rect_angle_scalable_rect_angle_is_angle_scalable_4}


```
 create_with_rect_angle_scalable(rect, angle, is_angle_scalable) 
```

Bir dikdörtgen ve yön açısına dayalı olarak yeni bir [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Doğrusal degrade'nin sınırlarını belirten bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı. |
| angle | float | Degrade yön çizgisinin, x ekseninden saat yönünde derece cinsinden ölçülen açısı. |
| is_angle_scalable | bool | eğer <c>true</c> olarak ayarlanırsa açı, bu [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) ile yapılan dönüşümler sırasında değiştirilir. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) |  |


### Method: create_with_rect_f(rect, angle)  [static] {#create_with_rect_f_rect_angle_5}


```
 create_with_rect_f(rect, angle) 
```

Bir dikdörtgen ve yön açısına dayalı olarak yeni bir [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Doğrusal degrade'nin sınırlarını belirten bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı. |
| angle | float | Degrade yön çizgisinin, x ekseninden saat yönünde derece cinsinden ölçülen açısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) |  |


### Method: create_with_rect_f_angle_scalable(rect, angle, is_angle_scalable)  [static] {#create_with_rect_f_angle_scalable_rect_angle_is_angle_scalable_6}


```
 create_with_rect_f_angle_scalable(rect, angle, is_angle_scalable) 
```

Bir dikdörtgen ve yön açısına dayalı olarak yeni bir [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Doğrusal degrade'nin sınırlarını belirten bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı. |
| angle | float | Degrade yön çizgisinin, x ekseninden saat yönünde derece cinsinden ölçülen açısı. |
| is_angle_scalable | bool | eğer <c>true</c> olarak ayarlanırsa açı, bu [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) ile yapılan dönüşümler sırasında değiştirilir. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [LinearMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/linearmulticolorgradientbrush/) |  |


### Method: deep_clone() {#deep_clone__7}


```
 deep_clone() 
```

Mevcut [Brush](/imaging/python-net/aspose.imaging/brush/) nesnesinin yeni bir derin kopyasını oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | Bu [Brush](/imaging/python-net/aspose.imaging/brush/) örneğinin derin kopyası olan yeni bir [Brush](/imaging/python-net/aspose.imaging/brush/). |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_8}


```
 multiply_transform(matrix) 
```

Bu [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) nesnesinin yerel geometrik dönüşümünü temsil eden [Matrix](/imaging/python-net/aspose.imaging/matrix/) belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) ile çarpar ve belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) ön eklenir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Geometrik dönüşümü çarpmak için kullanılacak [Matrix](/imaging/python-net/aspose.imaging/matrix/). |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_9}


```
 multiply_transform(matrix, order) 
```

Bu [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) nesnesinin yerel geometrik dönüşümünü temsil eden [Matrix](/imaging/python-net/aspose.imaging/matrix/) belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) ile belirtilen sırada çarpar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Geometrik dönüşümü çarpmak için kullanılacak [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | İki matrisi hangi sırada çarpacağını belirten bir [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/). |

### Method: rotate_transform(angle) {#rotate_transform_angle_10}


```
 rotate_transform(angle) 
```

Yerel geometrik dönüşümü belirtilen miktarda döndürür. Bu yöntem döndürmeyi dönüşüme ön ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| angle | float | Dönüş açısı. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_11}


```
 rotate_transform(angle, order) 
```

Yerel geometrik dönüşümü belirtilen miktarda, belirtilen sırada döndürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| angle | float | Dönüş açısı. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Dönüşüm matrisini ekleyecek mi yoksa ön ekleyecek mi olduğunu belirten bir [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/). |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_12}


```
 scale_transform(sx, sy) 
```

Yerel geometrik dönüşümü belirtilen değerlerle ölçeklendirir. Bu yöntem ölçekleme matrisini dönüşüme ön ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| sx | float | Dönüşümün x ekseni yönündeki ölçekleme miktarı. |
| sy | float | Dönüşümün y ekseni yönündeki ölçekleme miktarı. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_13}


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

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_14}


```
 translate_transform(dx, dy) 
```

Yerel geometrik dönüşümü belirtilen boyutlarla çevirir. Bu yöntem çeviriyi dönüşüme ön ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dx | float | x eksenindeki çevirmenin değeri. |
| dy | float | y eksenindeki çevirmenin değeri. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_15}


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

