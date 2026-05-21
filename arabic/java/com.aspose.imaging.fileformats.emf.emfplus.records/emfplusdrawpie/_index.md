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
| [EmfPlusDrawPie(EmfPlusRecord source)](#EmfPlusDrawPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfPlusDrawPie`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCompressed()](#getCompressed--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت بيانات النقطة PointData مضغوطة. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت بيانات النقطة PointData مضغوطة. |
| [getObjectId()](#getObjectId--) | يحصل أو يعيّن معرف الكائن. |
| [setObjectId(byte value)](#setObjectId-byte-) | يحصل أو يعيّن معرف الكائن. |
| [getStartAngle()](#getStartAngle--) | يحصل أو يعيّن زاوية البداية عدد عائم 32‑بت غير سالب يحدد الزاوية بين محور x والنقطة البداية لشريحة الفطيرة. |
| [setStartAngle(float value)](#setStartAngle-float-) | يحصل أو يعيّن زاوية البداية عدد عائم 32‑بت غير سالب يحدد الزاوية بين محور x والنقطة البداية لشريحة الفطيرة. |
| [getSweepAngle()](#getSweepAngle--) | يحصل أو يعيّن زاوية القوس عدد عائم 32‑بت يحدد مدى القوس الذي يحدد شريحة الفطيرة للرسم، كزاوية بالدرجات تُقاس من النقطة البداية المحددة بواسطة قيمة StartAngle. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | يحصل أو يعيّن زاوية القوس عدد عائم 32‑بت يحدد مدى القوس الذي يحدد شريحة الفطيرة للرسم، كزاوية بالدرجات تُقاس من النقطة البداية المحددة بواسطة قيمة StartAngle. |
| [getRectData()](#getRectData--) | يحصل أو يعيّن بيانات المستطيل إما كائن EmfPlusRect أو EmfPlusRectF يحدد الصندوق المحيط بالقطع الناقص الذي يحتوي على شريحة الفطيرة. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | يحصل أو يعيّن بيانات المستطيل إما كائن EmfPlusRect أو EmfPlusRectF يحدد الصندوق المحيط بالقطع الناقص الذي يحتوي على شريحة الفطيرة. |
### EmfPlusDrawPie(EmfPlusRecord source) {#EmfPlusDrawPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawPie(EmfPlusRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfPlusDrawPie`.

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


يحصل أو يضبط معرف الكائن. فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+ لرسم الفطيرة. يجب أن تكون القيمة بين 0 و 63 شاملًا.

القيمة: معرف الكائن.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


يحصل أو يضبط معرف الكائن. فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+ لرسم الفطيرة. يجب أن تكون القيمة بين 0 و 63 شاملًا.

القيمة: معرف الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte |  |

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

