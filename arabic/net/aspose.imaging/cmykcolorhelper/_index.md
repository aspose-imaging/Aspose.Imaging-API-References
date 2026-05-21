---
title: "فئة CmykColorHelper"
second_title: "Aspose.Imaging for .NET API Reference"
description: "فئة Aspose.Imaging.CmykColorHelper. طرق مساعدة للعمل مع لون CMYK المقدم كقيمة عدد صحيح موقعة 32 بت. توفر واجهة برمجة تطبيقات مشابهة للهيكل CmykColor. هي أخف وزنًا لأن لون CMYK يُقدم كـ Int32 فقط بدلاً من هيكل يحتوي على حقول داخلية. يرجى تفضيل استخدام الطرق الساكنة لهذه الفئة عندما يكون ذلك ممكنًا بدلاً من الهيكل CmykColor المهمل."
type: docs
weight: 290
url: /ar/net/aspose.imaging/cmykcolorhelper/
---
## CmykColorHelper class

طرق مساعدة للعمل مع لون CMYK المقدم كقيمة عدد صحيح موقعة 32-بت. توفر واجهة برمجة تطبيقات مشابهة للهيكل [`CmykColor`](../cmykcolor/). إنها أخف وزنًا لأن لون CMYK يُقدم كـ Int32 فقط بدلاً من هيكل يحتوي على حقول داخلية. يرجى تفضيل استخدام الطرق الساكنة لهذه الفئة عندما يكون ذلك ممكنًا بدلاً من الهيكل المهمل [`CmykColor`](../cmykcolor/).

