---
title: "DicomImage.ResizeWidthProportionally"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة DicomImage. ضبط عرض الصورة مع الحفاظ على نسبة العرض إلى الارتفاع باستخدام هذه الطريقة المريحة. مثالية للمطورين الذين يسعون لتغيير حجم الصور بشكل متناسب لضمان نتائج متسقة وجذابة بصريًا عبر بيئات العرض المختلفة."
type: docs
weight: 270
url: /ar/net/aspose.imaging.fileformats.dicom/dicomimage/resizewidthproportionally/
---
## DicomImage.ResizeWidthProportionally method

قم بضبط عرض الصورة مع الحفاظ على نسبة العرض إلى الارتفاع باستخدام هذه الطريقة المريحة. مثالي للمطورين الذين يرغبون في تغيير حجم الصور بشكل متناسب، مع ضمان نتائج متسقة وجذابة بصريًا عبر بيئات العرض المختلفة.

```csharp
public override void ResizeWidthProportionally(int newWidth, ResizeType resizeType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد. |
| resizeType | ResizeType | نوع تغيير الحجم. |

## أمثلة

هذا المثال يحمل صورة DICOM ويعيد تحجيمها بشكل متناسب باستخدام طرق تحجيم مختلفة. يتم تحديد العرض فقط، ويتم حساب الارتفاع تلقائيًا.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.ResizeWidthProportionally(image.Width* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // حفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.ResizeWidthProportionally(image.Width / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // حفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.ResizeWidthProportionally(image.Width* 2, Aspose.Imaging.ResizeType.BilinearResample);

    // حفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.ResizeWidthProportionally(image.Width / 2, Aspose.Imaging.ResizeType.BilinearResample);                

    // حفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


