---
title: "EmfPlusPath"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmfPlusPath-Objekt gibt eine Reihe von Linien- und Kurvensegmenten an, die einen Grafikpfad bilden."
type: docs
weight: 58
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusPath extends EmfPlusGraphicsObjectType
```

Das EmfPlusPath‑Objekt gibt eine Reihe von Linien‑ und Kurvensegmenten an, die einen Grafikpfad bilden. Die Reihenfolge der Bezier‑Datenpunkte ist Startpunkt, Kontrollpunkt 1, Kontrollpunkt 2 und Endpunkt. Weitere Informationen siehe[MSDN - DrawBeziers].
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusPath()](#EmfPlusPath--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPathPointFlags()](#getPathPointFlags--) | Liest oder setzt die Anzahl der Pfadpunkte. Ein 32‑Bit vorzeichenloser Integer, der angibt, wie die Punkte und zugehörigen Punkttypen, die von diesem Objekt definiert werden, zu interpretieren sind. |
| [setPathPointFlags(short value)](#setPathPointFlags-short-) | Liest oder setzt die Anzahl der Pfadpunkte. Ein 32‑Bit vorzeichenloser Integer, der angibt, wie die Punkte und zugehörigen Punkttypen, die von diesem Objekt definiert werden, zu interpretieren sind. |
| [getPathPoints()](#getPathPoints--) | Liest oder setzt ein Array von Pfadpunkten. Ein Array von PathPointCount‑Punkten, die den Pfad angeben. |
| [setPathPoints(PointF[] value)](#setPathPoints-com.aspose.imaging.PointF---) | Liest oder setzt ein Array von Pfadpunkten. Ein Array von PathPointCount‑Punkten, die den Pfad angeben. |
| [getPathPointTypes()](#getPathPointTypes--) | Liest oder setzt ein Array, das angibt, wie die Punkte im Feld PathPoints zum Zeichnen des Pfades verwendet werden. |
| [setPathPointTypes(EmfPlusBasePointType[] value)](#setPathPointTypes-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType---) | Liest oder setzt ein Array, das angibt, wie die Punkte im Feld PathPoints zum Zeichnen des Pfades verwendet werden. |
### EmfPlusPath() {#EmfPlusPath--}
```
public EmfPlusPath()
```


### getPathPointFlags() {#getPathPointFlags--}
```
public short getPathPointFlags()
```


Liest oder setzt die Anzahl der Pfadpunkte. Ein 32‑Bit vorzeichenloser Integer, der angibt, wie die Punkte und zugehörigen Punkttypen, die von diesem Objekt definiert werden, zu interpretieren sind.

**Returns:**
short
### setPathPointFlags(short value) {#setPathPointFlags-short-}
```
public void setPathPointFlags(short value)
```


Liest oder setzt die Anzahl der Pfadpunkte. Ein 32‑Bit vorzeichenloser Integer, der angibt, wie die Punkte und zugehörigen Punkttypen, die von diesem Objekt definiert werden, zu interpretieren sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


Liest oder setzt ein Array von Pfadpunkten. Ein Array von PathPointCount‑Punkten, die den Pfad angeben. Der Typ der Objekte in diesem Array wird durch das Feld PathPointFlags bestimmt, wie folgt: Wenn das P‑Flag gesetzt ist, sind die Punkte relative Positionen, die durch EmfPlusPointR‑Objekte (Abschnitt 2.2.2.37) angegeben werden. Wenn das P‑Flag nicht gesetzt und das C‑Flag gesetzt ist, sind die Punkte absolute Positionen, die durch EmfPlusPoint‑Objekte (Abschnitt 2.2.2.35) angegeben werden. Wenn weder das P‑Flag noch das C‑Flag gesetzt ist, sind die Punkte absolute Positionen, die durch EmfPlusPointF‑Objekte (Abschnitt 2.2.2.36) angegeben werden.

**Returns:**
com.aspose.imaging.PointF[]
### setPathPoints(PointF[] value) {#setPathPoints-com.aspose.imaging.PointF---}
```
public void setPathPoints(PointF[] value)
```


Liest oder setzt ein Array von Pfadpunkten. Ein Array von PathPointCount‑Punkten, die den Pfad angeben. Der Typ der Objekte in diesem Array wird durch das Feld PathPointFlags bestimmt, wie folgt: Wenn das P‑Flag gesetzt ist, sind die Punkte relative Positionen, die durch EmfPlusPointR‑Objekte (Abschnitt 2.2.2.37) angegeben werden. Wenn das P‑Flag nicht gesetzt und das C‑Flag gesetzt ist, sind die Punkte absolute Positionen, die durch EmfPlusPoint‑Objekte (Abschnitt 2.2.2.35) angegeben werden. Wenn weder das P‑Flag noch das C‑Flag gesetzt ist, sind die Punkte absolute Positionen, die durch EmfPlusPointF‑Objekte (Abschnitt 2.2.2.36) angegeben werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

### getPathPointTypes() {#getPathPointTypes--}
```
public EmfPlusBasePointType[] getPathPointTypes()
```


Liest oder setzt ein Array, das angibt, wie die Punkte im Feld PathPoints zum Zeichnen des Pfades verwendet werden. Der Typ der Objekte in diesem Array wird durch das R‑Flag im Feld PathPointFlags bestimmt.

Wert: Die Pfadpunkttypen.

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType[]
### setPathPointTypes(EmfPlusBasePointType[] value) {#setPathPointTypes-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType---}
```
public void setPathPointTypes(EmfPlusBasePointType[] value)
```


Liest oder setzt ein Array, das angibt, wie die Punkte im Feld PathPoints zum Zeichnen des Pfades verwendet werden. Der Typ der Objekte in diesem Array wird durch das R‑Flag im Feld PathPointFlags bestimmt.

Wert: Die Pfadpunkttypen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPlusBasePointType\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype) |  |

