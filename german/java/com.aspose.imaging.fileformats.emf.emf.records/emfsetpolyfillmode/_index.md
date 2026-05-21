---
title: "EmfSetPolyFillMode"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_SETPOLYFILLMODE‑Datensatz definiert den Polygon‑Füllmodus."
type: docs
weight: 136
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetPolyFillMode extends EmfStateRecordType
```

Der EMR\_SETPOLYFILLMODE-Datensatz definiert den Polygon‑Füllmodus.

Im Allgemeinen unterscheiden sich die Modi nur in Fällen, in denen ein komplexes, überlappendes Polygon AUSGEFÜLLT werden MUSS; zum Beispiel ein fünfseitiges Polygon, das einen fünfzackigen Stern mit einem Pentagon in der Mitte bildet. In solchen Fällen SOLLTE der ALTERNATE‑Modus jedes zweite eingeschlossene Gebiet innerhalb des Polygons (die Spitzen des Sterns) füllen, während der WINDING‑Modus alle Gebiete (die Spitzen des Sterns und das Pentagon) füllen SOLLTE. Wenn der Füllmodus ALTERNATE ist, SOLLTE der Bereich zwischen ungeraden und geraden Polygonseiten auf jeder Scan‑Zeile gefüllt werden. Das heißt, der Bereich zwischen der ersten und zweiten Seite SOLLTE gefüllt werden, ebenso zwischen der dritten und vierten Seite usw. Wenn der Füllmodus WINDING ist, SOLLTE jedes Gebiet, das einen von Null verschiedenen Windungswert hat, gefüllt werden. Der Windungswert ist die Anzahl der Male, die ein Stift, der das Polygon zeichnet, das Gebiet umkreist. Die Richtung jeder Kante des Polygons ist bedeutend.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfSetPolyFillMode(EmfRecord source)](#EmfSetPolyFillMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der Klasse `EmfSetPolyFillMode`. |
| [EmfSetPolyFillMode()](#EmfSetPolyFillMode--) | Initialisiert eine neue Instanz der Klasse `EmfSetPolyFillMode`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPolygonFillMode()](#getPolygonFillMode--) | Liest oder legt eine 32‑Bit‑vorzeichenlose Ganzzahl fest, die den Polygon‑Füllmodus angibt und MUSS in der PolygonFillMode‑Aufzählung (Abschnitt 2.1.27) enthalten sein. |
| [setPolygonFillMode(int value)](#setPolygonFillMode-int-) | Liest oder legt eine 32‑Bit‑vorzeichenlose Ganzzahl fest, die den Polygon‑Füllmodus angibt und MUSS in der PolygonFillMode‑Aufzählung (Abschnitt 2.1.27) enthalten sein. |
### EmfSetPolyFillMode(EmfRecord source) {#EmfSetPolyFillMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetPolyFillMode(EmfRecord source)
```


Initialisiert eine neue Instanz der Klasse `EmfSetPolyFillMode`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfSetPolyFillMode() {#EmfSetPolyFillMode--}
```
public EmfSetPolyFillMode()
```


Initialisiert eine neue Instanz der Klasse `EmfSetPolyFillMode`.

### getPolygonFillMode() {#getPolygonFillMode--}
```
public int getPolygonFillMode()
```


Liest oder legt eine 32‑Bit‑vorzeichenlose Ganzzahl fest, die den Polygon‑Füllmodus angibt und MUSS in der PolygonFillMode‑Aufzählung (Abschnitt 2.1.27) enthalten sein.

**Returns:**
int
### setPolygonFillMode(int value) {#setPolygonFillMode-int-}
```
public void setPolygonFillMode(int value)
```


Liest oder legt eine 32‑Bit‑vorzeichenlose Ganzzahl fest, die den Polygon‑Füllmodus angibt und MUSS in der PolygonFillMode‑Aufzählung (Abschnitt 2.1.27) enthalten sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

