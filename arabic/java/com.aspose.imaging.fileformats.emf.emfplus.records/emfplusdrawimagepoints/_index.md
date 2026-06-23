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

يمكن لـ EmfPlusImage تحديد إما صورة نقطية أو ملف تعريف. يمكن تعديل الألوان في الصورة أثناء العرض. يمكن تصحيحها، تعتيمها، إضاءتها، وإزالتها.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusDrawImagePoints(EmfPlusRecord source)](#EmfPlusDrawImagePoints-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfPlusDrawImagePoints`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCompressed()](#getCompressed--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان PointData مضغوطاً. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان PointData مضغوطاً. |
| [getObjectId()](#getObjectId--) | يحصل أو يعيّن معرف الكائن. |
| [setObjectId(byte value)](#setObjectId-byte-) | يحصل أو يعيّن معرف الكائن. |
| [getApplyingAnEffect()](#getApplyingAnEffect--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [applying an effect]. |
| [setApplyingAnEffect(boolean value)](#setApplyingAnEffect-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [applying an effect]. |
| [getRelative()](#getRelative--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusDrawImagePoints` نسبياً. |
| [setRelative(boolean value)](#setRelative-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusDrawImagePoints` نسبياً. |
| [getImageAttributesId()](#getImageAttributesId--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحتوي على فهرس كائن EmfPlusImageAttributes الاختياري (القسم 2.2.1.5) في جدول كائنات EMF+. |
| [setImageAttributesId(int value)](#setImageAttributesId-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحتوي على فهرس كائن EmfPlusImageAttributes الاختياري (القسم 2.2.1.5) في جدول كائنات EMF+. |
| [getSrcUnit()](#getSrcUnit--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد وحدات حقل SrcRect. |
| [setSrcUnit(int value)](#setSrcUnit-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد وحدات حقل SrcRect. |
| [getSrcRect()](#getSrcRect--) | يحصل أو يعيّن كائن EmfPlusRectF (القسم 2.2.2.39) يحدد جزءًا من الصورة التي سيتم عرضها. |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | يحصل أو يعيّن كائن EmfPlusRectF (القسم 2.2.2.39) يحدد جزءًا من الصورة التي سيتم عرضها. |
| [getPointData()](#getPointData--) | يحصل أو يعيّن مصفوفة من Count نقطة تحدد ثلاث نقاط لمستطيل متوازي الأضلاع. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | يحصل أو يعيّن مصفوفة من Count نقطة تحدد ثلاث نقاط لمستطيل متوازي الأضلاع. |
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


يحصل أو يعيّن قيمة تشير إلى ما إذا كان PointData مضغوطًا. تشير هذه البتة إلى ما إذا كان حقل PointData يحدد بيانات مضغوطة. إذا تم تعيينها، فإن PointData يحدد مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات صحيحة 16‑بت. إذا لم تُعيّن، فإن PointData يحدد مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات عائمة 32‑بت. ملاحظة: إذا تم تعيين علم P (أدناه)، تكون هذه العلامة غير معرفة ويجب تجاهلها.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان PointData مضغوطًا. تشير هذه البتة إلى ما إذا كان حقل PointData يحدد بيانات مضغوطة. إذا تم تعيينها، فإن PointData يحدد مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات صحيحة 16‑بت. إذا لم تُعيّن، فإن PointData يحدد مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات عائمة 32‑بت. ملاحظة: إذا تم تعيين علم P (أدناه)، تكون هذه العلامة غير معرفة ويجب تجاهلها.

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

### getApplyingAnEffect() {#getApplyingAnEffect--}
```
public boolean getApplyingAnEffect()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [applying an effect]. تشير هذه البتة إلى أن عرض الصورة يتضمن تطبيق تأثير. إذا تم تعيينها، يجب أن يكون كائن من فئة Effect قد تم تحديده في سجل EmfPlusSerializableObject سابقًا (القسم 2.3.5.2).

القيمة: `true` إذا كان [applying an effect]؛ وإلا `false`.

**Returns:**
boolean
### setApplyingAnEffect(boolean value) {#setApplyingAnEffect-boolean-}
```
public void setApplyingAnEffect(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [applying an effect]. تشير هذه البتة إلى أن عرض الصورة يتضمن تطبيق تأثير. إذا تم تعيينها، يجب أن يكون كائن من فئة Effect قد تم تحديده في سجل EmfPlusSerializableObject سابقًا (القسم 2.3.5.2).

القيمة: `true` إذا كان [applying an effect]؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusDrawImagePoints` نسبياً. تشير هذه البتة إلى ما إذا كان حقل PointData يحدد مواقع نسبية أو مطلقة. إذا تم تعيينها، كل عنصر في PointData يحدد موقعًا في مساحة الإحداثيات يكون نسبياً إلى الموقع المحدد بالعنصر السابق في المصفوفة. في حالة العنصر الأول في PointData، يُفترض وجود موقع سابق عند الإحداثيات (0,0). إذا لم تُعيّن، فإن PointData يحدد مواقع مطلقة وفقًا لعلم C. ملاحظة: إذا تم تعيين هذه العلامة، فإن علم C (أعلاه) غير معرف ويجب تجاهله.

القيمة: `true` إذا كان نسبيًا؛ وإلا `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusDrawImagePoints` نسبياً. تشير هذه البتة إلى ما إذا كان حقل PointData يحدد مواقع نسبية أو مطلقة. إذا تم تعيينها، كل عنصر في PointData يحدد موقعًا في مساحة الإحداثيات يكون نسبياً إلى الموقع المحدد بالعنصر السابق في المصفوفة. في حالة العنصر الأول في PointData، يُفترض وجود موقع سابق عند الإحداثيات (0,0). إذا لم تُعيّن، فإن PointData يحدد مواقع مطلقة وفقًا لعلم C. ملاحظة: إذا تم تعيين هذه العلامة، فإن علم C (أعلاه) غير معرف ويجب تجاهله.

القيمة: `true` إذا كان نسبيًا؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getImageAttributesId() {#getImageAttributesId--}
```
public int getImageAttributesId()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحتوي على فهرس كائن EmfPlusImageAttributes الاختياري (القسم 2.2.1.5) في جدول كائنات EMF+.

القيمة: معرف سمات الصورة.

**Returns:**
int
### setImageAttributesId(int value) {#setImageAttributesId-int-}
```
public void setImageAttributesId(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحتوي على فهرس كائن EmfPlusImageAttributes الاختياري (القسم 2.2.1.5) في جدول كائنات EMF+.

القيمة: معرف سمات الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

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
| value | int |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


يحصل أو يعيّن كائن EmfPlusRectF (القسم 2.2.2.39) يحدد جزءًا من الصورة التي سيتم عرضها.

القيمة: مستطيل المصدر.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


يحصل أو يعيّن كائن EmfPlusRectF (القسم 2.2.2.39) يحدد جزءًا من الصورة التي سيتم عرضها.

القيمة: مستطيل المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


يحصل أو يعيّن مصفوفة من Count نقطة تحدد ثلاث نقاط لمستطيل متوازي الأضلاع. تمثل النقاط الثلاث الزاوية العليا اليسرى، العليا اليمنى، والسفلى اليسرى للمستطيل. يتم استنتاج النقطة الرابعة للمستطيل من الثلاث نقاط الأولى. يجب أن يخضع الجزء من الصورة المحدد بحقل SrcRect إلى تحويلات التحجيم والقص إذا لزم الأمر لتناسب داخل المستطيل.

القيمة: بيانات النقاط.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


يحصل أو يعيّن مصفوفة من Count نقطة تحدد ثلاث نقاط لمستطيل متوازي الأضلاع. تمثل النقاط الثلاث الزاوية العليا اليسرى، العليا اليمنى، والسفلى اليسرى للمستطيل. يتم استنتاج النقطة الرابعة للمستطيل من الثلاث نقاط الأولى. يجب أن يخضع الجزء من الصورة المحدد بحقل SrcRect إلى تحويلات التحجيم والقص إذا لزم الأمر لتناسب داخل المستطيل.

القيمة: بيانات النقاط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

