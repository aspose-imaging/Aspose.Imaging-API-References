---
title: "MetafileOptions.Compress"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية MetafileOptions. يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا ICompressedOptions مضغوطًا"
type: docs
weight: 20
url: /ar/net/aspose.imaging.imageoptions/metafileoptions/compress/
---
## MetafileOptions.Compress property

يحصل أو يضبط قيمة تشير إلى ما إذا كان ICompressedOptions مضغوطًا.

```csharp
public bool Compress { get; set; }
```

### Property Value

`true` إذا كان مضغوطًا؛ وإلا `false`.

## أمثلة

المثال التالي يوضح كيفية تحويل صور emf إلى تنسيق emz

```csharp
[C#]

string file = "input.emf";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".emz";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.EmfOptions() {VectorRasterizationOptions = vectorRasterizationOptions, Compress = true});
}
```

يوضح المثال التالي كيفية تحويل صور wmf إلى تنسيق wmz.

```csharp
[C#]

string file = "castle.wmf";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".wmz";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.WmfOptions() {VectorRasterizationOptions = vectorRasterizationOptions, Compress = true});
}
```

### انظر أيضًا

* class [MetafileOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../metafileoptions/)
* assembly [Aspose.Imaging](../../../)


