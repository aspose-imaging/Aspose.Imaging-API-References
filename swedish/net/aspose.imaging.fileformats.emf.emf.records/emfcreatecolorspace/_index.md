---
title: EmfCreateColorSpace
second_title: Aspose.Imaging för .NET API-referens
description: EMR_CREATECOLORSPACE-posten skapar ett logiskt färgrymdsobjekt från en färgprofil med ett -namn som består av ASCII-tecken.
type: docs
weight: 3470
url: /sv/net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/
---
## EmfCreateColorSpace class

EMR_CREATECOLORSPACE-posten skapar ett logiskt färgrymdsobjekt från en färgprofil med ett -namn som består av ASCII-tecken.

```csharp
public sealed class EmfCreateColorSpace : EmfObjectCreationRecordType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfCreateColorSpace](emfcreatecolorspace)(EmfRecord) | Initierar en ny instans av[`EmfCreateColorSpace`](../emfcreatecolorspace) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [IhCS](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/ihcs) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger indexet för det logiska färgrymdsobjektet i EMF-objekttabellen (avsnitt 3.1.1.1). Detta index MÅSTE sparas så att detta objekt kan återanvändas eller modifieras. |
| [Lcs](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/lcs) { get; set; } | Hämtar eller ställer in ett WMF LogColorSpace-objekt ([MS-WMF] avsnitt 2.2.2.11), som kan specificera namnet på en färgprofil i ASCII-tecken. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Hämtar eller ställer in storleken på posten |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Hämtar eller ställer in typen. |

### Anmärkningar

Det logiska färgrymdsobjektet som definieras av denna post kan väljas i uppspelningsenheten context av en EMR_SETCOLORSPACE-post (avsnitt 2.3.8.7), som definierar den logiska färgrymd som ska användas i efterföljande grafikoperationer.

### Se även

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
