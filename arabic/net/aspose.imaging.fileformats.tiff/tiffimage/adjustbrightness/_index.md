---
title: "TiffImage.AdjustBrightness"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة TiffImage. نفّذ تعديل السطوع للصورة مما يسمح بتعديل مستويات الإضاءة العامة. أدمج هذه الطريقة في سير عمل معالجة الصور الخاص بك لتعزيز الوضوح وتحسين الجودة البصرية للصور داخل تطبيقك"
type: docs
weight: 160
url: /ar/net/aspose.imaging.fileformats.tiff/tiffimage/adjustbrightness/
---
## TiffImage.AdjustBrightness method

تنفيذ تعديل *السطوع* للصورة، مما يسمح بتعديل مستويات الإضاءة العامة. دمج هذه الطريقة في سير عمل معالجة الصور لتعزيز الرؤية وتحسين الجودة البصرية للصور داخل تطبيقك.

```csharp
public override void AdjustBrightness(int brightness)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| السطوع | Int32 | قيمة السطوع. |

## أمثلة

المثال التالي يقوم بتصحيح السطوع لصورة TIFF.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // حدد قيمة السطوع. القيم المقبولة للسطوع هي في النطاق [-255, 255].
    tiffImage.AdjustBrightness(50);
    tiffImage.Save(dir + "sample.AdjustBrightness.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


