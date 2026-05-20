---
title: "EmfSelectPalette"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_SELECTPALETTE‑Datensatz definiert eine logische Palette für den Wiedergabegeräte‑Kontext."
type: docs
weight: 117
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfselectpalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfSelectPalette extends EmfObjectManipulationRecordType
```

Der EMR\_SELECTPALETTE-Datensatz spezifiziert eine logische Palette für den Wiedergabe‑Gerätekontext.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfSelectPalette(EmfRecord source)](#EmfSelectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfSelectPalette`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getIhPal()](#getIhPal--) | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die entweder den Index eines LogPalette‑Objekts (Abschnitt 2.2.17) in der EMF‑Objekttabelle oder den Wert DEFAULT\_PALETTE angibt, welcher der Index einer Standardobjekt‑Palette aus der StockObject‑Aufzählung (Abschnitt 2.1.31) ist. |
| [setIhPal(int value)](#setIhPal-int-) | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die entweder den Index eines LogPalette‑Objekts (Abschnitt 2.2.17) in der EMF‑Objekttabelle oder den Wert DEFAULT\_PALETTE angibt, welcher der Index einer Standardobjekt‑Palette aus der StockObject‑Aufzählung (Abschnitt 2.1.31) ist. |
### EmfSelectPalette(EmfRecord source) {#EmfSelectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSelectPalette(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfSelectPalette`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die entweder den Index eines LogPalette‑Objekts (Abschnitt 2.2.17) in der EMF‑Objekttabelle oder den Wert DEFAULT\_PALETTE angibt, welcher der Index einer Standardobjekt‑Palette aus der StockObject‑Aufzählung (Abschnitt 2.1.31) ist.

Dieser Wert DARF NICHT null sein oder den Index eines anderen Standardobjekts haben.

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die entweder den Index eines LogPalette‑Objekts (Abschnitt 2.2.17) in der EMF‑Objekttabelle oder den Wert DEFAULT\_PALETTE angibt, welcher der Index einer Standardobjekt‑Palette aus der StockObject‑Aufzählung (Abschnitt 2.1.31) ist.

Dieser Wert DARF NICHT null sein oder den Index eines anderen Standardobjekts haben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

