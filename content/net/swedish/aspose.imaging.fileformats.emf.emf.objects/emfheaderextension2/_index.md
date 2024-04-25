---
title: EmfHeaderExtension2
second_title: Aspose.Imaging för .NET API-referens
description: HeaderExtension2-objektet definierar det andra tillägget till EMF-metafilhuvudet. Den lägger till förmågan att mäta enhetens ytor i mikrometer vilket förbättrar upplösningen och skalbarheten hos EMF-metafiler.
type: docs
weight: 3000
url: /sv/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension2/
---
## EmfHeaderExtension2 class

HeaderExtension2-objektet definierar det andra tillägget till EMF-metafilhuvudet. Den lägger till förmågan att mäta enhetens ytor i mikrometer, vilket förbättrar upplösningen och skalbarheten hos EMF-metafiler.

```csharp
public sealed class EmfHeaderExtension2 : EmfHeaderObject
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfHeaderExtension2](emfheaderextension2)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/bounds) { get; set; } | Hämtar eller ställer in ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar de rektangulära inkluderande-inkluderande -gränserna i enhetsenheter för den minsta rektangeln som kan ritas runt bilden som är lagrad i x_ the met00d_ |
| [Bytes](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/bytes) { get; set; } | Hämtar eller ställer in 32-bitars osignerat heltal som anger storleken på metafilen, i bytes. |
| [Device](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/device) { get; set; } | Hämtar eller ställer in ett WMF SizeL-objekt ([MS-WMF] avsnitt 2.2.2.22) som anger storleken på referensenheten, i pixels |
| [Frame](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/frame) { get; set; } | Hämtar eller ställer in ett WMF RectL-objekt som anger de rektangulära inklusive-inkluderande dimensionerna, i 0,01 millimeter enheter, för en rektangel som omger bilden lagrad i metafilen |
| [Handles](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/handles) { get; set; } | Hämtar eller ställer in ett 16-bitars osignerat heltal som anger antalet grafikobjekt som kommer att användas under bearbetningen av metafilen |
| [MicrometersX](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderextension2/micrometersx) { get; set; } | Hämtar eller ställer in den 32-bitars horisontella storleken för visningsenheten för vilken metafilbilden genererades, i mikrometer |
| [MicrometersY](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderextension2/micrometersy) { get; set; } | Hämtar eller ställer in den 32-bitars vertikala storleken på visningsenheten som metafilbilden genererades för, i mikrometer. |
| [Millimeters](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/millimeters) { get; set; } | Hämtar eller ställer in ett WMF SizeL-objekt som anger storleken på referensenheten, i millimeter |
| [NDesription](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/ndesription) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger antalet tecken i arrayen som innehåller beskrivningen av metafilens innehåll. Detta är noll om det inte finns någon beskrivningssträng. |
| [NPalEntries](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/npalentries) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger antalet poster i metafilpaletten . Paletten finns i EMR_EOF record |
| [OffDescription](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/offdescription) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger förskjutningen från början av denna -post till arrayen som innehåller beskrivningen av metafilens innehåll |
| [Records](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/records) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger antalet poster i metafilen |
| [RecordSignature](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/recordsignature) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger postsignaturen. Detta MÅSTE vara ENHMETA_SIGNATURE, från FormatSignature-uppräkningen (avsnitt 2.1.14). |
| [Reserved](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/reserved) { get; set; } | Hämtar eller ställer in ett 16-bitars osignerat heltal som MÅSTE vara 0x0000 och MÅSTE ignoreras |
| [Valid](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/valid) { get; } | Får ett värde som indikerar om detta[`EmfHeaderObject`](../emfheaderobject)är giltig. |
| [Version](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/version) { get; set; } | Hämtar eller ställer in Version (4 byte): Ett 32-bitars osignerat heltal som anger EMF-metafilinteroperabilitet. Detta SKA vara 0x00010000 |

### Se även

* class [EmfHeaderObject](../emfheaderobject)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
