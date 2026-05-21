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
| [EmfPlusDrawImage(EmfPlusRecord source)](#EmfPlusDrawImage-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ مثيلاً جديداً من الفئة `EmfPlusDrawImage`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCompressed()](#getCompressed--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت بيانات النقطة PointData مضغوطة. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت بيانات النقطة PointData مضغوطة. |
| [getObjectId()](#getObjectId--) | يحصل أو يعيّن معرف الكائن. |
| [setObjectId(byte value)](#setObjectId-byte-) | يحصل أو يعيّن معرف الكائن. |
| [getImageAttributesId()](#getImageAttributesId--) | يحصل أو يعيّن معرف سمات الصورة عدد صحيح غير موقع 32‑بت يحدد فهرس كائن EmfPlusImageAttributes اختياري (القسم 2.2.1.5) في جدول كائنات EMF+. |
| [setImageAttributesId(int value)](#setImageAttributesId-int-) | يحصل أو يعيّن معرف سمات الصورة عدد صحيح غير موقع 32‑بت يحدد فهرس كائن EmfPlusImageAttributes اختياري (القسم 2.2.1.5) في جدول كائنات EMF+. |
| [getRectData()](#getRectData--) | يحصل أو يعيّن بيانات المستطيل إما كائن EmfPlusRect أو EmfPlusRectF يحدد صندوق الحد للصورة. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | يحصل أو يعيّن بيانات المستطيل إما كائن EmfPlusRect أو EmfPlusRectF يحدد صندوق الحد للصورة. |
| [getSrcRect()](#getSrcRect--) | يحصل أو يعيّن مستطيل المصدر كائن EmfPlusRectF يحدد جزءاً من الصورة ليتم عرضه. |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | يحصل أو يعيّن مستطيل المصدر كائن EmfPlusRectF يحدد جزءاً من الصورة ليتم عرضه. |
| [getSrcUnit()](#getSrcUnit--) | يحصل أو يعيّن وحدة المصدر عدد صحيح موقع 32‑بت يحدد وحدات حقل SrcRect. |
| [setSrcUnit(int value)](#setSrcUnit-int-) | يحصل أو يعيّن وحدة المصدر عدد صحيح موقع 32‑بت يحدد وحدات حقل SrcRect. |
### EmfPlusDrawImage(EmfPlusRecord source) {#EmfPlusDrawImage-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawImage(EmfPlusRecord source)
```


ينشئ مثيلاً جديداً من الفئة `EmfPlusDrawImage`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت بيانات النقطة PointData مضغوطة. إذا تم التعيين، يحتوي RectData على كائن EmfPlusRect (القسم 2.2.2.38). إذا لم يُحدد، يحتوي RectData على كائن EmfPlusRectF (القسم 2.2.2.39).

القيمة: `true` إذا كانت مضغوطة؛ وإلا `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت بيانات النقطة PointData مضغوطة. إذا تم التعيين، يحتوي RectData على كائن EmfPlusRect (القسم 2.2.2.38). إذا لم يُحدد، يحتوي RectData على كائن EmfPlusRectF (القسم 2.2.2.39).

القيمة: `true` إذا كانت مضغوطة؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


يحصل أو يضبط معرف الكائن. فهرس كائن EmfPlusImage (القسم 2.2.1.4) في جدول كائنات EMF+، الذي يحدد الصورة التي سيتم عرضها. يجب أن تكون القيمة بين الصفر و63، شاملًا.

القيمة: معرف الكائن.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


يحصل أو يضبط معرف الكائن. فهرس كائن EmfPlusImage (القسم 2.2.1.4) في جدول كائنات EMF+، الذي يحدد الصورة التي سيتم عرضها. يجب أن تكون القيمة بين الصفر و63، شاملًا.

القيمة: معرف الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

### getImageAttributesId() {#getImageAttributesId--}
```
public int getImageAttributesId()
```


يحصل أو يعيّن معرف سمات الصورة عدد صحيح غير موقع 32‑بت يحدد فهرس كائن EmfPlusImageAttributes اختياري (القسم 2.2.1.5) في جدول كائنات EMF+.

**Returns:**
int
### setImageAttributesId(int value) {#setImageAttributesId-int-}
```
public void setImageAttributesId(int value)
```


يحصل أو يعيّن معرف سمات الصورة عدد صحيح غير موقع 32‑بت يحدد فهرس كائن EmfPlusImageAttributes اختياري (القسم 2.2.1.5) في جدول كائنات EMF+.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


يحصل أو يعيّن بيانات المستطيل إما كائن EmfPlusRect أو EmfPlusRectF يحدد صندوق الحد للصورة. الجزء من الصورة المحدد بحقل SrcRect يُقاس ليتناسب مع هذا المستطيل.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


يحصل أو يعيّن بيانات المستطيل إما كائن EmfPlusRect أو EmfPlusRectF يحدد صندوق الحد للصورة. الجزء من الصورة المحدد بحقل SrcRect يُقاس ليتناسب مع هذا المستطيل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


يحصل أو يعيّن مستطيل المصدر كائن EmfPlusRectF يحدد جزءاً من الصورة ليتم عرضه. الجزء من الصورة المحدد بهذا المستطيل يُقاس ليتناسب مع مستطيل الوجهة المحدد بحقل RectData.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


يحصل أو يعيّن مستطيل المصدر كائن EmfPlusRectF يحدد جزءاً من الصورة ليتم عرضه. الجزء من الصورة المحدد بهذا المستطيل يُقاس ليتناسب مع مستطيل الوجهة المحدد بحقل RectData.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcUnit() {#getSrcUnit--}
```
public int getSrcUnit()
```


يحصل أو يعيّن وحدة المصدر عدد صحيح موقع 32‑بت يحدد وحدات حقل SrcRect. يجب أن تكون الوحدة هي العنصر UnitTypePixel من تعداد UnitType (القسم 2.1.1.33).

**Returns:**
int
### setSrcUnit(int value) {#setSrcUnit-int-}
```
public void setSrcUnit(int value)
```


يحصل أو يعيّن وحدة المصدر عدد صحيح موقع 32‑بت يحدد وحدات حقل SrcRect. يجب أن تكون الوحدة هي العنصر UnitTypePixel من تعداد UnitType (القسم 2.1.1.33).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

