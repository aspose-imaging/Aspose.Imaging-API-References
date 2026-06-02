---
title: "RasterImage.LoadArgb64Pixels"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterImage. تقوم بتحميل بكسلات ARGB 64 بت"
type: docs
weight: 410
url: /ar/net/aspose.imaging/rasterimage/loadargb64pixels/
---
## RasterImage.LoadArgb64Pixels method

يحمّل بكسلات ARGB 64‑بت.

```csharp
public long[] LoadArgb64Pixels(Rectangle rectangle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المستطيل | Rectangle | المستطيل الذي يتم تحميل البكسلات منه. |

### قيمة الإرجاع

مصفوفة بكسلات ARGB 64‑بت المحملة.

## أمثلة

المثال التالي يوضح كيفية تحميل ومعالجة بكسلات صورة نقطية. تم تمثيل البكسلات كقيم صحيحة 64‑بت. على سبيل المثال، ضع في الاعتبار مشكلة حساب البكسلات الشفافة بالكامل في صورة.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\16rgba.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // حمّل البكسلات لكامل الصورة. يمكن تحديد أي جزء مستطيل من الصورة كمعامل لطريقة Aspose.Imaging.RasterImage.LoadArgb64Pixels.
    // لاحظ أن الصورة نفسها يجب أن تكون 16 بت لكل عينة، لأن Aspose.Imaging.RasterImage.LoadArgb64Pixels لا يعمل مع 8 بت لكل عينة.
    // للعمل مع 8 بت لكل عينة يرجى استخدام الطريقة القديمة الجيدة Aspose.Imaging.RasterImage.LoadArgb32Pixels.
    long[] pixels = rasterImage.LoadArgb64Pixels(rasterImage.Bounds);

    int count = 0;
    foreach (int pixel in pixels)
    {
        // لاحظ أن جميع مكونات اللون بما في ذلك ألفا ممثلة بقيم 16‑بت، لذا فإن القيم المسموح بها تقع في النطاق [0, 63535].
        int alpha = (pixel >> 48) & 0xffff;
        if (alpha == 0)
        {
            count++;
        }
    }

    System.Console.WriteLine("The number of fully transparent pixels is {0}", count);
    System.Console.WriteLine("The total number of pixels is {0}", image.Width * image.Height);
}
```

### انظر أيضًا

* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


