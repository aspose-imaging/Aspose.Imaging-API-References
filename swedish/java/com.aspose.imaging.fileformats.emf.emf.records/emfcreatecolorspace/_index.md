---
title: "EmfCreateColorSpace"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_CREATECOLORSPACE-posten skapar ett logiskt färgrymdsobjekt från en färgprofil med ett namn bestående av ASCII-tecken."
type: docs
weight: 36
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateColorSpace extends EmfObjectCreationRecordType
```

Den EMR\_CREATECOLORSPACE-posten skapar ett logiskt färgrymdsobjekt från en färgprofil med ett namn bestående av ASCII-tecken.

Det logiska färgrymdsobjektet som definieras av denna post kan väljas in i uppspelningsenhetens kontext av en EMR\_SETCOLORSPACE-post (avsnitt 2.3.8.7), som definierar den logiska färgrymden som ska användas i efterföljande grafikoperationer.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfCreateColorSpace(EmfRecord source)](#EmfCreateColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfCreateColorSpace`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getIhCS()](#getIhCS--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för det logiska färgrymdsobjektet i EMF-objektstabellen (avsnitt 3.1.1.1). |
| [setIhCS(int value)](#setIhCS-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för det logiska färgrymdsobjektet i EMF-objektstabellen (avsnitt 3.1.1.1). |
| [getLcs()](#getLcs--) | Hämtar eller anger ett WMF LogColorSpace-objekt ([MS-WMF] avsnitt 2.2.2.11), som kan specificera namnet på en färgprofil i ASCII-tecken. |
| [setLcs(WmfLogColorSpace value)](#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpace-) | Hämtar eller anger ett WMF LogColorSpace-objekt ([MS-WMF] avsnitt 2.2.2.11), som kan specificera namnet på en färgprofil i ASCII-tecken. |
### EmfCreateColorSpace(EmfRecord source) {#EmfCreateColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateColorSpace(EmfRecord source)
```


Initierar en ny instans av klassen `EmfCreateColorSpace`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### getIhCS() {#getIhCS--}
```
public int getIhCS()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för det logiska färgrymdsobjektet i EMF-objektstabellen (avsnitt 3.1.1.1). Detta index MÅSTE sparas så att detta objekt kan återanvändas eller modifieras.

**Returns:**
int
### setIhCS(int value) {#setIhCS-int-}
```
public void setIhCS(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för det logiska färgrymdsobjektet i EMF-objektstabellen (avsnitt 3.1.1.1). Detta index MÅSTE sparas så att detta objekt kan återanvändas eller modifieras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getLcs() {#getLcs--}
```
public WmfLogColorSpace getLcs()
```


Hämtar eller anger ett WMF LogColorSpace-objekt ([MS-WMF] avsnitt 2.2.2.11), som kan specificera namnet på en färgprofil i ASCII-tecken.

**Returns:**
[WmfLogColorSpace](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspace)
### setLcs(WmfLogColorSpace value) {#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpace-}
```
public void setLcs(WmfLogColorSpace value)
```


Hämtar eller anger ett WMF LogColorSpace-objekt ([MS-WMF] avsnitt 2.2.2.11), som kan specificera namnet på en färgprofil i ASCII-tecken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WmfLogColorSpace](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspace) |  |

