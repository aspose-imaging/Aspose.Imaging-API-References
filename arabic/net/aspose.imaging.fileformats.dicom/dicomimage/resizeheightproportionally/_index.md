---
title: ResizeHeightProportionally
second_title: Aspose.Imaging لمرجع NET API
description: يغير حجم العرض بشكل متناسب .
type: docs
weight: 270
url: /ar/net/aspose.imaging.fileformats.dicom/dicomimage/resizeheightproportionally/
---
## DicomImage.ResizeHeightProportionally method

يغير حجم العرض بشكل متناسب .

```csharp
public override void ResizeHeightProportionally(int newHeight, ResizeType resizeType)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| newHeight | Int32 | الارتفاع الجديد. |
| resizeType | ResizeType | نوع تغيير الحجم. |

### أمثلة

يقوم هذا المثال بتحميل صورة DICOM وتغيير حجمها بشكل متناسب باستخدام طرق تغيير الحجم المختلفة. يتم تحديد الارتفاع فقط ، ويتم حساب العرض تلقائيًا.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // قم بالزيادة بمقدار مرتين باستخدام إعادة تشكيل أقرب الجوار.
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
        
    // حفظ في PNG مع الخيارات الافتراضية.
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // تصغير بمقدار مرتين باستخدام إعادة تشكيل أقرب الجوار.
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // حفظ في PNG مع الخيارات الافتراضية.
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // قم بالارتقاء بمقدار مرتين باستخدام إعادة التشكيل Bilinear.
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);
        
    // حفظ في PNG مع الخيارات الافتراضية.
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // تصغير بمقدار مرتين باستخدام إعادة التشكيل Bilinear.
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // حفظ في PNG مع الخيارات الافتراضية.
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### أنظر أيضا

* enum [ResizeType](../../../aspose.imaging/resizetype)
* class [DicomImage](../../dicomimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Dicom](../../dicomimage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
