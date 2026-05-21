---
title: "GifImage.BinarizeFixed"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة GifImage. تحويل الصورة إلى ثنائية باستخدام عتبة محددة مسبقًا يحول الصورة ذات التدرج الرمادي أو الملونة إلى صورة ثنائية حيث يتم تصنيف كل بكسل إما أسود أو أبيض بناءً على ما إذا كانت قيمة شدتها تتجاوز العتبة المحددة."
type: docs
weight: 250
url: /ar/net/aspose.imaging.fileformats.gif/gifimage/binarizefixed/
---
## GifImage.BinarizeFixed method

تحويل الصورة إلى ثنائية باستخدام عتبة محددة مسبقًا يحول صورة رمادية أو ملونة إلى صورة ثنائية، حيث يُصنّف كل بكسل إما أسود أو أبيض بناءً على ما إذا كانت قيمته الشدة تتجاوز العتبة المحددة.

```csharp
public override void BinarizeFixed(byte threshold)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| threshold | بايت | قيمة العتبة. إذا كانت القيمة الرمادية المقابلة للبكسل أكبر من العتبة، سيتم تعيين القيمة 255 له، وإلا ستكون 0. |

## أمثلة

المثال التالي يحول صورة GIF إلى ثنائية باستخدام العتبة المحددة مسبقًا. الصور الثنائية تحتوي فقط على لونين - الأسود والأبيض.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage djvuImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // حوّل الصورة إلى ثنائية باستخدام قيمة عتبة 127.
    // إذا كانت القيمة الرمادية المقابلة للبكسل أكبر من 127، سيتم تعيين القيمة 255 له، وإلا ستكون 0.
    djvuImage.BinarizeFixed(127);
    djvuImage.Save(dir + "sample.BinarizeFixed.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


