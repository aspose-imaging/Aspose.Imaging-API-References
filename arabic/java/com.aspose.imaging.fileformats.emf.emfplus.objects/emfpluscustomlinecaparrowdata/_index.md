---
title: "EmfPlusCustomLineCapArrowData"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EmfPlusCustomLineCapArrowData يحدد بيانات السهم القابلة للتعديل لغطاء خط مخصص."
type: docs
weight: 35
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecaparrowdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomBaseLineCap](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustombaselinecap)
```
public final class EmfPlusCustomLineCapArrowData extends EmfPlusCustomBaseLineCap
```

كائن EmfPlusCustomLineCapArrowData يحدد بيانات السهم القابلة للتعديل لغطاء خط مخصص.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusCustomLineCapArrowData()](#EmfPlusCustomLineCapArrowData--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getWidth()](#getWidth--) | يحصل أو يضبط قيمة عائمة بسعة 32 بت تحدد عرض رأس السهم. |
| [setWidth(float value)](#setWidth-float-) | يحصل أو يضبط قيمة عائمة بسعة 32 بت تحدد عرض رأس السهم. |
| [getHeight()](#getHeight--) | يحصل أو يضبط قيمة عائمة بسعة 32 بت تحدد ارتفاع رأس السهم. |
| [setHeight(float value)](#setHeight-float-) | يحصل أو يضبط قيمة عائمة بسعة 32 بت تحدد ارتفاع رأس السهم. |
| [getMiddleInset()](#getMiddleInset--) | يحصل أو يضبط قيمة عائمة بسعة 32 بت تحدد عدد البكسلات بين حدود رأس السهم وملئه. |
| [setMiddleInset(float value)](#setMiddleInset-float-) | يحصل أو يضبط قيمة عائمة بسعة 32 بت تحدد عدد البكسلات بين حدود رأس السهم وملئه. |
| [getFillState()](#getFillState--) | يحصل أو يضبط قيمة منطقية بسعة 32 بت تحدد ما إذا كان رأس السهم مملوءًا. |
| [setFillState(boolean value)](#setFillState-boolean-) | يحصل أو يضبط قيمة منطقية بسعة 32 بت تحدد ما إذا كان رأس السهم مملوءًا. |
| [getLineStartCap()](#getLineStartCap--) | يحصل أو يضبط عددًا صحيحًا غير موقع بسعة 32 بت يحدد القيمة في تعداد LineCap التي تشير إلى غطاء الخط الذي سيُستخدم في بداية الخط المراد رسمه |
| [setLineStartCap(int value)](#setLineStartCap-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع بسعة 32 بت يحدد القيمة في تعداد LineCap التي تشير إلى غطاء الخط الذي سيُستخدم في بداية الخط المراد رسمه |
| [getLineEndCap()](#getLineEndCap--) | يحصل أو يضبط عددًا صحيحًا غير موقع بسعة 32 بت يحدد القيمة في تعداد LineCap التي تشير إلى غطاء الخط الذي سيُستخدم في نهاية الخط المراد رسمه |
| [setLineEndCap(int value)](#setLineEndCap-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع بسعة 32 بت يحدد القيمة في تعداد LineCap التي تشير إلى غطاء الخط الذي سيُستخدم في نهاية الخط المراد رسمه |
| [getLineJoin()](#getLineJoin--) | يحصل أو يضبط عددًا صحيحًا غير موقع بسعة 32 بت يحدد القيمة في تعداد LineJoin التي تحدد كيفية ربط خطين يتم رسمهما بالقلم نفسه وتلتقي نهايتهما. |
| [setLineJoin(int value)](#setLineJoin-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع بسعة 32 بت يحدد القيمة في تعداد LineJoin التي تحدد كيفية ربط خطين يتم رسمهما بالقلم نفسه وتلتقي نهايتهما. |
| [getLineMiterLimit()](#getLineMiterLimit--) | يحصل أو يضبط قيمة عائمة بسعة 32 بت تحدد حد سمك الوصلة عند زاوية مِتر عن طريق ضبط النسبة القصوى المسموح بها لطول المِتر إلى عرض الخط. |
| [setLineMiterLimit(float value)](#setLineMiterLimit-float-) | يحصل أو يضبط قيمة عائمة بسعة 32 بت تحدد حد سمك الوصلة عند زاوية مِتر عن طريق ضبط النسبة القصوى المسموح بها لطول المِتر إلى عرض الخط. |
| [getWidthScale()](#getWidthScale--) | يحصل أو يضبط قيمة عائمة بسعة 32 بت تحدد مقدار التحجيم لكائن EmfPlusCustomLineCap بالنسبة إلى عرض قلم الرسومات المستخدم لرسم الخطوط. |
| [setWidthScale(float value)](#setWidthScale-float-) | يحصل أو يضبط قيمة عائمة بسعة 32 بت تحدد مقدار التحجيم لكائن EmfPlusCustomLineCap بالنسبة إلى عرض قلم الرسومات المستخدم لرسم الخطوط. |
| [getFillHotSpot()](#getFillHotSpot--) | الحصول أو تعيين كائن EmfPlusPointF غير مستخدم حالياً. |
| [setFillHotSpot(PointF value)](#setFillHotSpot-com.aspose.imaging.PointF-) | الحصول أو تعيين كائن EmfPlusPointF غير مستخدم حالياً. |
| [getLineHotSpot()](#getLineHotSpot--) | يحصل أو يضبط كائن EmfPlusPointF غير مستخدم حاليًا. |
| [setLineHotSpot(PointF value)](#setLineHotSpot-com.aspose.imaging.PointF-) | يحصل أو يضبط كائن EmfPlusPointF غير مستخدم حاليًا. |
### EmfPlusCustomLineCapArrowData() {#EmfPlusCustomLineCapArrowData--}
```
public EmfPlusCustomLineCapArrowData()
```


### getWidth() {#getWidth--}
```
public float getWidth()
```


يحصل أو يضبط قيمة عائمة بسعة 32 بت تحدد عرض رأس السهم.

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


يحصل أو يضبط قيمة عائمة بسعة 32 بت تحدد عرض رأس السهم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public float getHeight()
```


يحصل أو يضبط قيمة عائمة بسعة 32 بت تحدد ارتفاع رأس السهم.

**Returns:**
float
### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


يحصل أو يضبط قيمة عائمة بسعة 32 بت تحدد ارتفاع رأس السهم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getMiddleInset() {#getMiddleInset--}
```
public float getMiddleInset()
```


يحصل أو يضبط قيمة عائمة بسعة 32 بت تحدد عدد البكسلات بين حدود رأس السهم وملئه.

**Returns:**
float
### setMiddleInset(float value) {#setMiddleInset-float-}
```
public void setMiddleInset(float value)
```


يحصل أو يضبط قيمة عائمة بسعة 32 بت تحدد عدد البكسلات بين حدود رأس السهم وملئه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getFillState() {#getFillState--}
```
public boolean getFillState()
```


يحصل أو يضبط قيمة منطقية بسعة 32 بت تحدد ما إذا كان رأس السهم مملوءًا. إذا لم يكن رأس السهم مملوءًا، يتم رسم الحد فقط.

**Returns:**
boolean
### setFillState(boolean value) {#setFillState-boolean-}
```
public void setFillState(boolean value)
```


يحصل أو يضبط قيمة منطقية بسعة 32 بت تحدد ما إذا كان رأس السهم مملوءًا. إذا لم يكن رأس السهم مملوءًا، يتم رسم الحد فقط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getLineStartCap() {#getLineStartCap--}
```
public int getLineStartCap()
```


يحصل أو يضبط عددًا صحيحًا غير موقع بسعة 32 بت يحدد القيمة في تعداد LineCap التي تشير إلى غطاء الخط الذي سيُستخدم في بداية الخط المراد رسمه

**Returns:**
int
### setLineStartCap(int value) {#setLineStartCap-int-}
```
public void setLineStartCap(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع بسعة 32 بت يحدد القيمة في تعداد LineCap التي تشير إلى غطاء الخط الذي سيُستخدم في بداية الخط المراد رسمه

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getLineEndCap() {#getLineEndCap--}
```
public int getLineEndCap()
```


يحصل أو يضبط عددًا صحيحًا غير موقع بسعة 32 بت يحدد القيمة في تعداد LineCap التي تشير إلى غطاء الخط الذي سيُستخدم في نهاية الخط المراد رسمه

**Returns:**
int
### setLineEndCap(int value) {#setLineEndCap-int-}
```
public void setLineEndCap(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع بسعة 32 بت يحدد القيمة في تعداد LineCap التي تشير إلى غطاء الخط الذي سيُستخدم في نهاية الخط المراد رسمه

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getLineJoin() {#getLineJoin--}
```
public int getLineJoin()
```


يحصل أو يضبط عددًا صحيحًا غير موقع بسعة 32 بت يحدد القيمة في تعداد LineJoin التي تحدد كيفية ربط خطين يتم رسمهما بالقلم نفسه وتلتقي نهايتهما. عند تقاطع نهايتي الخطين، تجعل وصلة الخط الاتصال يبدو أكثر استمرارية.

**Returns:**
int
### setLineJoin(int value) {#setLineJoin-int-}
```
public void setLineJoin(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع بسعة 32 بت يحدد القيمة في تعداد LineJoin التي تحدد كيفية ربط خطين يتم رسمهما بالقلم نفسه وتلتقي نهايتهما. عند تقاطع نهايتي الخطين، تجعل وصلة الخط الاتصال يبدو أكثر استمرارية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getLineMiterLimit() {#getLineMiterLimit--}
```
public float getLineMiterLimit()
```


يحصل أو يضبط قيمة عائمة بسعة 32 بت تحدد حد سمك الوصلة عند زاوية مِتر عن طريق ضبط النسبة القصوى المسموح بها لطول المِتر إلى عرض الخط.

**Returns:**
float
### setLineMiterLimit(float value) {#setLineMiterLimit-float-}
```
public void setLineMiterLimit(float value)
```


يحصل أو يضبط قيمة عائمة بسعة 32 بت تحدد حد سمك الوصلة عند زاوية مِتر عن طريق ضبط النسبة القصوى المسموح بها لطول المِتر إلى عرض الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


يحصل أو يضبط قيمة عائمة بسعة 32 بت تحدد مقدار التحجيم لكائن EmfPlusCustomLineCap بالنسبة إلى عرض قلم الرسومات المستخدم لرسم الخطوط.

**Returns:**
float
### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


يحصل أو يضبط قيمة عائمة بسعة 32 بت تحدد مقدار التحجيم لكائن EmfPlusCustomLineCap بالنسبة إلى عرض قلم الرسومات المستخدم لرسم الخطوط.

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

### getLineHotSpot() {#getLineHotSpot--}
```
public PointF getLineHotSpot()
```


يحصل أو يضبط كائن EmfPlusPointF غير مستخدم حاليًا. يجب تعيينه إلى \{0.0, 0.0\}.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setLineHotSpot(PointF value) {#setLineHotSpot-com.aspose.imaging.PointF-}
```
public void setLineHotSpot(PointF value)
```


يحصل أو يضبط كائن EmfPlusPointF غير مستخدم حاليًا. يجب تعيينه إلى \{0.0, 0.0\}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

