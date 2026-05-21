---
title: "EmfPlusLevelsEffect"
second_title: "Aspose.Imaging för Java API-referens"
description: "LevelsEffect‑objektet specificerar justeringar av högdagrar, mellantoner och skuggor i en bild."
type: docs
weight: 51
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusLevelsEffect extends EmfPlusImageEffectsObjectType
```

LevelsEffect-objektet specificerar justeringar av högdagrar, mellantoner och skuggor i en bild.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusLevelsEffect()](#EmfPlusLevelsEffect--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getHighlight()](#getHighlight--) | Hämtar eller anger hur mycket högdagrarna i en bild ska ljusas upp. |
| [setHighlight(int value)](#setHighlight-int-) | Hämtar eller anger hur mycket högdagrarna i en bild ska ljusas upp. |
| [getMidTone()](#getMidTone--) | Hämtar eller anger hur mycket mellantonerna i en bild ska ljusas upp eller mörkas ner. |
| [setMidTone(int value)](#setMidTone-int-) | Hämtar eller anger hur mycket mellantonerna i en bild ska ljusas upp eller mörkas ner. |
| [getShadow()](#getShadow--) | Hämtar eller anger hur mycket skuggorna i en bild ska mörkas ner. |
| [setShadow(int value)](#setShadow-int-) | Hämtar eller anger hur mycket skuggorna i en bild ska mörkas ner. |
### EmfPlusLevelsEffect() {#EmfPlusLevelsEffect--}
```
public EmfPlusLevelsEffect()
```


### getHighlight() {#getHighlight--}
```
public int getHighlight()
```


Hämtar eller anger hur mycket högdagrarna i en bild ska ljusas upp. Färgkanalvärdena i den övre delen av intensitetsintervallet förändras mer än värden nära mitten eller den lägre delen, vilket innebär att en bild kan ljusas upp utan att förlora kontrasten mellan de mörkare delarna av bilden. 0 \\u2264 value < Anger att högdagrar med en intensitetsprocent över detta tröskelvärde SKALL 100 ökas. 100 Anger att högdagrar INTE får förändras.

Värde: Höjdpunkten.

**Returns:**
int
### setHighlight(int value) {#setHighlight-int-}
```
public void setHighlight(int value)
```


Hämtar eller anger hur mycket högdagrarna i en bild ska ljusas upp. Färgkanalvärdena i den övre delen av intensitetsintervallet förändras mer än värden nära mitten eller den lägre delen, vilket innebär att en bild kan ljusas upp utan att förlora kontrasten mellan de mörkare delarna av bilden. 0 \\u2264 value < Anger att högdagrar med en intensitetsprocent över detta tröskelvärde SKALL 100 ökas. 100 Anger att högdagrar INTE får förändras.

Värde: Höjdpunkten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getMidTone() {#getMidTone--}
```
public int getMidTone()
```


Hämtar eller anger hur mycket mellantonerna i en bild ska ljusas upp eller mörkas ner. Färgkanalvärdena i mitten av intensitetsintervallet förändras mer än värden nära den höga eller låga delen, vilket innebär att en bild kan ljusas upp eller mörkas ner utan att förlora kontrasten mellan de mörkaste och ljusaste delarna av bilden. -100 \\u2264 value < 0 Anger att mellantonerna görs mörkare. 0 Anger att mellantonerna INTE får förändras. 0 < value \\u2264 100 Anger att mellantonerna görs ljusare.

Värde: Mellanton.

**Returns:**
int
### setMidTone(int value) {#setMidTone-int-}
```
public void setMidTone(int value)
```


Hämtar eller anger hur mycket mellantonerna i en bild ska ljusas upp eller mörkas ner. Färgkanalvärdena i mitten av intensitetsintervallet förändras mer än värden nära den höga eller låga delen, vilket innebär att en bild kan ljusas upp eller mörkas ner utan att förlora kontrasten mellan de mörkaste och ljusaste delarna av bilden. -100 \\u2264 value < 0 Anger att mellantonerna görs mörkare. 0 Anger att mellantonerna INTE får förändras. 0 < value \\u2264 100 Anger att mellantonerna görs ljusare.

Värde: Mellanton.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getShadow() {#getShadow--}
```
public int getShadow()
```


Hämtar eller anger hur mycket skuggorna i en bild ska mörkas ner. Färgkanalvärdena i den låga delen av intensitetsintervallet förändras mer än värden nära mitten eller den höga delen, vilket innebär att en bild kan mörkas utan att förlora kontrasten mellan de ljusare delarna av bilden. 0 Anger att skuggorna INTE får förändras. 0 < value \\u2264 100 Anger att skuggor med en intensitetsprocent under detta tröskelvärde görs mörkare.

Värde: Skuggan.

**Returns:**
int
### setShadow(int value) {#setShadow-int-}
```
public void setShadow(int value)
```


Hämtar eller anger hur mycket skuggorna i en bild ska mörkas ner. Färgkanalvärdena i den låga delen av intensitetsintervallet förändras mer än värden nära mitten eller den höga delen, vilket innebär att en bild kan mörkas utan att förlora kontrasten mellan de ljusare delarna av bilden. 0 Anger att skuggorna INTE får förändras. 0 < value \\u2264 100 Anger att skuggor med en intensitetsprocent under detta tröskelvärde görs mörkare.

Värde: Skuggan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

