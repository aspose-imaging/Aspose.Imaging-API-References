---
title: "TiffImage.Grayscale"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة TiffImage. تحويل الصورة إلى تمثيلها الرمادي بتحويلها إلى صورة ذات قناة واحدة حيث يمثل كل بكسل الشدة. دمج هذه الطريقة في خط معالجة الصور الخاص بك لتبسيط التحليل وتعزيز التوافق مع الخوارزميات القائمة على التدرج الرمادي مما يسهل مهام الرؤية الحاسوبية وتحليل الصور المختلفة داخل تطبيقك."
type: docs
weight: 270
url: /ar/net/aspose.imaging.fileformats.tiff/tiffimage/grayscale/
---
## TiffImage.Grayscale method

حوّل الصورة إلى تمثيلها الرمادي، محولًا إياها إلى صورة ذات قناة واحدة حيث يمثل كل بكسل الشدة. دمج هذه الطريقة في خط أنابيب معالجة الصور لتبسيط التحليل وتعزيز التوافق مع الخوارزميات القائمة على التدرج الرمادي، مسهلاً مختلف مهام الرؤية الحاسوبية وتحليل الصور داخل تطبيقك.

```csharp
public override void Grayscale()
```

## أمثلة

المثال التالي يحول صورة TIFF ملونة إلى تمثيلها الرمادي. الصور الرمادية تتكون حصريًا من درجات اللون الرمادي وتحمل معلومات الشدة فقط.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    tiffImage.Grayscale();
    tiffImage.Save(dir + "sample.Grayscale.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


