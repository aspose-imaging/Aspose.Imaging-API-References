---
title: "فئة FontSettings"
second_title: "Aspose.Imaging for .NET API Reference"
description: "فئة Aspose.Imaging.FontSettings. إعدادات الخط لمُعالج صيغ المتجهات العامة للتصوير."
type: docs
weight: 9520
url: /ar/net/aspose.imaging/fontsettings/
---
## FontSettings class

إعدادات خط عارض صيغ المتجهات العامة للتصوير.

```csharp
public static class FontSettings
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [DefaultFontName](../../aspose.imaging/fontsettings/defaultfontname/) { get; set; } | يحصل أو يعيّن الاسم الافتراضي للخط. |
| static [GetSystemAlternativeFont](../../aspose.imaging/fontsettings/getsystemalternativefont/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [get alternative font]. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [GetDefaultFontsFolders](../../aspose.imaging/fontsettings/getdefaultfontsfolders/)() | يحصل على مجلدات الخطوط الافتراضية. |
| static [GetFontsFolders](../../aspose.imaging/fontsettings/getfontsfolders/)() | يحصل على نسخة من المصفوفة التي تحتوي على قائمة المجلدات التي يبحث فيها Aspose.Words عن خطوط TrueType. |
| static [Reset](../../aspose.imaging/fontsettings/reset/)() | يعيد تعيين مجلد الخطوط والاسم الافتراضي للخط إلى الإعداد الافتراضي للنظام. |
| static [SetFontsFolder](../../aspose.imaging/fontsettings/setfontsfolder/)(string) | هذا اختصار إلى [`SetFontsFolders`](./setfontsfolders/) لتعيين مجلد خطوط واحد فقط. لا يتم إجراء أي فحوصات على مجلد الخطوط. |
| static [SetFontsFolders](../../aspose.imaging/fontsettings/setfontsfolders/)(string[], bool) | يضبط المجلدات التي يتم تحميل خطوط TrueType منها ويُمسح جميع الخطوط المحملة. لا يتم إجراء أي فحص على مجلدات الخطوط. |
| static [UpdateFonts](../../aspose.imaging/fontsettings/updatefonts/)() | يقوم بتحديث ذاكرة التخزين المؤقت للخطوط لملفات PSD التي تحتوي على طبقات نصية. يضمن هذه الطريقة أن الخطوط من المجلد fontsFolder باستخدام الطريقة FontSettings.SetFontsFolder(fontsFolder) أو بعد إعادة ضبط الخطوط باستخدام FontSettings.Reset() ستؤخذ في الاعتبار عند معالجة ملفات PSD. يرجى استخدام هذه الطريقة في كل مرة يتم فيها استدعاء FontSettings.SetFontsFolder(fontsFolder) أو FontSettings.Reset() لصور PSD. دون استدعاء هذه الطريقة لا توجد ضمانات لتحديث الخطوط. |

### انظر أيضًا

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


