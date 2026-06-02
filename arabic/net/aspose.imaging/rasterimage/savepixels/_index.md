---
title: "RasterImage.SavePixels"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterImage. تحفظ البكسلات."
type: docs
weight: 600
url: /ar/net/aspose.imaging/rasterimage/savepixels/
---
## RasterImage.SavePixels method

يحفظ البكسلات.

```csharp
public void SavePixels(Rectangle rectangle, Color[] pixels)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المستطيل | Rectangle | المستطيل لحفظ البكسلات فيه. |
| البكسلات | Color[] | مصفوفة البكسلات. |

## أمثلة

المثال التالي يملأ المنطقة المركزية لصورة نقطية ببكسلات سوداء باستخدام طريقة Aspose.Imaging.RasterImage.SavePixels.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // المربع الأسود
    Color[] pixels = new Color[(rasterImage.Width / 2) * (rasterImage.Height / 2)];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Color.Black;
    }

    // ارسم المربع الأسود في مركز الصورة.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(rasterImage.Width / 4, rasterImage.Height / 4, rasterImage.Width / 2, rasterImage.Height / 2);
    rasterImage.SavePixels(area, pixels);

    rasterImage.Save(dir + "sample.SavePixels.png");
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

* struct [Rectangle](../../rectangle/)
* struct [Color](../../color/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


