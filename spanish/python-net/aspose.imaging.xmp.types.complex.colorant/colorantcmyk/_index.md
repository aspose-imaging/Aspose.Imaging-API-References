---
title: "Clase ColorantCmyk"
type: docs
weight: 20
url: /es/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/
---

**Summary:** Represents CMYK Colorant.

**Module:** [aspose.imaging.xmp.types.complex.colorant](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/)

**Full Name:** aspose.imaging.xmp.types.complex.colorant.ColorantCmyk

**Inheritance:** IXmpType, ColorantBase

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [ColorantCmyk()](#ColorantCmyk__1) | Inicializa una nueva instancia de la clase [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/). |
| [ColorantCmyk(black, cyan, magenta, yellow)](#ColorantCmyk_black_cyan_magenta_yellow_2) | Inicializa una nueva instancia de la clase [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| COLOR_VALUE_MAX [static] | float | r | Valor máximo de color en el colorante CMYK. |
| COLOR_VALUE_MIN [static] | float | r | Valor mínimo de color en el colorante CMYK. |
| negro | float | r/w | Obtiene o establece el valor del componente negro. |
| color_type | [ColorType](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colortype/) | r/w | Obtiene o establece el tipo de color. |
| cian | float | r/w | Obtiene o establece el valor del componente cian. |
| magenta | float | r/w | Obtiene o establece el valor del componente magenta. |
| mode | [ColorMode](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colormode/) | r | Obtiene [ColorMode](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colormode/). |
| namespace_uri | string | r | Obtiene el URI del espacio de nombres predeterminado. |
| prefix | string | r | Obtiene el prefijo. |
| swatch_name | string | r/w | Obtiene o establece el nombre de la muestra. |
| amarillo | float | r/w | Obtiene o establece el valor del componente amarillo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [clone()](#clone__1) | Clona esta instancia. |
| [get_xmp_representation()](#get_xmp_representation__2) | Obtiene el valor de cadena contenido en formato XMP. |


### Constructor: ColorantCmyk() {#ColorantCmyk__1}


```
 ColorantCmyk() 
```

Inicializa una nueva instancia de la clase [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/).

### Constructor: ColorantCmyk(black, cyan, magenta, yellow) {#ColorantCmyk_black_cyan_magenta_yellow_2}


```
 ColorantCmyk(black, cyan, magenta, yellow) 
```

Inicializa una nueva instancia de la clase [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| negro | float | El valor del componente negro. |
| cian | float | El valor del componente de color cian. |
| magenta | float | El valor del componente magenta. |
| amarillo | float | El valor del componente amarillo. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clona esta instancia.

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Object | Una clonación por miembros. |


### Method: get_xmp_representation() {#get_xmp_representation__2}


```
 get_xmp_representation() 
```

Obtiene el valor de cadena contenido en formato XMP.

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Devuelve el valor de cadena contenido en formato XMP. |


