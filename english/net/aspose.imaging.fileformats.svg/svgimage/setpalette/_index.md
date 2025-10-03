---
title: SvgImage.SetPalette
second_title: Aspose.Imaging for .NET API Reference
description: SvgImage method. Applies a specified palette to the image enabling customization of color schemes for aesthetic or functional purposes. This method provides flexibility in managing color palettes to suit various design or application requirements
type: docs
weight: 90
url: /net/aspose.imaging.fileformats.svg/svgimage/setpalette/
---
## SvgImage.SetPalette method

Applies a specified palette to the image, enabling customization of color schemes for aesthetic or functional purposes. This method provides flexibility in managing color palettes to suit various design or application requirements.

```csharp
public override void SetPalette(IColorPalette palette, bool updateColors)
```

| Parameter | Type | Description |
| --- | --- | --- |
| palette | IColorPalette | The palette to set. |
| updateColors | Boolean | if set to `true` colors will be updated according to the new palette; otherwise color indexes remain unchanged. Note that unchanged indexes may crash the image on loading if some indexes have no corresponding palette entries. |

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException |  |

### See Also

* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* class [SvgImage](../)
* namespace [Aspose.Imaging.FileFormats.Svg](../../svgimage/)
* assembly [Aspose.Imaging](../../../)


