---
title: Image.SetPalette
second_title: Aspose.Imaging for .NET API Reference
description: Image method. Sets the image palette
type: docs
weight: 320
url: /net/aspose.imaging/image/setpalette/
---
## Image.SetPalette method

Sets the image palette.

```csharp
public abstract void SetPalette(IColorPalette palette, bool updateColors)
```

| Parameter | Type | Description |
| --- | --- | --- |
| palette | IColorPalette | The palette to set. |
| updateColors | Boolean | if set to `true` colors will be updated according to the new palette; otherwise color indexes remain unchanged. Note that unchanged indexes may crash the image on loading if some indexes have no corresponding palette entries. |

### See Also

* interface [IColorPalette](../../icolorpalette/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


