---
title: "EmfPlusDrawString"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusDrawString يحدد إخراج النص مع تنسيق السلسلة"
type: docs
weight: 28
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawString extends EmfPlusDrawingRecordType
```

سجل EmfPlusDrawString يحدد إخراج النص مع تنسيق السلسلة
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusDrawString(EmfPlusRecord source)](#EmfPlusDrawString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ مثيلاً جديداً من الفئة `EmfPlusDrawString`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isColor()](#isColor--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الحالة ملونة. |
| [setColor(boolean value)](#setColor-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الحالة ملونة. |
| [getObjectId()](#getObjectId--) | يحصل أو يعيّن معرف الكائن. |
| [setObjectId(byte value)](#setObjectId-byte-) | يحصل أو يعيّن معرف الكائن. |
| [getBrushId()](#getBrushId--) | يحصل أو يعيّن معرف الفرشاة عددًا صحيحًا غير موقع 32‑بت يحدد الفرشاة، حيث يتم تحديد محتواها بواسطة بت S في حقل Flags. |
| [setBrushId(int value)](#setBrushId-int-) | يحصل أو يعيّن معرف الفرشاة عددًا صحيحًا غير موقع 32‑بت يحدد الفرشاة، حيث يتم تحديد محتواها بواسطة بت S في حقل Flags. |
| [getFormatId()](#getFormatId--) | يحصل أو يعيّن معرف التنسيق عددًا صحيحًا غير موقع 32‑بت يحدد فهرس كائن EmfPlusStringFormat اختياري (القسم 2.2.1.9) في جدول كائنات EMF+. |
| [setFormatId(int value)](#setFormatId-int-) | يحصل أو يعيّن معرف التنسيق عددًا صحيحًا غير موقع 32‑بت يحدد فهرس كائن EmfPlusStringFormat اختياري (القسم 2.2.1.9) في جدول كائنات EMF+. |
| [getLength()](#getLength--) | يحصل أو يعيّن الطول عددًا صحيحًا غير موقع 32‑بت يحدد عدد الأحرف في السلسلة. |
| [setLength(int value)](#setLength-int-) | يحصل أو يعيّن الطول عددًا صحيحًا غير موقع 32‑بت يحدد عدد الأحرف في السلسلة. |
| [getLayoutRect()](#getLayoutRect--) | يحصل أو يعيّن مستطيل التخطيط كائن EmfPlusRectF (القسم 2.2.2.39) الذي يحدد المنطقة المحيطة بالوجهة التي ستستقبل السلسلة. |
| [setLayoutRect(RectangleF value)](#setLayoutRect-com.aspose.imaging.RectangleF-) | يحصل أو يعيّن مستطيل التخطيط كائن EmfPlusRectF (القسم 2.2.2.39) الذي يحدد المنطقة المحيطة بالوجهة التي ستستقبل السلسلة. |
| [getStringData()](#getStringData--) | يحصل أو يعيّن بيانات السلسلة مصفوفة من أحرف Unicode 16‑بت تحدد السلسلة التي سيتم رسمها. |
| [setStringData(String value)](#setStringData-java.lang.String-) | يحصل أو يعيّن بيانات السلسلة مصفوفة من أحرف Unicode 16‑بت تحدد السلسلة التي سيتم رسمها. |
### EmfPlusDrawString(EmfPlusRecord source) {#EmfPlusDrawString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawString(EmfPlusRecord source)
```


ينشئ مثيلاً جديداً من الفئة `EmfPlusDrawString`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### isColor() {#isColor--}
```
public boolean isColor()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الحالة ملونة. إذا تم الضبط، يحدد BrushId اللون ككائن EmfPlusARGB (القسم 2.2.2.1). إذا لم يتم الضبط، يحتوي BrushId على فهرس كائن EmfPlusBrush (القسم 2.2.1.1) في جدول كائنات EMF+.

القيمة: `true` إذا كانت هذه الحالة ملونة؛ وإلا `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الحالة ملونة. إذا تم الضبط، يحدد BrushId اللون ككائن EmfPlusARGB (القسم 2.2.2.1). إذا لم يتم الضبط، يحتوي BrushId على فهرس كائن EmfPlusBrush (القسم 2.2.1.1) في جدول كائنات EMF+.

