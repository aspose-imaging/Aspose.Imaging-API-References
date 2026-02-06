---
title: Class EmfPlusHatchBrushData
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusHatchBrushData class. The EmfPlusHatchBrushData object specifies a hatch pattern for a graphics brush
type: docs
weight: 5600
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfplushatchbrushdata/
---
## EmfPlusHatchBrushData class

The EmfPlusHatchBrushData object specifies a hatch pattern for a graphics brush.

```csharp
public sealed class EmfPlusHatchBrushData : EmfPlusBaseBrushData
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusHatchBrushData](emfplushatchbrushdata/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BackArgb32Color](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplushatchbrushdata/backargb32color/) { get; set; } | Gets or sets a 32-bit EmfPlusArgb object that specifies the color used to paint the background of the hatch pattern. |
| [ForeArgb32Color](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplushatchbrushdata/foreargb32color/) { get; set; } | Gets or sets a 32-bit EmfPlusArgb object that specifies the color used to draw the lines of the hatch pattern. |
| [HatchStyle](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplushatchbrushdata/hatchstyle/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the brush hatch style. It MUST be defined in the [`EmfPlusHatchStyle`](../../aspose.imaging.fileformats.emf.emfplus.consts/emfplushatchstyle/) enumeration. |

## Remarks

Graphics brushes are specified by [`EmfPlusBrush`](../emfplusbrush/) objects (section 2.2.1.1). A hatch brush paints a background and draws a pattern of lines, dots, dashes, squares, and crosshatch lines over this background. The hatch brush defines two colors: one for the background and one for the pattern over the background. The color of the background is called the background color, and the color of the pattern is called the foreground color.

### See Also

* class [EmfPlusBaseBrushData](../emfplusbasebrushdata/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


