---
title: "RasterImage.SaveCmyk32Pixels"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterImage. تحفظ البكسلات."
type: docs
weight: 590
url: /ar/net/aspose.imaging/rasterimage/savecmyk32pixels/
---
## RasterImage.SaveCmyk32Pixels method

يحفظ البكسلات.

```csharp
public void SaveCmyk32Pixels(Rectangle rectangle, int[] pixels)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المستطيل | Rectangle | المستطيل لحفظ البكسلات فيه. |
| البكسلات | Int32[] | بكسلات CMYK مقدمة كقيم صحيحة 32‑بت. |

## أمثلة

المثال التالي يملأ المنطقة المركزية من صورة نقطية بكسلات سوداء باستخدام طريقة Aspose.Imaging.RasterImage.SaveCmyk32Pixels.

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // احصل على تمثيل صحيح للون الأسود في مساحة ألوان CMYK.
    int blackCmyk = Aspose.Imaging.CmykColorHelper.ToCmyk(Color.Black);

    // المربع الأسود.
    int[] pixels = new int[(rasterImage.Width / 2) * (rasterImage.Height / 2)];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = blackCmyk;
    }

    // ارسم المربع الأسود في مركز الصورة.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(rasterImage.Width / 4, rasterImage.Height / 4, rasterImage.Width / 2, rasterImage.Height / 2);
    rasterImage.SaveCmyk32Pixels(area, pixels);

    rasterImage.Save(dir + "sample.SaveCmyk32Pixels.png");
}
```

### انظر أيضًا

* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