القيمة: `true` إذا كانت هذه الحالة ملونة؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


يحصل أو يعيّن معرف الكائن. فهرس كائن EmfPlusFont (القسم 2.2.1.3) في جدول كائنات EMF+ لتصيير النص. يجب أن تكون القيمة بين الصفر والستة وثلاثين، شاملة.

القيمة: معرف الكائن.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


يحصل أو يعيّن معرف الكائن. فهرس كائن EmfPlusFont (القسم 2.2.1.3) في جدول كائنات EMF+ لتصيير النص. يجب أن تكون القيمة بين الصفر والستة وثلاثين، شاملة.

القيمة: معرف الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


يحصل أو يعيّن معرف الفرشاة عددًا صحيحًا غير موقع 32‑بت يحدد الفرشاة، حيث يتم تحديد محتواها بواسطة بت S في حقل Flags. يُستخدم هذا التعريف لتلوين لون نص المقدمة؛ أي فقط الأحرف نفسها.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


يحصل أو يعيّن معرف الفرشاة عددًا صحيحًا غير موقع 32‑بت يحدد الفرشاة، حيث يتم تحديد محتواها بواسطة بت S في حقل Flags. يُستخدم هذا التعريف لتلوين لون نص المقدمة؛ أي فقط الأحرف نفسها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getFormatId() {#getFormatId--}
```
public int getFormatId()
```


يحصل أو يعيّن معرف التنسيق عددًا صحيحًا غير موقع 32‑بت يحدد فهرس كائن EmfPlusStringFormat اختياري (القسم 2.2.1.9) في جدول كائنات EMF+. يحدد هذا الكائن معلومات تخطيط النص والتعديلات العرضية التي تُطبق على السلسلة.

**Returns:**
int
### setFormatId(int value) {#setFormatId-int-}
```
public void setFormatId(int value)
```


يحصل أو يعيّن معرف التنسيق عددًا صحيحًا غير موقع 32‑بت يحدد فهرس كائن EmfPlusStringFormat اختياري (القسم 2.2.1.9) في جدول كائنات EMF+. يحدد هذا الكائن معلومات تخطيط النص والتعديلات العرضية التي تُطبق على السلسلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getLength() {#getLength--}
```
public int getLength()
```


يحصل أو يعيّن الطول عددًا صحيحًا غير موقع 32‑بت يحدد عدد الأحرف في السلسلة.

**Returns:**
int
### setLength(int value) {#setLength-int-}
```
public void setLength(int value)
```


يحصل أو يعيّن الطول عددًا صحيحًا غير موقع 32‑بت يحدد عدد الأحرف في السلسلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getLayoutRect() {#getLayoutRect--}
```
public RectangleF getLayoutRect()
```


يحصل أو يعيّن مستطيل التخطيط كائن EmfPlusRectF (القسم 2.2.2.39) الذي يحدد المنطقة المحيطة بالوجهة التي ستستقبل السلسلة.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setLayoutRect(RectangleF value) {#setLayoutRect-com.aspose.imaging.RectangleF-}
```
public void setLayoutRect(RectangleF value)
```


يحصل أو يعيّن مستطيل التخطيط كائن EmfPlusRectF (القسم 2.2.2.39) الذي يحدد المنطقة المحيطة بالوجهة التي ستستقبل السلسلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getStringData() {#getStringData--}
```
public String getStringData()
```


يحصل أو يعيّن بيانات السلسلة مصفوفة من أحرف Unicode 16‑بت تحدد السلسلة التي سيتم رسمها.

**Returns:**
java.lang.String
### setStringData(String value) {#setStringData-java.lang.String-}
```
public void setStringData(String value)
```


يحصل أو يعيّن بيانات السلسلة مصفوفة من أحرف Unicode 16‑بت تحدد السلسلة التي سيتم رسمها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

