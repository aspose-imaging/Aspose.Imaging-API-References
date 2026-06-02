---
title: "EmfNamedEscape"
second_title: "Aspose.Imaging för Java API-referens"
description: "MR_NAMEDESCAPE‑posten överför godtycklig information till en specificerad skrivardrivrutin."
type: docs
weight: 75
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfnamedescape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfEscapeRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype)
```
public final class EmfNamedEscape extends EmfEscapeRecordType
```

MR\_NAMEDESCAPE‑posten överför godtycklig information till en specificerad skrivardrivrutin.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfNamedEscape(EmfRecord source)](#EmfNamedEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfNamedEscape`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCjDriver()](#getCjDriver--) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar antalet byte i fältet DriverName. |
| [setCjDriver(int value)](#setCjDriver-int-) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar antalet byte i fältet DriverName. |
| [getCjIn()](#getCjIn--) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar antalet byte som ska skickas till skrivardrivrutinen. |
| [setCjIn(int value)](#setCjIn-int-) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar antalet byte som ska skickas till skrivardrivrutinen. |
| [getDriverName()](#getDriverName--) | Hämtar eller anger en sträng av 16‑bitars Unicode‑tecken som specificerar namnet på skrivardrivrutinen som ska ta emot data. |
| [setDriverName(String value)](#setDriverName-java.lang.String-) | Hämtar eller anger en sträng av 16‑bitars Unicode‑tecken som specificerar namnet på skrivardrivrutinen som ska ta emot data. |
| [getData()](#getData--) | Hämtar eller anger data som ska skickas till skrivardrivrutinen. |
| [setData(byte[] value)](#setData-byte---) | Hämtar eller anger data som ska skickas till skrivardrivrutinen. |
### EmfNamedEscape(EmfRecord source) {#EmfNamedEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfNamedEscape(EmfRecord source)
```


Initierar en ny instans av klassen `EmfNamedEscape`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### getCjDriver() {#getCjDriver--}
```
public int getCjDriver()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar antalet byte i fältet DriverName. Detta värde MÅSTE vara ett jämnt tal.

**Returns:**
int
### setCjDriver(int value) {#setCjDriver-int-}
```
public void setCjDriver(int value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar antalet byte i fältet DriverName. Detta värde MÅSTE vara ett jämnt tal.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCjIn() {#getCjIn--}
```
public int getCjIn()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar antalet byte som ska skickas till skrivardrivrutinen.

**Returns:**
int
### setCjIn(int value) {#setCjIn-int-}
```
public void setCjIn(int value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar antalet byte som ska skickas till skrivardrivrutinen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getDriverName() {#getDriverName--}
```
public String getDriverName()
```


Hämtar eller anger en sträng av 16‑bitars Unicode‑tecken som specificerar namnet på skrivardrivrutinen som ska ta emot data. Detta värde MÅSTE vara cjDriver byte långt och det MÅSTE avslutas med ett nolltecken.

**Returns:**
java.lang.String
### setDriverName(String value) {#setDriverName-java.lang.String-}
```
public void setDriverName(String value)
```


Hämtar eller anger en sträng av 16‑bitars Unicode‑tecken som specificerar namnet på skrivardrivrutinen som ska ta emot data. Detta värde MÅSTE vara cjDriver byte långt och det MÅSTE avslutas med ett nolltecken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

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

