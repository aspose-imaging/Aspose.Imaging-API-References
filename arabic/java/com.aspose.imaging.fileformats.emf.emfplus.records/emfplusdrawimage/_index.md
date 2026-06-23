---
title: "EmfPlusDrawImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusDrawImage يحدد رسم صورة مُقاسة."
type: docs
weight: 22
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawImage extends EmfPlusDrawingRecordType
```

سجل EmfPlusDrawImage يحدد رسم صورة مُقاسة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusDrawImage(EmfPlusRecord source)](#EmfPlusDrawImage-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ مثيلاً جديدًا من الفئة `EmfPlusDrawImage`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCompressed()](#getCompressed--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان PointData مضغوطاً. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان PointData مضغوطاً. |
| [getObjectId()](#getObjectId--) | يحصل أو يعيّن معرف الكائن. |
| [setObjectId(byte value)](#setObjectId-byte-) | يحصل أو يعيّن معرف الكائن. |
| [getImageAttributesId()](#getImageAttributesId--) | يحصل أو يضبط معرف سمات الصورة عدد صحيح غير موقع 32-بت يحدد فهرس كائن EmfPlusImageAttributes اختياري (القسم 2.2.1.5) في جدول كائنات EMF+. |
| [setImageAttributesId(int value)](#setImageAttributesId-int-) | يحصل أو يضبط معرف سمات الصورة عدد صحيح غير موقع 32-بت يحدد فهرس كائن EmfPlusImageAttributes اختياري (القسم 2.2.1.5) في جدول كائنات EMF+. |
| [getRectData()](#getRectData--) | يحصل أو يضبط بيانات المستطيل إما كائن EmfPlusRect أو EmfPlusRectF يحدد صندوق الحدود للصورة. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | يحصل أو يضبط بيانات المستطيل إما كائن EmfPlusRect أو EmfPlusRectF يحدد صندوق الحدود للصورة. |
| [getSrcRect()](#getSrcRect--) | يحصل أو يضبط مستطيل المصدر كائن EmfPlusRectF يحدد جزءًا من الصورة ليتم عرضه. |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | يحصل أو يضبط مستطيل المصدر كائن EmfPlusRectF يحدد جزءًا من الصورة ليتم عرضه. |
| [getSrcUnit()](#getSrcUnit--) | يحصل أو يضبط وحدة المصدر عدد صحيح موقع 32-بت يحدد وحدات الحقل SrcRect. |
| [setSrcUnit(int value)](#setSrcUnit-int-) | يحصل أو يضبط وحدة المصدر عدد صحيح موقع 32-بت يحدد وحدات الحقل SrcRect. |
### EmfPlusDrawImage(EmfPlusRecord source) {#EmfPlusDrawImage-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawImage(EmfPlusRecord source)
```


ينشئ مثيلاً جديدًا من الفئة `EmfPlusDrawImage`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان PointData مضغوطاً. إذا تم الضبط، يحتوي RectData على كائن EmfPlusRect (القسم 2.2.2.38). إذا لم يتم الضبط، يحتوي RectData على كائن EmfPlusRectF (القسم 2.2.2.39).

القيمة: `true` إذا كان مضغوطًا؛ وإلا `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان PointData مضغوطاً. إذا تم الضبط، يحتوي RectData على كائن EmfPlusRect (القسم 2.2.2.38). إذا لم يتم الضبط، يحتوي RectData على كائن EmfPlusRectF (القسم 2.2.2.39).

القيمة: `true` إذا كان مضغوطًا؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


يحصل أو يعيّن معرف الكائن. فهرس كائن EmfPlusImage (القسم 2.2.1.4) في جدول كائنات EMF+، الذي يحدد الصورة المراد عرضها. يجب أن تكون القيمة بين الصفر و 63 شاملًا.

القيمة: معرف الكائن.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


يحصل أو يعيّن معرف الكائن. فهرس كائن EmfPlusImage (القسم 2.2.1.4) في جدول كائنات EMF+، الذي يحدد الصورة المراد عرضها. يجب أن تكون القيمة بين الصفر و 63 شاملًا.

القيمة: معرف الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getImageAttributesId() {#getImageAttributesId--}
```
public int getImageAttributesId()
```


يحصل أو يضبط معرف سمات الصورة عدد صحيح غير موقع 32-بت يحدد فهرس كائن EmfPlusImageAttributes اختياري (القسم 2.2.1.5) في جدول كائنات EMF+.

**Returns:**
int
### setImageAttributesId(int value) {#setImageAttributesId-int-}
```
public void setImageAttributesId(int value)
```


يحصل أو يضبط معرف سمات الصورة عدد صحيح غير موقع 32-بت يحدد فهرس كائن EmfPlusImageAttributes اختياري (القسم 2.2.1.5) في جدول كائنات EMF+.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


يحصل أو يضبط بيانات المستطيل إما كائن EmfPlusRect أو EmfPlusRectF يحدد صندوق الحدود للصورة. الجزء من الصورة المحدد بالحقل SrcRect يتم تحجيمه ليتناسب مع هذا المستطيل.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


يحصل أو يضبط بيانات المستطيل إما كائن EmfPlusRect أو EmfPlusRectF يحدد صندوق الحدود للصورة. الجزء من الصورة المحدد بالحقل SrcRect يتم تحجيمه ليتناسب مع هذا المستطيل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


يحصل أو يضبط مستطيل المصدر كائن EmfPlusRectF يحدد جزءًا من الصورة ليتم عرضه. الجزء من الصورة المحدد بهذا المستطيل يتم تحجيمه ليتناسب مع مستطيل الوجهة المحدد بحقل RectData.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


يحصل أو يضبط مستطيل المصدر كائن EmfPlusRectF يحدد جزءًا من الصورة ليتم عرضه. الجزء من الصورة المحدد بهذا المستطيل يتم تحجيمه ليتناسب مع مستطيل الوجهة المحدد بحقل RectData.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcUnit() {#getSrcUnit--}
```
public int getSrcUnit()
```


يحصل أو يضبط وحدة المصدر عدد صحيح موقع 32-بت يحدد وحدات الحقل SrcRect. يجب أن يكون عضو UnitTypePixel من تعداد UnitType (القسم 2.1.1.33).

**Returns:**
int
### setSrcUnit(int value) {#setSrcUnit-int-}
```
public void setSrcUnit(int value)
```


يحصل أو يضبط وحدة المصدر عدد صحيح موقع 32-بت يحدد وحدات الحقل SrcRect. يجب أن يكون عضو UnitTypePixel من تعداد UnitType (القسم 2.1.1.33).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

