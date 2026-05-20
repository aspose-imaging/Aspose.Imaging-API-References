---
title: "XmpMeta"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt XMP-Meta dar."
type: docs
weight: 18
url: /de/java/com.aspose.imaging.xmp/xmpmeta/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpElementBase](../../com.aspose.imaging.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpMeta extends XmpElementBase implements IXmlValue, System.IEquatable<XmpElementBase>
```

Stellt xmp-Meta dar. Optional. Der Zweck dieses Elements besteht darin, XMP-Metadaten innerhalb von allgemeinem XML-Text zu identifizieren, der andere nicht-XMP-Verwendungen von RDF enthalten kann.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XmpMeta(String toolkitVersion)](#XmpMeta-java.lang.String-) | Initialisiert eine neue Instanz der `XmpMeta`-Klasse. |
| [XmpMeta()](#XmpMeta--) | Initialisiert eine neue Instanz der `XmpMeta`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAdobeXmpToolkit()](#getAdobeXmpToolkit--) | Liest oder setzt Adobe Xmp toolkit version. |
| [setAdobeXmpToolkit(String value)](#setAdobeXmpToolkit-java.lang.String-) | Liest oder setzt Adobe Xmp toolkit version. |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Fügt das Attribut hinzu. |
| [getXmlValue()](#getXmlValue--) | Konvertiert den XMP-Wert in die XML-Darstellung. |
| [isEquals(XmpMeta other)](#isEquals-com.aspose.imaging.xmp.XmpMeta-) | Gibt an, ob das aktuelle Objekt einem anderen Objekt desselben Typs gleich ist. |
| [equals(Object other)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene `System.Object` gleich dieser Instanz ist. |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für diese Instanz zurück. |
### XmpMeta(String toolkitVersion) {#XmpMeta-java.lang.String-}
```
public XmpMeta(String toolkitVersion)
```


Initialisiert eine neue Instanz der `XmpMeta`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| toolkitVersion | java.lang.String | Adobe XMP Toolkit-Version. |

### XmpMeta() {#XmpMeta--}
```
public XmpMeta()
```


Initialisiert eine neue Instanz der `XmpMeta`-Klasse.

### getAdobeXmpToolkit() {#getAdobeXmpToolkit--}
```
public String getAdobeXmpToolkit()
```


Liest oder setzt Adobe Xmp toolkit version.

**Returns:**
java.lang.String
### setAdobeXmpToolkit(String value) {#setAdobeXmpToolkit-java.lang.String-}
```
public void setAdobeXmpToolkit(String value)
```


Liest oder setzt Adobe Xmp toolkit version.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

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

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Konvertiert den XMP-Wert in die XML-Darstellung.

**Returns:**
java.lang.String - Gibt den XMP-Wert zurück, der in die XML-Darstellung konvertiert wurde.
### isEquals(XmpMeta other) {#isEquals-com.aspose.imaging.xmp.XmpMeta-}
```
public boolean isEquals(XmpMeta other)
```


Gibt an, ob das aktuelle Objekt einem anderen Objekt desselben Typs gleich ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | [XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) | Ein Objekt zum Vergleich mit diesem Objekt. |

**Returns:**
boolean - true, wenn das aktuelle Objekt dem Parameter `other` entspricht; andernfalls false.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Bestimmt, ob das angegebene `System.Object` gleich dieser Instanz ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| andere | java.lang.Object | Das `System.Object` zum Vergleich mit dieser Instanz. |

**Returns:**
boolean - `true`, wenn das angegebene `System.Object` dieser Instanz gleich ist; andernfalls `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für diese Instanz zurück.

**Returns:**
int – Ein Hashcode für diese Instanz, geeignet für den Einsatz in Hash‑Algorithmen und Datenstrukturen wie einer Hashtabelle.
