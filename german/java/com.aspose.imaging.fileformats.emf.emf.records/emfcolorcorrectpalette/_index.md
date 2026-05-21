---
title: "EmfColorCorrectPalette"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_COLORCORRECTPALETTE‑Datensatz gibt an, wie die Einträge eines logischen Palettenobjekts mithilfe von WCS‑1.0‑Werten korrigiert werden."
type: docs
weight: 23
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfcolorcorrectpalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfColorCorrectPalette extends EmfObjectManipulationRecordType
```

Der EMR\_COLORCORRECTPALETTE-Datensatz gibt an, wie die Einträge eines logischen Palettenobjekts mit WCS‑1.0‑Werten korrigiert werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfColorCorrectPalette(EmfRecord source)](#EmfColorCorrectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfColorCorrectPalette`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getIhPalette()](#getIhPalette--) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab, der den Index eines logischen Palettenobjekts (Abschnitt 2.2.17) in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt. |
| [setIhPalette(int value)](#setIhPalette-int-) | Legt einen 32‑Bit‑vorzeichenlosen Integer fest, der den Index eines logischen Palettenobjekts (Abschnitt 2.2.17) in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt. |
| [getNFirstEntry()](#getNFirstEntry--) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab, der den Index des ersten zu korrigierenden Eintrags angibt. |
| [setNFirstEntry(int value)](#setNFirstEntry-int-) | Legt einen 32‑Bit‑vorzeichenlosen Integer fest, der den Index des ersten zu korrigierenden Eintrags angibt. |
| [getNPalEntries()](#getNPalEntries--) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab, der die Anzahl der zu korrigierenden Paletteneinträge angibt. |
| [setNPalEntries(int value)](#setNPalEntries-int-) | Legt einen 32‑Bit‑vorzeichenlosen Integer fest, der die Anzahl der zu korrigierenden Paletteneinträge angibt. |
### EmfColorCorrectPalette(EmfRecord source) {#EmfColorCorrectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfColorCorrectPalette(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfColorCorrectPalette`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### getIhPalette() {#getIhPalette--}
```
public int getIhPalette()
```


Ruft einen 32‑Bit‑vorzeichenlosen Integer ab, der den Index eines logischen Palettenobjekts (Abschnitt 2.2.17) in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt.

**Returns:**
int
### setIhPalette(int value) {#setIhPalette-int-}
```
public void setIhPalette(int value)
```


Legt einen 32‑Bit‑vorzeichenlosen Integer fest, der den Index eines logischen Palettenobjekts (Abschnitt 2.2.17) in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getNFirstEntry() {#getNFirstEntry--}
```
public int getNFirstEntry()
```


Ruft einen 32‑Bit‑vorzeichenlosen Integer ab, der den Index des ersten zu korrigierenden Eintrags angibt.

**Returns:**
int
### setNFirstEntry(int value) {#setNFirstEntry-int-}
```
public void setNFirstEntry(int value)
```


Legt einen 32‑Bit‑vorzeichenlosen Integer fest, der den Index des ersten zu korrigierenden Eintrags angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getNPalEntries() {#getNPalEntries--}
```
public int getNPalEntries()
```


Ruft einen 32‑Bit‑vorzeichenlosen Integer ab, der die Anzahl der zu korrigierenden Paletteneinträge angibt.

**Returns:**
int
### setNPalEntries(int value) {#setNPalEntries-int-}
```
public void setNPalEntries(int value)
```


Legt einen 32‑Bit‑vorzeichenlosen Integer fest, der die Anzahl der zu korrigierenden Paletteneinträge angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

