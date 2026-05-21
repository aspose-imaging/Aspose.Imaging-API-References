---
title: "EmfSetTextJustification"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_SETTEXTJUSTIFICATION‑Datensatz gibt die Menge des zusätzlichen Abstands an, der zu Trennzeichen für die Textausrichtung hinzugefügt wird."
type: docs
weight: 141
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfsettextjustification/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetTextJustification extends EmfStateRecordType
```

Der EMR\_SETTEXTJUSTIFICATION-Datensatz gibt die Menge zusätzlichen Raums an, der zu Trennzeichen für die Text­ausrichtung hinzugefügt wird.

Anstatt einen EMR\_SETTEXTJUSTIFICATION‑Datensatz zu verwenden, SOLLTE eine Implementierung einen EMR\_EXTTEXTOUTW‑Datensatz (Abschnitt 2.3.5.8) nutzen, um diese Funktion auszuführen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfSetTextJustification(EmfRecord source)](#EmfSetTextJustification-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfSetTextJustification`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getNBreakExtra()](#getNBreakExtra--) | Ruft einen 32‑Bit‑vorzeichenbehafteten Integer ab oder legt ihn fest, der die gesamte Menge zusätzlichen Speicherplatzes in logischen Einheiten angibt, die hinzugefügt werden soll. |
| [setNBreakExtra(int value)](#setNBreakExtra-int-) | Ruft einen 32‑Bit‑vorzeichenbehafteten Integer ab oder legt ihn fest, der die gesamte Menge zusätzlichen Speicherplatzes in logischen Einheiten angibt, die hinzugefügt werden soll. |
| [getNBreakCount()](#getNBreakCount--) | Ruft einen 32‑Bit‑vorzeichenbehafteten Integer ab oder legt ihn fest, der die Anzahl der Trennzeichen angibt. |
| [setNBreakCount(int value)](#setNBreakCount-int-) | Ruft einen 32‑Bit‑vorzeichenbehafteten Integer ab oder legt ihn fest, der die Anzahl der Trennzeichen angibt. |
### EmfSetTextJustification(EmfRecord source) {#EmfSetTextJustification-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetTextJustification(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfSetTextJustification`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### getNBreakExtra() {#getNBreakExtra--}
```
public int getNBreakExtra()
```


Ruft einen 32‑Bit‑vorzeichenbehafteten Integer ab oder legt ihn fest, der die gesamte Menge zusätzlichen Speicherplatzes in logischen Einheiten angibt, die hinzugefügt werden soll.

**Returns:**
int
### setNBreakExtra(int value) {#setNBreakExtra-int-}
```
public void setNBreakExtra(int value)
```


Ruft einen 32‑Bit‑vorzeichenbehafteten Integer ab oder legt ihn fest, der die gesamte Menge zusätzlichen Speicherplatzes in logischen Einheiten angibt, die hinzugefügt werden soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getNBreakCount() {#getNBreakCount--}
```
public int getNBreakCount()
```


Ruft einen 32‑Bit‑vorzeichenbehafteten Integer ab oder legt ihn fest, der die Anzahl der Trennzeichen angibt.

**Returns:**
int
### setNBreakCount(int value) {#setNBreakCount-int-}
```
public void setNBreakCount(int value)
```


Ruft einen 32‑Bit‑vorzeichenbehafteten Integer ab oder legt ihn fest, der die Anzahl der Trennzeichen angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

