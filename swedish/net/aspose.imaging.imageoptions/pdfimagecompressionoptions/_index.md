---
title: PdfImageCompressionOptions
second_title: Aspose.Imaging för .NET API-referens
description: Pdf-bildkomprimeringsalternativ
type: docs
weight: 10100
url: /sv/net/aspose.imaging.imageoptions/pdfimagecompressionoptions/
---
## PdfImageCompressionOptions enumeration

Pdf-bildkomprimeringsalternativ

```csharp
public enum PdfImageCompressionOptions
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| Auto | `0` | Väljer automatiskt den lämpligaste komprimeringen för varje bild. |
| None | `1` | Sparar råa bildbytes vilket resulterar i större pdf-filstorlekar. |
| Rle | `2` | Run Length-komprimering. |
| Flate | `3` | Flate compression. |
| LzwBaselinePredictor | `4` | Prediktorval är begränsat till PNG Paeth-prediktor för att påskynda processen. I praktiken presterar förvånansvärt bra. Bättre änLzwOptimizedPredictor . |
| LzwOptimizedPredictor | `5` | Val av prediktor är mer komplicerat och bör resultera i mindre bildstorlekar men tar längre tid. RFC 2083 säger att det är den bästa vägen att gå. Men på testdatabaslinjen predictor LzwBaselinePredictor kickar ass och lämnar en optimerad prediktor som med 25-40 % komprimeringshastighetsökning. |
| Jpeg | `6` | Jpeg-komprimering. Stöder inte transparens. |
| Ccitt3 | `7` | /CCITTFaxDecode/DecodeParms/K 0/Kolumner 173 Stöder inte transparens. |
| Ccitt4 | `8` | /CCITTFaxDecode/DecodeParms/K -1/Kolumner 173 Stöder inte transparens. |

### Se även

* namnutrymme [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->