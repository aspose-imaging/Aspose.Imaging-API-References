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
| [EmfPlusDrawDriverString(EmfPlusRecord source)](#EmfPlusDrawDriverString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | يُهيئ مثيلًا جديدًا من الفئة `EmfPlusDrawDriverString`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getObjectId()](#getObjectId--) | يحصل على معرف الكائن. |
| [setObjectId(byte value)](#setObjectId-byte-) | يعيّن معرف الكائن. |
| [getBrushId()](#getBrushId--) | يحصل على معرف الفرشاة عدد صحيح غير موقع 32‑بت يحدد إما لون النص الأمامي أو فرشاة رسومية، حسب قيمة علم S في Flags. |
| [setBrushId(int value)](#setBrushId-int-) | يعيّن معرف الفرشاة عددًا صحيحًا غير موقع 32‑بت يحدد إما لون النص الأمامي أو فرشاة رسومية، حسب قيمة علم S في Flags. |
| [getDriverStringOptionsFlags()](#getDriverStringOptionsFlags--) | يحصل على driver string options flags عدد صحيح غير موقع 32‑بت يحدد التباعد والاتجاه وجودة العرض للسلسلة. |
| [setDriverStringOptionsFlags(int value)](#setDriverStringOptionsFlags-int-) | يعيّن driver string options flags عددًا صحيحًا غير موقع 32‑بت يحدد التباعد والاتجاه وجودة العرض للسلسلة. |
| [getGlyphCount()](#getGlyphCount--) | يحصل على عدد الرموز (glyph count) عددًا صحيحًا غير موقع 32‑بت يحدد عدد الرموز في السلسلة. |
| [setGlyphCount(int value)](#setGlyphCount-int-) | يعيّن عدد الرموز (glyph count) عددًا صحيحًا غير موقع 32‑بت يحدد عدد الرموز في السلسلة. |
| [getGlyphPos()](#getGlyphPos--) | يحصل على مصفوفة مواضع الرموز مصفوفة من كائنات EmfPlusPointF (القسم 2.2.2.36) التي تحدد موضع الإخراج لكل رمز حرفي. |
| [setGlyphPos(PointF[] value)](#setGlyphPos-com.aspose.imaging.PointF---) | يعيّن مصفوفة مواضع الرموز مصفوفة من كائنات EmfPlusPointF (القسم 2.2.2.36) التي تحدد موضع الإخراج لكل رمز حرفي. |
| [getGlyphs()](#getGlyphs--) | يحصل على مصفوفة الرموز مصفوفة من قيم 16‑بت تحدد سلسلة النص المراد رسمها. |
| [setGlyphs(short[] value)](#setGlyphs-short---) | يعيّن مصفوفة الرموز مصفوفة من قيم 16‑بت تحدد سلسلة النص المراد رسمها. |
| [isColor()](#isColor--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الحالة ملونة. |
| [setColor(boolean value)](#setColor-boolean-) | يعيّن قيمة تشير إلى ما إذا كان هذا المثيل ملونًا. |
| [getMatrixPresent()](#getMatrixPresent--) | يحصل على علم وجود المصفوفة عدد صحيح غير موقع 32‑بت يحدد ما إذا كانت مصفوفة تحويل موجودة في حقل TransformMatrix 0 - لا توجد مصفوفة. |
| [setMatrixPresent(int value)](#setMatrixPresent-int-) | يعيّن علم وجود المصفوفة عددًا صحيحًا غير موقع 32‑بت يحدد ما إذا كانت مصفوفة تحويل موجودة في حقل TransformMatrix 0 - لا توجد مصفوفة. |
| [getTransformMatrix()](#getTransformMatrix--) | يحصل على مصفوفة التحويل كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد التحويل لتطبيقه على كل قيمة في مصفوفة النص. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | يعيّن مصفوفة التحويل كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد التحويل لتطبيقه على كل قيمة في مصفوفة النص. |
### EmfPlusDrawDriverString(EmfPlusRecord source) {#EmfPlusDrawDriverString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawDriverString(EmfPlusRecord source)
```


يُهيئ مثيلًا جديدًا من الفئة `EmfPlusDrawDriverString`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


يحصل على معرف الكائن. فهرس جدول كائنات EMF+ لكائن `` (القسم 2.2.1.3) لتصيير النص. يجب أن تكون القيمة بين 0 و 63 شاملًا.

**Returns:**
byte - معرف الكائن.
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


يعيّن معرف الكائن. فهرس جدول كائنات EMF+ لكائن `` (القسم 2.2.1.3) لتصيير النص. يجب أن تكون القيمة بين 0 و 63 شاملًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte | معرّف الكائن. |

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


يعيّن معرف الفرشاة عددًا صحيحًا غير موقع 32‑بت يحدد إما لون النص الأمامي أو فرشاة رسومية، حسب قيمة علم S في Flags.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDriverStringOptionsFlags() {#getDriverStringOptionsFlags--}
```
public int getDriverStringOptionsFlags()
```


يحصل على driver string options flags عدد صحيح غير موقع 32‑بت يحدد التباعد والاتجاه وجودة العرض للسلسلة.

**Returns:**
int
### setDriverStringOptionsFlags(int value) {#setDriverStringOptionsFlags-int-}
```
public void setDriverStringOptionsFlags(int value)
```


يعيّن driver string options flags عددًا صحيحًا غير موقع 32‑بت يحدد التباعد والاتجاه وجودة العرض للسلسلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getGlyphCount() {#getGlyphCount--}
```
public int getGlyphCount()
```


يحصل على عدد الرموز (glyph count) عددًا صحيحًا غير موقع 32‑بت يحدد عدد الرموز في السلسلة.

**Returns:**
int
### setGlyphCount(int value) {#setGlyphCount-int-}
```
public void setGlyphCount(int value)
```


يعيّن عدد الرموز (glyph count) عددًا صحيحًا غير موقع 32‑بت يحدد عدد الرموز في السلسلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getGlyphPos() {#getGlyphPos--}
```
public PointF[] getGlyphPos()
```


يحصل على مصفوفة مواضع الحروف. مصفوفة من كائنات EmfPlusPointF (القسم 2.2.2.36) التي تحدد موضع الإخراج لكل حرف رسومي. يجب أن يكون هناك عدد GlyphCount من العناصر، والتي لها تطابق واحد لواحد مع العناصر في مصفوفة Glyphs. يتم حساب مواضع الحروف من موضع الحرف الأول إذا تم تعيين علم DriverStringOptionsRealizedAdvance في أعلام DriverStringOptions. في هذه الحالة، يحدد GlyphPos موضع الحرف الأول فقط.

**Returns:**
com.aspose.imaging.PointF[]
### setGlyphPos(PointF[] value) {#setGlyphPos-com.aspose.imaging.PointF---}
```
public void setGlyphPos(PointF[] value)
```


يضبط مصفوفة مواضع الحروف. مصفوفة من كائنات EmfPlusPointF (القسم 2.2.2.36) التي تحدد موضع الإخراج لكل حرف رسومي. يجب أن يكون هناك عدد GlyphCount من العناصر، والتي لها تطابق واحد لواحد مع العناصر في مصفوفة Glyphs. يتم حساب مواضع الحروف من موضع الحرف الأول إذا تم تعيين علم DriverStringOptionsRealizedAdvance في أعلام DriverStringOptions. في هذه الحالة، يحدد GlyphPos موضع الحرف الأول فقط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

### getGlyphs() {#getGlyphs--}
```
public short[] getGlyphs()
```


يحصل على مصفوفة الحروف. مصفوفة من قيم 16‑بت التي تحدد سلسلة النص التي سيتم رسمها. إذا تم تعيين علم DriverStringOptionsCmapLookup في حقل DriverStringOptionsFlags، فإن كل قيمة في هذه المصفوفة تحدد حرف Unicode. وإلا، فإن كل قيمة تحدد فهرسًا إلى حرف رسومي في كائن EmfPlusFont المحدد بواسطة قيمة ObjectId في حقل Flags.

**Returns:**
short[]
### setGlyphs(short[] value) {#setGlyphs-short---}
```
public void setGlyphs(short[] value)
```


يضبط مصفوفة الحروف. مصفوفة من قيم 16‑بت التي تحدد سلسلة النص التي سيتم رسمها. إذا تم تعيين علم DriverStringOptionsCmapLookup في حقل DriverStringOptionsFlags، فإن كل قيمة في هذه المصفوفة تحدد حرف Unicode. وإلا، فإن كل قيمة تحدد فهرسًا إلى حرف رسومي في كائن EmfPlusFont المحدد بواسطة قيمة ObjectId في حقل Flags.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | short[] |  |

### isColor() {#isColor--}
```
public boolean isColor()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كانت هذه العينة ملونة. هذه البتة تشير إلى نوع البيانات في حقل BrushId. إذا تم تعيينها، فإن BrushId يحدد قيمة اللون في كائن EmfPlusARGB (القسم 2.2.2.1). إذا كانت غير معينة، فإن BrushId يحتوي على فهرس جدول كائنات EMF+ لكائن EmfPlusBrush (القسم 2.2.1.1).

**Returns:**
منطقي - `true` إذا كانت هذه العينة ملونة؛ وإلا `false`.
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


يضبط قيمة تشير إلى ما إذا كانت هذه العينة ملونة. هذه البتة تشير إلى نوع البيانات في حقل BrushId. إذا تم تعيينها، فإن BrushId يحدد قيمة اللون في كائن EmfPlusARGB (القسم 2.2.2.1). إذا كانت غير معينة، فإن BrushId يحتوي على فهرس جدول كائنات EMF+ لكائن EmfPlusBrush (القسم 2.2.1.1).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | `true` إذا كانت هذه العينة ملونة؛ وإلا `false`. |

### getMatrixPresent() {#getMatrixPresent--}
```
public int getMatrixPresent()
```


يحصل على علم وجود المصفوفة. عدد صحيح غير موقع 32‑بت يحدد ما إذا كانت مصفوفة تحويل موجودة في حقل TransformMatrix. 0 - لا توجد مصفوفة. 1 - مصفوفة التحويل موجودة في حقل TransformMatrix.

**Returns:**
int
### setMatrixPresent(int value) {#setMatrixPresent-int-}
```
public void setMatrixPresent(int value)
```


يضبط علم وجود المصفوفة. عدد صحيح غير موقع 32‑بت يحدد ما إذا كانت مصفوفة تحويل موجودة في حقل TransformMatrix. 0 - لا توجد مصفوفة. 1 - مصفوفة التحويل موجودة في حقل TransformMatrix.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


يحصل على مصفوفة التحويل. كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد التحويل لتطبيقه على كل قيمة في مصفوفة النص. يتم تحديد وجود هذه البيانات من حقل MatrixPresent.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


يضبط مصفوفة التحويل. كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد التحويل لتطبيقه على كل قيمة في مصفوفة النص. يتم تحديد وجود هذه البيانات من حقل MatrixPresent.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

