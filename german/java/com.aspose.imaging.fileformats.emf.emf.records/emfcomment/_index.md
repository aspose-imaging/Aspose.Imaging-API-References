---
title: "EmfComment"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_COMMENT-Datensatz enthält beliebige private Daten."
type: docs
weight: 25
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfcomment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public final class EmfComment extends EmfCommentRecordType
```

Der EMR\_COMMENT-Datensatz enthält beliebige private Daten. Hinweis: Felder, die in diesem Abschnitt nicht beschrieben werden, sind in Abschnitt 2.3.3 angegeben.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfComment(EmfRecord source)](#EmfComment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfComment`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPrivateData()](#getPrivateData--) | Liest oder setzt ein optionales Byte-Array, das die privaten Daten angibt. |
| [setPrivateData(byte[] value)](#setPrivateData-byte---) | Liest oder setzt ein optionales Byte-Array, das die privaten Daten angibt. |
| [getCommentIdentifier()](#getCommentIdentifier--) | Liest oder setzt den Kommentar-Identifikator. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Liest oder setzt den Kommentar-Identifikator. |
### EmfComment(EmfRecord source) {#EmfComment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfComment(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfComment`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### getPrivateData() {#getPrivateData--}
```
public byte[] getPrivateData()
```


Liest oder setzt ein optionales Byte-Array, das die privaten Daten angibt. Das erste DWORD dieser Daten DÜRFT NICHT einer der vordefinierten Kommentar-Identifikatorwerte sein, die in Abschnitt 2.3.3 angegeben sind. Private Daten sind EMF unbekannt; sie sind nur für Anwendungen von Bedeutung, die das Datenformat kennen und wissen, wie sie zu verwenden sind. EMR\_COMMENT-Privatdatensätze KÖNNTEN ignoriert werden.

**Returns:**
byte[]
### setPrivateData(byte[] value) {#setPrivateData-byte---}
```
public void setPrivateData(byte[] value)
```


Liest oder setzt ein optionales Byte-Array, das die privaten Daten angibt. Das erste DWORD dieser Daten DÜRFT NICHT einer der vordefinierten Kommentar-Identifikatorwerte sein, die in Abschnitt 2.3.3 angegeben sind. Private Daten sind EMF unbekannt; sie sind nur für Anwendungen von Bedeutung, die das Datenformat kennen und wissen, wie sie zu verwenden sind. EMR\_COMMENT-Privatdatensätze KÖNNTEN ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

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

