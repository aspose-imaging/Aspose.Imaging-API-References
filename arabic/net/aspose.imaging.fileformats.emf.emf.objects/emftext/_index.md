---
title: "الفئة EmfText"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfText class. يحتوي كائن EmrText على قيم لإخراج النص."
type: docs
weight: 3250
url: /ar/net/aspose.imaging.fileformats.emf.emf.objects/emftext/
---
## EmfText class

كائن EmrText يحتوي على قيم لإخراج النص.

```csharp
public sealed class EmfText : EmfObject
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfText](emftext/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Chars](../../aspose.imaging.fileformats.emf.emf.objects/emftext/chars/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد الأحرف في السلسلة |
| [DxBuffer](../../aspose.imaging.fileformats.emf.emf.objects/emftext/dxbuffer/) { get; set; } | يحصل أو يعيّن مخزن تباعد الأحرف الاختياري UndefinedSpace2 (متغيّر): عدد اختياري من البايتات غير المستخدمة. لا يُشترط أن يتبع حقل OutputDx مباشرةً الجزء السابق من هذا الهيكل. OutputDx (متغيّر): مصفوفة من الأعداد الصحيحة غير الموقعة 32‑بت تحدد تباعد الإخراج بين أصول خلايا الأحرف المتجاورة بوحدات منطقية. يتم تحديد موقع هذا الحقل بقيمة offDx بالبايتات من بداية هذا السجل. إذا تم تعريف التباعد، يحتوي هذا الحقل على نفس عدد القيم كعدد الأحرف في سلسلة الإخراج. إذا كان حقل Options لكائن EmrText يحتوي على علم ETO_PDY، فإن هذا المخزن يحتوي على ضعف عدد القيم مقارنةً بعدد الأحرف في سلسلة الإخراج، إزاحة أفقية وإزاحة رأسية لكل حرف، بهذا الترتيب. إذا تم تحديد ETO_RTLREADING، تُرتّب الأحرف من اليمين إلى اليسار بدلاً من اليسار إلى اليمين. لا تؤثر أي خيارات أخرى على تفسير هذا الحقل. |
| [GlyphIndexBuffer](../../aspose.imaging.fileformats.emf.emf.objects/emftext/glyphindexbuffer/) { get; set; } | يحصل أو يعيّن مخزن فهارس القوالب الاختياري. إذا كان للخيارات علم ETO_GLYPH_INDEX فإن رموز الأحرف في سلسلة النص المُخرجة هي في الواقع فهارس لقوالب الأحرف في خط TrueType (تعداد ExtTextOutOptions القسم 2.1.11). فهارس القوالب خاصة بالخط، لذا لعرض الأحرف الصحيحة عند التشغيل، يجب أن يكون الخط المستخدم متماثلًا تمامًا مع الخط المستخدم لإنشاء الفهارس. |
| [Options](../../aspose.imaging.fileformats.emf.emf.objects/emftext/options/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد طريقة استخدام المستطيل المحدد في حقل Rectangle. يمكن أن يكون هذا الحقل مزيجًا من أكثر من قيمة لتعداد ExtTextOutOptions (القسم 2.1.11). |
| [Rectangle](../../aspose.imaging.fileformats.emf.emf.objects/emftext/rectangle/) { get; set; } | يحصل أو يعيّن كائن WMF RectL اختياري ([MS-WMF] القسم 2.2.2.19) يحدد مستطيل قص و/أو تعتيم بوحدات منطقية. يُطبق هذا المستطيل على إخراج النص الذي ينفذه السجل الحاوي. |
| [Reference](../../aspose.imaging.fileformats.emf.emf.objects/emftext/reference/) { get; set; } | يحصل أو يعيّن كائن WMF PointL ([MS-WMF] القسم 2.2.2.15) يحدد إحداثيات نقطة المرجع المستخدمة لتحديد موضع السلسلة. تُعرّف نقطة المرجع بواسطة سجل EMR_SETTEXTALIGN الأخير (القسم 2.3.11.25). إذا لم يتم ضبط أي سجل من هذا النوع، يكون المحاذاة الافتراضية هي TA_LEFT,TA_TOP. |
| [StringBuffer](../../aspose.imaging.fileformats.emf.emf.objects/emftext/stringbuffer/) { get; set; } | يحصل أو يعيّن مخزن سلسلة الأحرف UndefinedSpace1 (متغيّر): عدد اختياري من البايتات غير المستخدمة. لا يُشترط أن يتبع حقل OutputString مباشرةً الجزء السابق من هذا الهيكل. OutputString (متغيّر): مصفوفة من الأحرف تحدد السلسلة المطلوب إخراجها. يتم تحديد موقع هذا الحقل بقيمة offString بالبايتات من بداية هذا السجل. يتم تحديد عدد الأحرف بقيمة Chars. |

### انظر أيضًا

* class [EmfObject](../emfobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


