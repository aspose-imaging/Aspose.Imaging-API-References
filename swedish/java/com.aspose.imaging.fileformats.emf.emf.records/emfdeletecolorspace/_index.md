---
title: "EmfDeleteColorSpace"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_DELETECOLORSPACE‑posten raderar ett logiskt färgrymdsobjekt."
type: docs
weight: 42
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfdeletecolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfDeleteColorSpace extends EmfObjectManipulationRecordType
```

Den EMR\_DELETECOLORSPACE-posten tar bort ett logiskt färgrymdsobjekt.

En EMR\_DELETEOBJECT‑post SKA användas i stället för EMR\_DELETECOLORSPACE för att radera ett logiskt färgrymdsobjekt.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfDeleteColorSpace(EmfRecord source)](#EmfDeleteColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfDeleteColorSpace`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getIhCS()](#getIhCS--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för ett logiskt färgrymdsobjekt i EMF‑objektabellen (avsnitt 3.1.1.1). |
| [setIhCS(int value)](#setIhCS-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för ett logiskt färgrymdsobjekt i EMF‑objektabellen (avsnitt 3.1.1.1). |
### EmfDeleteColorSpace(EmfRecord source) {#EmfDeleteColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfDeleteColorSpace(EmfRecord source)
```


Initierar en ny instans av klassen `EmfDeleteColorSpace`.

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

