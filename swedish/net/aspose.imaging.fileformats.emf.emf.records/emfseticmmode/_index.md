---
title: EmfSetIcmMode
second_title: Aspose.Imaging för .NET API-referens
description: EMR_SETICMMODE-posten anger läget för bildfärghantering ICM för grafikoperationer.
type: docs
weight: 4340
url: /sv/net/aspose.imaging.fileformats.emf.emf.records/emfseticmmode/
---
## EmfSetIcmMode class

EMR_SETICMMODE-posten anger läget för bildfärghantering (ICM) för grafikoperationer.

```csharp
public sealed class EmfSetIcmMode : EmfStateRecordType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfSetIcmMode](emfseticmmode)(EmfRecord) | Initierar en ny instans av[`EmfSetIcmMode`](../emfseticmmode) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [IcmMode](../../aspose.imaging.fileformats.emf.emf.records/emfseticmmode/icmmode) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger om ICM, ska aktiveras eller inaktiveras från ICMMode-uppräkningen (avsnitt 2.1.18). Detta värde är en del av tillståndet för uppspelningsenhetskontext. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Hämtar eller ställer in storleken på posten |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Hämtar eller ställer in typen. |

### Anmärkningar

När ICM-läget är aktiverat SKA färger som anges i EMF-poster vara färgmatchade, medan standardfärgprofilen i uppspelningsenhetssammanhang SKA användas när en bitblocksöverföring utförs. Om standardfärgprofilen inte önskas, SKA ICM-läget stängas av innan utför bitblocksöverföringen.

### Se även

* class [EmfStateRecordType](../emfstaterecordtype)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->