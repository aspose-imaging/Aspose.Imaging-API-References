---
title: "RasterImage.LoadPartialArgb32Pixels"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterImage. تقوم بتحميل بكسلات ARGB 32 بت جزئيًا على شكل حزم."
type: docs
weight: 430
url: /ar/net/aspose.imaging/rasterimage/loadpartialargb32pixels/
---
## RasterImage.LoadPartialArgb32Pixels method

يحمّل بكسلات ARGB 32‑بت جزئيًا عن طريق الحزم.

```csharp
public void LoadPartialArgb32Pixels(Rectangle rectangle, 
    IPartialArgb32PixelLoader partialPixelLoader)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المستطيل | Rectangle | المستطيل المطلوب. |
| partialPixelLoader | IPartialArgb32PixelLoader | محمل بكسلات ARGB 32 بت. |

## أمثلة

المثال التالي يوضح كيفية تحميل ومعالجة بكسلات صورة نقطية باستخدام معالج جزئي خاص بك. على سبيل المثال، اعتبر مشكلة عد البكسلات الشفافة بالكامل في صورة. من أجل عد البكسلات الشفافة باستخدام آلية التحميل الجزئي، يتم تقديم فئة منفصلة تسمى TransparentArgb32PixelCounter التي تنفذ Aspose.Imaging.IPartialArgb32PixelLoader.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\alpha.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // أنشئ مثيلًا من Aspose.Imaging.IPartialArgb32PixelLoader ومرره إلى Aspose.Imaging.RasterImage.LoadPartialArgb32Pixels
    TransparentArgb32PixelCounter counter = new TransparentArgb32PixelCounter();

    // حمّل البكسلات لكامل الصورة. يمكن تحديد أي جزء مستطيل من الصورة كالمعامل الأول لطريقة Aspose.Imaging.RasterImage.LoadPartialArgb32Pixels.
    rasterImage.LoadPartialArgb32Pixels(rasterImage.Bounds, counter);

    System.Console.WriteLine("The number of fully transparent pixels is {0}", counter.Count);
    System.Console.WriteLine("The total number of pixels is {0}", image.Width * image.Height);
}

// قد يبدو العداد هكذا:        
/// <summary>
/// يحسب عدد البكسلات الشفافة بالكامل ذات قيمة قناة ألفا 0.
/// </summary>
private class TransparentArgb32PixelCounter : IPartialArgb32PixelLoader
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
    public void Process(Aspose.Imaging.Rectangle pixelsRectangle, int[] pixels, Aspose.Imaging.Point start, Aspose.Imaging.Point end)
    {
        foreach (int pixel in pixels)
        {
            int alpha = (pixel >> 24) & 0xff;
            if (alpha == 0)
            {
                this.count++;
            }
        }
    }
}
```

### انظر أيضًا

* struct [Rectangle](../../rectangle/)
* interface [IPartialArgb32PixelLoader](../../ipartialargb32pixelloader/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


