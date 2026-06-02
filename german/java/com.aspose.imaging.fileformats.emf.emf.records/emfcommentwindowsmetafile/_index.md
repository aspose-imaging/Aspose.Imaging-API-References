---
title: "EmfCommentWindowsMetaFile"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_COMMENT_WINDOWS_METAFILE-Datensatz gibt ein Bild in einer eingebetteten WMF-Metadatei an."
type: docs
weight: 33
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype)
```
public final class EmfCommentWindowsMetaFile extends EmfCommentPublicRecordType
```

Der EMR\_COMMENT\_WINDOWS\_METAFILE-Datensatz gibt ein Bild in einer eingebetteten WMF-Metadatei an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfCommentWindowsMetaFile(EmfRecord source)](#EmfCommentWindowsMetaFile-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfCommentWindowsMetaFile`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getVersion()](#getVersion--) | Liest oder setzt ein 16‑Bit vorzeichenloser Integer, der die WMF‑Metadatei‑Version in Bezug auf die Unterstützung von geräteunabhängigen Bitmaps (DIBs) aus der WMF‑MetafileVersion‑Aufzählung ([MS-WMF] Abschnitt 2.1.1.19) angibt. |
| [setVersion(short value)](#setVersion-short-) | Liest oder setzt ein 16‑Bit vorzeichenloser Integer, der die WMF‑Metadatei‑Version in Bezug auf die Unterstützung von geräteunabhängigen Bitmaps (DIBs) aus der WMF‑MetafileVersion‑Aufzählung ([MS-WMF] Abschnitt 2.1.1.19) angibt. |
| [getChecksum()](#getChecksum--) | Liest oder setzt ein 32‑Bit vorzeichenloser Integer, der die Prüfsumme für diesen Datensatz angibt. |
| [setChecksum(int value)](#setChecksum-int-) | Liest oder setzt ein 32‑Bit vorzeichenloser Integer, der die Prüfsumme für diesen Datensatz angibt. |
| [getFlags()](#getFlags--) | Liest oder setzt einen 32‑Bit‑Wert, der 0x00000000 sein MUSS und ignoriert werden MUSS. |
| [setFlags(int value)](#setFlags-int-) | Liest oder setzt einen 32‑Bit‑Wert, der 0x00000000 sein MUSS und ignoriert werden MUSS. |
| [getWinMetafileSize()](#getWinMetafileSize--) | Liest oder setzt ein 32‑Bit vorzeichenloser Integer, der die Größe (in Bytes) der WMF‑Metadatei im WinMetafile‑Feld angibt. |
| [setWinMetafileSize(int value)](#setWinMetafileSize-int-) | Liest oder setzt ein 32‑Bit vorzeichenloser Integer, der die Größe (in Bytes) der WMF‑Metadatei im WinMetafile‑Feld angibt. |
| [getWinMetafile()](#getWinMetafile--) | Liest oder setzt einen Puffer, der die WMF‑Metadatei enthält. |
| [setWinMetafile(MetaImage value)](#setWinMetafile-com.aspose.imaging.fileformats.emf.MetaImage-) | Liest oder setzt einen Puffer, der die WMF‑Metadatei enthält. |
### EmfCommentWindowsMetaFile(EmfRecord source) {#EmfCommentWindowsMetaFile-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentWindowsMetaFile(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfCommentWindowsMetaFile`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### getVersion() {#getVersion--}
```
public short getVersion()
```


Liest oder setzt ein 16‑Bit vorzeichenloser Integer, der die WMF‑Metadatei‑Version in Bezug auf die Unterstützung von geräteunabhängigen Bitmaps (DIBs) aus der WMF‑MetafileVersion‑Aufzählung ([MS-WMF] Abschnitt 2.1.1.19) angibt.

**Returns:**
short
### setVersion(short value) {#setVersion-short-}
```
public void setVersion(short value)
```


Liest oder setzt ein 16‑Bit vorzeichenloser Integer, der die WMF‑Metadatei‑Version in Bezug auf die Unterstützung von geräteunabhängigen Bitmaps (DIBs) aus der WMF‑MetafileVersion‑Aufzählung ([MS-WMF] Abschnitt 2.1.1.19) angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getChecksum() {#getChecksum--}
```
public int getChecksum()
```


Liest oder setzt ein 32‑Bit vorzeichenloser Integer, der die Prüfsumme für diesen Datensatz angibt.

**Returns:**
int
### setChecksum(int value) {#setChecksum-int-}
```
public void setChecksum(int value)
```


Liest oder setzt ein 32‑Bit vorzeichenloser Integer, der die Prüfsumme für diesen Datensatz angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getFlags() {#getFlags--}
```
public int getFlags()
```


Liest oder setzt einen 32‑Bit‑Wert, der 0x00000000 sein MUSS und ignoriert werden MUSS.

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Liest oder setzt einen 32‑Bit‑Wert, der 0x00000000 sein MUSS und ignoriert werden MUSS.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getWinMetafileSize() {#getWinMetafileSize--}
```
public int getWinMetafileSize()
```


Liest oder setzt ein 32‑Bit vorzeichenloser Integer, der die Größe (in Bytes) der WMF‑Metadatei im WinMetafile‑Feld angibt.

**Returns:**
int
### setWinMetafileSize(int value) {#setWinMetafileSize-int-}
```
public void setWinMetafileSize(int value)
```


Liest oder setzt ein 32‑Bit vorzeichenloser Integer, der die Größe (in Bytes) der WMF‑Metadatei im WinMetafile‑Feld angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getWinMetafile() {#getWinMetafile--}
```
public MetaImage getWinMetafile()
```


Liest oder setzt einen Puffer, der die WMF‑Metadatei enthält.

**Returns:**
[MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage)
### setWinMetafile(MetaImage value) {#setWinMetafile-com.aspose.imaging.fileformats.emf.MetaImage-}
```
public void setWinMetafile(MetaImage value)
```


Liest oder setzt einen Puffer, der die WMF‑Metadatei enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage) |  |

