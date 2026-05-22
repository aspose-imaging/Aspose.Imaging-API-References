---
title: "EmfPlusColorCurveEffect فئة"
type: docs
weight: 180
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/
---

**Summary:** The ColorCurveEffect object specifies one of eight adjustments to the color curve of an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusColorCurveEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusColorCurveEffect()](#EmfPlusColorCurveEffect__1) | يُنشئ مثيلًا جديدًا من فئة EmfPlusColorCurveEffect |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| adjustment_intensity | int | r/w | يحصل أو يضبط عدد صحيح 32-بت موقع يحدد شدة تعديل المنحنى لقناة اللون المحددة بواسطة CurveChannel. تتفاوت نطاقات القيم ذات المعنى لهذا الحقل وفقًا لقيمة CurveAdjustment، كما يلي:<br/>            نطاق تعديل التعرض:<br/>            -255 ≤ value &lt; 0 كلما انخفضت القيمة، SHOULD يقل تعريض الصورة.<br/>            0 قيمة 0 تحدد أن التعرض MUST NOT يتغير.<br/>            0 &lt; value ≤ 255 كلما زادت القيمة، SHOULD يزيد تعريض الصورة.<br/>            نطاق تعديل الكثافة:<br/>            -255 ≤ value &lt; 0<br/>            كلما انخفضت القيمة، SHOULD تقل كثافة الصورة، مما ينتج صورة أغمق.<br/>            0 قيمة 0 تحدد أن الكثافة MUST NOT تتغير.<br/>            0 &lt; value ≤ 255<br/>            كلما زادت القيمة، SHOULD تزيد كثافة الصورة.<br/>            نطاق تعديل التباين:<br/>            -100 ≤ value &lt; 0 كلما انخفضت القيمة، SHOULD يقل تباين الصورة.<br/>            0 قيمة 0 تحدد أن التباين MUST NOT يتغير.<br/>            0 &lt; value ≤ 100 كلما زادت القيمة، SHOULD يزيد تباين الصورة.<br/>            نطاق تعديل الإبراز:<br/>            -100 ≤ value &lt; 0 كلما انخفضت القيمة، SHOULD تظهر المناطق الفاتحة في الصورة أغمق.<br/>            0 قيمة 0 تحدد أن الإبراز MUST NOT يتغير.<br/>            0 &lt; value ≤ 100 كلما زادت القيمة، SHOULD تظهر المناطق الفاتحة في الصورة أفتح.<br/>            نطاق تعديل الظل:<br/>            -100 ≤ value &lt; 0 كلما انخفضت القيمة، SHOULD تظهر المناطق الداكنة في الصورة أغمق.<br/>            0 قيمة 0 تحدد أن الظل MUST NOT يتغير.<br/>            0 &lt; value ≤ 100 كلما زادت القيمة، SHOULD تظهر المناطق الداكنة في الصورة أفتح.<br/>            نطاق تعديل تشبع الأبيض:<br/>            0 — 255 كلما زادت القيمة، يزيد الحد الأعلى لنطاق شدة قنوات اللون.<br/>            نطاق تعديل تشبع الأسود:<br/>            0 — 255 كلما زادت القيمة، يزيد الحد الأدنى لنطاق شدة قنوات اللون. |
| curve_adjustment | [EmfPlusCurveAdjustments](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscurveadjustments/) | r/w | يحصل أو يضبط عدد صحيح غير موقع 32-بت يحدد تعديل المنحنى لتطبيقه على الألوان في bitmap. يجب أن تكون هذه القيمة معرفة في تعداد CurveAdjustments<br/>            (section 2.1.1.7). |
| curve_channel | [EmfPlusCurveChannel](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscurvechannel/) | r/w | يحصل أو يضبط عدد صحيح غير موقع 32-بت يحدد قناة اللون التي يطبق عليها تعديل المنحنى. يجب أن تكون هذه القيمة معرفة في تعداد CurveChannel<br/>            (section 2.1.1.8). |


### Constructor: EmfPlusColorCurveEffect() {#EmfPlusColorCurveEffect__1}


```
 EmfPlusColorCurveEffect() 
```

يُنشئ مثيلًا جديدًا من فئة EmfPlusColorCurveEffect

