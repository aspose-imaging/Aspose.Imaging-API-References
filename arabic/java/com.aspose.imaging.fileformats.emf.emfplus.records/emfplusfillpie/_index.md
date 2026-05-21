---
title: "EmfPlusFillPie"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يسجل EmfPlusFillPie يحدد تعبئة جزء من داخل إهليلج."
type: docs
weight: 35
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillPie extends EmfPlusDrawingRecordType
```

يسجل EmfPlusFillPie يحدد تعبئة جزء من داخل إهليلج.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusFillPie(EmfPlusRecord source)](#EmfPlusFillPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ مثيلاً جديداً من الفئة `EmfPlusFillPie`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCompressed()](#getCompressed--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت بيانات النقطة PointData مضغوطة. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت بيانات النقطة PointData مضغوطة. |
| [isColor()](#isColor--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه النسخة ملونة. |
| [setColor(boolean value)](#setColor-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه النسخة ملونة. |
| [getStartAngle()](#getStartAngle--) | يحصل أو يعيّن زاوية البداية عدد عائم 32‑بت غير سالب يحدد الزاوية بين محور x والنقطة البداية لشريحة الفطيرة. |
| [setStartAngle(float value)](#setStartAngle-float-) | يحصل أو يعيّن زاوية البداية عدد عائم 32‑بت غير سالب يحدد الزاوية بين محور x والنقطة البداية لشريحة الفطيرة. |
| [getSweepAngle()](#getSweepAngle--) | يحصل أو يعيّن زاوية القوس عدد عائم 32‑بت يحدد مدى القوس الذي يحدد شريحة الفطيرة للرسم، كزاوية بالدرجات تُقاس من النقطة البداية المحددة بواسطة قيمة StartAngle. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | يحصل أو يعيّن زاوية القوس عدد عائم 32‑بت يحدد مدى القوس الذي يحدد شريحة الفطيرة للرسم، كزاوية بالدرجات تُقاس من النقطة البداية المحددة بواسطة قيمة StartAngle. |
| [getRectData()](#getRectData--) | يحصل أو يعيّن بيانات المستطيل إما كائن EmfPlusRect أو EmfPlusRectF يحدد الصندوق المحيط بالقطع الناقص الذي يحتوي على شريحة الفطيرة. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | يحصل أو يعيّن بيانات المستطيل إما كائن EmfPlusRect أو EmfPlusRectF يحدد الصندوق المحيط بالقطع الناقص الذي يحتوي على شريحة الفطيرة. |
| [getBrushId()](#getBrushId--) | يحصل أو يعيّن معرف الفرشاة عددًا صحيحًا غير موقع 32‑بت يحدد الفرشاة، ومحتواه يُحدد بواسطة بت S في حقل العلامات. |
| [setBrushId(int value)](#setBrushId-int-) | يحصل أو يعيّن معرف الفرشاة عددًا صحيحًا غير موقع 32‑بت يحدد الفرشاة، ومحتواه يُحدد بواسطة بت S في حقل العلامات. |
### EmfPlusFillPie(EmfPlusRecord source) {#EmfPlusFillPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillPie(EmfPlusRecord source)
```


ينشئ مثيلاً جديداً من الفئة `EmfPlusFillPie`.

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

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


يحصل أو يعيّن زاوية البداية عدد عائم 32‑بت غير سالب يحدد الزاوية بين محور x والنقطة البداية لشريحة الفطيرة. أي قيمة مقبولة، لكن يجب تفسيرها modulo 360، بحيث يكون الناتج في النطاق من 0.0 شامل إلى 360.0 غير شامل.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


يحصل أو يعيّن زاوية البداية عدد عائم 32‑بت غير سالب يحدد الزاوية بين محور x والنقطة البداية لشريحة الفطيرة. أي قيمة مقبولة، لكن يجب تفسيرها modulo 360، بحيث يكون الناتج في النطاق من 0.0 شامل إلى 360.0 غير شامل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


يحصل أو يعيّن زاوية القوس عدد عائم 32‑بت يحدد مدى القوس الذي يحدد شريحة الفطيرة للرسم، كزاوية بالدرجات تُقاس من النقطة البداية المحددة بواسطة قيمة StartAngle. أي قيمة مقبولة، لكن يجب حصرها بين -360.0 و 360.0 شامل. القيمة الموجبة تشير إلى أن القوس يُعرّف باتجاه عقارب الساعة، والقيمة السالبة تشير إلى أن القوس يُعرّف باتجاه عكس عقارب الساعة.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


يحصل أو يعيّن زاوية القوس عدد عائم 32‑بت يحدد مدى القوس الذي يحدد شريحة الفطيرة للرسم، كزاوية بالدرجات تُقاس من النقطة البداية المحددة بواسطة قيمة StartAngle. أي قيمة مقبولة، لكن يجب حصرها بين -360.0 و 360.0 شامل. القيمة الموجبة تشير إلى أن القوس يُعرّف باتجاه عقارب الساعة، والقيمة السالبة تشير إلى أن القوس يُعرّف باتجاه عكس عقارب الساعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


يحصل أو يعيّن بيانات المستطيل إما كائن EmfPlusRect أو EmfPlusRectF يحدد الصندوق المحيط بالقطع الناقص الذي يحتوي على شريحة الفطيرة. هذا المستطيل يحدد موضع الفطيرة وحجمها وشكلها. نوع الكائن في هذا الحقل يُحدد بقيمة حقل Flags.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


يحصل أو يعيّن بيانات المستطيل إما كائن EmfPlusRect أو EmfPlusRectF يحدد الصندوق المحيط بالقطع الناقص الذي يحتوي على شريحة الفطيرة. هذا المستطيل يحدد موضع الفطيرة وحجمها وشكلها. نوع الكائن في هذا الحقل يُحدد بقيمة حقل Flags.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

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

