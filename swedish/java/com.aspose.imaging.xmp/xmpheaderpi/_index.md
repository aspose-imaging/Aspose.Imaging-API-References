---
title: "XmpHeaderPi"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar XMP‑headerns bearbetningsinstruktion."
type: docs
weight: 17
url: /sv/java/com.aspose.imaging.xmp/xmpheaderpi/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpHeaderPi implements IXmlValue, System.IEquatable<XmpHeaderPi>
```

Representerar XMP‑headerns bearbetningsinstruktion.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [XmpHeaderPi()](#XmpHeaderPi--) | Initierar en ny instans av klassen `XmpHeaderPi`. |
| [XmpHeaderPi(String guid)](#XmpHeaderPi-java.lang.String-) | Initierar en ny instans av klassen `XmpHeaderPi`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getGuid()](#getGuid--) | Representerar Header Guid. |
| [setGuid(String value)](#setGuid-java.lang.String-) | Representerar Header Guid. |
| [getXmlValue()](#getXmlValue--) | Konverterar XMP-värde till XML-representationen. |
| [isEquals(XmpHeaderPi other)](#isEquals-com.aspose.imaging.xmp.XmpHeaderPi-) | Indikerar om det aktuella objektet är lika med ett annat objekt av samma typ. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om det angivna `System.Object` är lika med den här instansen. |
| [hashCode()](#hashCode--) | Returnerar en hashkod för detta objekt. |
### XmpHeaderPi() {#XmpHeaderPi--}
```
public XmpHeaderPi()
```


Initierar en ny instans av klassen `XmpHeaderPi`.

### XmpHeaderPi(String guid) {#XmpHeaderPi-java.lang.String-}
```
public XmpHeaderPi(String guid)
```


Initierar en ny instans av klassen `XmpHeaderPi`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| guid | java.lang.String | Den unika identifieraren. |

### getGuid() {#getGuid--}
```
public String getGuid()
```


Representerar Header Guid.

Texten i header-PI innehåller ett GUID, vilket gör det osannolikt att den visas av misstag i dataströmmen.

**Returns:**
java.lang.String
### setGuid(String value) {#setGuid-java.lang.String-}
```
public void setGuid(String value)
```


Representerar Header Guid.

Texten i header-PI innehåller ett GUID, vilket gör det osannolikt att den visas av misstag i dataströmmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Konverterar XMP-värde till XML-representationen.

**Returns:**
java.lang.String - Returnerar XMP‑värdet konverterat till XML-representationen.
### isEquals(XmpHeaderPi other) {#isEquals-com.aspose.imaging.xmp.XmpHeaderPi-}
```
public boolean isEquals(XmpHeaderPi other)
```


Indikerar om det aktuella objektet är lika med ett annat objekt av samma typ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [XmpHeaderPi](../../com.aspose.imaging.xmp/xmpheaderpi) | Ett objekt att jämföra med detta objekt. |

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
