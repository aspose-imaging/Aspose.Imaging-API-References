---
title: "EmfMetafileHeader"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die EMR_HEADER-Datensatztypen definieren die Ausgangspunkte von EMF‑Metadateien und geben Eigenschaften des Geräts an, auf dem das Bild in der Metadatei erstellt wurde."
type: docs
weight: 70
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public class EmfMetafileHeader extends EmfRecord
```

Die EMR\_HEADER-Datensatztypen definieren die Ausgangspunkte von EMF‑Metadateien und geben Eigenschaften des Geräts an, auf dem das Bild in der Metadatei erstellt wurde. Die Informationen im Header‑Datensatz ermöglichen es, dass EMF‑Metadateien unabhängig von einem bestimmten Ausgabegerät sind. Der Wert des Size‑Feldes kann verwendet werden, um zwischen den verschiedenen in diesem Abschnitt zuvor aufgeführten EMR\_HEADER-Datensatztypen zu unterscheiden. Es gibt drei mögliche Header: Der Basis‑Header, der der EmfMetafileHeader‑Datensatz ist. Der feste Teil dieses Headers ist 88 Byte groß und enthält ein Header‑Objekt. Der erste Erweiterungs‑Header, der der EmfMetafileHeaderExtension1‑Datensatz ist. Der feste Teil dieses Headers ist 100 Byte groß und enthält ein Header‑Objekt und ein HeaderExtension1‑Objekt (Abschnitt 2.2.10). Der zweite Erweiterungs‑Header, der der EmfMetafileHeaderExtension2‑Datensatz ist. Der feste Teil dieses Headers ist 108 Byte groß und enthält ein Header‑Objekt, ein HeaderExtension1‑Objekt und ein HeaderExtension2‑Objekt (Abschnitt 2.2.11).
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfMetafileHeader(EmfRecord record)](#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfMetafileHeader`‑Klasse. |
| [EmfMetafileHeader()](#EmfMetafileHeader--) | Initialisiert eine neue Instanz der `EmfMetafileHeader`‑Klasse. |
| [EmfMetafileHeader(EmfMetafileHeader header)](#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-) | Initialisiert eine neue Instanz der `EmfMetafileHeader`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEmfHeader()](#getEmfHeader--) | Ruft ein Header-Objekt (Abschnitt 2.2.9) ab, das Informationen über den Inhalt und die Struktur der Metadatei enthält. |
| [setEmfHeader(EmfHeaderObject value)](#setEmfHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject-) | Legt ein Header-Objekt (Abschnitt 2.2.9) fest, das Informationen über den Inhalt und die Struktur der Metadatei enthält. |
| [getEmfHeaderRecordBuffer()](#getEmfHeaderRecordBuffer--) | Ruft ein optionales Byte-Array ab, das den Rest des EMF-Header-Datensatzes enthält. |
| [setEmfHeaderRecordBuffer(byte[] value)](#setEmfHeaderRecordBuffer-byte---) | Legt ein optionales Byte-Array fest, das den Rest des EMF-Header-Datensatzes enthält. |
| [getEmfDescriptionBuffer()](#getEmfDescriptionBuffer--) | Ruft den EMF-Beschreibungs-Puffer ab. Ein optionales Byte-Array, das die EMF-Beschreibungszeichenkette enthält und nicht zwingend zusammenhängend mit dem festen Teil des EmfMetafileHeader-Datensatzes sein muss. |
| [setEmfDescriptionBuffer(byte[] value)](#setEmfDescriptionBuffer-byte---) | Legt den EMF-Beschreibungs-Puffer fest. Ein optionales Byte-Array, das die EMF-Beschreibungszeichenkette enthält und nicht zwingend zusammenhängend mit dem festen Teil des EmfMetafileHeader-Datensatzes sein muss. |
| [getEmfDescription()](#getEmfDescription--) | Ruft die EMF-Beschreibung ab. Eine optionale, nullterminierte Unicode UTF16-LE-Zeichenkette beliebiger Länge und Inhalte. |
| [setEmfDescription(String value)](#setEmfDescription-java.lang.String-) | Legt die EMF-Beschreibung fest. Eine optionale, nullterminierte Unicode UTF16-LE-Zeichenkette beliebiger Länge und Inhalte. |
### EmfMetafileHeader(EmfRecord record) {#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfMetafileHeader(EmfRecord record)
```


Initialisiert eine neue Instanz der `EmfMetafileHeader`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Der Datensatz. |

### EmfMetafileHeader() {#EmfMetafileHeader--}
```
public EmfMetafileHeader()
```


Initialisiert eine neue Instanz der `EmfMetafileHeader`‑Klasse.

### EmfMetafileHeader(EmfMetafileHeader header) {#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-}
```
public EmfMetafileHeader(EmfMetafileHeader header)
```


Initialisiert eine neue Instanz der `EmfMetafileHeader`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| header | [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) | Der Header. |

### getEmfHeader() {#getEmfHeader--}
```
public EmfHeaderObject getEmfHeader()
```


Ruft ein Header-Objekt (Abschnitt 2.2.9) ab, das Informationen über den Inhalt und die Struktur der Metadatei enthält.

**Returns:**
[EmfHeaderObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject)
### setEmfHeader(EmfHeaderObject value) {#setEmfHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject-}
```
public void setEmfHeader(EmfHeaderObject value)
```


Legt ein Header-Objekt (Abschnitt 2.2.9) fest, das Informationen über den Inhalt und die Struktur der Metadatei enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfHeaderObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject) |  |

### getEmfHeaderRecordBuffer() {#getEmfHeaderRecordBuffer--}
```
public byte[] getEmfHeaderRecordBuffer()
```


Ruft ein optionales Byte-Array ab, das den Rest des EMF-Header-Datensatzes enthält. Die Größe dieses Feldes MUSS ein Vielfaches von 4 Bytes sein.

**Returns:**
byte[]
### setEmfHeaderRecordBuffer(byte[] value) {#setEmfHeaderRecordBuffer-byte---}
```
public void setEmfHeaderRecordBuffer(byte[] value)
```


Legt ein optionales Byte-Array fest, das den Rest des EMF-Header-Datensatzes enthält. Die Größe dieses Feldes MUSS ein Vielfaches von 4 Bytes sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### getEmfDescriptionBuffer() {#getEmfDescriptionBuffer--}
```
public byte[] getEmfDescriptionBuffer()
```


Ruft den EMF-Beschreibungs-Puffer ab. Ein optionales Byte-Array, das die EMF-Beschreibungszeichenkette enthält und nicht zwingend zusammenhängend mit dem festen Teil des EmfMetafileHeader-Datensatzes sein muss. Dementsprechend ist das in diesem Puffer mit "UndefinedSpace" bezeichnete Feld optional und MUSS ignoriert werden.

**Returns:**
byte[]
### setEmfDescriptionBuffer(byte[] value) {#setEmfDescriptionBuffer-byte---}
```
public void setEmfDescriptionBuffer(byte[] value)
```


Legt den EMF-Beschreibungs-Puffer fest. Ein optionales Byte-Array, das die EMF-Beschreibungszeichenkette enthält und nicht zwingend zusammenhängend mit dem festen Teil des EmfMetafileHeader-Datensatzes sein muss. Dementsprechend ist das in diesem Puffer mit "UndefinedSpace" bezeichnete Feld optional und MUSS ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### getEmfDescription() {#getEmfDescription--}
```
public String getEmfDescription()
```


Ruft die EMF-Beschreibung ab. Eine optionale, nullterminierte Unicode UTF16-LE-Zeichenkette beliebiger Länge und Inhalte. Ihre Position im Datensatz und die Anzahl der Zeichen werden durch die Felder offDescription bzw. nDescription im EmfHeader angegeben. Ist der Wert eines dieser Felder Null, ist keine Beschreibungszeichenkette vorhanden.

**Returns:**
java.lang.String
### setEmfDescription(String value) {#setEmfDescription-java.lang.String-}
```
public void setEmfDescription(String value)
```


Legt die EMF-Beschreibung fest. Eine optionale, nullterminierte Unicode UTF16-LE-Zeichenkette beliebiger Länge und Inhalte. Ihre Position im Datensatz und die Anzahl der Zeichen werden durch die Felder offDescription bzw. nDescription im EmfHeader angegeben. Ist der Wert eines dieser Felder Null, ist keine Beschreibungszeichenkette vorhanden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

