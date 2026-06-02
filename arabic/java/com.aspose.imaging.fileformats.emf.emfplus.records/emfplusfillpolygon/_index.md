---
title: "EmfPlusFillPolygon"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يسجل EmfPlusFillPolygon يحدد تعبئة داخل مضلع."
type: docs
weight: 36
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillPolygon extends EmfPlusDrawingRecordType
```

يسجل EmfPlusFillPolygon يحدد تعبئة داخل مضلع.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusFillPolygon(EmfPlusRecord source)](#EmfPlusFillPolygon-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ مثيلاً جديداً من الفئة `EmfPlusFillPolygon`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isColor()](#isColor--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه النسخة ملونة. |
| [setColor(boolean value)](#setColor-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه النسخة ملونة. |
| [isCompressed()](#isCompressed--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل مضغوطاً. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل مضغوطاً. |
| [isRelative()](#isRelative--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل نسبياً. |
| [setRelative(boolean value)](#setRelative-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل نسبياً. |
| [getBrushId()](#getBrushId--) | يحصل أو يعيّن معرف الفرشاة عددًا صحيحًا غير موقع 32‑بت يحدد الفرشاة، ومحتواه يُحدد بواسطة بت S في حقل العلامات. |
| [setBrushId(int value)](#setBrushId-int-) | يحصل أو يعيّن معرف الفرشاة عددًا صحيحًا غير موقع 32‑بت يحدد الفرشاة، ومحتواه يُحدد بواسطة بت S في حقل العلامات. |
| [getPointData()](#getPointData--) | يحصل أو يعيّن بيانات النقاط مصفوفة من Count نقطة تحدد رؤوس المضلع. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | يحصل أو يعيّن بيانات النقاط مصفوفة من Count نقطة تحدد رؤوس المضلع. |
### EmfPlusFillPolygon(EmfPlusRecord source) {#EmfPlusFillPolygon-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillPolygon(EmfPlusRecord source)
```


ينشئ مثيلاً جديداً من الفئة `EmfPlusFillPolygon`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### isColor() {#isColor--}
```
public boolean isColor()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه النسخة ملونة. إذا تم تعيينها، يحدد BrushId لونًا ككائن EmfPlusARGB (القسم 2.2.2.1). إذا لم تُعيّن، يحتوي BrushId على فهرس كائن EmfPlusBrush (القسم 2.2.1.1) في جدول كائنات EMF+.

القيمة: `true` إذا كانت هذه النسخة ملونة؛ وإلا `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه النسخة ملونة. إذا تم تعيينها، يحدد BrushId لونًا ككائن EmfPlusARGB (القسم 2.2.2.1). إذا لم تُعيّن، يحتوي BrushId على فهرس كائن EmfPlusBrush (القسم 2.2.1.1) في جدول كائنات EMF+.

القيمة: `true` إذا كانت هذه النسخة ملونة؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### isCompressed() {#isCompressed--}
```
public boolean isCompressed()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا الكائن مضغوطًا. إذا تم التعيين، فإن PointData يحدد المواقع المطلقة في مساحة الإحداثيات باستخدام إحداثيات صحيحة 16-بت. إذا لم يتم التعيين، فإن PointData يحدد المواقع المطلقة في مساحة الإحداثيات باستخدام إحداثيات عائمة 32-بت.

القيمة: `true` إذا كان هذا المثيل مضغوطاً؛ وإلا `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا الكائن مضغوطًا. إذا تم التعيين، فإن PointData يحدد المواقع المطلقة في مساحة الإحداثيات باستخدام إحداثيات صحيحة 16-بت. إذا لم يتم التعيين، فإن PointData يحدد المواقع المطلقة في مساحة الإحداثيات باستخدام إحداثيات عائمة 32-بت.

القيمة: `true` إذا كان هذا المثيل مضغوطاً؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### isRelative() {#isRelative--}
```
public boolean isRelative()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا الكائن نسبيًا. إذا تم التعيين، فإن كل عنصر في PointData يحدد موقعًا في مساحة الإحداثيات يكون نسبيًا للموقع المحدد بواسطة العنصر السابق في المصفوفة. في حالة العنصر الأول في PointData، يُفترض وجود موقع سابق عند الإحداثيات (0,0). إذا لم يتم التعيين، فإن PointData يحدد المواقع المطلقة وفقًا لعلامة C.

القيمة: `true` إذا كان هذا الكائن نسبيًا؛ وإلا `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا الكائن نسبيًا. إذا تم التعيين، فإن كل عنصر في PointData يحدد موقعًا في مساحة الإحداثيات يكون نسبيًا للموقع المحدد بواسطة العنصر السابق في المصفوفة. في حالة العنصر الأول في PointData، يُفترض وجود موقع سابق عند الإحداثيات (0,0). إذا لم يتم التعيين، فإن PointData يحدد المواقع المطلقة وفقًا لعلامة C.

القيمة: `true` إذا كان هذا الكائن نسبيًا؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


يحصل أو يعيّن معرف الفرشاة عددًا صحيحًا غير موقع 32‑بت يحدد الفرشاة، ومحتواه يُحدد بواسطة بت S في حقل العلامات.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


يحصل أو يعيّن معرف الفرشاة عددًا صحيحًا غير موقع 32‑بت يحدد الفرشاة، ومحتواه يُحدد بواسطة بت S في حقل العلامات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


يحصل أو يعيّن بيانات النقاط مصفوفة من نقاط Count التي تحدد رؤوس المضلع. أول نقطتين في المصفوفة تحددان الجانب الأول من المضلع. كل نقطة إضافية تحدد جانبًا جديدًا، تشمل رؤوسه النقطة والنقطة السابقة. إذا لم تتطابق النقطة الأخيرة مع الأولى، فإنهما تحددان الجانب الأخير من المضلع.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


يحصل أو يعيّن بيانات النقاط مصفوفة من نقاط Count التي تحدد رؤوس المضلع. أول نقطتين في المصفوفة تحددان الجانب الأول من المضلع. كل نقطة إضافية تحدد جانبًا جديدًا، تشمل رؤوسه النقطة والنقطة السابقة. إذا لم تتطابق النقطة الأخيرة مع الأولى، فإنهما تحددان الجانب الأخير من المضلع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

