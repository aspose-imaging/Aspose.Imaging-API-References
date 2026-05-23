---
title: "LinearGradientBrush Sınıfı"
type: docs
weight: 20
url: /tr/python-net/aspose.imaging.brushes/lineargradientbrush/
---

**Summary:** Encapsulates a [Brush](/imaging/python-net/aspose.imaging/brush/) with a linear gradient. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.LinearGradientBrush

**Inheritance:** LinearGradientBrushBase

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [LinearGradientBrush()](#LinearGradientBrush__1) | Yeni bir [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) sınıfının örneğini varsayılan parametrelerle başlatır.<br/>            Başlangıç rengi siyahtır, bitiş rengi beyazdır, açı 45 derecedir ve dikdörtgen (0,0) konumunda, (1,1) boyutundadır. |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_2) | Yeni bir [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) sınıfının örneğini başlatır. |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_3) | Yeni bir [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) sınıfının örneğini başlatır. |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_4) | Yeni bir [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) sınıfının örneğini başlatır. |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_5) | Yeni bir [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) sınıfının örneğini başlatır. |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6) | Yeni bir [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) sınıfının örneğini başlatır. |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7) | Yeni bir [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| angle | float | r/w | Gradyan açısını alır veya ayarlar. |
| blend | [Blend](/imaging/python-net/aspose.imaging/blend/) | r/w | Gradyan için özel bir düşüş tanımlayan konumları ve faktörleri belirten bir [Blend](/imaging/python-net/aspose.imaging/blend/) alır veya ayarlar. |
| dağıtıldı | bool | r | Bu örneğin dağıtılıp dağıtılmadığını gösteren bir değer alır. |
| end_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Bitiş gradyan rengini alır veya ayarlar. |
| gamma_correction | bool | r/w | Bu [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/) için gama düzeltmesinin etkin olup olmadığını gösteren bir değeri alır veya ayarlar. |
| interpolation_colors | [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | r/w | Çok renkli doğrusal bir gradyan tanımlayan bir [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) alır veya ayarlar. |
| is_angle_scalable | bool | r/w | Bu [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/) ile yapılan dönüşümler sırasında [LinearGradientBrushBase.angle](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/) değiştirildiğini gösteren bir değeri alır veya ayarlar. |
| is_transform_changed | bool | r | Dönüşümlerin bir şekilde değişip değişmediğini gösteren bir değeri alır. Örneğin dönüşüm matrisini ayarlamak veya<br/>            dönüşüm matrisini değiştiren herhangi bir yöntemi çağırmak. Özellik, GDI+ ile geriye uyumluluk sağlamak için eklenmiştir. |
| linear_colors | [Color[]](/imaging/python-net/aspose.imaging/color/) | r/w | Gradyanın başlangıç ve bitiş renklerini alır veya ayarlar. |
| opacity | float | r/w | Fırça opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri fırçanın tamamen görünür olduğu, 1 değeri ise fırçanın tamamen opak olduğu anlamına gelir. |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Gradyanın başlangıç ve bitiş noktalarını tanımlayan bir dikdörtgen bölgeyi alır veya ayarlar. |
| start_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Başlangıç gradyan rengini alır veya ayarlar. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Bu [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/) için yerel bir geometrik dönüşüm tanımlayan bir kopya [Matrix](/imaging/python-net/aspose.imaging/matrix/) alır veya ayarlar. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | Bu [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/) için sarma modunu gösteren bir [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) enumerasyonunu alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_with_points(point1, point2, color1, color2)](#create_with_points_point1_point2_color1_color2_1) | Belirtilen noktalar ve renklerle yeni bir [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) sınıfının örneğini başlatır. |
| [create_with_points_f(point1, point2, color1, color2)](#create_with_points_f_point1_point2_color1_color2_2) | Belirtilen noktalar ve renklerle yeni bir [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) sınıfının örneğini başlatır. |
| [create_with_rect_colors_angle(rect, color1, color2, angle)](#create_with_rect_colors_angle_rect_color1_color2_angle_3) | Bir dikdörtgen, başlangıç ve bitiş renkleri ve bir yön açısına dayalı olarak yeni bir [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) sınıfının örneğini başlatır. |
| [create_with_rect_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)](#create_with_rect_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_4) | Bir dikdörtgen, başlangıç ve bitiş renkleri ve bir yön açısına dayalı olarak yeni bir [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) sınıfının örneğini başlatır. |
| [create_with_rect_f_colors_angle(rect, color1, color2, angle)](#create_with_rect_f_colors_angle_rect_color1_color2_angle_5) | Bir dikdörtgen, başlangıç ve bitiş renkleri ve bir yön açısına dayalı olarak yeni bir [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) sınıfının örneğini başlatır. |
| [create_with_rect_f_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)](#create_with_rect_f_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_6) | Bir dikdörtgen, başlangıç ve bitiş renkleri ve bir yön açısına dayalı olarak yeni bir [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) sınıfının örneğini başlatır. |
| [deep_clone()](#deep_clone__7) | Mevcut [Brush](/imaging/python-net/aspose.imaging/brush/) nesnesinin yeni bir derin kopyasını oluşturur. |
| [multiply_transform(matrix)](#multiply_transform_matrix_8) | Bu [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) nesnesinin yerel geometrik dönüşümünü temsil eden [Matrix](/imaging/python-net/aspose.imaging/matrix/) belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) ile çarpar ve belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) ön eklenir. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_9) | Bu [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) nesnesinin yerel geometrik dönüşümünü temsil eden [Matrix](/imaging/python-net/aspose.imaging/matrix/) belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) ile belirtilen sırada çarpar. |
| reset_transform() | [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) özelliğini birim matrisine sıfırlar. |
| [rotate_transform(angle)](#rotate_transform_angle_10) | Yerel geometrik dönüşümü belirtilen miktarda döndürür. Bu yöntem döndürmeyi dönüşüme ön ekler. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_11) | Yerel geometrik dönüşümü belirtilen miktarda, belirtilen sırada döndürür. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_12) | Yerel geometrik dönüşümü belirtilen değerlerle ölçeklendirir. Bu yöntem ölçekleme matrisini dönüşüme ön ekler. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_13) | Yerel geometrik dönüşümü belirtilen değerlerle, belirtilen sırada ölçeklendirir. |
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_14) | Ortadaki renk ve her iki uçta tek bir renge doğru lineer bir düşüş içeren bir lineer gradyan oluşturur. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_15) | Ortadaki renk ve her iki uçta tek bir renge doğru lineer bir düşüş içeren bir lineer gradyan oluşturur. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_16) | Çan şeklinde bir eğriye dayalı bir gradyan düşüşü oluşturur. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_17) | Çan şeklinde bir eğriye dayalı bir gradyan düşüşü oluşturur. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_18) | Yerel geometrik dönüşümü belirtilen boyutlarla çevirir. Bu yöntem çeviriyi dönüşüme ön ekler. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_19) | Yerel geometrik dönüşümü belirtilen boyutlarla, belirtilen sırada çevirir. |


### Constructor: LinearGradientBrush() {#LinearGradientBrush__1}


```
 LinearGradientBrush() 
```

Yeni bir [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) sınıfının örneğini varsayılan parametrelerle başlatır.<br/>            Başlangıç rengi siyahtır, bitiş rengi beyazdır, açı 45 derecedir ve dikdörtgen (0,0) konumunda, (1,1) boyutundadır.

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_2}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Yeni bir [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Nokta1. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Nokta2. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Renk1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Renk2. |

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_3}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Yeni bir [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | Nokta1. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | Nokta2. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Renk1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Renk2. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_4}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Yeni bir [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Dikdörtgen. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Renk1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Renk2. |
| angle | float | Açı. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_5}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Yeni bir [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Dikdörtgen. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Renk1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Renk2. |
| angle | float | Açı. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Yeni bir [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Dikdörtgen. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Renk1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Renk2. |
| angle | float | Açı. |
| is_angle_scalable | bool | eğer <c>true</c> olarak ayarlanırsa [açı ölçeklenebilir]. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Yeni bir [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Dikdörtgen. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Renk1. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Renk2. |
| angle | float | Açı. |
| is_angle_scalable | bool | eğer <c>true</c> olarak ayarlanırsa [açı ölçeklenebilir]. |

### Method: create_with_points(point1, point2, color1, color2)  [static] {#create_with_points_point1_point2_color1_color2_1}


```
 create_with_points(point1, point2, color1, color2) 
```

Belirtilen noktalar ve renklerle yeni bir [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| point1 | [Point](/imaging/python-net/aspose.imaging/point/) | Doğrusal degrade'nin başlangıç noktasını temsil eden bir [Point](/imaging/python-net/aspose.imaging/point/) yapısı. |
| point2 | [Point](/imaging/python-net/aspose.imaging/point/) | Doğrusal degrade'nin bitiş noktasını temsil eden bir [Point](/imaging/python-net/aspose.imaging/point/) yapısı. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Doğrusal degrade'nin başlangıç rengini temsil eden bir [Color](/imaging/python-net/aspose.imaging/color/) yapısı. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Doğrusal degrade'nin bitiş rengini temsil eden bir [Color](/imaging/python-net/aspose.imaging/color/) yapısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_points_f(point1, point2, color1, color2)  [static] {#create_with_points_f_point1_point2_color1_color2_2}


```
 create_with_points_f(point1, point2, color1, color2) 
```

Belirtilen noktalar ve renklerle yeni bir [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| point1 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Doğrusal degrade'nin başlangıç noktasını temsil eden bir [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı. |
| point2 | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Doğrusal degrade'nin bitiş noktasını temsil eden bir [PointF](/imaging/python-net/aspose.imaging/pointf/) yapısı. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Doğrusal degrade'nin başlangıç rengini temsil eden bir [Color](/imaging/python-net/aspose.imaging/color/) yapısı. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Doğrusal degrade'nin bitiş rengini temsil eden bir [Color](/imaging/python-net/aspose.imaging/color/) yapısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_colors_angle(rect, color1, color2, angle)  [static] {#create_with_rect_colors_angle_rect_color1_color2_angle_3}


```
 create_with_rect_colors_angle(rect, color1, color2, angle) 
```

Bir dikdörtgen, başlangıç ve bitiş renkleri ve bir yön açısına dayalı olarak yeni bir [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Doğrusal degrade'nin sınırlarını belirten bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Degrade için başlangıç rengini temsil eden bir [Color](/imaging/python-net/aspose.imaging/color/) yapısı. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Degrade için bitiş rengini temsil eden bir [Color](/imaging/python-net/aspose.imaging/color/) yapısı. |
| angle | float | Degrade yön çizgisinin, x ekseninden saat yönünde derece cinsinden ölçülen açısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)  [static] {#create_with_rect_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_4}


```
 create_with_rect_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable) 
```

Bir dikdörtgen, başlangıç ve bitiş renkleri ve bir yön açısına dayalı olarak yeni bir [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Doğrusal degrade'nin sınırlarını belirten bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Degrade için başlangıç rengini temsil eden bir [Color](/imaging/python-net/aspose.imaging/color/) yapısı. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Degrade için bitiş rengini temsil eden bir [Color](/imaging/python-net/aspose.imaging/color/) yapısı. |
| angle | float | Degrade yön çizgisinin, x ekseninden saat yönünde derece cinsinden ölçülen açısı. |
| is_angle_scalable | bool | eğer <c>true</c> olarak ayarlanırsa açı, bu [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) ile dönüşümler sırasında değiştirilir. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_f_colors_angle(rect, color1, color2, angle)  [static] {#create_with_rect_f_colors_angle_rect_color1_color2_angle_5}


```
 create_with_rect_f_colors_angle(rect, color1, color2, angle) 
```

Bir dikdörtgen, başlangıç ve bitiş renkleri ve bir yön açısına dayalı olarak yeni bir [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Doğrusal degrade'nin sınırlarını belirten bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Degrade için başlangıç rengini temsil eden bir [Color](/imaging/python-net/aspose.imaging/color/) yapısı. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Degrade için bitiş rengini temsil eden bir [Color](/imaging/python-net/aspose.imaging/color/) yapısı. |
| angle | float | Degrade yön çizgisinin, x ekseninden saat yönünde derece cinsinden ölçülen açısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


### Method: create_with_rect_f_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)  [static] {#create_with_rect_f_colors_angle_scalable_rect_color1_color2_angle_is_angle_scalable_6}


```
 create_with_rect_f_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable) 
```

Bir dikdörtgen, başlangıç ve bitiş renkleri ve bir yön açısına dayalı olarak yeni bir [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Doğrusal degrade'nin sınırlarını belirten bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı. |
| color1 | [Color](/imaging/python-net/aspose.imaging/color/) | Degrade için başlangıç rengini temsil eden bir [Color](/imaging/python-net/aspose.imaging/color/) yapısı. |
| color2 | [Color](/imaging/python-net/aspose.imaging/color/) | Degrade için bitiş rengini temsil eden bir [Color](/imaging/python-net/aspose.imaging/color/) yapısı. |
| angle | float | Degrade yön çizgisinin, x ekseninden saat yönünde derece cinsinden ölçülen açısı. |
| is_angle_scalable | bool | eğer <c>true</c> olarak ayarlanırsa açı, bu [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) ile dönüşümler sırasında değiştirilir. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) |  |


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

### Method: set_blend_triangular_shape(focus) {#set_blend_triangular_shape_focus_14}


```
 set_blend_triangular_shape(focus) 
```

Ortadaki renk ve her iki uçta tek bir renge doğru lineer bir düşüş içeren bir lineer gradyan oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| odak | float | 0 ile 1 arasında bir değer ve degrade'nin merkezini (degrade'nin yalnızca bitiş renginden oluştuğu nokta) belirler. |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_15}


```
 set_blend_triangular_shape(focus, scale) 
```

Ortadaki renk ve her iki uçta tek bir renge doğru lineer bir düşüş içeren bir lineer gradyan oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| odak | float | 0 ile 1 arasında bir değer ve degrade'nin merkezini (degrade'nin yalnızca bitiş renginden oluştuğu nokta) belirler. |
| ölçek | float | 0 ile 1 arasında bir değer ve renklerin başlangıç renginden _focus_'a (bitiş rengine) ne kadar hızlı azaldığını belirler. |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_16}


```
 set_sigma_bell_shape(focus) 
```

Çan şeklinde bir eğriye dayalı bir gradyan düşüşü oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| odak | float | 0 ile 1 arasında bir değer ve degrade'nin merkezini (başlangıç rengi ile bitiş renginin eşit şekilde karıştığı nokta) belirler. |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_17}


```
 set_sigma_bell_shape(focus, scale) 
```

Çan şeklinde bir eğriye dayalı bir gradyan düşüşü oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| odak | float | 0 ile 1 arasında bir değer ve degrade'nin merkezini (degrade'nin yalnızca bitiş renginden oluştuğu nokta) belirler. |
| ölçek | float | 0 ile 1 arasında bir değer ve renklerin _focus_'dan ne kadar hızlı azaldığını belirler. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_18}


```
 translate_transform(dx, dy) 
```

Yerel geometrik dönüşümü belirtilen boyutlarla çevirir. Bu yöntem çeviriyi dönüşüme ön ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dx | float | x eksenindeki çevirmenin değeri. |
| dy | float | y eksenindeki çevirmenin değeri. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_19}


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

