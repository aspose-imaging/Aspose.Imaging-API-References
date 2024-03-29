---
title: SetPalette
second_title: Aspose.Imaging för .NET API-referens
description: Ställer in bildpaletten.
type: docs
weight: 160
url: /sv/net/aspose.imaging.fileformats.emf/emfimage/setpalette/
---
## EmfImage.SetPalette method

Ställer in bildpaletten.

```csharp
public override void SetPalette(IColorPalette palette, bool updateColors)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| palette | IColorPalette | Paletten att ställa in. |
| updateColors | Boolean | om inställt på`Sann`färger kommer att uppdateras enligt den nya paletten; annars förblir färgindexen oförändrade. Observera att oförändrade index kan krascha bilden vid laddning om vissa index inte har några motsvarande palettposter. |

### Undantag

| undantag | skick |
| --- | --- |
| NotImplementedException | Ej giltigt för vektorbilder |

### Se även

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [EmfImage](../../emfimage)
* namnutrymme [Aspose.Imaging.FileFormats.Emf](../../emfimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
