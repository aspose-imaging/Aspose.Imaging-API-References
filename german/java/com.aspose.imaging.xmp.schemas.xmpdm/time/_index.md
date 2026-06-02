---
title: "Time"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Darstellung eines Zeitwerts in Sekunden."
type: docs
weight: 14
url: /de/java/com.aspose.imaging.xmp.schemas.xmpdm/time/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class Time extends XmpTypeBase
```

Darstellung eines Zeitwerts in Sekunden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Time(Rational scale, int value)](#Time-com.aspose.imaging.xmp.types.derived.Rational-int-) | Initialisiert eine neue Instanz der `Time`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getScale()](#getScale--) | Liest oder setzt die Skalierung für den Zeitwert. |
| [setScale(Rational value)](#setScale-com.aspose.imaging.xmp.types.derived.Rational-) | Liest oder setzt die Skalierung für den Zeitwert. |
| [getValue()](#getValue--) | Liest oder setzt den Zeitwert in der angegebenen Skala. |
| [setValue(int value)](#setValue-int-) | Liest oder setzt den Zeitwert in der angegebenen Skala. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Liest den enthaltenen Zeichenfolgenwert im XMP‑Format. |
### Time(Rational scale, int value) {#Time-com.aspose.imaging.xmp.types.derived.Rational-int-}
```
public Time(Rational scale, int value)
```


Initialisiert eine neue Instanz der `Time`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scale | [Rational](../../com.aspose.imaging.xmp.types.derived/rational) | Die Skala. |
| Wert | int | Der Wert. |

### getScale() {#getScale--}
```
public Rational getScale()
```


Liest oder setzt die Skalierung für den Zeitwert.

Für NTSC verwenden Sie 1001/30000 oder die weniger genaue 100/2997. Für PAL verwenden Sie 1/25. Wert: Die Skala für den Zeitwert.

**Returns:**
[Rational](../../com.aspose.imaging.xmp.types.derived/rational)
### setScale(Rational value) {#setScale-com.aspose.imaging.xmp.types.derived.Rational-}
```
public void setScale(Rational value)
```


Liest oder setzt die Skalierung für den Zeitwert.

Für NTSC verwenden Sie 1001/30000 oder die weniger genaue 100/2997. Für PAL verwenden Sie 1/25. Wert: Die Skala für den Zeitwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rational](../../com.aspose.imaging.xmp.types.derived/rational) |  |

### getValue() {#getValue--}
```
public int getValue()
```


Liest oder setzt den Zeitwert in der angegebenen Skala.

Wert: Der Zeitwert in der angegebenen Skala.

**Returns:**
int
### setValue(int value) {#setValue-int-}
```
public void setValue(int value)
```


Liest oder setzt den Zeitwert in der angegebenen Skala.

Wert: Der Zeitwert in der angegebenen Skala.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Liest den enthaltenen Zeichenfolgenwert im XMP‑Format.

**Returns:**
java.lang.String - Gibt den im String enthaltenen Wert im XMP-Format zurück.
