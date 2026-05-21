---
title: "EmfPlusBlurEffect"
second_title: "Aspose.Imaging för Java API-referens"
description: "BlurEffect-objektet specificerar en minskning av skillnaden i intensitet mellan pixlar i en bild."
type: docs
weight: 19
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusBlurEffect extends EmfPlusImageEffectsObjectType
```

BlurEffect-objektet specificerar en minskning av skillnaden i intensitet mellan pixlar i en bild.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusBlurEffect()](#EmfPlusBlurEffect--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Hämtar eller anger ett 32-bitars flyttal som specificerar oskärperadens radie i pixlar, vilket bestämmer antalet pixlar som är involverade i beräkningen av det nya värdet för en given pixel. |
| [setBlurRadius(float value)](#setBlurRadius-float-) | Hämtar eller anger ett 32-bitars flyttal som specificerar oskärperadens radie i pixlar, vilket bestämmer antalet pixlar som är involverade i beräkningen av det nya värdet för en given pixel. |
| [getExpandEdge()](#getExpandEdge--) | Hämtar eller anger ett 32-bitars booleskt värde som specificerar om bitmapen expanderar med ett belopp lika med värdet av BlurRadius för att skapa mjuka kanter. |
| [setExpandEdge(boolean value)](#setExpandEdge-boolean-) | Hämtar eller anger ett 32-bitars booleskt värde som specificerar om bitmapen expanderar med ett belopp lika med värdet av BlurRadius för att skapa mjuka kanter. |
### EmfPlusBlurEffect() {#EmfPlusBlurEffect--}
```
public EmfPlusBlurEffect()
```


### getBlurRadius() {#getBlurRadius--}
```
public float getBlurRadius()
```


Hämtar eller anger ett 32-bitars flyttal som specificerar oskärperadens radie i pixlar, vilket bestämmer antalet pixlar som är involverade i beräkningen av det nya värdet för en given pixel. Detta värde MÅSTE ligga i intervallet 0,0 till 255,0.

**Returns:**
float
### setBlurRadius(float value) {#setBlurRadius-float-}
```
public void setBlurRadius(float value)
```


Hämtar eller anger ett 32-bitars flyttal som specificerar oskärperadens radie i pixlar, vilket bestämmer antalet pixlar som är involverade i beräkningen av det nya värdet för en given pixel. Detta värde MÅSTE ligga i intervallet 0,0 till 255,0.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getExpandEdge() {#getExpandEdge--}
```
public boolean getExpandEdge()
```


Hämtar eller anger ett 32-bitars booleskt värde som specificerar om bitmapen expanderar med ett belopp lika med värdet av BlurRadius för att skapa mjuka kanter. Detta värde MÅSTE vara ett av följande: FALSE 0x00000000 Storleken på bitmapen FÅR INTE ändras, och dess mjuka kanter SKA klippas till storleken av BlurRadius. TRUE 0x00000001 Storleken på bitmapen SKA expandera med ett belopp lika med BlurRadius för att skapa mjuka kanter.

**Returns:**
boolean
### setExpandEdge(boolean value) {#setExpandEdge-boolean-}
```
public void setExpandEdge(boolean value)
```


Hämtar eller anger ett 32-bitars booleskt värde som specificerar om bitmapen expanderar med ett belopp lika med värdet av BlurRadius för att skapa mjuka kanter. Detta värde MÅSTE vara ett av följande: FALSE 0x00000000 Storleken på bitmapen FÅR INTE ändras, och dess mjuka kanter SKA klippas till storleken av BlurRadius. TRUE 0x00000001 Storleken på bitmapen SKA expandera med ett belopp lika med BlurRadius för att skapa mjuka kanter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

