---
title: EmfLogPenEx
second_title: Aspose.Imaging för .NET API-referens
description: LogPenEx-objektet anger stil bredd och färg för en utökad logisk penna.
type: docs
weight: 3090
url: /sv/net/aspose.imaging.fileformats.emf.emf.objects/emflogpenex/
---
## EmfLogPenEx class

LogPenEx-objektet anger stil, bredd och färg för en utökad logisk penna.

```csharp
public sealed class EmfLogPenEx : EmfBasePen
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfLogPenEx](emflogpenex)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| override [Argb32ColorRef](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/argb32colorref) { get; set; } | Hämtar eller ställer in ett WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8). Tolkningen av detta -fält beror på BrushStyle-värdet, som visas i tabellen längre fram i detta avsnitt. |
| [BrushDibPattern](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/brushdibpattern) { get; set; } | Hämtar eller ställer in borstmönstret. |
| [BrushHatch](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/brushhatch) { get; set; } | Hämtar eller ställer in mönstret för borstluckan. Definitionen av detta fält beror på BrushStyle-värdet, som visas i tabellen längre fram i detta avsnitt. |
| [BrushStyle](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/brushstyle) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger en penselstil för pennan från WMF BrushStyle-uppräkningen ([MS-WMF] avsnitt 2.1.1.4). Om penntypen i PenStyle-fältet är PS_GEOMETRIC, MÅSTE detta värde vara antingen BS_SOLID eller BS_HATCHED. Värdet på det här fältet kan vara BS_NULL, men bara om linjestilen som anges i PenStyle är PS_NULL. Stilen BS_NULL SKA användas för att ange en pensel som inte har någon effekt. |
| [NumStyleEntities](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/numstyleentities) { get; } | Hämtar antalet element i arrayen som anges i StyleEntry-fältet. Detta värde SKA vara noll om PenStyle inte anger PS_USERSTYLE. |
| override [PenStyle](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/penstyle) { get; set; } | Hämtar eller ställer in pennstilen |
| [StyleEntry](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/styleentry) { get; set; } | Hämtar eller ställer in en valfri matris med 32-bitars heltal utan tecken som definierar längden på streck och luckor i linjen som ritas av denna penna, när värdet på PenStyle är PS_USERSTYLE linjestil för pennan. Arrayen innehåller ett antal -poster specificerade av NumStyleEntries, men den används som om den upprepades i oändlighet Den första posten i arrayen anger längden på det första bindestrecket. Den andra -posten anger längden på det första mellanrummet. Därefter växlar längder av streck och mellanrum. Om penntypen i PenStyle-fältet är PS_GEOMETRIC, anges längderna i logiska enheter; annars anges längderna i enhetsenheter. |
| [Width](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/width) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger bredden på linjen som ritas av pennan. Om penntypen i fältet PenStyle är PS_GEOMETRIC, är detta värde bredden i logiska enheter; annars anges bredden i enhetsenheter. Om penntypen i PenStyle-fältet är PS_COSMETIC, MÅSTE detta värde vara 0x00000001. |

### Se även

* class [EmfBasePen](../emfbasepen)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
