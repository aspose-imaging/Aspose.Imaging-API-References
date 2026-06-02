---
title: "EmfPlusColorCurveEffect klass"
type: docs
weight: 180
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/
---

**Summary:** The ColorCurveEffect object specifies one of eight adjustments to the color curve of an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusColorCurveEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusColorCurveEffect()](#EmfPlusColorCurveEffect__1) | Initierar en ny instans av EmfPlusColorCurveEffect-klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| adjustment_intensity | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar intensiteten för<br/>            kurvjusteringen av färgkanalen som anges av CurveChannel. De meningsfulla<br/>            värdeintervallen för detta fält varierar beroende på CurveAdjustment-värdet, enligt följande:<br/>            Exponeringsjusteringsintervall:<br/>            -255 ≤ value < 0 När värdet minskar bör exponeringen av bilden minska.<br/>            0 Ett värde på 0 specificerar att exponeringen INTE får förändras.<br/>            0 < value ≤ 255 När värdet ökar bör exponeringen av bilden öka.<br/>            Densitetsjusteringsintervall:<br/>            -255 ≤ value < 0<br/>            När värdet minskar bör densiteten i bilden minska, vilket resulterar i<br/>            en mörkare bild.<br/>            0 Ett värde på 0 specificerar att densiteten INTE får förändras.<br/>            0 < value ≤ 255<br/>            När värdet ökar bör densiteten i bilden öka.<br/>            Kontrastjusteringsintervall:<br/>            -100 ≤ value < 0 När värdet minskar bör kontrasten i bilden minska.<br/>            0 Ett värde på 0 specificerar att kontrasten INTE får förändras.<br/>            0 < value ≤ 100 När värdet ökar bör kontrasten i bilden öka.<br/>            Högdagrsjusteringsintervall:<br/>            -100 ≤ value < 0 När värdet minskar bör de ljusa områdena i bilden framstå mörkare.<br/>            0 Ett värde på 0 specificerar att högdagrar INTE får förändras.<br/>            0 < value ≤ 100 När värdet ökar bör de ljusa områdena i bilden framstå ljusare.<br/>            Skuggjusteringsintervall:<br/>            -100 ≤ value < 0 När värdet minskar bör de mörka områdena i bilden framstå mörkare.<br/>            0 Ett värde på 0 specificerar att skuggor INTE får förändras.<br/>            0 < value ≤ 100 När värdet ökar bör de mörka områdena i bilden framstå ljusare.<br/>            Vit mättnadsjusteringsintervall:<br/>            0 — 255 När värdet ökar ökar den övre gränsen för intervallet av färgkanalintensiteter.<br/>            Svart mättnadsjusteringsintervall:<br/>            0 — 255 När värdet ökar ökar den nedre gränsen för intervallet av färgkanalintensiteter. |
| curve_adjustment | [EmfPlusCurveAdjustments](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscurveadjustments/) | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar kurvjusteringen som<br/>            ska tillämpas på färgerna i bitmap. Detta värde MÅSTE definieras i CurveAdjustments<br/>            uppräkning (avsnitt 2.1.1.7). |
| curve_channel | [EmfPlusCurveChannel](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscurvechannel/) | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar färgkanalen som<br/>            kurvjusteringen gäller för. Detta värde MÅSTE definieras i CurveChannel<br/>            uppräkning (avsnitt 2.1.1.8). |


### Constructor: EmfPlusColorCurveEffect() {#EmfPlusColorCurveEffect__1}


```
 EmfPlusColorCurveEffect() 
```

Initierar en ny instans av EmfPlusColorCurveEffect-klassen

