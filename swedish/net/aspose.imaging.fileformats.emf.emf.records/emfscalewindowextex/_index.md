---
title: EmfScaleWindowExtex
second_title: Aspose.Imaging för .NET API-referens
description: EMR_SCALEWINDOWEXTEX-posten specificerar fönstret för en uppspelningsenhetskontext med med hjälp av förhållanden som bildas av de angivna multiplikanderna och divisorerna.
type: docs
weight: 4230
url: /sv/net/aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/
---
## EmfScaleWindowExtex class

EMR_SCALEWINDOWEXTEX-posten specificerar fönstret för en uppspelningsenhetskontext med med hjälp av förhållanden som bildas av de angivna multiplikanderna och divisorerna.

```csharp
public sealed class EmfScaleWindowExtex : EmfStateRecordType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfScaleWindowExtex](emfscalewindowextex#constructor)() | Initierar en ny instans av[`EmfScaleWindowExtex`](../emfscalewindowextex) class. |
| [EmfScaleWindowExtex](emfscalewindowextex#constructor_1)(EmfRecord) | Initierar en ny instans av[`EmfScaleWindowExtex`](../emfscalewindowextex) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Hämtar eller ställer in storleken på posten |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Hämtar eller ställer in typen. |
| [XDenom](../../aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/xdenom) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal med tecken som anger den horisontella divisorn. FÅR INTE vara noll. |
| [XNum](../../aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/xnum) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal med tecken som anger den horisontella multiplikanden. FÅR INTE vara noll. |
| [YDenom](../../aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/ydenom) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal med tecken som anger den vertikala divisorn. FÅR INTE vara noll. |
| [YNum](../../aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/ynum) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal med tecken som anger den vertikala multiplikanten. FÅR INTE vara noll. |

### Anmärkningar

Omfattningen kan inte ändras om enhetskontexten använder ett fast skala mappningsläge. Only MM_ISOTROPIC och MM_ANISOTROPIC är inte fasta skalor. Fönsterutsträckningarna är ändras enligt följande. xNewWE = (xOldWE * xNum) / xDenom yNewWE = (yOldWE * yNum) / yDenom

### Se även

* class [EmfStateRecordType](../emfstaterecordtype)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->