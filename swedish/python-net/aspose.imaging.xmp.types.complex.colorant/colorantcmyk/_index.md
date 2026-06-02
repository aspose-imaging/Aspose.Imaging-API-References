---
title: "ColorantCmyk klass"
type: docs
weight: 20
url: /sv/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/
---

**Summary:** Represents CMYK Colorant.

**Module:** [aspose.imaging.xmp.types.complex.colorant](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/)

**Full Name:** aspose.imaging.xmp.types.complex.colorant.ColorantCmyk

**Inheritance:** IXmpType, ColorantBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ColorantCmyk()](#ColorantCmyk__1) | Initierar en ny instans av klassen [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/). |
| [ColorantCmyk(black, cyan, magenta, yellow)](#ColorantCmyk_black_cyan_magenta_yellow_2) | Initierar en ny instans av klassen [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| COLOR_VALUE_MAX [statisk] | float | r | Maximalt färgvärde i CMYK-färgämne. |
| COLOR_VALUE_MIN [statisk] | float | r | Minimalt färgvärde i CMYK-färgämne. |
| black | float | r/w | Hämtar eller anger värdet för svartkomponenten. |
| color_type | [ColorType](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colortype/) | r/w | Hämtar eller anger färgens typ. |
| cyan | float | r/w | Hämtar eller anger värdet för cyan-komponenten. |
| magenta | float | r/w | Hämtar eller anger värdet för magentakomponenten. |
| mode | [ColorMode](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colormode/) | r | Hämtar [ColorMode](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colormode/). |
| namespace_uri | string | r | Hämtar standard‑namnrymdens URI. |
| prefix | string | r | Hämtar prefixet. |
| swatch_name | string | r/w | Hämtar eller anger namn på färgprovet. |
| yellow | float | r/w | Hämtar eller anger värdet för gulkomponenten. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Klonar den här instansen. |
| [get_xmp_representation()](#get_xmp_representation__2) | Hämtar det strängvärde som finns i XMP-format. |


### Constructor: ColorantCmyk() {#ColorantCmyk__1}


```
 ColorantCmyk() 
```

Initierar en ny instans av klassen [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/).

### Constructor: ColorantCmyk(black, cyan, magenta, yellow) {#ColorantCmyk_black_cyan_magenta_yellow_2}


```
 ColorantCmyk(black, cyan, magenta, yellow) 
```

Initierar en ny instans av klassen [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| black | float | Svart-komponentvärdet. |
| cyan | float | Värdet för cyan-färgkomponenten. |
| magenta | float | Magenta-komponentvärdet. |
| yellow | float | Det gula komponentvärdet. |

### Method: clone() {#clone__1}


```
 clone() 
```

Klonar den här instansen.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Object | En medlemsklon. |


### Method: get_xmp_representation() {#get_xmp_representation__2}


```
 get_xmp_representation() 
```

Hämtar det strängvärde som finns i XMP-format.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Returnerar det strängvärde som finns i XMP-format. |


