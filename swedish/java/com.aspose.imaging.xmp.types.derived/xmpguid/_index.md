---
title: "XmpGuid"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar XMP:s globala unika identifierare."
type: docs
weight: 14
url: /sv/java/com.aspose.imaging.xmp.types.derived/xmpguid/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class XmpGuid extends XmpTypeBase
```

Representerar XMP:s globala unika identifierare.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [XmpGuid(String value)](#XmpGuid-java.lang.String-) | Initierar en ny instans av klassen `XmpGuid`. |
| [XmpGuid(UUID guid)](#XmpGuid-java.util.UUID-) | Initierar en ny instans av klassen `XmpGuid`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPrefix()](#getPrefix--) | Hämtar eller anger prefixet, t.ex. uuid. |
| [setPrefix(String value)](#setPrefix-java.lang.String-) | Hämtar eller anger prefixet, t.ex. uuid. |
| [getValue()](#getValue--) | Hämtar eller anger värdet. |
| [setValue(UUID value)](#setValue-java.util.UUID-) | Hämtar eller anger värdet. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Hämtar det stränginnehållande värdet i XMP-format. |
### XmpGuid(String value) {#XmpGuid-java.lang.String-}
```
public XmpGuid(String value)
```


Initierar en ny instans av klassen `XmpGuid`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Värdet. |

### XmpGuid(UUID guid) {#XmpGuid-java.util.UUID-}
```
public XmpGuid(UUID guid)
```


Initierar en ny instans av klassen `XmpGuid`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| guid | java.util.UUID | Den unika identifieraren. |

### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Hämtar eller anger prefixet, t.ex. uuid.

Värde: Prefixet, t.ex. uuid.

**Returns:**
java.lang.String
### setPrefix(String value) {#setPrefix-java.lang.String-}
```
public void setPrefix(String value)
```


Hämtar eller anger prefixet, t.ex. uuid.

Värde: Prefixet, t.ex. uuid.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getValue() {#getValue--}
```
public UUID getValue()
```


Hämtar eller anger värdet.

Värde: Värdet.

**Returns:**
java.util.UUID
### setValue(UUID value) {#setValue-java.util.UUID-}
```
public void setValue(UUID value)
```


Hämtar eller anger värdet.

Värde: Värdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.UUID |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Hämtar det stränginnehållande värdet i XMP-format.

**Returns:**
java.lang.String - Returnerar det stränginnehållande värdet i XMP-format.
