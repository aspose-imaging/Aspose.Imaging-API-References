---
title: "DicomImage.InsertPage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة DicomImage. أدخل صفحة جديدة في قائمة صفحات الصورة عند فهرس محدد باستخدام هذه الطريقة البديهية. مثالية للمطورين الذين يسعون إلى تحكم دقيق في ترتيب الصفحات في الصور متعددة الصفحات لضمان تنظيم سلس وتخصيص محتوى الصورة."
type: docs
weight: 220
url: /ar/net/aspose.imaging.fileformats.dicom/dicomimage/insertpage/
---
## DicomImage.InsertPage method

أدرج صفحة جديدة في قائمة صفحات الصورة عند فهرس محدد باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يرغبون في التحكم الدقيق في ترتيب الصفحات في الصور متعددة الصفحات، مما يضمن تنظيمًا سلسًا وتخصيصًا لمحتوى الصورة.

```csharp
public DicomPage InsertPage(int pageIndex)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pageIndex | Int32 | فهرس الصفحة. |

### قيمة الإرجاع

الـ[`DicomPage`](../../dicompage/) الذي تم إنشاؤه حديثًا.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | *pageIndex* خارج النطاق. |

## أمثلة

إنشاء صورة DICOM متعددة الصفحات.

```csharp
[C#]

using (DicomImage image = (DicomImage)Image.Create(
        new DicomOptions() { Source = new StreamSource(new MemoryStream()) },
        100,
        100))
{
    // ارسم شيئًا باستخدام الرسومات المتجهة
    Graphics graphics = new Graphics(image);
    graphics.FillRectangle(new SolidBrush(Color.BlueViolet), image.Bounds);
    graphics.FillRectangle(new SolidBrush(Color.Aqua), 10, 20, 50, 20);
    graphics.FillEllipse(new SolidBrush(Color.Orange), 30, 50, 70, 30);

    // احفظ بكسلات الصورة المرسومة. الآن هي على الصفحة الأولى من صورة DICOM.
    int[] pixels = image.LoadArgb32Pixels(image.Bounds);

    // أضف بعض الصفحات بعد ذلك، لتجعلها أغمق
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.AddPage();
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(i * 30);
    }

    // أضف بعض الصفحات أمام الصفحة الرئيسية، لتجعلها أكثر سطوعًا
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.InsertPage(0);
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(-i * 30);
    }

    // احفظ الصورة المتعددة الصفحات التي تم إنشاؤها إلى ملف الإخراج
    image.Save("MultiPage.dcm");
}
```

### انظر أيضًا

* class [DicomPage](../../dicompage/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


