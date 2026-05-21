---
title: "EmfPlusFillEllipse"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يسجل EmfPlusFillEllipse يحدد تعبئة داخل إهليلج."
type: docs
weight: 33
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillEllipse extends EmfPlusDrawingRecordType
```

يسجل EmfPlusFillEllipse يحدد تعبئة داخل إهليلج.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusFillEllipse(EmfPlusRecord source)](#EmfPlusFillEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ مثيلاً جديداً من الفئة `EmfPlusFillEllipse`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isColor()](#isColor--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه النسخة ملونة. |
| [setColor(boolean value)](#setColor-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه النسخة ملونة. |
| [isCompressed()](#isCompressed--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل مضغوطاً. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل مضغوطاً. |
| [getBrushId()](#getBrushId--) | يحصل أو يعيّن معرف الفرشاة عددًا صحيحًا غير موقع 32‑بت يحدد الفرشاة، ومحتواها يُحدَّد بواسطة البت S في حقل Flags. |
| [setBrushId(int value)](#setBrushId-int-) | يحصل أو يعيّن معرف الفرشاة عددًا صحيحًا غير موقع 32‑بت يحدد الفرشاة، ومحتواها يُحدَّد بواسطة البت S في حقل Flags. |
| [getRectData()](#getRectData--) | يحصل أو يعيّن بيانات المستطيل إما ككائن EmfPlusRect أو EmfPlusRectF يحدد الصندوق المحيط بالقطع الناقص |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | يحصل أو يعيّن بيانات المستطيل إما ككائن EmfPlusRect أو EmfPlusRectF يحدد الصندوق المحيط بالقطع الناقص |
### EmfPlusFillEllipse(EmfPlusRecord source) {#EmfPlusFillEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillEllipse(EmfPlusRecord source)
```


ينشئ مثيلاً جديداً من الفئة `EmfPlusFillEllipse`.

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


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل مضغوطاً. إذا تم تعيينها، يحتوي RectData على كائن EmfPlusRect (القسم 2.2.2.38). إذا تم إلغاء تعيينها، يحتوي RectData على كائن EmfPlusRectF (القسم 2.2.2.39).

القيمة: `true` إذا كان هذا المثيل مضغوطاً؛ وإلا `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل مضغوطاً. إذا تم تعيينها، يحتوي RectData على كائن EmfPlusRect (القسم 2.2.2.38). إذا تم إلغاء تعيينها، يحتوي RectData على كائن EmfPlusRectF (القسم 2.2.2.39).

القيمة: `true` إذا كان هذا المثيل مضغوطاً؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


يحصل أو يعيّن معرف الفرشاة وهو عدد صحيح غير موقع 32‑بت يحدد الفرشاة، محتواها يُحدد بواسطة البت S في حقل Flags. يُستخدم هذا التعريف لملء داخل القطع الناقص.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


يحصل أو يعيّن معرف الفرشاة وهو عدد صحيح غير موقع 32‑بت يحدد الفرشاة، محتواها يُحدد بواسطة البت S في حقل Flags. يُستخدم هذا التعريف لملء داخل القطع الناقص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


يحصل أو يعيّن بيانات المستطيل إما ككائن EmfPlusRect أو EmfPlusRectF يحدد الصندوق المحيط بالقطع الناقص

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


يحصل أو يعيّن بيانات المستطيل إما ككائن EmfPlusRect أو EmfPlusRectF يحدد الصندوق المحيط بالقطع الناقص

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

