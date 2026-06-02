---
title: "EmfSetPaletteEntries"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_SETPALETTEENTRIES‑Datensatz definiert RGB‑Farbwerte in einem Bereich von Einträgen für ein vorhandenes LogPalette‑Objekt (Abschnitt 2.2.17)."
type: docs
weight: 134
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfSetPaletteEntries extends EmfObjectManipulationRecordType
```

Der EMR\_SETPALETTEENTRIES-Datensatz definiert RGB‑Farbwerte in einem Bereich von Einträgen für ein bestehendes LogPalette‑Objekt (Abschnitt 2.2.17).
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfSetPaletteEntries(EmfRecord source)](#EmfSetPaletteEntries-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfSetPaletteEntries`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getIhPal()](#getIhPal--) | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die den Index der Palette‑EMF‑Objekttabelle angibt. |
| [setIhPal(int value)](#setIhPal-int-) | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die den Index der Palette‑EMF‑Objekttabelle angibt. |
| [getStart()](#getStart--) | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die den Index des ersten zu setzenden Eintrags angibt. |
| [setStart(int value)](#setStart-int-) | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die den Index des ersten zu setzenden Eintrags angibt. |
| [getNumberofEntries()](#getNumberofEntries--) | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die Anzahl der Einträge angibt. |
| [setNumberofEntries(int value)](#setNumberofEntries-int-) | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die Anzahl der Einträge angibt. |
| [getArgb32PalEntries()](#getArgb32PalEntries--) | Liest oder setzt ein Array von LogPaletteEntry‑Objekten (Abschnitt 2.2.18) mit der Länge NumberOfEntries, das die Paletteneintragsdaten angibt. |
| [setArgb32PalEntries(int[] value)](#setArgb32PalEntries-int---) | Liest oder setzt ein Array von LogPaletteEntry‑Objekten (Abschnitt 2.2.18) mit der Länge NumberOfEntries, das die Paletteneintragsdaten angibt. |
### EmfSetPaletteEntries(EmfRecord source) {#EmfSetPaletteEntries-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetPaletteEntries(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfSetPaletteEntries`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die den Index der Palette‑EMF‑Objekttabelle angibt.

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die den Index der Palette‑EMF‑Objekttabelle angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getStart() {#getStart--}
```
public int getStart()
```


Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die den Index des ersten zu setzenden Eintrags angibt.

**Returns:**
int
### setStart(int value) {#setStart-int-}
```
public void setStart(int value)
```


Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die den Index des ersten zu setzenden Eintrags angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getNumberofEntries() {#getNumberofEntries--}
```
public int getNumberofEntries()
```


Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die Anzahl der Einträge angibt.

**Returns:**
int
### setNumberofEntries(int value) {#setNumberofEntries-int-}
```
public void setNumberofEntries(int value)
```


Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die Anzahl der Einträge angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getArgb32PalEntries() {#getArgb32PalEntries--}
```
public int[] getArgb32PalEntries()
```


Liest oder setzt ein Array von LogPaletteEntry‑Objekten (Abschnitt 2.2.18) mit der Länge NumberOfEntries, das die Paletteneintragsdaten angibt. Die Values‑Mitglieder enthalten keine Werte.

**Returns:**
int[]
### setArgb32PalEntries(int[] value) {#setArgb32PalEntries-int---}
```
public void setArgb32PalEntries(int[] value)
```


Liest oder setzt ein Array von LogPaletteEntry‑Objekten (Abschnitt 2.2.18) mit der Länge NumberOfEntries, das die Paletteneintragsdaten angibt. Die Values‑Mitglieder enthalten keine Werte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] |  |

