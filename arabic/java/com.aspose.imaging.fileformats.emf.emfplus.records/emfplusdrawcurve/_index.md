---
title: "EmfPlusDrawCurve"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusDrawCurve يحدد رسم منحنى كاردينال ملاحظة ObjectID 1 بايت فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF لرسم المنحنى."
type: docs
weight: 19
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawCurve extends EmfPlusDrawingRecordType
```

سجل EmfPlusDrawCurve يحدد رسم منحنى كاردينال ملاحظة: ObjectID (1 بايت): فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+ لرسم المنحنى. يجب أن تكون القيمة بين 0 و 63، شاملة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusDrawCurve(EmfPlusRecord source)](#EmfPlusDrawCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ مثيلاً جديدًا من الفئة `EmfPlusDrawCurve`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCompressed()](#getCompressed--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusDrawClosedCurve` مضغوطًا. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusDrawClosedCurve` مضغوطًا. |
| [getObjectId()](#getObjectId--) | يحصل أو يعيّن معرف الكائن. |
| [setObjectId(byte value)](#setObjectId-byte-) | يحصل أو يعيّن معرف الكائن. |
| [getTension()](#getTension--) | يحصل أو يعيّن التوتر، وهو عدد عائم 32‑بت يحدد مدى انحناء المنحنى بشكل ضيق أثناء مروره عبر النقاط. |
| [setTension(float value)](#setTension-float-) | يحصل أو يعيّن التوتر، وهو عدد عائم 32‑بت يحدد مدى انحناء المنحنى بشكل ضيق أثناء مروره عبر النقاط. |
| [getNumSegments()](#getNumSegments--) | يحصل أو يضبط عدد المقاطع عدد صحيح غير موقع 32-بت يحدد عدد مقاطع الخط التي تشكل المنحنى. |
| [setNumSegments(int value)](#setNumSegments-int-) | يحصل أو يضبط عدد المقاطع عدد صحيح غير موقع 32-بت يحدد عدد مقاطع الخط التي تشكل المنحنى. |
| [getPointData()](#getPointData--) | يحصل أو يضبط مصفوفة إما من أعداد صحيحة موقعة 32-بت أو أعداد عائمة 32-بت بطول Count التي تحدد قيم إحداثيات نقاط النهاية للخطوط التي سيتم رسمها. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | يحصل أو يضبط مصفوفة إما من أعداد صحيحة موقعة 32-بت أو أعداد عائمة 32-بت بطول Count التي تحدد قيم إحداثيات نقاط النهاية للخطوط التي سيتم رسمها. |
### EmfPlusDrawCurve(EmfPlusRecord source) {#EmfPlusDrawCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawCurve(EmfPlusRecord source)
```


ينشئ مثيلاً جديدًا من الفئة `EmfPlusDrawCurve`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusDrawClosedCurve` مضغوطًا. تشير هذه البتة إلى ما إذا كان حقل PointData يحدد بيانات مضغوطة. إذا تم تعيينه، يحدد PointData مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات صحيحة 16‑bit. إذا لم يتم تعيينه، يحدد PointData مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات عائمة 32‑bit. ملاحظة: إذا تم تعيين علم Relative (أدناه)، تكون هذه العلامة غير معرفة ويجب تجاهلها

القيمة: `true` إذا كان مضغوطًا؛ وإلا `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusDrawClosedCurve` مضغوطًا. تشير هذه البتة إلى ما إذا كان حقل PointData يحدد بيانات مضغوطة. إذا تم تعيينه، يحدد PointData مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات صحيحة 16‑bit. إذا لم يتم تعيينه، يحدد PointData مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات عائمة 32‑bit. ملاحظة: إذا تم تعيين علم Relative (أدناه)، تكون هذه العلامة غير معرفة ويجب تجاهلها

القيمة: `true` إذا كان مضغوطًا؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


يحصل أو يضبط معرف الكائن. فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+ لرسم المنحنى. يجب أن تكون القيمة بين 0 و 63، شاملة.

القيمة: معرف الكائن.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


يحصل أو يضبط معرف الكائن. فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+ لرسم المنحنى. يجب أن تكون القيمة بين 0 و 63، شاملة.

القيمة: معرف الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getTension() {#getTension--}
```
public float getTension()
```


يحصل أو يعيّن التوتر، وهو عدد عائم 32‑بت يحدد مدى انحناء المنحنى بشكل ضيق أثناء مروره عبر النقاط. القيمة 0 تشير إلى أن المنحنى هو سلسلة من الخطوط المستقيمة. كلما زادت القيمة، يصبح المنحنى أكثر استدارة. لمزيد من المعلومات، راجع [SPLINE77] و [PETZOLD].

**Returns:**
float
### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


يحصل أو يعيّن التوتر، وهو عدد عائم 32‑بت يحدد مدى انحناء المنحنى بشكل ضيق أثناء مروره عبر النقاط. القيمة 0 تشير إلى أن المنحنى هو سلسلة من الخطوط المستقيمة. كلما زادت القيمة، يصبح المنحنى أكثر استدارة. لمزيد من المعلومات، راجع [SPLINE77] و [PETZOLD].

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getNumSegments() {#getNumSegments--}
```
public int getNumSegments()
```


يحصل أو يضبط عدد المقاطع عدد صحيح غير موقع 32-بت يحدد عدد مقاطع الخط التي تشكل المنحنى.

**Returns:**
int
### setNumSegments(int value) {#setNumSegments-int-}
```
public void setNumSegments(int value)
```


يحصل أو يضبط عدد المقاطع عدد صحيح غير موقع 32-بت يحدد عدد مقاطع الخط التي تشكل المنحنى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


يحصل أو يضبط مصفوفة إما من أعداد صحيحة موقعة 32-بت أو أعداد عائمة 32-بت بطول Count التي تحدد قيم إحداثيات نقاط النهاية للخطوط التي سيتم رسمها.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


يحصل أو يضبط مصفوفة إما من أعداد صحيحة موقعة 32-بت أو أعداد عائمة 32-بت بطول Count التي تحدد قيم إحداثيات نقاط النهاية للخطوط التي سيتم رسمها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

