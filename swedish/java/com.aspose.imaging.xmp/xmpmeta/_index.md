---
title: "XmpMeta"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar xmp‑meta."
type: docs
weight: 18
url: /sv/java/com.aspose.imaging.xmp/xmpmeta/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpElementBase](../../com.aspose.imaging.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpMeta extends XmpElementBase implements IXmlValue, System.IEquatable<XmpElementBase>
```

Representerar xmp meta. Valfritt. Syftet med detta element är att identifiera XMP-metadata inom generell XML-text som kan innehålla andra icke-XMP-användningar av RDF.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [XmpMeta(String toolkitVersion)](#XmpMeta-java.lang.String-) | Initierar en ny instans av klassen `XmpMeta`. |
| [XmpMeta()](#XmpMeta--) | Initierar en ny instans av klassen `XmpMeta`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAdobeXmpToolkit()](#getAdobeXmpToolkit--) | Hämtar eller anger Adobe Xmp-verktygsversion. |
| [setAdobeXmpToolkit(String value)](#setAdobeXmpToolkit-java.lang.String-) | Hämtar eller anger Adobe Xmp-verktygsversion. |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Lägger till attributet. |
| [getXmlValue()](#getXmlValue--) | Konverterar XMP-värde till XML-representationen. |
| [isEquals(XmpMeta other)](#isEquals-com.aspose.imaging.xmp.XmpMeta-) | Indikerar om det aktuella objektet är lika med ett annat objekt av samma typ. |
| [equals(Object other)](#equals-java.lang.Object-) | Bestämmer om det angivna `System.Object` är lika med den här instansen. |
| [hashCode()](#hashCode--) | Returnerar en hashkod för detta objekt. |
### XmpMeta(String toolkitVersion) {#XmpMeta-java.lang.String-}
```
public XmpMeta(String toolkitVersion)
```


Initierar en ny instans av klassen `XmpMeta`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| toolkitVersion | java.lang.String | Adobe XMP-verktygsversion. |

### XmpMeta() {#XmpMeta--}
```
public XmpMeta()
```


Initierar en ny instans av klassen `XmpMeta`.

### getAdobeXmpToolkit() {#getAdobeXmpToolkit--}
```
public String getAdobeXmpToolkit()
```


Hämtar eller anger Adobe Xmp-verktygsversion.

**Returns:**
java.lang.String
### setAdobeXmpToolkit(String value) {#setAdobeXmpToolkit-java.lang.String-}
```
public void setAdobeXmpToolkit(String value)
```


Hämtar eller anger Adobe Xmp-verktygsversion.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

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

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Konverterar XMP-värde till XML-representationen.

**Returns:**
java.lang.String - Returnerar XMP‑värdet konverterat till XML-representationen.
### isEquals(XmpMeta other) {#isEquals-com.aspose.imaging.xmp.XmpMeta-}
```
public boolean isEquals(XmpMeta other)
```


Indikerar om det aktuella objektet är lika med ett annat objekt av samma typ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) | Ett objekt att jämföra med detta objekt. |

**Returns:**
boolean - true om det aktuella objektet är lika med parametern `other`; annars false.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Bestämmer om det angivna `System.Object` är lika med den här instansen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| annat | java.lang.Object | Den `System.Object` att jämföra med denna instans. |

**Returns:**
boolean - `true` om det angivna `System.Object` är lika med denna instans; annars `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för detta objekt.

**Returns:**
int - En hashkod för denna instans, lämplig för användning i hash-algoritmer och datastrukturer som en hash‑tabell.
