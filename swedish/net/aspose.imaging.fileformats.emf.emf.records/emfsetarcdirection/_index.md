---
title: EmfSetArcDirection
second_title: Aspose.Imaging för .NET API-referens
description: EMR_SETARCDIRECTION-posten anger ritriktningen som ska användas för båge- och rektangelutgång.
type: docs
weight: 4270
url: /sv/net/aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/
---
## EmfSetArcDirection class

EMR_SETARCDIRECTION-posten anger ritriktningen som ska användas för båge- och rektangelutgång.

```csharp
public sealed class EmfSetArcDirection : EmfStateRecordType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfSetArcDirection](emfsetarcdirection#constructor)() | Initierar en ny instans av[`EmfSetArcDirection`](../emfsetarcdirection) class. |
| [EmfSetArcDirection](emfsetarcdirection#constructor_1)(EmfRecord) | Initierar en ny instans av[`EmfSetArcDirection`](../emfsetarcdirection) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [ArcDirection](../../aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/arcdirection) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal utan tecken som anger bågriktningen. Värdet MÅSTE finnas i ArcDirection-uppräkningen (avsnitt 2.1.2). Standardriktningen är moturs. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Hämtar eller ställer in storleken på posten |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Hämtar eller ställer in typen. |

### Anmärkningar

EMR_SETARCDIRECTION-posten påverkar i vilken riktning följande poster ritar: - EMR_ARC (avsnitt 2.3.5.2) - EMR_ARCTO (avsnitt 2.3.5.3) - EMR_2.0sektion.5.5.0.5.0.5.0.5.5.5.5.5.5.5 (avsnitt 2.3.5.3) - EMR_PIE (avsnitt 2.3.5.15) - EMR_RECTANGLE (avsnitt 2.3.5.34) - EMR_ROUNDRECT (avsnitt 2.3.5.35)

### Se även

* class [EmfStateRecordType](../emfstaterecordtype)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->