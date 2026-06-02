---
title: "EmfEof"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_EOF-Datensatz kennzeichnet das Ende der Metadatei und gibt eine Palette an."
type: docs
weight: 48
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfeof/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfControlRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcontrolrecordtype)
```
public final class EmfEof extends EmfControlRecordType
```

Der EMR\_EOF-Datensatz zeigt das Ende der Metadatei an und gibt eine Palette an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfEof(EmfRecord record)](#EmfEof-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der Klasse `EmfEof`. |
| [EmfEof()](#EmfEof--) | Initialisiert eine neue Instanz der Klasse `EmfEof`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPaletteArgb32Entries()](#getPaletteArgb32Entries--) | Liest einen optionalen Puffer, der Palettendaten enthält und nicht zwingend zusammenhängend mit dem festen Teil des EMR\_EOF-Datensatzes sein muss. |
| [setPaletteArgb32Entries(int[] value)](#setPaletteArgb32Entries-int---) | Setzt einen optionalen Puffer, der Palettendaten enthält und nicht zwingend zusammenhängend mit dem festen Teil des EMR\_EOF-Datensatzes sein muss. |
| [getSizeLast()](#getSizeLast--) | Liest einen 32‑Bit‑vorzeichenlosen Integer, der GLEICH wie Size sein MUSS und das letzte Feld des Datensatzes und damit der Metadatei sein MUSS. |
| [setSizeLast(int value)](#setSizeLast-int-) | Setzt einen 32‑Bit‑vorzeichenlosen Integer, der GLEICH wie Size sein MUSS und das letzte Feld des Datensatzes und damit der Metadatei sein MUSS. |
### EmfEof(EmfRecord record) {#EmfEof-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfEof(EmfRecord record)
```


Initialisiert eine neue Instanz der Klasse `EmfEof`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Der Datensatz. |

### EmfEof() {#EmfEof--}
```
public EmfEof()
```


Initialisiert eine neue Instanz der Klasse `EmfEof`.

### getPaletteArgb32Entries() {#getPaletteArgb32Entries--}
```
public int[] getPaletteArgb32Entries()
```


Liest einen optionalen Puffer, der Palettendaten enthält und nicht zwingend zusammenhängend mit dem festen Teil des EMR\_EOF-Datensatzes sein muss. Entsprechend sind Felder in diesem Puffer, die mit \"UndefinedSpace\" gekennzeichnet sind, optional und MÜSSEN ignoriert werden. Die Größe dieses Feldes MUSS ein Vielfaches von 4 Bytes sein.

**Returns:**
int[]
### setPaletteArgb32Entries(int[] value) {#setPaletteArgb32Entries-int---}
```
public void setPaletteArgb32Entries(int[] value)
```


Setzt einen optionalen Puffer, der Palettendaten enthält und nicht zwingend zusammenhängend mit dem festen Teil des EMR\_EOF-Datensatzes sein muss. Entsprechend sind Felder in diesem Puffer, die mit \"UndefinedSpace\" gekennzeichnet sind, optional und MÜSSEN ignoriert werden. Die Größe dieses Feldes MUSS ein Vielfaches von 4 Bytes sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] |  |

### getSizeLast() {#getSizeLast--}
```
public int getSizeLast()
```


Liest einen 32‑Bit‑vorzeichenlosen Integer, der GLEICH wie Size sein MUSS und das letzte Feld des Datensatzes und damit der Metadatei sein MUSS. LogPaletteEntry‑Objekte, falls vorhanden, MÜSSEN diesem Feld vorausgehen.

**Returns:**
int
### setSizeLast(int value) {#setSizeLast-int-}
```
public void setSizeLast(int value)
```


Setzt einen 32‑Bit‑vorzeichenlosen Integer, der GLEICH wie Size sein MUSS und das letzte Feld des Datensatzes und damit der Metadatei sein MUSS. LogPaletteEntry‑Objekte, falls vorhanden, MÜSSEN diesem Feld vorausgehen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

