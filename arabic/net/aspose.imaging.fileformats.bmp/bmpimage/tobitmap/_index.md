---
title: "BmpImage.ToBitmap"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة BmpImage. حول صورتك النقطية إلى صورة bitmap بسهولة باستخدام هذه الطريقة البسيطة. مثالية للمطورين الذين يحتاجون إلى الانتقال بسلاسة بين صيغ الصور المختلفة."
type: docs
weight: 150
url: /ar/net/aspose.imaging.fileformats.bmp/bmpimage/tobitmap/
---
## BmpImage.ToBitmap method

حوّل صورتك النقطية بسهولة إلى bitmap باستخدام هذه الطريقة البسيطة. مثالي للمطورين الذين يحتاجون إلى الانتقال بسلاسة بين صيغ الصور المختلفة.

```csharp
public override Bitmap ToBitmap()
```

### قيمة الإرجاع

صورة bitmap

## أمثلة

المثال التالي يحول صورة BMP إلى bitmap من نوع GDI.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
    System.Drawing.Bitmap bitmap = bmpImage.ToBitmap();

    // معالجة bitmap الـ GDI.
}
```

### انظر أيضًا

* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)


