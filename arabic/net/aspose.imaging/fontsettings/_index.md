---
title: FontSettings
second_title: Aspose.Imaging لمرجع NET API
description: إعدادات خط العارض لتنسيقات التصوير العامة.
type: docs
weight: 9340
url: /ar/net/aspose.imaging/fontsettings/
---
## FontSettings class

إعدادات خط العارض لتنسيقات التصوير العامة.

```csharp
public static class FontSettings
```

## الخصائص

| اسم | وصف |
| --- | --- |
| static [DefaultFontName](../../aspose.imaging/fontsettings/defaultfontname) { get; set; } | الحصول على الاسم الافتراضي للخط أو تعيينه. |
| static [GetSystemAlternativeFont](../../aspose.imaging/fontsettings/getsystemalternativefont) { get; set; } | الحصول على أو تعيين قيمة تشير إلى [الحصول على خط بديل] . |

## طُرق

| اسم | وصف |
| --- | --- |
| static [GetDefaultFontsFolders](../../aspose.imaging/fontsettings/getdefaultfontsfolders)() | يحصل على مجلدات الخطوط الافتراضية. |
| static [GetFontsFolders](../../aspose.imaging/fontsettings/getfontsfolders)() | يحصل على نسخة من المصفوفة التي تحتوي على قائمة المجلدات حيث يبحث Aspose.Words عن خطوط TrueType . |
| static [Reset](../../aspose.imaging/fontsettings/reset)() | يعيد تعيين مجلد الخطوط واسم الخط الافتراضي إلى النظام الافتراضي. |
| static [SetFontsFolder](../../aspose.imaging/fontsettings/setfontsfolder)(string) | هذا اختصار لـ[`SetFontsFolders`](./setfontsfolders) لتعيين دليل خطوط واحد فقط. لم يتم إجراء عمليات تدقيق على مجلد الخطوط. |
| static [SetFontsFolders](../../aspose.imaging/fontsettings/setfontsfolders)(string[], bool) | يضبط المجلدات التي يتم تحميل خطوط TrueType منها ويمسح جميع الخطوط المحملة. |
| static [UpdateFonts](../../aspose.imaging/fontsettings/updatefonts)() | يقوم بتحديث ذاكرة التخزين المؤقت للخطوط لملفات PSD التي تحتوي على طبقات نصية. تضمن هذه الطريقة أن الخطوط من مجلد الخطوط التي تستخدم طريقة FontSettings.SetFontsFolder (FontSettings) أو بعد إعادة تعيين الخطوط باستخدام FontSettings.Reset () ستؤخذ في الاعتبار عند معالجة ملفات PSD. يرجى استخدام هذه الطريقة في كل مرة عند استدعاء FontSettings.SetFontsFolder (FontSettings) أو FontSettings.Reset () لصور PSD. بدون استدعاء هذه الطريقة ، لا يوجد ضمان بأنه سيتم تحديث الخطوط. |

### أنظر أيضا

* مساحة الاسم [Aspose.Imaging](../../aspose.imaging)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->