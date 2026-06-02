---
title: "EmfPlusSharpenEffect klass"
type: docs
weight: 630
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplussharpeneffect/
---

**Summary:** The SharpenEffect object specifies an increase in the difference in intensity between pixels in an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusSharpenEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusSharpenEffect()](#EmfPlusSharpenEffect__1) | Initierar en ny instans av klassen EmfPlusSharpenEffect |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| amount | float | r/w | Hämtar eller anger ett 32-bitars flyttal som specificerar skillnaden i intensitet<br/>            mellan en given pixel och de omgivande pixlarna.<br/>            0 Anger att skärpning INTE MÅSTE utföras.<br/>            0 &lt; värde ≤ 100<br/>            När detta värde ökar, bör skillnaden i intensitet mellan pixlarna<br/>            öka. |
| radie | float | r/w | Hämtar eller anger ett 32-bitars flyttal som specificerar skärpningsradien i pixlar,<br/>            vilket bestämmer antalet pixlar som är involverade i beräkningen av det nya värdet för en given pixel.<br/>            När detta värde ökar ökar antalet pixlar som är involverade i beräkningen, och den<br/>            resulterande bitmapen SHOULD bli skarpare. |


### Constructor: EmfPlusSharpenEffect() {#EmfPlusSharpenEffect__1}


```
 EmfPlusSharpenEffect() 
```

Initierar en ny instans av klassen EmfPlusSharpenEffect

