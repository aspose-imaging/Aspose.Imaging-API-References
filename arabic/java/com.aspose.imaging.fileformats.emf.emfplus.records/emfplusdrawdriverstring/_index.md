---
title: "EmfPlusDrawDriverString"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusDrawDriverString يحدد إخراج النص مع مواضع الأحرف."
type: docs
weight: 20
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawDriverString extends EmfPlusDrawingRecordType
```

سجل EmfPlusDrawDriverString يحدد إخراج النص مع مواضع الأحرف.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusDrawDriverString(EmfPlusRecord source)](#EmfPlusDrawDriverString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ مثيلاً جديداً من الفئة `EmfPlusDrawDriverString`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getObjectId()](#getObjectId--) | يحصل على معرف الكائن. |
| [setObjectId(byte value)](#setObjectId-byte-) | يعيّن معرف الكائن. |
| [getBrushId()](#getBrushId--) | يحصل على معرف الفرشاة عدد صحيح غير موقع 32‑بت يحدد إما لون النص الأمامي أو فرشاة رسومية، حسب قيمة علم S في Flags. |
| [setBrushId(int value)](#setBrushId-int-) | يضبط معرف الفرشاة عددًا صحيحًا غير موقعًا 32 بت يحدد إما لون النص الأمامي أو فرشاة رسومية، اعتمادًا على قيمة علم S في Flags |
| [getDriverStringOptionsFlags()](#getDriverStringOptionsFlags--) | يحصل على أعلام خيارات سلسلة السائق عددًا صحيحًا غير موقعًا 32 بت يحدد التباعد والاتجاه وجودة العرض للسلسلة. |
| [setDriverStringOptionsFlags(int value)](#setDriverStringOptionsFlags-int-) | يضبط أعلام خيارات سلسلة السائق عددًا صحيحًا غير موقعًا 32 بت يحدد التباعد والاتجاه وجودة العرض للسلسلة. |
| [getGlyphCount()](#getGlyphCount--) | يحصل على عدد الرموز عددًا صحيحًا غير موقعًا 32 بت يحدد عدد الرموز في السلسلة |
| [setGlyphCount(int value)](#setGlyphCount-int-) | يضبط عدد الرموز عددًا صحيحًا غير موقعًا 32 بت يحدد عدد الرموز في السلسلة |
| [getGlyphPos()](#getGlyphPos--) | يحصل على مصفوفة مواضع الرموز مصفوفة من كائنات EmfPlusPointF (القسم 2.2.2.36) التي تحدد موضع الإخراج لكل رمز حرف. |
| [setGlyphPos(PointF[] value)](#setGlyphPos-com.aspose.imaging.PointF---) | يضبط مصفوفة مواضع الرموز مصفوفة من كائنات EmfPlusPointF (القسم 2.2.2.36) التي تحدد موضع الإخراج لكل رمز حرف. |
| [getGlyphs()](#getGlyphs--) | يحصل على مصفوفة الرموز مصفوفة من قيم 16‑بت التي تحدد سلسلة النص المراد رسمها. |
| [setGlyphs(short[] value)](#setGlyphs-short---) | يضبط مصفوفة الرموز مصفوفة من قيم 16‑بت التي تحدد سلسلة النص المراد رسمها. |
| [isColor()](#isColor--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه النسخة ملونة. |
| [setColor(boolean value)](#setColor-boolean-) | يضبط قيمة تشير إلى ما إذا كانت هذه الحالة ملونة. |
| [getMatrixPresent()](#getMatrixPresent--) | يحصل على علم وجود المصفوفة عددًا صحيحًا غير موقعًا 32 بت يحدد ما إذا كانت مصفوفة تحويل موجودة في حقل TransformMatrix 0 - لا توجد مصفوفة. |
| [setMatrixPresent(int value)](#setMatrixPresent-int-) | يضبط علم وجود المصفوفة عددًا صحيحًا غير موقعًا 32 بت يحدد ما إذا كانت مصفوفة تحويل موجودة في حقل TransformMatrix 0 - لا توجد مصفوفة. |
| [getTransformMatrix()](#getTransformMatrix--) | يحصل على مصفوفة التحويل كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد التحويل لتطبيقه على كل قيمة في مصفوفة النص. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | يضبط مصفوفة التحويل كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد التحويل لتطبيقه على كل قيمة في مصفوفة النص. |
### EmfPlusDrawDriverString(EmfPlusRecord source) {#EmfPlusDrawDriverString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawDriverString(EmfPlusRecord source)
```


