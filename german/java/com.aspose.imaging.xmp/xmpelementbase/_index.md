---
title: "XmpElementBase"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt das Basiselement XMP dar, das Attribute enthält."
type: docs
weight: 16
url: /de/java/com.aspose.imaging.xmp/xmpelementbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class XmpElementBase implements System.IEquatable<XmpElementBase>
```

Stellt das Basiselement XMP dar, das Attribute enthält.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Fügt das Attribut hinzu. |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | Liest das Attribut. |
| [clearAttributes()](#clearAttributes--) | Entfernt alle Attribute. |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.imaging.xmp.XmpElementBase-) | Gibt an, ob das aktuelle Objekt einem anderen Objekt desselben Typs gleich ist. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene `Object` gleich dieser Instanz ist. |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für diese Instanz zurück. |
### addAttribute(String attribute, String value) {#addAttribute-java.lang.String-java.lang.String-}
```
public void addAttribute(String attribute, String value)
```


Fügt das Attribut hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Attribut | java.lang.String | Das Attribut. |
| Wert | java.lang.String | Der Wert. |

### getAttribute(String attribute) {#getAttribute-java.lang.String-}
```
public String getAttribute(String attribute)
```


Liest das Attribut.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Attribut | java.lang.String | Das Attribut. |

**Returns:**
java.lang.String - Gibt das Attribut für den angegebenen Attributnamen zurück.
### clearAttributes() {#clearAttributes--}
```
public void clearAttributes()
```


Entfernt alle Attribute.

### isEquals(XmpElementBase other) {#isEquals-com.aspose.imaging.xmp.XmpElementBase-}
```
public boolean isEquals(XmpElementBase other)
```


Gibt an, ob das aktuelle Objekt einem anderen Objekt desselben Typs gleich ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | [XmpElementBase](../../com.aspose.imaging.xmp/xmpelementbase) | Ein Objekt zum Vergleich mit diesem Objekt. |

**Returns:**
boolean - true, wenn das aktuelle Objekt dem Parameter `other` entspricht; andernfalls false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob das angegebene `Object` gleich dieser Instanz ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das `Object` zum Vergleich mit dieser Instanz. |

**Returns:**
boolean - `true` wenn das angegebene `Object` dieser Instanz gleich ist; andernfalls `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für diese Instanz zurück.

**Returns:**
int – Ein Hashcode für diese Instanz, geeignet für den Einsatz in Hash‑Algorithmen und Datenstrukturen wie einer Hashtabelle.
