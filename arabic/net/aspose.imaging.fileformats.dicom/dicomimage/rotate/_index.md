---
title: "DicomImage.Rotate"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة DicomImage. قم بتدوير الصورة حول مركزها باستخدام هذه الطريقة المريحة. مثالي للمطورين الذين يرغبون في تعديل اتجاه الصورة ديناميكيًا لضمان عرض ومحاذاة مثالية داخل تطبيقاتهم"
type: docs
weight: 280
url: /ar/net/aspose.imaging.fileformats.dicom/dicomimage/rotate/
---
## DicomImage.Rotate method

دوّر الصورة حول مركزها باستخدام هذه الطريقة المريحة. مثالي للمطورين الذين يرغبون في ضبط اتجاه الصورة ديناميكيًا، مع ضمان عرض ومحاذاة مثالية داخل تطبيقاتهم.

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | فردي | زاوية التدوير بالدرجات. القيم الموجبة ستدور باتجاه عقارب الساعة. |
| resizeProportionally | Boolean | إذا تم تعيينه إلى `true` سيتغير حجم الصورة وفقًا لإسقاطات المستطيل المدور (نقاط الزوايا)، وفي الحالة الأخرى تُترك الأبعاد دون تغيير وتُدور فقط محتويات الصورة `internal`. |
| backgroundColor | لون | لون الخلفية. |

## أمثلة

يوضح هذا المثال كيفية تدوير جميع صفحات صورة DICOM وحفظها جميعًا في صورة TIFF متعددة الإطارات.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل صورة DICOM من تدفق ملف.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "multiframe.dicom"))
{
    using (Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = new Aspose.Imaging.FileFormats.Dicom.DicomImage(stream))
    {
        // دوِّر الصورة حول المركز بزاوية 60 درجة باتجاه عقارب الساعة.
        // استخدم اللون الرمادي كلون خلفية.
        dicomImage.Rotate(60, true, Aspose.Imaging.Color.Gray);

        Aspose.Imaging.ImageOptions.TiffOptions createOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
        createOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Deflate;

        // لاحظ أنه إذا كانت الصورة ملونة، فسيتم تحويلها تلقائيًا إلى صيغة التدرج الرمادي وفقًا للخيارات أدناه
        createOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;
        createOptions.BitsPerSample = new ushort[] { 8 };

        // إنشاء مصفوفة من إطارات TIFF.
        // عدد الإطارات يساوي عدد صفحات DJVU.
        Aspose.Imaging.FileFormats.Tiff.TiffFrame[] tiffFrames = new Aspose.Imaging.FileFormats.Tiff.TiffFrame[dicomImage.DicomPages.Length];

        // احفظ كل صفحة كإطار TIFF منفصل.
        foreach (Aspose.Imaging.FileFormats.Dicom.DicomPage dicomPage in dicomImage.DicomPages)
        {
            // إنشاء إطار TIFF بناءً على صفحة DICOM.
            tiffFrames[dicomPage.Index] = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(dicomPage, createOptions);
        }

        // تجميع صورة TIFF من الإطارات.
        using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(tiffFrames))
        {
            // احفظ إلى ملف.
            tiffImage.Save(dir + "multiframe.tif");
        }
    }
}
```

### انظر أيضًا

* struct [Color](../../../aspose.imaging/color/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


