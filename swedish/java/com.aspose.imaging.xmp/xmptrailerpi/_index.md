---
title: "XmpTrailerPi"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar XMP‑trailer‑bearbetningsinstruktion."
type: docs
weight: 23
url: /sv/java/com.aspose.imaging.xmp/xmptrailerpi/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpTrailerPi implements IXmlValue, System.IEquatable<XmpTrailerPi>
```

Representerar XMP‑trailer‑bearbetningsinstruktion.

Den end=\"w\" eller end=\"r\" delen ska användas av paket-scanningsprocessorer för att avgöra om XMP kan modifieras på plats.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [XmpTrailerPi(boolean isWritable)](#XmpTrailerPi-boolean-) | Initierar en ny instans av klassen `XmpTrailerPi`. |
| [XmpTrailerPi()](#XmpTrailerPi--) | Initierar en ny instans av klassen `XmpTrailerPi`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isWritable()](#isWritable--) | Hämtar eller anger ett värde som indikerar om den här instansen är skrivbar. |
| [setWritable(boolean value)](#setWritable-boolean-) | Hämtar eller anger ett värde som indikerar om den här instansen är skrivbar. |
| [getXmlValue()](#getXmlValue--) | Konvertar xmp‑värde till xml‑representationen. |
| [isEquals(XmpTrailerPi other)](#isEquals-com.aspose.imaging.xmp.XmpTrailerPi-) | Indikerar om det aktuella objektet är lika med ett annat objekt av samma typ. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om det angivna `System.Object` är lika med den här instansen. |
| [hashCode()](#hashCode--) | Returnerar en hashkod för detta objekt. |
### XmpTrailerPi(boolean isWritable) {#XmpTrailerPi-boolean-}
```
public XmpTrailerPi(boolean isWritable)
```


Initierar en ny instans av klassen `XmpTrailerPi`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isWritable | boolean | Anger om trailer är skrivbar. |

### XmpTrailerPi() {#XmpTrailerPi--}
```
public XmpTrailerPi()
```


Initierar en ny instans av klassen `XmpTrailerPi`.

### isWritable() {#isWritable--}
```
public boolean isWritable()
```


Hämtar eller anger ett värde som indikerar om den här instansen är skrivbar.

Värde: `true` om detta objekt är skrivbart; annars `false`.

**Returns:**
boolean
### setWritable(boolean value) {#setWritable-boolean-}
```
public void setWritable(boolean value)
```


Hämtar eller anger ett värde som indikerar om den här instansen är skrivbar.

Värde: `true` om detta objekt är skrivbart; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Konvertar xmp‑värde till xml‑representationen.

**Returns:**
java.lang.String - Returnerar XML‑representation av XMP.
### isEquals(XmpTrailerPi other) {#isEquals-com.aspose.imaging.xmp.XmpTrailerPi-}
```
public boolean isEquals(XmpTrailerPi other)
```


Indikerar om det aktuella objektet är lika med ett annat objekt av samma typ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [XmpTrailerPi](../../com.aspose.imaging.xmp/xmptrailerpi) | Ett objekt att jämföra med detta objekt. |

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
