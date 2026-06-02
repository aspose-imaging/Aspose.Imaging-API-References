---
title: "EmfPlusDrawLines"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusDrawlLines يحدد رسم سلسلة من الخطوط المتصلة."
type: docs
weight: 24
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawLines extends EmfPlusDrawingRecordType
```

سجل EmfPlusDrawlLines يحدد رسم سلسلة من الخطوط المتصلة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusDrawLines(EmfPlusRecord source)](#EmfPlusDrawLines-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ مثيلاً جديداً من الفئة `EmfPlusDrawLines`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getObjectId()](#getObjectId--) | يحصل أو يعيّن معرف الكائن. |
| [setObjectId(byte value)](#setObjectId-byte-) | يحصل أو يعيّن معرف الكائن. |
| [getCompressed()](#getCompressed--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusDrawClosedCurve` مضغوطاً. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusDrawClosedCurve` مضغوطاً. |
| [getRelative()](#getRelative--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusDrawClosedCurve` نسبياً. |
| [setRelative(boolean value)](#setRelative-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusDrawClosedCurve` نسبياً. |
| [getClosedShape()](#getClosedShape--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [closed shape]. |
| [setClosedShape(boolean value)](#setClosedShape-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [closed shape]. |
| [getPointData()](#getPointData--) | يحصل أو يعيّن بيانات النقطة مصفوفة من Count نقطة تحدد نقاط البداية والنهاية للخطوط التي سيتم رسمها. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | يحصل أو يعيّن بيانات النقطة مصفوفة من Count نقطة تحدد نقاط البداية والنهاية للخطوط التي سيتم رسمها. |
### EmfPlusDrawLines(EmfPlusRecord source) {#EmfPlusDrawLines-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawLines(EmfPlusRecord source)
```


ينشئ مثيلاً جديداً من الفئة `EmfPlusDrawLines`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


يحصل أو يعيّن معرف الكائن. فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+ لرسم الخطوط. يجب أن تكون القيمة بين الصفر و63، شاملة.

القيمة: معرف الكائن.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


يحصل أو يعيّن معرف الكائن. فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+ لرسم الخطوط. يجب أن تكون القيمة بين الصفر و63، شاملة.

القيمة: معرف الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

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

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusDrawClosedCurve` نسبيًا. هذه البتة تشير إلى ما إذا كان حقل PointData يحدد مواقع نسبية أو مطلقة. إذا تم التعيين، كل عنصر في PointData يحدد موقعًا في مساحة الإحداثيات يكون نسبياً إلى الموقع المحدد بالعنصر السابق في المصفوفة. في حالة العنصر الأول في PointData، يُفترض وجود موقع سابق عند الإحداثيات (0,0). إذا تم إلغاء التعيين، يحدد PointData مواقع مطلقة وفقًا لعلم C. ملاحظة: إذا تم تعيين هذا العلم، يكون علم Compressed (أعلاه) غير معرف ويجب تجاهله

القيمة: `true` إذا كان نسبيًا؛ وإلا `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusDrawClosedCurve` نسبيًا. هذه البتة تشير إلى ما إذا كان حقل PointData يحدد مواقع نسبية أو مطلقة. إذا تم التعيين، كل عنصر في PointData يحدد موقعًا في مساحة الإحداثيات يكون نسبياً إلى الموقع المحدد بالعنصر السابق في المصفوفة. في حالة العنصر الأول في PointData، يُفترض وجود موقع سابق عند الإحداثيات (0,0). إذا تم إلغاء التعيين، يحدد PointData مواقع مطلقة وفقًا لعلم C. ملاحظة: إذا تم تعيين هذا العلم، يكون علم Compressed (أعلاه) غير معرف ويجب تجاهله

القيمة: `true` إذا كان نسبيًا؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getClosedShape() {#getClosedShape--}
```
public boolean getClosedShape()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [closed shape].

القيمة: `true` إذا كان [closed shape]؛ وإلا `false`.

**Returns:**
boolean
### setClosedShape(boolean value) {#setClosedShape-boolean-}
```
public void setClosedShape(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [closed shape].

القيمة: `true` إذا كان [closed shape]؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


يحصل أو يعيّن بيانات النقطة مصفوفة من Count نقطة تحدد نقاط البداية والنهاية للخطوط التي سيتم رسمها.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


يحصل أو يعيّن بيانات النقطة مصفوفة من Count نقطة تحدد نقاط البداية والنهاية للخطوط التي سيتم رسمها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

