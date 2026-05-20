---
title: "EmfPlusFillClosedCurve"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يسجل EmfPlusFillClosedCurve يحدد تعبئة داخل منحنى كاردينال مغلق."
type: docs
weight: 32
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillClosedCurve extends EmfPlusDrawingRecordType
```

يسجل EmfPlusFillClosedCurve يحدد تعبئة داخل منحنى كاردينال مغلق.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusFillClosedCurve(EmfPlusRecord source)](#EmfPlusFillClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | يُنشئ مثيلاً جديدًا من الفئة `EmfPlusFillClosedCurve`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isColor()](#isColor--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه النسخة ملونة. |
| [setColor(boolean value)](#setColor-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه النسخة ملونة. |
| [getCompressed()](#getCompressed--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillClosedCurve` مضغوطًا. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillClosedCurve` مضغوطًا. |
| [getWinding()](#getWinding--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillClosedCurve` متعرجًا. |
| [setWinding(boolean value)](#setWinding-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillClosedCurve` متعرجًا. |
| [getRelative()](#getRelative--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillClosedCurve` نسبيًا. |
| [setRelative(boolean value)](#setRelative-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillClosedCurve` نسبيًا. |
| [getBrushId()](#getBrushId--) | يحصل أو يعيّن معرف الفرشاة، عددًا صحيحًا غير موقع 32‑بت يحدد EmfPlusBrush، حيث يتم تحديد محتواه بواسطة البت S في حقل العلامات. |
| [setBrushId(int value)](#setBrushId-int-) | يحصل أو يعيّن معرف الفرشاة، عددًا صحيحًا غير موقع 32‑بت يحدد EmfPlusBrush، حيث يتم تحديد محتواه بواسطة البت S في حقل العلامات. |
| [getTension()](#getTension--) | يحصل أو يعيّن قيمة التوتر، عددًا عائمًا 32‑بت يحدد مدى انحناء المنحنى بشكل ضيق أثناء مروره عبر النقاط. |
| [setTension(float value)](#setTension-float-) | يحصل أو يعيّن قيمة التوتر، عددًا عائمًا 32‑بت يحدد مدى انحناء المنحنى بشكل ضيق أثناء مروره عبر النقاط. |
| [getPointData()](#getPointData--) | يحصل أو يعيّن بيانات النقاط، مصفوفة من نقاط Count تحدد نقاط النهاية للخطوط التي تُعرّف المنحنى. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | يحصل أو يعيّن بيانات النقاط، مصفوفة من نقاط Count تحدد نقاط النهاية للخطوط التي تُعرّف المنحنى. |
### EmfPlusFillClosedCurve(EmfPlusRecord source) {#EmfPlusFillClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillClosedCurve(EmfPlusRecord source)
```


يُنشئ مثيلاً جديدًا من الفئة `EmfPlusFillClosedCurve`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

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

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillClosedCurve` مضغوطًا. تشير هذه البتة إلى ما إذا كان حقل PointData يحدد بيانات مضغوطة. إذا تم تعيينها، يحدد PointData مواقع مطلقة في فضاء الإحداثيات باستخدام إحداثيات صحيحة 16‑بت. إذا لم تُعيّن، يحدد PointData مواقع مطلقة في فضاء الإحداثيات باستخدام إحداثيات عائمة 32‑بت. ---------------------- عملية تعبئة "winding" تملأ المناطق وفقًا لقاعدة "even-odd parity". وفقًا لهذه القاعدة، يمكن تحديد ما إذا كانت نقطة الاختبار داخل أو خارج منحنى مغلق كما يلي: ارسم خطًا من نقطة الاختبار إلى نقطة تقع بعيدًا عن المنحنى. إذا قطع هذا الخط المنحنى عددًا فرديًا من المرات، تكون نقطة الاختبار داخل المنحنى؛ وإلا تكون خارج المنحنى. --------------------- عملية تعبئة "alternate" تملأ المناطق وفقًا لقاعدة "non-zero". وفقًا لهذه القاعدة، يمكن تحديد ما إذا كانت نقطة الاختبار داخل أو خارج منحنى مغلق كما يلي: ارسم خطًا من نقطة الاختبار إلى نقطة تقع بعيدًا عن المنحنى. عد عدد المرات التي يقطع فيها المنحنى الخط الاختباري من اليسار إلى اليمين، وعد عدد المرات التي يقطع فيها المنحنى الخط الاختباري من اليمين إلى اليسار. إذا كان العددان متساويين، تكون نقطة الاختبار خارج المنحنى؛ وإلا تكون داخل المنحنى.

القيمة: `true` إذا كانت مضغوطة؛ وإلا `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillClosedCurve` مضغوطًا. تشير هذه البتة إلى ما إذا كان حقل PointData يحدد بيانات مضغوطة. إذا تم تعيينها، يحدد PointData مواقع مطلقة في فضاء الإحداثيات باستخدام إحداثيات صحيحة 16‑بت. إذا لم تُعيّن، يحدد PointData مواقع مطلقة في فضاء الإحداثيات باستخدام إحداثيات عائمة 32‑بت. ---------------------- عملية تعبئة "winding" تملأ المناطق وفقًا لقاعدة "even-odd parity". وفقًا لهذه القاعدة، يمكن تحديد ما إذا كانت نقطة الاختبار داخل أو خارج منحنى مغلق كما يلي: ارسم خطًا من نقطة الاختبار إلى نقطة تقع بعيدًا عن المنحنى. إذا قطع هذا الخط المنحنى عددًا فرديًا من المرات، تكون نقطة الاختبار داخل المنحنى؛ وإلا تكون خارج المنحنى. --------------------- عملية تعبئة "alternate" تملأ المناطق وفقًا لقاعدة "non-zero". وفقًا لهذه القاعدة، يمكن تحديد ما إذا كانت نقطة الاختبار داخل أو خارج منحنى مغلق كما يلي: ارسم خطًا من نقطة الاختبار إلى نقطة تقع بعيدًا عن المنحنى. عد عدد المرات التي يقطع فيها المنحنى الخط الاختباري من اليسار إلى اليمين، وعد عدد المرات التي يقطع فيها المنحنى الخط الاختباري من اليمين إلى اليسار. إذا كان العددان متساويين، تكون نقطة الاختبار خارج المنحنى؛ وإلا تكون داخل المنحنى.

القيمة: `true` إذا كانت مضغوطة؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getWinding() {#getWinding--}
```
public boolean getWinding()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillClosedCurve` متعرجًا. تشير هذه البتة إلى كيفية تنفيذ عملية التعبئة. إذا تم تعيينها، تكون التعبئة من نوع "winding". إذا لم تُعيّن، تكون التعبئة من نوع "alternate".

القيمة: `true` إذا كان متعرجًا؛ وإلا `false`.

**Returns:**
boolean
### setWinding(boolean value) {#setWinding-boolean-}
```
public void setWinding(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillClosedCurve` متعرجًا. تشير هذه البتة إلى كيفية تنفيذ عملية التعبئة. إذا تم تعيينها، تكون التعبئة من نوع "winding". إذا لم تُعيّن، تكون التعبئة من نوع "alternate".

القيمة: `true` إذا كان متعرجًا؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillClosedCurve` نسبيًا. تشير هذه البتة إلى ما إذا كان حقل PointData يحدد مواقع نسبية أو مطلقة. إذا تم تعيينها، يحدد كل عنصر في PointData موقعًا في فضاء الإحداثيات يكون نسبيًا إلى الموقع المحدد بواسطة العنصر السابق في المصفوفة. في حالة العنصر الأول في PointData، يُفترض وجود موقع سابق عند الإحداثيات (0,0). إذا لم تُعيّن، يحدد PointData مواقع مطلقة وفقًا للبت C. ملاحظة: إذا تم تعيين هذا العلم، يكون علم C (أعلاه) غير معرف ويجب تجاهله.

القيمة: `true` إذا كان نسبيًا؛ وإلا `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillClosedCurve` نسبيًا. تشير هذه البتة إلى ما إذا كان حقل PointData يحدد مواقع نسبية أو مطلقة. إذا تم تعيينها، يحدد كل عنصر في PointData موقعًا في فضاء الإحداثيات يكون نسبيًا إلى الموقع المحدد بواسطة العنصر السابق في المصفوفة. في حالة العنصر الأول في PointData، يُفترض وجود موقع سابق عند الإحداثيات (0,0). إذا لم تُعيّن، يحدد PointData مواقع مطلقة وفقًا للبت C. ملاحظة: إذا تم تعيين هذا العلم، يكون علم C (أعلاه) غير معرف ويجب تجاهله.

القيمة: `true` إذا كان نسبيًا؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


يحصل أو يعيّن معرف الفرشاة، عددًا صحيحًا غير موقع 32‑بت يحدد EmfPlusBrush، حيث يتم تحديد محتواه بواسطة البت S في حقل العلامات. تُستخدم هذه الفرشاة لملء داخل المنحنى الكاردينالي المغلق.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


يحصل أو يعيّن معرف الفرشاة، عددًا صحيحًا غير موقع 32‑بت يحدد EmfPlusBrush، حيث يتم تحديد محتواه بواسطة البت S في حقل العلامات. تُستخدم هذه الفرشاة لملء داخل المنحنى الكاردينالي المغلق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getTension() {#getTension--}
```
public float getTension()
```


يحصل أو يعيّن قيمة التوتر، عددًا عائمًا 32‑بت يحدد مدى انحناء المنحنى بشكل ضيق أثناء مروره عبر النقاط. القيمة 0.0 تشير إلى أن المنحنى هو سلسلة من الخطوط المستقيمة. كلما زادت القيمة، يصبح المنحنى أكثر استدارة. لمزيد من المعلومات، راجع [SPLINE77] و [PETZOLD].

**Returns:**
float
### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


يحصل أو يعيّن قيمة التوتر، عددًا عائمًا 32‑بت يحدد مدى انحناء المنحنى بشكل ضيق أثناء مروره عبر النقاط. القيمة 0.0 تشير إلى أن المنحنى هو سلسلة من الخطوط المستقيمة. كلما زادت القيمة، يصبح المنحنى أكثر استدارة. لمزيد من المعلومات، راجع [SPLINE77] و [PETZOLD].

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


يحصل أو يعيّن بيانات النقاط، مصفوفة من نقاط Count تحدد نقاط النهاية للخطوط التي تُعرّف المنحنى. في منحنى كاردينالي مغلق، يستمر المنحنى عبر النقطة الأخيرة في مصفوفة PointData ويتصل بالنقطة الأولى في المصفوفة.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


يحصل أو يعيّن بيانات النقاط، مصفوفة من نقاط Count تحدد نقاط النهاية للخطوط التي تُعرّف المنحنى. في منحنى كاردينالي مغلق، يستمر المنحنى عبر النقطة الأخيرة في مصفوفة PointData ويتصل بالنقطة الأولى في المصفوفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

