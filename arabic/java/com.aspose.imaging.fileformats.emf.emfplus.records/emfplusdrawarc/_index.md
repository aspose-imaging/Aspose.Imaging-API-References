---
title: "EmfPlusDrawArc"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusDrawArc يحدد رسم قوس إهليلجي."
type: docs
weight: 16
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawArc extends EmfPlusDrawingRecordType
```

سجل EmfPlusDrawArc يحدد رسم قوس إهليلجي.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusDrawArc(EmfPlusRecord source)](#EmfPlusDrawArc-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | يقوم بتهيئة نسخة جديدة من الفئة `EmfPlusDrawArc`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDataSize()](#getDataSize--) | يحصل على حجم البيانات. |
| [setDataSize(int value)](#setDataSize-int-) | يعيّن حجم البيانات. |
| [getRectFloat()](#getRectFloat--) | يحصل على قيمة تشير إلى ما إذا كانت البيانات تحتوي على سجلات EmfPlusRectF أو EmfPlusRect. هذه البتة تشير إلى ما إذا كانت البيانات في حقل RectData مضغوطة. |
| [setRectFloat(boolean value)](#setRectFloat-boolean-) | يعيّن قيمة تشير إلى ما إذا كانت البيانات تحتوي على سجلات EmfPlusRectF أو EmfPlusRect. هذه البتة تشير إلى ما إذا كانت البيانات في حقل RectData مضغوطة. |
| [getObjectId()](#getObjectId--) | يحصل على معرف الكائن. |
| [setObjectId(byte value)](#setObjectId-byte-) | يعيّن معرف الكائن. |
| [getSize()](#getSize--) | يحصل على الحجم. |
| [setSize(int value)](#setSize-int-) | يعيّن الحجم. |
| [getStartAngle()](#getStartAngle--) | يحصل على زاوية البدء قيمة عائمة غير سالبة 32‑بت تحدد الزاوية بين محور x والنقطة الابتدائية للقوس. |
| [setStartAngle(float value)](#setStartAngle-float-) | يعيّن زاوية البدء قيمة عائمة غير سالبة 32‑بت تحدد الزاوية بين محور x والنقطة الابتدائية للقوس. |
| [getSweepAngle()](#getSweepAngle--) | يحصل على زاوية المسح قيمة عائمة 32‑بت تحدد مدى القوس المراد رسمه، كزاوية بالدرجات تُقاس من النقطة الابتدائية المحددة بقيمة StartAngle. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | يعيّن زاوية المسح قيمة عائمة 32‑بت تحدد مدى القوس المراد رسمه، كزاوية بالدرجات تُقاس من النقطة الابتدائية المحددة بقيمة StartAngle. |
| [getRectangleData()](#getRectangleData--) | يحصل على بيانات المستطيل إما ككائن EmfPlusRect أو EmfPlusRectF يحدد صندوق الحد للبيضاوي المتوازي مع القوس. |
| [setRectangleData(RectangleF value)](#setRectangleData-com.aspose.imaging.RectangleF-) | يعيّن بيانات المستطيل إما ككائن EmfPlusRect أو EmfPlusRectF يحدد صندوق الحد للبيضاوي المتوازي مع القوس. |
### EmfPlusDrawArc(EmfPlusRecord source) {#EmfPlusDrawArc-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawArc(EmfPlusRecord source)
```


يقوم بتهيئة نسخة جديدة من الفئة `EmfPlusDrawArc`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


يحصل على حجم البيانات. عدد صحيح غير موقع 32‑بت يحدد عدد البايتات المحاذاة إلى 32‑بت للبيانات الخاصة بالسجل التي تليه. لهذا النوع من السجلات، يجب أن تكون القيمة واحدة من القيم التالية: 0x00000010 إذا تم تعيين البت C في حقل Flags. 0x00000018 إذا كان البت C غير معين في حقل Flags.

**Returns:**
int - حجم البيانات.
### setDataSize(int value) {#setDataSize-int-}
```
public void setDataSize(int value)
```


يعيّن حجم البيانات. عدد صحيح غير موقع 32‑بت يحدد عدد البايتات المحاذاة إلى 32‑بت للبيانات الخاصة بالسجل التي تليه. لهذا النوع من السجلات، يجب أن تكون القيمة واحدة من القيم التالية: 0x00000010 إذا تم تعيين البت C في حقل Flags. 0x00000018 إذا كان البت C غير معين في حقل Flags.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | حجم البيانات. |

### getRectFloat() {#getRectFloat--}
```
public boolean getRectFloat()
```


يحصل على قيمة تشير إلى ما إذا كانت البيانات تحتوي على سجلات EmfPlusRectF أو EmfPlusRect. هذه البتة تشير إلى ما إذا كانت البيانات في حقل RectData مضغوطة. إذا كانت معينة، يحتوي RectData على كائن EmfPlusRect (القسم 2.2.2.38). إذا كانت غير معينة، يحتوي RectData على كائن EmfPlusRectF (القسم 2.2.2.39).

