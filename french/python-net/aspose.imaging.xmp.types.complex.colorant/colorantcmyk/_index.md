---
title: "Classe ColorantCmyk"
type: docs
weight: 20
url: /fr/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/
---

**Summary:** Represents CMYK Colorant.

**Module:** [aspose.imaging.xmp.types.complex.colorant](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/)

**Full Name:** aspose.imaging.xmp.types.complex.colorant.ColorantCmyk

**Inheritance:** IXmpType, ColorantBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ColorantCmyk()](#ColorantCmyk__1) | Initialise une nouvelle instance de la classe [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/). |
| [ColorantCmyk(black, cyan, magenta, yellow)](#ColorantCmyk_black_cyan_magenta_yellow_2) | Initialise une nouvelle instance de la classe [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| COLOR_VALUE_MAX [static] | float | r | Valeur maximale de couleur dans le colorant CMYK. |
| COLOR_VALUE_MIN [static] | float | r | Valeur minimale de couleur dans le colorant CMYK. |
| black | float | r/w | Obtient ou définit la valeur du composant noir. |
| color_type | [ColorType](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colortype/) | r/w | Obtient ou définit le type de couleur. |
| cyan | float | r/w | Obtient ou définit la valeur du composant cyan. |
| magenta | float | r/w | Obtient ou définit la valeur du composant magenta. |
| mode | [ColorMode](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colormode/) | r | Obtient [ColorMode](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colormode/). |
| namespace_uri | string | r | Obtient l'URI de l'espace de noms par défaut. |
| prefix | string | r | Obtient le préfixe. |
| swatch_name | string | r/w | Obtient ou définit le nom de l'échantillon. |
| yellow | float | r/w | Obtient ou définit la valeur du composant jaune. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clone cette instance. |
| [get_xmp_representation()](#get_xmp_representation__2) | Obtient la valeur de chaîne contenue au format XMP. |


### Constructor: ColorantCmyk() {#ColorantCmyk__1}


```
 ColorantCmyk() 
```

Initialise une nouvelle instance de la classe [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/).

### Constructor: ColorantCmyk(black, cyan, magenta, yellow) {#ColorantCmyk_black_cyan_magenta_yellow_2}


```
 ColorantCmyk(black, cyan, magenta, yellow) 
```

Initialise une nouvelle instance de la classe [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| black | float | La valeur du composant noir. |
| cyan | float | La valeur du composant couleur cyan. |
| magenta | float | La valeur du composant magenta. |
| yellow | float | La valeur du composant jaune. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clone cette instance.

**Returns**

| Type | Description |
| :- | :- |
| System.Object | Un clone membre à membre. |


### Method: get_xmp_representation() {#get_xmp_representation__2}


```
 get_xmp_representation() 
```

Obtient la valeur de chaîne contenue au format XMP.

**Returns**

| Type | Description |
| :- | :- |
| string | Renvoie la valeur de chaîne contenue au format XMP. |


