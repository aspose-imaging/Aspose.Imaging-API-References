---
title: "EmfPlusColorBalanceEffect"
second_title: "Aspose.Imaging för Java API-referens"
description: "ColorBalanceEffect‑objektet specificerar justeringar av de relativa mängderna rött, grönt och blått i en bild."
type: docs
weight: 26
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorbalanceeffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusColorBalanceEffect extends EmfPlusImageEffectsObjectType
```

ColorBalanceEffect-objektet specificerar justeringar av de relativa mängderna rött, grönt och blått i en bild.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusColorBalanceEffect()](#EmfPlusColorBalanceEffect--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCyanRed()](#getCyanRed--) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar en förändring av mängden rött i bilden. |
| [setCyanRed(int value)](#setCyanRed-int-) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar en förändring av mängden rött i bilden. |
| [getMagentaGreen()](#getMagentaGreen--) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar en förändring av mängden grönt i bilden. |
| [setMagentaGreen(int value)](#setMagentaGreen-int-) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar en förändring av mängden grönt i bilden. |
| [getYellowBlue()](#getYellowBlue--) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar en förändring av mängden blått i bilden. |
| [setYellowBlue(int value)](#setYellowBlue-int-) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar en förändring av mängden blått i bilden. |
### EmfPlusColorBalanceEffect() {#EmfPlusColorBalanceEffect--}
```
public EmfPlusColorBalanceEffect()
```


### getCyanRed() {#getCyanRed--}
```
public int getCyanRed()
```


Hämtar eller anger ett 32‑bitars signerat heltal som specificerar en förändring av mängden rött i bilden. Detta värde MÅSTE ligga i intervallet -100 till 100, med följande effekter: -100 ≤ värde < 0 När värdet minskar bör mängden rött i bilden minska och mängden cyan öka. 0 Ett värde på 0 anger att mängden rött och cyan INTE får förändras. 0 < värde ≤ 100 När värdet ökar bör mängden rött i bilden öka och mängden cyan minska.

**Returns:**
int
### setCyanRed(int value) {#setCyanRed-int-}
```
public void setCyanRed(int value)
```


Hämtar eller anger ett 32‑bitars signerat heltal som specificerar en förändring av mängden rött i bilden. Detta värde MÅSTE ligga i intervallet -100 till 100, med följande effekter: -100 ≤ värde < 0 När värdet minskar bör mängden rött i bilden minska och mängden cyan öka. 0 Ett värde på 0 anger att mängden rött och cyan INTE får förändras. 0 < värde ≤ 100 När värdet ökar bör mängden rött i bilden öka och mängden cyan minska.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getMagentaGreen() {#getMagentaGreen--}
```
public int getMagentaGreen()
```


Hämtar eller anger ett 32‑bitars signerat heltal som specificerar en förändring av mängden grönt i bilden. Detta värde MÅSTE ligga i intervallet -100 till 100, med följande effekter: -100 ≤ värde < 0 När värdet minskar bör mängden grönt i bilden minska och mängden magenta öka. 0 Ett värde på 0 anger att mängden grönt och magenta INTE får förändras. 0 < värde ≤ 100 När värdet ökar bör mängden grönt i bilden öka och mängden magenta minska.

**Returns:**
int
### setMagentaGreen(int value) {#setMagentaGreen-int-}
```
public void setMagentaGreen(int value)
```


Hämtar eller anger ett 32‑bitars signerat heltal som specificerar en förändring av mängden grönt i bilden. Detta värde MÅSTE ligga i intervallet -100 till 100, med följande effekter: -100 ≤ värde < 0 När värdet minskar bör mängden grönt i bilden minska och mängden magenta öka. 0 Ett värde på 0 anger att mängden grönt och magenta INTE får förändras. 0 < värde ≤ 100 När värdet ökar bör mängden grönt i bilden öka och mängden magenta minska.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getYellowBlue() {#getYellowBlue--}
```
public int getYellowBlue()
```


Hämtar eller anger ett 32‑bitars signerat heltal som specificerar en förändring av mängden blått i bilden. Detta värde MÅSTE ligga i intervallet -100 till 100, med följande effekter: -100 ≤ värde < 0 När värdet minskar bör mängden blått i bilden minska och mängden gult öka. 0 Ett värde på 0 anger att mängden blått och gult INTE får förändras. 0 < värde ≤ 100 När värdet ökar bör mängden blått i bilden öka och mängden gult minska.

**Returns:**
int
### setYellowBlue(int value) {#setYellowBlue-int-}
```
public void setYellowBlue(int value)
```


Hämtar eller anger ett 32‑bitars signerat heltal som specificerar en förändring av mängden blått i bilden. Detta värde MÅSTE ligga i intervallet -100 till 100, med följande effekter: -100 ≤ värde < 0 När värdet minskar bör mängden blått i bilden minska och mängden gult öka. 0 Ett värde på 0 anger att mängden blått och gult INTE får förändras. 0 < värde ≤ 100 När värdet ökar bör mängden blått i bilden öka och mängden gult minska.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

