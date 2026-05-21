---
title: "الفئة OdgRasterizationOptions"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.ImageOptions.OdgRasterizationOptions الفئة. خيارات التحويل إلى نقطية Odg"
type: docs
weight: 10460
url: /ar/net/aspose.imaging.imageoptions/odgrasterizationoptions/
---
## OdgRasterizationOptions class

خيارات تمثيل Odg

```csharp
public class OdgRasterizationOptions : OdRasterizationOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [OdgRasterizationOptions](odgrasterizationoptions/)() | المنشئ الافتراضي. |

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

المثال التالي يوضح كيفية تصدير صورة FODG (قالب ODF XML مسطح) إلى صيغة PDF.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3635";

string inputFileName = System.IO.Path.Combine(dir, "VariousObjectsMultiPage.fodg");
string outputFileName = inputFileName + ".pdf";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFileName))
{
    Aspose.Imaging.ImageOptions.OdgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.OdgRasterizationOptions();
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.White;
    rasterizationOptions.PageSize = image.Size;

    Aspose.Imaging.ImageOptions.PdfOptions saveOptions = new Aspose.Imaging.ImageOptions.PdfOptions();
    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    image.Save(outputFileName, saveOptions);
}
```

### انظر أيضًا

* class [OdRasterizationOptions](../odrasterizationoptions/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


