---
title: "EmfPlusTintEffect klass"
type: docs
weight: 700
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustinteffect/
---

**Summary:** The TintEffect object specifies an addition of black or white to a specified hue in an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTintEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusTintEffect()](#EmfPlusTintEffect__1) | Initierar en ny instans av EmfPlusTintEffect‑klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| amount | int | r/w | Hämtar eller anger ett 32-bitars heltal som specificerar hur mycket nyansen förstärks eller försvagas.<br/>            -100 ≤ värde &lt; 0<br/>            Negativa värden anger hur mycket nyansen försvagas, vilket motsvarar<br/>            tillsats av svart.<br/>            0 Ett värde på 0 anger att tonen MUST NOT förändras.<br/>            0 &lt; värde ≤ 100<br/>            Positiva värden anger hur mycket nyansen förstärks, vilket motsvarar<br/>            tillsats av vitt. |
| nyans | int | r/w | Hämtar eller anger ett 32-bitars heltal som specificerar den nyans som tint‑effekten appliceras på.<br/>            -180 ≤ värde < 0 <br/>            Färgen vid en specificerad moturs rotation av färghjulet, med start<br/>            från blått.<br/>            0 Ett värde på 0 anger färgen blå på färghjulet.<br/>            0 < värde ≤ 180<br/>            Färgen vid en specificerad medurs rotation av färghjulet, med start från blått. |


### Constructor: EmfPlusTintEffect() {#EmfPlusTintEffect__1}


```
 EmfPlusTintEffect() 
```

Initierar en ny instans av EmfPlusTintEffect‑klassen

