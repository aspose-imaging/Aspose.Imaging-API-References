---
title: VectorMultipageImage.SetPalette
second_title: Aspose.Imaging for .NET API Reference
description: VectorMultipageImage method. Sets the image palette
type: docs
weight: 170
url: /net/aspose.imaging/vectormultipageimage/setpalette/
---
## VectorMultipageImage.SetPalette method

Sets the image palette.

```csharp
public override void SetPalette(IColorPalette palette, bool updateColors)
```

| Parameter | Type | Description |
| --- | --- | --- |
| palette | IColorPalette | The palette to set. |
| updateColors | Boolean | if set to `true` colors will be updated according to the new palette; otherwise color indexes remain unchanged. Note that unchanged indexes may crash the image on loading if some indexes have no corresponding palette entries. |

### See Also

* interface [IColorPalette](../../icolorpalette/)
* class [VectorMultipageImage](../)
* namespace [Aspose.Imaging](../../vectormultipageimage/)
* assembly [Aspose.Imaging](../../../)


