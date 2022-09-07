---
title: EmfPlusDrawImagePoints
second_title: Aspose.Imaging för .NET API-referens
description: EmfPlusDrawImagePoints-posten anger att man ritar en skalad bild inuti ett parallellogram.
type: docs
weight: 5970
url: /sv/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/
---
## EmfPlusDrawImagePoints class

EmfPlusDrawImagePoints-posten anger att man ritar en skalad bild inuti ett parallellogram.

```csharp
public sealed class EmfPlusDrawImagePoints : EmfPlusDrawingRecordType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfPlusDrawImagePoints](emfplusdrawimagepoints)(EmfPlusRecord) | Initierar en ny instans av[`EmfPlusDrawImagePoints`](../emfplusdrawimagepoints) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [ApplyingAnEffect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/applyinganeffect) { get; set; } | Hämtar eller ställer in ett värde som indikerar om [tillämpar en effekt]. Den här biten indikerar att renderingen av bilden inkluderar applicering av en effekt. Om angivet MÅSTE ett objekt av klassen Effect ha specificerats i en tidigare EmfPlusSerializableObject-post ( 2.3.5.2). |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/compressed) { get; set; } | Hämtar eller ställer in ett värde som indikerar om PointData är komprimerad. Denna bit indikerar om PointData-fältet specificerar komprimerad data. Om angivet, anger PointData absoluta platser i koordinatutrymmet med 16-bitars heltal coordinates. Om den är ren, specificerar PointData absoluta platser i koordinatutrymmet med 32-bitars flyttalskoordinater. Obs! Om P-flaggan (nedan) är inställd är denna flagga odefinierad och MÅSTE ignoreras. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars-justerade antalet byte med data i RecordData-fältet som följer. Detta nummer inkluderar inte posthuvudet på 12 byte. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Hämtar eller ställer in ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur operationen ska utföras och om postens struktur. |
| [ImageAttributesId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/imageattributesid) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som innehåller indexet för det valfria EmfPlusImageAttributes-objektet (avsnitt 2.2.1.5) i EMF+-objekttabellen. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/objectid) { get; set; } | Hämtar eller ställer in objektidentifieraren. Indexet för ett EmfPlusImage-objekt (avsnitt 2.2.1.4) i objekttabellen EMF+ , som anger bilden som ska renderas. Värdet MÅSTE vara noll till 63, inklusive. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/pointdata) { get; set; } | Hämtar eller ställer in en matris med Räknepunkter som anger tre punkter i ett parallellogram. De tre punkterna representerar de övre vänstra, övre högra och nedre vänstra hörnen av parallellogrammet. Den fjärde punkten i parallellogrammet extrapoleras från de tre första. Den delen av bilden som specificeras av SrcRect-fältet SKA ha skalning och shearing omvandlingar tillämpas om det behövs för att passa inuti parallellogrammet. |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/relative) { get; set; } | Hämtar eller ställer in ett värde som indikerar om detta[`EmfPlusDrawImagePoints`](../emfplusdrawimagepoints)is relative. Den här biten indikerar om PointData-fältet specificerar relativa eller absoluta platser. Om satt, specificerar varje element i PointData en plats i koordinatutrymmet som är relativt den plats som specificerats av det föregående elementet i arrayen. I fallet med första elementet i PointData antas en tidigare plats vid koordinater (0,0). Om den är klar, anger PointData absoluta platser enligt C-flaggan. Obs Om denna flagga är inställd är C-flaggan (ovan) odefinierad och MÅSTE ignoreras. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger det 32-bitars justerade antalet bytes i hela posten, inklusive 12-byte posthuvudet och postspecifika data. |
| [SrcRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/srcrect) { get; set; } | Hämtar eller ställer in ett EmfPlusRectF-objekt (avsnitt 2.2.2.39) som definierar en del av bilden som ska renderas. |
| [SrcUnit](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/srcunit) { get; set; } | Hämtar eller ställer in ett 32-bitars signerat heltal som definierar enheterna i SrcRect-fältet. Det MÅSTE vara UnitPixel-värdet för UnitType-uppräkningen (avsnitt 2.1.1.33). |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Får ett 16-bitars osignerat heltal som identifierar posttypen. |

### Anmärkningar

En EmfPlusImage kan ange antingen en bitmapp eller metafil. Färger i en bild kan manipuleras under rendering. De kan korrigeras, mörkas, ljusare och tas bort.

### Se även

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
