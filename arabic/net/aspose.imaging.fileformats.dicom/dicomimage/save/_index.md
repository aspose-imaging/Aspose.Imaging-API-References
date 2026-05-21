---
title: "DicomImage.Save"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة DicomImage. احفظ بيانات الصورة بسهولة إلى تدفق محدد بالتنسيق المطلوب باستخدام هذه الطريقة المريحة. سواء كنت تعمل مع JPEG PNG أو أي تنسيق آخر، فإن هذه الدالة تضمن حفظ بيانات الصورة بكفاءة ودقة، مما يجعلها مثالية للمطورين الذين يرغبون في تبسيط عمليات حفظ الملفات."
type: docs
weight: 300
url: /ar/net/aspose.imaging.fileformats.dicom/dicomimage/save/
---
## DicomImage.Save method

احفظ بيانات صورتك بسهولة إلى دفق محدد بالتنسيق الملف المطلوب باستخدام هذه الطريقة المريحة. سواء كنت تعمل مع JPEG أو PNG أو أي تنسيق آخر، تضمن هذه الدالة حفظ بيانات الصورة بكفاءة ودقة، مما يجعلها مثالية للمطورين الذين يرغبون في تبسيط عمليات حفظ الملفات.

```csharp
public override void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | التدفق لحفظ بيانات الصورة إليه. |
| optionsBase | ImageOptionsBase | خيارات الحفظ. |
| boundsRectangle | Rectangle | مستطيل حدود الصورة الهدف. اضبط المستطيل الفارغ لاستخدام حدود المصدر. |

## أمثلة

المثال التالي يحمل صورة DICOM من ملف، ثم يحفظ الصورة إلى تدفق ملف PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(0, 0, image.Width / 2, image.Height / 2);
    using (System.IO.Stream outputStream = System.IO.File.Open(dir + "output.png", System.IO.FileMode.Create))
    {
        // احفظ الربع العلوي الأيسر من الصورة إلى تدفق ملف.
        image.Save(outputStream, saveOptions, bounds);
    }
}
```

### انظر أيضًا

* class [ImageOptionsBase](../../../aspose.imaging/imageoptionsbase/)
* struct [Rectangle](../../../aspose.imaging/rectangle/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


