---
title: "MetafileRecorderGraphics2D.SetTransform"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة MetafileRecorderGraphics2D. تضبط التحويل"
type: docs
weight: 290
url: /ar/net/aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/settransform/
---
## MetafileRecorderGraphics2D.SetTransform method

يضبط التحويل.

```csharp
public void SetTransform(Matrix transform)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| تحويل | مصفوفة | مصفوفة التحويل الجديدة. |

## أمثلة

هذا المثال يوضح كيفية تحميل صورة EMF من ملف ورسم سلسلة نصية فوقها.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
    Aspose.Imaging.FileFormats.Emf.Graphics.EmfRecorderGraphics2D graphics =
        Aspose.Imaging.FileFormats.Emf.Graphics.EmfRecorderGraphics2D.FromEmfImage(emfImage);

    // أولاً، احصل على حجم الصورة
    int width = emfImage.Width;
    int height = emfImage.Height;

    // ثانياً، احسب تحويلًا لوضع سلسلة نصية على القطر الرئيسي للصورة -
    // من الزاوية العليا اليسرى إلى الزاوية السفلية اليمنى.
    float emFontSize = 96f;
    float d = (float)System.Math.Sqrt(width * width + height * height);
    float scaleFactor = d / (emFontSize * 5f);

    float tan = ((float)height) / width;                
    double radians = System.Math.Atan(tan);
    double degrees = (180 * radians) / System.Math.PI;

    Aspose.Imaging.Matrix transform = new Aspose.Imaging.Matrix();
    transform.Rotate((float)degrees);
    transform.Scale(scaleFactor, scaleFactor);

    // ثم، اضبط التحويل.
    graphics.SetTransform(transform);

    // أخيرًا، ضع علامة مائية (سلسلة نصية باللون الوردي) على القطر الرئيسي.
    graphics.DrawString("WATERMARK", new Aspose.Imaging.Font("Courier New", emFontSize), Aspose.Imaging.Color.LightPink, 0, 0/*, (float)degrees*/);

    // احفظ الصورة مع العلامة المائية إلى ملف EMF آخر.
    using (Aspose.Imaging.FileFormats.Emf.EmfImage scaledEmfImage = graphics.EndRecording())
    {
        scaledEmfImage.Save(dir + "test.scaled.emf");
    }
}
```

### انظر أيضًا

* class [Matrix](../../../aspose.imaging/matrix/)
* class [MetafileRecorderGraphics2D](../)
* namespace [Aspose.Imaging.FileFormats.Emf.Graphics](../../metafilerecordergraphics2d/)
* assembly [Aspose.Imaging](../../../)


