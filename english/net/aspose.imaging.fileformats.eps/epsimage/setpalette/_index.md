---
title: EpsImage.SetPalette
second_title: Aspose.Imaging for .NET API Reference
description: EpsImage method. Customize image palettes to achieve unique color schemes and enhance visual appeal. Tailor colors for specific effects and optimize image quality across different platforms and devices with ease
type: docs
weight: 220
url: /net/aspose.imaging.fileformats.eps/epsimage/setpalette/
---
## EpsImage.SetPalette method

Customize image palettes to achieve unique color schemes and enhance visual appeal. Tailor colors for specific effects and optimize image quality across different platforms and devices with ease.

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
| NotSupportedException | Not supported by VectorImage |

### See Also

* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* class [EpsImage](../)
* namespace [Aspose.Imaging.FileFormats.Eps](../../epsimage/)
* assembly [Aspose.Imaging](../../../)


