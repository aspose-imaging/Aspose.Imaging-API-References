---
title: "EmfPlusScaleWorldTransform"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusScaleWorldTransform-Datensatz führt eine Skalierung der aktuellen Weltkoordinatentransformation durch."
type: docs
weight: 52
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusScaleWorldTransform extends EmfPlusTerminalServerRecordType
```

Der EmfPlusScaleWorldTransform-Datensatz führt eine Skalierung der aktuellen Weltkoordinatentransformation durch.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusScaleWorldTransform(EmfPlusRecord source)](#EmfPlusScaleWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusScaleWorldTransform`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | Liest einen Wert, der angibt, ob [post multiplied matrix]. |
| [getSx()](#getSx--) | Liest oder setzt einen 32‑Bit‑Gleitkommawert, der den horizontalen Skalierungsfaktor definiert. |
| [setSx(float value)](#setSx-float-) | Liest oder setzt einen 32‑Bit‑Gleitkommawert, der den horizontalen Skalierungsfaktor definiert. |
| [getSy()](#getSy--) | Liest oder setzt einen 32‑Bit‑Gleitkommawert, der den vertikalen Skalierungsfaktor definiert. |
| [setSy(float value)](#setSy-float-) | Liest oder setzt einen 32‑Bit‑Gleitkommawert, der den vertikalen Skalierungsfaktor definiert. |
### EmfPlusScaleWorldTransform(EmfPlusRecord source) {#EmfPlusScaleWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusScaleWorldTransform(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusScaleWorldTransform`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### getPostMultipliedMatrix() {#getPostMultipliedMatrix--}
```
public boolean getPostMultipliedMatrix()
```


Liest einen Wert, der angibt, ob [post multiplied matrix]. Wenn gesetzt, sollte die Transformationsmatrix post‑multipliziert werden. Wenn nicht gesetzt, sollte sie pre‑multipliziert werden.

Wert: `true` wenn [post multiplied matrix]; andernfalls `false`.

**Returns:**
boolean
### getSx() {#getSx--}
```
public float getSx()
```


Liest oder setzt einen 32‑Bit‑Gleitkommawert, der den horizontalen Skalierungsfaktor definiert. Die Skalierung wird durchgeführt, indem aus den Feldwerten Sx und Sy eine neue Transformationsmatrix erstellt wird, wie in der folgenden Tabelle gezeigt. ----------------- | Sx | 0 | 0 | | 0 | Sx | 0 | ----------------- Abbildung 3: Skalierungstransformationsmatrix

**Returns:**
float
### setSx(float value) {#setSx-float-}
```
public void setSx(float value)
```


Liest oder setzt einen 32‑Bit‑Gleitkommawert, der den horizontalen Skalierungsfaktor definiert. Die Skalierung wird durchgeführt, indem aus den Feldwerten Sx und Sy eine neue Transformationsmatrix erstellt wird, wie in der folgenden Tabelle gezeigt. ----------------- | Sx | 0 | 0 | | 0 | Sx | 0 | ----------------- Abbildung 3: Skalierungstransformationsmatrix

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getSy() {#getSy--}
```
public float getSy()
```


Liest oder setzt einen 32‑Bit‑Gleitkommawert, der den vertikalen Skalierungsfaktor definiert.

**Returns:**
float
### setSy(float value) {#setSy-float-}
```
public void setSy(float value)
```


Liest oder setzt einen 32‑Bit‑Gleitkommawert, der den vertikalen Skalierungsfaktor definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

