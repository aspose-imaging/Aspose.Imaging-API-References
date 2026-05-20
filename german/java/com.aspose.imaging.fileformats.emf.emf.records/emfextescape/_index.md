---
title: "EmfExtEscape"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_EXTESCAPE-Datensatz übergibt beliebige Informationen an einen Druckertreiber."
type: docs
weight: 53
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfextescape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfEscapeRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype)
```
public final class EmfExtEscape extends EmfEscapeRecordType
```

Der EMR\_EXTESCAPE-Datensatz übergibt beliebige Informationen an einen Druckertreiber. Die Absicht ist, dass diese Informationen nicht zu einer Zeichnung führen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfExtEscape(EmfRecord source)](#EmfExtEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfExtEscape`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCjIn()](#getCjIn--) | Ruft ab oder legt eine 32‑Bit‑vorzeichenlose Ganzzahl fest, die die Anzahl der an den Druckertreiber zu übergebenden Bytes angibt. |
| [setCjIn(int value)](#setCjIn-int-) | Ruft ab oder legt eine 32‑Bit‑vorzeichenlose Ganzzahl fest, die die Anzahl der an den Druckertreiber zu übergebenden Bytes angibt. |
| [getData()](#getData--) | Ruft ab oder legt die Daten fest, die an den Druckertreiber übergeben werden. |
| [setData(byte[] value)](#setData-byte---) | Ruft ab oder legt die Daten fest, die an den Druckertreiber übergeben werden. |
### EmfExtEscape(EmfRecord source) {#EmfExtEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtEscape(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfExtEscape`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### getCjIn() {#getCjIn--}
```
public int getCjIn()
```


Ruft ab oder legt eine 32‑Bit‑vorzeichenlose Ganzzahl fest, die die Anzahl der an den Druckertreiber zu übergebenden Bytes angibt.

**Returns:**
int
### setCjIn(int value) {#setCjIn-int-}
```
public void setCjIn(int value)
```


Ruft ab oder legt eine 32‑Bit‑vorzeichenlose Ganzzahl fest, die die Anzahl der an den Druckertreiber zu übergebenden Bytes angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Ruft ab oder legt die Daten fest, die an den Druckertreiber übergeben werden. Es MUSS cjIn Bytes verfügbar sein.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Ruft ab oder legt die Daten fest, die an den Druckertreiber übergeben werden. Es MUSS cjIn Bytes verfügbar sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

