---
title: "EmfSetRop2"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_SETROP2-Datensatz definiert einen binären Rasteroperation‑Modus."
type: docs
weight: 137
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetrop2/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetRop2 extends EmfStateRecordType
```

Der EMR\_SETROP2-Datensatz definiert einen binären Raster‑Operations‑Modus.

Binäre Rasteroperations‑Mischmodi definieren, wie Quell‑ und Ziel­farben beim Zeichnen mit dem aktuellen Stift kombiniert werden. Die Mischmodi sind binäre Rasteroperations‑Codes, die alle möglichen booleschen Funktionen von zwei Variablen darstellen, unter Verwendung der binären Operationen AND, OR und XOR (exclusive OR) sowie der unären Operation NOT. Der Mischmodus gilt nur für Rastergeräte; er ist für Vektorggeräte nicht verfügbar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfSetRop2(EmfRecord source)](#EmfSetRop2-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfSetRop2`‑Klasse. |
| [EmfSetRop2()](#EmfSetRop2--) | Initialisiert eine neue Instanz der `EmfSetRop2`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRop2Mode()](#getRop2Mode--) | Liest oder setzt ein 32‑Bit vorzeichenloser Integer, der den Rasteroperations‑Modus angibt und MUSS in der WMF‑Binary‑Raster‑Op‑Aufzählung ([MS-WMF] Abschnitt 2.1.1.2) enthalten sein. |
| [setRop2Mode(int value)](#setRop2Mode-int-) | Liest oder setzt ein 32‑Bit vorzeichenloser Integer, der den Rasteroperations‑Modus angibt und MUSS in der WMF‑Binary‑Raster‑Op‑Aufzählung ([MS-WMF] Abschnitt 2.1.1.2) enthalten sein. |
### EmfSetRop2(EmfRecord source) {#EmfSetRop2-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetRop2(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfSetRop2`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfSetRop2() {#EmfSetRop2--}
```
public EmfSetRop2()
```


Initialisiert eine neue Instanz der `EmfSetRop2`‑Klasse.

### getRop2Mode() {#getRop2Mode--}
```
public int getRop2Mode()
```


Liest oder setzt ein 32‑Bit vorzeichenloser Integer, der den Rasteroperations‑Modus angibt und MUSS in der WMF‑Binary‑Raster‑Op‑Aufzählung ([MS-WMF] Abschnitt 2.1.1.2) enthalten sein.

**Returns:**
int
### setRop2Mode(int value) {#setRop2Mode-int-}
```
public void setRop2Mode(int value)
```


Liest oder setzt ein 32‑Bit vorzeichenloser Integer, der den Rasteroperations‑Modus angibt und MUSS in der WMF‑Binary‑Raster‑Op‑Aufzählung ([MS-WMF] Abschnitt 2.1.1.2) enthalten sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

