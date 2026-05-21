---
title: "الفئة OtgRasterizationOptions"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.ImageOptions.OtgRasterizationOptions الفئة. خيارات التحويل إلى نقطية Otg"
type: docs
weight: 10470
url: /ar/net/aspose.imaging.imageoptions/otgrasterizationoptions/
---
## OtgRasterizationOptions class

خيارات تمثيل Otg

```csharp
public class OtgRasterizationOptions : OdRasterizationOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [OtgRasterizationOptions](otgrasterizationoptions/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.imageoptions/vectorrasterizationoptions/backgroundcolor/) { get; set; } | يحصل أو يعيّن لون الخلفية. |
| [BorderX](../../aspose.imaging.imageoptions/vectorrasterizationoptions/borderx/) { get; set; } | يحصل أو يعيّن الحد X. |
| [BorderY](../../aspose.imaging.imageoptions/vectorrasterizationoptions/bordery/) { get; set; } | الحصول أو تعيين الحد Y. |
| [CenterDrawing](../../aspose.imaging.imageoptions/vectorrasterizationoptions/centerdrawing/) { get; set; } | الحصول أو تعيين قيمة تشير إلى ما إذا كان الرسم مركزيًا. |
| [DrawColor](../../aspose.imaging.imageoptions/vectorrasterizationoptions/drawcolor/) { get; set; } | الحصول أو تعيين لون المقدمة. |
| [PageHeight](../../aspose.imaging.imageoptions/vectorrasterizationoptions/pageheight/) { get; set; } | الحصول أو تعيين ارتفاع الصفحة. إذا كانت القيمة 0، سيتم الحفاظ على نسبة أبعاد الصورة الأصلية. |
| [PageSize](../../aspose.imaging.imageoptions/vectorrasterizationoptions/pagesize/) { get; set; } | الحصول أو تعيين حجم الصفحة. إذا كان أحد أبعاد [`SizeF`](../../aspose.imaging/sizef/) هو 0، سيتم الحفاظ على نسبة أبعاد الصورة الأصلية. |
| [PageWidth](../../aspose.imaging.imageoptions/vectorrasterizationoptions/pagewidth/) { get; set; } | الحصول أو تعيين عرض الصفحة. إذا كانت القيمة 0، سيتم الحفاظ على نسبة أبعاد الصورة الأصلية. |
| [Positioning](../../aspose.imaging.imageoptions/vectorrasterizationoptions/positioning/) { get; set; } | الحصول أو تعيين التموضع. |
| [ReplaceTextMapping](../../aspose.imaging.imageoptions/vectorrasterizationoptions/replacetextmapping/) { get; set; } | الحصول أو تعيين خريطة استبدال النص. |
| [SmoothingMode](../../aspose.imaging.imageoptions/vectorrasterizationoptions/smoothingmode/) { get; set; } | يحصل أو يعيّن وضع التنعيم. |
| [TextRenderingHint](../../aspose.imaging.imageoptions/vectorrasterizationoptions/textrenderinghint/) { get; set; } | يحصل أو يعيّن تلميح عرض النص. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Clone](../../aspose.imaging.imageoptions/vectorrasterizationoptions/clone/)() | ينشئ كائنًا جديدًا هو نسخة سطحية من المثيل الحالي. |
| virtual [CopyTo](../../aspose.imaging.imageoptions/vectorrasterizationoptions/copyto/)(VectorRasterizationOptions) | ينسخ إلى. |

## أمثلة

المقتطف البرمجي التالي يوضح كيفية تحويل صورة OTG إلى PDF وصيغ صور أخرى.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3567\\";
string inputFilePath = dir + "VariousObjectsMultiPage.otg";
Aspose.Imaging.ImageOptionsBase[] options = { new Aspose.Imaging.ImageOptions.PngOptions(), new Aspose.Imaging.ImageOptions.PdfOptions() };
foreach (Aspose.Imaging.ImageOptionsBase saveOptions in options)
{
    string extension = saveOptions is Aspose.Imaging.ImageOptions.PngOptions ? ".png" : ".pdf";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
    {
        Aspose.Imaging.ImageOptions.OtgRasterizationOptions otgRasterizationOptions = new Aspose.Imaging.ImageOptions.OtgRasterizationOptions();
        otgRasterizationOptions.PageSize = image.Size;
        saveOptions.VectorRasterizationOptions = otgRasterizationOptions;

        image.Save(inputFilePath + extension, saveOptions);
    }
}
```

### انظر أيضًا

* class [OdRasterizationOptions](../odrasterizationoptions/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


