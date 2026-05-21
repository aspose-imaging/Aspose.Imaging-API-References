---
title: "EmfCommentPublicRecordType"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die EMR_COMMENT_PUBLIC-Datensatztypen geben Erweiterungen der EMF‑Verarbeitung an."
type: docs
weight: 31
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public abstract class EmfCommentPublicRecordType extends EmfCommentRecordType
```

Die EMR\_COMMENT\_PUBLIC-Datensatztypen geben Erweiterungen für die EMF-Verarbeitung an.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die diesen Kommentar-Datensatz als Angabe öffentlicher Daten identifiziert. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die diesen Kommentar-Datensatz als Angabe öffentlicher Daten identifiziert. |
| [getPublicCommentIdentifier()](#getPublicCommentIdentifier--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Typ des öffentlichen Kommentar‑Datensatzes identifiziert. |
| [setPublicCommentIdentifier(long value)](#setPublicCommentIdentifier-long-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Typ des öffentlichen Kommentar‑Datensatzes identifiziert. |
### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die diesen Kommentar-Datensatz als Angabe öffentlicher Daten identifiziert. Der Wert 0x43494447, der die ASCII‑Zeichenkette "CIDG" ist, identifiziert dies als EMR\_COMMENT\_PUBLIC‑Datensatz.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die diesen Kommentar-Datensatz als Angabe öffentlicher Daten identifiziert. Der Wert 0x43494447, der die ASCII‑Zeichenkette "CIDG" ist, identifiziert dies als EMR\_COMMENT\_PUBLIC‑Datensatz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getPublicCommentIdentifier() {#getPublicCommentIdentifier--}
```
public long getPublicCommentIdentifier()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Typ des öffentlichen Kommentar‑Datensatzes identifiziert. Dieser SOLLTE einer der in der vorhergehenden Tabelle aufgeführten Werte sein, die in der EmrComment‑Aufzählung (Abschnitt 2.1.10) definiert sind, sofern nicht zusätzliche öffentliche Kommentar‑Datensatztypen auf dem Druckserver implementiert wurden.

**Returns:**
long
### setPublicCommentIdentifier(long value) {#setPublicCommentIdentifier-long-}
```
public void setPublicCommentIdentifier(long value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Typ des öffentlichen Kommentar‑Datensatzes identifiziert. Dieser SOLLTE einer der in der vorhergehenden Tabelle aufgeführten Werte sein, die in der EmrComment‑Aufzählung (Abschnitt 2.1.10) definiert sind, sofern nicht zusätzliche öffentliche Kommentar‑Datensatztypen auf dem Druckserver implementiert wurden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

