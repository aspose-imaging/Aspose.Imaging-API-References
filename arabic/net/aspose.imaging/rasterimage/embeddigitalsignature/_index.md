---
title: "RasterImage.EmbedDigitalSignature"
second_title: "Aspose.Imaging for .NET API Reference"
description: "RasterImage method. إدراج توقيع رقمي بناءً على كلمة المرور المقدمة في الصورة باستخدام التخفي الرقمي"
type: docs
weight: 290
url: /ar/net/aspose.imaging/rasterimage/embeddigitalsignature/
---
## RasterImage.EmbedDigitalSignature method

إدراج توقيع رقمي بناءً على كلمة المرور المقدمة داخل الصورة باستخدام تقنية التضمين.

```csharp
public virtual void EmbedDigitalSignature(string password)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| كلمة المرور | String | كلمة المرور المستخدمة لتوليد بيانات التوقيع الرقمي |

## أمثلة

يوضح المثال كيفية تضمين توقيع رقمي بناءً على كلمة المرور المقدمة في بيانات بكسل الصورة.

```csharp
[C#]

var imageFilePath = "ball.png";
var password = "veryStr0ngPassword";
using (var image = Image.Load(imageFilePath))
{
    image.EmbedDigitalSignature(password);
    image.Save(outputPath);
}
```

### انظر أيضًا

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


