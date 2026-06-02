---
title: "تعداد EmfPlusInterpolationMode"
second_title: "Aspose.Imaging for .NET API Reference"
description: "تعداد Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusInterpolationMode. يعرّف تعداد InterpolationMode طرق تنفيذ التحجيم بما في ذلك التمدد والتقليص."
type: docs
weight: 4990
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusinterpolationmode/
---
## EmfPlusInterpolationMode enumeration

يحدد تعداد InterpolationMode طرق تنفيذ التحجيم، بما في ذلك التمدد والتقليص.

```csharp
public enum EmfPlusInterpolationMode : byte
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| InterpolationModeDefault | `0` | يحدد وضع الاستيفاء الافتراضي، والذي يُعرّف بأنه InterpolationModeBilinear. |
| InterpolationModeLowQuality | `1` | يحدد وضع استيفاء منخفض الجودة، والذي يُعرّف بأنه InterpolationModeNearestNeighbor. |
| InterpolationModeHighQuality | `2` | يحدد وضع استيفاء عالي الجودة، والذي يُعرّف بأنه InterpolationModeHighQualityBicubic. |
| InterpolationModeBilinear | `3` | يحدد الاستيفاء الثنائي الخطّي، الذي يستخدم أقرب مجموعة 2×2 من البكسلات المعروفة المحيطة بالبكسل المستوفى. المتوسط المرجّح لهذه القيم الأربعة يحدد القيمة التي تُعطى للبكسل المستوفى. النتيجة تبدو أكثر سلاسة مقارنةً بـ InterpolationModeNearestNeighbor. |
| InterpolationModeBicubic | `4` | يحدد الاستيفاء البيكوبيكي، الذي يستخدم أقرب جوار 4×4 من البكسلات المعروفة المحيطة بالبكسل المستنتج. المتوسط المرجح لهذه القيم الـ16 للبكسلات المعروفة يحدد القيمة التي تُعيّن للبكسل المستنتج. نظرًا لأن البكسلات المعروفة قد تكون على مسافات متفاوتة من البكسل المستنتج، تُعطى البكسلات الأقرب وزنًا أعلى في الحساب. النتيجة تبدو أكثر سلاسة من InterpolationModeBilinear. |
| InterpolationModeNearestNeighbor | `5` | يحدد استيفاء أقرب جار، الذي يستخدم فقط قيمة البكسل الأقرب إلى البكسل المستنتج. هذا الوضع يكرر أو يزيل البكسلات ببساطة، مما ينتج أدنى جودة بين هذه الخيارات. |
| InterpolationModeHighQualityBilinear | `6` | يحدد الاستيفاء الثنائي مع الترشيح المسبق. |
| InterpolationModeHighQualityBicubic | `7` | يحدد الاستيفاء البيكوبيكي مع الترشيح المسبق، والذي ينتج أعلى جودة بين هذه الخيارات. |

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


