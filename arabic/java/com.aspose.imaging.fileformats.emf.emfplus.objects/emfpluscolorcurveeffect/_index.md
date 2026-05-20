---
title: "EmfPlusColorCurveEffect"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن ColorCurveEffect يحدد أحد ثمانية تعديلات على منحنى ألوان الصورة."
type: docs
weight: 27
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusColorCurveEffect extends EmfPlusImageEffectsObjectType
```

كائن ColorCurveEffect يحدد أحد ثمانية تعديلات على منحنى ألوان الصورة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusColorCurveEffect()](#EmfPlusColorCurveEffect--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCurveAdjustment()](#getCurveAdjustment--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد تعديل المنحنى لتطبيقه على الألوان في bitmap. |
| [setCurveAdjustment(int value)](#setCurveAdjustment-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد تعديل المنحنى لتطبيقه على الألوان في bitmap. |
| [getCurveChannel()](#getCurveChannel--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد قناة اللون التي يُطبق عليها تعديل المنحنى. |
| [setCurveChannel(int value)](#setCurveChannel-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد قناة اللون التي يُطبق عليها تعديل المنحنى. |
| [getAdjustmentIntensity()](#getAdjustmentIntensity--) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد شدة تعديل المنحنى لقناة اللون المحددة بواسطة CurveChannel. |
| [setAdjustmentIntensity(int value)](#setAdjustmentIntensity-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد شدة تعديل المنحنى لقناة اللون المحددة بواسطة CurveChannel. |
### EmfPlusColorCurveEffect() {#EmfPlusColorCurveEffect--}
```
public EmfPlusColorCurveEffect()
```


### getCurveAdjustment() {#getCurveAdjustment--}
```
public int getCurveAdjustment()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد تعديل المنحنى لتطبيقه على الألوان في bitmap. يجب أن تكون هذه القيمة معرفة في تعداد CurveAdjustments (القسم 2.1.1.7).

**Returns:**
int
### setCurveAdjustment(int value) {#setCurveAdjustment-int-}
```
public void setCurveAdjustment(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد تعديل المنحنى لتطبيقه على الألوان في bitmap. يجب أن تكون هذه القيمة معرفة في تعداد CurveAdjustments (القسم 2.1.1.7).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getCurveChannel() {#getCurveChannel--}
```
public int getCurveChannel()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد قناة اللون التي يُطبق عليها تعديل المنحنى. يجب أن تكون هذه القيمة معرفة في تعداد CurveChannel (القسم 2.1.1.8).

