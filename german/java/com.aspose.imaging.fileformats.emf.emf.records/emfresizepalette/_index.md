---
title: "EmfResizePalette"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_RESIZEPALETTE‑Datensatz vergrößert oder verkleinert die Größe eines vorhandenen LogPalette‑Objekts (Abschnitt 2.2.17)."
type: docs
weight: 108
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfresizepalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfResizePalette extends EmfObjectManipulationRecordType
```

Der EMR\_RESIZEPALETTE-Datensatz vergrößert oder verkleinert die Größe eines bestehenden LogPalette-Objekts (Abschnitt 2.2.17).

Die neue Größe des LogPalette‑Objekts MUSS im Feld NumberOfEntries dieser Struktur wiedergegeben werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfResizePalette(EmfRecord source)](#EmfResizePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfResizePalette`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getIhPal()](#getIhPal--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des Palettenobjekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt. |
| [setIhPal(int value)](#setIhPal-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des Palettenobjekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt. |
### EmfResizePalette(EmfRecord source) {#EmfResizePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfResizePalette(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfResizePalette`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des Palettenobjekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt.

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des Palettenobjekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

