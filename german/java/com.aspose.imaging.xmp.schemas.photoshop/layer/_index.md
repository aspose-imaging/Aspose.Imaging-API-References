---
title: "Ebene"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt die Photoshop-Textebene dar."
type: docs
weight: 11
url: /de/java/com.aspose.imaging.xmp.schemas.photoshop/layer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public class Layer extends XmpTypeBase implements System.IEquatable<Layer>
```

Stellt die Photoshop-Textebene dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Layer(String layerName, String layerText)](#Layer-java.lang.String-java.lang.String-) | Initialisiert eine neue Instanz der `Layer` Klasse. |
| [Layer()](#Layer--) | Initialisiert eine neue Instanz der `Layer` Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getName()](#getName--) | Liest oder setzt den Namen der Textebene. |
| [setName(String value)](#setName-java.lang.String-) | Liest oder setzt den Namen der Textebene. |
| [getText()](#getText--) | Liest oder setzt den Textinhalt der Ebene. |
| [setText(String value)](#setText-java.lang.String-) | Liest oder setzt den Textinhalt der Ebene. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Gibt den enthaltenen Zeichenkettenwert im XMP-Format zurück. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene `System.Object` gleich dieser Instanz ist. |
| [isEquals(Layer other)](#isEquals-com.aspose.imaging.xmp.schemas.photoshop.Layer-) | Gibt an, ob das aktuelle Objekt einem anderen Objekt desselben Typs gleich ist. |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für diese Instanz zurück. |
### Layer(String layerName, String layerText) {#Layer-java.lang.String-java.lang.String-}
```
public Layer(String layerName, String layerText)
```


Initialisiert eine neue Instanz der `Layer` Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| layerName | java.lang.String | Name der Ebene. |
| layerText | java.lang.String | Der Ebenentext. |

### Layer() {#Layer--}
```
public Layer()
```


Initialisiert eine neue Instanz der `Layer` Klasse.

### getName() {#getName--}
```
public String getName()
```


Liest oder setzt den Namen der Textebene.

Wert: Der Name der Textebene.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Liest oder setzt den Namen der Textebene.

Wert: Der Name der Textebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getText() {#getText--}
```
public String getText()
```


Liest oder setzt den Textinhalt der Ebene.

Wert: Der Textinhalt der Ebene.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Liest oder setzt den Textinhalt der Ebene.

Wert: Der Textinhalt der Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Gibt den enthaltenen Zeichenkettenwert im XMP-Format zurück.

**Returns:**
java.lang.String - Gibt den enthaltenen Zeichenkettenwert im XMP-Format zurück.
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
### isEquals(Layer other) {#isEquals-com.aspose.imaging.xmp.schemas.photoshop.Layer-}
```
public boolean isEquals(Layer other)
```


Gibt an, ob das aktuelle Objekt einem anderen Objekt desselben Typs gleich ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | [Layer](../../com.aspose.imaging.xmp.schemas.photoshop/layer) | Ein Objekt zum Vergleich mit diesem Objekt. |

**Returns:**
boolean - true, wenn das aktuelle Objekt dem Parameter `other` entspricht; andernfalls false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für diese Instanz zurück.

**Returns:**
int – Ein Hashcode für diese Instanz, geeignet für den Einsatz in Hash‑Algorithmen und Datenstrukturen wie einer Hashtabelle.
