---
title: "WmfEscapeEnhancedMetafile"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der Escape Enhanced Meta‑Datei‑Datensatz."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.fileformats.wmf.objects.escaperecords/wmfescapeenhancedmetafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.escaperecords.WmfEscapeRecordBase](../../com.aspose.imaging.fileformats.wmf.objects.escaperecords/wmfescaperecordbase)
```
public class WmfEscapeEnhancedMetafile extends WmfEscapeRecordBase
```

Der Escape Enhanced Meta‑Datei‑Datensatz.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WmfEscapeEnhancedMetafile()](#WmfEscapeEnhancedMetafile--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Liest oder setzt den Kommentar-Identifikator. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Liest oder setzt den Kommentar-Identifikator. |
| [getCommentType()](#getCommentType--) | Liest oder schreibt den Typ des Kommentars. |
| [setCommentType(int value)](#setCommentType-int-) | Liest oder schreibt den Typ des Kommentars. |
| [getVersion()](#getVersion--) | Liest oder setzt die Version. |
| [setVersion(int value)](#setVersion-int-) | Liest oder setzt die Version. |
| [getChecksum()](#getChecksum--) | Liest oder schreibt die Prüfsumme. |
| [setChecksum(int value)](#setChecksum-int-) | Liest oder schreibt die Prüfsumme. |
| [getFlags()](#getFlags--) | Liest oder setzt die Flags. |
| [setFlags(int value)](#setFlags-int-) | Liest oder setzt die Flags. |
| [getCommentRecordCount()](#getCommentRecordCount--) | Liest oder schreibt die Anzahl der Kommentar‑Datensätze. |
| [setCommentRecordCount(int value)](#setCommentRecordCount-int-) | Liest oder schreibt die Anzahl der Kommentar‑Datensätze. |
| [getCurrentRecordSize()](#getCurrentRecordSize--) | Liest oder schreibt die Größe des aktuellen Datensatzes. |
| [setCurrentRecordSize(int value)](#setCurrentRecordSize-int-) | Liest oder schreibt die Größe des aktuellen Datensatzes. |
| [getRemainingBytes()](#getRemainingBytes--) | Liest oder schreibt die verbleibenden Bytes. |
| [setRemainingBytes(int value)](#setRemainingBytes-int-) | Liest oder schreibt die verbleibenden Bytes. |
| [getEnhancedMetafileDataSize()](#getEnhancedMetafileDataSize--) | Liest oder schreibt die Größe der Enhanced‑Metafile‑Daten. |
| [setEnhancedMetafileDataSize(int value)](#setEnhancedMetafileDataSize-int-) | Liest oder schreibt die Größe der Enhanced‑Metafile‑Daten. |
| [getEnhancedMetafileData()](#getEnhancedMetafileData--) | Liest oder schreibt die Enhanced‑Metafile‑Daten. |
| [setEnhancedMetafileData(byte[] value)](#setEnhancedMetafileData-byte---) | Liest oder schreibt die Enhanced‑Metafile‑Daten. |
### WmfEscapeEnhancedMetafile() {#WmfEscapeEnhancedMetafile--}
```
public WmfEscapeEnhancedMetafile()
```


### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Liest oder setzt den Kommentar-Identifikator.

Wert: Ein 32‑Bit vorzeichenloser Integer, der diesen Datensatz als WMF‑Kommentar‑Datensatz definiert. Dieser Wert MUSS 0x43464D57 sein.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Liest oder setzt den Kommentar-Identifikator.

Wert: Ein 32‑Bit vorzeichenloser Integer, der diesen Datensatz als WMF‑Kommentar‑Datensatz definiert. Dieser Wert MUSS 0x43464D57 sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getCommentType() {#getCommentType--}
```
public int getCommentType()
```


Liest oder schreibt den Typ des Kommentars.

Wert: Ein 32‑Bit vorzeichenloser Integer, der den Typ des Kommentars in diesem Datensatz identifiziert. Dieser Wert MUSS 0x00000001 sein.

**Returns:**
int
### setCommentType(int value) {#setCommentType-int-}
```
public void setCommentType(int value)
```


Liest oder schreibt den Typ des Kommentars.

Wert: Ein 32‑Bit vorzeichenloser Integer, der den Typ des Kommentars in diesem Datensatz identifiziert. Dieser Wert MUSS 0x00000001 sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Liest oder setzt die Version.

Wert: Ein 32‑Bit vorzeichenloser Integer, der die Interoperabilität der EMF‑Metadatei angibt. Dieser SOLLTE 0x00010000 sein.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Liest oder setzt die Version.

Wert: Ein 32‑Bit vorzeichenloser Integer, der die Interoperabilität der EMF‑Metadatei angibt. Dieser SOLLTE 0x00010000 sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getChecksum() {#getChecksum--}
```
public int getChecksum()
```


Liest oder schreibt die Prüfsumme.

Wert: Ein 16‑Bit vorzeichenloser Integer, der verwendet wird, um die Korrektheit des eingebetteten EMF‑Streams zu validieren. Dieser Wert MUSS das Einerkomplement des Ergebnisses einer XOR‑Operation auf alle WORDs im EMF‑Stream sein.

**Returns:**
int
### setChecksum(int value) {#setChecksum-int-}
```
public void setChecksum(int value)
```


Liest oder schreibt die Prüfsumme.

Wert: Ein 16‑Bit vorzeichenloser Integer, der verwendet wird, um die Korrektheit des eingebetteten EMF‑Streams zu validieren. Dieser Wert MUSS das Einerkomplement des Ergebnisses einer XOR‑Operation auf alle WORDs im EMF‑Stream sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getFlags() {#getFlags--}
```
public int getFlags()
```


Liest oder setzt die Flags.

Wert: Dieser 32‑Bit vorzeichenlose Integer wird nicht verwendet und MUSS auf Null gesetzt werden.

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Liest oder setzt die Flags.

Wert: Dieser 32‑Bit vorzeichenlose Integer wird nicht verwendet und MUSS auf Null gesetzt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getCommentRecordCount() {#getCommentRecordCount--}
```
public int getCommentRecordCount()
```


Liest oder schreibt die Anzahl der Kommentar‑Datensätze.

Wert: Ein 32‑Bit vorzeichenloser Integer, der die Gesamtzahl aufeinanderfolgender META\_ESCAPE\_ENHANCED\_METAFILE‑Datensätze angibt, die die eingebettete EMF‑Metadatei enthalten.

**Returns:**
int
### setCommentRecordCount(int value) {#setCommentRecordCount-int-}
```
public void setCommentRecordCount(int value)
```


Liest oder schreibt die Anzahl der Kommentar‑Datensätze.

Wert: Ein 32‑Bit vorzeichenloser Integer, der die Gesamtzahl aufeinanderfolgender META\_ESCAPE\_ENHANCED\_METAFILE‑Datensätze angibt, die die eingebettete EMF‑Metadatei enthalten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getCurrentRecordSize() {#getCurrentRecordSize--}
```
public int getCurrentRecordSize()
```


Liest oder schreibt die Größe des aktuellen Datensatzes.

Wert: Ein 32‑Bit vorzeichenloser Integer, der die Größe des Feldes EnhancedMetafileData in Bytes angibt. Dieser Wert MUSS kleiner oder gleich 8,192 sein.

**Returns:**
int
### setCurrentRecordSize(int value) {#setCurrentRecordSize-int-}
```
public void setCurrentRecordSize(int value)
```


Liest oder schreibt die Größe des aktuellen Datensatzes.

Wert: Ein 32‑Bit vorzeichenloser Integer, der die Größe des Feldes EnhancedMetafileData in Bytes angibt. Dieser Wert MUSS kleiner oder gleich 8,192 sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getRemainingBytes() {#getRemainingBytes--}
```
public int getRemainingBytes()
```


Liest oder schreibt die verbleibenden Bytes.

Wert: Ein 32‑Bit vorzeichenloser Integer, der die Anzahl der Bytes im EMF‑Stream angibt, die nach diesem Datensatz noch verarbeitet werden müssen. Diese zusätzlichen EMF‑Bytes MUSS in den EnhancedMetafileData‑Feldern nachfolgender META\_ESCAPE\_ENHANDED\_METAFILE‑Escape‑Datensätze folgen.

**Returns:**
int
### setRemainingBytes(int value) {#setRemainingBytes-int-}
```
public void setRemainingBytes(int value)
```


Liest oder schreibt die verbleibenden Bytes.

Wert: Ein 32‑Bit vorzeichenloser Integer, der die Anzahl der Bytes im EMF‑Stream angibt, die nach diesem Datensatz noch verarbeitet werden müssen. Diese zusätzlichen EMF‑Bytes MUSS in den EnhancedMetafileData‑Feldern nachfolgender META\_ESCAPE\_ENHANDED\_METAFILE‑Escape‑Datensätze folgen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getEnhancedMetafileDataSize() {#getEnhancedMetafileDataSize--}
```
public int getEnhancedMetafileDataSize()
```


Liest oder schreibt die Größe der Enhanced‑Metafile‑Daten.

Wert: Ein 32‑Bit vorzeichenloser Integer, der die Gesamgröße des in dieser Sequenz von META\_ESCAPE\_ENHANCED\_METAFILE‑Datensätzen eingebetteten EMF‑Streams angibt.

**Returns:**
int
### setEnhancedMetafileDataSize(int value) {#setEnhancedMetafileDataSize-int-}
```
public void setEnhancedMetafileDataSize(int value)
```


Liest oder schreibt die Größe der Enhanced‑Metafile‑Daten.

Wert: Ein 32‑Bit vorzeichenloser Integer, der die Gesamgröße des in dieser Sequenz von META\_ESCAPE\_ENHANCED\_METAFILE‑Datensätzen eingebetteten EMF‑Streams angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getEnhancedMetafileData() {#getEnhancedMetafileData--}
```
public byte[] getEnhancedMetafileData()
```


Liest oder schreibt die Enhanced‑Metafile‑Daten.

Wert: Ein Segment einer EMF‑Datei. Die Bytes in aufeinanderfolgenden META\_ESCAPE\_ENHANCED\_METAFILE‑Datensätzen MUSS zu einer einzigen Datei zusammengefügt werden, um die gesamte eingebettete EMF‑Datei darzustellen.

**Returns:**
byte[]
### setEnhancedMetafileData(byte[] value) {#setEnhancedMetafileData-byte---}
```
public void setEnhancedMetafileData(byte[] value)
```


Liest oder schreibt die Enhanced‑Metafile‑Daten.

Wert: Ein Segment einer EMF‑Datei. Die Bytes in aufeinanderfolgenden META\_ESCAPE\_ENHANCED\_METAFILE‑Datensätzen MUSS zu einer einzigen Datei zusammengefügt werden, um die gesamte eingebettete EMF‑Datei darzustellen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

