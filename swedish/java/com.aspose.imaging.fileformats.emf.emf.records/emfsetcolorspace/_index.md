---
title: "EmfSetColorSpace"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_SETCOLORSPACE‑posten definierar det aktuella logiska färgrymdsobjektet för grafikoperationer."
type: docs
weight: 123
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetcolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfSetColorSpace extends EmfObjectManipulationRecordType
```

EMR\_SETCOLORSPACE-posten definierar det aktuella logiska färgrymdsobjektet för grafikoperationer.

Det logiska färgrymdsobjektet som definieras av den här posten MÅSTE användas i ritoperationer som specificeras av efterföljande EMF-poster, tills antingen ett annat logiskt färgrymdsobjekt specificeras av en annan EMR\_SETCOLORSPACE-post, eller objektet tas bort av en EMR\_DELETECOLORSPACE-post.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfSetColorSpace(EmfRecord source)](#EmfSetColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfSetColorSpace`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getIhCS()](#getIhCS--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för ett logiskt färgrymdsobjekt i EMF‑objektabellen (avsnitt 3.1.1.1). |
| [setIhCS(int value)](#setIhCS-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för ett logiskt färgrymdsobjekt i EMF‑objektabellen (avsnitt 3.1.1.1). |
### EmfSetColorSpace(EmfRecord source) {#EmfSetColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetColorSpace(EmfRecord source)
```


Initierar en ny instans av klassen `EmfSetColorSpace`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### getIhCS() {#getIhCS--}
```
public int getIhCS()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för ett logiskt färgrymdsobjekt i EMF‑objektabellen (avsnitt 3.1.1.1).

Detta objekt är antingen ett WMF LogColorSpace‑ eller LogColorSpaceW‑objekt ([MS-WMF] avsnitt 2.2.2.11 respektive 2.2.2.12).

**Returns:**
int
### setIhCS(int value) {#setIhCS-int-}
```
public void setIhCS(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för ett logiskt färgrymdsobjekt i EMF‑objektabellen (avsnitt 3.1.1.1).

Detta objekt är antingen ett WMF LogColorSpace‑ eller LogColorSpaceW‑objekt ([MS-WMF] avsnitt 2.2.2.11 respektive 2.2.2.12).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

