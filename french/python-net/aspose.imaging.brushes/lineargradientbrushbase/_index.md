---
title: "Classe LinearGradientBrushBase"
type: docs
weight: 30
url: /fr/python-net/aspose.imaging.brushes/lineargradientbrushbase/
---

**Summary:** Represents a [Brush](/imaging/python-net/aspose.imaging/brush/) with gradient capabilities and appropriate properties.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.LinearGradientBrushBase

**Inheritance:** TransformBrush

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| angle | float | r/w | Obtient ou définit l'angle du dégradé. |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| gamma_correction | bool | r/w | Obtient ou définit une valeur indiquant si la correction gamma est activée pour ce [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/). |
| is_angle_scalable | bool | r/w | Obtient ou définit une valeur indiquant si [LinearGradientBrushBase.angle](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/) est modifié lors des transformations avec ce [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/). |
| is_transform_changed | bool | r | Obtient une valeur indiquant si les transformations ont été modifiées d'une manière ou d'une autre. Par exemple en définissant la matrice de transformation ou<br/>            en appelant l'une des méthodes modifiant la matrice de transformation. La propriété est introduite pour la compatibilité descendante avec GDI+. |
| opacity | float | r/w | Obtient ou définit l'opacité du pinceau. La valeur doit être comprise entre 0 et 1. Une valeur de 0 signifie que le pinceau est totalement visible, une valeur de 1 signifie que le pinceau est totalement opaque. |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Obtient ou définit une région rectangulaire qui définit les points de départ et d'arrivée du dégradé. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtient ou définit une copie de la [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui définit une transformation géométrique locale pour ce [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | Obtient ou définit une énumération [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) qui indique le mode d'habillage pour ce [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Crée un nouveau clone profond du [Brush](/imaging/python-net/aspose.imaging/brush/) actuel. |
| [multiply_transform(matrix)](#multiply_transform_matrix_2) | Multiplie la [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui représente la transformation géométrique locale de ce [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) par la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée en préfixant la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_3) | Multiplie la [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui représente la transformation géométrique locale de ce [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) par la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée dans l'ordre indiqué. |
| reset_transform() | Réinitialise la propriété [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) à l'identité. |
| [rotate_transform(angle)](#rotate_transform_angle_4) | Fait pivoter la transformation géométrique locale de la valeur spécifiée. Cette méthode préfixe la rotation à la transformation. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_5) | Fait pivoter la transformation géométrique locale de la valeur spécifiée dans l'ordre indiqué. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_6) | Redimensionne la transformation géométrique locale par les valeurs spécifiées. Cette méthode préfixe la matrice d'échelle à la transformation. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_7) | Redimensionne la transformation géométrique locale par les valeurs spécifiées dans l'ordre indiqué. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | Transalte la transformation géométrique locale des dimensions spécifiées. Cette méthode préfixe la translation à la transformation. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | Transalte la transformation géométrique locale des dimensions spécifiées dans l'ordre indiqué. |


### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Crée un nouveau clone profond du [Brush](/imaging/python-net/aspose.imaging/brush/) actuel.

**Returns**

| Type | Description |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | Un nouveau [Brush](/imaging/python-net/aspose.imaging/brush/) qui est le clone profond de cette instance [Brush](/imaging/python-net/aspose.imaging/brush/). |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_2}


```
 multiply_transform(matrix) 
```

Multiplie la [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui représente la transformation géométrique locale de ce [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) par la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée en préfixant la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) par laquelle multiplier la transformation géométrique. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_3}


```
 multiply_transform(matrix, order) 
```

Multiplie la [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui représente la transformation géométrique locale de ce [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) par la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée dans l'ordre indiqué.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) par laquelle multiplier la transformation géométrique. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) qui spécifie dans quel ordre multiplier les deux matrices. |

### Method: rotate_transform(angle) {#rotate_transform_angle_4}


```
 rotate_transform(angle) 
```

Fait pivoter la transformation géométrique locale de la valeur spécifiée. Cette méthode préfixe la rotation à la transformation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle de rotation. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_5}


```
 rotate_transform(angle, order) 
```

Fait pivoter la transformation géométrique locale de la valeur spécifiée dans l'ordre indiqué.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle de rotation. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) qui spécifie s'il faut ajouter ou préfixer la matrice de rotation. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_6}


```
 scale_transform(sx, sy) 
```

Redimensionne la transformation géométrique locale par les valeurs spécifiées. Cette méthode préfixe la matrice d'échelle à la transformation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| sx | float | La valeur par laquelle redimensionner la transformation selon l'axe x. |
| sy | float | La valeur par laquelle redimensionner la transformation selon l'axe y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_7}


```
 scale_transform(sx, sy, order) 
```

Redimensionne la transformation géométrique locale par les valeurs spécifiées dans l'ordre indiqué.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| sx | float | La valeur par laquelle redimensionner la transformation selon l'axe x. |
| sy | float | La valeur par laquelle redimensionner la transformation selon l'axe y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) qui spécifie s'il faut ajouter ou préfixer la matrice d'échelle. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

Transalte la transformation géométrique locale des dimensions spécifiées. Cette méthode préfixe la translation à la transformation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dx | float | La valeur de la translation en x. |
| dy | float | La valeur de la translation en y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


```
 translate_transform(dx, dy, order) 
```

Transalte la transformation géométrique locale des dimensions spécifiées dans l'ordre indiqué.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dx | float | La valeur de la translation en x. |
| dy | float | La valeur de la translation en y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | L'ordre (préfixer ou ajouter) dans lequel appliquer la translation. |

