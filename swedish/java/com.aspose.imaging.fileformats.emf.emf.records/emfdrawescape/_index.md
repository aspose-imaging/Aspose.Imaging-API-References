---
title: "EmfDrawEscape"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_DRAWESCAPE-posten överför godtycklig information till en skrivardrivrutin."
type: docs
weight: 44
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfdrawescape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfEscapeRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype)
```
public final class EmfDrawEscape extends EmfEscapeRecordType
```

EMR\_DRAWESCAPE-posten skickar godtycklig information till en skrivardrivrutin. Avsikten är att informationen ska leda till att ritning utförs.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfDrawEscape(EmfRecord source)](#EmfDrawEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfDrawEscape`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCjIn()](#getCjIn--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet byte som ska skickas till skrivardrivrutinen. |
| [setCjIn(int value)](#setCjIn-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet byte som ska skickas till skrivardrivrutinen. |
| [getData()](#getData--) | Hämtar eller anger data som ska skickas till skrivardrivrutinen. |
| [setData(byte[] value)](#setData-byte---) | Hämtar eller anger data som ska skickas till skrivardrivrutinen. |
### EmfDrawEscape(EmfRecord source) {#EmfDrawEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfDrawEscape(EmfRecord source)
```


Initierar en ny instans av klassen `EmfDrawEscape`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### getCjIn() {#getCjIn--}
```
public int getCjIn()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet byte som ska skickas till skrivardrivrutinen.

**Returns:**
int
### setCjIn(int value) {#setCjIn-int-}
```
public void setCjIn(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet byte som ska skickas till skrivardrivrutinen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Hämtar eller anger data som ska skickas till skrivardrivrutinen. Det MÅSTE finnas cjIn byte tillgängliga.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Hämtar eller anger data som ska skickas till skrivardrivrutinen. Det MÅSTE finnas cjIn byte tillgängliga.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

