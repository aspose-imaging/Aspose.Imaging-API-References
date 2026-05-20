---
title: "EmfGlsRecord"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_GLSRECORD-Datensatz gibt eine OpenGL-Funktion an."
type: docs
weight: 64
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfglsrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfOpenGlRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfopenglrecordtype)
```
public final class EmfGlsRecord extends EmfOpenGlRecordType
```

Der EMR\_GLSRECORD-Datensatz gibt eine OpenGL-Funktion an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfGlsRecord(EmfRecord source)](#EmfGlsRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der Klasse `EmfGlsRecord`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCbData()](#getCbData--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe des Datenfeldes in Bytes angibt. |
| [setCbData(int value)](#setCbData-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe des Datenfeldes in Bytes angibt. |
| [getData()](#getData--) | Liest oder setzt ein optionales Byte‑Array der Länge cbData, das Daten für die OpenGL‑Funktion angibt. |
| [setData(byte[] value)](#setData-byte---) | Liest oder setzt ein optionales Byte‑Array der Länge cbData, das Daten für die OpenGL‑Funktion angibt. |
### EmfGlsRecord(EmfRecord source) {#EmfGlsRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfGlsRecord(EmfRecord source)
```


Initialisiert eine neue Instanz der Klasse `EmfGlsRecord`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe des Datenfeldes in Bytes angibt. Wenn dieser Wert null ist, werden keine Daten an diesen Datensatz angehängt.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe des Datenfeldes in Bytes angibt. Wenn dieser Wert null ist, werden keine Daten an diesen Datensatz angehängt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Liest oder setzt ein optionales Byte‑Array der Länge cbData, das Daten für die OpenGL‑Funktion angibt.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Liest oder setzt ein optionales Byte‑Array der Länge cbData, das Daten für die OpenGL‑Funktion angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

