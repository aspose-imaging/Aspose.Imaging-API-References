---
title: "Classe ColorantCmyk"
type: docs
weight: 20
url: /it/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/
---

**Summary:** Represents CMYK Colorant.

**Module:** [aspose.imaging.xmp.types.complex.colorant](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/)

**Full Name:** aspose.imaging.xmp.types.complex.colorant.ColorantCmyk

**Inheritance:** IXmpType, ColorantBase

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [ColorantCmyk()](#ColorantCmyk__1) | Inizializza una nuova istanza della classe [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/). |
| [ColorantCmyk(black, cyan, magenta, yellow)](#ColorantCmyk_black_cyan_magenta_yellow_2) | Inizializza una nuova istanza della classe [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| COLOR_VALUE_MAX [statico] | float | r | Valore massimo del colore nel colorante CMYK. |
| COLOR_VALUE_MIN [statico] | float | r | Valore minimo del colore nel colorante CMYK. |
| nero | float | r/w | Ottiene o imposta il valore del componente nero. |
| color_type | [ColorType](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colortype/) | r/w | Ottiene o imposta il tipo di colore. |
| ciano | float | r/w | Ottiene o imposta il valore del componente ciano. |
| magenta | float | r/w | Ottiene o imposta il valore del componente magenta. |
| mode | [ColorMode](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colormode/) | r | Ottiene [ColorMode](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colormode/). |
| namespace_uri | string | r | Ottiene l'URI dello spazio dei nomi predefinito. |
| prefix | string | r | Restituisce il prefisso. |
| swatch_name | string | r/w | Ottiene o imposta il nome del campione. |
| giallo | float | r/w | Ottiene o imposta il valore del componente giallo. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [clone()](#clone__1) | Clona questa istanza. |
| [get_xmp_representation()](#get_xmp_representation__2) | Ottiene il valore stringa contenuto nel formato XMP. |


### Constructor: ColorantCmyk() {#ColorantCmyk__1}


```
 ColorantCmyk() 
```

Inizializza una nuova istanza della classe [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/).

### Constructor: ColorantCmyk(black, cyan, magenta, yellow) {#ColorantCmyk_black_cyan_magenta_yellow_2}


```
 ColorantCmyk(black, cyan, magenta, yellow) 
```

Inizializza una nuova istanza della classe [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| nero | float | Il valore del componente nero. |
| ciano | float | Il valore del componente colore ciano. |
| magenta | float | Il valore del componente magenta. |
| giallo | float | Il valore del componente giallo. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clona questa istanza.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Object | Una clonazione a livello di membro. |


### Method: get_xmp_representation() {#get_xmp_representation__2}


```
 get_xmp_representation() 
```

Ottiene il valore stringa contenuto nel formato XMP.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Restituisce il valore stringa contenuto nel formato XMP. |


