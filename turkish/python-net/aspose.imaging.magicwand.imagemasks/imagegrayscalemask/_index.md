---
title: "ImageGrayscaleMask Sınıfı"
type: docs
weight: 60
url: /tr/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/
---

**Summary:** Describes a grayscale image mask.

**Module:** [aspose.imaging.magicwand.imagemasks](/imaging/python-net/aspose.imaging.magicwand.imagemasks/)

**Full Name:** aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask

**Inheritance:** IImageMask

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [ImageGrayscaleMask(image)](#ImageGrayscaleMask_image_1) | Belirtilen mevcut [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) boyutunda yeni bir [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) sınıfı örneği başlatır.<br/>            Belirtilen [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) kaynak görüntü olarak saklanacaktır. |
| [ImageGrayscaleMask(width, height)](#ImageGrayscaleMask_width_height_2) | Belirtilen genişlik ve yükseklik ile yeni bir [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Bu maskenin piksel cinsinden sınırlarını alır. |
| height | int | r | Bu maskenin piksel cinsinden yüksekliğini alır. |
| selection_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Maskenin seçilen kısmının piksel cinsinden sınırlarını alır. |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | r | Bu maskeyi oluşturmak için kullanılan kaynak görüntüyü, varsa, alır. |
| width | int | r | Bu maskenin piksel cinsinden genişliğini alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| apply() | Mevcut maskeyi, mevcutsa, [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) kaynağına uygular. |
| [apply_to(image)](#apply_to_image_1) | Mevcut maskeyi belirtilen [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) üzerine uygular. |
| [clone()](#clone__2) | Mevcut örneğin bir kopyası olan yeni bir nesne oluşturur. |
| [crop(rectangle)](#crop_rectangle_3) | Maskeyi belirtilen dikdörtgenle kırpar. |
| [crop(size)](#crop_size_4) | Maskeyi belirtilen boyutla kırpar. |
| [crop(width, height)](#crop_width_height_5) | Maskeyi belirtilen genişlik ve yükseklik ile kırpar. |
| [exclusive_disjunction(mask)](#exclusive_disjunction_mask_6) | Mevcut maskeyi sağlanan ile dışlayıcı birleşimini alır. |
| [get(x, y)](#get_x_y_7) | Belirtilen pikselin opaklığını alır veya ayarlar. |
| [get_byte_opacity(x, y)](#get_byte_opacity_x_y_8) | Belirtilen pikselin opaklığını bayt hassasiyetiyle alır. |
| [intersect(mask)](#intersect_mask_9) | Mevcut maskenin sağlanan ile kesişimini alır. |
| [invert()](#invert__10) | Mevcut maskenin tersini alır. |
| [is_opaque(x, y)](#is_opaque_x_y_11) | Belirtilen pikselin opak olup olmadığını kontrol eder. |
| [is_transparent(x, y)](#is_transparent_x_y_12) | Belirtilen pikselin şeffaf olup olmadığını kontrol eder. |
| [set(x, y, value)](#set_x_y_value_13) | Belirtilen pikselin opaklığını ayarlar. |
| [subtract(mask)](#subtract_mask_14) | Sağlanan maskeyi mevcut maskeden çıkarır. |
| [union(mask)](#union_mask_15) | İki maskenin birleşimi. |


### Constructor: ImageGrayscaleMask(image) {#ImageGrayscaleMask_image_1}


```
 ImageGrayscaleMask(image) 
```

Belirtilen mevcut [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) boyutunda yeni bir [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) sınıfı örneği başlatır.<br/>            Belirtilen [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) kaynak görüntü olarak saklanacaktır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Kaynak görüntü. |

### Constructor: ImageGrayscaleMask(width, height) {#ImageGrayscaleMask_width_height_2}


```
 ImageGrayscaleMask(width, height) 
```

Belirtilen genişlik ve yükseklik ile yeni bir [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| width | int | Maskenin genişliği. |
| height | int | Maskenin yüksekliği. |

### Method: apply_to(image) {#apply_to_image_1}


```
 apply_to(image) 
```

Mevcut maskeyi belirtilen [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) üzerine uygular.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Maskenin uygulanacağı görüntü. |

### Method: clone() {#clone__2}


```
 clone() 
```

Mevcut örneğin bir kopyası olan yeni bir nesne oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Object | Bu örneğin bir kopyası olan yeni bir nesne. |


### Method: crop(rectangle) {#crop_rectangle_3}


```
 crop(rectangle) 
```

Maskeyi belirtilen dikdörtgenle kırpar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Belirtilen dikdörtgen. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Kırpılmış [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: crop(size) {#crop_size_4}


```
 crop(size) 
```

Maskeyi belirtilen boyutla kırpar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | Belirtilen boyut. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Kırpılmış [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: crop(width, height) {#crop_width_height_5}


```
 crop(width, height) 
```

Maskeyi belirtilen genişlik ve yükseklik ile kırpar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| width | int | Belirtilen genişlik. |
| height | int | Belirtilen yükseklik. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Kırpılmış [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: exclusive_disjunction(mask) {#exclusive_disjunction_mask_6}


```
 exclusive_disjunction(mask) 
```

Mevcut maskeyi sağlanan ile dışlayıcı birleşimini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Sağlanan maske |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Yeni [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: get(x, y) {#get_x_y_7}


```
 get(x, y) 
```

Belirtilen pikselin opaklığını alır veya ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | int | Pikselin x koordinatı. |
| y | int | Pikselin y koordinatı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Byte | Bayt değeri; şeffaf ise 0; opak ise 255. |


### Method: get_byte_opacity(x, y) {#get_byte_opacity_x_y_8}


```
 get_byte_opacity(x, y) 
```

Belirtilen pikselin opaklığını bayt hassasiyetiyle alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | int | Pikselin x koordinatı. |
| y | int | Pikselin y koordinatı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Byte | Belirtilen pikselin opaklığını temsil eden bayt değeri. |


### Method: intersect(mask) {#intersect_mask_9}


```
 intersect(mask) 
```

Mevcut maskenin sağlanan ile kesişimini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Sağlanan maske |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Yeni [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: invert() {#invert__10}


```
 invert() 
```

Mevcut maskenin tersini alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Yeni [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: is_opaque(x, y) {#is_opaque_x_y_11}


```
 is_opaque(x, y) 
```

Belirtilen pikselin opak olup olmadığını kontrol eder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | int | Pikselin x koordinatı. |
| y | int | Pikselin y koordinatı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen piksel opak ise true; aksi takdirde false. |


### Method: is_transparent(x, y) {#is_transparent_x_y_12}


```
 is_transparent(x, y) 
```

Belirtilen pikselin şeffaf olup olmadığını kontrol eder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | int | Pikselin x koordinatı. |
| y | int | Pikselin y koordinatı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen piksel şeffaf ise true; aksi takdirde false. |


### Method: set(x, y, value) {#set_x_y_value_13}


```
 set(x, y, value) 
```

Belirtilen pikselin opaklığını ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | int | Pikselin x koordinatı. |
| y | int | Pikselin y koordinatı. |
| değer | System.Byte | Bayt değeri; şeffaf ise 0; opak ise 255. |

### Method: subtract(mask) {#subtract_mask_14}


```
 subtract(mask) 
```

Sağlanan maskeyi mevcut maskeden çıkarır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Sağlanan maske |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Yeni [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: union(mask) {#union_mask_15}


```
 union(mask) 
```

İki maskenin birleşimi.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Sağlanan maske |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Yeni [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


