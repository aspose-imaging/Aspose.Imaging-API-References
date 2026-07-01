---
title: "EmfPlusFillPath"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل ملء المسار FLAGS عدد صحيح غير موقع 16‑بت يوفر معلومات حول كيفية تنفيذ العملية وعن بنية السجل."
type: docs
weight: 34
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillPath extends EmfPlusDrawingRecordType
```

سجل مسار التعبئة FLAGS: عدد صحيح غير موقع 16‑بت يوفر معلومات حول كيفية تنفيذ العملية، وكذلك حول بنية السجل. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 S X X X X X X X | ObjectId | S (بت واحد): يشير هذا البت إلى نوع البيانات في حقل BrushId. إذا كان مضبوطًا، يحدد BrushId لونًا ككائن EmfPlusARGB (القسم 2.2.2.1). إذا كان غير مضبوط، يحتوي BrushId على فهرس كائن EmfPlusBrush (القسم 2.2.1.1) في جدول كائنات EMF+. X (بت واحد): محجوز ويجب تجاهله. ObjectId (بايت واحد): فهرس كائن EmfPlusPath (القسم 2.2.1.6) الذي سيُملأ، في جدول كائنات EMF+. يجب أن تكون القيمة بين 0 و 63 inclusive.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusFillPath(EmfPlusRecord source)](#EmfPlusFillPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfPlusFillPath`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isColor()](#isColor--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الحالة ملونة. |
| [setColor(boolean value)](#setColor-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الحالة ملونة. |
| [getObjectId()](#getObjectId--) | يحصل أو يعيّن معرف الكائن. |
| [setObjectId(byte value)](#setObjectId-byte-) | يحصل أو يعيّن معرف الكائن. |
| [getBrushId()](#getBrushId--) | يحصل أو يعيّن معرف الفرشاة Brush ID عدد صحيح غير موقع 32‑بت يحدد الفرشاة، ويُحدد محتواه بت الـ S في حقل Flags. |
| [setBrushId(int value)](#setBrushId-int-) | يحصل أو يعيّن معرف الفرشاة Brush ID عدد صحيح غير موقع 32‑بت يحدد الفرشاة، ويُحدد محتواه بت الـ S في حقل Flags. |
### EmfPlusFillPath(EmfPlusRecord source) {#EmfPlusFillPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillPath(EmfPlusRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfPlusFillPath`.

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

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


يحصل أو يعيّن معرف الكائن. فهرس كائن EmfPlusPath (القسم 2.2.1.6) الذي سيُملأ، في جدول كائنات EMF+. يجب أن تكون القيمة بين 0 و 63 inclusive.

القيمة: معرف الكائن.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


يحصل أو يعيّن معرف الكائن. فهرس كائن EmfPlusPath (القسم 2.2.1.6) الذي سيُملأ، في جدول كائنات EMF+. يجب أن تكون القيمة بين 0 و 63 inclusive.

القيمة: معرف الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


يحصل أو يعيّن معرف الفرشاة Brush ID عدد صحيح غير موقع 32‑بت يحدد الفرشاة، ويُحدد محتواه بت الـ S في حقل Flags.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


يحصل أو يعيّن معرف الفرشاة Brush ID عدد صحيح غير موقع 32‑بت يحدد الفرشاة، ويُحدد محتواه بت الـ S في حقل Flags.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

