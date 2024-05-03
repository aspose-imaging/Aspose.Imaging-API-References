---
title: CdrImage.SetPalette
second_title: Aspose.Imaging for .NET API Reference
description: CdrImage method. Customize the color palette of the image with this intuitive method. Ideal for developers seeking to apply specific color schemes or adjustments dynamically ensuring precise control over the visual appearance of their images
type: docs
weight: 150
url: /net/aspose.imaging.fileformats.cdr/cdrimage/setpalette/
---
## CdrImage.SetPalette method

Customize the color palette of the image with this intuitive method. Ideal for developers seeking to apply specific color schemes or adjustments dynamically, ensuring precise control over the visual appearance of their images.

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
* class [CdrImage](../)
* namespace [Aspose.Imaging.FileFormats.Cdr](../../cdrimage/)
* assembly [Aspose.Imaging](../../../)


