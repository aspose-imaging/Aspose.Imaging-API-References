---
title: "EmfCreateColorSpaceW"
second_title: "Aspose.Imaging för Java API-referens"
description: "Posten EMR_CREATECOLORSPACEW skapar ett logiskt färgrymdsobjekt från en färgprofil med ett namn bestående av Unicode‑tecken."
type: docs
weight: 37
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateColorSpaceW extends EmfObjectCreationRecordType
```

Den EMR\_CREATECOLORSPACEW-posten skapar ett logiskt färgrymdsobjekt från en färgprofil med ett namn bestående av Unicode-tecken.

Det logiska färgrymdsobjektet som definieras av denna post kan väljas in i uppspelningsenhetens kontext av en EMR\_SETCOLORSPACE-post (avsnitt 2.3.8.7), som definierar den logiska färgrymden som ska användas i efterföljande grafikoperationer.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfCreateColorSpaceW(EmfRecord source)](#EmfCreateColorSpaceW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfCreateColorSpaceW`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getIhCS()](#getIhCS--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för det logiska färgrymdsobjektet i EMF-objektstabellen (avsnitt 3.1.1.1). |
| [setIhCS(int value)](#setIhCS-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för det logiska färgrymdsobjektet i EMF-objektstabellen (avsnitt 3.1.1.1). |
| [getLcs()](#getLcs--) | Hämtar eller anger ett WMF LogColorSpaceW-objekt ([MS-WMF] avsnitt 2.2.2.12) som kan specificera namnet på en färgprofil i Unicode UTF16-LE-tecken |
| [setLcs(WmfLogColorSpaceW value)](#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpaceW-) | Hämtar eller anger ett WMF LogColorSpaceW-objekt ([MS-WMF] avsnitt 2.2.2.12) som kan specificera namnet på en färgprofil i Unicode UTF16-LE-tecken |
| [getDwFlags()](#getDwFlags--) | Hämtar eller anger ett 32-bitars osignerat heltal som ger information om data i denna post. |
| [setDwFlags(int value)](#setDwFlags-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som ger information om data i denna post. |
| [getCbData()](#getCbData--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken, i byte, på Data-fältet. |
| [setCbData(int value)](#setCbData-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken, i byte, på Data-fältet. |
| [getData()](#getData--) | Hämtar eller anger en valfri bytearray som specificerar färgprofildata. |
| [setData(byte[] value)](#setData-byte---) | Hämtar eller anger en valfri bytearray som specificerar färgprofildata. |
### EmfCreateColorSpaceW(EmfRecord source) {#EmfCreateColorSpaceW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateColorSpaceW(EmfRecord source)
```


Initierar en ny instans av klassen `EmfCreateColorSpaceW`.

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
public WmfLogColorSpaceW getLcs()
```


Hämtar eller anger ett WMF LogColorSpaceW-objekt ([MS-WMF] avsnitt 2.2.2.12) som kan specificera namnet på en färgprofil i Unicode UTF16-LE-tecken

**Returns:**
[WmfLogColorSpaceW](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew)
### setLcs(WmfLogColorSpaceW value) {#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpaceW-}
```
public void setLcs(WmfLogColorSpaceW value)
```


Hämtar eller anger ett WMF LogColorSpaceW-objekt ([MS-WMF] avsnitt 2.2.2.12) som kan specificera namnet på en färgprofil i Unicode UTF16-LE-tecken

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WmfLogColorSpaceW](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew) |  |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


Hämtar eller anger ett 32-bitars osignerat heltal som ger information om data i denna post.

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som ger information om data i denna post.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken, i byte, på Data-fältet.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken, i byte, på Data-fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Hämtar eller anger en valfri bytearray som specificerar färgprofildata.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Hämtar eller anger en valfri bytearray som specificerar färgprofildata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

