---
title: "XmpDate"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar datum i XMP-paket."
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.xmp.types.basic/xmpdate/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class XmpDate extends XmpTypeBase
```

Representerar datum i XMP-paket.

Ett datum-tidsvärde representeras med hjälp av en delmängd av formaten som definieras i Datum- och tidsformat: YYYY YYYY-MM YYYY-MM-DD YYYY-MM-DDThh:mmTZD YYYY-MM-DDThh:mm:ssTZD YYYY-MM-DDThh:mm:ss.sTZD
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [XmpDate(Date dateTime)](#XmpDate-java.util.Date-) | Initierar en ny instans av klassen `XmpDate`. |
| [XmpDate(String dateString)](#XmpDate-java.lang.String-) | Initierar en ny instans av klassen `XmpDate`. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [ISO_8601_FORMAT](#ISO-8601-FORMAT) | ISO 8601 (roundtrip)-formatsträngen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getValue()](#getValue--) | Hämtar eller anger datumvärdet. |
| [setValue(Date value)](#setValue-java.util.Date-) | Hämtar eller anger datumvärdet. |
| [getFormat()](#getFormat--) | Hämtar formatsträngen för aktuellt värde. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Returnerar strängens innehållsvärde i XMP-format. |
### XmpDate(Date dateTime) {#XmpDate-java.util.Date-}
```
public XmpDate(Date dateTime)
```


Initierar en ny instans av klassen `XmpDate`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dateTime | java.util.Date | Ett datum‑tid‑värde som representeras med en delmängd av ISO RFC 8601‑formatering. |

### XmpDate(String dateString) {#XmpDate-java.lang.String-}
```
public XmpDate(String dateString)
```


Initierar en ny instans av klassen `XmpDate`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dateString | java.lang.String | Strängrepresentationen av datumet. |

### ISO_8601_FORMAT {#ISO-8601-FORMAT}
```
public static final String ISO_8601_FORMAT
```


ISO 8601 (roundtrip)-formatsträngen.

Se mer: [ här ][here].


[here]: https://en.wikipedia.org/wiki/ISO_8601

### getValue() {#getValue--}
```
public Date getValue()
```


Hämtar eller anger datumvärdet.

Värde: datumvärdet.

**Returns:**
java.util.Date
### setValue(Date value) {#setValue-java.util.Date-}
```
public void setValue(Date value)
```


Hämtar eller anger datumvärdet.

Värde: datumvärdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.Date |  |

### getFormat() {#getFormat--}
```
public String getFormat()
```


Hämtar formatsträngen för aktuellt värde.

Värde: Formatsträngen för aktuellt värde.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Returnerar strängens innehållsvärde i XMP-format.

**Returns:**
java.lang.String – Returnerar en sträng som innehåller xmp‑representation.
