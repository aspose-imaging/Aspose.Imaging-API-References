---
title: "DjvuImage.Grayscale"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة DjvuImage. تحويل التدرج الرمادي يحول الصورة إلى تمثيل أبيض وأسود حيث يتم تمثيل شدة كل بكسل بقيمة واحدة تتراوح من الأسود إلى الأبيض. هذه العملية تزيل معلومات اللون مما ينتج صورة أحادية اللون. تُستخدم صور التدرج الرمادي عادةً في التطبيقات التي لا تكون فيها الألوان ضرورية أو حيث يُفضَّل البساطة مثل مسح المستندات ضوئياً والطباعة وبعض أنواع تحليل الصور."
type: docs
weight: 250
url: /ar/net/aspose.imaging.fileformats.djvu/djvuimage/grayscale/
---
## DjvuImage.Grayscale method

تحويل إلى تدرج الرمادي يحول الصورة إلى تمثيل أبيض وأسود، حيث يتم تمثيل شدة كل بكسل بقيمة واحدة تتراوح بين الأسود والأبيض. يزيل هذا العملية معلومات اللون، مما ينتج صورة أحادية اللون. تُستخدم صور التدرج الرمادي عادةً في التطبيقات التي لا تكون فيها الألوان ضرورية أو حيث يُفضَّل البساطة، مثل مسح المستندات، والطباعة، وبعض أنواع تحليل الصور.

```csharp
public override void Grayscale()
```

## أمثلة

المثال التالي يحول صورة DJVU ملونة إلى تمثيلها بالتدرج الرمادي. تتكون صور التدرج الرمادي حصريًا من درجات اللون الرمادي وتحمل معلومات الشدة فقط.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    djvuImage.Grayscale();
    djvuImage.Save(dir + "sample.Grayscale.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


