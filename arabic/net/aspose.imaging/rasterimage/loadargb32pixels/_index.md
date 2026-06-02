---
title: "RasterImage.LoadArgb32Pixels"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterImage. تقوم بتحميل بكسلات ARGB 32 بت"
type: docs
weight: 400
url: /ar/net/aspose.imaging/rasterimage/loadargb32pixels/
---
## RasterImage.LoadArgb32Pixels method

يحمّل بكسلات ARGB 32‑بت.

```csharp
public int[] LoadArgb32Pixels(Rectangle rectangle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المستطيل | Rectangle | المستطيل الذي يتم تحميل البكسلات منه. |

### قيمة الإرجاع

مصفوفة بكسلات ARGB 32‑بت التي تم تحميلها.

## أمثلة

المثال التالي يوضح كيفية تحميل ومعالجة بكسلات صورة نقطية. تمثل البكسلات كقيم صحيحة 32‑بت. على سبيل المثال، ضع في الاعتبار مشكلة عد البكسلات الشفافة تمامًا في صورة.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\alpha.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // تحميل البكسلات لكامل الصورة. يمكن تحديد أي جزء مستطيل من الصورة كمعامل لطريقة Aspose.Imaging.RasterImage.LoadArgb32Pixels.
    int[] pixels = rasterImage.LoadArgb32Pixels(rasterImage.Bounds);

    int count = 0;
    foreach (int pixel in pixels)
    {
        int alpha = (pixel >> 24) & 0xff;
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


