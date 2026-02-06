---
title: Class OtgRasterizationOptions
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.ImageOptions.OtgRasterizationOptions class. The Otg rasterization options
type: docs
weight: 10460
url: /net/aspose.imaging.imageoptions/otgrasterizationoptions/
---
## OtgRasterizationOptions class

The Otg rasterization options

```csharp
public class OtgRasterizationOptions : OdRasterizationOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [OtgRasterizationOptions](otgrasterizationoptions/)() | The default constructor. |

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

The following code snippet demonstrates how to convert an OTG image to PDF and other image formats.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3567\\";
string inputFilePath = dir + "VariousObjectsMultiPage.otg";
Aspose.Imaging.ImageOptionsBase[] options = { new Aspose.Imaging.ImageOptions.PngOptions(), new Aspose.Imaging.ImageOptions.PdfOptions() };
foreach (Aspose.Imaging.ImageOptionsBase saveOptions in options)
{
    string extension = saveOptions is Aspose.Imaging.ImageOptions.PngOptions ? ".png" : ".pdf";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
    {
        Aspose.Imaging.ImageOptions.OtgRasterizationOptions otgRasterizationOptions = new Aspose.Imaging.ImageOptions.OtgRasterizationOptions();
        otgRasterizationOptions.PageSize = image.Size;
        saveOptions.VectorRasterizationOptions = otgRasterizationOptions;

        image.Save(inputFilePath + extension, saveOptions);
    }
}
```

### See Also

* class [OdRasterizationOptions](../odrasterizationoptions/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


