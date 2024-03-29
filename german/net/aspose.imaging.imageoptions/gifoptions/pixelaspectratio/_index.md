---
title: PixelAspectRatio
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ruft das GIF-Pixel-Seitenverhältnis ab oder legt es fest.
type: docs
weight: 120
url: /de/net/aspose.imaging.imageoptions/gifoptions/pixelaspectratio/
---
## GifOptions.PixelAspectRatio property

Ruft das GIF-Pixel-Seitenverhältnis ab oder legt es fest.

```csharp
public byte PixelAspectRatio { get; set; }
```

### Eigentumswert

Das GIF-Pixel-Seitenverhältnis.

### Bemerkungen

Pixel-Seitenverhältnis - Faktor, der verwendet wird, um eine Annäherung des Seitenverhältnisses des Pixels im Originalbild zu berechnen. Wenn der Wert des Felds nicht 0 ist, wird diese Annäherung des Seitenverhältnisses basierend auf der Formel berechnet: Seitenverhältnis = (Pixel-Seitenverhältnis + 15) / 64 Das Pixel-Seitenverhältnis ist definiert als der Quotient des Pixels. s Breite über seine Höhe. Der Wertebereich in diesem Feld erlaubt die Angabe vom breitesten Pixel von 4:1 bis zum höchsten Pixel von 1:4 in 1/64-Schritten. Werte : 0 - Es wird keine Angabe des Seitenverhältnisses gemacht. 1..255 - Bei der Berechnung verwendeter Wert.

### Siehe auch

* class [GifOptions](../../gifoptions)
* namensraum [Aspose.Imaging.ImageOptions](../../gifoptions)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
