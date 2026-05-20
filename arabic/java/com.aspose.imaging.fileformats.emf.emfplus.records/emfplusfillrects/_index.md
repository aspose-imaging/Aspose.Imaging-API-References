---
title: "EmfPlusFillRects"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يسجل EmfPlusFillRects يحدد تعبئة داخل سلسلة من المستطيلات."
type: docs
weight: 37
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillRects extends EmfPlusDrawingRecordType
```

يسجل EmfPlusFillRects يحدد تعبئة داخل سلسلة من المستطيلات.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusFillRects(EmfPlusRecord source)](#EmfPlusFillRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfPlusFillRects`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isColor()](#isColor--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه النسخة ملونة. |
| [setColor(boolean value)](#setColor-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه النسخة ملونة. |
| [getCompressed()](#getCompressed--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا `EmfPlusFillRects` مضغوطًا. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا `EmfPlusFillRects` مضغوطًا. |
| [getBrushId()](#getBrushId--) | يحصل أو يعيّن معرف الفرشاة عددًا صحيحًا غير موقع 32‑بت يحدد الفرشاة، ومحتواه يُحدد بواسطة بت S في حقل العلامات. |
| [setBrushId(int value)](#setBrushId-int-) | يحصل أو يعيّن معرف الفرشاة عددًا صحيحًا غير موقع 32‑بت يحدد الفرشاة، ومحتواه يُحدد بواسطة بت S في حقل العلامات. |
| [getRectData()](#getRectData--) | يحصل أو يضبط بيانات المستطيل. مصفوفة إما من كائنات EmfPlusRect أو EmfPlusRectF بطول Count التي تحدد بيانات المستطيل. |
| [setRectData(RectangleF[] value)](#setRectData-com.aspose.imaging.RectangleF---) | يحصل أو يضبط بيانات المستطيل. مصفوفة إما من كائنات EmfPlusRect أو EmfPlusRectF بطول Count التي تحدد بيانات المستطيل. |
### EmfPlusFillRects(EmfPlusRecord source) {#EmfPlusFillRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillRects(EmfPlusRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfPlusFillRects`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### isColor() {#isColor--}
```
public boolean isColor()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا الكائن لونه. إذا تم التعيين، فإن BrushId يحدد لونًا ككائن EmfPlusARGB (القسم 2.2.2.1). إذا لم يتم التعيين، فإن BrushId يحتوي على فهرس كائن EmfPlusBrush (القسم 2.2.1.1) في جدول كائنات EMF+.

القيمة: `true` إذا كانت هذه النسخة ملونة؛ وإلا `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا الكائن لونه. إذا تم التعيين، فإن BrushId يحدد لونًا ككائن EmfPlusARGB (القسم 2.2.2.1). إذا لم يتم التعيين، فإن BrushId يحتوي على فهرس كائن EmfPlusBrush (القسم 2.2.1.1) في جدول كائنات EMF+.

القيمة: `true` إذا كانت هذه النسخة ملونة؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا `EmfPlusFillRects` مضغوطًا. إذا تم ضبطها، يحتوي RectData على كائن EmfPlusRect (القسم 2.2.2.38). إذا كانت غير مضبوطة، يحتوي RectData على كائن EmfPlusRectF (القسم 2.2.2.39).

القيمة: `true` إذا كانت مضغوطة؛ وإلا `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا `EmfPlusFillRects` مضغوطًا. إذا تم ضبطها، يحتوي RectData على كائن EmfPlusRect (القسم 2.2.2.38). إذا كانت غير مضبوطة، يحتوي RectData على كائن EmfPlusRectF (القسم 2.2.2.39).

القيمة: `true` إذا كانت مضغوطة؛ وإلا `false`.

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

### getRectData() {#getRectData--}
```
public RectangleF[] getRectData()
```


يحصل أو يضبط بيانات المستطيل. مصفوفة إما من كائنات EmfPlusRect أو EmfPlusRectF بطول Count التي تحدد بيانات المستطيل.

**Returns:**
com.aspose.imaging.RectangleF[]
### setRectData(RectangleF[] value) {#setRectData-com.aspose.imaging.RectangleF---}
```
public void setRectData(RectangleF[] value)
```


يحصل أو يضبط بيانات المستطيل. مصفوفة إما من كائنات EmfPlusRect أو EmfPlusRectF بطول Count التي تحدد بيانات المستطيل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RectangleF\[\]](../../com.aspose.imaging/rectanglef) |  |

