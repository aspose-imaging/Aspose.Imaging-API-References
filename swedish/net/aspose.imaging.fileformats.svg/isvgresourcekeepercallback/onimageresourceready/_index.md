---
title: OnImageResourceReady
second_title: Aspose.Imaging för .NET API-referens
description: Anropas när bildresursen är klar.
type: docs
weight: 20
url: /sv/net/aspose.imaging.fileformats.svg/isvgresourcekeepercallback/onimageresourceready/
---
## ISvgResourceKeeperCallback.OnImageResourceReady method

Anropas när bildresursen är klar.

```csharp
public string OnImageResourceReady(byte[] imageData, SvgImageType imageType, 
    string suggestedFileName, ref bool useEmbeddedImage)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageData | Byte[] | Resursdata. |
| imageType | SvgImageType | Typ av bild. |
| suggestedFileName | String | Namnet på den föreslagna filen. |
| useEmbeddedImage | Boolean& | om inställt på`Sann` den inbäddade bilden måste användas. |

### Returvärde

Returnerar sökväg till sparad resurs. Sökvägen ska vara relativ till mål-SVG-dokumentet.

### Se även

* enum [SvgImageType](../../svgimagetype)
* interface [ISvgResourceKeeperCallback](../../isvgresourcekeepercallback)
* namnutrymme [Aspose.Imaging.FileFormats.Svg](../../isvgresourcekeepercallback)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
