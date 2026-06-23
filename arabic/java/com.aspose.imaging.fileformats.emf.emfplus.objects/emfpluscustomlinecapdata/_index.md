---
title: "EmfPlusCustomLineCapData"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EmfPlusCustomLineCapData يحدد البيانات الافتراضية لغطاء خط مخصص."
type: docs
weight: 36
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomBaseLineCap](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustombaselinecap)
```
public final class EmfPlusCustomLineCapData extends EmfPlusCustomBaseLineCap
```

كائن EmfPlusCustomLineCapData يحدد البيانات الافتراضية لغطاء خط مخصص.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusCustomLineCapData()](#EmfPlusCustomLineCapData--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCustomLineCapDataFlags()](#getCustomLineCapDataFlags--) | الحصول أو تعيين عدد صحيح غير موقع 32-بت يحدد البيانات في حقل OptionalData |
| [setCustomLineCapDataFlags(int value)](#setCustomLineCapDataFlags-int-) | الحصول أو تعيين عدد صحيح غير موقع 32-بت يحدد البيانات في حقل OptionalData |
| [getBaseCap()](#getBaseCap--) | الحصول أو تعيين عدد صحيح غير موقع 32-بت يحدد القيمة من تعداد LineCap (القسم 2.1.1.18) الذي يُستند إليه غطاء الخط المخصص. |
| [setBaseCap(int value)](#setBaseCap-int-) | الحصول أو تعيين عدد صحيح غير موقع 32-بت يحدد القيمة من تعداد LineCap (القسم 2.1.1.18) الذي يُستند إليه غطاء الخط المخصص. |
| [getBaseInset()](#getBaseInset--) | الحصول أو تعيين قيمة نقطية عائمة 32-بت تحدد المسافة بين بداية غطاء الخط ونهاية الخط. |
| [setBaseInset(float value)](#setBaseInset-float-) | الحصول أو تعيين قيمة نقطية عائمة 32-بت تحدد المسافة بين بداية غطاء الخط ونهاية الخط. |
| [getStrokeStartCap()](#getStrokeStartCap--) | الحصول أو تعيين عدد صحيح غير موقع 32-بت يحدد القيمة في تعداد LineCap التي تشير إلى غطاء الخط المستخدم في بداية الخط المراد رسمه |
| [setStrokeStartCap(int value)](#setStrokeStartCap-int-) | الحصول أو تعيين عدد صحيح غير موقع 32-بت يحدد القيمة في تعداد LineCap التي تشير إلى غطاء الخط المستخدم في بداية الخط المراد رسمه |
| [getStrokeEndCap()](#getStrokeEndCap--) | الحصول أو تعيين عدد صحيح غير موقع 32-بت يحدد القيمة في تعداد LineCap التي تشير إلى غطاء الخط الذي سيُستخدم في نهاية الخط المراد رسمه. |
| [setStrokeEndCap(int value)](#setStrokeEndCap-int-) | الحصول أو تعيين عدد صحيح غير موقع 32-بت يحدد القيمة في تعداد LineCap التي تشير إلى غطاء الخط الذي سيُستخدم في نهاية الخط المراد رسمه. |
| [getStrokeJoin()](#getStrokeJoin--) | الحصول أو تعيين عدد صحيح غير موقع 32-بت يحدد القيمة في تعداد LineJoin (القسم 2.1.1.19)، الذي يحدد كيفية ربط خطين يتم رسمهما بنفس القلم وتلتقي نهاياتهما. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | الحصول أو تعيين عدد صحيح غير موقع 32-بت يحدد القيمة في تعداد LineJoin (القسم 2.1.1.19)، الذي يحدد كيفية ربط خطين يتم رسمهما بنفس القلم وتلتقي نهاياتهما. |
| [getStrokeMiterLimit()](#getStrokeMiterLimit--) | الحصول أو تعيين قيمة نقطية عائمة 32-بت تحتوي على حد سمك الوصلة عند زاوية ميتير عن طريق ضبط النسبة القصوى المسموح بها لطول الميتير إلى عرض الخط. |
| [setStrokeMiterLimit(float value)](#setStrokeMiterLimit-float-) | الحصول أو تعيين قيمة نقطية عائمة 32-بت تحتوي على حد سمك الوصلة عند زاوية ميتير عن طريق ضبط النسبة القصوى المسموح بها لطول الميتير إلى عرض الخط. |
| [getWidthScale()](#getWidthScale--) | الحصول أو تعيين قيمة نقطية عائمة 32-بت تحدد مقدار تعديل مقياس غطاء الخط المخصص بالنسبة إلى عرض كائن EmfPlusPen (القسم 2.2.1.7) المستخدم لرسم الخطوط. |
| [setWidthScale(float value)](#setWidthScale-float-) | الحصول أو تعيين قيمة نقطية عائمة 32-بت تحدد مقدار تعديل مقياس غطاء الخط المخصص بالنسبة إلى عرض كائن EmfPlusPen (القسم 2.2.1.7) المستخدم لرسم الخطوط. |
| [getFillHotSpot()](#getFillHotSpot--) | الحصول أو تعيين كائن EmfPlusPointF غير مستخدم حالياً. |
| [setFillHotSpot(PointF value)](#setFillHotSpot-com.aspose.imaging.PointF-) | الحصول أو تعيين كائن EmfPlusPointF غير مستخدم حالياً. |
| [getStrokeHotSpot()](#getStrokeHotSpot--) | الحصول أو تعيين كائن EmfPlusPointF غير مستخدم حالياً. |
| [setStrokeHotSpot(PointF value)](#setStrokeHotSpot-com.aspose.imaging.PointF-) | الحصول أو تعيين كائن EmfPlusPointF غير مستخدم حالياً. |
| [getOptionalData()](#getOptionalData--) | الحصول أو تعيين كائن EmfPlusCustomLineCapOptionalData اختياري (القسم 2.2.2.14) يحدد بيانات إضافية لغطاء الخط الرسومي المخصص. |
| [setOptionalData(EmfPlusCustomLineCapOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapOptionalData-) | الحصول أو تعيين كائن EmfPlusCustomLineCapOptionalData اختياري (القسم 2.2.2.14) يحدد بيانات إضافية لغطاء الخط الرسومي المخصص. |
### EmfPlusCustomLineCapData() {#EmfPlusCustomLineCapData--}
```
public EmfPlusCustomLineCapData()
```


### getCustomLineCapDataFlags() {#getCustomLineCapDataFlags--}
```
public int getCustomLineCapDataFlags()
```


الحصول أو تعيين عدد صحيح غير موقع 32-بت يحدد البيانات في حقل OptionalData

**Returns:**
int
### setCustomLineCapDataFlags(int value) {#setCustomLineCapDataFlags-int-}
```
public void setCustomLineCapDataFlags(int value)
```


الحصول أو تعيين عدد صحيح غير موقع 32-بت يحدد البيانات في حقل OptionalData

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


الحصول أو تعيين عدد صحيح غير موقع 32-بت يحدد القيمة من تعداد LineCap (القسم 2.1.1.18) الذي يُستند إليه غطاء الخط المخصص.

**Returns:**
int
### setBaseCap(int value) {#setBaseCap-int-}
```
public void setBaseCap(int value)
```


الحصول أو تعيين عدد صحيح غير موقع 32-بت يحدد القيمة من تعداد LineCap (القسم 2.1.1.18) الذي يُستند إليه غطاء الخط المخصص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


الحصول أو تعيين قيمة نقطية عائمة 32-بت تحدد المسافة بين بداية غطاء الخط ونهاية الخط.

**Returns:**
float
### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


الحصول أو تعيين قيمة نقطية عائمة 32-بت تحدد المسافة بين بداية غطاء الخط ونهاية الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getStrokeStartCap() {#getStrokeStartCap--}
```
public int getStrokeStartCap()
```


الحصول أو تعيين عدد صحيح غير موقع 32-بت يحدد القيمة في تعداد LineCap التي تشير إلى غطاء الخط المستخدم في بداية الخط المراد رسمه

**Returns:**
int
### setStrokeStartCap(int value) {#setStrokeStartCap-int-}
```
public void setStrokeStartCap(int value)
```


الحصول أو تعيين عدد صحيح غير موقع 32-بت يحدد القيمة في تعداد LineCap التي تشير إلى غطاء الخط المستخدم في بداية الخط المراد رسمه

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getStrokeEndCap() {#getStrokeEndCap--}
```
public int getStrokeEndCap()
```


الحصول أو تعيين عدد صحيح غير موقع 32-بت يحدد القيمة في تعداد LineCap التي تشير إلى غطاء الخط الذي سيُستخدم في نهاية الخط المراد رسمه.

**Returns:**
int
### setStrokeEndCap(int value) {#setStrokeEndCap-int-}
```
public void setStrokeEndCap(int value)
```


الحصول أو تعيين عدد صحيح غير موقع 32-بت يحدد القيمة في تعداد LineCap التي تشير إلى غطاء الخط الذي سيُستخدم في نهاية الخط المراد رسمه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


الحصول أو تعيين عدد صحيح غير موقع 32-بت يحدد القيمة في تعداد LineJoin (القسم 2.1.1.19)، الذي يحدد كيفية ربط خطين يتم رسمهما بنفس القلم وتلتقي نهاياتهما. عند تقاطع نهايتي الخطين، تجعل وصلة الخط الاتصال يبدو أكثر استمرارية.

**Returns:**
int
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


الحصول أو تعيين عدد صحيح غير موقع 32-بت يحدد القيمة في تعداد LineJoin (القسم 2.1.1.19)، الذي يحدد كيفية ربط خطين يتم رسمهما بنفس القلم وتلتقي نهاياتهما. عند تقاطع نهايتي الخطين، تجعل وصلة الخط الاتصال يبدو أكثر استمرارية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getStrokeMiterLimit() {#getStrokeMiterLimit--}
```
public float getStrokeMiterLimit()
```


الحصول أو تعيين قيمة نقطية عائمة 32-بت تحتوي على حد سمك الوصلة عند زاوية ميتير عن طريق ضبط النسبة القصوى المسموح بها لطول الميتير إلى عرض الخط.

**Returns:**
float
### setStrokeMiterLimit(float value) {#setStrokeMiterLimit-float-}
```
public void setStrokeMiterLimit(float value)
```


الحصول أو تعيين قيمة نقطية عائمة 32-بت تحتوي على حد سمك الوصلة عند زاوية ميتير عن طريق ضبط النسبة القصوى المسموح بها لطول الميتير إلى عرض الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


الحصول أو تعيين قيمة نقطية عائمة 32-بت تحدد مقدار تعديل مقياس غطاء الخط المخصص بالنسبة إلى عرض كائن EmfPlusPen (القسم 2.2.1.7) المستخدم لرسم الخطوط.

**Returns:**
float
### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


الحصول أو تعيين قيمة نقطية عائمة 32-بت تحدد مقدار تعديل مقياس غطاء الخط المخصص بالنسبة إلى عرض كائن EmfPlusPen (القسم 2.2.1.7) المستخدم لرسم الخطوط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getFillHotSpot() {#getFillHotSpot--}
```
public PointF getFillHotSpot()
```


الحصول أو تعيين كائن EmfPlusPointF غير مستخدم حالياً. يجب تعيينه إلى \{0.0, 0.0\}.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setFillHotSpot(PointF value) {#setFillHotSpot-com.aspose.imaging.PointF-}
```
public void setFillHotSpot(PointF value)
```


الحصول أو تعيين كائن EmfPlusPointF غير مستخدم حالياً. يجب تعيينه إلى \{0.0, 0.0\}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getStrokeHotSpot() {#getStrokeHotSpot--}
```
public PointF getStrokeHotSpot()
```


الحصول أو تعيين كائن EmfPlusPointF غير مستخدم حالياً. يجب تعيينه إلى \{0.0, 0.0\}.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setStrokeHotSpot(PointF value) {#setStrokeHotSpot-com.aspose.imaging.PointF-}
```
public void setStrokeHotSpot(PointF value)
```


الحصول أو تعيين كائن EmfPlusPointF غير مستخدم حالياً. يجب تعيينه إلى \{0.0, 0.0\}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusCustomLineCapOptionalData getOptionalData()
```


الحصول أو تعيين كائن EmfPlusCustomLineCapOptionalData اختياري (القسم 2.2.2.14) يحدد بيانات إضافية لغطاء الخط الرسومي المخصص. المحتويات المحددة لهذا الحقل تُحدد بقيمة حقل CustomLineCapDataFlags.

**Returns:**
[EmfPlusCustomLineCapOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata)
### setOptionalData(EmfPlusCustomLineCapOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapOptionalData-}
```
public void setOptionalData(EmfPlusCustomLineCapOptionalData value)
```


الحصول أو تعيين كائن EmfPlusCustomLineCapOptionalData اختياري (القسم 2.2.2.14) يحدد بيانات إضافية لغطاء الخط الرسومي المخصص. المحتويات المحددة لهذا الحقل تُحدد بقيمة حقل CustomLineCapDataFlags.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusCustomLineCapOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata) |  |

