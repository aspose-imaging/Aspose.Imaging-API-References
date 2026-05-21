---
title: "DicomImage.AddPage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة DicomImage. وسّع مجموعة صورك بإضافة صفحة جديدة باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يرغبون في إلحاق صفحات ديناميكيًا بصور متعددة الصفحات لضمان توسع سلس وتنظيم محتوى الصورة."
type: docs
weight: 100
url: /ar/net/aspose.imaging.fileformats.dicom/dicomimage/addpage/
---
## AddPage(RasterImage) {#addpage_1}

وسّع مجموعة صورك بإضافة صفحة جديدة باستخدام هذه الطريقة البديهية. مثالية للمطورين الذين يرغبون في إلحاق صفحات ديناميكيًا بالصور متعددة الصفحات، مع ضمان توسيع وتنظيم محتوى الصورة بسلاسة.

```csharp
public void AddPage(RasterImage page)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| page | RasterImage | الصفحة المراد إضافتها. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *page* فارغ. |

### انظر أيضًا

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)

---

## AddPage() {#addpage}

أضف صفحة جديدة إلى نهاية قائمة صفحات الصورة باستخدام هذه الطريقة البسيطة. مثالية للمطورين الذين يرغبون في توسيع الصور متعددة الصفحات ديناميكيًا، مع ضمان دمج وتنظيم محتوى الصورة بسلاسة.

```csharp
public DicomPage AddPage()
```

### قيمة الإرجاع

الـ[`DicomPage`](../../dicompage/) الذي تم إنشاؤه حديثًا.

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


