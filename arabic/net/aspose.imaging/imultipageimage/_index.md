---
title: "واجهة IMultipageImage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.IMultipageImage واجهة. واجهة الصورة المتعددة الصفحات"
type: docs
weight: 9740
url: /ar/net/aspose.imaging/imultipageimage/
---
## IMultipageImage interface

واجهة الصورة متعددة الصفحات

```csharp
public interface IMultipageImage
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [PageCount](../../aspose.imaging/imultipageimage/pagecount/) { get; } | يحصل على عدد الصفحات. |
| [PageExportingAction](../../aspose.imaging/imultipageimage/pageexportingaction/) { get; set; } | يحصل أو يعيّن إجراء تصدير الصفحة. يرجى ملاحظة أن ضبط هذه الطريقة سيؤدي تلقائيًا إلى تحرير موارد الصفحة بعد تنفيذها. سيتم تنفيذها مباشرةً قبل حفظ كل صفحة. |
| [Pages](../../aspose.imaging/imultipageimage/pages/) { get; } | يحصل على الصفحات. |

## أمثلة

المثال التالي يوضح كيفية تصدير صورة متجه متعددة الصفحات إلى تنسيق آخر بطريقة عامة دون الإشارة إلى نوع صورة معين.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.tif");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // تصدير الصفحتين الأوليتين فقط
    Aspose.Imaging.IMultipageImage multipageImage = image as Aspose.Imaging.IMultipageImage;
    if (multipageImage != null && (multipageImage.Pages != null && multipageImage.PageCount > 2))
    {
        exportOptions.MultiPageOptions = new Aspose.Imaging.ImageOptions.MultiPageOptions(new Aspose.Imaging.IntRange(0, 2));
    }

    if (image is Aspose.Imaging.VectorImage)
    {
        exportOptions.VectorRasterizationOptions = (Aspose.Imaging.ImageOptions.VectorRasterizationOptions)image.GetDefaultOptions(new object[] { Aspose.Imaging.Color.White, image.Width, image.Height });
        exportOptions.VectorRasterizationOptions.TextRenderingHint = Aspose.Imaging.TextRenderingHint.SingleBitPerPixel;
        exportOptions.VectorRasterizationOptions.SmoothingMode = Aspose.Imaging.SmoothingMode.None;
    }

    image.Save(outputFilePath, exportOptions);
}
```

### انظر أيضًا

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


