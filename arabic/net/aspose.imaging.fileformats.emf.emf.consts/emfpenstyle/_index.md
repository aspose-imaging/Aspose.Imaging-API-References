---
title: "Enum EmfPenStyle"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfPenStyle enum. يحدد تعداد PenStyle سمات الأقلام التي يمكن استخدامها في عمليات الرسومات. نمط القلم هو مزيج من نوع القلم، نمط الخط، رأس الخط، وتوصيل الخط."
type: docs
weight: 2870
url: /ar/net/aspose.imaging.fileformats.emf.emf.consts/emfpenstyle/
---
## EmfPenStyle enumeration

تعداد PenStyle يحدد سمات الأقلام التي يمكن استخدامها في عمليات الرسومات. نمط القلم هو مزيج من نوع القلم، نمط الخط، طرف الخط، واتصال الخط.

```csharp
[Flags]
public enum EmfPenStyle
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| PS_COSMETIC | `0` | نوع قلم يحدد خطًا بعرض وحدة منطقية واحدة ونمطًا بلون صلب. |
| PS_ENDCAP_ROUND | `0` | رأس خط يحدد نهايات مستديرة. |
| PS_JOIN_ROUND | `0` | توصيل خط يحدد وصلات مستديرة |
| PS_SOLID | `0` | نمط خط بلون صلب |
| PS_DASH | `1` | نمط خط متقطع |
| PS_DOT | `2` | نمط خط منقّط. |
| PS_DASHDOT | `3` | نمط خط يتكوّن من شرطات ونقاط متناوبة |
| PS_DASHDOTDOT | `4` | نمط خط يتكوّن من شرطات ونقط مزدوجة. |
| PS_NULL | `5` | نمط خط غير مرئي. |
| PS_INSIDEFRAME | `6` | نمط خط بلون صلب. عندما يتم تحديد هذا النمط في سجل رسم يأخذ مستطيلًا محيطًا، يتم تقليص أبعاد الشكل بحيث يتناسب تمامًا داخل المستطيل المحيط، مع مراعاة عرض القلم. |
| PS_USERSTYLE | `7` | نمط خط يُعرّف بواسطة مصفوفة تنسيق، تحدد أطوال الشرطات والفجوات في الخط |
| PS_ALTERNATE | `8` | نمط خط يتم فيه تعيين كل بكسل بديل. هذا النمط ينطبق فقط على نوع القلم PS_COSMETIC |
| PS_ENDCAP_SQUARE | `100` | غطاء خط يحدد نهايات مربعة. |
| PS_ENDCAP_FLAT | `200` | غطاء خط يحدد نهايات مسطحة. |
| PS_JOIN_BEVEL | `1000` | اتصال خط يحدد وصلات مائلة. |
| PS_JOIN_MITER | `2000` | اتصال خط يحدد وصلات مائلة عندما تكون أطوال الوصلات ضمن حد طول الميتر الحالي المحدد في سياق جهاز التشغيل. إذا تجاوزت أطوال الوصلات حد الميتر، يتم تحديد وصلات مائلة. |
| PS_GEOMETRIC | `10000` | نوع قلم يحدد خطًا بعرض يُقاس بوحدات منطقية ونمط يمكن أن يحتوي على أي من خصائص الفرشاة. |
| StyleMask | `F` | قناع النمط |
| EndCapMask | `F00` | قناع غطاء النهاية |
| JoinMask | `F000` | قناع الوصل |
| TypeMask | `F0000` | قناع النوع |

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)


