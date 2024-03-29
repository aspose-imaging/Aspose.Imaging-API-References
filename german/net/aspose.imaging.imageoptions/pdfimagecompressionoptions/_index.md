---
title: PdfImageCompressionOptions
second_title: Aspose.Imaging für .NET-API-Referenz
description: Komprimierungsoptionen für PDF-Bilder
type: docs
weight: 10100
url: /de/net/aspose.imaging.imageoptions/pdfimagecompressionoptions/
---
## PdfImageCompressionOptions enumeration

Komprimierungsoptionen für PDF-Bilder

```csharp
public enum PdfImageCompressionOptions
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Auto | `0` | Wählt automatisch die am besten geeignete Komprimierung für jedes Bild aus. |
| None | `1` | Speichert Rohbild-Bytes, was zu größeren PDF-Dateigrößen führt. |
| Rle | `2` | Komprimierung der Lauflänge. |
| Flate | `3` | Flate-Komprimierung. |
| LzwBaselinePredictor | `4` | Die Prädiktorauswahl ist auf den PNG-Paeth-Prädiktor beschränkt, um den Prozess zu beschleunigen. In der Praxis schneidet überraschend gut ab. Besser alsLzwOptimizedPredictor . |
| LzwOptimizedPredictor | `5` | Die Auswahl des Prädiktors ist komplizierter und sollte zu kleineren Bildgrößen führen, aber nimmt mehr Zeit in Anspruch. RFC 2083 sagt, dass dies der beste Weg ist. Aber auf der Basislinie der Testdaten.LzwBaselinePredictor Kicks ass wenn man den optimierten Prädiktor hinter zurücklässt um 25-40% Kompressionsratengewinne. |
| Jpeg | `6` | JPEG-Komprimierung. Unterstützt keine Transparenz. |
| Ccitt3 | `7` | /CCITTFaxDecode/DecodeParms/K 0/Columns 173 Unterstützt keine Transparenz. |
| Ccitt4 | `8` | /CCITTFaxDecode/DecodeParms/K -1/Columns 173 Unterstützt keine Transparenz. |

### Siehe auch

* namensraum [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
