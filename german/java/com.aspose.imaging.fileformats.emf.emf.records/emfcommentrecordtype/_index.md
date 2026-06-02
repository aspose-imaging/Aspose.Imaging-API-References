---
title: "EmfCommentRecordType"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Kommentar‑Datensatztypen definieren Formate zum Festlegen beliebiger privater Daten‑Einbettungsdatensätze in anderen Metadateiformaten und zum Hinzufügen neuer oder spezieller Befehle."
type: docs
weight: 32
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public abstract class EmfCommentRecordType extends EmfRecord
```

Die Kommentar-Datensatztypen definieren Formate zur Angabe beliebiger privater Daten, zum Einbetten von Datensätzen in andere Metadateiformate und zum Hinzufügen neuer oder spezieller Befehle.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDataSize()](#getDataSize--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe (in Bytes) der Felder CommentIdentifier und CommentRecordParm im nachfolgenden RecordBuffer‑Feld angibt. |
| [setDataSize(int value)](#setDataSize-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe (in Bytes) der Felder CommentIdentifier und CommentRecordParm im nachfolgenden RecordBuffer‑Feld angibt. |
| [getCommentIdentifier()](#getCommentIdentifier--) | Liest oder setzt den Kommentar-Identifikator. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Liest oder setzt den Kommentar-Identifikator. |
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe (in Bytes) der Felder CommentIdentifier und CommentRecordParm im nachfolgenden RecordBuffer‑Feld angibt. Sie MUSS die Größe ihrer selbst oder die Größe des AlignmentPadding‑Feldes, falls vorhanden, nicht enthalten.

**Returns:**
int
### setDataSize(int value) {#setDataSize-int-}
```
public void setDataSize(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe (in Bytes) der Felder CommentIdentifier und CommentRecordParm im nachfolgenden RecordBuffer‑Feld angibt. Sie MUSS die Größe ihrer selbst oder die Größe des AlignmentPadding‑Feldes, falls vorhanden, nicht enthalten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Liest oder setzt den Kommentar-Identifikator.

Wert: Der Kommentar-Identifikator.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Liest oder setzt den Kommentar-Identifikator.

Wert: Der Kommentar-Identifikator.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

