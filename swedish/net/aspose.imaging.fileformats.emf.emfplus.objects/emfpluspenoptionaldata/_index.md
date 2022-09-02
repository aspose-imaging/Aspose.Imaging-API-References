---
title: EmfPlusPenOptionalData
second_title: Aspose.Imaging för .NET API-referens
description: EmfPlusPenOptionalData-objektet anger valfria data för en grafikpenna
type: docs
weight: 5680
url: /sv/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/
---
## EmfPlusPenOptionalData class

EmfPlusPenOptionalData-objektet anger valfria data för en grafikpenna

```csharp
public sealed class EmfPlusPenOptionalData : EmfPlusStructureObjectType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfPlusPenOptionalData](emfpluspenoptionaldata)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [CompoundLineData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/compoundlinedata) { get; set; } | Hämtar eller ställer in valfritt EmfPlusCompoundLineData-objekt (avsnitt 2.2.2.9) som specificerar en matris med flyttalsvärden som definierar den sammansatta linjen i en penna, som består av parallella linjer Det här fältet MÅSTE finnas om flaggan PenDataCompoundLine är inställd i fältet PenDataFlags i EmfPlusPenData-objektet |
| [CustomEndCapData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/customendcapdata) { get; set; } | Hämtar eller ställer in valfritt EmfPlusCustomEndCapData-objekt (avsnitt 2.2.2.11) som definierar den anpassade ändlocksformen, vilket är formen att använda i slutet av en linje som ritas med denna penna. Det kan vara vilken som helst av olika former, till exempel en kvadrat, cirkel eller diamant. Detta -fält MÅSTE finnas om PenDataCustomEndCap-flaggan är satt i PenDataFlags-fältet i EmfPlusPenData object |
| [CustomStartCapData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/customstartcapdata) { get; set; } | Hämtar eller ställer in valfritt EmfPlusCustomStartCapData-objekt (avsnitt 2.2.2.15) som definierar den anpassade start-cap-formen, vilket är formen att använda i början av en linje som ritas med denna penna. Det kan vara vilken som helst av olika former, till exempel en kvadrat, cirkel eller diamant. Det här fältet MÅSTE finnas om PenDataCustomStartCap-flaggan är inställd i fältet PenDataFlags i EmfPlusPenData object |
| [DashedLineCapType](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashedlinecaptype) { get; set; } | Hämtar eller ställer in valfritt 32-bitars heltal med tecken som anger formen för båda ändarna av varje streck i en streckad linje. Det här fältet MÅSTE vara närvarande om PenDataDashedLineCap-flaggan är inställd i fältet PenDataFlags i EmfPlusPenData-objektet, och värdet MÅSTE definieras i DashedLineCapType-uppräkningen _._x0002d_._1d.x0002d. |
| [DashedLineData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashedlinedata) { get; set; } | Hämtar eller ställer in valfritt EmfPlusDashedLineData-objekt (avsnitt 2.2.2.16) som anger längden på streck och mellanslag i en anpassad streckad linje. Det här fältet MÅSTE finnas om flaggan PenDataDashedLine är inställd i fältet PenDataFlags för objektet EmfPlusPenData . |
| [DashOffset](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashoffset) { get; set; } | Hämtar eller ställer in valfritt 32-bitars flyttalsvärde som specificerar avståndet från början av en linje till början av det första utrymmet i ett streckat linjemönster. Det här fältet MÅSTE vara närvarande om flaggan PenDataDashedLineOffset är inställd i fältet PenDataFlags för objektet EmfPlusPenData. |
| [EndCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/endcap) { get; set; } | Hämtar eller ställer in valfritt 32-bitars heltal med tecken som anger shape för slutet av en rad i fältet CustomEndCapData. Detta -fält MÅSTE finnas om PenDataEndCap-flaggan är inställd i fältet PenDataFlags i EmfPlusPenData-objektet och värdet MÅSTE definieras i LineCapType enumeration |
| [Join](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/join) { get; set; } | Hämtar eller ställer in ett valfritt 32-bitars signerat heltal som anger hur man sammanfogar två linjer som ritas av samma penna och vars ändar möts. Det här fältet MÅSTE finnas om PenDataJoin-flaggan är inställd i PenDataFlags-fältet för EmfPlusPenData-objektet, och värdet MÅSTE definieras i LineJoinType-uppräkningen (avsnitt 1.01._d_) |
| [LineStyle](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/linestyle) { get; set; } | Hämtar eller ställer in valfritt 32-bitars heltal med tecken som anger stilen som används för linjer som ritas med detta pennobjekt. Det här fältet MÅSTE finnas om PenDataLineStyle-flaggan är inställd i fältet PenDataFlags i EmfPlusPenData-objektet, och värdet MÅSTE definieras i LineStyle-uppräkningen (sektion 1.00._0.20). |
| [MiterLimit](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/miterlimit) { get; set; } | Hämtar eller ställer in valfritt 32-bitars flyttalsvärde som anger gränsen för miter , vilket är det maximalt tillåtna förhållandet mellan geringslängd och linjebredd. Geringslängden är avståndet från skärningspunkten mellan linjeväggarna på insidan av fogen till skärningspunkten mellan linjeväggarna utanför fogen. Geringslängden kan vara stor när vinkeln mellan två linjer är liten. Detta fält MÅSTE finnas om flaggan PenDataMiterLimit är inställd i fältet PenDataFlags för EmfPlusPenData-objektet. |
| [PenAlignment](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/penalignment) { get; set; } | Hämtar eller ställer in valfritt 32-bitars heltal med tecken som anger -fördelningen av pennans bredd med avseende på -koordinaterna för linjen som ritas. Det här fältet MÅSTE finnas om PenDataNonCenter-flaggan är inställd i fältet PenDataFlags i EmfPlusPenData-objektet, och MÅSTE värdet definieras i PenAlignment uppräkningen (avsnitt 2.01.01._d_2). |
| [StartCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/startcap) { get; set; } | Hämtar eller ställer in ett valfritt 32-bitars heltal med tecken som anger formen för början av en rad i fältet CustomStartCapData. Det här fältet MÅSTE finnas om PenDataStartCap-flaggan är satt i PenDataFlags-fältet i EmfPlusPenData-objektet, och värdet MÅSTE definieras i LineCapType-uppräkningen (sektion 1.08._0). |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/transformmatrix) { get; set; } | Hämtar eller ställer in ett valfritt EmfPlusTransformMatrix-objekt (avsnitt 2.2.2.47) som anger en transformation av världsutrymme till enhetsutrymme för pennan. Detta fält MÅSTE finnas om flaggan PenDataTransform är inställd i fältet PenDataFlags i EmfPlusPenData -objektet. |

### Se även

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
