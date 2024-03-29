---
title: EmfMetafileHeaderExtension1
second_title: Aspose.Imaging för .NET API-referens
description: EmfMetafileHeaderExtension1-posten är rubrikposten som används i det första tillägget till EMF-metafiler. Efter fältet EmfHeaderExtension1 är de återstående fälten valfria och kan finnas i valfri ordning.
type: docs
weight: 3820
url: /sv/net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/
---
## EmfMetafileHeaderExtension1 class

EmfMetafileHeaderExtension1-posten är rubrikposten som används i det första tillägget till EMF-metafiler. Efter fältet EmfHeaderExtension1 är de återstående fälten valfria och kan finnas i valfri ordning.

```csharp
public class EmfMetafileHeaderExtension1 : EmfMetafileHeader
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfMetafileHeaderExtension1](emfmetafileheaderextension1#constructor)(EmfMetafileHeader) | Initierar en ny instans av[`EmfMetafileHeaderExtension1`](../emfmetafileheaderextension1) class. |
| [EmfMetafileHeaderExtension1](emfmetafileheaderextension1#constructor_1)(EmfMetafileHeaderExtension1) | Initierar en ny instans av[`EmfMetafileHeaderExtension1`](../emfmetafileheaderextension1) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [EmfDescription](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfdescription) { get; set; } | Hämtar eller ställer in EMF description En valfri, nollterminerad Unicode UTF16-LE-sträng med godtycklig längd och innehåll. Dess plats i posten och antalet tecken anges av offDescription respektive nDescription-fälten i EmfHeader. Om värdet för något av fälten är noll, finns ingen beskrivningssträng. |
| [EmfDescriptionBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfdescriptionbuffer) { get; set; } | Hämtar eller ställer in EMF-beskrivningen buffer En valfri array av byte som innehåller EMF-beskrivningssträngen, som inte behöver vara sammanhängande med den fasta delen av EmfMetafileHeader -posten. Följaktligen är fältet i denna buffert som är märkt "UndefinedSpace" valfritt och MÅSTE ignoreras. |
| [EmfHeader](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfheader) { get; set; } | Hämtar eller ställer in ett Header-objekt (avsnitt 2.2.9), som innehåller information om content och strukturen för metafilen |
| [EmfHeaderExtension1](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/emfheaderextension1) { get; set; } | Hämtar eller ställer in ett HeaderExtension1-objekt, som anger ytterligare information om bilden i metafilen. |
| [EmfHeaderRecordBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfheaderrecordbuffer) { get; set; } | Hämtar eller ställer in en valfri array av byte som innehåller resten av EMF-rubrikposten. Storleken på detta fält MÅSTE vara en multipel av 4 bytes |
| [EmfPixelFormatBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/emfpixelformatbuffer) { get; set; } | Hämtar eller ställer in en valfri array av byte som innehåller EMF-pixelformatbeskrivningen, som inte krävs för att vara sammanhängande med den fasta delen av EmfMetafileHeaderExtension1-posten eller med EMF beskrivningssträngen. Följaktligen är fältet i denna buffert som är märkt "UndefinedSpace" valfritt och MÅSTE ignoreras |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Hämtar eller ställer in storleken på posten |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Hämtar eller ställer in typen. |

### Se även

* class [EmfMetafileHeader](../emfmetafileheader)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
