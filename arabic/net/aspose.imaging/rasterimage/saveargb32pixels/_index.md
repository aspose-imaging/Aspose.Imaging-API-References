---
title: "RasterImage.SaveArgb32Pixels"
second_title: "Aspose.Imaging for .NET API Reference"
description: "RasterImage method. يحفظ بكسلات ARGB 32-بت"
type: docs
weight: 580
url: /ar/net/aspose.imaging/rasterimage/saveargb32pixels/
---
## RasterImage.SaveArgb32Pixels method

يحفظ بكسلات ARGB 32 بت.

```csharp
public void SaveArgb32Pixels(Rectangle rectangle, int[] pixels)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المستطيل | Rectangle | المستطيل لحفظ البكسلات فيه. |
| البكسلات | Int32[] | مصفوفة بكسلات ARGB 32-بت. |

## أمثلة

المثال التالي يملأ المنطقة المركزية لصورة نقطية بكسلات سوداء باستخدام طريقة Aspose.Imaging.RasterImage.SaveArgb32Pixels.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // المربع الأسود
    int[] pixels = new int[(rasterImage.Width / 2) * (rasterImage.Height / 2)];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Color.Black.ToArgb();
    }

    // ارسم المربع الأسود في مركز الصورة.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(rasterImage.Width / 4, rasterImage.Height / 4, rasterImage.Width / 2, rasterImage.Height / 2);
    rasterImage.SaveArgb32Pixels(area, pixels);

    rasterImage.Save(dir + "sample.SaveArgb32Pixels.png");
}
```

### انظر أيضًا

* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


