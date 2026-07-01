---
title: "EmfPlusBitmap"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EmfPlusBitmap يحدد بت ماب يحتوي على صورة رسومية."
type: docs
weight: 14
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata)
```
public final class EmfPlusBitmap extends EmfPlusBaseImageData
```

كائن EmfPlusBitmap يحدد بت ماب يحتوي على صورة رسومية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusBitmap()](#EmfPlusBitmap--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBitmapData()](#getBitmapData--) | يحصل أو يعيّن bitmap data BitmapData (متغير): بيانات بطول متغير تُعرّف كائن بيانات البت ماب المحدد في حقل Type. |
| [setBitmapData(EmfPlusBaseBitmapData value)](#setBitmapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData-) | يحصل أو يعيّن bitmap data BitmapData (متغير): بيانات بطول متغير تُعرّف كائن بيانات البت ماب المحدد في حقل Type. |
| [getHeight()](#getHeight--) | يحصل أو يعيّن bitmap height Height (4 بايت): عدد صحيح موقع 32-بت يحدد الارتفاع بالبكسل للمنطقة التي يشغلها البت ماب. |
| [setHeight(int value)](#setHeight-int-) | يحصل أو يعيّن bitmap height Height (4 بايت): عدد صحيح موقع 32-بت يحدد الارتفاع بالبكسل للمنطقة التي يشغلها البت ماب. |
| [getPixelFormat()](#getPixelFormat--) | يحصل أو يعيّن pixel format PixelFormat (4 بايت): عدد صحيح غير موقع 32-بت يحدد تنسيق البكسلات التي تشكل صورة البت ماب. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | يحصل أو يعيّن pixel format PixelFormat (4 بايت): عدد صحيح غير موقع 32-بت يحدد تنسيق البكسلات التي تشكل صورة البت ماب. |
| [getStride()](#getStride--) | يحصل أو يعيّن stride of the image Stride (4 بايت): عدد صحيح موقع 32-بت يحدد إزاحة البايت بين بداية سطر مسح وآخر. |
| [setStride(int value)](#setStride-int-) | يحصل أو يعيّن stride of the image Stride (4 بايت): عدد صحيح موقع 32-بت يحدد إزاحة البايت بين بداية سطر مسح وآخر. |
| [getType()](#getType--) | يحصل أو يعيّن type of the image Type (4 بايت): عدد صحيح غير موقع 32-بت يحدد نوع البيانات في حقل BitmapData. |
| [setType(int value)](#setType-int-) | يحصل أو يعيّن type of the image Type (4 بايت): عدد صحيح غير موقع 32-بت يحدد نوع البيانات في حقل BitmapData. |
| [getWidth()](#getWidth--) | يحصل أو يعيّن image Width Width (4 بايت): عدد صحيح موقع 32-بت يحدد العرض بالبكسل للمنطقة التي يشغلها البت ماب. |
| [setWidth(int value)](#setWidth-int-) | يحصل أو يعيّن image Width Width (4 بايت): عدد صحيح موقع 32-بت يحدد العرض بالبكسل للمنطقة التي يشغلها البت ماب. |
### EmfPlusBitmap() {#EmfPlusBitmap--}
```
public EmfPlusBitmap()
```


### getBitmapData() {#getBitmapData--}
```
public EmfPlusBaseBitmapData getBitmapData()
```


يحصل أو يعيّن bitmap data BitmapData (متغير): بيانات بطول متغير تُعرّف كائن بيانات البت ماب المحدد في حقل Type. يمكن أن يكون المحتوى وتنسيق البيانات مختلفين لكل نوع من أنواع البت ماب.

القيمة: بيانات البت ماب.

**Returns:**
[EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata)
### setBitmapData(EmfPlusBaseBitmapData value) {#setBitmapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData-}
```
public void setBitmapData(EmfPlusBaseBitmapData value)
```


يحصل أو يعيّن bitmap data BitmapData (متغير): بيانات بطول متغير تُعرّف كائن بيانات البت ماب المحدد في حقل Type. يمكن أن يكون المحتوى وتنسيق البيانات مختلفين لكل نوع من أنواع البت ماب.

القيمة: بيانات البت ماب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata) |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


يحصل أو يعيّن ارتفاع البت ماب Height (4 بايت): عدد صحيح موقّع 32‑بت يحدد الارتفاع بالبكسل للمنطقة التي يشغلها البت ماب. إذا كانت الصورة مضغوطة، وفقًا لحقل Type، تكون هذه القيمة غير معرفة ويجب تجاهلها.

القيمة: الارتفاع.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


يحصل أو يعيّن ارتفاع البت ماب Height (4 بايت): عدد صحيح موقّع 32‑بت يحدد الارتفاع بالبكسل للمنطقة التي يشغلها البت ماب. إذا كانت الصورة مضغوطة، وفقًا لحقل Type، تكون هذه القيمة غير معرفة ويجب تجاهلها.

القيمة: الارتفاع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


يحصل أو يعيّن تنسيق البكسل PixelFormat (4 بايت): عدد صحيح غير موقّع 32‑بت يحدد تنسيق البكسلات التي تشكّل صورة البت ماب. تنسيقات البكسل المدعومة محددة في تعداد `EmfPlusPixelFormat` (القسم 2.1.1.25). إذا كانت الصورة مضغوطة، وفقًا لحقل Type، تكون هذه القيمة غير معرفة ويجب تجاهلها.

القيمة: تنسيق البكسل.

**Returns:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public void setPixelFormat(int value)
```


يحصل أو يعيّن تنسيق البكسل PixelFormat (4 بايت): عدد صحيح غير موقّع 32‑بت يحدد تنسيق البكسلات التي تشكّل صورة البت ماب. تنسيقات البكسل المدعومة محددة في تعداد `EmfPlusPixelFormat` (القسم 2.1.1.25). إذا كانت الصورة مضغوطة، وفقًا لحقل Type، تكون هذه القيمة غير معرفة ويجب تجاهلها.

القيمة: تنسيق البكسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getStride() {#getStride--}
```
public int getStride()
```


يحصل أو يعيّن خطوة الصورة Stride (4 بايت): عدد صحيح موقّع 32‑بت يحدد إزاحة البايت بين بداية سطر مسح وآخر. هذه القيمة هي عدد البايتات لكل بكسل، المحددة في حقل PixelFormat، مضروبة في العرض بالبكسل، المحدد في حقل Width. يجب أن تكون قيمة هذا الحقل مضاعفًا للعدد أربعة. إذا كانت الصورة مضغوطة، وفقًا لحقل Type، تكون هذه القيمة غير معرفة ويجب تجاهلها.

القيمة: خطوة الصورة.

**Returns:**
int
### setStride(int value) {#setStride-int-}
```
public void setStride(int value)
```


يحصل أو يعيّن خطوة الصورة Stride (4 بايت): عدد صحيح موقّع 32‑بت يحدد إزاحة البايت بين بداية سطر مسح وآخر. هذه القيمة هي عدد البايتات لكل بكسل، المحددة في حقل PixelFormat، مضروبة في العرض بالبكسل، المحدد في حقل Width. يجب أن تكون قيمة هذا الحقل مضاعفًا للعدد أربعة. إذا كانت الصورة مضغوطة، وفقًا لحقل Type، تكون هذه القيمة غير معرفة ويجب تجاهلها.

القيمة: خطوة الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public int getType()
```


يحصل أو يعيّن نوع الصورة Type (4 بايت): عدد صحيح غير موقّع 32‑بت يحدد نوع البيانات في حقل BitmapData. يجب أن تكون هذه القيمة معرفة في تعداد `EmfPlusBitmapDataType` (القسم 2.1.1.2).

القيمة: النوع.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


يحصل أو يعيّن نوع الصورة Type (4 بايت): عدد صحيح غير موقّع 32‑بت يحدد نوع البيانات في حقل BitmapData. يجب أن تكون هذه القيمة معرفة في تعداد `EmfPlusBitmapDataType` (القسم 2.1.1.2).

القيمة: النوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


يحصل أو يعيّن عرض الصورة Width (4 بايت): عدد صحيح موقّع 32‑بت يحدد العرض بالبكسل للمنطقة التي يشغلها البت ماب. إذا كانت الصورة مضغوطة، وفقًا لحقل Type، تكون هذه القيمة غير معرفة ويجب تجاهلها.

القيمة: العرض.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


يحصل أو يعيّن عرض الصورة Width (4 بايت): عدد صحيح موقّع 32‑بت يحدد العرض بالبكسل للمنطقة التي يشغلها البت ماب. إذا كانت الصورة مضغوطة، وفقًا لحقل Type، تكون هذه القيمة غير معرفة ويجب تجاهلها.

القيمة: العرض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

