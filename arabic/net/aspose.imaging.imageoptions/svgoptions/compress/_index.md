---
title: "SvgOptions.Compress"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية SvgOptions. يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب ضغط الصورة الناتجة"
type: docs
weight: 40
url: /ar/net/aspose.imaging.imageoptions/svgoptions/compress/
---
## SvgOptions.Compress property

يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب ضغط الصورة الناتجة.

```csharp
public bool Compress { get; set; }
```

### Property Value

`true` إذا كان مضغوطًا؛ وإلا `false`.

## أمثلة

المثال التالي يوضح كيفية تحويل صور svg إلى صيغة svgz.

```csharp
[C#]

string file = "juanmontoya_lingerie.svg";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".svgz";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.SvgOptions() {VectorRasterizationOptions = vectorRasterizationOptions, Compress = true});
}
```

### انظر أيضًا

* class [SvgOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../svgoptions/)
* assembly [Aspose.Imaging](../../../)


