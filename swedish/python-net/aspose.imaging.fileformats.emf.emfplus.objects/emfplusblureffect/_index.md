---
title: "EmfPlusBlurEffect Class"
type: docs
weight: 100
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/
---

**Summary:** The BlurEffect object specifies a decrease in the difference in intensity between pixels in an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlurEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusBlurEffect()](#EmfPlusBlurEffect__1) | Initierar en ny instans av EmfPlusBlurEffect-klassen. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blur_radius | float | r/w | Hämtar eller anger ett 32-bitars flyttal som specificerar oskärperadien i pixlar,<br/>            vilket bestämmer antalet pixlar som är involverade i beräkningen av det nya värdet för en given pixel.<br/>            Detta värde MÅSTE ligga i intervallet 0,0 till 255,0. |
| expand_edge | bool | r/w | Hämtar eller anger ett 32-bitars booleskt värde som specificerar om bitmapen expanderar med<br/>            ett belopp lika med värdet av BlurRadius för att skapa mjuka kanter. Detta värde MÅSTE vara<br/>            ett av följande:<br/>            FALSE<br/>            0x00000000<br/>            Storleken på bitmapen FÅR INTE ändras, och dess mjuka kanter SKA klippas till<br/>            storleken av BlurRadius.<br/>            TRUE<br/>            0x00000001<br/>            Storleken på bitmapen SKA expandera med ett belopp lika med BlurRadius för<br/>            att skapa mjuka kanter. |


### Constructor: EmfPlusBlurEffect() {#EmfPlusBlurEffect__1}


```
 EmfPlusBlurEffect() 
```

Initierar en ny instans av EmfPlusBlurEffect-klassen.

