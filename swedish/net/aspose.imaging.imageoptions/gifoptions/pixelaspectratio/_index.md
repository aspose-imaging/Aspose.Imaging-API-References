---
title: PixelAspectRatio
second_title: Aspose.Imaging för .NET API-referens
description: Hämtar eller ställer in GIF-pixelns bildförhållande.
type: docs
weight: 120
url: /sv/net/aspose.imaging.imageoptions/gifoptions/pixelaspectratio/
---
## GifOptions.PixelAspectRatio property

Hämtar eller ställer in GIF-pixelns bildförhållande.

```csharp
public byte PixelAspectRatio { get; set; }
```

### Fastighetsvärde

GIF-pixelns bildförhållande.

### Anmärkningar

Pixel Aspect Ratio - Faktor som används för att beräkna en approximation av bildförhållandet för pixeln i originalbilden. Om värdet för fältet inte är 0, beräknas denna approximation av bildförhållandet baserat på formeln: Bildförhållande = (Pixelbildförhållande + 15) / 64 Pixelbildförhållandet definieras som kvoten av pixel s bredd över dess höjd. Värdeintervallet i det här fältet tillåter specifikation av den bredaste pixeln på 4:1 till den högsta pixeln på 1:4 i steg om 1/64:e. Värden : 0 - Ingen information om bildförhållande ges.1..255 - Värde som används i beräkningen.

### Se även

* class [GifOptions](../../gifoptions)
* namnutrymme [Aspose.Imaging.ImageOptions](../../gifoptions)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
