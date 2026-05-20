---
title: "EmfSetIcmProfileW"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_SETICMPROFILEW-Datensatz spezifiziert ein Farbprofil in einer Datei, deren Name aus Unicode‑Zeichen für die Grafikausgabe besteht."
type: docs
weight: 127
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetIcmProfileW extends EmfStateRecordType
```

Der EMR\_SETICMPROFILEW-Datensatz gibt ein Farbprofil in einer Datei an, deren Name aus Unicode‑Zeichen besteht, für die Grafikausgabe.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfSetIcmProfileW(EmfRecord source)](#EmfSetIcmProfileW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfSetIcmProfileW`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDwFlags()](#getDwFlags--) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der Farbprofil‑Flags enthält. |
| [setDwFlags(int value)](#setDwFlags-int-) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der Farbprofil‑Flags enthält. |
| [getCbName()](#getCbName--) | Liest oder setzt eine 32‑Bit‑unsigned‑Integer, der die Anzahl der Bytes im Unicode‑UTF16‑LE‑Namen des gewünschten Farbprofils angibt. |
| [setCbName(int value)](#setCbName-int-) | Liest oder setzt eine 32‑Bit‑unsigned‑Integer, der die Anzahl der Bytes im Unicode‑UTF16‑LE‑Namen des gewünschten Farbprofils angibt. |
| [getCbData()](#getCbData--) | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die die Größe der Farprofil‑Daten angibt, falls angehängt. |
| [setCbData(int value)](#setCbData-int-) | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die die Größe der Farprofil‑Daten angibt, falls angehängt. |
| [getData()](#getData--) | Liest oder setzt ein Array der Größe (cbName + cbData) in Bytes, das den UTF16-LE-Namen und die Rohdaten des gewünschten Farbprofils angibt. |
| [setData(byte[] value)](#setData-byte---) | Liest oder setzt ein Array der Größe (cbName + cbData) in Bytes, das den UTF16-LE-Namen und die Rohdaten des gewünschten Farbprofils angibt. |
| [getName()](#getName--) | Ruft den Namen ab. |
| [getRawData()](#getRawData--) | Ruft die Rohdaten ab. |
### EmfSetIcmProfileW(EmfRecord source) {#EmfSetIcmProfileW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetIcmProfileW(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfSetIcmProfileW`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der Farbprofil‑Flags enthält.

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der Farbprofil‑Flags enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getCbName() {#getCbName--}
```
public int getCbName()
```


Liest oder setzt eine 32‑Bit‑unsigned‑Integer, der die Anzahl der Bytes im Unicode‑UTF16‑LE‑Namen des gewünschten Farbprofils angibt.

**Returns:**
int
### setCbName(int value) {#setCbName-int-}
```
public void setCbName(int value)
```


Liest oder setzt eine 32‑Bit‑unsigned‑Integer, der die Anzahl der Bytes im Unicode‑UTF16‑LE‑Namen des gewünschten Farbprofils angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die die Größe der Farprofil‑Daten angibt, falls angehängt.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die die Größe der Farprofil‑Daten angibt, falls angehängt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Liest oder setzt ein Array der Größe (cbName + cbData) in Bytes, das den UTF16-LE-Namen und die Rohdaten des gewünschten Farbprofils angibt.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Liest oder setzt ein Array der Größe (cbName + cbData) in Bytes, das den UTF16-LE-Namen und die Rohdaten des gewünschten Farbprofils angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### getName() {#getName--}
```
public String getName()
```


Ruft den Namen ab.

**Returns:**
java.lang.String
### getRawData() {#getRawData--}
```
public byte[] getRawData()
```


Ruft die Rohdaten ab.

**Returns:**
byte[]
