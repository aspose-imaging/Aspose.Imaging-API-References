---
title: "Time"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representation av ett tidsvärde i sekunder."
type: docs
weight: 14
url: /sv/java/com.aspose.imaging.xmp.schemas.xmpdm/time/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class Time extends XmpTypeBase
```

Representation av ett tidsvärde i sekunder.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Time(Rational scale, int value)](#Time-com.aspose.imaging.xmp.types.derived.Rational-int-) | Initierar en ny instans av `Time`-klassen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getScale()](#getScale--) | Hämtar eller sätter skala för tidsvärdet. |
| [setScale(Rational value)](#setScale-com.aspose.imaging.xmp.types.derived.Rational-) | Hämtar eller sätter skala för tidsvärdet. |
| [getValue()](#getValue--) | Hämtar eller anger tidsvärde i den angivna skalan. |
| [setValue(int value)](#setValue-int-) | Hämtar eller anger tidsvärde i den angivna skalan. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Hämtar det stränginnehållande värdet i XMP-format. |
### Time(Rational scale, int value) {#Time-com.aspose.imaging.xmp.types.derived.Rational-int-}
```
public Time(Rational scale, int value)
```


Initierar en ny instans av `Time`-klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scale | [Rational](../../com.aspose.imaging.xmp.types.derived/rational) | Skalan. |
| värde | int | Värdet. |

### getScale() {#getScale--}
```
public Rational getScale()
```


Hämtar eller sätter skala för tidsvärdet.

För NTSC, använd 1001/30000, eller den mindre exakta 100/2997. För PAL, använd 1/25. Värde: Skalan för tidsvärdet.

**Returns:**
[Rational](../../com.aspose.imaging.xmp.types.derived/rational)
### setScale(Rational value) {#setScale-com.aspose.imaging.xmp.types.derived.Rational-}
```
public void setScale(Rational value)
```


Hämtar eller sätter skala för tidsvärdet.

För NTSC, använd 1001/30000, eller den mindre exakta 100/2997. För PAL, använd 1/25. Värde: Skalan för tidsvärdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rational](../../com.aspose.imaging.xmp.types.derived/rational) |  |

### getValue() {#getValue--}
```
public int getValue()
```


Hämtar eller anger tidsvärde i den angivna skalan.

Värde: Tidsvärdet i den angivna skalan.

**Returns:**
int
### setValue(int value) {#setValue-int-}
```
public void setValue(int value)
```


Hämtar eller anger tidsvärde i den angivna skalan.

Värde: Tidsvärdet i den angivna skalan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Hämtar det stränginnehållande värdet i XMP-format.

**Returns:**
java.lang.String - Returnerar det stränginnehållande värdet i XMP-format.
