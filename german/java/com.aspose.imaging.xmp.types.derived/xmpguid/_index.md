---
title: "XmpGuid"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt die globale eindeutige XMP-Kennung dar."
type: docs
weight: 14
url: /de/java/com.aspose.imaging.xmp.types.derived/xmpguid/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class XmpGuid extends XmpTypeBase
```

Stellt die globale eindeutige XMP-Kennung dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XmpGuid(String value)](#XmpGuid-java.lang.String-) | Initialisiert eine neue Instanz der `XmpGuid`-Klasse. |
| [XmpGuid(UUID guid)](#XmpGuid-java.util.UUID-) | Initialisiert eine neue Instanz der `XmpGuid`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPrefix()](#getPrefix--) | Liest oder setzt das Präfix wie uuid. |
| [setPrefix(String value)](#setPrefix-java.lang.String-) | Liest oder setzt das Präfix wie uuid. |
| [getValue()](#getValue--) | Liest oder setzt den Wert. |
| [setValue(UUID value)](#setValue-java.util.UUID-) | Liest oder setzt den Wert. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Liest den enthaltenen Zeichenfolgenwert im XMP‑Format. |
### XmpGuid(String value) {#XmpGuid-java.lang.String-}
```
public XmpGuid(String value)
```


Initialisiert eine neue Instanz der `XmpGuid`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Der Wert. |

### XmpGuid(UUID guid) {#XmpGuid-java.util.UUID-}
```
public XmpGuid(UUID guid)
```


Initialisiert eine neue Instanz der `XmpGuid`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| guid | java.util.UUID | Der eindeutige Bezeichner. |

### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Liest oder setzt das Präfix wie uuid.

Wert: Das Präfix wie uuid.

**Returns:**
java.lang.String
### setPrefix(String value) {#setPrefix-java.lang.String-}
```
public void setPrefix(String value)
```


Liest oder setzt das Präfix wie uuid.

Wert: Das Präfix wie uuid.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getValue() {#getValue--}
```
public UUID getValue()
```


Liest oder setzt den Wert.

Wert: Der Wert.

**Returns:**
java.util.UUID
### setValue(UUID value) {#setValue-java.util.UUID-}
```
public void setValue(UUID value)
```


Liest oder setzt den Wert.

Wert: Der Wert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.UUID |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Liest den enthaltenen Zeichenfolgenwert im XMP‑Format.

**Returns:**
java.lang.String - Gibt den im String enthaltenen Wert im XMP-Format zurück.
