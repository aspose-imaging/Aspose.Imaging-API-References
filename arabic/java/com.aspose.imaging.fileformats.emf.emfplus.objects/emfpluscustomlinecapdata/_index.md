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
| [getCustomLineCapDataFlags()](#getCustomLineCapDataFlags--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑bit يحدد البيانات في الحقل OptionalData. |
| [setCustomLineCapDataFlags(int value)](#setCustomLineCapDataFlags-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑bit يحدد البيانات في الحقل OptionalData. |
| [getBaseCap()](#getBaseCap--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑bit يحدد القيمة من تعداد LineCap (القسم 2.1.1.18) الذي يستند إليه غطاء الخط المخصص. |
| [setBaseCap(int value)](#setBaseCap-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑bit يحدد القيمة من تعداد LineCap (القسم 2.1.1.18) الذي يستند إليه غطاء الخط المخصص. |
| [getBaseInset()](#getBaseInset--) | يحصل أو يعيّن قيمة عائمة 32‑bit تحدد المسافة بين بداية غطاء الخط ونهاية الخط. |
| [setBaseInset(float value)](#setBaseInset-float-) | يحصل أو يعيّن قيمة عائمة 32‑bit تحدد المسافة بين بداية غطاء الخط ونهاية الخط. |
| [getStrokeStartCap()](#getStrokeStartCap--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑bit يحدد القيمة في تعداد LineCap التي تشير إلى غطاء الخط المستخدم في بداية الخط المراد رسمه. |
| [setStrokeStartCap(int value)](#setStrokeStartCap-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑bit يحدد القيمة في تعداد LineCap التي تشير إلى غطاء الخط المستخدم في بداية الخط المراد رسمه. |
| [getStrokeEndCap()](#getStrokeEndCap--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑bit يحدد القيمة في تعداد LineCap التي تشير إلى غطاء الخط الذي سيُستخدم في نهاية الخط المراد رسمه. |
| [setStrokeEndCap(int value)](#setStrokeEndCap-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑bit يحدد القيمة في تعداد LineCap التي تشير إلى غطاء الخط الذي سيُستخدم في نهاية الخط المراد رسمه. |
| [getStrokeJoin()](#getStrokeJoin--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑bit يحدد القيمة في تعداد LineJoin (القسم 2.1.1.19)، والذي يحدد كيفية ربط خطين يُرسمان بالقلم نفسه وتلتقي نهاياتهما. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑bit يحدد القيمة في تعداد LineJoin (القسم 2.1.1.19)، والذي يحدد كيفية ربط خطين يُرسمان بالقلم نفسه وتلتقي نهاياتهما. |
| [getStrokeMiterLimit()](#getStrokeMiterLimit--) | يحصل أو يعيّن قيمة عائمة 32‑bit تحتوي على حد سمك الوصلة في زاوية مسننة عن طريق ضبط النسبة القصوى المسموح بها لطول المِسْنَة إلى عرض الخط. |
| [setStrokeMiterLimit(float value)](#setStrokeMiterLimit-float-) | يحصل أو يعيّن قيمة عائمة 32‑bit تحتوي على حد سمك الوصلة في زاوية مسننة عن طريق ضبط النسبة القصوى المسموح بها لطول المِسْنَة إلى عرض الخط. |
| [getWidthScale()](#getWidthScale--) | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقدار مقياس غطاء الخط المخصص بالنسبة إلى عرض كائن EmfPlusPen (القسم 2.2.1.7) المستخدم لرسم الخطوط. |
| [setWidthScale(float value)](#setWidthScale-float-) | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقدار مقياس غطاء الخط المخصص بالنسبة إلى عرض كائن EmfPlusPen (القسم 2.2.1.7) المستخدم لرسم الخطوط. |
| [getFillHotSpot()](#getFillHotSpot--) | يحصل أو يعيّن كائن EmfPlusPointF الذي لا يُستخدم حاليًا. |
| [setFillHotSpot(PointF value)](#setFillHotSpot-com.aspose.imaging.PointF-) | يحصل أو يعيّن كائن EmfPlusPointF الذي لا يُستخدم حاليًا. |
| [getStrokeHotSpot()](#getStrokeHotSpot--) | يحصل أو يعيّن كائن EmfPlusPointF الذي لا يُستخدم حاليًا. |
| [setStrokeHotSpot(PointF value)](#setStrokeHotSpot-com.aspose.imaging.PointF-) | يحصل أو يعيّن كائن EmfPlusPointF الذي لا يُستخدم حاليًا. |
| [getOptionalData()](#getOptionalData--) | يحصل أو يعيّن كائن EmfPlusCustomLineCapOptionalData اختياري (القسم 2.2.2.14) يحدد بيانات إضافية لغطاء الخط الرسومي المخصص. |
| [setOptionalData(EmfPlusCustomLineCapOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapOptionalData-) | يحصل أو يعيّن كائن EmfPlusCustomLineCapOptionalData اختياري (القسم 2.2.2.14) يحدد بيانات إضافية لغطاء الخط الرسومي المخصص. |
### EmfPlusCustomLineCapData() {#EmfPlusCustomLineCapData--}
```
public EmfPlusCustomLineCapData()
```


### getCustomLineCapDataFlags() {#getCustomLineCapDataFlags--}
```
public int getCustomLineCapDataFlags()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑bit يحدد البيانات في الحقل OptionalData.

**Returns:**
int
### setCustomLineCapDataFlags(int value) {#setCustomLineCapDataFlags-int-}
```
public void setCustomLineCapDataFlags(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑bit يحدد البيانات في الحقل OptionalData.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑bit يحدد القيمة من تعداد LineCap (القسم 2.1.1.18) الذي يستند إليه غطاء الخط المخصص.

**Returns:**
int
### setBaseCap(int value) {#setBaseCap-int-}
```
public void setBaseCap(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑bit يحدد القيمة من تعداد LineCap (القسم 2.1.1.18) الذي يستند إليه غطاء الخط المخصص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


يحصل أو يعيّن قيمة عائمة 32‑bit تحدد المسافة بين بداية غطاء الخط ونهاية الخط.

**Returns:**
float
### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


يحصل أو يعيّن قيمة عائمة 32‑bit تحدد المسافة بين بداية غطاء الخط ونهاية الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### getStrokeStartCap() {#getStrokeStartCap--}
```
public int getStrokeStartCap()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑bit يحدد القيمة في تعداد LineCap التي تشير إلى غطاء الخط المستخدم في بداية الخط المراد رسمه.

**Returns:**
int
### setStrokeStartCap(int value) {#setStrokeStartCap-int-}
```
public void setStrokeStartCap(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑bit يحدد القيمة في تعداد LineCap التي تشير إلى غطاء الخط المستخدم في بداية الخط المراد رسمه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getStrokeEndCap() {#getStrokeEndCap--}
```
public int getStrokeEndCap()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑bit يحدد القيمة في تعداد LineCap التي تشير إلى غطاء الخط الذي سيُستخدم في نهاية الخط المراد رسمه.

**Returns:**
int
### setStrokeEndCap(int value) {#setStrokeEndCap-int-}
```
public void setStrokeEndCap(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑bit يحدد القيمة في تعداد LineCap التي تشير إلى غطاء الخط الذي سيُستخدم في نهاية الخط المراد رسمه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد القيمة في تعداد LineJoin (القسم 2.1.1.19)، الذي يحدد كيفية ربط خطين يتم رسمهما بنفس القلم وتلتقي نهايتهما. عند تقاطع نهايتي الخطين، يجعل اتصال الخط الم join يبدو أكثر استمرارية.

**Returns:**
int
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد القيمة في تعداد LineJoin (القسم 2.1.1.19)، الذي يحدد كيفية ربط خطين يتم رسمهما بنفس القلم وتلتقي نهايتهما. عند تقاطع نهايتي الخطين، يجعل اتصال الخط الم join يبدو أكثر استمرارية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getStrokeMiterLimit() {#getStrokeMiterLimit--}
```
public float getStrokeMiterLimit()
```


يحصل أو يعيّن قيمة عائمة 32‑bit تحتوي على حد سمك الوصلة في زاوية مسننة عن طريق ضبط النسبة القصوى المسموح بها لطول المِسْنَة إلى عرض الخط.

**Returns:**
float
### setStrokeMiterLimit(float value) {#setStrokeMiterLimit-float-}
```
public void setStrokeMiterLimit(float value)
```


يحصل أو يعيّن قيمة عائمة 32‑bit تحتوي على حد سمك الوصلة في زاوية مسننة عن طريق ضبط النسبة القصوى المسموح بها لطول المِسْنَة إلى عرض الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقدار مقياس غطاء الخط المخصص بالنسبة إلى عرض كائن EmfPlusPen (القسم 2.2.1.7) المستخدم لرسم الخطوط.

**Returns:**
float
### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقدار مقياس غطاء الخط المخصص بالنسبة إلى عرض كائن EmfPlusPen (القسم 2.2.1.7) المستخدم لرسم الخطوط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### getFillHotSpot() {#getFillHotSpot--}
```
public PointF getFillHotSpot()
```


يحصل أو يعيّن كائن EmfPlusPointF الذي لا يُستخدم حاليًا. يجب تعيينه إلى \{0.0, 0.0\}.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setFillHotSpot(PointF value) {#setFillHotSpot-com.aspose.imaging.PointF-}
```
public void setFillHotSpot(PointF value)
```


يحصل أو يعيّن كائن EmfPlusPointF الذي لا يُستخدم حاليًا. يجب تعيينه إلى \{0.0, 0.0\}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getStrokeHotSpot() {#getStrokeHotSpot--}
```
public PointF getStrokeHotSpot()
```


يحصل أو يعيّن كائن EmfPlusPointF الذي لا يُستخدم حاليًا. يجب تعيينه إلى \{0.0, 0.0\}.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setStrokeHotSpot(PointF value) {#setStrokeHotSpot-com.aspose.imaging.PointF-}
```
public void setStrokeHotSpot(PointF value)
```


يحصل أو يعيّن كائن EmfPlusPointF الذي لا يُستخدم حاليًا. يجب تعيينه إلى \{0.0, 0.0\}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusCustomLineCapOptionalData getOptionalData()
```


يحصل أو يعيّن كائن EmfPlusCustomLineCapOptionalData اختياري (القسم 2.2.2.14) يحدد بيانات إضافية لغطاء الخط الرسومي المخصص. المحتويات المحددة لهذا الحقل تُحدَّد بقيمة الحقل CustomLineCapDataFlags.

**Returns:**
[EmfPlusCustomLineCapOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata)
### setOptionalData(EmfPlusCustomLineCapOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapOptionalData-}
```
public void setOptionalData(EmfPlusCustomLineCapOptionalData value)
```


يحصل أو يعيّن كائن EmfPlusCustomLineCapOptionalData اختياري (القسم 2.2.2.14) يحدد بيانات إضافية لغطاء الخط الرسومي المخصص. المحتويات المحددة لهذا الحقل تُحدَّد بقيمة الحقل CustomLineCapDataFlags.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusCustomLineCapOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata) |  |

