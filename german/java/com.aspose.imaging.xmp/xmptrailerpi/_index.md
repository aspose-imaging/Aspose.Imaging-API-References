---
title: "XmpTrailerPi"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt die XMP-Trailer-Verarbeitungsanweisung dar."
type: docs
weight: 23
url: /de/java/com.aspose.imaging.xmp/xmptrailerpi/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpTrailerPi implements IXmlValue, System.IEquatable<XmpTrailerPi>
```

Stellt die XMP-Trailer-Verarbeitungsanweisung dar.

Der Teil end="w" oder end="r" soll von Paket‑Scanning‑Prozessoren verwendet werden, um zu bestimmen, ob das XMP in‑Place geändert werden darf.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XmpTrailerPi(boolean isWritable)](#XmpTrailerPi-boolean-) | Initialisiert eine neue Instanz der Klasse `XmpTrailerPi`. |
| [XmpTrailerPi()](#XmpTrailerPi--) | Initialisiert eine neue Instanz der Klasse `XmpTrailerPi`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isWritable()](#isWritable--) | Liest oder setzt einen Wert, der angibt, ob diese Instanz schreibbar ist. |
| [setWritable(boolean value)](#setWritable-boolean-) | Liest oder setzt einen Wert, der angibt, ob diese Instanz schreibbar ist. |
| [getXmlValue()](#getXmlValue--) | Konvertiert den xmp-Wert in die XML-Darstellung. |
| [isEquals(XmpTrailerPi other)](#isEquals-com.aspose.imaging.xmp.XmpTrailerPi-) | Gibt an, ob das aktuelle Objekt einem anderen Objekt desselben Typs gleich ist. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene `System.Object` gleich dieser Instanz ist. |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für diese Instanz zurück. |
### XmpTrailerPi(boolean isWritable) {#XmpTrailerPi-boolean-}
```
public XmpTrailerPi(boolean isWritable)
```


Initialisiert eine neue Instanz der Klasse `XmpTrailerPi`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isWritable | boolean | Gibt an, ob der Trailer beschreibbar ist. |

### XmpTrailerPi() {#XmpTrailerPi--}
```
public XmpTrailerPi()
```


Initialisiert eine neue Instanz der Klasse `XmpTrailerPi`.

### isWritable() {#isWritable--}
```
public boolean isWritable()
```


Liest oder setzt einen Wert, der angibt, ob diese Instanz schreibbar ist.

Wert: `true`, wenn diese Instanz beschreibbar ist; andernfalls `false`.

**Returns:**
boolean
### setWritable(boolean value) {#setWritable-boolean-}
```
public void setWritable(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob diese Instanz schreibbar ist.

Wert: `true`, wenn diese Instanz beschreibbar ist; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Konvertiert den xmp-Wert in die XML-Darstellung.

**Returns:**
java.lang.String - Gibt die XML-Darstellung von XMP zurück.
### isEquals(XmpTrailerPi other) {#isEquals-com.aspose.imaging.xmp.XmpTrailerPi-}
```
public boolean isEquals(XmpTrailerPi other)
```


Gibt an, ob das aktuelle Objekt einem anderen Objekt desselben Typs gleich ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | [XmpTrailerPi](../../com.aspose.imaging.xmp/xmptrailerpi) | Ein Objekt zum Vergleich mit diesem Objekt. |

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
