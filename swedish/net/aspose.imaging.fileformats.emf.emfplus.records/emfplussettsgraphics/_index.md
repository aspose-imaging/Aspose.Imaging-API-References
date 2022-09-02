---
title: EmfPlusSetTsGraphics
second_title: Aspose.Imaging för .NET API-referens
description: EmfPlusSetTSGraphics-posten anger tillståndet för en grafikenhetskontext för en terminalserver.
type: docs
weight: 6410
url: /sv/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---
## EmfPlusSetTsGraphics class

EmfPlusSetTSGraphics-posten anger tillståndet för en grafikenhetskontext för en terminalserver.

```csharp
public sealed class EmfPlusSetTsGraphics : EmfPlusTerminalServerRecordType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfPlusSetTsGraphics](emfplussettsgraphics)(EmfPlusRecord) | Initierar en ny instans av[`EmfPlusSetTsGraphics`](../emfplussettsgraphics) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AntiAliasMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/antialiasmode) { get; set; } | Hämtar eller ställer in ett 8-bitars osignerat heltal som anger kvaliteten på linjerenderingen, inklusive typen av linjekantutjämning. Det MÅSTE definieras i SmoothingMode uppräkningen (avsnitt 2.1.1.28). |
| [BasicVgaColors](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/basicvgacolors) { get; } | Får ett värde som anger om [grundläggande vga-färger]. Om det är inställt innehåller paletten endast de grundläggande VGA-färgerna. |
| [CompositingMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/compositingmode) { get; set; } | Hämtar eller ställer in ett 8-bitars osignerat heltal som anger hur källfärger kombineras med bakgrundsfärger. Det MÅSTE vara ett värde i CompositingMode uppräkningen (avsnitt 2.1.1.5). |
| [CompositingQuality](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/compositingquality) { get; set; } | Hämtar eller ställer in ett 8-bitars heltal utan tecken som anger graden av utjämning som ska tillämpas på linjer, kurvor och kanterna på fyllda områden för att få dem att se mer kontinuerliga eller skarpt definierade. Det MÅSTE vara ett värde i CompositingQuality-uppräkningen (avsnitt 2.1.1.6). |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars-justerade antalet byte med data i RecordData-fältet som följer. Detta nummer inkluderar inte posthuvudet på 12 byte. |
| [FilterType](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/filtertype) { get; set; } | Hämtar eller ställer in ett 8-bitars osignerat heltal som anger hur skalning, inklusive stretching och krympning, utförs. Det MÅSTE vara ett värde i FilterType-uppräkningen (avsnitt 2.1.1.11). |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Hämtar eller ställer in ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur operationen ska utföras och om postens struktur. |
| [HavePalette](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/havepalette) { get; } | Får ett värde som indikerar om [har palett]. Om denna post har angetts innehåller denna post ett EmfPlusPalette-objekt (avsnitt 2.2.2.28) i fältet Palette efter grafiktillståndsdata. |
| [Palette](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/palette) { get; set; } | Hämtar eller ställer in ett valfritt EmfPlusPalette-objekt. |
| [PixelOffset](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/pixeloffset) { get; set; } | Hämtar eller ställer in ett 8-bitars osignerat heltal som anger den övergripande kvaliteten på image och textrenderingsprocessen. Det MÅSTE vara ett värde i PixelOffsetMode-uppräkningen (avsnitt 2.1.1.26). |
| [RenderOriginX](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/renderoriginx) { get; set; } | Hämtar eller ställer in ett 16-bitars heltal med tecken, vilket är den horisontella koordinaten för ursprunget för att rendera halvtons- och rastermatriser. |
| [RenderOriginY](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/renderoriginy) { get; set; } | Hämtar eller ställer in ett 16-bitars heltal med tecken, vilket är den vertikala koordinaten för origin för rendering av halvtons- och rastermatriser. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger det 32-bitars justerade antalet bytes i hela posten, inklusive 12-byte posthuvudet och postspecifika data. |
| [TextContrast](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/textcontrast) { get; set; } | Hämtar eller ställer in ett 16-bitars osignerat heltal som anger gammakorrigeringsvärdet som används för att rendera kantutjämnad och ClearType-text. Detta värde MÅSTE vara i intervallet 0 till 12, inklusive. |
| [TextRenderHint](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/textrenderhint) { get; set; } | Hämtar eller ställer in ett 8-bitars osignerat heltal som anger kvaliteten på text -rendering, inklusive typen av textkantutjämning. Det MÅSTE definieras i TextRenderingHint-uppräkningen (avsnitt 2.1.1.32). |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Får ett 16-bitars osignerat heltal som identifierar posttypen. |
| [WorldToDevice](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/worldtodevice) { get; set; } | Hämtar eller ställer in ett 192-bitars EmfPlusTransformMatrix-objekt (avsnitt 2.2.2.47) som specificerar världsutrymmet till enhetsutrymmestransformationer. |

### Se även

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
