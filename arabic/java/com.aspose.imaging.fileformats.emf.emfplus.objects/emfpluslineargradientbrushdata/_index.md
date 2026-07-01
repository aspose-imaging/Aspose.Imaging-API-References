---
title: "EmfPlusLinearGradientBrushData"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EmfPlusLinearGradientBrushData يحدد تدرجًا خطيًا لفرشاة رسومية."
type: docs
weight: 53
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusLinearGradientBrushData extends EmfPlusBaseBrushData
```

كائن EmfPlusLinearGradientBrushData يحدد تدرجًا خطيًا لفرشاة رسومية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusLinearGradientBrushData()](#EmfPlusLinearGradientBrushData--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBrushDataFlags()](#getBrushDataFlags--) | يحصل أو يضبط أعلام بيانات الفرشاة. |
| [setBrushDataFlags(int value)](#setBrushDataFlags-int-) | يحصل أو يضبط أعلام بيانات الفرشاة. |
| [getEndArgb32Color()](#getEndArgb32Color--) | يحصل أو يضبط اللون النهائي. |
| [setEndArgb32Color(int value)](#setEndArgb32Color-int-) | يحصل أو يضبط اللون النهائي. |
| [getOptionalData()](#getOptionalData--) | يحصل أو يضبط البيانات الاختيارية. |
| [setOptionalData(EmfPlusLinearGradientBrushOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinearGradientBrushOptionalData-) | يحصل أو يضبط البيانات الاختيارية. |
| [getRectF()](#getRectF--) | يحصل أو يضبط المستطيل f. |
| [setRectF(RectangleF value)](#setRectF-com.aspose.imaging.RectangleF-) | يحصل أو يضبط المستطيل f. |
| [getStartArgb32Color()](#getStartArgb32Color--) | يحصل أو يضبط اللون الابتدائي. |
| [setStartArgb32Color(int value)](#setStartArgb32Color-int-) | يحصل أو يضبط اللون الابتدائي. |
| [getWrapMode()](#getWrapMode--) | يحصل أو يضبط وضع الالتفاف. |
| [setWrapMode(int value)](#setWrapMode-int-) | يحصل أو يضبط وضع الالتفاف. |
### EmfPlusLinearGradientBrushData() {#EmfPlusLinearGradientBrushData--}
```
public EmfPlusLinearGradientBrushData()
```


### getBrushDataFlags() {#getBrushDataFlags--}
```
public int getBrushDataFlags()
```


يحصل أو يضبط أعلام بيانات الفرشاة.

القيمة: BrushDataFlags (4 بايت): عدد صحيح غير موقع 32-بت يحدد البيانات في حقل OptionalData. يجب أن يتكون هذا القيمة من `EmfPlusBrushDataFlags` (القسم 2.1.2.1).

**Returns:**
int
### setBrushDataFlags(int value) {#setBrushDataFlags-int-}
```
public void setBrushDataFlags(int value)
```


يحصل أو يضبط أعلام بيانات الفرشاة.

القيمة: BrushDataFlags (4 بايت): عدد صحيح غير موقع 32-بت يحدد البيانات في حقل OptionalData. يجب أن يتكون هذا القيمة من `EmfPlusBrushDataFlags` (القسم 2.1.2.1).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getEndArgb32Color() {#getEndArgb32Color--}
```
public int getEndArgb32Color()
```


يحصل أو يضبط اللون النهائي.

القيمة: كائن EmfPlusARGB يحدد اللون عند نقطة الحد النهائية لفرشاة التدرج الخطي.

**Returns:**
int
### setEndArgb32Color(int value) {#setEndArgb32Color-int-}
```
public void setEndArgb32Color(int value)
```


يحصل أو يضبط اللون النهائي.

القيمة: كائن EmfPlusARGB يحدد اللون عند نقطة الحد النهائية لفرشاة التدرج الخطي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusLinearGradientBrushOptionalData getOptionalData()
```


يحصل أو يضبط البيانات الاختيارية.

القيمة: كائن `EmfPlusLinearGradientBrushOptionalData` اختياري (القسم 2.2.2.25) يحدد بيانات إضافية لفرشاة التدرج الخطي. المحتويات المحددة لهذا الحقل تُحدد بناءً على قيمة حقل BrushDataFlags.

**Returns:**
[EmfPlusLinearGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata)
### setOptionalData(EmfPlusLinearGradientBrushOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinearGradientBrushOptionalData-}
```
public void setOptionalData(EmfPlusLinearGradientBrushOptionalData value)
```


يحصل أو يضبط البيانات الاختيارية.

القيمة: كائن `EmfPlusLinearGradientBrushOptionalData` اختياري (القسم 2.2.2.25) يحدد بيانات إضافية لفرشاة التدرج الخطي. المحتويات المحددة لهذا الحقل تُحدد بناءً على قيمة حقل BrushDataFlags.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusLinearGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata) |  |

### getRectF() {#getRectF--}
```
public RectangleF getRectF()
```


يحصل أو يضبط المستطيل f.

القيمة: كائن EmfPlusRectF (القسم 2.2.2.39) يحدد نقطتي البداية والنهاية لخط التدرج. الزاوية العلوية اليسرى للمستطيل هي نقطة البداية. الزاوية السفلية اليمنى هي نقطة النهاية.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectF(RectangleF value) {#setRectF-com.aspose.imaging.RectangleF-}
```
public void setRectF(RectangleF value)
```


يحصل أو يضبط المستطيل f.

القيمة: كائن EmfPlusRectF (القسم 2.2.2.39) يحدد نقطتي البداية والنهاية لخط التدرج. الزاوية العلوية اليسرى للمستطيل هي نقطة البداية. الزاوية السفلية اليمنى هي نقطة النهاية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getStartArgb32Color() {#getStartArgb32Color--}
```
public int getStartArgb32Color()
```


يحصل أو يضبط اللون الابتدائي.

القيمة: كائن EmfPlusARGB (القسم 2.2.2.1) يحدد اللون عند نقطة الحد الابتدائية لفرشاة التدرج الخطي.

**Returns:**
int
### setStartArgb32Color(int value) {#setStartArgb32Color-int-}
```
public void setStartArgb32Color(int value)
```


يحصل أو يضبط اللون الابتدائي.

القيمة: كائن EmfPlusARGB (القسم 2.2.2.1) يحدد اللون عند نقطة الحد الابتدائية لفرشاة التدرج الخطي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


يحصل أو يضبط وضع الالتفاف.

القيمة: عدد صحيح موقع 32-بت من تعداد WrapMode (القسم 2.1.1.34) يحدد ما إذا كان سيتم رسم المنطقة خارج حد الفرشاة. عند الرسم خارج الحد، يحدد وضع الالتفاف كيفية تكرار تدرج اللون.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


يحصل أو يضبط وضع الالتفاف.

القيمة: عدد صحيح موقع 32-بت من تعداد WrapMode (القسم 2.1.1.34) يحدد ما إذا كان سيتم رسم المنطقة خارج حد الفرشاة. عند الرسم خارج الحد، يحدد وضع الالتفاف كيفية تكرار تدرج اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

