---
title: "EmfPlusColorCurveEffect"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن ColorCurveEffect يحدد أحد ثمانية تعديلات على منحنى الألوان في الصورة."
type: docs
weight: 27
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusColorCurveEffect extends EmfPlusImageEffectsObjectType
```

كائن ColorCurveEffect يحدد أحد ثمانية تعديلات على منحنى الألوان في الصورة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusColorCurveEffect()](#EmfPlusColorCurveEffect--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCurveAdjustment()](#getCurveAdjustment--) | يحصل أو يضبط عددًا صحيحًا غير موقع بسعة 32 بت يحدد تعديل المنحنى لتطبيقه على الألوان في الصورة النقطية. |
| [setCurveAdjustment(int value)](#setCurveAdjustment-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع بسعة 32 بت يحدد تعديل المنحنى لتطبيقه على الألوان في الصورة النقطية. |
| [getCurveChannel()](#getCurveChannel--) | يحصل أو يضبط عددًا صحيحًا غير موقع بسعة 32 بت يحدد قناة اللون التي يُطبق عليها تعديل المنحنى. |
| [setCurveChannel(int value)](#setCurveChannel-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع بسعة 32 بت يحدد قناة اللون التي يُطبق عليها تعديل المنحنى. |
| [getAdjustmentIntensity()](#getAdjustmentIntensity--) | يحصل أو يضبط عددًا صحيحًا موقعًا بسعة 32 بت يحدد شدة تعديل المنحنى لقناة اللون المحددة بواسطة CurveChannel. |
| [setAdjustmentIntensity(int value)](#setAdjustmentIntensity-int-) | يحصل أو يضبط عددًا صحيحًا موقعًا بسعة 32 بت يحدد شدة تعديل المنحنى لقناة اللون المحددة بواسطة CurveChannel. |
### EmfPlusColorCurveEffect() {#EmfPlusColorCurveEffect--}
```
public EmfPlusColorCurveEffect()
```


### getCurveAdjustment() {#getCurveAdjustment--}
```
public int getCurveAdjustment()
```


يحصل أو يضبط عددًا صحيحًا غير موقع بسعة 32 بت يحدد تعديل المنحنى لتطبيقه على الألوان في الصورة النقطية. يجب أن تكون هذه القيمة معرفة في تعداد CurveAdjustments (القسم 2.1.1.7).

**Returns:**
int
### setCurveAdjustment(int value) {#setCurveAdjustment-int-}
```
public void setCurveAdjustment(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع بسعة 32 بت يحدد تعديل المنحنى لتطبيقه على الألوان في الصورة النقطية. يجب أن تكون هذه القيمة معرفة في تعداد CurveAdjustments (القسم 2.1.1.7).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getCurveChannel() {#getCurveChannel--}
```
public int getCurveChannel()
```


يحصل أو يضبط عددًا صحيحًا غير موقع بسعة 32 بت يحدد قناة اللون التي يُطبق عليها تعديل المنحنى. يجب أن تكون هذه القيمة معرفة في تعداد CurveChannel (القسم 2.1.1.8).

**Returns:**
int
### setCurveChannel(int value) {#setCurveChannel-int-}
```
public void setCurveChannel(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع بسعة 32 بت يحدد قناة اللون التي يُطبق عليها تعديل المنحنى. يجب أن تكون هذه القيمة معرفة في تعداد CurveChannel (القسم 2.1.1.8).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getAdjustmentIntensity() {#getAdjustmentIntensity--}
```
public int getAdjustmentIntensity()
```


يحصل أو يضبط عددًا صحيحًا موقعًا بسعة 32 بت يحدد شدة تعديل المنحنى لقناة اللون المحددة بواسطة CurveChannel. تتفاوت نطاقات القيم المعنوية لهذا الحقل وفقًا لقيمة CurveAdjustment، كما يلي: نطاق تعديل التعرض: -255 \u2264 value < 0 كلما انخفضت القيمة، يجب أن ينخفض تعرض الصورة. 0 قيمة 0 تحدد أن التعرض لا يجب أن يتغير. 0 < value \u2264 255 كلما زادت القيمة، يجب أن يزداد تعرض الصورة. نطاق تعديل الكثافة: -255 \u2264 value < 0 كلما انخفضت القيمة، يجب أن تنخفض كثافة الصورة، مما ينتج صورة أغمق. 0 قيمة 0 تحدد أن الكثافة لا يجب أن تتغير. 0 < value \u2264 255 كلما زادت القيمة، يجب أن تزداد كثافة الصورة. نطاق تعديل التباين: -100 \u2264 value < 0 كلما انخفضت القيمة، يجب أن ينخفض تباين الصورة. 0 قيمة 0 تحدد أن التباين لا يجب أن يتغير. 0 < value \u2264 100 كلما زادت القيمة، يجب أن يزداد تباين الصورة. نطاق تعديل الإبراز: -100 \u2264 value < 0 كلما انخفضت القيمة، يجب أن تظهر المناطق الفاتحة من الصورة أغمق. 0 قيمة 0 تحدد أن الإبراز لا يجب أن يتغير. 0 < value \u2264 100 كلما زادت القيمة، يجب أن تظهر المناطق الفاتحة من الصورة أفتح. نطاق تعديل الظل: -100 \u2264 value < 0 كلما انخفضت القيمة، يجب أن تظهر المناطق الداكنة من الصورة أغمق. 0 قيمة 0 تحدد أن الظل لا يجب أن يتغير. 0 < value \u2264 100 كلما زادت القيمة، يجب أن تظهر المناطق الداكنة من الصورة أفتح. نطاق تعديل تشبع الأبيض: 0 \u2014 255 كلما زادت القيمة، يزداد الحد الأعلى لنطاق شدة قنوات اللون. نطاق تعديل تشبع الأسود: 0 \u2014 255 كلما زادت القيمة، يزداد الحد الأدنى لنطاق شدة قنوات اللون.

**Returns:**
int
### setAdjustmentIntensity(int value) {#setAdjustmentIntensity-int-}
```
public void setAdjustmentIntensity(int value)
```


يحصل أو يضبط عددًا صحيحًا موقعًا بسعة 32 بت يحدد شدة تعديل المنحنى لقناة اللون المحددة بواسطة CurveChannel. تتفاوت نطاقات القيم المعنوية لهذا الحقل وفقًا لقيمة CurveAdjustment، كما يلي: نطاق تعديل التعرض: -255 \u2264 value < 0 كلما انخفضت القيمة، يجب أن ينخفض تعرض الصورة. 0 قيمة 0 تحدد أن التعرض لا يجب أن يتغير. 0 < value \u2264 255 كلما زادت القيمة، يجب أن يزداد تعرض الصورة. نطاق تعديل الكثافة: -255 \u2264 value < 0 كلما انخفضت القيمة، يجب أن تنخفض كثافة الصورة، مما ينتج صورة أغمق. 0 قيمة 0 تحدد أن الكثافة لا يجب أن تتغير. 0 < value \u2264 255 كلما زادت القيمة، يجب أن تزداد كثافة الصورة. نطاق تعديل التباين: -100 \u2264 value < 0 كلما انخفضت القيمة، يجب أن ينخفض تباين الصورة. 0 قيمة 0 تحدد أن التباين لا يجب أن يتغير. 0 < value \u2264 100 كلما زادت القيمة، يجب أن يزداد تباين الصورة. نطاق تعديل الإبراز: -100 \u2264 value < 0 كلما انخفضت القيمة، يجب أن تظهر المناطق الفاتحة من الصورة أغمق. 0 قيمة 0 تحدد أن الإبراز لا يجب أن يتغير. 0 < value \u2264 100 كلما زادت القيمة، يجب أن تظهر المناطق الفاتحة من الصورة أفتح. نطاق تعديل الظل: -100 \u2264 value < 0 كلما انخفضت القيمة، يجب أن تظهر المناطق الداكنة من الصورة أغمق. 0 قيمة 0 تحدد أن الظل لا يجب أن يتغير. 0 < value \u2264 100 كلما زادت القيمة، يجب أن تظهر المناطق الداكنة من الصورة أفتح. نطاق تعديل تشبع الأبيض: 0 \u2014 255 كلما زادت القيمة، يزداد الحد الأعلى لنطاق شدة قنوات اللون. نطاق تعديل تشبع الأسود: 0 \u2014 255 كلما زادت القيمة، يزداد الحد الأدنى لنطاق شدة قنوات اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

