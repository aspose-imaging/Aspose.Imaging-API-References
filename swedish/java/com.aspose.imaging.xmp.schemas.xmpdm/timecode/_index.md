---
title: "Timecode"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar timecodevärde i video."
type: docs
weight: 16
url: /sv/java/com.aspose.imaging.xmp.schemas.xmpdm/timecode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public final class Timecode extends XmpTypeBase implements System.IEquatable<Timecode>
```

Representerar timecodevärde i video.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Timecode(TimeFormat format, String timeValue)](#Timecode-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-java.lang.String-) | Initierar en ny instans av klassen `Timecode`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFormat()](#getFormat--) | Hämtar eller anger formatet som används i `TimeValue`. |
| [setFormat(TimeFormat value)](#setFormat-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-) | Hämtar eller anger formatet som används i `TimeValue`. |
| [getTimeValue()](#getTimeValue--) | Hämtar eller anger tidsvärdet i det angivna formatet. |
| [setTimeValue(String value)](#setTimeValue-java.lang.String-) | Hämtar eller anger tidsvärdet i det angivna formatet. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Returnerar den stränginnehållande värdet i XMP-format. |
| [isEquals(Timecode other)](#isEquals-com.aspose.imaging.xmp.schemas.xmpdm.Timecode-) | Indikerar om det aktuella objektet är lika med ett annat objekt av samma typ. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om det angivna `System.Object` är lika med den här instansen. |
| [hashCode()](#hashCode--) | Returnerar en hashkod för detta objekt. |
### Timecode(TimeFormat format, String timeValue) {#Timecode-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-java.lang.String-}
```
public Timecode(TimeFormat format, String timeValue)
```


Initierar en ny instans av klassen `Timecode`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | [TimeFormat](../../com.aspose.imaging.xmp.schemas.xmpdm/timeformat) | Tidsformatet. |
| timeValue | java.lang.String | Tidsvärdet. |

### getFormat() {#getFormat--}
```
public TimeFormat getFormat()
```


Hämtar eller anger formatet som används i `TimeValue`.

Värde: Formatet som används i `TimeValue`.

**Returns:**
[TimeFormat](../../com.aspose.imaging.xmp.schemas.xmpdm/timeformat)
### setFormat(TimeFormat value) {#setFormat-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-}
```
public void setFormat(TimeFormat value)
```


Hämtar eller anger formatet som används i `TimeValue`.

Värde: Formatet som används i `TimeValue`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TimeFormat](../../com.aspose.imaging.xmp.schemas.xmpdm/timeformat) |  |

### getTimeValue() {#getTimeValue--}
```
public String getTimeValue()
```


Hämtar eller anger tidsvärdet i det angivna formatet.

Värde: Tidsvärdet i det angivna formatet.

**Returns:**
java.lang.String
### setTimeValue(String value) {#setTimeValue-java.lang.String-}
```
public void setTimeValue(String value)
```


Hämtar eller anger tidsvärdet i det angivna formatet.

Värde: Tidsvärdet i det angivna formatet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Returnerar den stränginnehållande värdet i XMP-format.

**Returns:**
java.lang.String - Returnerar strängen som innehåller xmp-representationen.
### isEquals(Timecode other) {#isEquals-com.aspose.imaging.xmp.schemas.xmpdm.Timecode-}
```
public boolean isEquals(Timecode other)
```


Indikerar om det aktuella objektet är lika med ett annat objekt av samma typ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [Timecode](../../com.aspose.imaging.xmp.schemas.xmpdm/timecode) | Ett objekt att jämföra med detta objekt. |

**Returns:**
boolean - true om det aktuella objektet är lika med parametern `other`; annars false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om det angivna `System.Object` är lika med den här instansen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Den `System.Object` att jämföra med denna instans. |

**Returns:**
boolean - `true` om det angivna `System.Object` är lika med denna instans; annars `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för detta objekt.

**Returns:**
int - En hashkod för denna instans, lämplig för användning i hash-algoritmer och datastrukturer som en hash‑tabell.
