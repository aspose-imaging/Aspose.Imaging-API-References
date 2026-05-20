---
title: "EmfPlusDrawImagePoints"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusDrawImagePoints يحدد رسم صورة مُقاسة داخل متوازي أضلاع."
type: docs
weight: 23
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawImagePoints extends EmfPlusDrawingRecordType
```

سجل EmfPlusDrawImagePoints يحدد رسم صورة مُقاسة داخل متوازي أضلاع.

يمكن لـ EmfPlusImage تحديد إما صورة نقطية أو ملف تعريف. يمكن تعديل ألوان الصورة أثناء العرض. يمكن تصحيحها، تعتيمها، إضاءتها، وإزالتها.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusDrawImagePoints(EmfPlusRecord source)](#EmfPlusDrawImagePoints-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfPlusDrawImagePoints`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCompressed()](#getCompressed--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت بيانات النقطة PointData مضغوطة. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت بيانات النقطة PointData مضغوطة. |
| [getObjectId()](#getObjectId--) | يحصل أو يعيّن معرف الكائن. |
| [setObjectId(byte value)](#setObjectId-byte-) | يحصل أو يعيّن معرف الكائن. |
| [getApplyingAnEffect()](#getApplyingAnEffect--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان [applying an effect]. |
| [setApplyingAnEffect(boolean value)](#setApplyingAnEffect-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان [applying an effect]. |
| [getRelative()](#getRelative--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا `EmfPlusDrawImagePoints` نسبيًا. |
| [setRelative(boolean value)](#setRelative-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا `EmfPlusDrawImagePoints` نسبيًا. |
| [getImageAttributesId()](#getImageAttributesId--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحتوي على فهرس كائن EmfPlusImageAttributes الاختياري (القسم 2.2.1.5) في جدول كائنات EMF+. |
| [setImageAttributesId(int value)](#setImageAttributesId-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحتوي على فهرس كائن EmfPlusImageAttributes الاختياري (القسم 2.2.1.5) في جدول كائنات EMF+. |
| [getSrcUnit()](#getSrcUnit--) | يحصل أو يضبط عددًا صحيحًا موقعًا 32 بت يحدد وحدات حقل SrcRect. |
| [setSrcUnit(int value)](#setSrcUnit-int-) | يحصل أو يضبط عددًا صحيحًا موقعًا 32 بت يحدد وحدات حقل SrcRect. |
| [getSrcRect()](#getSrcRect--) | يحصل أو يضبط كائن EmfPlusRectF (القسم 2.2.2.39) الذي يحدد جزءًا من الصورة ليتم عرضه. |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | يحصل أو يضبط كائن EmfPlusRectF (القسم 2.2.2.39) الذي يحدد جزءًا من الصورة ليتم عرضه. |
| [getPointData()](#getPointData--) | يحصل أو يضبط مصفوفة من نقاط Count التي تحدد ثلاث نقاط لمتوازي أضلاع. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | يحصل أو يضبط مصفوفة من نقاط Count التي تحدد ثلاث نقاط لمتوازي أضلاع. |
### EmfPlusDrawImagePoints(EmfPlusRecord source) {#EmfPlusDrawImagePoints-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawImagePoints(EmfPlusRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfPlusDrawImagePoints`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كانت PointData مضغوطة. تشير هذه البت إلى ما إذا كان حقل PointData يحدد بيانات مضغوطة. إذا تم ضبطه، تحدد PointData المواقع المطلقة في مساحة الإحداثيات باستخدام إحداثيات عددية 16‑بت. إذا لم يتم ضبطه، تحدد PointData المواقع المطلقة في مساحة الإحداثيات باستخدام إحداثيات عائمة 32‑بت. ملاحظة: إذا تم ضبط علم P (أدناه)، فإن هذه العلامة غير معرفة ويجب تجاهلها.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كانت PointData مضغوطة. تشير هذه البت إلى ما إذا كان حقل PointData يحدد بيانات مضغوطة. إذا تم ضبطه، تحدد PointData المواقع المطلقة في مساحة الإحداثيات باستخدام إحداثيات عددية 16‑بت. إذا لم يتم ضبطه، تحدد PointData المواقع المطلقة في مساحة الإحداثيات باستخدام إحداثيات عائمة 32‑بت. ملاحظة: إذا تم ضبط علم P (أدناه)، فإن هذه العلامة غير معرفة ويجب تجاهلها.

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

### getApplyingAnEffect() {#getApplyingAnEffect--}
```
public boolean getApplyingAnEffect()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [applying an effect]. هذه البتة تشير إلى أن عرض الصورة يتضمن تطبيق تأثير. إذا تم تعيينها، يجب أن يكون كائن من فئة Effect قد تم تحديده في سجل EmfPlusSerializableObject سابق (القسم 2.3.5.2).

القيمة: `true` إذا كان [applying an effect]؛ وإلا `false`.

**Returns:**
boolean
### setApplyingAnEffect(boolean value) {#setApplyingAnEffect-boolean-}
```
public void setApplyingAnEffect(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [applying an effect]. هذه البتة تشير إلى أن عرض الصورة يتضمن تطبيق تأثير. إذا تم تعيينها، يجب أن يكون كائن من فئة Effect قد تم تحديده في سجل EmfPlusSerializableObject سابق (القسم 2.3.5.2).

القيمة: `true` إذا كان [applying an effect]؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusDrawImagePoints` نسبياً. هذه البتة تشير إلى ما إذا كان حقل PointData يحدد مواقع نسبية أو مطلقة. إذا تم تعيينها، كل عنصر في PointData يحدد موقعاً في فضاء الإحداثيات يكون نسبياً إلى الموقع المحدد بواسطة العنصر السابق في المصفوفة. في حالة العنصر الأول في PointData، يُفترض وجود موقع سابق عند الإحداثيات (0,0). إذا تم إلغاء تعيينها، يحدد PointData مواقع مطلقة وفقاً لعلامة C. ملاحظة: إذا تم تعيين هذه العلامة، تكون علامة C (أعلاه) غير معرفة ويجب تجاهلها.

القيمة: `true` إذا كان نسبيًا؛ وإلا `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusDrawImagePoints` نسبياً. هذه البتة تشير إلى ما إذا كان حقل PointData يحدد مواقع نسبية أو مطلقة. إذا تم تعيينها، كل عنصر في PointData يحدد موقعاً في فضاء الإحداثيات يكون نسبياً إلى الموقع المحدد بواسطة العنصر السابق في المصفوفة. في حالة العنصر الأول في PointData، يُفترض وجود موقع سابق عند الإحداثيات (0,0). إذا تم إلغاء تعيينها، يحدد PointData مواقع مطلقة وفقاً لعلامة C. ملاحظة: إذا تم تعيين هذه العلامة، تكون علامة C (أعلاه) غير معرفة ويجب تجاهلها.

القيمة: `true` إذا كان نسبيًا؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getImageAttributesId() {#getImageAttributesId--}
```
public int getImageAttributesId()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحتوي على فهرس كائن EmfPlusImageAttributes الاختياري (القسم 2.2.1.5) في جدول كائنات EMF+.

القيمة: معرف خصائص الصورة.

**Returns:**
int
### setImageAttributesId(int value) {#setImageAttributesId-int-}
```
public void setImageAttributesId(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحتوي على فهرس كائن EmfPlusImageAttributes الاختياري (القسم 2.2.1.5) في جدول كائنات EMF+.

القيمة: معرف خصائص الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getSrcUnit() {#getSrcUnit--}
```
public int getSrcUnit()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد وحدات حقل SrcRect. يجب أن يكون قيمة UnitPixel من تعداد UnitType (القسم 2.1.1.33).

القيمة: وحدة المصدر.

**Returns:**
int
### setSrcUnit(int value) {#setSrcUnit-int-}
```
public void setSrcUnit(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد وحدات حقل SrcRect. يجب أن يكون قيمة UnitPixel من تعداد UnitType (القسم 2.1.1.33).

القيمة: وحدة المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


يحصل أو يضبط كائن EmfPlusRectF (القسم 2.2.2.39) الذي يحدد جزءًا من الصورة ليتم عرضه.

القيمة: مستطيل المصدر.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


يحصل أو يضبط كائن EmfPlusRectF (القسم 2.2.2.39) الذي يحدد جزءًا من الصورة ليتم عرضه.

القيمة: مستطيل المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


يحصل أو يعيّن مصفوفة من Count نقطة تحدد ثلاث نقاط لمتوازي أضلاع. تمثل النقاط الثلاث الزاوية العلوية اليسرى، العلوية اليمنى، والسفلية اليسرى لمتوازي الأضلاع. يتم استنتاج النقطة الرابعة من الثلاث نقاط الأولى. يجب أن تُطبق عمليات التحجيم والقص إذا لزم الأمر على الجزء من الصورة المحدد بحقل SrcRect لتناسب داخل متوازي الأضلاع.

القيمة: بيانات النقطة.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


يحصل أو يعيّن مصفوفة من Count نقطة تحدد ثلاث نقاط لمتوازي أضلاع. تمثل النقاط الثلاث الزاوية العلوية اليسرى، العلوية اليمنى، والسفلية اليسرى لمتوازي الأضلاع. يتم استنتاج النقطة الرابعة من الثلاث نقاط الأولى. يجب أن تُطبق عمليات التحجيم والقص إذا لزم الأمر على الجزء من الصورة المحدد بحقل SrcRect لتناسب داخل متوازي الأضلاع.

القيمة: بيانات النقطة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

