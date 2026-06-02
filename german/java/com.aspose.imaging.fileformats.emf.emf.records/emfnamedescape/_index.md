---
title: "EmfNamedEscape"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der MR_NAMEDESCAPE‑Datensatz übergibt beliebige Informationen an einen angegebenen Druckertreiber."
type: docs
weight: 75
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfnamedescape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfEscapeRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype)
```
public final class EmfNamedEscape extends EmfEscapeRecordType
```

Der MR\\_NAMEDESCAPE-Datensatz übergibt beliebige Informationen an einen angegebenen Druckertreiber.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfNamedEscape(EmfRecord source)](#EmfNamedEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfNamedEscape`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCjDriver()](#getCjDriver--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Anzahl der Bytes im Feld DriverName angibt. |
| [setCjDriver(int value)](#setCjDriver-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Anzahl der Bytes im Feld DriverName angibt. |
| [getCjIn()](#getCjIn--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Anzahl der Bytes angibt, die an den Druckertreiber übergeben werden. |
| [setCjIn(int value)](#setCjIn-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Anzahl der Bytes angibt, die an den Druckertreiber übergeben werden. |
| [getDriverName()](#getDriverName--) | Liest oder setzt eine Zeichenkette aus 16‑Bit‑Unicode‑Zeichen, die den Namen des Druckertreibers angibt, der die Daten empfängt. |
| [setDriverName(String value)](#setDriverName-java.lang.String-) | Liest oder setzt eine Zeichenkette aus 16‑Bit‑Unicode‑Zeichen, die den Namen des Druckertreibers angibt, der die Daten empfängt. |
| [getData()](#getData--) | Liest oder setzt die Daten, die an den Druckertreiber übergeben werden. |
| [setData(byte[] value)](#setData-byte---) | Liest oder setzt die Daten, die an den Druckertreiber übergeben werden. |
### EmfNamedEscape(EmfRecord source) {#EmfNamedEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfNamedEscape(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfNamedEscape`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### getCjDriver() {#getCjDriver--}
```
public int getCjDriver()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Anzahl der Bytes im Feld DriverName angibt. Dieser Wert MUSS eine gerade Zahl sein.

**Returns:**
int
### setCjDriver(int value) {#setCjDriver-int-}
```
public void setCjDriver(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Anzahl der Bytes im Feld DriverName angibt. Dieser Wert MUSS eine gerade Zahl sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getCjIn() {#getCjIn--}
```
public int getCjIn()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Anzahl der Bytes angibt, die an den Druckertreiber übergeben werden.

**Returns:**
int
### setCjIn(int value) {#setCjIn-int-}
```
public void setCjIn(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Anzahl der Bytes angibt, die an den Druckertreiber übergeben werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getDriverName() {#getDriverName--}
```
public String getDriverName()
```


Liest oder setzt eine Zeichenkette aus 16‑Bit‑Unicode‑Zeichen, die den Namen des Druckertreibers angibt, der die Daten empfängt. Dieser Wert MUSS cjDriver Bytes lang sein und MUSS mit einem Nullzeichen abgeschlossen werden.

**Returns:**
java.lang.String
### setDriverName(String value) {#setDriverName-java.lang.String-}
```
public void setDriverName(String value)
```


Liest oder setzt eine Zeichenkette aus 16‑Bit‑Unicode‑Zeichen, die den Namen des Druckertreibers angibt, der die Daten empfängt. Dieser Wert MUSS cjDriver Bytes lang sein und MUSS mit einem Nullzeichen abgeschlossen werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getData() {#getData--}
```
public byte[] getData()
```


Liest oder setzt die Daten, die an den Druckertreiber übergeben werden. Es MUSS cjIn Bytes verfügbar sein.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Liest oder setzt die Daten, die an den Druckertreiber übergeben werden. Es MUSS cjIn Bytes verfügbar sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

