---
title: "EmfPlusFillRects"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusFillRects يحدد تعبئة داخل مجموعة من المستطيلات"
type: docs
weight: 37
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillRects extends EmfPlusDrawingRecordType
```

سجل EmfPlusFillRects يحدد تعبئة داخل مجموعة من المستطيلات
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusFillRects(EmfPlusRecord source)](#EmfPlusFillRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | يُنشئ مثيلاً جديدًا للفئة `EmfPlusFillRects`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isColor()](#isColor--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الحالة ملونة. |
| [setColor(boolean value)](#setColor-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الحالة ملونة. |
| [getCompressed()](#getCompressed--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillRects` مضغوطًا. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillRects` مضغوطًا. |
| [getBrushId()](#getBrushId--) | يحصل أو يعيّن معرف الفرشاة، عددًا صحيحًا غير موقع 32‑بت يحدد الفرشاة، ومحتواه يُحدد بواسطة البت S في حقل العلامات. |
| [setBrushId(int value)](#setBrushId-int-) | يحصل أو يعيّن معرف الفرشاة، عددًا صحيحًا غير موقع 32‑بت يحدد الفرشاة، ومحتواه يُحدد بواسطة البت S في حقل العلامات. |
| [getRectData()](#getRectData--) | يحصل أو يعيّن بيانات المستطيل. مصفوفة من كائنات EmfPlusRect أو EmfPlusRectF بطول Count التي تُعرّف بيانات المستطيل. |
| [setRectData(RectangleF[] value)](#setRectData-com.aspose.imaging.RectangleF---) | يحصل أو يعيّن بيانات المستطيل. مصفوفة من كائنات EmfPlusRect أو EmfPlusRectF بطول Count التي تُعرّف بيانات المستطيل. |
### EmfPlusFillRects(EmfPlusRecord source) {#EmfPlusFillRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillRects(EmfPlusRecord source)
```


يُنشئ مثيلاً جديدًا للفئة `EmfPlusFillRects`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### isColor() {#isColor--}
```
public boolean isColor()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل لونيًا. إذا كان مضبوطًا، يحدد BrushId لونًا ككائن EmfPlusARGB (القسم 2.2.2.1). إذا كان غير مضبوط، يحتوي BrushId على فهرس كائن EmfPlusBrush (القسم 2.2.1.1) في جدول كائنات EMF+.

القيمة: `true` إذا كانت هذه الحالة ملونة؛ وإلا `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل لونيًا. إذا كان مضبوطًا، يحدد BrushId لونًا ككائن EmfPlusARGB (القسم 2.2.2.1). إذا كان غير مضبوط، يحتوي BrushId على فهرس كائن EmfPlusBrush (القسم 2.2.1.1) في جدول كائنات EMF+.

القيمة: `true` إذا كانت هذه الحالة ملونة؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillRects` مضغوطًا. إذا تم تعيينه، يحتوي RectData على كائن EmfPlusRect (القسم 2.2.2.38). إذا لم يتم تعيينه، يحتوي RectData على كائن EmfPlusRectF (القسم 2.2.2.39).

القيمة: `true` إذا كان مضغوطًا؛ وإلا `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillRects` مضغوطًا. إذا تم تعيينه، يحتوي RectData على كائن EmfPlusRect (القسم 2.2.2.38). إذا لم يتم تعيينه، يحتوي RectData على كائن EmfPlusRectF (القسم 2.2.2.39).

القيمة: `true` إذا كان مضغوطًا؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


يحصل أو يعيّن معرف الفرشاة، عددًا صحيحًا غير موقع 32‑بت يحدد الفرشاة، ومحتواه يُحدد بواسطة البت S في حقل العلامات.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


يحصل أو يعيّن معرف الفرشاة، عددًا صحيحًا غير موقع 32‑بت يحدد الفرشاة، ومحتواه يُحدد بواسطة البت S في حقل العلامات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getRectData() {#getRectData--}
```
public RectangleF[] getRectData()
```


يحصل أو يعيّن بيانات المستطيل. مصفوفة من كائنات EmfPlusRect أو EmfPlusRectF بطول Count التي تُعرّف بيانات المستطيل.

**Returns:**
com.aspose.imaging.RectangleF[]
### setRectData(RectangleF[] value) {#setRectData-com.aspose.imaging.RectangleF---}
```
public void setRectData(RectangleF[] value)
```


يحصل أو يعيّن بيانات المستطيل. مصفوفة من كائنات EmfPlusRect أو EmfPlusRectF بطول Count التي تُعرّف بيانات المستطيل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RectangleF\[\]](../../com.aspose.imaging/rectanglef) |  |

