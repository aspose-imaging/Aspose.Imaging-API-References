---
title: EmfPlusColorCurveEffect
second_title: Aspose.Imaging för .NET API-referens
description: ColorCurveEffect-objektet anger en av åtta justeringar av färgkurvan för en bild.
type: docs
weight: 5300
url: /sv/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/
---
## EmfPlusColorCurveEffect class

ColorCurveEffect-objektet anger en av åtta justeringar av färgkurvan för en bild.

```csharp
public sealed class EmfPlusColorCurveEffect : EmfPlusImageEffectsObjectType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfPlusColorCurveEffect](emfpluscolorcurveeffect)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AdjustmentIntensity](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/adjustmentintensity) { get; set; } | Hämtar eller ställer in ett 32-bitars signerat heltal som anger intensiteten för kurvjusteringen av till färgkanalen som specificeras av CurveChannel. Områdena för meningsfulla värden för detta fält varierar beroende på CurveAdjustment-värdet, enligt följande: Exponeringsjusteringsområde: -255 ≤ värde &lt; 0 När värdet minskar SKA bildens exponering minska. 0 anger ett värde på 0 att exponeringen INTE FÅR ändras. 0 &lt; värde ≤ 255 När värdet ökar, SKA bildens exponering öka. Densitetsjusteringsområde: -255 ≤ värde &lt; 0 När värdet minskar, SKA bildens densitet minska , vilket resulterar i en mörkare bild. 0 Ett värde på 0 anger att densiteten INTE FÅR ändras. 0 &lt; värde ≤ 255 När värdet ökar, SKA bildens densitet öka. &lt; 0 När värdet minskar, SKA bildens kontrast minska. 0 Ett värde på 0 anger att kontrasten INTE FÅR ändras. 0 &lt; värde ≤ 100 När värdet ökar, SKA bildens kontrast öka. e. Justeringsområde för högdagrar: -100 ≤ värde &lt; 0 När värdet minskar SKA bildens ljusa områden verka mörkare. 0 Ett värde på 0 anger att markeringen INTE FÅR ändras. 0 &lt; värde ≤ värdet ökar, de ljusa områdena i bilden SKA verka ljusare. Skuggjusteringsområde: -100 ≤ värde &lt; 0 När värdet minskar SKA de mörka områdena i bilden verka mörkare. 0 Ett värde på 0 anger att skugga FÅR INTE ändras. 0 &lt; värde ≤ 100 När värdet ökar, SKA de mörka områdena i bilden verka ljusare. Justeringsområde för vitmättnad: 0 — 255 När värdet ökar, blir den övre gränsen för färgkanalens omfång. intensiteterna ökar. Justeringsområde för svartmättnad: 0 — 255 När värdet ökar, ökar den nedre gränsen för området för färgkanalintensiteter. |
| [CurveAdjustment](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/curveadjustment) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal utan tecken som specificerar kurvjusteringen till tillämpas på färgerna i bitmapp. Detta värde MÅSTE definieras i CurveAdjustments uppräkningen (avsnitt 2.1.1.7). |
| [CurveChannel](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/curvechannel) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal utan tecken som anger färgkanalen till vilken kurvjusteringen gäller. Detta värde MÅSTE definieras i CurveChannel uppräkningen (avsnitt 2.1.1.8). |

### Se även

* class [EmfPlusImageEffectsObjectType](../emfplusimageeffectsobjecttype)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
