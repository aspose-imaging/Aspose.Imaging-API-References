---
title: "EmfPlusInterpolationMode تعداد"
type: docs
weight: 200
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusinterpolationmode/
---

تحدد تعداد InterpolationMode طرق تنفيذ التحجيم، بما في ذلك التمدد والتقليص.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusInterpolationMode

## **Members**
| **اسم العضو** | **الوصف** |
| :- | :- |
| INTERPOLATION_MODE_BICUBIC | يحدد الاستيفاء الثلاثي المكعب، الذي يستخدم أقرب مجموعة 4×4 من البكسلات المعروفة المحيطة بالبكسل المستنتج. المتوسط المرجح لهذه القيم الـ 16 للبكسلات المعروفة يحدد القيمة التي تُعطى للبكسل المستنتج. نظرًا لأن البكسلات المعروفة قد تكون على مسافات مختلفة من البكسل المستنتج، تُعطى البكسلات الأقرب وزنًا أعلى في الحساب. النتيجة تبدو أكثر سلاسة مقارنةً بـ InterpolationModeBilinear. |
| INTERPOLATION_MODE_BILINEAR | يحدد الاستيفاء الثنائي الخطى، الذي يستخدم أقرب مجموعة 2×2 من البكسلات المعروفة المحيطة بالبكسل المستنتج. المتوسط المرجح لهذه القيم الـ 4 للبكسلات المعروفة يحدد القيمة التي تُعطى للبكسل المستنتج. النتيجة تبدو أكثر سلاسة مقارنةً بـ InterpolationModeNearestNeighbor. |
| INTERPOLATION_MODE_DEFAULT | يحدد وضع الاستيفاء الافتراضي، والذي يُعرّف على أنه InterpolationModeBilinear. |
| INTERPOLATION_MODE_HIGH_QUALITY | يحدد وضع استيفاء عالي الجودة، والذي يُعرّف بأنه InterpolationModeHighQualityBicubic. |
| INTERPOLATION_MODE_HIGH_QUALITY_BICUBIC | يحدد استيفاء بيكوبيك مع الترشيح المسبق، والذي ينتج أعلى نتيجة جودة بين هذه الخيارات. |
| INTERPOLATION_MODE_HIGH_QUALITY_BILINEAR | يحدد استيفاء ثنائي الخطوط مع الترشيح المسبق. |
| INTERPOLATION_MODE_LOW_QUALITY | يحدد وضع استيفاء منخفض الجودة، والذي يُعرّف بأنه InterpolationModeNearestNeighbor. |
| INTERPOLATION_MODE_NEAREST_NEIGHBOR | يحدد استيفاء أقرب جار، والذي يستخدم فقط قيمة البكسل الأقرب إلى البكسل المستوفى. هذا الوضع يكرر أو يزيل البكسلات ببساطة، مما ينتج أدنى نتيجة جودة بين هذه الخيارات. |
