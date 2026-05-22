---
title: "فئة ImageGrayscaleMask"
type: docs
weight: 60
url: /ar/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/
---

**Summary:** Describes a grayscale image mask.

**Module:** [aspose.imaging.magicwand.imagemasks](/imaging/python-net/aspose.imaging.magicwand.imagemasks/)

**Full Name:** aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask

**Inheritance:** IImageMask

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [ImageGrayscaleMask(image)](#ImageGrayscaleMask_image_1) | يُنشئ مثلاً جديداً من الفئة [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) بالحجم المستند إلى [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) المحدد الموجود.<br/>            سيتم تخزين [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) المحدد كمصدر الصورة. |
| [ImageGrayscaleMask(width, height)](#ImageGrayscaleMask_width_height_2) | يُنشئ مثلاً جديداً من الفئة [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) بالعرض والارتفاع المحددين. |
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
| [exclusive_disjunction(mask)](#exclusive_disjunction_mask_6) | يحصل على الفرق الحصري بين القناع الحالي والمُقدَّم. |
| [get(x, y)](#get_x_y_7) | يحصل أو يضبط شفافية البكسل المحدد. |
| [get_byte_opacity(x, y)](#get_byte_opacity_x_y_8) | يحصل على شفافية البكسل المحدد بدقة بايت. |
| [intersect(mask)](#intersect_mask_9) | يحصل على تقاطع القناع الحالي مع القناع المقدم. |
| [invert()](#invert__10) | يحصل على عكس القناع الحالي. |
| [is_opaque(x, y)](#is_opaque_x_y_11) | يتحقق مما إذا كان البكسل المحدد معتمًا. |
| [is_transparent(x, y)](#is_transparent_x_y_12) | يتحقق مما إذا كان البكسل المحدد شفافًا. |
| [set(x, y, value)](#set_x_y_value_13) | يضبط شفافية البكسل المحدد. |
| [subtract(mask)](#subtract_mask_14) | يحصل على طرح القناع المقدم من القناع الحالي. |
| [union(mask)](#union_mask_15) | اتحاد قناعين. |


### Constructor: ImageGrayscaleMask(image) {#ImageGrayscaleMask_image_1}


```
 ImageGrayscaleMask(image) 
```

يُنشئ مثلاً جديداً من الفئة [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) بالحجم المستند إلى [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) المحدد الموجود.<br/>            سيتم تخزين [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) المحدد كمصدر الصورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة المصدر. |

### Constructor: ImageGrayscaleMask(width, height) {#ImageGrayscaleMask_width_height_2}


```
 ImageGrayscaleMask(width, height) 
```

يُنشئ مثلاً جديداً من الفئة [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) بالعرض والارتفاع المحددين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| width | int | عرض القناع. |
| height | int | ارتفاع القناع. |

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
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | قناع [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) مقصوص. |


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
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | قناع [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) مقصوص. |


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
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | قناع [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) مقصوص. |


### Method: exclusive_disjunction(mask) {#exclusive_disjunction_mask_6}


```
 exclusive_disjunction(mask) 
```

يحصل على الفرق الحصري بين القناع الحالي والمُقدَّم.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | القناع المقدم |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | قناع [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) جديد. |


### Method: get(x, y) {#get_x_y_7}


```
 get(x, y) 
```

يحصل أو يضبط شفافية البكسل المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | int | الإحداثي السيني للبكسل. |
| y | int | الإحداثي الصادي للبكسل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Byte | قيمة بايت؛ 0 إذا كان شفافًا؛ 255 إذا كان غير شفاف. |


### Method: get_byte_opacity(x, y) {#get_byte_opacity_x_y_8}


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


### Method: intersect(mask) {#intersect_mask_9}


```
 intersect(mask) 
```

يحصل على تقاطع القناع الحالي مع القناع المقدم.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | القناع المقدم |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | قناع [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) جديد. |


### Method: invert() {#invert__10}


```
 invert() 
```

يحصل على عكس القناع الحالي.

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | قناع [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) جديد. |


### Method: is_opaque(x, y) {#is_opaque_x_y_11}


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


### Method: is_transparent(x, y) {#is_transparent_x_y_12}


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


### Method: set(x, y, value) {#set_x_y_value_13}


```
 set(x, y, value) 
```

يضبط شفافية البكسل المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | int | الإحداثي السيني للبكسل. |
| y | int | الإحداثي الصادي للبكسل. |
| القيمة | System.Byte | قيمة بايت؛ 0 إذا كان شفافًا؛ 255 إذا كان غير شفاف. |

### Method: subtract(mask) {#subtract_mask_14}


```
 subtract(mask) 
```

يحصل على طرح القناع المقدم من القناع الحالي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | القناع المقدم |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | قناع [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) جديد. |


### Method: union(mask) {#union_mask_15}


```
 union(mask) 
```

اتحاد قناعين.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | القناع المقدم |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | قناع [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) جديد. |


