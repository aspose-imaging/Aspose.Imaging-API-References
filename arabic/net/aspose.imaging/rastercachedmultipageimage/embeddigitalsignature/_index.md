---
title: "RasterCachedMultipageImage.EmbedDigitalSignature"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterCachedMultipageImage. تضمين توقيع رقمي بناءً على كلمة المرور المقدمة في كل صفحة من الصورة"
type: docs
weight: 240
url: /ar/net/aspose.imaging/rastercachedmultipageimage/embeddigitalsignature/
---
## RasterCachedMultipageImage.EmbedDigitalSignature method

أدمج توقيعًا رقميًا بناءً على كلمة المرور المقدمة في كل صفحة من الصورة.

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

* class [RasterCachedMultipageImage](../)
* namespace [Aspose.Imaging](../../rastercachedmultipageimage/)
* assembly [Aspose.Imaging](../../../)


