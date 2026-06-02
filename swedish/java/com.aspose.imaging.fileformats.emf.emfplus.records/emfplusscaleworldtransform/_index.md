---
title: "EmfPlusScaleWorldTransform"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusScaleWorldTransform-posten utför en skalning på den aktuella världsrumstransformen."
type: docs
weight: 52
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusScaleWorldTransform extends EmfPlusTerminalServerRecordType
```

EmfPlusScaleWorldTransform-posten utför en skalning på den aktuella världsrumstransformen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusScaleWorldTransform(EmfPlusRecord source)](#EmfPlusScaleWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusScaleWorldTransform`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | Hämtar ett värde som indikerar om [post multiplied matrix]. |
| [getSx()](#getSx--) | Hämtar eller anger ett 32-bitars flyttal som definierar den horisontella skalningsfaktorn. |
| [setSx(float value)](#setSx-float-) | Hämtar eller anger ett 32-bitars flyttal som definierar den horisontella skalningsfaktorn. |
| [getSy()](#getSy--) | Hämtar eller anger ett 32-bitars flyttal som definierar den vertikala skalningsfaktorn. |
| [setSy(float value)](#setSy-float-) | Hämtar eller anger ett 32-bitars flyttal som definierar den vertikala skalningsfaktorn. |
### EmfPlusScaleWorldTransform(EmfPlusRecord source) {#EmfPlusScaleWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusScaleWorldTransform(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusScaleWorldTransform`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### getPostMultipliedMatrix() {#getPostMultipliedMatrix--}
```
public boolean getPostMultipliedMatrix()
```


Hämtar ett värde som indikerar om [post multiplicerad matris]. Om satt ska transformmatrisen post‑multipliceras. Om avmarkerad ska den premultipliceras.

Värde: `true` om [post multiplied matrix]; annars `false`.

**Returns:**
boolean
### getSx() {#getSx--}
```
public float getSx()
```


Hämtar eller anger ett 32-bitars flyttal som definierar den horisontella skalningsfaktorn. Skalningen utförs genom att konstruera en ny transformmatris från fältvärdena Sx och Sy, som visas i följande tabell. ----------------- | Sx | 0 | 0 | | 0 | Sx | 0 | ----------------- Figur 3: Skala Transformmatris

**Returns:**
float
### setSx(float value) {#setSx-float-}
```
public void setSx(float value)
```


Hämtar eller anger ett 32-bitars flyttal som definierar den horisontella skalningsfaktorn. Skalningen utförs genom att konstruera en ny transformmatris från fältvärdena Sx och Sy, som visas i följande tabell. ----------------- | Sx | 0 | 0 | | 0 | Sx | 0 | ----------------- Figur 3: Skala Transformmatris

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getSy() {#getSy--}
```
public float getSy()
```


Hämtar eller anger ett 32-bitars flyttal som definierar den vertikala skalningsfaktorn.

**Returns:**
float
### setSy(float value) {#setSy-float-}
```
public void setSy(float value)
```


Hämtar eller anger ett 32-bitars flyttal som definierar den vertikala skalningsfaktorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

