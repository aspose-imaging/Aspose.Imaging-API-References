---
title: "TextureBrush Sınıfı"
type: docs
weight: 90
url: /tr/python-net/aspose.imaging.brushes/texturebrush/
---

**Summary:** Each property of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class is a [Brush](/imaging/python-net/aspose.imaging/brush/) object that uses an image to fill the interior of a shape. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.TextureBrush

**Inheritance:** TransformBrush

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [TextureBrush(image)](#TextureBrush_image_1) | Belirtilen görüntüyü kullanan [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_2) | Belirtilen görüntüyü ve sınırlayıcı dikdörtgeni kullanan [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_3) | Belirtilen görüntüyü ve sınırlayıcı dikdörtgeni kullanan [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_4) | Belirtilen görüntüyü, sınırlayıcı dikdörtgeni ve görüntü özniteliklerini kullanan [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_5) | Belirtilen görüntüyü, sınırlayıcı dikdörtgeni ve görüntü özniteliklerini kullanan [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır. |
| [TextureBrush(image, wrap_mode)](#TextureBrush_image_wrap_mode_6) | Belirtilen görüntüyü ve sarma modunu kullanan [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_7) | Belirtilen görüntüyü, sarma modunu ve sınırlayıcı dikdörtgeni kullanan [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_8) | Belirtilen görüntüyü, sarma modunu ve sınırlayıcı dikdörtgeni kullanan [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| dağıtıldı | bool | r | Bu örneğin dağıtılıp dağıtılmadığını gösteren bir değer alır. |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | r | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesiyle ilişkili [Image](/imaging/python-net/aspose.imaging/image/) nesnesini alır. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | r | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) ile ilişkili [TextureBrush.image_attributes](/imaging/python-net/aspose.imaging.brushes/texturebrush/) öğesini alır. |
| image_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) ile ilişkili [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) alır. |
| is_transform_changed | bool | r | Dönüşümlerin bir şekilde değişip değişmediğini gösteren bir değeri alır. Örneğin dönüşüm matrisini ayarlamak veya<br/>            dönüşüm matrisini değiştiren herhangi bir yöntemi çağırmak. Özellik, GDI+ ile geriye uyumluluk sağlamak için eklenmiştir. |
| opacity | float | r/w | Fırça opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri fırçanın tamamen görünür olduğu, 1 değeri ise fırçanın tamamen opak olduğu anlamına gelir. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Bu [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/) için yerel bir geometrik dönüşüm tanımlayan bir kopya [Matrix](/imaging/python-net/aspose.imaging/matrix/) alır veya ayarlar. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | Bu [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/) için sarma modunu gösteren bir [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) enumerasyonunu alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_with_image_rect(image, destination_rectangle)](#create_with_image_rect_image_destination_rectangle_1) | Belirtilen görüntüyü ve sınırlayıcı dikdörtgeni kullanan [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır. |
| [create_with_image_rect_attribs(image, destination_rectangle, image_attributes)](#create_with_image_rect_attribs_image_destination_rectangle_image_attributes_2) | Belirtilen görüntüyü, sınırlayıcı dikdörtgeni ve görüntü özniteliklerini kullanan [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır. |
| [create_with_image_rect_f(image, destination_rectangle)](#create_with_image_rect_f_image_destination_rectangle_3) | Belirtilen görüntüyü ve sınırlayıcı dikdörtgeni kullanan [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır. |
| [create_with_image_rect_f_attribs(image, destination_rectangle, image_attributes)](#create_with_image_rect_f_attribs_image_destination_rectangle_image_attributes_4) | Belirtilen görüntüyü, sınırlayıcı dikdörtgeni ve görüntü özniteliklerini kullanan [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır. |
| [create_with_image_wrap_mode(image, wrap_mode)](#create_with_image_wrap_mode_image_wrap_mode_5) | Belirtilen görüntüyü ve sarma modunu kullanan [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır. |
| [create_with_image_wrap_mode_rect(image, wrap_mode, destination_rectangle)](#create_with_image_wrap_mode_rect_image_wrap_mode_destination_rectangle_6) | Belirtilen görüntüyü, sarma modunu ve sınırlayıcı dikdörtgeni kullanan [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır. |
| [create_with_image_wrap_mode_rect_f(image, wrap_mode, destination_rectangle)](#create_with_image_wrap_mode_rect_f_image_wrap_mode_destination_rectangle_7) | Belirtilen görüntüyü, sarma modunu ve sınırlayıcı dikdörtgeni kullanan [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır. |
| [deep_clone()](#deep_clone__8) | Mevcut [Brush](/imaging/python-net/aspose.imaging/brush/) nesnesinin yeni bir derin kopyasını oluşturur. |
| [multiply_transform(matrix)](#multiply_transform_matrix_9) | Bu [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) nesnesinin yerel geometrik dönüşümünü temsil eden [Matrix](/imaging/python-net/aspose.imaging/matrix/) belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) ile çarpar ve belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) ön eklenir. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_10) | Bu [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) nesnesinin yerel geometrik dönüşümünü temsil eden [Matrix](/imaging/python-net/aspose.imaging/matrix/) belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) ile belirtilen sırada çarpar. |
| reset_transform() | [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) özelliğini birim matrisine sıfırlar. |
| [rotate_transform(angle)](#rotate_transform_angle_11) | Yerel geometrik dönüşümü belirtilen miktarda döndürür. Bu yöntem döndürmeyi dönüşüme ön ekler. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_12) | Yerel geometrik dönüşümü belirtilen miktarda, belirtilen sırada döndürür. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_13) | Yerel geometrik dönüşümü belirtilen değerlerle ölçeklendirir. Bu yöntem ölçekleme matrisini dönüşüme ön ekler. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_14) | Yerel geometrik dönüşümü belirtilen değerlerle, belirtilen sırada ölçeklendirir. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_15) | Yerel geometrik dönüşümü belirtilen boyutlarla çevirir. Bu yöntem çeviriyi dönüşüme ön ekler. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_16) | Yerel geometrik dönüşümü belirtilen boyutlarla, belirtilen sırada çevirir. |


### Constructor: TextureBrush(image) {#TextureBrush_image_1}


```
 TextureBrush(image) 
```

Belirtilen görüntüyü kullanan [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesinin içlerini doldurduğu [Image](/imaging/python-net/aspose.imaging/image/) nesnesi. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_2}


```
 TextureBrush(image, destination_rectangle) 
```

Belirtilen görüntüyü ve sınırlayıcı dikdörtgeni kullanan [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesinin içlerini doldurduğu [Image](/imaging/python-net/aspose.imaging/image/) nesnesi. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesi için sınırlayıcı dikdörtgeni temsil eden bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısı. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_3}


```
 TextureBrush(image, destination_rectangle) 
```

Belirtilen görüntüyü ve sınırlayıcı dikdörtgeni kullanan [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesinin içlerini doldurduğu [Image](/imaging/python-net/aspose.imaging/image/) nesnesi. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesi için sınırlayıcı dikdörtgeni temsil eden bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısı. |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_4}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Belirtilen görüntüyü, sınırlayıcı dikdörtgeni ve görüntü özniteliklerini kullanan [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesinin içlerini doldurduğu [Image](/imaging/python-net/aspose.imaging/image/) nesnesi. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesi için sınırlayıcı dikdörtgeni temsil eden bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısı. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesi tarafından kullanılan görüntü hakkında ek bilgi içeren bir [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) nesnesi. |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_5}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Belirtilen görüntüyü, sınırlayıcı dikdörtgeni ve görüntü özniteliklerini kullanan [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesinin içlerini doldurduğu [Image](/imaging/python-net/aspose.imaging/image/) nesnesi. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesi için sınırlayıcı dikdörtgeni temsil eden bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısı. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesi tarafından kullanılan görüntü hakkında ek bilgi içeren bir [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) nesnesi. |

### Constructor: TextureBrush(image, wrap_mode) {#TextureBrush_image_wrap_mode_6}


```
 TextureBrush(image, wrap_mode) 
```

Belirtilen görüntüyü ve sarma modunu kullanan [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesinin içlerini doldurduğu [Image](/imaging/python-net/aspose.imaging/image/) nesnesi. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesinin döşenme şeklini belirten bir [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) sayımı. |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_7}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Belirtilen görüntüyü, sarma modunu ve sınırlayıcı dikdörtgeni kullanan [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesinin içlerini doldurduğu [Image](/imaging/python-net/aspose.imaging/image/) nesnesi. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesinin döşenme şeklini belirten bir [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) sayımı. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesi için sınırlayıcı dikdörtgeni temsil eden bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısı. |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_8}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Belirtilen görüntüyü, sarma modunu ve sınırlayıcı dikdörtgeni kullanan [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesinin içlerini doldurduğu [Image](/imaging/python-net/aspose.imaging/image/) nesnesi. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesinin döşenme şeklini belirten bir [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) sayımı. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesi için sınırlayıcı dikdörtgeni temsil eden bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısı. |

### Method: create_with_image_rect(image, destination_rectangle)  [static] {#create_with_image_rect_image_destination_rectangle_1}


```
 create_with_image_rect(image, destination_rectangle) 
```

Belirtilen görüntüyü ve sınırlayıcı dikdörtgeni kullanan [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesinin içlerini doldurduğu [Image](/imaging/python-net/aspose.imaging/image/) nesnesi. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesi için sınırlayıcı dikdörtgeni temsil eden bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_rect_attribs(image, destination_rectangle, image_attributes)  [static] {#create_with_image_rect_attribs_image_destination_rectangle_image_attributes_2}


```
 create_with_image_rect_attribs(image, destination_rectangle, image_attributes) 
```

Belirtilen görüntüyü, sınırlayıcı dikdörtgeni ve görüntü özniteliklerini kullanan [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesinin içlerini doldurduğu [Image](/imaging/python-net/aspose.imaging/image/) nesnesi. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesi için sınırlayıcı dikdörtgeni temsil eden bir [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) yapısı. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesi tarafından kullanılan görüntü hakkında ek bilgi içeren bir [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) nesnesi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_rect_f(image, destination_rectangle)  [static] {#create_with_image_rect_f_image_destination_rectangle_3}


```
 create_with_image_rect_f(image, destination_rectangle) 
```

Belirtilen görüntüyü ve sınırlayıcı dikdörtgeni kullanan [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesinin içlerini doldurduğu [Image](/imaging/python-net/aspose.imaging/image/) nesnesi. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesi için sınırlayıcı dikdörtgeni temsil eden bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_rect_f_attribs(image, destination_rectangle, image_attributes)  [static] {#create_with_image_rect_f_attribs_image_destination_rectangle_image_attributes_4}


```
 create_with_image_rect_f_attribs(image, destination_rectangle, image_attributes) 
```

Belirtilen görüntüyü, sınırlayıcı dikdörtgeni ve görüntü özniteliklerini kullanan [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesinin içlerini doldurduğu [Image](/imaging/python-net/aspose.imaging/image/) nesnesi. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesi için sınırlayıcı dikdörtgeni temsil eden bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesi tarafından kullanılan görüntü hakkında ek bilgi içeren bir [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) nesnesi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_wrap_mode(image, wrap_mode)  [static] {#create_with_image_wrap_mode_image_wrap_mode_5}


```
 create_with_image_wrap_mode(image, wrap_mode) 
```

Belirtilen görüntüyü ve sarma modunu kullanan [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesinin içlerini doldurduğu [Image](/imaging/python-net/aspose.imaging/image/) nesnesi. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesinin döşenme şeklini belirten bir [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) sayımı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_wrap_mode_rect(image, wrap_mode, destination_rectangle)  [static] {#create_with_image_wrap_mode_rect_image_wrap_mode_destination_rectangle_6}


```
 create_with_image_wrap_mode_rect(image, wrap_mode, destination_rectangle) 
```

Belirtilen görüntüyü, sarma modunu ve sınırlayıcı dikdörtgeni kullanan [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesinin içlerini doldurduğu [Image](/imaging/python-net/aspose.imaging/image/) nesnesi. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesinin döşenme şeklini belirten bir [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) sayımı. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesi için sınırlayıcı dikdörtgeni temsil eden bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_wrap_mode_rect_f(image, wrap_mode, destination_rectangle)  [static] {#create_with_image_wrap_mode_rect_f_image_wrap_mode_destination_rectangle_7}


```
 create_with_image_wrap_mode_rect_f(image, wrap_mode, destination_rectangle) 
```

Belirtilen görüntüyü, sarma modunu ve sınırlayıcı dikdörtgeni kullanan [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesinin içlerini doldurduğu [Image](/imaging/python-net/aspose.imaging/image/) nesnesi. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesinin döşenme şeklini belirten bir [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) sayımı. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Bu [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) nesnesi için sınırlayıcı dikdörtgeni temsil eden bir [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) yapısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: deep_clone() {#deep_clone__8}


```
 deep_clone() 
```

Mevcut [Brush](/imaging/python-net/aspose.imaging/brush/) nesnesinin yeni bir derin kopyasını oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | Bu [Brush](/imaging/python-net/aspose.imaging/brush/) örneğinin derin kopyası olan yeni bir [Brush](/imaging/python-net/aspose.imaging/brush/). |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_9}


```
 multiply_transform(matrix) 
```

Bu [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) nesnesinin yerel geometrik dönüşümünü temsil eden [Matrix](/imaging/python-net/aspose.imaging/matrix/) belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) ile çarpar ve belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) ön eklenir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Geometrik dönüşümü çarpmak için kullanılacak [Matrix](/imaging/python-net/aspose.imaging/matrix/). |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_10}


```
 multiply_transform(matrix, order) 
```

Bu [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) nesnesinin yerel geometrik dönüşümünü temsil eden [Matrix](/imaging/python-net/aspose.imaging/matrix/) belirtilen [Matrix](/imaging/python-net/aspose.imaging/matrix/) ile belirtilen sırada çarpar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Geometrik dönüşümü çarpmak için kullanılacak [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | İki matrisi hangi sırada çarpacağını belirten bir [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/). |

### Method: rotate_transform(angle) {#rotate_transform_angle_11}


```
 rotate_transform(angle) 
```

Yerel geometrik dönüşümü belirtilen miktarda döndürür. Bu yöntem döndürmeyi dönüşüme ön ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| angle | float | Dönüş açısı. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_12}


```
 rotate_transform(angle, order) 
```

Yerel geometrik dönüşümü belirtilen miktarda, belirtilen sırada döndürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| angle | float | Dönüş açısı. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Dönüşüm matrisini ekleyecek mi yoksa ön ekleyecek mi olduğunu belirten bir [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/). |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_13}


```
 scale_transform(sx, sy) 
```

Yerel geometrik dönüşümü belirtilen değerlerle ölçeklendirir. Bu yöntem ölçekleme matrisini dönüşüme ön ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| sx | float | Dönüşümün x ekseni yönündeki ölçekleme miktarı. |
| sy | float | Dönüşümün y ekseni yönündeki ölçekleme miktarı. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_14}


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

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_15}


```
 translate_transform(dx, dy) 
```

Yerel geometrik dönüşümü belirtilen boyutlarla çevirir. Bu yöntem çeviriyi dönüşüme ön ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| dx | float | x eksenindeki çevirmenin değeri. |
| dy | float | y eksenindeki çevirmenin değeri. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_16}


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

