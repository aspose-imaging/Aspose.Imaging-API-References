---
title: "EmfPlusDrawCurve"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusDrawCurve يحدد رسم منحنى كاردينال ملاحظة ObjectID 1 بايت فهرس كائن EmfPlusPen القسم 2.2.1.7 في جدول كائنات EMF لرسم المنحنى."
type: docs
weight: 19
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawCurve extends EmfPlusDrawingRecordType
```

سجل EmfPlusDrawCurve يحدد رسم منحنى كاردينال ملاحظة: ObjectID (1 بايت): فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+ لرسم المنحنى. يجب أن تكون القيمة بين الصفر و63، شاملة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusDrawCurve(EmfPlusRecord source)](#EmfPlusDrawCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ مثيلاً جديداً من الفئة `EmfPlusDrawCurve`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCompressed()](#getCompressed--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusDrawClosedCurve` مضغوطاً. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusDrawClosedCurve` مضغوطاً. |
| [getObjectId()](#getObjectId--) | يحصل أو يعيّن معرف الكائن. |
| [setObjectId(byte value)](#setObjectId-byte-) | يحصل أو يعيّن معرف الكائن. |
| [getTension()](#getTension--) | يحصل أو يعيّن التوتر، وهو عدد عائم 32-bit يحدد مدى انحناء المنحنى بشكل ضيق أثناء مروره عبر النقاط. |
| [setTension(float value)](#setTension-float-) | يحصل أو يعيّن التوتر، وهو عدد عائم 32-bit يحدد مدى انحناء المنحنى بشكل ضيق أثناء مروره عبر النقاط. |
| [getNumSegments()](#getNumSegments--) | يحصل أو يعيّن عدد المقاطع عدد صحيح غير موقع 32‑بت يحدد عدد مقاطع الخط التي تشكّل المنحنى. |
| [setNumSegments(int value)](#setNumSegments-int-) | يحصل أو يعيّن عدد المقاطع عدد صحيح غير موقع 32‑بت يحدد عدد مقاطع الخط التي تشكّل المنحنى. |
| [getPointData()](#getPointData--) | يحصل أو يعيّن مصفوفة إما من أعداد صحيحة موقعة 32‑بت أو أعداد عائمة 32‑بت بطول Count تحدد قيم إحداثيات نقاط النهاية للخطوط التي سيتم رسمها. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | يحصل أو يعيّن مصفوفة إما من أعداد صحيحة موقعة 32‑بت أو أعداد عائمة 32‑بت بطول Count تحدد قيم إحداثيات نقاط النهاية للخطوط التي سيتم رسمها. |
### EmfPlusDrawCurve(EmfPlusRecord source) {#EmfPlusDrawCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawCurve(EmfPlusRecord source)
```


ينشئ مثيلاً جديداً من الفئة `EmfPlusDrawCurve`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusDrawClosedCurve` مضغوطًا. هذه البتة تشير إلى ما إذا كان حقل PointData يحدد بيانات مضغوطة. إذا تم التعيين، يحدد PointData مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات صحيحة 16-بت. إذا تم إلغاء التعيين، يحدد PointData مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات عائمة 32-بت. ملاحظة: إذا تم تعيين علم Relative (أدناه)، تكون هذه العلامة غير معرفة ويجب تجاهلها

القيمة: `true` إذا كانت مضغوطة؛ وإلا `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusDrawClosedCurve` مضغوطًا. هذه البتة تشير إلى ما إذا كان حقل PointData يحدد بيانات مضغوطة. إذا تم التعيين، يحدد PointData مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات صحيحة 16-بت. إذا تم إلغاء التعيين، يحدد PointData مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات عائمة 32-بت. ملاحظة: إذا تم تعيين علم Relative (أدناه)، تكون هذه العلامة غير معرفة ويجب تجاهلها

القيمة: `true` إذا كانت مضغوطة؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


يحصل أو يعيّن معرف الكائن. فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+ لرسم المنحنى. يجب أن تكون القيمة بين الصفر و63، شاملة.

القيمة: معرف الكائن.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


يحصل أو يعيّن معرف الكائن. فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+ لرسم المنحنى. يجب أن تكون القيمة بين الصفر و63، شاملة.

القيمة: معرف الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

### getTension() {#getTension--}
```
public float getTension()
```


يحصل أو يعيّن التوتر عدد عائم 32‑بت يحدد مدى انحناء المنحنى أثناء مروره عبر النقاط. القيمة 0 تعني أن المنحنى هو سلسلة من الخطوط المستقيمة. كلما زادت القيمة، يصبح المنحنى أكثر استدارة. لمزيد من المعلومات، راجع [SPLINE77] و [PETZOLD].

**Returns:**
float
### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


يحصل أو يعيّن التوتر عدد عائم 32‑بت يحدد مدى انحناء المنحنى أثناء مروره عبر النقاط. القيمة 0 تعني أن المنحنى هو سلسلة من الخطوط المستقيمة. كلما زادت القيمة، يصبح المنحنى أكثر استدارة. لمزيد من المعلومات، راجع [SPLINE77] و [PETZOLD].

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### getNumSegments() {#getNumSegments--}
```
public int getNumSegments()
```


يحصل أو يعيّن عدد المقاطع عدد صحيح غير موقع 32‑بت يحدد عدد مقاطع الخط التي تشكّل المنحنى.

**Returns:**
int
### setNumSegments(int value) {#setNumSegments-int-}
```
public void setNumSegments(int value)
```


يحصل أو يعيّن عدد المقاطع عدد صحيح غير موقع 32‑بت يحدد عدد مقاطع الخط التي تشكّل المنحنى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


يحصل أو يعيّن مصفوفة إما من أعداد صحيحة موقعة 32‑بت أو أعداد عائمة 32‑بت بطول Count تحدد قيم إحداثيات نقاط النهاية للخطوط التي سيتم رسمها.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


يحصل أو يعيّن مصفوفة إما من أعداد صحيحة موقعة 32‑بت أو أعداد عائمة 32‑بت بطول Count تحدد قيم إحداثيات نقاط النهاية للخطوط التي سيتم رسمها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

