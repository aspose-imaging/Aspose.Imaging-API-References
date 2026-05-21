---
title: "EmfPlusTranslateWorldTransform"
second_title: "Aspose.Imaging för Java API-referens"
description: "Den EmfPlusTranslateWorldTransform-posten utför en translation på den aktuella världsrums‑transformationen."
type: docs
weight: 72
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusTranslateWorldTransform extends EmfPlusTerminalServerRecordType
```

Den EmfPlusTranslateWorldTransform-posten utför en translation på den aktuella världsrums‑transformationen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusTranslateWorldTransform(EmfPlusRecord source)](#EmfPlusTranslateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusTranslateWorldTransform`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | Hämtar ett värde som indikerar om [post multiplied matrix]. |
| [getDx()](#getDx--) | Hämtar eller anger ett 32-bitars flyttal som definierar det horisontella avståndet. |
| [setDx(float value)](#setDx-float-) | Hämtar eller anger ett 32-bitars flyttal som definierar det horisontella avståndet. |
| [getDy()](#getDy--) | Hämtar eller anger ett 32-bitars flyttal som definierar det vertikala avståndet. |
| [setDy(float value)](#setDy-float-) | Hämtar eller anger ett 32-bitars flyttal som definierar det vertikala avståndet. |
### EmfPlusTranslateWorldTransform(EmfPlusRecord source) {#EmfPlusTranslateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusTranslateWorldTransform(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusTranslateWorldTransform`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### getPostMultipliedMatrix() {#getPostMultipliedMatrix--}
```
public boolean getPostMultipliedMatrix()
```


Hämtar ett värde som indikerar om [post multiplied matrix]. Om satt ska transformationsmatrisen post‑multipliceras. Om rensad ska den premultipliceras.

Värde: `true` om [post multiplied matrix]; annars `false`.

**Returns:**
boolean
### getDx() {#getDx--}
```
public float getDx()
```


Hämtar eller anger ett 32-bitars flyttal som definierar det horisontella avståndet. Översättningen utförs genom att konstruera en ny världstransformmatris från fälten dx och dy.

Värde: dx.

**Returns:**
float
### setDx(float value) {#setDx-float-}
```
public void setDx(float value)
```


Hämtar eller anger ett 32-bitars flyttal som definierar det horisontella avståndet. Översättningen utförs genom att konstruera en ny världstransformmatris från fälten dx och dy.

Värde: dx.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getDy() {#getDy--}
```
public float getDy()
```


Hämtar eller anger ett 32-bitars flyttal som definierar det vertikala avståndet.

Värde: dy.

**Returns:**
float
### setDy(float value) {#setDy-float-}
```
public void setDy(float value)
```


Hämtar eller anger ett 32-bitars flyttal som definierar det vertikala avståndet.

Värde: dy.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

