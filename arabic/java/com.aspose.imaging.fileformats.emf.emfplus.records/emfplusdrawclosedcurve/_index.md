---
title: "EmfPlusDrawClosedCurve"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusDrawClosedCurve يحدد رسم منحنى كاردينال مغلق"
type: docs
weight: 18
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawClosedCurve extends EmfPlusDrawingRecordType
```

سجل EmfPlusDrawClosedCurve يحدد رسم منحنى كاردينال مغلق
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusDrawClosedCurve(EmfPlusRecord source)](#EmfPlusDrawClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ مثيلاً جديدًا من الفئة `EmfPlusDrawClosedCurve`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getObjectId()](#getObjectId--) | يحصل أو يعيّن معرف الكائن. |
| [setObjectId(byte value)](#setObjectId-byte-) | يحصل أو يعيّن معرف الكائن. |
| [getCompressed()](#getCompressed--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusDrawClosedCurve` مضغوطًا. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusDrawClosedCurve` مضغوطًا. |
| [getRelative()](#getRelative--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusDrawClosedCurve` نسبيًا. |
| [setRelative(boolean value)](#setRelative-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusDrawClosedCurve` نسبيًا. |
| [getTension()](#getTension--) | يحصل أو يعيّن التوتر، وهو عدد عائم 32‑بت يحدد مدى انحناء المنحنى بشكل ضيق أثناء مروره عبر النقاط. |
| [setTension(float value)](#setTension-float-) | يحصل أو يعيّن التوتر، وهو عدد عائم 32‑بت يحدد مدى انحناء المنحنى بشكل ضيق أثناء مروره عبر النقاط. |
| [getPointData()](#getPointData--) | يحصل أو يعيّن بيانات النقطة مصفوفة من Count نقاط تحدد نقاط النهاية للخطوط التي تُعرّف المنحنى المكعب. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | يحصل أو يعيّن بيانات النقطة مصفوفة من Count نقاط تحدد نقاط النهاية للخطوط التي تُعرّف المنحنى المكعب. |
### EmfPlusDrawClosedCurve(EmfPlusRecord source) {#EmfPlusDrawClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawClosedCurve(EmfPlusRecord source)
```


ينشئ مثيلاً جديدًا من الفئة `EmfPlusDrawClosedCurve`. RecordType - عدد صحيح غير موقع 16‑بت يحدد هذا النوع من السجلات كـ EmfPlusDrawClosedCurve من تعداد RecordType (القسم 2.1.1.1). يجب أن تكون القيمة 0x4017.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


يحصل أو يعيّن معرف الكائن. فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+ لرسم المنحنى المغلق. يجب أن تكون القيمة بين 0 و 63 شاملًا.

القيمة: معرف الكائن.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


يحصل أو يعيّن معرف الكائن. فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+ لرسم المنحنى المغلق. يجب أن تكون القيمة بين 0 و 63 شاملًا.

القيمة: معرف الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

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

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusDrawClosedCurve` نسبيًا. تشير هذه البتة إلى ما إذا كان حقل PointData يحدد مواقع نسبية أو مطلقة. إذا تم تعيينها، يحدد كل عنصر في PointData موقعًا في مساحة الإحداثيات يكون نسبياً إلى الموقع المحدد بالعنصر السابق في المصفوفة. بالنسبة للعنصر الأول في PointData، يُفترض وجود موقع سابق عند الإحداثيات (0,0). إذا لم يتم تعيينها، يحدد PointData مواقع مطلقة وفقًا لعلم C. ملاحظة: إذا تم تعيين هذا العلم، يكون علم Compressed (أعلاه) غير معرف ويجب تجاهله

القيمة: `true` إذا كان نسبيًا؛ وإلا `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusDrawClosedCurve` نسبيًا. تشير هذه البتة إلى ما إذا كان حقل PointData يحدد مواقع نسبية أو مطلقة. إذا تم تعيينها، يحدد كل عنصر في PointData موقعًا في مساحة الإحداثيات يكون نسبياً إلى الموقع المحدد بالعنصر السابق في المصفوفة. بالنسبة للعنصر الأول في PointData، يُفترض وجود موقع سابق عند الإحداثيات (0,0). إذا لم يتم تعيينها، يحدد PointData مواقع مطلقة وفقًا لعلم C. ملاحظة: إذا تم تعيين هذا العلم، يكون علم Compressed (أعلاه) غير معرف ويجب تجاهله

القيمة: `true` إذا كان نسبيًا؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

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

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


يحصل أو يعيّن بيانات النقاط. مصفوفة من نقاط Count تحدد نقاط النهاية للخطوط التي تُعرّف المنحنى. في منحنى كاردينال مغلق، يستمر المنحنى عبر النقطة الأخيرة في مصفوفة PointData ويتصل بالنقطة الأولى في المصفوفة. نوع البيانات في هذه المصفوفة يُحدد بواسطة حقل Flags، كما يلي: نوع البيانات معنى EmfPlusPointR object (القسم 2.2.2.37) إذا كان علم P مُحددًا في Flags، فإن النقاط تحدد مواقع نسبية. EmfPlusPointF object (القسم 2.2.2.36) إذا كان علما P و C مُحددين في حقل Flags، فإن النقاط تحدد مواقع مطلقة. EmfPlusPoint object (القسم 2.2.2.35) إذا كان علم P غير مُحدد وعلم C مُحدد في حقل Flags، فإن النقاط تحدد مواقع نسبية.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


يحصل أو يعيّن بيانات النقاط. مصفوفة من نقاط Count تحدد نقاط النهاية للخطوط التي تُعرّف المنحنى. في منحنى كاردينال مغلق، يستمر المنحنى عبر النقطة الأخيرة في مصفوفة PointData ويتصل بالنقطة الأولى في المصفوفة. نوع البيانات في هذه المصفوفة يُحدد بواسطة حقل Flags، كما يلي: نوع البيانات معنى EmfPlusPointR object (القسم 2.2.2.37) إذا كان علم P مُحددًا في Flags، فإن النقاط تحدد مواقع نسبية. EmfPlusPointF object (القسم 2.2.2.36) إذا كان علما P و C مُحددين في حقل Flags، فإن النقاط تحدد مواقع مطلقة. EmfPlusPoint object (القسم 2.2.2.35) إذا كان علم P غير مُحدد وعلم C مُحدد في حقل Flags، فإن النقاط تحدد مواقع نسبية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

