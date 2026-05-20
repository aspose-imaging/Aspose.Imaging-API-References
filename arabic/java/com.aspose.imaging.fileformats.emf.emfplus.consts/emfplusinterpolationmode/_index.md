---
title: "EmfPlusInterpolationMode"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تحدد تعداد InterpolationMode طرق تنفيذ التحجيم بما في ذلك التمدد والتقليص."
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
| [InterpolationModeDefault](#InterpolationModeDefault) | يحدد وضع الاستيفاء الافتراضي، والذي يُعرّف كـ InterpolationModeBilinear. |
| [InterpolationModeLowQuality](#InterpolationModeLowQuality) | يحدد وضع استيفاء منخفض الجودة، والذي يُعرّف كـ InterpolationModeNearestNeighbor. |
| [InterpolationModeHighQuality](#InterpolationModeHighQuality) | يحدد وضع استيفاء عالي الجودة، والذي يُعرّف كـ InterpolationModeHighQualityBicubic. |
| [InterpolationModeBilinear](#InterpolationModeBilinear) | يحدد الاستيفاء الثنائي الخطية، والذي يستخدم أقرب جوار 2×2 من البكسلات المعروفة المحيطة بالبكسل المستوفى. |
| [InterpolationModeBicubic](#InterpolationModeBicubic) | يحدد الاستيفاء البيكوبيكي، والذي يستخدم أقرب جوار 4x4 من البكسلات المعروفة المحيطة بالبكسل المستنتج. |
| [InterpolationModeNearestNeighbor](#InterpolationModeNearestNeighbor) | يحدد استيفاء أقرب جار، والذي يستخدم فقط قيمة البكسل الأقرب إلى البكسل المستنتج. |
| [InterpolationModeHighQualityBilinear](#InterpolationModeHighQualityBilinear) | يحدد الاستيفاء الخطي الثنائي مع الترشيح المسبق. |
| [InterpolationModeHighQualityBicubic](#InterpolationModeHighQualityBicubic) | يحدد الاستيفاء البيكوبيكي مع الترشيح المسبق، والذي ينتج أعلى جودة نتيجة بين هذه الخيارات. |
### InterpolationModeDefault {#InterpolationModeDefault}
```
public static final byte InterpolationModeDefault
```


يحدد وضع الاستيفاء الافتراضي، والذي يُعرّف كـ InterpolationModeBilinear.

### InterpolationModeLowQuality {#InterpolationModeLowQuality}
```
public static final byte InterpolationModeLowQuality
```


يحدد وضع استيفاء منخفض الجودة، والذي يُعرّف كـ InterpolationModeNearestNeighbor.

### InterpolationModeHighQuality {#InterpolationModeHighQuality}
```
public static final byte InterpolationModeHighQuality
```


يحدد وضع استيفاء عالي الجودة، والذي يُعرّف كـ InterpolationModeHighQualityBicubic.

### InterpolationModeBilinear {#InterpolationModeBilinear}
```
public static final byte InterpolationModeBilinear
```


يحدد الاستيفاء الخطي الثنائي، والذي يستخدم أقرب جوار 2x2 من البكسلات المعروفة المحيطة بالبكسل المستنتج. المتوسط المرجح لهذه القيم الأربع للبكسلات المعروفة يحدد القيمة التي تُعطى للبكسل المستنتج. النتيجة تبدو أكثر سلاسة مقارنةً بـ InterpolationModeNearestNeighbor.

### InterpolationModeBicubic {#InterpolationModeBicubic}
```
public static final byte InterpolationModeBicubic
```


يحدد الاستيفاء البيكوبيكي، والذي يستخدم أقرب جوار 4x4 من البكسلات المعروفة المحيطة بالبكسل المستنتج. المتوسط المرجح لهذه القيم الستة عشر للبكسلات المعروفة يحدد القيمة التي تُعطى للبكسل المستنتج. نظرًا لأن البكسلات المعروفة قد تكون على مسافات مختلفة من البكسل المستنتج، تُعطى البكسلات الأقرب وزنًا أعلى في الحساب. النتيجة تبدو أكثر سلاسة مقارنةً بـ InterpolationModeBilinear.

### InterpolationModeNearestNeighbor {#InterpolationModeNearestNeighbor}
```
public static final byte InterpolationModeNearestNeighbor
```


يحدد استيفاء أقرب جار، والذي يستخدم فقط قيمة البكسل الأقرب إلى البكسل المستنتج. هذا الوضع يكرر أو يزيل البكسلات ببساطة، مما ينتج أدنى جودة نتيجة بين هذه الخيارات.

### InterpolationModeHighQualityBilinear {#InterpolationModeHighQualityBilinear}
```
public static final byte InterpolationModeHighQualityBilinear
```


يحدد الاستيفاء الخطي الثنائي مع الترشيح المسبق.

### InterpolationModeHighQualityBicubic {#InterpolationModeHighQualityBicubic}
```
public static final byte InterpolationModeHighQualityBicubic
```


يحدد الاستيفاء البيكوبيكي مع الترشيح المسبق، والذي ينتج أعلى جودة نتيجة بين هذه الخيارات.

