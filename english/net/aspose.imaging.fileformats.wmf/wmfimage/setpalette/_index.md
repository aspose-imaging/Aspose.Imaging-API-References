---
title: WmfImage.SetPalette
second_title: Aspose.Imaging for .NET API Reference
description: WmfImage method. Apply a specified palette to the image enabling customization of color representation. Utilize this method to enhance visual rendering and achieve specific color effects within your application
type: docs
weight: 150
url: /net/aspose.imaging.fileformats.wmf/wmfimage/setpalette/
---
## WmfImage.SetPalette method

Apply a specified palette to the image, enabling customization of color representation. Utilize this method to enhance visual rendering and achieve specific color effects within your application.

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
* class [WmfImage](../)
* namespace [Aspose.Imaging.FileFormats.Wmf](../../wmfimage/)
* assembly [Aspose.Imaging](../../../)


