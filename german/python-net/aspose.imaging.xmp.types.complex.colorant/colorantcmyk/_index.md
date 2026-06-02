---
title: "ColorantCmyk Klasse"
type: docs
weight: 20
url: /de/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/
---

**Summary:** Represents CMYK Colorant.

**Module:** [aspose.imaging.xmp.types.complex.colorant](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/)

**Full Name:** aspose.imaging.xmp.types.complex.colorant.ColorantCmyk

**Inheritance:** IXmpType, ColorantBase

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [ColorantCmyk()](#ColorantCmyk__1) | Initialisiert eine neue Instanz der Klasse [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/). |
| [ColorantCmyk(black, cyan, magenta, yellow)](#ColorantCmyk_black_cyan_magenta_yellow_2) | Initialisiert eine neue Instanz der Klasse [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| COLOR_VALUE_MAX [statisch] | float | r | Maximaler Farbwert im CMYK-Farbanteil. |
| COLOR_VALUE_MIN [statisch] | float | r | Minimaler Farbwert im CMYK-Farbanteil. |
| black | float | r/w | Liest oder setzt den Wert der schwarzen Komponente. |
| color_type | [ColorType](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colortype/) | r/w | Liest oder setzt den Typ der Farbe. |
| cyan | float | r/w | Liest oder setzt den Wert der Cyan‑Komponente. |
| magenta | float | r/w | Liest oder setzt den Wert der Magenta‑Komponente. |
| mode | [ColorMode](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colormode/) | r | Liest [ColorMode](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colormode/). |
| namespace_uri | string | r | Liest die Standard-Namespace-URI. |
| prefix | string | r | Gibt das Präfix zurück. |
| swatch_name | string | r/w | Liest oder setzt den Namen des Swatch. |
| yellow | float | r/w | Liest oder setzt den Wert der Gelb‑Komponente. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [clone()](#clone__1) | Klont diese Instanz. |
| [get_xmp_representation()](#get_xmp_representation__2) | Liefert den im XMP-Format enthaltenen Zeichenkettenwert. |


### Constructor: ColorantCmyk() {#ColorantCmyk__1}


```
 ColorantCmyk() 
```

Initialisiert eine neue Instanz der Klasse [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/).

### Constructor: ColorantCmyk(black, cyan, magenta, yellow) {#ColorantCmyk_black_cyan_magenta_yellow_2}


```
 ColorantCmyk(black, cyan, magenta, yellow) 
```

Initialisiert eine neue Instanz der Klasse [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| black | float | Der Schwarz-Komponentenwert. |
| cyan | float | Der Cyan‑Farbkomponentenwert. |
| magenta | float | Der Magenta-Komponentenwert. |
| yellow | float | Der Wert der gelben Komponente. |

### Method: clone() {#clone__1}


```
 clone() 
```

Klont diese Instanz.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Object | Ein Memberwise-Klon. |


### Method: get_xmp_representation() {#get_xmp_representation__2}


```
 get_xmp_representation() 
```

Liefert den im XMP-Format enthaltenen Zeichenkettenwert.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Gibt den im XMP-Format enthaltenen Zeichenkettenwert zurück. |


