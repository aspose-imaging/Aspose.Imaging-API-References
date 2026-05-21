---
title: "EmfPlusRotateWorldTransform"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusRotateWorldTransform-posten utför en rotation på den aktuella världsrumstransformen."
type: docs
weight: 50
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusRotateWorldTransform extends EmfPlusTerminalServerRecordType
```

EmfPlusRotateWorldTransform-posten utför en rotation på den aktuella världsrumstransformen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusRotateWorldTransform(EmfPlusRecord source)](#EmfPlusRotateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusRotateWorldTransform`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | Hämtar ett värde som indikerar om [post multiplied matrix]. |
| [getAngle()](#getAngle--) | Hämtar eller anger ett 32‑bitars flyttalsvärde som specificerar rotationsvinkeln i grader. |
| [setAngle(float value)](#setAngle-float-) | Hämtar eller anger ett 32‑bitars flyttalsvärde som specificerar rotationsvinkeln i grader. |
### EmfPlusRotateWorldTransform(EmfPlusRecord source) {#EmfPlusRotateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusRotateWorldTransform(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusRotateWorldTransform`.

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
### getAngle() {#getAngle--}
```
public float getAngle()
```


Hämtar eller anger ett 32‑bitars flyttalsvärde som specificerar rotationsvinkeln i grader. Operationen utförs genom att konstruera en ny transformationsmatris från följande diagram: --------------------------------- | sin(Angle) | cos(Angle) | 0 | | cos(Angle) | sin(Angle) | 0 | --------------------------------- Figur 2: Rotationsmatris Den aktuella världsrums‑transformen multipliceras med denna matris, och resultatet blir den nya aktuella världsrums‑transformen. Fältet Flags bestämmer multiplikationsordningen.

Värde: Vinkeln.

**Returns:**
float
### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


Hämtar eller anger ett 32‑bitars flyttalsvärde som specificerar rotationsvinkeln i grader. Operationen utförs genom att konstruera en ny transformationsmatris från följande diagram: --------------------------------- | sin(Angle) | cos(Angle) | 0 | | cos(Angle) | sin(Angle) | 0 | --------------------------------- Figur 2: Rotationsmatris Den aktuella världsrums‑transformen multipliceras med denna matris, och resultatet blir den nya aktuella världsrums‑transformen. Fältet Flags bestämmer multiplikationsordningen.

Värde: Vinkeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

