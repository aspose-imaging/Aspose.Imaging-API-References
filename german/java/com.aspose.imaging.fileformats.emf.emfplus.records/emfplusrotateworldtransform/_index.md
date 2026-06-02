---
title: "EmfPlusRotateWorldTransform"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusRotateWorldTransform-Datensatz führt eine Rotation der aktuellen Weltkoordinatentransformation durch."
type: docs
weight: 50
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusRotateWorldTransform extends EmfPlusTerminalServerRecordType
```

Der EmfPlusRotateWorldTransform-Datensatz führt eine Rotation der aktuellen Weltkoordinatentransformation durch.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusRotateWorldTransform(EmfPlusRecord source)](#EmfPlusRotateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der Klasse `EmfPlusRotateWorldTransform`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | Liest einen Wert, der angibt, ob [post multiplied matrix]. |
| [getAngle()](#getAngle--) | Liest oder setzt einen 32‑Bit‑Gleitkommawert, der den Rotationswinkel in Grad angibt. |
| [setAngle(float value)](#setAngle-float-) | Liest oder setzt einen 32‑Bit‑Gleitkommawert, der den Rotationswinkel in Grad angibt. |
### EmfPlusRotateWorldTransform(EmfPlusRecord source) {#EmfPlusRotateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusRotateWorldTransform(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der Klasse `EmfPlusRotateWorldTransform`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### getPostMultipliedMatrix() {#getPostMultipliedMatrix--}
```
public boolean getPostMultipliedMatrix()
```


Liest einen Wert, der angibt, ob [post multiplied matrix]. Ist das Bit gesetzt, sollte die Transformationsmatrix nachträglich multipliziert werden. Ist das Bit nicht gesetzt, sollte sie vorab multipliziert werden.

Wert: `true` wenn [post multiplied matrix]; andernfalls `false`.

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public float getAngle()
```


Liest oder setzt einen 32‑Bit‑Gleitkommawert, der den Rotationswinkel in Grad angibt. Der Vorgang wird durchgeführt, indem aus dem folgenden Diagramm eine neue Transformationsmatrix erstellt wird: --------------------------------- | sin(Winkel) | cos(Winkel) | 0 | | cos(Winkel) | sin(Winkel) | 0 | --------------------------------- Abbildung 2: Rotations‑Transformationsmatrix Die aktuelle Welt‑Raum‑Transformation wird mit dieser Matrix multipliziert, und das Ergebnis wird zur neuen aktuellen Welt‑Raum‑Transformation. Das Feld Flags bestimmt die Reihenfolge der Multiplikation.

Wert: Der Winkel.

**Returns:**
float
### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


Liest oder setzt einen 32‑Bit‑Gleitkommawert, der den Rotationswinkel in Grad angibt. Der Vorgang wird durchgeführt, indem aus dem folgenden Diagramm eine neue Transformationsmatrix erstellt wird: --------------------------------- | sin(Winkel) | cos(Winkel) | 0 | | cos(Winkel) | sin(Winkel) | 0 | --------------------------------- Abbildung 2: Rotations‑Transformationsmatrix Die aktuelle Welt‑Raum‑Transformation wird mit dieser Matrix multipliziert, und das Ergebnis wird zur neuen aktuellen Welt‑Raum‑Transformation. Das Feld Flags bestimmt die Reihenfolge der Multiplikation.

Wert: Der Winkel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

