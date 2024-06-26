---
title: SvgOptions.Compress
second_title: Aspose.Imaging for .NET API Reference
description: SvgOptions property. Gets or sets a value indicating whether the output image must to be compressed
type: docs
weight: 40
url: /net/aspose.imaging.imageoptions/svgoptions/compress/
---
## SvgOptions.Compress property

Gets or sets a value indicating whether the output image must to be compressed.

```csharp
public bool Compress { get; set; }
```

### Property Value

`true` if compressed; otherwise, `false`.

## Examples

The following example shows how to convert a svg images to svgz fromat

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

### See Also

* class [SvgOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../svgoptions/)
* assembly [Aspose.Imaging](../../../)


