---
title: "DicomImage.ResizeHeightProportionally"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة DicomImage. ضبط ارتفاع الصورة مع الحفاظ على نسبة أبعادها باستخدام هذه الطريقة سهلة الاستخدام. مثالية للمطورين الذين يرغبون في تغيير حجم الصور ديناميكيًا مع الحفاظ على نسبها لضمان عرض مثالي وسهولة الاستخدام في تطبيقاتهم."
type: docs
weight: 250
url: /ar/net/aspose.imaging.fileformats.dicom/dicomimage/resizeheightproportionally/
---
## DicomImage.ResizeHeightProportionally method

قم بضبط ارتفاع الصورة مع الحفاظ على نسبة العرض إلى الارتفاع باستخدام هذه الطريقة السهلة الاستخدام. مثالي للمطورين الذين يسعون لتغيير حجم الصور ديناميكيًا مع الحفاظ على نسبها، مما يضمن عرضًا مثاليًا وقابلية استخدام في تطبيقاتهم.

```csharp
public override void ResizeHeightProportionally(int newHeight, ResizeType resizeType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newHeight | Int32 | الارتفاع الجديد. |
| resizeType | ResizeType | نوع تغيير الحجم. |

## أمثلة

هذا المثال يقوم بتحميل صورة DICOM ويعيد تحجيمها بشكل متناسب باستخدام طرق تحجيم مختلفة. يتم تحديد الارتفاع فقط، ويتم حساب العرض تلقائيًا.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
        
    // حفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // حفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);
        
    // حفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // حفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