**Returns:**
منطقي - `true` إذا كان عددًا عائمًا؛ وإلا `false`.
### setRectFloat(boolean value) {#setRectFloat-boolean-}
```
public void setRectFloat(boolean value)
```


يضبط قيمة تشير إلى ما إذا كانت البيانات تحتوي على سجلات EmfPlusRectF أو EmfPlusRect. هذه البتة تشير إلى ما إذا كانت البيانات في حقل RectData مضغوطة. إذا تم ضبطها، يحتوي RectData على كائن EmfPlusRect (القسم 2.2.2.38). إذا كانت غير مضبوطة، يحتوي RectData على كائن EmfPlusRectF (القسم 2.2.2.39).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | `true` إذا كان عددًا عائمًا؛ وإلا `false`. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


يحصل على معرف الكائن. فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+ لرسم القوس. يجب أن تكون القيمة بين 0 و 63 شاملًا.

**Returns:**
byte - معرف الكائن.
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


يضبط معرف الكائن. فهرس كائن EmfPlusPen (القسم 2.2.1.7) في جدول كائنات EMF+ لرسم القوس. يجب أن تكون القيمة بين 0 و 63 شاملًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte | معرف الكائن. |

### getSize() {#getSize--}
```
public int getSize()
```


يحصل على الحجم. عدد صحيح غير موقع 32 بت يحدد عدد البايتات المتراص على 32 بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايتًا والبيانات الخاصة بالسجل. لهذا النوع من السجلات، يجب أن تكون القيمة واحدة من التالي: 0x0000001C إذا كانت بتة C مضبوطة في حقل Flags. 0x00000024 إذا كانت بتة C غير مضبوطة في حقل Flags.

**Returns:**
int - الحجم.
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


يضبط الحجم. عدد صحيح غير موقع 32 بت يحدد عدد البايتات المتراص على 32 بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايتًا والبيانات الخاصة بالسجل. لهذا النوع من السجلات، يجب أن تكون القيمة واحدة من التالي: 0x0000001C إذا كانت بتة C مضبوطة في حقل Flags. 0x00000024 إذا كانت بتة C غير مضبوطة في حقل Flags.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | الحجم. |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


يحصل على زاوية البداية. قيمة عائمة غير سالبة 32 بت تحدد الزاوية بين محور x والنقطة البداية للقوس. أي قيمة مقبولة، ولكن يجب تفسيرها modulo 360، بحيث تكون النتيجة المستخدمة في النطاق من 0.0 شاملًا إلى 360.0 غير شامل.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


يضبط زاوية البداية. قيمة عائمة غير سالبة 32 بت تحدد الزاوية بين محور x والنقطة البداية للقوس. أي قيمة مقبولة، ولكن يجب تفسيرها modulo 360، بحيث تكون النتيجة المستخدمة في النطاق من 0.0 شاملًا إلى 360.0 غير شامل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


يحصل على زاوية القوس. قيمة عائمة 32 بت تحدد مدى القوس المراد رسمه، كزاوية بالدرجات مقاسة من النقطة البداية المحددة بواسطة قيمة StartAngle. أي قيمة مقبولة، ولكن يجب تقييدها بين -360.0 و 360.0 شاملًا. القيمة الموجبة تشير إلى أن القوس يُعرف باتجاه عقارب الساعة، والقيمة السالبة تشير إلى أن القوس يُعرف باتجاه عكس عقارب الساعة.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


يضبط زاوية القوس. قيمة عائمة 32 بت تحدد مدى القوس المراد رسمه، كزاوية بالدرجات مقاسة من النقطة البداية المحددة بواسطة قيمة StartAngle. أي قيمة مقبولة، ولكن يجب تقييدها بين -360.0 و 360.0 شاملًا. القيمة الموجبة تشير إلى أن القوس يُعرف باتجاه عقارب الساعة، والقيمة السالبة تشير إلى أن القوس يُعرف باتجاه عكس عقارب الساعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### getRectangleData() {#getRectangleData--}
```
public RectangleF getRectangleData()
```


يحصل على بيانات المستطيل إما كائن EmfPlusRect أو EmfPlusRectF يحدد صندوق الحدود للقطع الناقص المتوازي مع القوس. هذا المستطيل يحدد موضع القوس وحجمه وشكله. نوع الكائن في هذا الحقل يُحدد بقيمة حقل Flags.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectangleData(RectangleF value) {#setRectangleData-com.aspose.imaging.RectangleF-}
```
public void setRectangleData(RectangleF value)
```


يضبط بيانات المستطيل إما كائن EmfPlusRect أو EmfPlusRectF يحدد صندوق الحدود للقطع الناقص المتوازي مع القوس. هذا المستطيل يحدد موضع القوس وحجمه وشكله. نوع الكائن في هذا الحقل يُحدد بقيمة حقل Flags.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

