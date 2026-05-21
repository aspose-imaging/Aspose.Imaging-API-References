---
title: "XmpHeaderPi"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt die XMP-Header-Verarbeitungsanweisung dar."
type: docs
weight: 17
url: /de/java/com.aspose.imaging.xmp/xmpheaderpi/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpHeaderPi implements IXmlValue, System.IEquatable<XmpHeaderPi>
```

Stellt die XMP-Header-Verarbeitungsanweisung dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XmpHeaderPi()](#XmpHeaderPi--) | Initialisiert eine neue Instanz der Klasse `XmpHeaderPi`. |
| [XmpHeaderPi(String guid)](#XmpHeaderPi-java.lang.String-) | Initialisiert eine neue Instanz der Klasse `XmpHeaderPi`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getGuid()](#getGuid--) | Stellt Header-Guid dar. |
| [setGuid(String value)](#setGuid-java.lang.String-) | Stellt Header-Guid dar. |
| [getXmlValue()](#getXmlValue--) | Konvertiert den XMP-Wert in die XML-Darstellung. |
| [isEquals(XmpHeaderPi other)](#isEquals-com.aspose.imaging.xmp.XmpHeaderPi-) | Gibt an, ob das aktuelle Objekt einem anderen Objekt desselben Typs gleich ist. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene `System.Object` gleich dieser Instanz ist. |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für diese Instanz zurück. |
### XmpHeaderPi() {#XmpHeaderPi--}
```
public XmpHeaderPi()
```


Initialisiert eine neue Instanz der Klasse `XmpHeaderPi`.

### XmpHeaderPi(String guid) {#XmpHeaderPi-java.lang.String-}
```
public XmpHeaderPi(String guid)
```


Initialisiert eine neue Instanz der Klasse `XmpHeaderPi`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| guid | java.lang.String | Der eindeutige Bezeichner. |

### getGuid() {#getGuid--}
```
public String getGuid()
```


Stellt Header-Guid dar.

Der Text der Header-PI enthält eine GUID, wodurch es unwahrscheinlich ist, dass er versehentlich im Datenstrom erscheint.

**Returns:**
java.lang.String
### setGuid(String value) {#setGuid-java.lang.String-}
```
public void setGuid(String value)
```


Stellt Header-Guid dar.

Der Text der Header-PI enthält eine GUID, wodurch es unwahrscheinlich ist, dass er versehentlich im Datenstrom erscheint.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Konvertiert den XMP-Wert in die XML-Darstellung.

**Returns:**
java.lang.String - Gibt den XMP-Wert zurück, der in die XML-Darstellung konvertiert wurde.
### isEquals(XmpHeaderPi other) {#isEquals-com.aspose.imaging.xmp.XmpHeaderPi-}
```
public boolean isEquals(XmpHeaderPi other)
```


Gibt an, ob das aktuelle Objekt einem anderen Objekt desselben Typs gleich ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | [XmpHeaderPi](../../com.aspose.imaging.xmp/xmpheaderpi) | Ein Objekt zum Vergleich mit diesem Objekt. |

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
