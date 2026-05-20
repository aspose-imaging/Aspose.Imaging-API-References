---
title: "XmpDate"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt ein Datum im XMP-Paket dar."
type: docs
weight: 11
url: /de/java/com.aspose.imaging.xmp.types.basic/xmpdate/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class XmpDate extends XmpTypeBase
```

Stellt ein Datum im XMP-Paket dar.

Ein Datum‑Uhrzeit‑Wert wird unter Verwendung eines Teilbereichs der Formate dargestellt, wie in Datums‑ und Zeitformaten definiert: YYYY YYYY-MM YYYY-MM-DD YYYY-MM-DDThh:mmTZD YYYY-MM-DDThh:mm:ssTZD YYYY-MM-DDThh:mm:ss.sTZD
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XmpDate(Date dateTime)](#XmpDate-java.util.Date-) | Initialisiert eine neue Instanz der `XmpDate`-Klasse. |
| [XmpDate(String dateString)](#XmpDate-java.lang.String-) | Initialisiert eine neue Instanz der `XmpDate`-Klasse. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [ISO_8601_FORMAT](#ISO-8601-FORMAT) | Der ISO 8601 (Roundtrip)-Formatstring. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getValue()](#getValue--) | Liest oder setzt den Datumswert. |
| [setValue(Date value)](#setValue-java.util.Date-) | Liest oder setzt den Datumswert. |
| [getFormat()](#getFormat--) | Liest die Formatzeichenkette für den aktuellen Wert. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Gibt den enthaltenen Zeichenkettenwert im XMP-Format zurück. |
### XmpDate(Date dateTime) {#XmpDate-java.util.Date-}
```
public XmpDate(Date dateTime)
```


Initialisiert eine neue Instanz der `XmpDate`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dateTime | java.util.Date | Ein Datum-Uhrzeit-Wert, der mit einem Teil der ISO-RFC-8601-Formatierung dargestellt wird. |

### XmpDate(String dateString) {#XmpDate-java.lang.String-}
```
public XmpDate(String dateString)
```


Initialisiert eine neue Instanz der `XmpDate`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dateString | java.lang.String | Die Zeichenkettenrepräsentation des Datums. |

### ISO_8601_FORMAT {#ISO-8601-FORMAT}
```
public static final String ISO_8601_FORMAT
```


Der ISO 8601 (Roundtrip)-Formatstring.

Siehe mehr: [ here ][here].


[here]: https://en.wikipedia.org/wiki/ISO_8601

### getValue() {#getValue--}
```
public Date getValue()
```


Liest oder setzt den Datumswert.

Wert: Der Datumswert.

**Returns:**
java.util.Date
### setValue(Date value) {#setValue-java.util.Date-}
```
public void setValue(Date value)
```


Liest oder setzt den Datumswert.

Wert: Der Datumswert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.Date |  |

### getFormat() {#getFormat--}
```
public String getFormat()
```


Liest die Formatzeichenkette für den aktuellen Wert.

Wert: Die Formatzeichenkette für den aktuellen Wert.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Gibt den enthaltenen Zeichenkettenwert im XMP-Format zurück.

**Returns:**
java.lang.String - Gibt eine Zeichenkette zurück, die die XMP-Darstellung enthält.
