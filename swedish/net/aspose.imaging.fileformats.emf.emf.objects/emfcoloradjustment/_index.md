---
title: EmfColorAdjustment
second_title: Aspose.Imaging för .NET API-referens
description: ColorAdjustment-objektet definierar värden för justering av färgerna i källbitmappar i bitblocksöverföringar.
type: docs
weight: 2930
url: /sv/net/aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/
---
## EmfColorAdjustment class

ColorAdjustment-objektet definierar värden för justering av färgerna i källbitmappar i bitblocksöverföringar.

```csharp
public sealed class EmfColorAdjustment : EmfObject
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfColorAdjustment](emfcoloradjustment)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BlueGamma](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/bluegamma) { get; set; } | Hämtar eller ställer in ett 16-bitars osignerat heltal som specificerar n:te potensens gammakorrigeringsvärde för blå primära av källfärgerna. Detta värde BÖR ligga i intervallet från 2 500 till 65 000. Ett värde på 10 000 betyder att gammakorrigering INTE FÅR utföras. |
| [Brightness](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/brightness) { get; set; } | Hämtar eller ställer in ett 16-bitars signerat heltal som anger mängden ljusstyrka som ska tillämpas på källobjektet. Detta värde BÖR ligga i intervallet från –100 till 100. Ett värde på noll betyder att ljusstyrkan INTE FÅR utföras. |
| [Colorfullness](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/colorfullness) { get; set; } | Hämtar eller ställer in ett 16-bitars signerat heltal som anger mängden färgstarkhet som ska tillämpas på källobjektet. Det här värdet BÖR ligga i intervallet från –100 till 100. Ett värde på noll betyder att färgriktighetsjustering INTE FÅR utföras |
| [Contrast](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/contrast) { get; set; } | Hämtar eller ställer in ett 16-bitars signerat heltal som anger mängden kontrast som ska tillämpas på källobjektet. Detta värde BÖR ligga i intervallet från –100 till 100. Ett värde på noll betyder att kontrastjustering INTE FÅR utföras. |
| [GreenGamma](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/greengamma) { get; set; } | Hämtar eller ställer in ett 16-bitars osignerat heltal som anger det n:te potensens gammakorrigeringsvärde för den gröna primära av källfärgerna. Detta värde BÖR ligga i intervallet från 2 500 till 65 000. Ett värde på 10 000 betyder att gammakorrigering INTE FÅR utföras. |
| [IlluminantIndex](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/illuminantindex) { get; set; } | Hämtar eller ställer in ett 16-bitars osignerat heltal som anger typen av standardljuskälla under vilken -bilden visas, från uppräkningen av belysningskällor (avsnitt 2.1.19). |
| [RedGamma](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/redgamma) { get; set; } | Hämtar eller ställer in ett 16-bitars heltal utan tecken som anger det n:te potensens gammakorrigeringsvärde för den röda primära av källfärgerna. Detta värde BÖR ligga i intervallet från 2 500 till 65 000. Ett värde på 10 000 betyder att gammakorrigering INTE FÅR utföras. |
| [RedGreenTint](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/redgreentint) { get; set; } | Hämtar eller ställer in 16-bitars signerat heltal som anger mängden röd eller grön nyansjustering som ska tillämpas på källobjektet. Detta värde BÖR ligga i intervallet från –100 till 100. Positiva tal justeras mot rött och negativa tal justerar mot grönt. Ett värde på noll betyder att nyansjustering INTE FÅR utföras |
| [ReferenceBlack](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/referenceblack) { get; set; } | Hämtar eller ställer in ett 16-bitars osignerat heltal som anger den svarta referensen för källfärgerna. Alla färger som är mörkare än detta behandlas som svarta. Detta värde BÖR ligga i intervallet från noll till 4 000 |
| [ReferenceWhite](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/referencewhite) { get; set; } | Hämtar eller ställer in ett 16-bitars osignerat heltal som anger den vita referensen för källfärgerna. Alla färger som är ljusare än detta behandlas som vita. Detta värde BÖR ligga i intervallet från 6 000 till 10 000. |
| [Size](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/size) { get; set; } | Hämtar eller ställer in ett 16-bitars osignerat heltal som anger storleken i byte för detta objekt. Detta MÅSTE vara 0x0018. |
| [Values](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/values) { get; set; } | Hämtar eller ställer in ett 16-bitars osignerat heltal som anger hur utdatabilden ska förberedas. Detta fält kan sättas till NULL eller till valfri kombination av värden i ColorAdjustment-uppräkningen (avsnitt 2.1.5). |

### Se även

* class [EmfObject](../emfobject)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
