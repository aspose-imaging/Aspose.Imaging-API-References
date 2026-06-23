---
title: "EmfPlusDrawBeziers"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusDrawBeziers يحدد رسم تسلسل من منحنيات بيزيه المتصلة."
type: docs
weight: 17
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawBeziers extends EmfPlusDrawingRecordType
```

سجل EmfPlusDrawBeziers يحدد رسم تسلسل من منحنيات بيزيه المتصلة. ترتيب نقاط بيانات بيزيه هو نقطة البداية، نقطة التحكم 1، نقطة التحكم 2 ونقطة النهاية. لمزيد من المعلومات راجع [MSDN-DrawBeziers].
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusDrawBeziers(EmfPlusRecord source)](#EmfPlusDrawBeziers-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ مثيلاً جديدًا من الفئة `EmfPlusDrawBeziers`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCompressed()](#getCompressed--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان PointData مضغوطاً. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان PointData مضغوطاً. |
| [getRelative()](#getRelative--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت PointData نسبية. |
| [setRelative(boolean value)](#setRelative-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت PointData نسبية. |
| [getObjectId()](#getObjectId--) | يحصل أو يعيّن معرف الكائن. |
| [setObjectId(byte value)](#setObjectId-byte-) | يحصل أو يعيّن معرف الكائن. |
| [getPointData()](#getPointData--) | يحصل أو يعيّن بيانات النقطة مصفوفة من Count نقاط تحدد نقاط البداية والنهاية ونقاط التحكم لمنحنيات بيزيه. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | يحصل أو يعيّن بيانات النقطة مصفوفة من Count نقاط تحدد نقاط البداية والنهاية ونقاط التحكم لمنحنيات بيزيه. |
### EmfPlusDrawBeziers(EmfPlusRecord source) {#EmfPlusDrawBeziers-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawBeziers(EmfPlusRecord source)
```


ينشئ مثيلاً جديدًا من الفئة `EmfPlusDrawBeziers`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت PointData مضغوطة. إذا تم الضبط، تحدد PointData مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات صحيحة 16‑بت. إذا تم الإلغاء، تحدد PointData مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات عائمة 32‑بت. ملاحظة: إذا تم ضبط علامة Relative (أدناه)، تكون هذه العلامة غير معرفة ويجب تجاهلها.

القيمة: `true` إذا كان مضغوطًا؛ وإلا `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت PointData مضغوطة. إذا تم الضبط، تحدد PointData مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات صحيحة 16‑بت. إذا تم الإلغاء، تحدد PointData مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات عائمة 32‑بت. ملاحظة: إذا تم ضبط علامة Relative (أدناه)، تكون هذه العلامة غير معرفة ويجب تجاهلها.

القيمة: `true` إذا كان مضغوطًا؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت PointData نسبية. إذا تم الضبط، كل عنصر في PointData يحدد موقعًا في مساحة الإحداثيات يكون نسبياً إلى الموقع المحدد بالعنصر السابق في المصفوفة. في حالة العنصر الأول في PointData، يُفترض موقع سابق عند الإحداثيات (0,0). إذا تم الإلغاء، تحدد PointData مواقع مطلقة وفقًا لعلامة C. ملاحظة: إذا تم ضبط هذه العلامة، تكون علامة C (أعلاه) غير معرفة ويجب تجاهلها.

القيمة: `true` إذا كان نسبيًا؛ وإلا `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت PointData نسبية. إذا تم الضبط، كل عنصر في PointData يحدد موقعًا في مساحة الإحداثيات يكون نسبياً إلى الموقع المحدد بالعنصر السابق في المصفوفة. في حالة العنصر الأول في PointData، يُفترض موقع سابق عند الإحداثيات (0,0). إذا تم الإلغاء، تحدد PointData مواقع مطلقة وفقًا لعلامة C. ملاحظة: إذا تم ضبط هذه العلامة، تكون علامة C (أعلاه) غير معرفة ويجب تجاهلها.

القيمة: `true` إذا كان نسبيًا؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


يحصل أو يعيّن معرف الكائن. فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+ لرسم منحنيات بيزيه. يجب أن تكون القيمة بين الصفر و63 شاملًا.

القيمة: معرف الكائن.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


يحصل أو يعيّن معرف الكائن. فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+ لرسم منحنيات بيزيه. يجب أن تكون القيمة بين الصفر و63 شاملًا.

القيمة: معرف الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


يحصل أو يعيّن بيانات النقطة مصفوفة من Count نقاط تحدد نقاط البداية والنهاية ونقاط التحكم لمنحنيات بيزيه. إحداثية النهاية لمنحنى بيزيه واحد هي إحداثية البداية للمنحنى التالي. تُستخدم نقاط التحكم لإنتاج تأثير بيزيه. نوع البيانات في هذه المصفوفة يُحدد بواسطة حقل Flags، كما يلي: نوع البيانات معنى كائن EmfPlusPointR (القسم 2.2.2.37) إذا تم ضبط علامة P في Flags، فإن النقاط تحدد مواقع نسبية. كائن EmfPlusPointF (القسم 2.2.2.36) إذا كانت بتا P و C غير مفعلة في حقل Flags، فإن النقاط تحدد مواقع مطلقة. كائن EmfPlusPoint (القسم 2.2.2.35) إذا كانت بتة P غير مفعلة وتم تفعيل بتة C في حقل Flags، فإن النقاط تحدد مواقع نسبية. لا يمر منحنى بيزيه عبر نقاط التحكم الخاصة به. نقاط التحكم تعمل كـ

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


يحصل أو يعيّن بيانات النقطة مصفوفة من Count نقاط تحدد نقاط البداية والنهاية ونقاط التحكم لمنحنيات بيزيه. إحداثية النهاية لمنحنى بيزيه واحد هي إحداثية البداية للمنحنى التالي. تُستخدم نقاط التحكم لإنتاج تأثير بيزيه. نوع البيانات في هذه المصفوفة يُحدد بواسطة حقل Flags، كما يلي: نوع البيانات معنى كائن EmfPlusPointR (القسم 2.2.2.37) إذا تم ضبط علامة P في Flags، فإن النقاط تحدد مواقع نسبية. كائن EmfPlusPointF (القسم 2.2.2.36) إذا كانت بتا P و C غير مفعلة في حقل Flags، فإن النقاط تحدد مواقع مطلقة. كائن EmfPlusPoint (القسم 2.2.2.35) إذا كانت بتة P غير مفعلة وتم تفعيل بتة C في حقل Flags، فإن النقاط تحدد مواقع نسبية. لا يمر منحنى بيزيه عبر نقاط التحكم الخاصة به. نقاط التحكم تعمل كـ

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

