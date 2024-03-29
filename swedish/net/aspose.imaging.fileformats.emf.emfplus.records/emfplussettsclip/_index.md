---
title: EmfPlusSetTsClip
second_title: Aspose.Imaging för .NET API-referens
description: EmfPlusSetTSClip-posten specificerar klippområden i grafikenhetskontexten för en terminalserver.
type: docs
weight: 6400
url: /sv/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/
---
## EmfPlusSetTsClip class

EmfPlusSetTSClip-posten specificerar klippområden i grafikenhetskontexten för en terminalserver.

```csharp
public sealed class EmfPlusSetTsClip : EmfPlusTerminalServerRecordType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfPlusSetTsClip](emfplussettsclip)(EmfPlusRecord) | Initierar en ny instans av[`EmfPlusSetTsClip`](../emfplussettsclip) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/compressed) { get; } | Får ett värde som indikerar om detta[`EmfPlusSetTsClip`](../emfplussettsclip)är komprimerad. Denna bit specificerar formatet för rektangeldata i rects-fältet. Om inställt, definieras varje rektangel i 4 byte. Om den är ren, definieras varje rektangel i 8 bytes. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars-justerade antalet byte med data i RecordData-fältet som följer. Detta nummer inkluderar inte posthuvudet på 12 byte. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Hämtar eller ställer in ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur operationen ska utföras och om postens struktur. |
| [NumRects](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/numrects) { get; } | Hämtar antalet rects. Det här fältet anger antalet rektanglar som är definierade i rect-fältet. |
| [Rects](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/rects) { get; set; } | Hämtar eller ställer in en array av NumRects-rektanglar som definierar klippområden. Formatet för denna data bestäms av C-biten i fältet Flaggor. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger det 32-bitars justerade antalet bytes i hela posten, inklusive 12-byte posthuvudet och postspecifika data. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Får ett 16-bitars osignerat heltal som identifierar posttypen. |

### Anmärkningar

Komprimeringsschemat för data i denna post använder följande algoritm. Varje punkt i each rektangel är kodad i antingen en enda byte eller 2 byte. Om punkten är kodad i en enda byte, MÅSTE bytens high bit (0x80) ställas in, och värdet är ett tecken med tecken som representeras av de lägre 7 bitarna. Om den höga biten inte är inställd kodas värdet i 2 byte, med högordningens byte kodad i de 7 lägre bitarna i den första byten, och lågordningens bytevärde kodas i den andra byten. Varje punkt är kodad som skillnaden mellan punkten i den aktuella raden och punkten i den föregående raden. Den nedre punkten av rekt är kodad som skillnaden mellan bottom koordinaten och den övre koordinaten på den aktuella rect.

### Se även

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
