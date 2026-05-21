---
title: "EmfEpsData"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EpsData-Objekt ist ein Container für EPS‑Daten."
type: docs
weight: 14
url: /de/java/com.aspose.imaging.fileformats.emf.emf.objects/emfepsdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfEpsData extends EmfObject
```

Das EpsData-Objekt ist ein Container für EPS‑Daten.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfEpsData()](#EmfEpsData--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSizeData()](#getSizeData--) | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die Gesamtgröße dieses Objekts in Bytes angibt. |
| [setSizeData(int value)](#setSizeData-int-) | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die Gesamtgröße dieses Objekts in Bytes angibt. |
| [getVersion()](#getVersion--) | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die das PostScript‑Sprachniveau angibt. |
| [setVersion(int value)](#setVersion-int-) | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die das PostScript‑Sprachniveau angibt. |
| [getPoints()](#getPoints--) | Liest oder setzt ein Array von drei Point28\_4‑Objekten (Abschnitt 2.2.23), das die Koordinaten des Ausgabeparallelogramms mit 28,4‑Bit‑FIX‑Notation definiert. |
| [setPoints(EmfPoint28To4[] value)](#setPoints-com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4---) | Liest oder setzt ein Array von drei Point28\_4‑Objekten (Abschnitt 2.2.23), das die Koordinaten des Ausgabeparallelogramms mit 28,4‑Bit‑FIX‑Notation definiert. |
| [getPostScriptData()](#getPostScriptData--) | Liest oder setzt ein Byte‑Array mit PostScript‑Daten. |
| [setPostScriptData(byte[] value)](#setPostScriptData-byte---) | Liest oder setzt ein Byte‑Array mit PostScript‑Daten. |
### EmfEpsData() {#EmfEpsData--}
```
public EmfEpsData()
```


### getSizeData() {#getSizeData--}
```
public int getSizeData()
```


Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die Gesamtgröße dieses Objekts in Bytes angibt.

**Returns:**
int
### setSizeData(int value) {#setSizeData-int-}
```
public void setSizeData(int value)
```


Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die Gesamtgröße dieses Objekts in Bytes angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die das PostScript‑Sprachniveau angibt. Dieser Wert MUSS 0x00000001 sein.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die das PostScript‑Sprachniveau angibt. Dieser Wert MUSS 0x00000001 sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getPoints() {#getPoints--}
```
public EmfPoint28To4[] getPoints()
```


Liest oder setzt ein Array von drei Point28\_4‑Objekten (Abschnitt 2.2.23), das die Koordinaten des Ausgabeparallelogramms mit 28,4‑Bit‑FIX‑Notation definiert.

Die obere linke Ecke des Parallelogramms ist der erste Punkt in diesem Array, die obere rechte Ecke ist der zweite Punkt und die untere linke Ecke ist der dritte Punkt. Die untere rechte Ecke des Parallelogramms wird aus den ersten drei Punkten (A, B und C) berechnet, indem sie als Vektoren behandelt werden.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4[]
### setPoints(EmfPoint28To4[] value) {#setPoints-com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4---}
```
public void setPoints(EmfPoint28To4[] value)
```


Liest oder setzt ein Array von drei Point28\_4‑Objekten (Abschnitt 2.2.23), das die Koordinaten des Ausgabeparallelogramms mit 28,4‑Bit‑FIX‑Notation definiert.

Die obere linke Ecke des Parallelogramms ist der erste Punkt in diesem Array, die obere rechte Ecke ist der zweite Punkt und die untere linke Ecke ist der dritte Punkt. Die untere rechte Ecke des Parallelogramms wird aus den ersten drei Punkten (A, B und C) berechnet, indem sie als Vektoren behandelt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPoint28To4\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpoint28to4) |  |

### getPostScriptData() {#getPostScriptData--}
```
public byte[] getPostScriptData()
```


Liest oder setzt ein Byte‑Array mit PostScript‑Daten. Die Länge dieses Arrays kann aus dem Feld SizeData berechnet werden. Diese Daten DÜRFEN verwendet werden, um ein Bild zu rendern.

**Returns:**
byte[]
### setPostScriptData(byte[] value) {#setPostScriptData-byte---}
```
public void setPostScriptData(byte[] value)
```


Liest oder setzt ein Byte‑Array mit PostScript‑Daten. Die Länge dieses Arrays kann aus dem Feld SizeData berechnet werden. Diese Daten DÜRFEN verwendet werden, um ein Bild zu rendern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

