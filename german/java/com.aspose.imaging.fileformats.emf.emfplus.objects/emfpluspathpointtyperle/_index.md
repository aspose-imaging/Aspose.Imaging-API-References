---
title: "EmfPlusPathPointTypeRle"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmfPlusPathPointTypeRle-Objekt gibt Typwerte an, die mit Punkten auf einem Grafikpfad unter Verwendung von RLE-Kompression verbunden sind."
type: docs
weight: 62
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype)
```
public final class EmfPlusPathPointTypeRle extends EmfPlusBasePointType
```

Das EmfPlusPathPointTypeRle-Objekt gibt Typwerte an, die mit Punkten auf einem Grafikpfad unter Verwendung von RLE-Kompression verknüpft sind. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 B|1|RunCount | PointType | B (1 Bit): Wenn gesetzt, liegen die Pfadpunkte auf einer Bézier-Kurve. Wenn nicht gesetzt, liegen die Pfadpunkte auf einer Grafiklinie. RunCount (6 Bits): Die Laufanzahl, also die Anzahl der Pfadpunkte, die dem Typ im Feld PointType zugeordnet werden. PointType (1 Byte): Ein EmfPlusPathPointType-Objekt (Abschnitt 2.2.2.31), das den dem Pfadpunkt zuzuweisenden Typ angibt.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusPathPointTypeRle()](#EmfPlusPathPointTypeRle--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getData()](#getData--) | Liest oder setzt die Daten. |
| [setData(int value)](#setData-int-) | Liest oder setzt die Daten. |
| [getBezier()](#getBezier--) | Liest oder schreibt einen Wert, der angibt, ob dieses `EmfPlusPathPointTypeRle` eine Bézier‑Kurve ist. |
| [setBezier(boolean value)](#setBezier-boolean-) | Liest oder schreibt einen Wert, der angibt, ob dieses `EmfPlusPathPointTypeRle` eine Bézier‑Kurve ist. |
| [getRunCount()](#getRunCount--) | Liest oder schreibt die Laufanzahl. |
| [setRunCount(byte value)](#setRunCount-byte-) | Liest oder schreibt die Laufanzahl. |
| [getPointType()](#getPointType--) | Liest oder schreibt den Typ des Punktes. |
| [setPointType(EmfPlusPathPointType value)](#setPointType-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointType-) | Liest oder schreibt den Typ des Punktes. |
### EmfPlusPathPointTypeRle() {#EmfPlusPathPointTypeRle--}
```
public EmfPlusPathPointTypeRle()
```


### getData() {#getData--}
```
public int getData()
```


Liest oder setzt die Daten.

Wert: Die Daten.

**Returns:**
int
### setData(int value) {#setData-int-}
```
public void setData(int value)
```


Liest oder setzt die Daten.

Wert: Die Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getBezier() {#getBezier--}
```
public boolean getBezier()
```


Liest oder schreibt einen Wert, der angibt, ob dieses `EmfPlusPathPointTypeRle` eine Bézier‑Kurve ist. Wenn gesetzt, liegen die Pfadpunkte auf einer Bézier‑Kurve. Wenn nicht gesetzt, liegen die Pfadpunkte auf einer Grafiklinie.

Wert: `true`, wenn Bézier; sonst `false`.

**Returns:**
boolean
### setBezier(boolean value) {#setBezier-boolean-}
```
public void setBezier(boolean value)
```


Liest oder schreibt einen Wert, der angibt, ob dieses `EmfPlusPathPointTypeRle` eine Bézier‑Kurve ist. Wenn gesetzt, liegen die Pfadpunkte auf einer Bézier‑Kurve. Wenn nicht gesetzt, liegen die Pfadpunkte auf einer Grafiklinie.

Wert: `true`, wenn Bézier; sonst `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getRunCount() {#getRunCount--}
```
public byte getRunCount()
```


Liest oder schreibt die Laufanzahl. RunCount (6 Bits): Die Laufanzahl, also die Anzahl der Pfadpunkte, die dem Typ im Feld PointType zugeordnet werden.

Wert: Die Laufanzahl.

**Returns:**
byte
### setRunCount(byte value) {#setRunCount-byte-}
```
public void setRunCount(byte value)
```


Liest oder schreibt die Laufanzahl. RunCount (6 Bits): Die Laufanzahl, also die Anzahl der Pfadpunkte, die dem Typ im Feld PointType zugeordnet werden.

Wert: Die Laufanzahl.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getPointType() {#getPointType--}
```
public EmfPlusPathPointType getPointType()
```


Liest oder schreibt den Typ des Punktes. PointType (1 Byte): Ein EmfPlusPathPointType-Objekt (Abschnitt 2.2.2.31), das den dem Pfadpunkt zuzuweisenden Typ angibt.

Wert: Der Typ des Punktes.

**Returns:**
[EmfPlusPathPointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype)
### setPointType(EmfPlusPathPointType value) {#setPointType-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointType-}
```
public void setPointType(EmfPlusPathPointType value)
```


Liest oder schreibt den Typ des Punktes. PointType (1 Byte): Ein EmfPlusPathPointType-Objekt (Abschnitt 2.2.2.31), das den dem Pfadpunkt zuzuweisenden Typ angibt.

Wert: Der Typ des Punktes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPlusPathPointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype) |  |