```csharp
public static class CmykColorHelper
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromComponents](../../aspose.imaging/cmykcolorhelper/fromcomponents/)(int, int, int, int) | ينشئ CMYK من قيم سيان، ماجنتا، أصفر وأسود 32-بت. |
| static [GetC](../../aspose.imaging/cmykcolorhelper/getc/)(int) | يحصل على قيمة المكوّن السيان. |
| static [GetK](../../aspose.imaging/cmykcolorhelper/getk/)(int) | يحصل على قيمة المكوّن الأسود. |
| static [GetM](../../aspose.imaging/cmykcolorhelper/getm/)(int) | يحصل على قيمة المكوّن الماجنتا. |
| static [GetY](../../aspose.imaging/cmykcolorhelper/gety/)(int) | يحصل على قيمة المكوّن الأصفر. |
| static [ToArgb](../../aspose.imaging/cmykcolorhelper/toargb/#toargb)(int) | التحويل من لون CMYK إلى لون ARGB. |
| static [ToArgb](../../aspose.imaging/cmykcolorhelper/toargb/#toargb_1)(int[]) | التحويل من ألوان CMYK إلى ألوان ARGB. |
| static [ToArgb32](../../aspose.imaging/cmykcolorhelper/toargb32/)(int[]) | التحويل من ألوان CMYK إلى ألوان ARGB. |
| static [ToArgbIcc](../../aspose.imaging/cmykcolorhelper/toargbicc/#toargbicc)(int) | التحويل من لون CMYK إلى ARGB Color باستخدام تحويل Icc مع ملفات تعريف افتراضية. |
| static [ToArgbIcc](../../aspose.imaging/cmykcolorhelper/toargbicc/#toargbicc_2)(int[]) | التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات تعريف افتراضية. |
| static [ToArgbIcc](../../aspose.imaging/cmykcolorhelper/toargbicc/#toargbicc_1)(int, Stream, Stream) | التحويل من لون CMYK إلى ARGB Color باستخدام تحويل Icc مع ملف تعريف مخصص. |
| static [ToArgbIcc](../../aspose.imaging/cmykcolorhelper/toargbicc/#toargbicc_3)(int[], Stream, Stream) | التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| static [ToCmyk](../../aspose.imaging/cmykcolorhelper/tocmyk/#tocmyk)(Color) | التحويل من لون ARGB إلى لون CMYK. |
| static [ToCmyk](../../aspose.imaging/cmykcolorhelper/tocmyk/#tocmyk_2)(Color[]) | التحويل من ألوان ARGB إلى ألوان CMYK. |
| static [ToCmyk](../../aspose.imaging/cmykcolorhelper/tocmyk/#tocmyk_1)(int) | التحويل من لون ARGB إلى لون CMYK. |
| static [ToCmyk](../../aspose.imaging/cmykcolorhelper/tocmyk/#tocmyk_3)(int[]) | التحويل من ألوان ARGB إلى ألوان CMYK. |
| static [ToCmykaBytes](../../aspose.imaging/cmykcolorhelper/tocmykabytes/)(int[], int, int) | يحوّل ARGB إلى CMYKA (مع الشفافية). |
| static [ToCmykaIccBytes](../../aspose.imaging/cmykcolorhelper/tocmykaiccbytes/)(int[], int, int, Stream, Stream) | يحوّل RGB إلى CMYKA (مع ألفا) باستخدام ملفات تعريف ICC مخصصة. |
| static [ToCmykBytes](../../aspose.imaging/cmykcolorhelper/tocmykbytes/)(int[], int, int) | يحوّل ARGB إلى CMYK. |
| static [ToCmykIcc](../../aspose.imaging/cmykcolorhelper/tocmykicc/#tocmykicc)(Color) | التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات تعريف افتراضية. |
| static [ToCmykIcc](../../aspose.imaging/cmykcolorhelper/tocmykicc/#tocmykicc_4)(Color[]) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف افتراضية. |
| static [ToCmykIcc](../../aspose.imaging/cmykcolorhelper/tocmykicc/#tocmykicc_2)(int) | التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات تعريف افتراضية. |
| static [ToCmykIcc](../../aspose.imaging/cmykcolorhelper/tocmykicc/#tocmykicc_6)(int[]) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف افتراضية. |
| static [ToCmykIcc](../../aspose.imaging/cmykcolorhelper/tocmykicc/#tocmykicc_1)(Color, Stream, Stream) | التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| static [ToCmykIcc](../../aspose.imaging/cmykcolorhelper/tocmykicc/#tocmykicc_5)(Color[], Stream, Stream) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| static [ToCmykIcc](../../aspose.imaging/cmykcolorhelper/tocmykicc/#tocmykicc_3)(int, Stream, Stream) | التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| static [ToCmykIcc](../../aspose.imaging/cmykcolorhelper/tocmykicc/#tocmykicc_7)(int[], Stream, Stream) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| static [ToCmykIccBytes](../../aspose.imaging/cmykcolorhelper/tocmykiccbytes/)(int[], int, int, Stream, Stream) | يحوّل RGB إلى CMYK باستخدام ملفات تعريف ICC مخصصة. |
| static [ToPsdCmykIcc](../../aspose.imaging/cmykcolorhelper/topsdcmykicc/#topsdcmykicc)(int) | التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات تعريف افتراضية. يستخدم تنسيق PSD CMYK بترتيب بايت KCMY مع قيم قنوات مقلوبة. |
| static [ToPsdCmykIcc](../../aspose.imaging/cmykcolorhelper/topsdcmykicc/#topsdcmykicc_2)(int[]) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف افتراضية. يستخدم تنسيق PSD CMYK بترتيب بايت KCMY مع قيم قنوات مقلوبة. |
| static [ToPsdCmykIcc](../../aspose.imaging/cmykcolorhelper/topsdcmykicc/#topsdcmykicc_1)(int, Stream, Stream) | التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| static [ToPsdCmykIcc](../../aspose.imaging/cmykcolorhelper/topsdcmykicc/#topsdcmykicc_3)(int[], Stream, Stream) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة. يستخدم تنسيق PSD CMYK بترتيب بايت KCMY مع قيم قنوات مقلوبة. |

### انظر أيضًا

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


