---
title: "PathMulticolorGradientBrush Sınıfı"
type: docs
weight: 70
url: /tr/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/
---

**Summary:** Encapsulates a [Brush](/imaging/python-net/aspose.imaging/brush/) object with a gradient. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.PathMulticolorGradientBrush

**Inheritance:** PathGradientBrushBase

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [PathMulticolorGradientBrush(path)](#PathMulticolorGradientBrush_path_1) | Belirtilen noktalarla [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) sınıfının yeni bir örneğini başlatır. |
| [PathMulticolorGradientBrush(path_points)](#PathMulticolorGradientBrush_path_points_2) | Belirtilen noktalarla [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) sınıfının yeni bir örneğini başlatır. |
| [PathMulticolorGradientBrush(path_points)](#PathMulticolorGradientBrush_path_points_3) | Belirtilen noktalarla [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) sınıfının yeni bir örneğini başlatır. |
| [PathMulticolorGradientBrush(path_points, wrap_mode)](#PathMulticolorGradientBrush_path_points_wrap_mode_4) | Belirtilen noktalar ve sarma modu ile [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) sınıfının yeni bir örneğini başlatır. |
| [PathMulticolorGradientBrush(path_points, wrap_mode)](#PathMulticolorGradientBrush_path_points_wrap_mode_5) | Belirtilen noktalar ve sarma modu ile [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| center_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Yol gradyanının merkez noktasını alır veya ayarlar. |
| dağıtıldı | bool | r | Bu örneğin dağıtılıp dağıtılmadığını gösteren bir değer alır. |
| focus_scales | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Gradyan düşüşü için odak noktasını alır veya ayarlar. |
| graphics_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r | Bu fırçanın üzerine inşa edildiği grafik yolunu alır. |
| interpolation_colors | [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | r/w | Çok renkli doğrusal bir gradyan tanımlayan bir [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) alır veya ayarlar. |
| is_transform_changed | bool | r | Dönüşümlerin bir şekilde değişip değişmediğini gösteren bir değeri alır. Örneğin dönüşüm matrisini ayarlamak veya<br/>            dönüşüm matrisini değiştiren herhangi bir yöntemi çağırmak. Özellik, GDI+ ile geriye uyumluluk sağlamak için eklenmiştir. |
| opacity | float | r/w | Fırça opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri fırçanın tamamen görünür olduğu, 1 değeri ise fırçanın tamamen opak olduğu anlamına gelir. |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r | Bu fırçanın üzerine inşa edildiği yol noktalarını alır. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Bu [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/) için yerel bir geometrik dönüşüm tanımlayan bir kopya [Matrix](/imaging/python-net/aspose.imaging/matrix/) alır veya ayarlar. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | Bu [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/) için sarma modunu gösteren bir [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) enumerasyonunu alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_with_path(path)](#create_with_path_path_1) | Belirtilen yol ile [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) sınıfının yeni bir örneğini başlatır. |
| [create_with_points(path_points)](#create_with_points_path_points_2) | Belirtilen noktalarla [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) sınıfının yeni bir örneğini başlatır. |
| [create_with_points_f(path_points)](#create_with_points_f_path_points_3) | Belirtilen noktalarla [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) sınıfının yeni bir örneğini başlatır. |
| [create_with_points_f_wrap_mode(path_points, wrap_mode)](#create_with_points_f_wrap_mode_path_points_wrap_mode_4) | Belirtilen noktalar ve sarma modu ile [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) sınıfının yeni bir örneğini başlatır. |
| [create_with_points_wrap_mode(path_points, wrap_mode)](#create_with_points_wrap_mode_path_points_wrap_mode_5) | Belirtilen noktalar ve sarma modu ile [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) sınıfının yeni bir örneğini başlatır. |
| [deep_clone()](#deep_clone__6) | Mevcut [Brush](/imaging/python-net/aspose.imaging/brush/) nesnesinin yeni bir derin kopyasını oluşturur. |
| [multiply_transform(matrix)](#multiply_transform_matrix_7) | Bu [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) nesnesinin yerel geometrik dönüşümünü temsil eden [Matrix](/imaging/python-net/aspose.imaging/matrix/) belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) ile çarpar ve belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) ön eklenir. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_8) | Bu [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) nesnesinin yerel geometrik dönüşümünü temsil eden [Matrix](/imaging/python-net/aspose.imaging/matrix/) belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) ile belirtilen sırada çarpar. |
| reset_transform() | [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) özelliğini birim matrisine sıfırlar. |
| [rotate_transform(angle)](#rotate_transform_angle_9) | Yerel geometrik dönüşümü belirtilen miktarda döndürür. Bu yöntem döndürmeyi dönüşüme ön ekler. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_10) | Yerel geometrik dönüşümü belirtilen miktarda, belirtilen sırada döndürür. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_11) | Yerel geometrik dönüşümü belirtilen değerlerle ölçeklendirir. Bu yöntem ölçekleme matrisini dönüşüme ön ekler. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_12) | Yerel geometrik dönüşümü belirtilen değerlerle, belirtilen sırada ölçeklendirir. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_13) | Yerel geometrik dönüşümü belirtilen boyutlarla çevirir. Bu yöntem çeviriyi dönüşüme ön ekler. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_14) | Yerel geometrik dönüşümü belirtilen boyutlarla, belirtilen sırada çevirir. |


### Constructor: PathMulticolorGradientBrush(path) {#PathMulticolorGradientBrush_path_1}


```
 PathMulticolorGradientBrush(path) 
```

Belirtilen noktalarla [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) |  |

### Constructor: PathMulticolorGradientBrush(path_points) {#PathMulticolorGradientBrush_path_points_2}


```
 PathMulticolorGradientBrush(path_points) 
```

Belirtilen noktalarla [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Yolun köşe noktalarını oluşturan noktaları temsil eden bir [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıları dizisi. |

### Constructor: PathMulticolorGradientBrush(path_points) {#PathMulticolorGradientBrush_path_points_3}


```
 PathMulticolorGradientBrush(path_points) 
```

Belirtilen noktalarla [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Yolun köşe noktalarını oluşturan noktaları temsil eden bir [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıları dizisi. |

### Constructor: PathMulticolorGradientBrush(path_points, wrap_mode) {#PathMulticolorGradientBrush_path_points_wrap_mode_4}


```
 PathMulticolorGradientBrush(path_points, wrap_mode) 
```

Belirtilen noktalar ve sarma modu ile [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Yolun köşe noktalarını oluşturan noktaları temsil eden bir [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıları dizisi. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Bu [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) ile çizilen doldurmaların nasıl döşeneceğini belirten bir [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/). |

### Constructor: PathMulticolorGradientBrush(path_points, wrap_mode) {#PathMulticolorGradientBrush_path_points_wrap_mode_5}


```
 PathMulticolorGradientBrush(path_points, wrap_mode) 
```

Belirtilen noktalar ve sarma modu ile [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Yolun köşe noktalarını oluşturan noktaları temsil eden bir [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıları dizisi. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Bu [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) ile çizilen doldurmaların nasıl döşeneceğini belirten bir [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/). |

### Method: create_with_path(path)  [static] {#create_with_path_path_1}


```
 create_with_path(path) 
```

Belirtilen yol ile [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) tarafından doldurulan alanı tanımlayan [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) |  |


### Method: create_with_points(path_points)  [static] {#create_with_points_path_points_2}


```
 create_with_points(path_points) 
```

Belirtilen noktalarla [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Yolun köşe noktalarını oluşturan noktaları temsil eden bir [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıları dizisi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) |  |


### Method: create_with_points_f(path_points)  [static] {#create_with_points_f_path_points_3}


```
 create_with_points_f(path_points) 
```

Belirtilen noktalarla [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Yolun köşe noktalarını oluşturan noktaları temsil eden bir [Point](/imaging/python-net/aspose.imaging/point/) yapıları dizisi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) |  |


### Method: create_with_points_f_wrap_mode(path_points, wrap_mode)  [static] {#create_with_points_f_wrap_mode_path_points_wrap_mode_4}


```
 create_with_points_f_wrap_mode(path_points, wrap_mode) 
```

Belirtilen noktalar ve sarma modu ile [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Yolun köşe noktalarını oluşturan noktaları temsil eden bir [PointF](/imaging/python-net/aspose.imaging/pointf/) yapıları dizisi. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Bu [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) ile çizilen doldurmaların nasıl döşeneceğini belirten bir [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) |  |


### Method: create_with_points_wrap_mode(path_points, wrap_mode)  [static] {#create_with_points_wrap_mode_path_points_wrap_mode_5}


```
 create_with_points_wrap_mode(path_points, wrap_mode) 
```

Belirtilen noktalar ve sarma modu ile [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Yolun köşe noktalarını oluşturan noktaları temsil eden bir [Point](/imaging/python-net/aspose.imaging/point/) yapıları dizisi. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Bu [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) ile çizilen doldurmaların nasıl döşeneceğini belirten bir [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) |  |


### Method: deep_clone() {#deep_clone__6}


```
 deep_clone() 
```

Mevcut [Brush](/imaging/python-net/aspose.imaging/brush/) nesnesinin yeni bir derin kopyasını oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | Bu [Brush](/imaging/python-net/aspose.imaging/brush/) örneğinin derin kopyası olan yeni bir [Brush](/imaging/python-net/aspose.imaging/brush/). |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_7}


```
 multiply_transform(matrix) 
```

Bu [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) nesnesinin yerel geometrik dönüşümünü temsil eden [Matrix](/imaging/python-net/aspose.imaging/matrix/) belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) ile çarpar ve belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) ön eklenir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Geometrik dönüşümü çarpmak için kullanılacak [Matrix](/imaging/python-net/aspose.imaging/matrix/). |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_8}


```
 multiply_transform(matrix, order) 
```

Bu [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) nesnesinin yerel geometrik dönüşümünü temsil eden [Matrix](/imaging/python-net/aspose.imaging/matrix/) belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) ile belirtilen sırada çarpar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Geometrik dönüşümü çarpmak için kullanılacak [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | İki matrisi hangi sırada çarpacağını belirten bir [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/). |

### Method: rotate_transform(angle) {#rotate_transform_angle_9}


```
 rotate_transform(angle) 
```

Yerel geometrik dönüşümü belirtilen miktarda döndürür. Bu yöntem döndürmeyi dönüşüme ön ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| angle | float | Dönüş açısı. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_10}


```
 rotate_transform(angle, order) 
```

Yerel geometrik dönüşümü belirtilen miktarda, belirtilen sırada döndürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| angle | float | Dönüş açısı. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Dönüşüm matrisini ekleyecek mi yoksa ön ekleyecek mi olduğunu belirten bir [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/). |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_11}


```
 scale_transform(sx, sy) 
```

Yerel geometrik dönüşümü belirtilen değerlerle ölçeklendirir. Bu yöntem ölçekleme matrisini dönüşüme ön ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| sx | float | Dönüşümün x ekseni yönündeki ölçekleme miktarı. |
| sy | float | Dönüşümün y ekseni yönündeki ölçekleme miktarı. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_12}


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

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_13}


```
 translate_transform(dx, dy) 
```

Yerel geometrik dönüşümü belirtilen boyutlarla çevirir. Bu yöntem çeviriyi dönüşüme ön ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dx | float | x eksenindeki çevirmenin değeri. |
| dy | float | y eksenindeki çevirmenin değeri. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_14}


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

