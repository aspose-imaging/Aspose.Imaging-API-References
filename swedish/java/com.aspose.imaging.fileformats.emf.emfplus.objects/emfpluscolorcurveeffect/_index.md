---
title: "EmfPlusColorCurveEffect"
second_title: "Aspose.Imaging för Java API-referens"
description: "ColorCurveEffect-objektet specificerar en av åtta justeringar av färgkurvan i en bild."
type: docs
weight: 27
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusColorCurveEffect extends EmfPlusImageEffectsObjectType
```

ColorCurveEffect-objektet specificerar en av åtta justeringar av färgkurvan i en bild.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusColorCurveEffect()](#EmfPlusColorCurveEffect--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCurveAdjustment()](#getCurveAdjustment--) | Hämtar eller anger ett 32‑bit osignerat heltal som specificerar kurvjusteringen som ska tillämpas på färgerna i bitmap. |
| [setCurveAdjustment(int value)](#setCurveAdjustment-int-) | Hämtar eller anger ett 32‑bit osignerat heltal som specificerar kurvjusteringen som ska tillämpas på färgerna i bitmap. |
| [getCurveChannel()](#getCurveChannel--) | Hämtar eller anger ett 32‑bit osignerat heltal som specificerar färgkanalen som kurvjusteringen gäller för. |
| [setCurveChannel(int value)](#setCurveChannel-int-) | Hämtar eller anger ett 32‑bit osignerat heltal som specificerar färgkanalen som kurvjusteringen gäller för. |
| [getAdjustmentIntensity()](#getAdjustmentIntensity--) | Hämtar eller anger ett 32‑bit signerat heltal som specificerar intensiteten för kurvjusteringen på färgkanalen som anges av CurveChannel. |
| [setAdjustmentIntensity(int value)](#setAdjustmentIntensity-int-) | Hämtar eller anger ett 32‑bit signerat heltal som specificerar intensiteten för kurvjusteringen på färgkanalen som anges av CurveChannel. |
### EmfPlusColorCurveEffect() {#EmfPlusColorCurveEffect--}
```
public EmfPlusColorCurveEffect()
```


### getCurveAdjustment() {#getCurveAdjustment--}
```
public int getCurveAdjustment()
```


Hämtar eller anger ett 32‑bit osignerat heltal som specificerar kurvjusteringen som ska tillämpas på färgerna i bitmap. Detta värde MÅSTE definieras i CurveAdjustments‑enumerationen (avsnitt 2.1.1.7).

**Returns:**
int
### setCurveAdjustment(int value) {#setCurveAdjustment-int-}
```
public void setCurveAdjustment(int value)
```


Hämtar eller anger ett 32‑bit osignerat heltal som specificerar kurvjusteringen som ska tillämpas på färgerna i bitmap. Detta värde MÅSTE definieras i CurveAdjustments‑enumerationen (avsnitt 2.1.1.7).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCurveChannel() {#getCurveChannel--}
```
public int getCurveChannel()
```


Hämtar eller anger ett 32‑bit osignerat heltal som specificerar färgkanalen som kurvjusteringen gäller för. Detta värde MÅSTE definieras i CurveChannel‑enumerationen (avsnitt 2.1.1.8).

**Returns:**
int
### setCurveChannel(int value) {#setCurveChannel-int-}
```
public void setCurveChannel(int value)
```


Hämtar eller anger ett 32‑bit osignerat heltal som specificerar färgkanalen som kurvjusteringen gäller för. Detta värde MÅSTE definieras i CurveChannel‑enumerationen (avsnitt 2.1.1.8).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getAdjustmentIntensity() {#getAdjustmentIntensity--}
```
public int getAdjustmentIntensity()
```


Hämtar eller anger ett 32‑bit signerat heltal som specificerar intensiteten för kurvjusteringen på färgkanalen som anges av CurveChannel. De meningsfulla värdeintervallen för detta fält varierar beroende på CurveAdjustment‑värdet, enligt följande: Exponeringsjusteringsintervall: -255 \\u2264 value < 0 När värdet minskar bör exponeringen av bilden minska. 0 Ett värde på 0 anger att exponeringen INTE får förändras. 0 < value \\u2264 255 När värdet ökar bör exponeringen av bilden öka. Densitetsjusteringsintervall: -255 \\u2264 value < 0 När värdet minskar bör densiteten i bilden minska, vilket resulterar i en mörkare bild. 0 Ett värde på 0 anger att densiteten INTE får förändras. 0 < value \\u2264 255 När värdet ökar bör densiteten i bilden öka. Kontrastjusteringsintervall: -100 \\u2264 value < 0 När värdet minskar bör kontrasten i bilden minska. 0 Ett värde på 0 anger att kontrasten INTE får förändras. 0 < value \\u2264 100 När värdet ökar bör kontrasten i bilden öka. Höjdpunktsjusteringsintervall: -100 \\u2264 value < 0 När värdet minskar bör de ljusa områdena i bilden framstå mörkare. 0 Ett värde på 0 anger att höjdpunkten INTE får förändras. 0 < value \\u2264 100 När värdet ökar bör de ljusa områdena i bilden framstå ljusare. Skuggjusteringsintervall: -100 \\u2264 value < 0 När värdet minskar bör de mörka områdena i bilden framstå mörkare. 0 Ett värde på 0 anger att skuggan INTE får förändras. 0 < value \\u2264 100 När värdet ökar bör de mörka områdena i bilden framstå ljusare. Vit mättnadsjusteringsintervall: 0 \\u2014 255 När värdet ökar ökas den övre gränsen för intervallet av färgkanalintensiteter. Svart mättnadsjusteringsintervall: 0 \\u2014 255 När värdet ökar ökas den nedre gränsen för intervallet av färgkanalintensiteter.

**Returns:**
int
### setAdjustmentIntensity(int value) {#setAdjustmentIntensity-int-}
```
public void setAdjustmentIntensity(int value)
```


Hämtar eller anger ett 32‑bit signerat heltal som specificerar intensiteten för kurvjusteringen på färgkanalen som anges av CurveChannel. De meningsfulla värdeintervallen för detta fält varierar beroende på CurveAdjustment‑värdet, enligt följande: Exponeringsjusteringsintervall: -255 \\u2264 value < 0 När värdet minskar bör exponeringen av bilden minska. 0 Ett värde på 0 anger att exponeringen INTE får förändras. 0 < value \\u2264 255 När värdet ökar bör exponeringen av bilden öka. Densitetsjusteringsintervall: -255 \\u2264 value < 0 När värdet minskar bör densiteten i bilden minska, vilket resulterar i en mörkare bild. 0 Ett värde på 0 anger att densiteten INTE får förändras. 0 < value \\u2264 255 När värdet ökar bör densiteten i bilden öka. Kontrastjusteringsintervall: -100 \\u2264 value < 0 När värdet minskar bör kontrasten i bilden minska. 0 Ett värde på 0 anger att kontrasten INTE får förändras. 0 < value \\u2264 100 När värdet ökar bör kontrasten i bilden öka. Höjdpunktsjusteringsintervall: -100 \\u2264 value < 0 När värdet minskar bör de ljusa områdena i bilden framstå mörkare. 0 Ett värde på 0 anger att höjdpunkten INTE får förändras. 0 < value \\u2264 100 När värdet ökar bör de ljusa områdena i bilden framstå ljusare. Skuggjusteringsintervall: -100 \\u2264 value < 0 När värdet minskar bör de mörka områdena i bilden framstå mörkare. 0 Ett värde på 0 anger att skuggan INTE får förändras. 0 < value \\u2264 100 När värdet ökar bör de mörka områdena i bilden framstå ljusare. Vit mättnadsjusteringsintervall: 0 \\u2014 255 När värdet ökar ökas den övre gränsen för intervallet av färgkanalintensiteter. Svart mättnadsjusteringsintervall: 0 \\u2014 255 När värdet ökar ökas den nedre gränsen för intervallet av färgkanalintensiteter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