**Returns:**
int
### setCurveChannel(int value) {#setCurveChannel-int-}
```
public void setCurveChannel(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد قناة اللون التي يُطبق عليها تعديل المنحنى. يجب أن تكون هذه القيمة معرفة في تعداد CurveChannel (القسم 2.1.1.8).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getAdjustmentIntensity() {#getAdjustmentIntensity--}
```
public int getAdjustmentIntensity()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد شدة تعديل المنحنى لقناة اللون المحددة بواسطة CurveChannel. تتفاوت نطاقات القيم ذات المعنى لهذا الحقل وفقًا لقيمة CurveAdjustment، كما يلي: نطاق تعديل التعرض: -255 \u2264 value < 0 كلما انخفضت القيمة، SHOULD يقل التعرض للصورة. 0 قيمة 0 تحدد أن التعرض MUST NOT يتغير. 0 < value \u2264 255 كلما ارتفعت القيمة، SHOULD يزيد التعرض للصورة. نطاق تعديل الكثافة: -255 \u2264 value < 0 كلما انخفضت القيمة، SHOULD تقل كثافة الصورة، مما ينتج صورة أغمق. 0 قيمة 0 تحدد أن الكثافة MUST NOT تتغير. 0 < value \u2264 255 كلما ارتفعت القيمة، SHOULD تزيد كثافة الصورة. نطاق تعديل التباين: -100 \u2264 value < 0 كلما انخفضت القيمة، SHOULD يقل التباين في الصورة. 0 قيمة 0 تحدد أن التباين MUST NOT يتغير. 0 < value \u2264 100 كلما ارتفعت القيمة، SHOULD يزيد التباين في الصورة. نطاق تعديل الإضاءة: -100 \u2264 value < 0 كلما انخفضت القيمة، SHOULD تظهر المناطق المضيئة في الصورة أغمق. 0 قيمة 0 تحدد أن الإضاءة MUST NOT تتغير. 0 < value \u2264 100 كلما ارتفعت القيمة، SHOULD تظهر المناطق المضيئة أفتح. نطاق تعديل الظلال: -100 \u2264 value < 0 كلما انخفضت القيمة، SHOULD تظهر المناطق الداكنة في الصورة أغمق. 0 قيمة 0 تحدد أن الظل MUST NOT يتغير. 0 < value \u2264 100 كلما ارتفعت القيمة، SHOULD تظهر المناطق الداكنة أفتح. نطاق تعديل تشبع الأبيض: 0 \u2014 255 كلما ارتفعت القيمة، يزداد الحد الأعلى لنطاق شدة قناة اللون. نطاق تعديل تشبع الأسود: 0 \u2014 255 كلما ارتفعت القيمة، يزداد الحد الأدنى لنطاق شدة قناة اللون.

**Returns:**
int
### setAdjustmentIntensity(int value) {#setAdjustmentIntensity-int-}
```
public void setAdjustmentIntensity(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد شدة تعديل المنحنى لقناة اللون المحددة بواسطة CurveChannel. تتفاوت نطاقات القيم ذات المعنى لهذا الحقل وفقًا لقيمة CurveAdjustment، كما يلي: نطاق تعديل التعرض: -255 \u2264 value < 0 كلما انخفضت القيمة، SHOULD يقل التعرض للصورة. 0 قيمة 0 تحدد أن التعرض MUST NOT يتغير. 0 < value \u2264 255 كلما ارتفعت القيمة، SHOULD يزيد التعرض للصورة. نطاق تعديل الكثافة: -255 \u2264 value < 0 كلما انخفضت القيمة، SHOULD تقل كثافة الصورة، مما ينتج صورة أغمق. 0 قيمة 0 تحدد أن الكثافة MUST NOT تتغير. 0 < value \u2264 255 كلما ارتفعت القيمة، SHOULD تزيد كثافة الصورة. نطاق تعديل التباين: -100 \u2264 value < 0 كلما انخفضت القيمة، SHOULD يقل التباين في الصورة. 0 قيمة 0 تحدد أن التباين MUST NOT يتغير. 0 < value \u2264 100 كلما ارتفعت القيمة، SHOULD يزيد التباين في الصورة. نطاق تعديل الإضاءة: -100 \u2264 value < 0 كلما انخفضت القيمة، SHOULD تظهر المناطق المضيئة في الصورة أغمق. 0 قيمة 0 تحدد أن الإضاءة MUST NOT تتغير. 0 < value \u2264 100 كلما ارتفعت القيمة، SHOULD تظهر المناطق المضيئة أفتح. نطاق تعديل الظلال: -100 \u2264 value < 0 كلما انخفضت القيمة، SHOULD تظهر المناطق الداكنة في الصورة أغمق. 0 قيمة 0 تحدد أن الظل MUST NOT يتغير. 0 < value \u2264 100 كلما ارتفعت القيمة، SHOULD تظهر المناطق الداكنة أفتح. نطاق تعديل تشبع الأبيض: 0 \u2014 255 كلما ارتفعت القيمة، يزداد الحد الأعلى لنطاق شدة قناة اللون. نطاق تعديل تشبع الأسود: 0 \u2014 255 كلما ارتفعت القيمة، يزداد الحد الأدنى لنطاق شدة قناة اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

