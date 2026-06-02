---
title: "XmpElementBase"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar bas‑xmp‑element som innehåller attribut."
type: docs
weight: 16
url: /sv/java/com.aspose.imaging.xmp/xmpelementbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class XmpElementBase implements System.IEquatable<XmpElementBase>
```

Representerar bas‑xmp‑element som innehåller attribut.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Lägger till attributet. |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | Hämtar attributet. |
| [clearAttributes()](#clearAttributes--) | Tar bort alla attribut. |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.imaging.xmp.XmpElementBase-) | Indikerar om det aktuella objektet är lika med ett annat objekt av samma typ. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om det specificerade `Object` är lika med den här instansen. |
| [hashCode()](#hashCode--) | Returnerar en hashkod för detta objekt. |
### addAttribute(String attribute, String value) {#addAttribute-java.lang.String-java.lang.String-}
```
public void addAttribute(String attribute, String value)
```


Lägger till attributet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| attribut | java.lang.String | Attributet. |
| värde | java.lang.String | Värdet. |

### getAttribute(String attribute) {#getAttribute-java.lang.String-}
```
public String getAttribute(String attribute)
```


Hämtar attributet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| attribut | java.lang.String | Attributet. |

**Returns:**
java.lang.String - Returnerar attributet för angivet attributnamn.
### clearAttributes() {#clearAttributes--}
```
public void clearAttributes()
```


Tar bort alla attribut.

### isEquals(XmpElementBase other) {#isEquals-com.aspose.imaging.xmp.XmpElementBase-}
```
public boolean isEquals(XmpElementBase other)
```


Indikerar om det aktuella objektet är lika med ett annat objekt av samma typ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [XmpElementBase](../../com.aspose.imaging.xmp/xmpelementbase) | Ett objekt att jämföra med detta objekt. |

**Returns:**
boolean - true om det aktuella objektet är lika med parametern `other`; annars false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om det specificerade `Object` är lika med den här instansen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Det `Object` att jämföra med den här instansen. |

**Returns:**
boolean - `true` om det angivna `Object` är lika med den här instansen; annars `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för detta objekt.

**Returns:**
int - En hashkod för denna instans, lämplig för användning i hash-algoritmer och datastrukturer som en hash‑tabell.
