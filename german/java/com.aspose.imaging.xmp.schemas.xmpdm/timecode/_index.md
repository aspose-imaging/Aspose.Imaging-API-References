---
title: "Timecode"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt den Timecode-Wert im Video dar."
type: docs
weight: 16
url: /de/java/com.aspose.imaging.xmp.schemas.xmpdm/timecode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public final class Timecode extends XmpTypeBase implements System.IEquatable<Timecode>
```

Stellt den Timecode-Wert im Video dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Timecode(TimeFormat format, String timeValue)](#Timecode-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-java.lang.String-) | Initialisiert eine neue Instanz der `Timecode`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFormat()](#getFormat--) | Liest oder setzt das im `TimeValue` verwendete Format. |
| [setFormat(TimeFormat value)](#setFormat-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-) | Liest oder setzt das im `TimeValue` verwendete Format. |
| [getTimeValue()](#getTimeValue--) | Liest oder setzt den Zeitwert im angegebenen Format. |
| [setTimeValue(String value)](#setTimeValue-java.lang.String-) | Liest oder setzt den Zeitwert im angegebenen Format. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Gibt den im String enthaltenen Wert im XMP-Format zurück. |
| [isEquals(Timecode other)](#isEquals-com.aspose.imaging.xmp.schemas.xmpdm.Timecode-) | Gibt an, ob das aktuelle Objekt einem anderen Objekt desselben Typs gleich ist. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene `System.Object` gleich dieser Instanz ist. |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für diese Instanz zurück. |
### Timecode(TimeFormat format, String timeValue) {#Timecode-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-java.lang.String-}
```
public Timecode(TimeFormat format, String timeValue)
```


Initialisiert eine neue Instanz der `Timecode`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| format | [TimeFormat](../../com.aspose.imaging.xmp.schemas.xmpdm/timeformat) | Das Zeitformat. |
| timeValue | java.lang.String | Der Zeitwert. |

### getFormat() {#getFormat--}
```
public TimeFormat getFormat()
```


Liest oder setzt das im `TimeValue` verwendete Format.

Wert: Das im `TimeValue` verwendete Format.

**Returns:**
[TimeFormat](../../com.aspose.imaging.xmp.schemas.xmpdm/timeformat)
### setFormat(TimeFormat value) {#setFormat-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-}
```
public void setFormat(TimeFormat value)
```


Liest oder setzt das im `TimeValue` verwendete Format.

Wert: Das im `TimeValue` verwendete Format.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TimeFormat](../../com.aspose.imaging.xmp.schemas.xmpdm/timeformat) |  |

### getTimeValue() {#getTimeValue--}
```
public String getTimeValue()
```


Liest oder setzt den Zeitwert im angegebenen Format.

Wert: Der Zeitwert im angegebenen Format.

**Returns:**
java.lang.String
### setTimeValue(String value) {#setTimeValue-java.lang.String-}
```
public void setTimeValue(String value)
```


Liest oder setzt den Zeitwert im angegebenen Format.

Wert: Der Zeitwert im angegebenen Format.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Gibt den im String enthaltenen Wert im XMP-Format zurück.

**Returns:**
java.lang.String - Gibt den String zurück, der die XMP-Darstellung enthält.
### isEquals(Timecode other) {#isEquals-com.aspose.imaging.xmp.schemas.xmpdm.Timecode-}
```
public boolean isEquals(Timecode other)
```


Gibt an, ob das aktuelle Objekt einem anderen Objekt desselben Typs gleich ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | [Timecode](../../com.aspose.imaging.xmp.schemas.xmpdm/timecode) | Ein Objekt zum Vergleich mit diesem Objekt. |

**Returns:**
boolean - true, wenn das aktuelle Objekt dem Parameter `other` entspricht; andernfalls false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob das angegebene `System.Object` gleich dieser Instanz ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das `System.Object` zum Vergleich mit dieser Instanz. |

**Returns:**
boolean - `true`, wenn das angegebene `System.Object` dieser Instanz gleich ist; andernfalls `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für diese Instanz zurück.

**Returns:**
int – Ein Hashcode für diese Instanz, geeignet für den Einsatz in Hash‑Algorithmen und Datenstrukturen wie einer Hashtabelle.
