---
title: "RasterImage.LoadPartialPixels"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterImage. تقوم بتحميل البكسلات جزئياً على شكل حزم"
type: docs
weight: 450
url: /ar/net/aspose.imaging/rasterimage/loadpartialpixels/
---
## RasterImage.LoadPartialPixels method

يحمّل البكسلات جزئيًا عن طريق الحزم.

```csharp
public void LoadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| desiredRectangle | Rectangle | المستطيل المطلوب. |
| pixelLoader | IPartialPixelLoader | محمل البكسل. |

## أمثلة

المثال التالي يوضح كيفية تحميل ومعالجة بكسلات صورة نقطية باستخدام معالج جزئي خاص بك. على سبيل المثال، اعتبر مشكلة عد البكسلات الشفافة بالكامل في صورة. من أجل عد الشفافية باستخدام آلية التحميل الجزئي، يتم تقديم فئة منفصلة تسمى TransparentPixelCounter تنفذ Aspose.Imaging.IPartialPixelLoader.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\alpha.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // أنشئ مثيلاً من Aspose.Imaging.IPartialPixelLoader ومرره إلى Aspose.Imaging.RasterImage.LoadPartialPixels
    TransparentPixelCounter counter = new TransparentPixelCounter();

    // حمّل البكسلات لكامل الصورة. يمكن تحديد أي جزء مستطيل من الصورة كمعامل أول لطريقة Aspose.Imaging.RasterImage.LoadPartialPixels.
    rasterImage.LoadPartialPixels(rasterImage.Bounds, counter);

    System.Console.WriteLine("The number of fully transparent pixels is {0}", counter.Count);
    System.Console.WriteLine("The total number of pixels is {0}", image.Width * image.Height);
}

// قد يبدو العداد هكذا:
/// <summary>
/// يحسب عدد البكسلات الشفافة بالكامل ذات قيمة قناة ألفا 0.
/// </summary>
private class TransparentPixelCounter : IPartialPixelLoader
{
    /// <summary>
    /// عدد البكسلات الشفافة بالكامل.
    /// </summary>
    private int count;

    /// <summary>
    /// يحصل على عدد البكسلات الشفافة بالكامل.
    /// </summary>
    public int Count
    {
        get { return this.count; }
    }

    /// <summary>
    /// يعالج البكسلات المحملة. يتم استدعاء هذه الطريقة في كل مرة يتم فيها تحميل جزء جديد من البكسلات.
    /// </summary>
    /// <param name="pixelsRectangle">مستطيل البكسلات.</param>
    /// <param name="pixels">بيكسلات ARGB 32-بت.</param>
    /// <param name="start">نقطة بكسلات البداية.</param>
    /// <param name="end">نقطة بكسلات النهاية.</param>
    public void Process(Aspose.Imaging.Rectangle pixelsRectangle, Aspose.Imaging.Color[] pixels, Aspose.Imaging.Point start, Aspose.Imaging.Point end)
    {
        foreach (Color pixel in pixels)
        {
            if (pixel.A == 0)
            {
                this.count++;
            }
        }
    }
}
```

### انظر أيضًا

* struct [Rectangle](../../rectangle/)
* interface [IPartialPixelLoader](../../ipartialpixelloader/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


