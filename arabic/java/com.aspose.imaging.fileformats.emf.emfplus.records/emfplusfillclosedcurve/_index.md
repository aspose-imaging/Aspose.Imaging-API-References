---
title: "EmfPlusFillClosedCurve"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusFillClosedCurve يحدد تعبئة داخل منحنى كاردينال مغلق"
type: docs
weight: 32
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillClosedCurve extends EmfPlusDrawingRecordType
```

سجل EmfPlusFillClosedCurve يحدد تعبئة داخل منحنى كاردينال مغلق
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusFillClosedCurve(EmfPlusRecord source)](#EmfPlusFillClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ مثيلاً جديدًا من الفئة `EmfPlusFillClosedCurve`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isColor()](#isColor--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الحالة ملونة. |
| [setColor(boolean value)](#setColor-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الحالة ملونة. |
| [getCompressed()](#getCompressed--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillClosedCurve` مضغوطًا. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillClosedCurve` مضغوطًا. |
| [getWinding()](#getWinding--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillClosedCurve` متدوّرًا. |
| [setWinding(boolean value)](#setWinding-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillClosedCurve` متدوّرًا. |
| [getRelative()](#getRelative--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillClosedCurve` نسبيًا. |
| [setRelative(boolean value)](#setRelative-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillClosedCurve` نسبيًا. |
| [getBrushId()](#getBrushId--) | يحصل أو يعيّن معرف الفرشاة عددًا صحيحًا غير موقع 32‑بت يحدد EmfPlusBrush، الذي يتم تحديد محتواه بواسطة البت S في حقل Flags. |
| [setBrushId(int value)](#setBrushId-int-) | يحصل أو يعيّن معرف الفرشاة عددًا صحيحًا غير موقع 32‑بت يحدد EmfPlusBrush، الذي يتم تحديد محتواه بواسطة البت S في حقل Flags. |
| [getTension()](#getTension--) | يحصل أو يعيّن التوتر قيمة عائمة 32‑بت تحدد مدى انحناء المنحنى المكعب عندما يمر عبر النقاط. |
| [setTension(float value)](#setTension-float-) | يحصل أو يعيّن التوتر قيمة عائمة 32‑بت تحدد مدى انحناء المنحنى المكعب عندما يمر عبر النقاط. |
| [getPointData()](#getPointData--) | يحصل أو يعيّن بيانات النقطة مصفوفة من Count نقاط تحدد نقاط النهاية للخطوط التي تُعرّف المنحنى المكعب. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | يحصل أو يعيّن بيانات النقطة مصفوفة من Count نقاط تحدد نقاط النهاية للخطوط التي تُعرّف المنحنى المكعب. |
### EmfPlusFillClosedCurve(EmfPlusRecord source) {#EmfPlusFillClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillClosedCurve(EmfPlusRecord source)
```


ينشئ مثيلاً جديدًا من الفئة `EmfPlusFillClosedCurve`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### isColor() {#isColor--}
```
public boolean isColor()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الحالة ملونة. إذا تم الضبط، يحدد BrushId اللون ككائن EmfPlusARGB (القسم 2.2.2.1). إذا لم يتم الضبط، يحتوي BrushId على فهرس كائن EmfPlusBrush (القسم 2.2.1.1) في جدول كائنات EMF+.

القيمة: `true` إذا كانت هذه الحالة ملونة؛ وإلا `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الحالة ملونة. إذا تم الضبط، يحدد BrushId اللون ككائن EmfPlusARGB (القسم 2.2.2.1). إذا لم يتم الضبط، يحتوي BrushId على فهرس كائن EmfPlusBrush (القسم 2.2.1.1) في جدول كائنات EMF+.

القيمة: `true` إذا كانت هذه الحالة ملونة؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillClosedCurve` مضغوطًا. تشير هذه العلامة إلى ما إذا كان حقل PointData يحدد بيانات مضغوطة. إذا تم الضبط، تحدد PointData مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات صحيحة 16‑بت. إذا تم الإلغاء، تحدد PointData مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات عائمة 32‑بت. ---------------------- عملية تعبئة "winding" تملأ المناطق وفقًا لقاعدة "التساوي الفردي". وفقًا لهذه القاعدة، يمكن تحديد ما إذا كانت نقطة الاختبار داخل أو خارج منحنى مغلق كما يلي: ارسم خطًا من نقطة الاختبار إلى نقطة تقع بعيدًا عن المنحنى. إذا قطع هذا الخط المنحنى عددًا فرديًا من المرات، تكون نقطة الاختبار داخل المنحنى؛ وإلا تكون خارج المنحنى. --------------------- عملية تعبئة "alternate" تملأ المناطق وفقًا لقاعدة "غير الصفر". وفقًا لهذه القاعدة، يمكن تحديد ما إذا كانت نقطة الاختبار داخل أو خارج منحنى مغلق كما يلي: ارسم خطًا من نقطة الاختبار إلى نقطة تقع بعيدًا عن المنحنى. احسب عدد المرات التي يقطع فيها المنحنى خط الاختبار من اليسار إلى اليمين، وعدد المرات التي يقطع فيها المنحنى خط الاختبار من اليمين إلى اليسار. إذا كان الرقمان متساويين، تكون نقطة الاختبار خارج المنحنى؛ وإلا تكون داخل المنحنى.

القيمة: `true` إذا كان مضغوطًا؛ وإلا `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillClosedCurve` مضغوطًا. تشير هذه العلامة إلى ما إذا كان حقل PointData يحدد بيانات مضغوطة. إذا تم الضبط، تحدد PointData مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات صحيحة 16‑بت. إذا تم الإلغاء، تحدد PointData مواقع مطلقة في مساحة الإحداثيات باستخدام إحداثيات عائمة 32‑بت. ---------------------- عملية تعبئة "winding" تملأ المناطق وفقًا لقاعدة "التساوي الفردي". وفقًا لهذه القاعدة، يمكن تحديد ما إذا كانت نقطة الاختبار داخل أو خارج منحنى مغلق كما يلي: ارسم خطًا من نقطة الاختبار إلى نقطة تقع بعيدًا عن المنحنى. إذا قطع هذا الخط المنحنى عددًا فرديًا من المرات، تكون نقطة الاختبار داخل المنحنى؛ وإلا تكون خارج المنحنى. --------------------- عملية تعبئة "alternate" تملأ المناطق وفقًا لقاعدة "غير الصفر". وفقًا لهذه القاعدة، يمكن تحديد ما إذا كانت نقطة الاختبار داخل أو خارج منحنى مغلق كما يلي: ارسم خطًا من نقطة الاختبار إلى نقطة تقع بعيدًا عن المنحنى. احسب عدد المرات التي يقطع فيها المنحنى خط الاختبار من اليسار إلى اليمين، وعدد المرات التي يقطع فيها المنحنى خط الاختبار من اليمين إلى اليسار. إذا كان الرقمان متساويين، تكون نقطة الاختبار خارج المنحنى؛ وإلا تكون داخل المنحنى.

القيمة: `true` إذا كان مضغوطًا؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getWinding() {#getWinding--}
```
public boolean getWinding()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillClosedCurve` متدوّرًا. تشير هذه العلامة إلى طريقة تنفيذ عملية التعبئة. إذا تم الضبط، تكون التعبئة من نوع "winding". إذا تم الإلغاء، تكون التعبئة من نوع "alternate".

القيمة: `true` إذا كان ملتفًا؛ وإلا `false`.

**Returns:**
boolean
### setWinding(boolean value) {#setWinding-boolean-}
```
public void setWinding(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillClosedCurve` متدوّرًا. تشير هذه العلامة إلى طريقة تنفيذ عملية التعبئة. إذا تم الضبط، تكون التعبئة من نوع "winding". إذا تم الإلغاء، تكون التعبئة من نوع "alternate".

القيمة: `true` إذا كان ملتفًا؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillClosedCurve` نسبيًا. تشير هذه البتة إلى ما إذا كان حقل PointData يحدد مواقع نسبية أو مطلقة. إذا تم تعيينها، كل عنصر في PointData يحدد موقعًا في فضاء الإحداثيات يكون نسبيًا للموقع المحدد بالعنصر السابق في المصفوفة. في حالة العنصر الأول في PointData، يُفترض وجود موقع سابق عند الإحداثيات (0,0). إذا لم تُعيّن، يحدد PointData المواقع المطلقة وفقًا لعلامة C. ملاحظة: إذا تم تعيين هذه العلامة، تكون علامة C (أعلاه) غير معرفة ويجب تجاهلها.

القيمة: `true` إذا كان نسبيًا؛ وإلا `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `EmfPlusFillClosedCurve` نسبيًا. تشير هذه البتة إلى ما إذا كان حقل PointData يحدد مواقع نسبية أو مطلقة. إذا تم تعيينها، كل عنصر في PointData يحدد موقعًا في فضاء الإحداثيات يكون نسبيًا للموقع المحدد بالعنصر السابق في المصفوفة. في حالة العنصر الأول في PointData، يُفترض وجود موقع سابق عند الإحداثيات (0,0). إذا لم تُعيّن، يحدد PointData المواقع المطلقة وفقًا لعلامة C. ملاحظة: إذا تم تعيين هذه العلامة، تكون علامة C (أعلاه) غير معرفة ويجب تجاهلها.

القيمة: `true` إذا كان نسبيًا؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


يحصل أو يعيّن معرف الفرشاة، وهو عدد صحيح غير موقع 32‑بت يحدد EmfPlusBrush، حيث يتم تحديد محتواه بواسطة البت S في حقل Flags. تُستخدم هذه الفرشاة لملء داخل المنحنى القاردي المغلق.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


يحصل أو يعيّن معرف الفرشاة، وهو عدد صحيح غير موقع 32‑بت يحدد EmfPlusBrush، حيث يتم تحديد محتواه بواسطة البت S في حقل Flags. تُستخدم هذه الفرشاة لملء داخل المنحنى القاردي المغلق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getTension() {#getTension--}
```
public float getTension()
```


يحصل أو يعيّن التوتر، وهو قيمة عائمة 32‑بت تحدد مدى انحناء المنحنى أثناء مروره عبر النقاط. القيمة 0.0 تشير إلى أن المنحنى هو سلسلة من الخطوط المستقيمة. كلما زادت القيمة، يصبح المنحنى أكثر استدارة. لمزيد من المعلومات، راجع [SPLINE77] و [PETZOLD].

**Returns:**
float
### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


يحصل أو يعيّن التوتر، وهو قيمة عائمة 32‑بت تحدد مدى انحناء المنحنى أثناء مروره عبر النقاط. القيمة 0.0 تشير إلى أن المنحنى هو سلسلة من الخطوط المستقيمة. كلما زادت القيمة، يصبح المنحنى أكثر استدارة. لمزيد من المعلومات، راجع [SPLINE77] و [PETZOLD].

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


يحصل أو يعيّن بيانات النقاط، وهي مصفوفة من نقاط Count تحدد نقاط النهاية للخطوط التي تُعرّف المنحنى. في منحنى قاردي مغلق، يستمر المنحنى عبر النقطة الأخيرة في مصفوفة PointData ويتصل بالنقطة الأولى في المصفوفة.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


يحصل أو يعيّن بيانات النقاط، وهي مصفوفة من نقاط Count تحدد نقاط النهاية للخطوط التي تُعرّف المنحنى. في منحنى قاردي مغلق، يستمر المنحنى عبر النقطة الأخيرة في مصفوفة PointData ويتصل بالنقطة الأولى في المصفوفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

