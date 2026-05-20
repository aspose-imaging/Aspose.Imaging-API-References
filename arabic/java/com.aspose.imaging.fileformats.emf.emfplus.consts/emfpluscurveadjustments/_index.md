---
title: "EmfPlusCurveAdjustments"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تعداد CurveAdjustments يحدد التعديلات التي يمكن تطبيقها على منحنى لون الصورة."
type: docs
weight: 16
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluscurveadjustments/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusCurveAdjustments extends System.Enum
```

تعداد CurveAdjustments يحدد التعديلات التي يمكن تطبيقها على منحنى لون الصورة.
## الحقول

| حقل | الوصف |
| --- | --- |
| [AdjustExposure](#AdjustExposure) | يحدد محاكاة زيادة أو تقليل التعرض لصورة. |
| [AdjustDensity](#AdjustDensity) | يحدد محاكاة زيادة أو تقليل كثافة صورة. |
| [AdjustContrast](#AdjustContrast) | يحدد زيادة أو تقليل التباين في صورة. |
| [AdjustHighlight](#AdjustHighlight) | يحدد زيادة أو تقليل قيمة قناة لون في صورة، إذا كانت تلك القناة لديها قيمة أعلى من نصف الشدة. |
| [AdjustShadow](#AdjustShadow) | يحدد زيادة أو تقليل قيمة قناة لون في صورة، إذا كانت تلك القناة لديها قيمة أقل من نصف الشدة. |
| [AdjustMidtone](#AdjustMidtone) | يحدد تعديلًا يفتح أو يغلق صورة. |
| [AdjustWhiteSaturation](#AdjustWhiteSaturation) | يحدد تعديلًا لتشبع الأبيض في الصورة، يُعرّف بأنه القيمة القصوى في نطاق الشدة لقناة اللون المحددة، والذي عادةً يكون من 0 إلى 255. |
| [AdjustBlackSaturation](#AdjustBlackSaturation) | يحدد تعديلًا لتشبع الأسود في الصورة، وهو القيمة الدنيا في نطاق الشدة لقناة اللون المحددة، والذي عادةً يكون من 0 إلى 255. |
### AdjustExposure {#AdjustExposure}
```
public static final int AdjustExposure
```


يحدد محاكاة زيادة أو تقليل التعرض لصورة.

### AdjustDensity {#AdjustDensity}
```
public static final int AdjustDensity
```


يحدد محاكاة زيادة أو تقليل كثافة صورة.

### AdjustContrast {#AdjustContrast}
```
public static final int AdjustContrast
```


يحدد زيادة أو تقليل التباين في صورة.

### AdjustHighlight {#AdjustHighlight}
```
public static final int AdjustHighlight
```


يحدد زيادة أو انخفاض في قيمة قناة اللون في الصورة، إذا كانت تلك القناة لديها قيمة أعلى من نصف الشدة. يمكن استخدام هذا التعديل لزيادة الوضوح في المناطق الفاتحة من الصورة دون التأثير على المناطق الداكنة.

### AdjustShadow {#AdjustShadow}
```
public static final int AdjustShadow
```


يحدد زيادة أو انخفاض في قيمة قناة اللون في الصورة، إذا كانت تلك القناة لديها قيمة أقل من نصف الشدة. يمكن استخدام هذا التعديل لزيادة الوضوح في المناطق الداكنة من الصورة دون التأثير على المناطق الفاتحة.

### AdjustMidtone {#AdjustMidtone}
```
public static final int AdjustMidtone
```


يحدد تعديلًا يفتح أو يغلق الصورة. قيم قناة اللون في وسط نطاق الشدة تُعدل أكثر من القيم القريبة من الحد الأدنى أو الحد الأقصى للشدة. يمكن استخدام هذا التعديل لفتح أو إغلاق الصورة دون فقدان التباين بين أظلم وأفتح أجزاء الصورة.

### AdjustWhiteSaturation {#AdjustWhiteSaturation}
```
public static final int AdjustWhiteSaturation
```


يحدد تعديلًا لتشبع الأبيض في الصورة، يُعرّف بأنه القيمة القصوى في نطاق الشدة لقناة اللون المحددة، والذي عادةً يكون من 0 إلى 255.

--------------------

على سبيل المثال، قيمة تعديل تشبع الأبيض 240 تحدد أن قيم قناة اللون في النطاق من 0 إلى 240 تُعدل لتنتشر على النطاق من 0 إلى 255، مع تعيين القيم التي تزيد عن 240 إلى 255.

### AdjustBlackSaturation {#AdjustBlackSaturation}
```
public static final int AdjustBlackSaturation
```


يحدد تعديلًا لتشبع الأسود في الصورة، وهو القيمة الدنيا في نطاق الشدة لقناة اللون المحددة، والذي عادةً يكون من 0 إلى 255.

--------------------

على سبيل المثال، قيمة تعديل تشبع الأسود 15 تحدد أن قيم قناة اللون في النطاق من 15 إلى 255 تُعدل لتنتشر على النطاق من 0 إلى 255، مع تعيين القيم التي تقل عن 15 إلى 0.

