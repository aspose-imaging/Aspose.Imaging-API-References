---
title: "RasterImage.LoadPixels"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterImage. تحمل البكسلات."
type: docs
weight: 460
url: /ar/net/aspose.imaging/rasterimage/loadpixels/
---
## RasterImage.LoadPixels method

يحمّل البكسلات.

```csharp
public Color[] LoadPixels(Rectangle rectangle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المستطيل | Rectangle | المستطيل الذي يتم تحميل البكسلات منه. |

### قيمة الإرجاع

مصفوفة البكسلات المحملة.

## أمثلة

المثال التالي يوضح كيفية تحميل ومعالجة بكسلات صورة نقطية. على سبيل المثال، ضع في الاعتبار مشكلة حساب البكسلات الشفافة بالكامل في صورة.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\alpha.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // حمّل البكسلات لكامل الصورة. يمكن تحديد أي جزء مستطيل من الصورة كمعامل لطريقة Aspose.Imaging.RasterImage.LoadPixels.
    Color[] pixels = rasterImage.LoadPixels(rasterImage.Bounds);

    int count = 0;
    foreach (Color pixel in pixels)
    {
        if (pixel.A == 0)
        {
            count++;
        }
    }

    System.Console.WriteLine("The number of fully transparent pixels is {0}", count);
    System.Console.WriteLine("The total number of pixels is {0}", image.Width * image.Height);
}
```

يوضح هذا المثال كيفية تحميل معلومات البكسل في مصفوفة من النوع Color، تعديل المصفوفة وإعادتها إلى الصورة. لتنفيذ هذه العمليات، ينشئ هذا المثال ملف صورة جديد (بتنسيق GIF) باستخدام كائن MemoryStream.

```csharp
[C#]

//إنشاء مثيل من MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //إنشاء مثيل من GifOptions وتعيين خصائصه المتنوعة بما في ذلك خاصية Source
    Aspose.Imaging.ImageOptions.GifOptions gifOptions = new Aspose.Imaging.ImageOptions.GifOptions();
    gifOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //إنشاء مثيل من Image
    using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(gifOptions, 500, 500))
    {
        //احصل على بكسلات الصورة عن طريق تحديد المنطقة كحدود الصورة
        Aspose.Imaging.Color[] pixels = image.LoadPixels(image.Bounds);

        //التكرار عبر المصفوفة وتعيين لون البكسل المفهرس البديل
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //تعيين لون البكسل المفهرس إلى الأصفر
                pixels[index] = Aspose.Imaging.Color.Yellow;
            }
            else
            {
                //تعيين لون البكسل المفهرس إلى الأزرق
                pixels[index] = Aspose.Imaging.Color.Blue;
            }
        }

        //تطبيق تغييرات البكسل على الصورة
        image.SavePixels(image.Bounds, pixels);

        // احفظ جميع التغييرات.
        image.Save();
    }

    // كتابة MemoryStream إلى ملف
    using (System.IO.FileStream fileStream = new System.IO.FileStream(@"C:\temp\output.gif", System.IO.FileMode.Create))
    {
        stream.WriteTo(fileStream);
    }   
}
```

### انظر أيضًا

* struct [Color](../../color/)
* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


