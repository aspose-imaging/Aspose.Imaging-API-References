---
title: Class OdgRasterizationOptions
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.ImageOptions.OdgRasterizationOptions class. The Odg rasterization options
type: docs
weight: 10370
url: /net/aspose.imaging.imageoptions/odgrasterizationoptions/
---
## OdgRasterizationOptions class

The Odg rasterization options

```csharp
public class OdgRasterizationOptions : OdRasterizationOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [OdgRasterizationOptions](odgrasterizationoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.imageoptions/vectorrasterizationoptions/backgroundcolor/) { get; set; } | Gets or sets a background color. |
| [BorderX](../../aspose.imaging.imageoptions/vectorrasterizationoptions/borderx/) { get; set; } | Gets or sets the border X. |
| [BorderY](../../aspose.imaging.imageoptions/vectorrasterizationoptions/bordery/) { get; set; } | Gets or sets the border Y. |
| [CenterDrawing](../../aspose.imaging.imageoptions/vectorrasterizationoptions/centerdrawing/) { get; set; } | Gets or sets a value indicating whether center drawing. |
| [DrawColor](../../aspose.imaging.imageoptions/vectorrasterizationoptions/drawcolor/) { get; set; } | Gets or sets a foreground color. |
| [PageHeight](../../aspose.imaging.imageoptions/vectorrasterizationoptions/pageheight/) { get; set; } | Gets or sets the page height. If the value is 0, the source image aspect ratio will be preserved. |
| [PageSize](../../aspose.imaging.imageoptions/vectorrasterizationoptions/pagesize/) { get; set; } | Gets or sets the page size. If one of [`SizeF`](../../aspose.imaging/sizef/) dimensions is 0, the source image aspect ratio will be preserved. |
| [PageWidth](../../aspose.imaging.imageoptions/vectorrasterizationoptions/pagewidth/) { get; set; } | Gets or sets the page width. If the value is 0, the source image aspect ratio will be preserved. |
| [Positioning](../../aspose.imaging.imageoptions/vectorrasterizationoptions/positioning/) { get; set; } | Gets or sets the positioning. |
| [ReplaceTextMapping](../../aspose.imaging.imageoptions/vectorrasterizationoptions/replacetextmapping/) { get; set; } | Gets or sets the text replace mapping. |
| [SmoothingMode](../../aspose.imaging.imageoptions/vectorrasterizationoptions/smoothingmode/) { get; set; } | Gets or sets the smoothing mode. |
| [TextRenderingHint](../../aspose.imaging.imageoptions/vectorrasterizationoptions/textrenderinghint/) { get; set; } | Gets or sets the text rendering hint. |

## Methods

| Name | Description |
| --- | --- |
| [Clone](../../aspose.imaging.imageoptions/vectorrasterizationoptions/clone/)() | Creates a new object that is a shallow copy of the current instance. |
| virtual [CopyTo](../../aspose.imaging.imageoptions/vectorrasterizationoptions/copyto/)(VectorRasterizationOptions) | Copies to. |

## Examples

The following example shows how to export a FODG (Flat XML ODF Template) image to PDF format.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3635";

string inputFileName = System.IO.Path.Combine(dir, "VariousObjectsMultiPage.fodg");
string outputFileName = inputFileName + ".pdf";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFileName))
{
    Aspose.Imaging.ImageOptions.OdgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.OdgRasterizationOptions();
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.White;
    rasterizationOptions.PageSize = image.Size;

    Aspose.Imaging.ImageOptions.PdfOptions saveOptions = new Aspose.Imaging.ImageOptions.PdfOptions();
    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    image.Save(outputFileName, saveOptions);
}
```

### See Also

* class [OdRasterizationOptions](../odrasterizationoptions/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


