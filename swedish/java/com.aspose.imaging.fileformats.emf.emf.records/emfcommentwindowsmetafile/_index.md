---
title: "EmfCommentWindowsMetaFile"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_COMMENT_WINDOWS_METAFILE-posten specificerar en bild i en inbäddad WMF-metafil."
type: docs
weight: 33
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype)
```
public final class EmfCommentWindowsMetaFile extends EmfCommentPublicRecordType
```

Den EMR\_COMMENT\_WINDOWS\_METAFILE-posten anger en bild i en inbäddad WMF-metafil.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfCommentWindowsMetaFile(EmfRecord source)](#EmfCommentWindowsMetaFile-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfCommentWindowsMetaFile`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getVersion()](#getVersion--) | Hämtar eller anger ett 16‑bitars osignerat heltal som specificerar WMF-metafilens version i termer av stöd för enhetsoberoende bitmaps (DIBs), från WMF MetafileVersion‑enumerationen ([MS-WMF] avsnitt 2.1.1.19). |
| [setVersion(short value)](#setVersion-short-) | Hämtar eller anger ett 16‑bitars osignerat heltal som specificerar WMF-metafilens version i termer av stöd för enhetsoberoende bitmaps (DIBs), från WMF MetafileVersion‑enumerationen ([MS-WMF] avsnitt 2.1.1.19). |
| [getChecksum()](#getChecksum--) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar kontrollsumman för denna post. |
| [setChecksum(int value)](#setChecksum-int-) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar kontrollsumman för denna post. |
| [getFlags()](#getFlags--) | Hämtar eller anger ett 32‑bitars värde som MÅSTE vara 0x00000000 och som MÅSTE ignoreras. |
| [setFlags(int value)](#setFlags-int-) | Hämtar eller anger ett 32‑bitars värde som MÅSTE vara 0x00000000 och som MÅSTE ignoreras. |
| [getWinMetafileSize()](#getWinMetafileSize--) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar storleken, i byte, på WMF-metafilen i WinMetafile‑fältet. |
| [setWinMetafileSize(int value)](#setWinMetafileSize-int-) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar storleken, i byte, på WMF-metafilen i WinMetafile‑fältet. |
| [getWinMetafile()](#getWinMetafile--) | Hämtar eller anger en buffert som innehåller WMF-metafilen. |
| [setWinMetafile(MetaImage value)](#setWinMetafile-com.aspose.imaging.fileformats.emf.MetaImage-) | Hämtar eller anger en buffert som innehåller WMF-metafilen. |
### EmfCommentWindowsMetaFile(EmfRecord source) {#EmfCommentWindowsMetaFile-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentWindowsMetaFile(EmfRecord source)
```


Initierar en ny instans av klassen `EmfCommentWindowsMetaFile`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### getVersion() {#getVersion--}
```
public short getVersion()
```


Hämtar eller anger ett 16‑bitars osignerat heltal som specificerar WMF-metafilens version i termer av stöd för enhetsoberoende bitmaps (DIBs), från WMF MetafileVersion‑enumerationen ([MS-WMF] avsnitt 2.1.1.19).

**Returns:**
short
### setVersion(short value) {#setVersion-short-}
```
public void setVersion(short value)
```


Hämtar eller anger ett 16‑bitars osignerat heltal som specificerar WMF-metafilens version i termer av stöd för enhetsoberoende bitmaps (DIBs), från WMF MetafileVersion‑enumerationen ([MS-WMF] avsnitt 2.1.1.19).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getChecksum() {#getChecksum--}
```
public int getChecksum()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar kontrollsumman för denna post.

**Returns:**
int
### setChecksum(int value) {#setChecksum-int-}
```
public void setChecksum(int value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar kontrollsumman för denna post.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getFlags() {#getFlags--}
```
public int getFlags()
```


Hämtar eller anger ett 32‑bitars värde som MÅSTE vara 0x00000000 och som MÅSTE ignoreras.

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Hämtar eller anger ett 32‑bitars värde som MÅSTE vara 0x00000000 och som MÅSTE ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getWinMetafileSize() {#getWinMetafileSize--}
```
public int getWinMetafileSize()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar storleken, i byte, på WMF-metafilen i WinMetafile‑fältet.

**Returns:**
int
### setWinMetafileSize(int value) {#setWinMetafileSize-int-}
```
public void setWinMetafileSize(int value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar storleken, i byte, på WMF-metafilen i WinMetafile‑fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getWinMetafile() {#getWinMetafile--}
```
public MetaImage getWinMetafile()
```


Hämtar eller anger en buffert som innehåller WMF-metafilen.

**Returns:**
[MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage)
### setWinMetafile(MetaImage value) {#setWinMetafile-com.aspose.imaging.fileformats.emf.MetaImage-}
```
public void setWinMetafile(MetaImage value)
```


Hämtar eller anger en buffert som innehåller WMF-metafilen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage) |  |

