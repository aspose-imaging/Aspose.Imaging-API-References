---
title: "ImageMask Sınıfı"
type: docs
weight: 70
url: /tr/python-net/aspose.imaging.magicwand.imagemasks/imagemask/
---

**Summary:** Describes a binary image mask.

**Module:** [aspose.imaging.magicwand.imagemasks](/imaging/python-net/aspose.imaging.magicwand.imagemasks/)

**Full Name:** aspose.imaging.magicwand.imagemasks.ImageMask

**Inheritance:** IImageMask

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
| [exclusive_disjunction(image, settings)](#exclusive_disjunction_image_settings_6) | Sağlanan görüntüye uygulanan sihirli değnek seçiminin sonucu ile mevcut maskenin dışlayıcı birleşimini alır. |
| [exclusive_disjunction(mask)](#exclusive_disjunction_mask_7) | Mevcut maskeyi sağlanan ile dışlayıcı birleşimini alır. |
| [exclusive_disjunction(settings)](#exclusive_disjunction_settings_8) | Maskenin kaynağına uygulanan sihirli değnek seçiminin sonucu ile mevcut maskenin dışlayıcı birleşimini alır. |
| [get(x, y)](#get_x_y_9) | Belirtilen pikselin opaklığını alır. |
| [get_byte_opacity(x, y)](#get_byte_opacity_x_y_10) | Belirtilen pikselin opaklığını bayt hassasiyetiyle alır. |
| [get_feathered(settings)](#get_feathered_settings_11) | Belirtilen ayarlarla kenarı yumuşatılmış gri tonlamalı maskeyi alır. |
| [inflate(size)](#inflate_size_12) | Bu maskeyi belirtilen miktarda şişirir. |
| [intersect(image, settings)](#intersect_image_settings_13) | Sağlanan görüntüye uygulanan sihirli değnek seçiminin sonucu ile mevcut maskenin kesişimini alır. |
| [intersect(mask)](#intersect_mask_14) | Mevcut maskenin sağlanan ile kesişimini alır. |
| [intersect(settings)](#intersect_settings_15) | Maskenin kaynağına uygulanan sihirli değnek seçiminin sonucu ile mevcut maskenin kesişimini alır. |
| [invert()](#invert__16) | Mevcut maskenin tersini alır. |
| [is_opaque(x, y)](#is_opaque_x_y_17) | Belirtilen pikselin opak olup olmadığını kontrol eder. |
| [is_transparent(x, y)](#is_transparent_x_y_18) | Belirtilen pikselin şeffaf olup olmadığını kontrol eder. |
| [subtract(image, settings)](#subtract_image_settings_19) | Sağlanan görüntüye uygulanan sihirli değnek seçiminin sonucunu mevcut maskeden çıkarır. |
| [subtract(mask)](#subtract_mask_20) | Sağlanan maskeyi mevcut maskeden çıkarır. |
| [subtract(settings)](#subtract_settings_21) | Mevcut maskenin kaynağına uygulanan sihirli değnek seçiminin sonucunu maskeden çıkarır. |
| [union(image, settings)](#union_image_settings_22) | Sağlanan görüntüye uygulanan sihirli değnek seçiminin sonucu ile mevcut maskenin birleşimini alır. |
| [union(mask)](#union_mask_23) | Mevcut maskenin sağlanan ile birleşimini alır. |
| [union(settings)](#union_settings_24) | Maskenin kaynağına uygulanan sihirli değnek seçiminin sonucu ile mevcut maskenin birleşimini alır. |


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
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Bir ImageMask. |


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
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Bir ImageMask. |


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
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Bir ImageMask. |


### Method: exclusive_disjunction(image, settings) {#exclusive_disjunction_image_settings_6}


```
 exclusive_disjunction(image, settings) 
```

Sağlanan görüntüye uygulanan sihirli değnek seçiminin sonucu ile mevcut maskenin dışlayıcı birleşimini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Sihirli değnek için görüntü. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Sihirli değnek ayarları. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Yeni [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: exclusive_disjunction(mask) {#exclusive_disjunction_mask_7}


```
 exclusive_disjunction(mask) 
```

Mevcut maskeyi sağlanan ile dışlayıcı birleşimini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Sağlanan maske |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Yeni [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: exclusive_disjunction(settings) {#exclusive_disjunction_settings_8}


```
 exclusive_disjunction(settings) 
```

Maskenin kaynağına uygulanan sihirli değnek seçiminin sonucu ile mevcut maskenin dışlayıcı birleşimini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Sihirli değnek ayarları. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Yeni [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: get(x, y) {#get_x_y_9}


```
 get(x, y) 
```

Belirtilen pikselin opaklığını alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| x | int | Pikselin x koordinatı. |
| y | int | Pikselin y koordinatı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen piksel opak ise true; aksi takdirde false. |


### Method: get_byte_opacity(x, y) {#get_byte_opacity_x_y_10}


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


### Method: get_feathered(settings) {#get_feathered_settings_11}


```
 get_feathered(settings) 
```

Belirtilen ayarlarla kenarı yumuşatılmış gri tonlamalı maskeyi alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| settings | [FeatheringSettings](/imaging/python-net/aspose.imaging.magicwand.imagemasks/featheringsettings/) | Tüylenme ayarları. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) tüylenmiş kenar ile. |


### Method: inflate(size) {#inflate_size_12}


```
 inflate(size) 
```

Bu maskeyi belirtilen miktarda şişirir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| size | int | Bu maskeyi şişirmek için miktar. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Bir ImageMask. |


### Method: intersect(image, settings) {#intersect_image_settings_13}


```
 intersect(image, settings) 
```

Sağlanan görüntüye uygulanan sihirli değnek seçiminin sonucu ile mevcut maskenin kesişimini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Sihirli değnek için görüntü. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Sihirli değnek ayarları. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Yeni [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: intersect(mask) {#intersect_mask_14}


```
 intersect(mask) 
```

Mevcut maskenin sağlanan ile kesişimini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Sağlanan maske |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Yeni [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: intersect(settings) {#intersect_settings_15}


```
 intersect(settings) 
```

Maskenin kaynağına uygulanan sihirli değnek seçiminin sonucu ile mevcut maskenin kesişimini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Sihirli değnek ayarları. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Yeni [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: invert() {#invert__16}


```
 invert() 
```

Mevcut maskenin tersini alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Yeni [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: is_opaque(x, y) {#is_opaque_x_y_17}


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


### Method: is_transparent(x, y) {#is_transparent_x_y_18}


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


### Method: subtract(image, settings) {#subtract_image_settings_19}


```
 subtract(image, settings) 
```

Sağlanan görüntüye uygulanan sihirli değnek seçiminin sonucunu mevcut maskeden çıkarır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Sihirli değnek için görüntü. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Sihirli değnek ayarları. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Yeni [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: subtract(mask) {#subtract_mask_20}


```
 subtract(mask) 
```

Sağlanan maskeyi mevcut maskeden çıkarır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Sağlanan maske |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Yeni [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: subtract(settings) {#subtract_settings_21}


```
 subtract(settings) 
```

Mevcut maskenin kaynağına uygulanan sihirli değnek seçiminin sonucunu maskeden çıkarır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Sihirli değnek ayarları. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Yeni [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: union(image, settings) {#union_image_settings_22}


```
 union(image, settings) 
```

Sağlanan görüntüye uygulanan sihirli değnek seçiminin sonucu ile mevcut maskenin birleşimini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Sihirli değnek için görüntü. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Sihirli değnek ayarları. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Yeni [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: union(mask) {#union_mask_23}


```
 union(mask) 
```

Mevcut maskenin sağlanan ile birleşimini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Sağlanan maske |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Yeni [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: union(settings) {#union_settings_24}


```
 union(settings) 
```

Maskenin kaynağına uygulanan sihirli değnek seçiminin sonucu ile mevcut maskenin birleşimini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Sihirli değnek ayarları. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Yeni [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


