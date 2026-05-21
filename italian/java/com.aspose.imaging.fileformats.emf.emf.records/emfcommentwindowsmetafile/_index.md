---
title: "EmfCommentWindowsMetaFile"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_COMMENT_WINDOWS_METAFILE specifica un'immagine in un metafile WMF incorporato."
type: docs
weight: 33
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype)
```
public final class EmfCommentWindowsMetaFile extends EmfCommentPublicRecordType
```

Il record EMR\_COMMENT\_WINDOWS\_METAFILE specifica un'immagine in un metafile WMF incorporato.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfCommentWindowsMetaFile(EmfRecord source)](#EmfCommentWindowsMetaFile-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfCommentWindowsMetaFile`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getVersion()](#getVersion--) | Ottiene o imposta un intero senza segno a 16 bit che specifica la versione del metafile WMF in termini di supporto per bitmap indipendenti dal dispositivo (DIB), dall'enumerazione WMF MetafileVersion ([MS-WMF] sezione 2.1.1.19). |
| [setVersion(short value)](#setVersion-short-) | Ottiene o imposta un intero senza segno a 16 bit che specifica la versione del metafile WMF in termini di supporto per bitmap indipendenti dal dispositivo (DIB), dall'enumerazione WMF MetafileVersion ([MS-WMF] sezione 2.1.1.19). |
| [getChecksum()](#getChecksum--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il checksum per questo record. |
| [setChecksum(int value)](#setChecksum-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il checksum per questo record. |
| [getFlags()](#getFlags--) | Ottiene o imposta un valore a 32 bit che DEVE essere 0x00000000 e DEVE essere ignorato. |
| [setFlags(int value)](#setFlags-int-) | Ottiene o imposta un valore a 32 bit che DEVE essere 0x00000000 e DEVE essere ignorato. |
| [getWinMetafileSize()](#getWinMetafileSize--) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione, in byte, del metafile WMF nel campo WinMetafile. |
| [setWinMetafileSize(int value)](#setWinMetafileSize-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione, in byte, del metafile WMF nel campo WinMetafile. |
| [getWinMetafile()](#getWinMetafile--) | Ottiene o imposta un buffer che contiene il metafile WMF. |
| [setWinMetafile(MetaImage value)](#setWinMetafile-com.aspose.imaging.fileformats.emf.MetaImage-) | Ottiene o imposta un buffer che contiene il metafile WMF. |
### EmfCommentWindowsMetaFile(EmfRecord source) {#EmfCommentWindowsMetaFile-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentWindowsMetaFile(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfCommentWindowsMetaFile`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### getVersion() {#getVersion--}
```
public short getVersion()
```


Ottiene o imposta un intero senza segno a 16 bit che specifica la versione del metafile WMF in termini di supporto per bitmap indipendenti dal dispositivo (DIB), dall'enumerazione WMF MetafileVersion ([MS-WMF] sezione 2.1.1.19).

**Returns:**
short
### setVersion(short value) {#setVersion-short-}
```
public void setVersion(short value)
```


Ottiene o imposta un intero senza segno a 16 bit che specifica la versione del metafile WMF in termini di supporto per bitmap indipendenti dal dispositivo (DIB), dall'enumerazione WMF MetafileVersion ([MS-WMF] sezione 2.1.1.19).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getChecksum() {#getChecksum--}
```
public int getChecksum()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il checksum per questo record.

**Returns:**
int
### setChecksum(int value) {#setChecksum-int-}
```
public void setChecksum(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il checksum per questo record.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getFlags() {#getFlags--}
```
public int getFlags()
```


Ottiene o imposta un valore a 32 bit che DEVE essere 0x00000000 e DEVE essere ignorato.

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Ottiene o imposta un valore a 32 bit che DEVE essere 0x00000000 e DEVE essere ignorato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getWinMetafileSize() {#getWinMetafileSize--}
```
public int getWinMetafileSize()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione, in byte, del metafile WMF nel campo WinMetafile.

**Returns:**
int
### setWinMetafileSize(int value) {#setWinMetafileSize-int-}
```
public void setWinMetafileSize(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione, in byte, del metafile WMF nel campo WinMetafile.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getWinMetafile() {#getWinMetafile--}
```
public MetaImage getWinMetafile()
```


Ottiene o imposta un buffer che contiene il metafile WMF.

**Returns:**
[MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage)
### setWinMetafile(MetaImage value) {#setWinMetafile-com.aspose.imaging.fileformats.emf.MetaImage-}
```
public void setWinMetafile(MetaImage value)
```


Ottiene o imposta un buffer che contiene il metafile WMF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage) |  |

