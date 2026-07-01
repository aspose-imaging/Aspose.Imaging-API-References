---
title: "EmfPlusDrawPie"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusDrawPie يحدد رسم جزء من داخل إهليلج."
type: docs
weight: 26
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawPie extends EmfPlusDrawingRecordType
```

سجل EmfPlusDrawPie يحدد رسم جزء من داخل إهليلج.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusDrawPie(EmfPlusRecord source)](#EmfPlusDrawPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | يُنشئ مثيلاً جديدًا للفئة `EmfPlusDrawPie`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCompressed()](#getCompressed--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان PointData مضغوطاً. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان PointData مضغوطاً. |
| [getObjectId()](#getObjectId--) | يحصل أو يعيّن معرف الكائن. |
| [setObjectId(byte value)](#setObjectId-byte-) | يحصل أو يعيّن معرف الكائن. |
| [getStartAngle()](#getStartAngle--) | يحصل أو يعيّن زاوية البداية، وهي قيمة عائمة 32‑بت غير سالبة تحدد الزاوية بين محور x والنقطة البداية لشريحة الفطيرة. |
| [setStartAngle(float value)](#setStartAngle-float-) | يحصل أو يعيّن زاوية البداية، وهي قيمة عائمة 32‑بت غير سالبة تحدد الزاوية بين محور x والنقطة البداية لشريحة الفطيرة. |
| [getSweepAngle()](#getSweepAngle--) | يحصل أو يعيّن زاوية القوس، وهي قيمة عائمة 32‑بت تحدد مدى القوس الذي يحدد شريحة الفطيرة للرسم، كزاوية بالدرجات تُقاس من نقطة البداية المحددة بواسطة قيمة StartAngle. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | يحصل أو يعيّن زاوية القوس، وهي قيمة عائمة 32‑بت تحدد مدى القوس الذي يحدد شريحة الفطيرة للرسم، كزاوية بالدرجات تُقاس من نقطة البداية المحددة بواسطة قيمة StartAngle. |
| [getRectData()](#getRectData--) | يحصل أو يعيّن بيانات المستطيل، إما كائن EmfPlusRect أو EmfPlusRectF يحدد صندوق الحد للقطع الناقص الذي يحتوي على شريحة الفطيرة. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | يحصل أو يعيّن بيانات المستطيل، إما كائن EmfPlusRect أو EmfPlusRectF يحدد صندوق الحد للقطع الناقص الذي يحتوي على شريحة الفطيرة. |
### EmfPlusDrawPie(EmfPlusRecord source) {#EmfPlusDrawPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawPie(EmfPlusRecord source)
```


يُنشئ مثيلاً جديدًا للفئة `EmfPlusDrawPie`.

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


يحصل أو يعيّن معرف الكائن. فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+ لرسم الفطيرة. يجب أن تكون القيمة من 0 إلى 63، شاملة.

القيمة: معرف الكائن.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


يحصل أو يعيّن معرف الكائن. فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+ لرسم الفطيرة. يجب أن تكون القيمة من 0 إلى 63، شاملة.

القيمة: معرف الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


يحصل أو يعيّن زاوية البداية، وهي قيمة عائمة 32‑بت غير سالبة تحدد الزاوية بين محور x والنقطة البداية لشريحة الفطيرة. أي قيمة مقبولة، ولكن يجب تفسيرها modulo 360، بحيث تكون النتيجة في النطاق من 0.0 شاملًا إلى 360.0 حصريًا.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


يحصل أو يعيّن زاوية البداية، وهي قيمة عائمة 32‑بت غير سالبة تحدد الزاوية بين محور x والنقطة البداية لشريحة الفطيرة. أي قيمة مقبولة، ولكن يجب تفسيرها modulo 360، بحيث تكون النتيجة في النطاق من 0.0 شاملًا إلى 360.0 حصريًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


يحصل أو يعيّن زاوية القوس، وهي قيمة عائمة 32‑بت تحدد مدى القوس الذي يحدد شريحة الفطيرة للرسم، كزاوية بالدرجات تُقاس من نقطة البداية المحددة بواسطة قيمة StartAngle. أي قيمة مقبولة، ولكن يجب حصرها بين -360.0 و 360.0 شاملًا. القيمة الموجبة تشير إلى أن القوس يُعرّف باتجاه عقارب الساعة، والقيمة السالبة تشير إلى أن القوس يُعرّف باتجاه عكس عقارب الساعة.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


يحصل أو يعيّن زاوية القوس، وهي قيمة عائمة 32‑بت تحدد مدى القوس الذي يحدد شريحة الفطيرة للرسم، كزاوية بالدرجات تُقاس من نقطة البداية المحددة بواسطة قيمة StartAngle. أي قيمة مقبولة، ولكن يجب حصرها بين -360.0 و 360.0 شاملًا. القيمة الموجبة تشير إلى أن القوس يُعرّف باتجاه عقارب الساعة، والقيمة السالبة تشير إلى أن القوس يُعرّف باتجاه عكس عقارب الساعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


يحصل أو يعيّن بيانات المستطيل، إما كائن EmfPlusRect أو EmfPlusRectF يحدد صندوق الحد للقطع الناقص الذي يحتوي على شريحة الفطيرة. هذا المستطيل يحدد موضع وحجم وشكل الشريحة. نوع الكائن في هذا الحقل يُحدد بواسطة قيمة حقل Flags.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


يحصل أو يعيّن بيانات المستطيل، إما كائن EmfPlusRect أو EmfPlusRectF يحدد صندوق الحد للقطع الناقص الذي يحتوي على شريحة الفطيرة. هذا المستطيل يحدد موضع وحجم وشكل الشريحة. نوع الكائن في هذا الحقل يُحدد بواسطة قيمة حقل Flags.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

