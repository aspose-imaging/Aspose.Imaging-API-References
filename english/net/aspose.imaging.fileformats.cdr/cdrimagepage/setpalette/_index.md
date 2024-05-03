---
title: CdrImagePage.SetPalette
second_title: Aspose.Imaging for .NET API Reference
description: CdrImagePage method. Sets the image palette
type: docs
weight: 130
url: /net/aspose.imaging.fileformats.cdr/cdrimagepage/setpalette/
---
## CdrImagePage.SetPalette method

Sets the image palette.

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
* class [CdrImagePage](../)
* namespace [Aspose.Imaging.FileFormats.Cdr](../../cdrimagepage/)
* assembly [Aspose.Imaging](../../../)


