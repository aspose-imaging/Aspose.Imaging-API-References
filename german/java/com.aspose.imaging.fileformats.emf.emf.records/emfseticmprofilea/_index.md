---
title: "EmfSetIcmProfileA"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_SETICMPROFILEA-Datensatz gibt ein Farbprofil in einer Datei an, dessen Name aus ASCII‑Zeichen für die Grafikausgabe besteht."
type: docs
weight: 126
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetIcmProfileA extends EmfStateRecordType
```

Der EMR\_SETICMPROFILEA-Datensatz gibt ein Farbprofil in einer Datei an, deren Name aus ASCII‑Zeichen besteht, für die Grafikausgabe.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfSetIcmProfileA(EmfRecord source)](#EmfSetIcmProfileA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfSetIcmProfileA`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDwFlags()](#getDwFlags--) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der Farbprofil‑Flags enthält. |
| [setDwFlags(int value)](#setDwFlags-int-) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der Farbprofil‑Flags enthält. |
| [getCbName()](#getCbName--) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die Anzahl der Bytes im ASCII‑Namen des gewünschten Farbprofils angibt. |
| [setCbName(int value)](#setCbName-int-) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die Anzahl der Bytes im ASCII‑Namen des gewünschten Farbprofils angibt. |
| [getCbData()](#getCbData--) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die Größe der Farbprofildaten angibt, falls sie im Datenfeld enthalten sind. |
| [setCbData(int value)](#setCbData-int-) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die Größe der Farbprofildaten angibt, falls sie im Datenfeld enthalten sind. |
| [getData()](#getData--) | Ruft ein Array der Größe (cbName + cbData) in Bytes ab oder legt es fest, das den ASCII‑Namen und die Rohdaten des gewünschten Farbprofils enthält. |
| [setData(byte[] value)](#setData-byte---) | Ruft ein Array der Größe (cbName + cbData) in Bytes ab oder legt es fest, das den ASCII‑Namen und die Rohdaten des gewünschten Farbprofils enthält. |
| [getName()](#getName--) | Ruft den Namen ab. |
| [getRawData()](#getRawData--) | Ruft die Rohdaten ab. |
### EmfSetIcmProfileA(EmfRecord source) {#EmfSetIcmProfileA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetIcmProfileA(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfSetIcmProfileA`-Klasse.

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


Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die Anzahl der Bytes im ASCII‑Namen des gewünschten Farbprofils angibt.

**Returns:**
int
### setCbName(int value) {#setCbName-int-}
```
public void setCbName(int value)
```


Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die Anzahl der Bytes im ASCII‑Namen des gewünschten Farbprofils angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die Größe der Farbprofildaten angibt, falls sie im Datenfeld enthalten sind.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die Größe der Farbprofildaten angibt, falls sie im Datenfeld enthalten sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Ruft ein Array der Größe (cbName + cbData) in Bytes ab oder legt es fest, das den ASCII‑Namen und die Rohdaten des gewünschten Farbprofils enthält.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Ruft ein Array der Größe (cbName + cbData) in Bytes ab oder legt es fest, das den ASCII‑Namen und die Rohdaten des gewünschten Farbprofils enthält.

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
