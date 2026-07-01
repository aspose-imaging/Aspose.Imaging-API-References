---
title: "EmfPlusInterpolationMode"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تحدد تعداد InterpolationMode طرقًا لتنفيذ التحجيم بما في ذلك التمدد والتقليص."
type: docs
weight: 29
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusinterpolationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusInterpolationMode extends System.Enum
```

تحدد تعداد InterpolationMode طرق تنفيذ التحجيم، بما في ذلك التمدد والتقليص.
## الحقول

| حقل | الوصف |
| --- | --- |
| [InterpolationModeDefault](#InterpolationModeDefault) | يحدد وضع الاستيفاء الافتراضي، والذي يتم تعريفه كـ InterpolationModeBilinear. |
| [InterpolationModeLowQuality](#InterpolationModeLowQuality) | يحدد وضع استيفاء منخفض الجودة، والذي يتم تعريفه كـ InterpolationModeNearestNeighbor. |
| [InterpolationModeHighQuality](#InterpolationModeHighQuality) | يحدد وضع استيفاء عالي الجودة، والذي يتم تعريفه كـ InterpolationModeHighQualityBicubic. |
| [InterpolationModeBilinear](#InterpolationModeBilinear) | يحدد الاستيفاء الثنائي الخطوط، والذي يستخدم أقرب جوار 2×2 من البكسلات المعروفة المحيطة بالبكسل المستنتج. |
| [InterpolationModeBicubic](#InterpolationModeBicubic) | يحدد الاستيفاء الثلاثي المكعب، والذي يستخدم أقرب جوار 4×4 من البكسلات المعروفة المحيطة بالبكسل المستنتج. |
| [InterpolationModeNearestNeighbor](#InterpolationModeNearestNeighbor) | يحدد استيفاء أقرب جار، والذي يستخدم فقط قيمة البكسل الأقرب إلى البكسل المستنتج. |
| [InterpolationModeHighQualityBilinear](#InterpolationModeHighQualityBilinear) | يحدد الاستيفاء الثنائي الخطوط مع الترشيح المسبق. |
| [InterpolationModeHighQualityBicubic](#InterpolationModeHighQualityBicubic) | يحدد الاستيفاء الثلاثي المكعب مع الترشيح المسبق، والذي ينتج أعلى جودة من بين هذه الخيارات. |
### InterpolationModeDefault {#InterpolationModeDefault}
```
public static final byte InterpolationModeDefault
```


يحدد وضع الاستيفاء الافتراضي، والذي يتم تعريفه كـ InterpolationModeBilinear.

### InterpolationModeLowQuality {#InterpolationModeLowQuality}
```
public static final byte InterpolationModeLowQuality
```


يحدد وضع استيفاء منخفض الجودة، والذي يتم تعريفه كـ InterpolationModeNearestNeighbor.

### InterpolationModeHighQuality {#InterpolationModeHighQuality}
```
public static final byte InterpolationModeHighQuality
```


يحدد وضع استيفاء عالي الجودة، والذي يتم تعريفه كـ InterpolationModeHighQualityBicubic.

### InterpolationModeBilinear {#InterpolationModeBilinear}
```
public static final byte InterpolationModeBilinear
```


يحدد الاستيفاء الثنائي الخطوط، والذي يستخدم أقرب جوار 2×2 من البكسلات المعروفة المحيطة بالبكسل المستنتج. المتوسط المرجح لهذه القيم الأربع للبكسلات المعروفة يحدد القيمة التي تُعيّن للبكسل المستنتج. النتيجة تبدو أكثر سلاسة من InterpolationModeNearestNeighbor.

### InterpolationModeBicubic {#InterpolationModeBicubic}
```
public static final byte InterpolationModeBicubic
```


يحدد الاستيفاء الثلاثي المكعب، والذي يستخدم أقرب جوار 4×4 من البكسلات المعروفة المحيطة بالبكسل المستنتج. المتوسط المرجح لهذه القيم الستة عشر للبكسلات المعروفة يحدد القيمة التي تُعيّن للبكسل المستنتج. وبما أن البكسلات المعروفة قد تكون على مسافات مختلفة من البكسل المستنتج، تُعطى البكسلات الأقرب وزنًا أعلى في الحساب. النتيجة تبدو أكثر سلاسة من InterpolationModeBilinear.

### InterpolationModeNearestNeighbor {#InterpolationModeNearestNeighbor}
```
public static final byte InterpolationModeNearestNeighbor
```


يحدد استيفاء أقرب جار، والذي يستخدم فقط قيمة البكسل الأقرب إلى البكسل المستنتج. هذا الوضع ببساطة يكرر أو يزيل البكسلات، مما ينتج أدنى جودة من بين هذه الخيارات.

### InterpolationModeHighQualityBilinear {#InterpolationModeHighQualityBilinear}
```
public static final byte InterpolationModeHighQualityBilinear
```


يحدد الاستيفاء الثنائي الخطوط مع الترشيح المسبق.

### InterpolationModeHighQualityBicubic {#InterpolationModeHighQualityBicubic}
```
public static final byte InterpolationModeHighQualityBicubic
```


يحدد الاستيفاء الثلاثي المكعب مع الترشيح المسبق، والذي ينتج أعلى جودة من بين هذه الخيارات.

