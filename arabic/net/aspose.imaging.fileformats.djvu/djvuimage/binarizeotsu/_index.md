---
title: "DjvuImage.BinarizeOtsu"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة DjvuImage. التثبيت باستخدام عتبة Otsu هي تقنية تحسب تلقائيًا قيمة عتبة مثالية بناءً على مخطط ترددات الصورة. تفصل الصورة إلى المقدمة والخلفية عن طريق تقليل التباين داخل الفئة. تُستخدم طريقة Otsu على نطاق واسع لتقسيم الصور إلى شكل ثنائي خاصةً عندما يكون توزيع شدة البكسلات ثنائي القمة أو متعدد القمم. هذا النهج مفيد للمهام مثل اكتشاف الكائنات وتقسيم الصور واستخراج الميزات حيث يكون التحديد الدقيق بين المقدمة والخلفية أمرًا حاسمًا."
type: docs
weight: 200
url: /ar/net/aspose.imaging.fileformats.djvu/djvuimage/binarizeotsu/
---
## DjvuImage.BinarizeOtsu method

التصنيف الثنائي باستخدام عتبة أوتسو هو تقنية تحسب تلقائيًا قيمة عتبة مثالية بناءً على هيستوجرام الصورة. تفصل الصورة إلى المقدمة والخلفية عن طريق تقليل التباين داخل الفئة. تُستخدم طريقة أوتسو على نطاق واسع لتجزئة الصور إلى شكل ثنائي، خاصةً عندما يكون توزيع شدة البكسلات ثنائي القمة أو متعدد القمم. هذا النهج مفيد لمهام مثل اكتشاف الكائنات، وتجزئة الصور، واستخراج الميزات، حيث يكون التحديد الدقيق بين المقدمة والخلفية أمرًا حاسمًا.

```csharp
public override void BinarizeOtsu()
```

## أمثلة

المثال التالي يثبت صورة DJVU باستخدام عتبة Otsu. تحتوي الصور المثبتة على لونين فقط - الأسود والأبيض.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // صنّف الصورة باستخدام عتبة Otsu.
    djvuImage.BinarizeOtsu();
    djvuImage.Save(dir + "sample.BinarizeOtsu.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


