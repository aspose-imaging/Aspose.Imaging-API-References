---
title: "عدد EmfPlusLineCapType"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusLineCapType تعداد. يحدد تعداد LineCapType أنواع أغطية الخط التي تُستخدم في نهايات الخطوط المرسومة بأقلام الرسومات."
type: docs
weight: 5010
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/
---
## EmfPlusLineCapType enumeration

تحدد تعداد LineCapType أنواع نهايات الخط التي تُستخدم في نهايات الخطوط المرسومة بأقلام الرسومات.

```csharp
public enum EmfPlusLineCapType
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| LineCapTypeFlat | `0` | يحدد غطاء خط مربع الشكل. يجب أن تكون نهاية الخط هي النقطة الأخيرة في الخط. |
| LineCapTypeSquare | `1` | يحدد غطاء خط مربع. يجب أن يكون مركز المربع موجودًا عند النقطة الأخيرة في الخط. عرض المربع هو عرض الخط. |
| LineCapTypeRound | `2` | يحدد غطاء خط دائري. يجب أن يكون مركز الدائرة موجودًا عند النقطة الأخيرة في الخط. قطر الدائرة هو عرض الخط. |
| LineCapTypeTriangle | `3` | يحدد غطاء خط مثلثي. يجب أن يكون قاعدة المثلث موجودة عند النقطة الأخيرة في الخط. قاعدة المثلث هي عرض الخط. |
| LineCapTypeNoAnchor | `16` | يحدد أن نهاية الخط غير مثبتة. |
| LineCapTypeSquareAnchor | `17` | يحدد أن نهاية الخط مثبتة بغطاء خط مربع. يجب أن يكون مركز المربع موجودًا عند النقطة الأخيرة في الخط. ارتفاع وعرض المربع هو عرض الخط. |
| LineCapTypeRoundAnchor | `18` | يحدد أن نهاية الخط مثبتة بغطاء خط دائري. يجب أن يكون مركز الدائرة موجودًا عند النقطة الأخيرة في الخط. يجب أن تكون الدائرة أوسع من الخط. |
| LineCapTypeDiamondAnchor | `19` | يحدد أن نهاية الخط مثبتة بغطاء خط على شكل ماسة، وهو مربع مدور بزاوية 45 درجة. يجب أن يكون مركز الماسة موجودًا عند النقطة الأخيرة في الخط. يجب أن تكون الماسة أوسع من الخط. |
| LineCapTypeArrowAnchor | `20` | يحدد أن نهاية الخط مرتبطة بشكل رأس سهم. يجب أن تكون نقطة رأس السهم موجودة في النقطة الأخيرة في الخط. يجب أن يكون رأس السهم أوسع من الخط. |
| LineCapTypeAnchorMask | `240` | قناع يُستخدم للتحقق مما إذا كان غطاء الخط هو غطاء مرساة. |
| LineCapTypeCustom | `255` | يحدد قمة خط مخصصة. |

## ملاحظات

يتم تحديد أغطية خطوط الرسومات بواسطة كائنات [`EmfPlusPen`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspen/) (القسم 2.2.1.7).

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


