---
title: "IImageMask فئة"
type: docs
weight: 40
url: /ar/python-net/aspose.imaging.magicwand.imagemasks/iimagemask/
---

**Summary:** Describes a mask.

**Module:** [aspose.imaging.magicwand.imagemasks](/imaging/python-net/aspose.imaging.magicwand.imagemasks/)

**Full Name:** aspose.imaging.magicwand.imagemasks.IImageMask

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
| [clone()](#clone__1) | ينشئ كائنًا جديدًا يكون نسخة من المثيل الحالي. |
| [get_byte_opacity(x, y)](#get_byte_opacity_x_y_2) | يحصل على شفافية البكسل المحدد بدقة بايت. |
| [is_opaque(x, y)](#is_opaque_x_y_3) | يتحقق مما إذا كان البكسل المحدد معتمًا. |
| [is_transparent(x, y)](#is_transparent_x_y_4) | يتحقق مما إذا كان البكسل المحدد شفافًا. |


### Method: clone() {#clone__1}


```
 clone() 
```

ينشئ كائنًا جديدًا يكون نسخة من المثيل الحالي.

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Object |  |


### Method: get_byte_opacity(x, y) {#get_byte_opacity_x_y_2}


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


### Method: is_opaque(x, y) {#is_opaque_x_y_3}


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


### Method: is_transparent(x, y) {#is_transparent_x_y_4}


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


