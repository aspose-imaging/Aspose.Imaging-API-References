---
title: MetafileOptions.Compress
second_title: Aspose.Imaging for .NET API Reference
description: MetafileOptions property. Gets or sets a value indicating whether this ICompressedOptions is compressed
type: docs
weight: 20
url: /net/aspose.imaging.imageoptions/metafileoptions/compress/
---
## MetafileOptions.Compress property

Gets or sets a value indicating whether this ICompressedOptions is compressed.

```csharp
public bool Compress { get; set; }
```

### Property Value

`true` if compressed; otherwise, `false`.

## Examples

The following example shows how to convert a emf images to emz fromat

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

The following example shows how to convert a wmf images to wmz fromat

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

### See Also

* class [MetafileOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../metafileoptions/)
* assembly [Aspose.Imaging](../../../)


