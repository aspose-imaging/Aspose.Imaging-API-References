---
title: "DicomImage.Dither"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة DicomImage. حسّن الصورة الحالية بتطبيق تأثيرات dithering باستخدام هذه الطريقة السهلة. مثالي للمطورين الذين يرغبون في إضافة نسيج وعمق للصور لتحسين جودتها البصرية وجاذبيتها العامة"
type: docs
weight: 190
url: /ar/net/aspose.imaging.fileformats.dicom/dicomimage/dither/
---
## DicomImage.Dither method

قم بتحسين الصورة الحالية بتطبيق تأثيرات التمويه باستخدام هذه الطريقة البسيطة. مثالي للمطورين الذين يهدفون إلى إضافة نسيج وعمق للصور، مما يحسن جودتها البصرية وجاذبيتها العامة.

```csharp
public override void Dither(DitheringMethod ditheringMethod, int bitsCount, 
    IColorPalette customPalette)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| ditheringMethod | DitheringMethod | طريقة dithering. |
| bitsCount | Int32 | عدد البتات النهائي للتمويه. |
| customPalette | IColorPalette | لوحة الألوان المخصصة للتمويه. |

## أمثلة

المثال التالي يقوم بتحميل صورة DICOM ويجري تمويه العتبة وتمويه فلويد باستخدام أعماق لوحة ألوان مختلفة.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // قم بتمويه العتبة باستخدام لوحة ألوان 4-بت تحتوي على 16 لونًا.
    // كلما زاد عدد البتات المحددة كلما ارتفت الجودة وحجم الصورة الناتجة.
    // لاحظ أن لوحات الألوان بدقة 1-بت، 4-بت و8-بت فقط هي المدعومة حاليًا.
    dicomImage.Dither(Aspose.Imaging.DitheringMethod.ThresholdDithering, 4, null);

    dicomImage.Save(dir + "sample.ThresholdDithering4.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // قم بتمويه فلويد باستخدام لوحة ألوان 1-بت تحتوي فقط على لونين - الأسود والأبيض.
    // كلما زاد عدد البتات المحددة كلما ارتفت الجودة وحجم الصورة الناتجة.
    // لاحظ أن لوحات الألوان بدقة 1-بت، 4-بت و8-بت فقط هي المدعومة حاليًا.
    dicomImage.Dither(Aspose.Imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    dicomImage.Save(dir + "sample.FloydSteinbergDithering1.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* enum [DitheringMethod](../../../aspose.imaging/ditheringmethod/)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


