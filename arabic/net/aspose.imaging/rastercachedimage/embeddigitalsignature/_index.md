---
title: "RasterCachedImage.EmbedDigitalSignature"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterCachedImage. تضمين توقيع رقمي بناءً على كلمة المرور المقدمة في الصورة باستخدام إخفاء البيانات"
type: docs
weight: 140
url: /ar/net/aspose.imaging/rastercachedimage/embeddigitalsignature/
---
## RasterCachedImage.EmbedDigitalSignature method

إدراج توقيع رقمي بناءً على كلمة المرور المقدمة داخل الصورة باستخدام تقنية التضمين.

```csharp
public override void EmbedDigitalSignature(string password)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| كلمة المرور | String | كلمة المرور المستخدمة لتوليد بيانات التوقيع الرقمي |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [ImageException](../../../aspose.imaging.coreexceptions/imageexception/) | يُطرح في حال حدوث أي مشكلات في المعالجة. |

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

* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)


