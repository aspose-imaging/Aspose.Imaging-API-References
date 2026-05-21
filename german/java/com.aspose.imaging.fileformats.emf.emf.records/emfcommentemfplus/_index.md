---
title: "EmfCommentEmfPlus"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_COMMENT_EMFPLUS‑Datensatz enthält eingebettete EMF‑Datensätze."
type: docs
weight: 27
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public final class EmfCommentEmfPlus extends EmfCommentRecordType
```

Der EMR\_COMMENT\_EMFPLUS‑Datensatz enthält eingebettete EMF+‑Datensätze. Hinweis: Felder, die in diesem Abschnitt nicht beschrieben werden, sind in Abschnitt 2.3.3 angegeben.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfCommentEmfPlus(EmfRecord source)](#EmfCommentEmfPlus-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfCommentEmfPlus`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die diesen Kommentar‑Datensatz als enthaltend EMF+‑Datensätze identifiziert. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die diesen Kommentar‑Datensatz als enthaltend EMF+‑Datensätze identifiziert. |
| [getEmfPlusRecords()](#getEmfPlusRecords--) | Liest oder setzt ein Byte‑Array, das einen oder mehrere EMF+‑Datensätze enthält ([MS-EMFPLUS] Abschnitt 2.3.1). |
| [setEmfPlusRecords(EmfPlusRecord[] value)](#setEmfPlusRecords-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord---) | Liest oder setzt ein Byte‑Array, das einen oder mehrere EMF+‑Datensätze enthält ([MS-EMFPLUS] Abschnitt 2.3.1). |
### EmfCommentEmfPlus(EmfRecord source) {#EmfCommentEmfPlus-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentEmfPlus(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfCommentEmfPlus`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die diesen Kommentar‑Datensatz als enthaltend EMF+‑Datensätze identifiziert. Der Wert 0x2B464D45, der die ASCII‑Zeichenkette "+FME" ist, identifiziert ihn als EMR\_COMMENT\_EMFPLUS‑Datensatz.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die diesen Kommentar‑Datensatz als enthaltend EMF+‑Datensätze identifiziert. Der Wert 0x2B464D45, der die ASCII‑Zeichenkette "+FME" ist, identifiziert ihn als EMR\_COMMENT\_EMFPLUS‑Datensatz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getEmfPlusRecords() {#getEmfPlusRecords--}
```
public EmfPlusRecord[] getEmfPlusRecords()
```


Liest oder setzt ein Byte‑Array, das einen oder mehrere EMF+‑Datensätze enthält ([MS-EMFPLUS] Abschnitt 2.3.1).

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord[]
### setEmfPlusRecords(EmfPlusRecord[] value) {#setEmfPlusRecords-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord---}
```
public void setEmfPlusRecords(EmfPlusRecord[] value)
```


Liest oder setzt ein Byte‑Array, das einen oder mehrere EMF+‑Datensätze enthält ([MS-EMFPLUS] Abschnitt 2.3.1).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPlusRecord\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) |  |

