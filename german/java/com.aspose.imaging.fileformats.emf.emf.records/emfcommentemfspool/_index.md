---
title: "EmfCommentEmfSpool"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_COMMENT_EMFSPOOL-Datensatz enthält eingebettete EMFSPOOL‑Datensätze."
type: docs
weight: 28
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public final class EmfCommentEmfSpool extends EmfCommentRecordType
```

Der EMR\_COMMENT\_EMFSPOOL-Datensatz enthält eingebettete EMFSPOOL‑Datensätze. Hinweis: Felder, die in diesem Abschnitt nicht beschrieben werden, sind in Abschnitt 2.3.3 angegeben.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfCommentEmfSpool(EmfRecord source)](#EmfCommentEmfSpool-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der Klasse `EmfCommentEmfSpool`. |
| [EmfCommentEmfSpool()](#EmfCommentEmfSpool--) | Initialisiert eine neue Instanz der Klasse `EmfCommentEmfSpool`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die diesen Kommentar‑Datensatz als enthaltend EMFSPOOL‑Datensätze identifiziert. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die diesen Kommentar‑Datensatz als enthaltend EMFSPOOL‑Datensätze identifiziert. |
| [getEmfSpoolRecordIdentifier()](#getEmfSpoolRecordIdentifier--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Typ des EMR\_COMMENT\_EMFSPOOL‑Datensatzes identifiziert. |
| [setEmfSpoolRecordIdentifier(int value)](#setEmfSpoolRecordIdentifier-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Typ des EMR\_COMMENT\_EMFSPOOL‑Datensatzes identifiziert. |
| [getEmfSpoolRecords()](#getEmfSpoolRecords--) | Liest oder setzt ein variabel langes Byte‑Array, das einen oder mehrere EMFSPOOL‑Schriftdefinitions‑Datensätze enthält ([MS-EMFSPOOL] Abschnitt 2.2.3.3). |
| [setEmfSpoolRecords(EmfSpoolFontDefinitionRecordType[] value)](#setEmfSpoolRecords-com.aspose.imaging.fileformats.emf.emfspool.records.EmfSpoolFontDefinitionRecordType---) | Liest oder setzt ein variabel langes Byte‑Array, das einen oder mehrere EMFSPOOL‑Schriftdefinitions‑Datensätze enthält ([MS-EMFSPOOL] Abschnitt 2.2.3.3). |
### EmfCommentEmfSpool(EmfRecord source) {#EmfCommentEmfSpool-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentEmfSpool(EmfRecord source)
```


Initialisiert eine neue Instanz der Klasse `EmfCommentEmfSpool`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfCommentEmfSpool() {#EmfCommentEmfSpool--}
```
public EmfCommentEmfSpool()
```


Initialisiert eine neue Instanz der Klasse `EmfCommentEmfSpool`.

### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die diesen Kommentar‑Datensatz als enthaltend EMFSPOOL‑Datensätze identifiziert. Der Wert 0x00000000 kennzeichnet ihn als EMR\_COMMENT\_EMFSPOOL‑Datensatz.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die diesen Kommentar‑Datensatz als enthaltend EMFSPOOL‑Datensätze identifiziert. Der Wert 0x00000000 kennzeichnet ihn als EMR\_COMMENT\_EMFSPOOL‑Datensatz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getEmfSpoolRecordIdentifier() {#getEmfSpoolRecordIdentifier--}
```
public int getEmfSpoolRecordIdentifier()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Typ des EMR\_COMMENT\_EMFSPOOL‑Datensatzes identifiziert.

**Returns:**
int
### setEmfSpoolRecordIdentifier(int value) {#setEmfSpoolRecordIdentifier-int-}
```
public void setEmfSpoolRecordIdentifier(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Typ des EMR\_COMMENT\_EMFSPOOL‑Datensatzes identifiziert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getEmfSpoolRecords() {#getEmfSpoolRecords--}
```
public EmfSpoolFontDefinitionRecordType[] getEmfSpoolRecords()
```


Liest oder setzt ein variabel langes Byte‑Array, das einen oder mehrere EMFSPOOL‑Schriftdefinitions‑Datensätze enthält ([MS-EMFSPOOL] Abschnitt 2.2.3.3).

**Returns:**
com.aspose.imaging.fileformats.emf.emfspool.records.EmfSpoolFontDefinitionRecordType[]
### setEmfSpoolRecords(EmfSpoolFontDefinitionRecordType[] value) {#setEmfSpoolRecords-com.aspose.imaging.fileformats.emf.emfspool.records.EmfSpoolFontDefinitionRecordType---}
```
public void setEmfSpoolRecords(EmfSpoolFontDefinitionRecordType[] value)
```


Liest oder setzt ein variabel langes Byte‑Array, das einen oder mehrere EMFSPOOL‑Schriftdefinitions‑Datensätze enthält ([MS-EMFSPOOL] Abschnitt 2.2.3.3).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfSpoolFontDefinitionRecordType\[\]](../../com.aspose.imaging.fileformats.emf.emfspool.records/emfspoolfontdefinitionrecordtype) |  |

