---
title: EmfPlusInterpolationMode
second_title: Aspose.Imaging لمرجع NET API
description: يحدد تعداد وضع الاستيفاء طرق إجراء القياس  بما في ذلك التمدد والانكماش .
type: docs
weight: 4870
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusinterpolationmode/
---
## EmfPlusInterpolationMode enumeration

يحدد تعداد وضع الاستيفاء طرق إجراء القياس ، بما في ذلك التمدد والانكماش .

```csharp
public enum EmfPlusInterpolationMode : byte
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| InterpolationModeDefault | `0` | يحدد وضع الاستيفاء الافتراضي ، والذي يتم تعريفه على أنه InterpolationModeBilinear. |
| InterpolationModeLowQuality | `1` | يحدد وضع الاستيفاء منخفض الجودة ، والذي يتم تعريفه على أنه InterpolationModeNearestNeighbor. |
| InterpolationModeHighQuality | `2` | تحديد وضع الاستيفاء عالي الجودة ، والذي يتم تعريفه على أنه InterpolationModeHighQualityBicubic. |
| InterpolationModeBilinear | `3` | يحدد الاستيفاء الثنائي الخطي ، والذي يستخدم أقرب 2 × 2 من وحدات البكسل المعروفة المحيطة بالبكسل المحرف. يحدد المتوسط المرجح لقيم البكسل الأربعة المعروفة القيمة التي يجب تعيينها للبكسل المحرف. والنتيجة هي مظهر أكثر سلاسة من InterpolationModeNearestNeighbor. |
| InterpolationModeBicubic | `4` | يحدد الاستيفاء التكعيبي bicubic interpolation ، والذي يستخدم أقرب جوار 4x4 من وحدات البكسل المعروفة المحيطة بالبكسل المحرف. يحدد المتوسط المرجح لقيم البكسل الـ 16 المعروفة هذه القيمة التي يجب تعيينها للبكسل المحرف. نظرًا لأنه من المحتمل أن تكون وحدات البكسل المعروفة على مسافات متفاوتة من البكسل المحرف ، يتم إعطاء وحدات البكسل الأقرب وزنًا أعلى في الحساب. والنتيجة هي مظهر أكثر سلاسة من InterpolationModeBilinear. |
| InterpolationModeNearestNeighbor | `5` | يحدد الاستيفاء الأقرب للجوار ، والذي يستخدم فقط قيمة البكسل الأقرب إلى البكسل المحرف. يقوم هذا الوضع ببساطة بتكرار وحدات البكسل أو إزالتها ، مما ينتج عنه النتيجة الأقل جودة من بين هذه الخيارات. |
| InterpolationModeHighQualityBilinear | `6` | تحديد الاستيفاء الثنائي مع التصفية المسبقة. |
| InterpolationModeHighQualityBicubic | `7` | تحديد الاستيفاء التكعيبي مع التصفية المسبقة ، والتي تنتج أعلى جودة من بين هذه الخيارات. |

### أنظر أيضا

* مساحة الاسم [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->