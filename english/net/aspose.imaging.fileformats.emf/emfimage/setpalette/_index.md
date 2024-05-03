---
title: EmfImage.SetPalette
second_title: Aspose.Imaging for .NET API Reference
description: EmfImage method. Enhance your images color palette by setting it with the specified IColorPalette. Achieve vivid vibrant visuals with ease ensuring your images stand out and captivate viewers. Ideal for optimizing color schemes and achieving the perfect look for your projects
type: docs
weight: 160
url: /net/aspose.imaging.fileformats.emf/emfimage/setpalette/
---
## EmfImage.SetPalette method

Enhance your image's color palette by setting it with the specified `IColorPalette`. Achieve vivid, vibrant visuals with ease, ensuring your images stand out and captivate viewers. Ideal for optimizing color schemes and achieving the perfect look for your projects.

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
| NotImplementedException | Invalid for vector images |

### See Also

* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* class [EmfImage](../)
* namespace [Aspose.Imaging.FileFormats.Emf](../../emfimage/)
* assembly [Aspose.Imaging](../../../)


