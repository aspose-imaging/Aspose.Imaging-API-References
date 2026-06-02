---
title: "EmfPlusFillRegion"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يسجل EmfPlusFillRegion يحدد تعبئة داخل منطقة رسومات."
type: docs
weight: 38
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillRegion extends EmfPlusDrawingRecordType
```

يسجل EmfPlusFillRegion يحدد تعبئة داخل منطقة رسومات.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusFillRegion(EmfPlusRecord source)](#EmfPlusFillRegion-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ مثيلاً جديداً من الفئة `EmfPlusFillRegion`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getObjectId()](#getObjectId--) | يحصل أو يعيّن معرف الكائن. |
| [setObjectId(byte value)](#setObjectId-byte-) | يحصل أو يعيّن معرف الكائن. |
| [isColor()](#isColor--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه النسخة ملونة. |
| [setColor(boolean value)](#setColor-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه النسخة ملونة. |
| [getBrushId()](#getBrushId--) | يحصل أو يعيّن معرف الفرشاة عددًا صحيحًا غير موقع 32‑بت يحدد الفرشاة، ومحتواه يُحدد بواسطة بت S في حقل العلامات. |
| [setBrushId(int value)](#setBrushId-int-) | يحصل أو يعيّن معرف الفرشاة عددًا صحيحًا غير موقع 32‑بت يحدد الفرشاة، ومحتواه يُحدد بواسطة بت S في حقل العلامات. |
### EmfPlusFillRegion(EmfPlusRecord source) {#EmfPlusFillRegion-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillRegion(EmfPlusRecord source)
```


ينشئ مثيلاً جديداً من الفئة `EmfPlusFillRegion`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


يحصل أو يعيّن معرف الكائن. فهرس كائن EmfPlusRegion (القسم 2.2.1.8) للتعبئة، في جدول كائنات EMF+. يجب أن تكون القيمة بين الصفر و63، شاملة.

القيمة: معرف الكائن.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


يحصل أو يعيّن معرف الكائن. فهرس كائن EmfPlusRegion (القسم 2.2.1.8) للتعبئة، في جدول كائنات EMF+. يجب أن تكون القيمة بين الصفر و63، شاملة.

القيمة: معرف الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

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

