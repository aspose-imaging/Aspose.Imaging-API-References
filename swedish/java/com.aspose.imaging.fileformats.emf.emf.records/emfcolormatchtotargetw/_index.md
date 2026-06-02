---
title: "EmfColorMatchToTargetW"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_COLORMATCHTOTargetW-posten specificerar huruvida färgmatchning ska utföras med en färgprofil som är specificerad i en fil med ett namn bestående av Unicode-tecken."
type: docs
weight: 24
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfColorMatchToTargetW extends EmfStateRecordType
```

EMR\_COLORMATCHTOTargetW-posten specificerar om färgmatchning ska utföras med en färgprofil som anges i en fil vars namn består av Unicode‑tecken.

En EMR\_COLORMATCHTOTargetW-post kan användas för att styra huruvida den aktuella färgtransformen ska tillämpas i uppspelningsenhetens kontext. Om dwAction‑värdet är CS\_ENABLE är färgkartläggning aktiverad, och den aktuella färgtransformen SKA tillämpas på efterföljande grafikoperationer. Om dwAction är satt till CS\_DISABLE SKA färgtransformen INTE tillämpas. Medan färgkartläggning till målet är aktiverad av ett dwAction‑värde på CS\_ENABLE, tillämpas inte förändringar av färgrymden eller färgtonomappning. Däremot MÅSTE dessa förändringar träda i kraft när färgkartläggning till målet är inaktiverad. dwAction‑fältet SKA INTE sättas till CS\_DELETE\_TRANSFORM om färghantering inte redan har aktiverats med en EMR\_SETICMMODE-post (avsnitt 2.3.11.14).
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfColorMatchToTargetW(EmfRecord source)](#EmfColorMatchToTargetW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfColorMatchToTargetW`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDwAction()](#getDwAction--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar ett värde från ColorSpace‑enumerationen (avsnitt 2.1.7). |
| [setDwAction(int value)](#setDwAction-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar ett värde från ColorSpace‑enumerationen (avsnitt 2.1.7). |
| [getDwFlags()](#getDwFlags--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar ett värde från ColorMatchToTarget‑enumerationen (avsnitt 2.1.6). |
| [setDwFlags(int value)](#setDwFlags-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar ett värde från ColorMatchToTarget‑enumerationen (avsnitt 2.1.6). |
| [getCbName()](#getCbName--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet byte i Unicode UTF16-LE‑namnet på den önskade färgprofilen. |
| [setCbName(int value)](#setCbName-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet byte i Unicode UTF16-LE‑namnet på den önskade färgprofilen. |
| [getCbData()](#getCbData--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken på rådata för mål‑färgprofilen, om den finns i Data‑fältet. |
| [setCbData(int value)](#setCbData-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken på rådata för mål‑färgprofilen, om den finns i Data‑fältet. |
| [getData()](#getData--) | Hämtar eller anger en array med storlek (cbName + cbData) i byte, som specificerar UTF16-LE-namnet och rådata för den önskade färgprofilen. |
| [setData(byte[] value)](#setData-byte---) | Hämtar eller anger en array med storlek (cbName + cbData) i byte, som specificerar UTF16-LE-namnet och rådata för den önskade färgprofilen. |
| [getName()](#getName--) | Hämtar namnet |
| [getRawData()](#getRawData--) | Hämtar rådata |
### EmfColorMatchToTargetW(EmfRecord source) {#EmfColorMatchToTargetW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfColorMatchToTargetW(EmfRecord source)
```


Initierar en ny instans av klassen `EmfColorMatchToTargetW`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### getDwAction() {#getDwAction--}
```
public int getDwAction()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar ett värde från ColorSpace‑enumerationen (avsnitt 2.1.7).

**Returns:**
int
### setDwAction(int value) {#setDwAction-int-}
```
public void setDwAction(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar ett värde från ColorSpace‑enumerationen (avsnitt 2.1.7).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar ett värde från ColorMatchToTarget‑enumerationen (avsnitt 2.1.6).

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar ett värde från ColorMatchToTarget‑enumerationen (avsnitt 2.1.6).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCbName() {#getCbName--}
```
public int getCbName()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet byte i Unicode UTF16-LE‑namnet på den önskade färgprofilen.

**Returns:**
int
### setCbName(int value) {#setCbName-int-}
```
public void setCbName(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet byte i Unicode UTF16-LE‑namnet på den önskade färgprofilen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken på rådata för mål‑färgprofilen, om den finns i Data‑fältet.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken på rådata för mål‑färgprofilen, om den finns i Data‑fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Hämtar eller anger en array med storlek (cbName + cbData) i byte, som specificerar UTF16-LE-namnet och rådata för den önskade färgprofilen.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Hämtar eller anger en array med storlek (cbName + cbData) i byte, som specificerar UTF16-LE-namnet och rådata för den önskade färgprofilen.

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
