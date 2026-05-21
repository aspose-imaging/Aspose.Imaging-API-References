---
title: "EmfPlusSharpenEffect"
second_title: "Aspose.Imaging för Java API-referens"
description: "SharpenEffect-objektet specificerar en ökning av skillnaden i intensitet mellan pixlar i en bild."
type: docs
weight: 72
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplussharpeneffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusSharpenEffect extends EmfPlusImageEffectsObjectType
```

SharpenEffect-objektet specificerar en ökning av skillnaden i intensitet mellan pixlar i en bild.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusSharpenEffect()](#EmfPlusSharpenEffect--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRadius()](#getRadius--) | Hämtar eller anger ett 32-bitars flyttal som specificerar skärpnadsradien i pixlar, vilket bestämmer antalet pixlar som är involverade i beräkningen av det nya värdet för en given pixel. |
| [setRadius(float value)](#setRadius-float-) | Hämtar eller anger ett 32-bitars flyttal som specificerar skärpnadsradien i pixlar, vilket bestämmer antalet pixlar som är involverade i beräkningen av det nya värdet för en given pixel. |
| [getAmount()](#getAmount--) | Hämtar eller anger ett 32-bitars flyttal som specificerar skillnaden i intensitet mellan en given pixel och de omgivande pixlarna. |
| [setAmount(float value)](#setAmount-float-) | Hämtar eller anger ett 32-bitars flyttal som specificerar skillnaden i intensitet mellan en given pixel och de omgivande pixlarna. |
### EmfPlusSharpenEffect() {#EmfPlusSharpenEffect--}
```
public EmfPlusSharpenEffect()
```


### getRadius() {#getRadius--}
```
public float getRadius()
```


Hämtar eller anger ett 32-bitars flyttal som specificerar skärpnadsradien i pixlar, vilket bestämmer antalet pixlar som är involverade i beräkningen av det nya värdet för en given pixel. När detta värde ökar, ökar antalet pixlar som är involverade i beräkningen, och den resulterande bitmapen SKA bli skarpare.

Värde: Radien.

**Returns:**
float
### setRadius(float value) {#setRadius-float-}
```
public void setRadius(float value)
```


Hämtar eller anger ett 32-bitars flyttal som specificerar skärpnadsradien i pixlar, vilket bestämmer antalet pixlar som är involverade i beräkningen av det nya värdet för en given pixel. När detta värde ökar, ökar antalet pixlar som är involverade i beräkningen, och den resulterande bitmapen SKA bli skarpare.

Värde: Radien.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getAmount() {#getAmount--}
```
public float getAmount()
```


Hämtar eller anger ett 32-bitars flyttal som specificerar skillnaden i intensitet mellan en given pixel och de omgivande pixlarna. 0 anger att skärpning INTE FÅR utföras. 0 < värde \\u2264 100 När detta värde ökar, bör skillnaden i intensitet mellan pixlar öka.

Värde: Mängden.

**Returns:**
float
### setAmount(float value) {#setAmount-float-}
```
public void setAmount(float value)
```


Hämtar eller anger ett 32-bitars flyttal som specificerar skillnaden i intensitet mellan en given pixel och de omgivande pixlarna. 0 anger att skärpning INTE FÅR utföras. 0 < värde \\u2264 100 När detta värde ökar, bör skillnaden i intensitet mellan pixlar öka.

Värde: Mängden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

