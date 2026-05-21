---
title: "EmfSetIcmProfileA"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_SETICMPROFILEA-posten specificerar en färgprofil i en fil med ett namn bestående av ASCII-tecken för grafikoutput."
type: docs
weight: 126
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetIcmProfileA extends EmfStateRecordType
```

EMR\\_SETICMPROFILEA-posten specificerar en färgprofil i en fil med ett namn bestående av ASCII-tecken, för grafikutmatning.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfSetIcmProfileA(EmfRecord source)](#EmfSetIcmProfileA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfSetIcmProfileA` . |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDwFlags()](#getDwFlags--) | Hämtar eller anger ett 32-bitars osignerat heltal som innehåller flaggor för färgprofil. |
| [setDwFlags(int value)](#setDwFlags-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som innehåller flaggor för färgprofil. |
| [getCbName()](#getCbName--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet byte i ASCII-namnet för den önskade färgprofilen. |
| [setCbName(int value)](#setCbName-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet byte i ASCII-namnet för den önskade färgprofilen. |
| [getCbData()](#getCbData--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken på färgprofilens data, om den finns i Data-fältet. |
| [setCbData(int value)](#setCbData-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken på färgprofilens data, om den finns i Data-fältet. |
| [getData()](#getData--) | Hämtar eller anger en array av storlek (cbName + cbData) i byte, som specificerar ASCII-namnet och rådata för den önskade färgprofilen. |
| [setData(byte[] value)](#setData-byte---) | Hämtar eller anger en array av storlek (cbName + cbData) i byte, som specificerar ASCII-namnet och rådata för den önskade färgprofilen. |
| [getName()](#getName--) | Hämtar namnet |
| [getRawData()](#getRawData--) | Hämtar rådata |
### EmfSetIcmProfileA(EmfRecord source) {#EmfSetIcmProfileA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetIcmProfileA(EmfRecord source)
```


Initierar en ny instans av klassen `EmfSetIcmProfileA` .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


Hämtar eller anger ett 32-bitars osignerat heltal som innehåller flaggor för färgprofil.

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som innehåller flaggor för färgprofil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCbName() {#getCbName--}
```
public int getCbName()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet byte i ASCII-namnet för den önskade färgprofilen.

**Returns:**
int
### setCbName(int value) {#setCbName-int-}
```
public void setCbName(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet byte i ASCII-namnet för den önskade färgprofilen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken på färgprofilens data, om den finns i Data-fältet.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken på färgprofilens data, om den finns i Data-fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Hämtar eller anger en array av storlek (cbName + cbData) i byte, som specificerar ASCII-namnet och rådata för den önskade färgprofilen.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Hämtar eller anger en array av storlek (cbName + cbData) i byte, som specificerar ASCII-namnet och rådata för den önskade färgprofilen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### getName() {#getName--}
```
public String getName()
```


Hämtar namnet

**Returns:**
java.lang.String
### getRawData() {#getRawData--}
```
public byte[] getRawData()
```


Hämtar rådata

**Returns:**
byte[]
