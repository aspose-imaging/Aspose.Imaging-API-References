---
title: "RectangleMask فئة"
type: docs
weight: 80
url: /ar/python-net/aspose.imaging.magicwand.imagemasks/rectanglemask/
---

**Summary:** Describes a rectangle mask.

**Module:** [aspose.imaging.magicwand.imagemasks](/imaging/python-net/aspose.imaging.magicwand.imagemasks/)

**Full Name:** aspose.imaging.magicwand.imagemasks.RectangleMask

**Inheritance:** IImageMask, ImageMask

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [RectangleMask(selected_area)](#RectangleMask_selected_area_1) | ينشئ مثيلًا جديدًا من الفئة [RectangleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/rectanglemask/) بالمستطيل المحدد. |
| [RectangleMask(x, y, width, height)](#RectangleMask_x_y_width_height_2) | ينشئ مثيلًا جديدًا من الفئة [RectangleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/rectanglemask/) بالنقطة اليسرى العليا المحددة، العرض والارتفاع. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | يحصل على حدود القناع، بوحدات البكسل، لهذا القناع. |
| height | int | r | يحصل على ارتفاع القناع، بوحدات البكسل، لهذا القناع. |
| selection_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | يحصل على حدود الجزء المحدد من القناع، بوحدات البكسل. |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | r | يحصل على صورة المصدر المستخدمة لإنشاء هذا القناع، إذا وجدت. |
| width | int | r | يحصل على عرض القناع، بوحدات البكسل، لهذا القناع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| apply() | يطبق القناع الحالي على مصدر [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) إذا كان موجودًا. |
| [apply_to(image)](#apply_to_image_1) | يطبق القناع الحالي على [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) المحدد. |
| [clone()](#clone__2) | ينشئ كائنًا جديدًا يكون نسخة من المثيل الحالي. |
| [crop(rectangle)](#crop_rectangle_3) | يقص القناع بالمستطيل المحدد. |
| [crop(size)](#crop_size_4) | يقص القناع بالحجم المحدد. |
| [crop(width, height)](#crop_width_height_5) | يقص القناع بالعرض والارتفاع المحددين. |
| [exclusive_disjunction(image, settings)](#exclusive_disjunction_image_settings_6) | يحصل على الفرق الحصري بين القناع الحالي ونتيجة اختيار العصا السحرية المطبقة على الصورة المقدمة. |
| [exclusive_disjunction(mask)](#exclusive_disjunction_mask_7) | يحصل على الفرق الحصري بين القناع الحالي والمُقدَّم. |
| [exclusive_disjunction(settings)](#exclusive_disjunction_settings_8) | يحصل على الفرق الحصري بين القناع الحالي ونتيجة اختيار العصا السحرية المطبقة على مصدر القناع. |
| [get(x, y)](#get_x_y_9) | يحصل على شفافية البكسل المحدد. |
| [get_byte_opacity(x, y)](#get_byte_opacity_x_y_10) | يحصل على شفافية البكسل المحدد بدقة بايت. |
| [get_feathered(settings)](#get_feathered_settings_11) | يحصل على قناع رمادي مع حافة مموهة وفقًا للإعدادات المحددة. |
| [inflate(size)](#inflate_size_12) | يوسع هذا القناع بالمقدار المحدد. |
| [intersect(image, settings)](#intersect_image_settings_13) | يحصل على تقاطع القناع الحالي مع نتيجة تحديد العصا السحرية المطبقة على الصورة المقدمة. |
| [intersect(mask)](#intersect_mask_14) | يحصل على تقاطع القناع الحالي مع القناع المقدم. |
| [intersect(settings)](#intersect_settings_15) | يحصل على تقاطع القناع الحالي مع نتيجة تحديد العصا السحرية المطبقة على مصدر القناع. |
| [invert()](#invert__16) | يحصل على عكس القناع الحالي. |
| [is_opaque(x, y)](#is_opaque_x_y_17) | يتحقق مما إذا كان البكسل المحدد معتمًا. |
| [is_transparent(x, y)](#is_transparent_x_y_18) | يتحقق مما إذا كان البكسل المحدد شفافًا. |
| [subtract(image, settings)](#subtract_image_settings_19) | يحصل على نتيجة تحديد العصا السحرية المطبقة على الصورة المقدمة مطروحًا من القناع الحالي. |
| [subtract(mask)](#subtract_mask_20) | يحصل على طرح القناع المقدم من القناع الحالي. |
| [subtract(settings)](#subtract_settings_21) | يحصل على نتيجة تحديد العصا السحرية المطبقة على مصدر القناع الحالي مطروحًا من القناع. |
| [union(image, settings)](#union_image_settings_22) | يحصل على اتحاد القناع الحالي مع نتيجة تحديد العصا السحرية المطبقة على الصورة المقدمة. |
| [union(mask)](#union_mask_23) | يحصل على اتحاد القناع الحالي مع القناع المقدم. |
| [union(settings)](#union_settings_24) | يحصل على اتحاد القناع الحالي مع نتيجة تحديد العصا السحرية المطبقة على مصدر القناع. |


### Constructor: RectangleMask(selected_area) {#RectangleMask_selected_area_1}


```
 RectangleMask(selected_area) 
```

ينشئ مثيلًا جديدًا من الفئة [RectangleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/rectanglemask/) بالمستطيل المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| selected_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المنطقة المحددة كمستطيل. |

### Constructor: RectangleMask(x, y, width, height) {#RectangleMask_x_y_width_height_2}


```
 RectangleMask(x, y, width, height) 
```

ينشئ مثيلًا جديدًا من الفئة [RectangleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/rectanglemask/) بالنقطة اليسرى العليا المحددة، العرض والارتفاع.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | int | الإحداثي السيني للنقطة اليسرى العليا للمنطقة المحددة. |
| y | int | الإحداثي الصادي للنقطة اليسرى العليا للمنطقة المحددة. |
| width | int | عرض المنطقة المحددة. |
| height | int | ارتفاع المنطقة المحددة. |

### Method: apply_to(image) {#apply_to_image_1}


```
 apply_to(image) 
```

يطبق القناع الحالي على [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة التي سيُطبق عليها القناع. |

### Method: clone() {#clone__2}


```
 clone() 
```

ينشئ كائنًا جديدًا يكون نسخة من المثيل الحالي.

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Object | كائن جديد هو نسخة من هذه الحالة. |


### Method: crop(rectangle) {#crop_rectangle_3}


```
 crop(rectangle) 
```

يقص القناع بالمستطيل المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | المستطيل المحدد. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | RectangleMask مقصوص كـ ImageMask. |


### Method: crop(size) {#crop_size_4}


```
 crop(size) 
```

يقص القناع بالحجم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | الحجم المحدد. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | قناع ImageMask. |


### Method: crop(width, height) {#crop_width_height_5}


```
 crop(width, height) 
```

يقص القناع بالعرض والارتفاع المحددين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| width | int | العرض المحدد. |
| height | int | الارتفاع المحدد. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | قناع ImageMask. |


### Method: exclusive_disjunction(image, settings) {#exclusive_disjunction_image_settings_6}


```
 exclusive_disjunction(image, settings) 
```

يحصل على الفرق الحصري بين القناع الحالي ونتيجة اختيار العصا السحرية المطبقة على الصورة المقدمة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | صورة للعصا السحرية. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | إعدادات العصا السحرية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | جديد [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: exclusive_disjunction(mask) {#exclusive_disjunction_mask_7}


```
 exclusive_disjunction(mask) 
```

يحصل على الفرق الحصري بين القناع الحالي والمُقدَّم.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | القناع المقدم |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | جديد [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: exclusive_disjunction(settings) {#exclusive_disjunction_settings_8}


```
 exclusive_disjunction(settings) 
```

يحصل على الفرق الحصري بين القناع الحالي ونتيجة اختيار العصا السحرية المطبقة على مصدر القناع.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | إعدادات العصا السحرية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | جديد [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: get(x, y) {#get_x_y_9}


```
 get(x, y) 
```

يحصل على شفافية البكسل المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | int | الإحداثي السيني للبكسل. |
| y | int | الإحداثي الصادي للبكسل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | صحيح إذا كان البكسل المحدد معتمًا؛ وإلا خاطئ. |


### Method: get_byte_opacity(x, y) {#get_byte_opacity_x_y_10}


```
 get_byte_opacity(x, y) 
```

يحصل على شفافية البكسل المحدد بدقة بايت.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | int | الإحداثي السيني للبكسل. |
| y | int | الإحداثي الصادي للبكسل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Byte | قيمة بايت تمثل شفافية البكسل المحدد. |


### Method: get_feathered(settings) {#get_feathered_settings_11}


```
 get_feathered(settings) 
```

يحصل على قناع رمادي مع حافة مموهة وفقًا للإعدادات المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| settings | [FeatheringSettings](/imaging/python-net/aspose.imaging.magicwand.imagemasks/featheringsettings/) | إعدادات التنعيم. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) مع حد مموه. |


### Method: inflate(size) {#inflate_size_12}


```
 inflate(size) 
```

يوسع هذا القناع بالمقدار المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الحجم | int | المقدار لتوسيع هذا القناع. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | RectangleMask مضخم كـ ImageMask. |


### Method: intersect(image, settings) {#intersect_image_settings_13}


```
 intersect(image, settings) 
```

يحصل على تقاطع القناع الحالي مع نتيجة تحديد العصا السحرية المطبقة على الصورة المقدمة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | صورة للعصا السحرية. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | إعدادات العصا السحرية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | جديد [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: intersect(mask) {#intersect_mask_14}


```
 intersect(mask) 
```

يحصل على تقاطع القناع الحالي مع القناع المقدم.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | القناع المقدم |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | جديد [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: intersect(settings) {#intersect_settings_15}


```
 intersect(settings) 
```

يحصل على تقاطع القناع الحالي مع نتيجة تحديد العصا السحرية المطبقة على مصدر القناع.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | إعدادات العصا السحرية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | جديد [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: invert() {#invert__16}


```
 invert() 
```

يحصل على عكس القناع الحالي.

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | جديد [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: is_opaque(x, y) {#is_opaque_x_y_17}


```
 is_opaque(x, y) 
```

يتحقق مما إذا كان البكسل المحدد معتمًا.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | int | الإحداثي السيني للبكسل. |
| y | int | الإحداثي الصادي للبكسل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | صحيح إذا كان البكسل المحدد معتمًا؛ وإلا خاطئ. |


### Method: is_transparent(x, y) {#is_transparent_x_y_18}


```
 is_transparent(x, y) 
```

يتحقق مما إذا كان البكسل المحدد شفافًا.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | int | الإحداثي السيني للبكسل. |
| y | int | الإحداثي الصادي للبكسل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | صحيح إذا كان البكسل المحدد شفافًا؛ وإلا خاطئ. |


### Method: subtract(image, settings) {#subtract_image_settings_19}


```
 subtract(image, settings) 
```

يحصل على نتيجة تحديد العصا السحرية المطبقة على الصورة المقدمة مطروحًا من القناع الحالي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | صورة للعصا السحرية. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | إعدادات العصا السحرية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | جديد [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: subtract(mask) {#subtract_mask_20}


```
 subtract(mask) 
```

يحصل على طرح القناع المقدم من القناع الحالي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | القناع المقدم |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | جديد [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: subtract(settings) {#subtract_settings_21}


```
 subtract(settings) 
```

يحصل على نتيجة تحديد العصا السحرية المطبقة على مصدر القناع الحالي مطروحًا من القناع.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | إعدادات العصا السحرية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | جديد [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: union(image, settings) {#union_image_settings_22}


```
 union(image, settings) 
```

يحصل على اتحاد القناع الحالي مع نتيجة تحديد العصا السحرية المطبقة على الصورة المقدمة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | صورة للعصا السحرية. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | إعدادات العصا السحرية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | جديد [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: union(mask) {#union_mask_23}


```
 union(mask) 
```

يحصل على اتحاد القناع الحالي مع القناع المقدم.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | القناع المقدم |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | جديد [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: union(settings) {#union_settings_24}


```
 union(settings) 
```

يحصل على اتحاد القناع الحالي مع نتيجة تحديد العصا السحرية المطبقة على مصدر القناع.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | إعدادات العصا السحرية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | جديد [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


