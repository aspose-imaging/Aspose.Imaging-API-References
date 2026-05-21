---
title: "الفئة EmfPlusCustomLineCapData"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusCustomLineCapData. يحدد كائن EmfPlusCustomLineCapData البيانات الافتراضية لرأس خط مخصص."
type: docs
weight: 5510
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/
---
## EmfPlusCustomLineCapData class

كائن EmfPlusCustomLineCapData يحدد البيانات الافتراضية لقبعة خط مخصصة.

```csharp
public sealed class EmfPlusCustomLineCapData : EmfPlusCustomBaseLineCap
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusCustomLineCapData](emfpluscustomlinecapdata/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BaseCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/basecap/) { get; set; } | الحصول أو تعيين عدد صحيح غير موقع 32‑بت يحدد القيمة من تعداد LineCap (القسم 2.1.1.18) الذي يُبنى عليه رأس الخط المخصص. |
| [BaseInset](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/baseinset/) { get; set; } | الحصول أو تعيين قيمة عشرية 32‑بت تحدد المسافة بين بداية رأس الخط ونهاية الخط. |
| [CustomLineCapDataFlags](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/customlinecapdataflags/) { get; set; } | الحصول أو تعيين عدد صحيح غير موقع 32‑بت يحدد البيانات في الحقل OptionalData. |
| [FillHotSpot](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/fillhotspot/) { get; set; } | الحصول أو تعيين كائن EmfPlusPointF غير مستخدم حاليًا. يجب تعيينه إلى {0.0, 0.0}. |
| [OptionalData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/optionaldata/) { get; set; } | الحصول أو تعيين كائن EmfPlusCustomLineCapOptionalData اختياري (القسم 2.2.2.14) يحدد بيانات إضافية لرأس الخط الرسومي المخصص. المحتويات المحددة لهذا الحقل تُحدد بقيمة الحقل CustomLineCapDataFlags. |
| [StrokeEndCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/strokeendcap/) { get; set; } | الحصول أو تعيين عدد صحيح غير موقع 32‑بت يحدد القيمة في تعداد LineCap التي تشير إلى رأس الخط الذي سيُستخدم في نهاية الخط المراد رسمه. |
| [StrokeHotSpot](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/strokehotspot/) { get; set; } | الحصول أو تعيين كائن EmfPlusPointF غير مستخدم حاليًا. يجب تعيينه إلى {0.0, 0.0}. |
| [StrokeJoin](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/strokejoin/) { get; set; } | الحصول أو تعيين عدد صحيح غير موقع 32‑بت يحدد القيمة في تعداد LineJoin (القسم 2.1.1.19)، الذي يحدد طريقة ربط خطين يُرسمان بالقلم نفسه وتلتقي نهايتهما. عند تقاطع نهايتي الخطين، يجعل ربط الخط الاتصال يبدو أكثر استمرارية. |
| [StrokeMiterLimit](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/strokemiterlimit/) { get; set; } | الحصول أو تعيين قيمة عشرية 32‑بت تحتوي على حد سمك الربط عند زاوية مِتَر عن طريق ضبط النسبة القصوى المسموح بها لطول المِتَر إلى عرض الخط. |
| [StrokeStartCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/strokestartcap/) { get; set; } | الحصول أو تعيين عدد صحيح غير موقع 32‑بت يحدد القيمة في تعداد LineCap التي تشير إلى رأس الخط المستخدم في بداية الخط المراد رسمه. |
| [WidthScale](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/widthscale/) { get; set; } | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقدار تعديل مقياس غطاء الخط المخصص بالنسبة إلى عرض كائن EmfPlusPen (القسم 2.2.1.7) المستخدم لرسم الخطوط. |

### انظر أيضًا

* class [EmfPlusCustomBaseLineCap](../emfpluscustombaselinecap/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


