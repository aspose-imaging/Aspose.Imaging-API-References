---
title: "EmfPlusLevelsEffect klass"
type: docs
weight: 420
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/
---

**Summary:** The LevelsEffect object specifies adjustments to the highlights, midtones, and shadows of an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLevelsEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusLevelsEffect()](#EmfPlusLevelsEffect__1) | Initierar en ny instans av klassen EmfPlusLevelsEffect |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| markering | int | r/w | Hämtar eller anger den som specificerar hur mycket högdagrarna i en bild ska ljusas upp. Färg<br/>            kanalvärdena i den högsta delen av intensitetsintervallet ändras mer än värden nära<br/>            mitten eller de låga delarna, vilket betyder att en bild kan ljusas upp utan att förlora kontrasten<br/>            mellan de mörkare delarna av bilden.<br/>            0 ≤ value &lt; Anger att högdagrar med en intensitetsprocent över detta tröskelvärde SKA<br/>            100 ökas.<br/>            100 Anger att högdagrar INTE får förändras. |
| mid_tone | int | r/w | Hämtar eller anger den som specificerar hur mycket mellantonerna i en bild ska ljusas upp eller mörkas. Färg<br/>            kanalvärden i mitten av intensitetsintervallet ändras mer än värden nära den höga<br/>            eller låga delen, vilket betyder att en bild kan ljusas upp eller mörkas utan att förlora kontrasten<br/>            mellan de mörkaste och ljusaste delarna av bilden.<br/>            -100 ≤ value &lt; 0 Anger att mellantonerna görs mörkare.<br/>            0 Anger att mellantonerna INTE får förändras.<br/>            0 &lt; value ≤ 100 Anger att mellantonerna görs ljusare. |
| shadow | int | r/w | Hämtar eller anger den som specificerar hur mycket skuggorna i en bild ska mörkas. Färg<br/>            kanalvärden i den låga delen av intensitetsintervallet ändras mer än värden nära mitten eller<br/>            de höga delarna, vilket betyder att en bild kan mörkas utan att förlora kontrasten mellan de<br/>            ljusare delarna av bilden.<br/>            0 Anger att skuggorna INTE får förändras.<br/>            0 &lt; value ≤ 100<br/>            Anger att skuggor med en intensitetsprocent under detta tröskelvärde görs<br/>            mörkare. |


### Constructor: EmfPlusLevelsEffect() {#EmfPlusLevelsEffect__1}


```
 EmfPlusLevelsEffect() 
```

Initierar en ny instans av klassen EmfPlusLevelsEffect