ينشئ مثيلاً جديداً من الفئة `EmfPlusDrawDriverString`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


يحصل على معرف الكائن. فهرس جدول كائنات EMF+ لعنصر `` (القسم 2.2.1.3) لتصيير النص. يجب أن تكون القيمة بين 0 و 63 شاملًا.

**Returns:**
byte - معرف الكائن.
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


يضبط معرف الكائن. فهرس جدول كائنات EMF+ لعنصر `` (القسم 2.2.1.3) لتصيير النص. يجب أن تكون القيمة بين 0 و 63 شاملًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte | معرف الكائن. |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


يحصل على معرف الفرشاة عدد صحيح غير موقع 32‑بت يحدد إما لون النص الأمامي أو فرشاة رسومية، حسب قيمة علم S في Flags.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


يضبط معرف الفرشاة عددًا صحيحًا غير موقعًا 32 بت يحدد إما لون النص الأمامي أو فرشاة رسومية، اعتمادًا على قيمة علم S في Flags

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getDriverStringOptionsFlags() {#getDriverStringOptionsFlags--}
```
public int getDriverStringOptionsFlags()
```


يحصل على أعلام خيارات سلسلة السائق عددًا صحيحًا غير موقعًا 32 بت يحدد التباعد والاتجاه وجودة العرض للسلسلة.

**Returns:**
int
### setDriverStringOptionsFlags(int value) {#setDriverStringOptionsFlags-int-}
```
public void setDriverStringOptionsFlags(int value)
```


يضبط أعلام خيارات سلسلة السائق عددًا صحيحًا غير موقعًا 32 بت يحدد التباعد والاتجاه وجودة العرض للسلسلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getGlyphCount() {#getGlyphCount--}
```
public int getGlyphCount()
```


يحصل على عدد الرموز عددًا صحيحًا غير موقعًا 32 بت يحدد عدد الرموز في السلسلة

**Returns:**
int
### setGlyphCount(int value) {#setGlyphCount-int-}
```
public void setGlyphCount(int value)
```


يضبط عدد الرموز عددًا صحيحًا غير موقعًا 32 بت يحدد عدد الرموز في السلسلة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getGlyphPos() {#getGlyphPos--}
```
public PointF[] getGlyphPos()
```


يحصل على مصفوفة مواضع الرموز مصفوفة من كائنات EmfPlusPointF (القسم 2.2.2.36) التي تحدد موضع الإخراج لكل رمز حرف. يجب أن يكون هناك عدد من العناصر يساوي GlyphCount، بحيث يكون هناك تطابق واحد لواحد مع العناصر في مصفوفة Glyphs. يتم حساب مواضع الرموز من موضع الرمز الأول إذا تم تعيين علم DriverStringOptionsRealizedAdvance في أعلام DriverStringOptions. في هذه الحالة، يحدد GlyphPos موضع الرمز الأول فقط.

**Returns:**
com.aspose.imaging.PointF[]
### setGlyphPos(PointF[] value) {#setGlyphPos-com.aspose.imaging.PointF---}
```
public void setGlyphPos(PointF[] value)
```


يضبط مصفوفة مواضع الرموز مصفوفة من كائنات EmfPlusPointF (القسم 2.2.2.36) التي تحدد موضع الإخراج لكل رمز حرف. يجب أن يكون هناك عدد من العناصر يساوي GlyphCount، بحيث يكون هناك تطابق واحد لواحد مع العناصر في مصفوفة Glyphs. يتم حساب مواضع الرموز من موضع الرمز الأول إذا تم تعيين علم DriverStringOptionsRealizedAdvance في أعلام DriverStringOptions. في هذه الحالة، يحدد GlyphPos موضع الرمز الأول فقط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

### getGlyphs() {#getGlyphs--}
```
public short[] getGlyphs()
```


يحصل على مصفوفة الرموز مصفوفة من قيم 16‑بت التي تحدد سلسلة النص المراد رسمها. إذا تم تعيين علم DriverStringOptionsCmapLookup في حقل DriverStringOptionsFlags، فإن كل قيمة في هذه المصفوفة تحدد حرف Unicode. وإلا، فإن كل قيمة تحدد فهرسًا إلى رمز حرف في كائن EmfPlusFont المحدد بواسطة قيمة ObjectId في حقل Flags.

**Returns:**
short[]
### setGlyphs(short[] value) {#setGlyphs-short---}
```
public void setGlyphs(short[] value)
```


يضبط مصفوفة الرموز مصفوفة من قيم 16‑بت التي تحدد سلسلة النص المراد رسمها. إذا تم تعيين علم DriverStringOptionsCmapLookup في حقل DriverStringOptionsFlags، فإن كل قيمة في هذه المصفوفة تحدد حرف Unicode. وإلا، فإن كل قيمة تحدد فهرسًا إلى رمز حرف في كائن EmfPlusFont المحدد بواسطة قيمة ObjectId في حقل Flags.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short[] |  |

### isColor() {#isColor--}
```
public boolean isColor()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كانت هذه الحالة ملونة. هذه البتة تشير إلى نوع البيانات في حقل BrushId. إذا تم تعيينها، فإن BrushId يحدد قيمة اللون في كائن EmfPlusARGB (القسم 2.2.2.1). إذا كانت غير معينة، فإن BrushId يحتوي على فهرس جدول كائنات EMF+ لكائن EmfPlusBrush (القسم 2.2.1.1).

**Returns:**
boolean - `true` إذا كانت هذه الحالة ملونة؛ وإلا `false`.
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


يضبط قيمة تشير إلى ما إذا كانت هذه الحالة ملونة. هذه البتة تشير إلى نوع البيانات في حقل BrushId. إذا تم تعيينها، فإن BrushId يحدد قيمة اللون في كائن EmfPlusARGB (القسم 2.2.2.1). إذا كانت غير معينة، فإن BrushId يحتوي على فهرس جدول كائنات EMF+ لكائن EmfPlusBrush (القسم 2.2.1.1).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | `true` إذا كان هذا الكائن ملونًا؛ وإلا `false`. |

### getMatrixPresent() {#getMatrixPresent--}
```
public int getMatrixPresent()
```


يحصل إذا كان علم وجود المصفوفة عدد صحيح غير موقع 32 بت يحدد ما إذا كانت مصفوفة تحويل موجودة في حقل TransformMatrix 0 - لا توجد مصفوفة. 1 - مصفوفة التحويل موجودة في حقل TransformMatrix.

**Returns:**
int
### setMatrixPresent(int value) {#setMatrixPresent-int-}
```
public void setMatrixPresent(int value)
```


يضبط علم وجود المصفوفة عدد صحيح غير موقع 32 بت يحدد ما إذا كانت مصفوفة تحويل موجودة في حقل TransformMatrix 0 - لا توجد مصفوفة. 1 - مصفوفة التحويل موجودة في حقل TransformMatrix.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


يحصل على مصفوفة التحويل كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد التحويل لتطبيقه على كل قيمة في مصفوفة النص. يتم تحديد وجود هذه البيانات من حقل MatrixPresent.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


يضبط مصفوفة التحويل كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد التحويل لتطبيقه على كل قيمة في مصفوفة النص. يتم تحديد وجود هذه البيانات من حقل MatrixPresent.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

