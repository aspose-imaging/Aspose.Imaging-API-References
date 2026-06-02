---
title: "Classe PathMulticolorGradientBrush"
type: docs
weight: 70
url: /fr/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/
---

**Summary:** Encapsulates a [Brush](/imaging/python-net/aspose.imaging/brush/) object with a gradient. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.PathMulticolorGradientBrush

**Inheritance:** PathGradientBrushBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PathMulticolorGradientBrush(path)](#PathMulticolorGradientBrush_path_1) | Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) avec les points spécifiés. |
| [PathMulticolorGradientBrush(path_points)](#PathMulticolorGradientBrush_path_points_2) | Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) avec les points spécifiés. |
| [PathMulticolorGradientBrush(path_points)](#PathMulticolorGradientBrush_path_points_3) | Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) avec les points spécifiés. |
| [PathMulticolorGradientBrush(path_points, wrap_mode)](#PathMulticolorGradientBrush_path_points_wrap_mode_4) | Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) avec les points spécifiés et le mode d'enroulement. |
| [PathMulticolorGradientBrush(path_points, wrap_mode)](#PathMulticolorGradientBrush_path_points_wrap_mode_5) | Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) avec les points spécifiés et le mode d'enroulement. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| center_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtient ou définit le point central du dégradé de chemin. |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| focus_scales | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtient ou définit le point de focalisation pour la chute du dégradé. |
| graphics_path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | r | Obtient le chemin graphique sur lequel ce pinceau a été construit. |
| interpolation_colors | [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | r/w | Obtient ou définit un [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) qui définit un dégradé linéaire multicolore. |
| is_transform_changed | bool | r | Obtient une valeur indiquant si les transformations ont été modifiées d'une manière ou d'une autre. Par exemple en définissant la matrice de transformation ou<br/>            en appelant l'une des méthodes modifiant la matrice de transformation. La propriété est introduite pour la compatibilité descendante avec GDI+. |
| opacity | float | r/w | Obtient ou définit l'opacité du pinceau. La valeur doit être comprise entre 0 et 1. Une valeur de 0 signifie que le pinceau est totalement visible, une valeur de 1 signifie que le pinceau est totalement opaque. |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r | Obtient les points du chemin sur lequel ce pinceau a été construit. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtient ou définit une copie de la [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui définit une transformation géométrique locale pour ce [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | Obtient ou définit une énumération [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) qui indique le mode d'habillage pour ce [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_path(path)](#create_with_path_path_1) | Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) avec le chemin spécifié. |
| [create_with_points(path_points)](#create_with_points_path_points_2) | Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) avec les points spécifiés. |
| [create_with_points_f(path_points)](#create_with_points_f_path_points_3) | Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) avec les points spécifiés. |
| [create_with_points_f_wrap_mode(path_points, wrap_mode)](#create_with_points_f_wrap_mode_path_points_wrap_mode_4) | Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) avec les points spécifiés et le mode d'enroulement. |
| [create_with_points_wrap_mode(path_points, wrap_mode)](#create_with_points_wrap_mode_path_points_wrap_mode_5) | Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) avec les points spécifiés et le mode d'enroulement. |
| [deep_clone()](#deep_clone__6) | Crée un nouveau clone profond du [Brush](/imaging/python-net/aspose.imaging/brush/) actuel. |
| [multiply_transform(matrix)](#multiply_transform_matrix_7) | Multiplie la [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui représente la transformation géométrique locale de ce [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) par la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée en préfixant la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_8) | Multiplie la [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui représente la transformation géométrique locale de ce [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) par la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée dans l'ordre indiqué. |
| reset_transform() | Réinitialise la propriété [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) à l'identité. |
| [rotate_transform(angle)](#rotate_transform_angle_9) | Fait pivoter la transformation géométrique locale de la valeur spécifiée. Cette méthode préfixe la rotation à la transformation. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_10) | Fait pivoter la transformation géométrique locale de la valeur spécifiée dans l'ordre indiqué. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_11) | Redimensionne la transformation géométrique locale par les valeurs spécifiées. Cette méthode préfixe la matrice d'échelle à la transformation. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_12) | Redimensionne la transformation géométrique locale par les valeurs spécifiées dans l'ordre indiqué. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_13) | Transalte la transformation géométrique locale des dimensions spécifiées. Cette méthode préfixe la translation à la transformation. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_14) | Transalte la transformation géométrique locale des dimensions spécifiées dans l'ordre indiqué. |


### Constructor: PathMulticolorGradientBrush(path) {#PathMulticolorGradientBrush_path_1}


```
 PathMulticolorGradientBrush(path) 
```

Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) avec les points spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) |  |

### Constructor: PathMulticolorGradientBrush(path_points) {#PathMulticolorGradientBrush_path_points_2}


```
 PathMulticolorGradientBrush(path_points) 
```

Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) avec les points spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représente les points constituant les sommets du chemin. |

### Constructor: PathMulticolorGradientBrush(path_points) {#PathMulticolorGradientBrush_path_points_3}


```
 PathMulticolorGradientBrush(path_points) 
```

Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) avec les points spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représente les points constituant les sommets du chemin. |

### Constructor: PathMulticolorGradientBrush(path_points, wrap_mode) {#PathMulticolorGradientBrush_path_points_wrap_mode_4}


```
 PathMulticolorGradientBrush(path_points, wrap_mode) 
```

Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) avec les points spécifiés et le mode d'enroulement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représente les points constituant les sommets du chemin. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Un [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) qui spécifie comment les remplissages dessinés avec ce [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) sont mosaïqués. |

### Constructor: PathMulticolorGradientBrush(path_points, wrap_mode) {#PathMulticolorGradientBrush_path_points_wrap_mode_5}


```
 PathMulticolorGradientBrush(path_points, wrap_mode) 
```

Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) avec les points spécifiés et le mode d'enroulement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représente les points constituant les sommets du chemin. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Un [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) qui spécifie comment les remplissages dessinés avec ce [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) sont mosaïqués. |

### Method: create_with_path(path)  [static] {#create_with_path_path_1}


```
 create_with_path(path) 
```

Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) avec le chemin spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Le [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) qui définit la zone remplie par ce [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/). |

**Returns**

| Type | Description |
| :- | :- |
| [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) |  |


### Method: create_with_points(path_points)  [static] {#create_with_points_path_points_2}


```
 create_with_points(path_points) 
```

Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) avec les points spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représente les points constituant les sommets du chemin. |

**Returns**

| Type | Description |
| :- | :- |
| [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) |  |


### Method: create_with_points_f(path_points)  [static] {#create_with_points_f_path_points_3}


```
 create_with_points_f(path_points) 
```

Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) avec les points spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Un tableau de structures [Point](/imaging/python-net/aspose.imaging/point/) qui représente les points constituant les sommets du chemin. |

**Returns**

| Type | Description |
| :- | :- |
| [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) |  |


### Method: create_with_points_f_wrap_mode(path_points, wrap_mode)  [static] {#create_with_points_f_wrap_mode_path_points_wrap_mode_4}


```
 create_with_points_f_wrap_mode(path_points, wrap_mode) 
```

Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) avec les points spécifiés et le mode d'enroulement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Un tableau de structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représente les points constituant les sommets du chemin. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Un [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) qui spécifie comment les remplissages dessinés avec ce [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) sont mosaïqués. |

**Returns**

| Type | Description |
| :- | :- |
| [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) |  |


### Method: create_with_points_wrap_mode(path_points, wrap_mode)  [static] {#create_with_points_wrap_mode_path_points_wrap_mode_5}


```
 create_with_points_wrap_mode(path_points, wrap_mode) 
```

Initialise une nouvelle instance de la classe [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) avec les points spécifiés et le mode d'enroulement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | Un tableau de structures [Point](/imaging/python-net/aspose.imaging/point/) qui représente les points constituant les sommets du chemin. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Un [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) qui spécifie comment les remplissages dessinés avec ce [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) sont mosaïqués. |

**Returns**

| Type | Description |
| :- | :- |
| [PathMulticolorGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathmulticolorgradientbrush/) |  |


### Method: deep_clone() {#deep_clone__6}


```
 deep_clone() 
```

Crée un nouveau clone profond du [Brush](/imaging/python-net/aspose.imaging/brush/) actuel.

**Returns**

| Type | Description |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | Un nouveau [Brush](/imaging/python-net/aspose.imaging/brush/) qui est le clone profond de cette instance [Brush](/imaging/python-net/aspose.imaging/brush/). |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_7}


```
 multiply_transform(matrix) 
```

Multiplie la [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui représente la transformation géométrique locale de ce [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) par la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée en préfixant la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) par laquelle multiplier la transformation géométrique. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_8}


```
 multiply_transform(matrix, order) 
```

Multiplie la [Matrix](/imaging/python-net/aspose.imaging/matrix/) qui représente la transformation géométrique locale de ce [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) par la [Matrix](/imaging/python-net/aspose.imaging/matrix/) spécifiée dans l'ordre indiqué.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La [Matrix](/imaging/python-net/aspose.imaging/matrix/) par laquelle multiplier la transformation géométrique. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) qui spécifie dans quel ordre multiplier les deux matrices. |

### Method: rotate_transform(angle) {#rotate_transform_angle_9}


```
 rotate_transform(angle) 
```

Fait pivoter la transformation géométrique locale de la valeur spécifiée. Cette méthode préfixe la rotation à la transformation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle de rotation. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_10}


```
 rotate_transform(angle, order) 
```

Fait pivoter la transformation géométrique locale de la valeur spécifiée dans l'ordre indiqué.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle de rotation. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) qui spécifie s'il faut ajouter ou préfixer la matrice de rotation. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_11}


```
 scale_transform(sx, sy) 
```

Redimensionne la transformation géométrique locale par les valeurs spécifiées. Cette méthode préfixe la matrice d'échelle à la transformation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| sx | float | La valeur par laquelle redimensionner la transformation selon l'axe x. |
| sy | float | La valeur par laquelle redimensionner la transformation selon l'axe y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_12}


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

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_13}


```
 translate_transform(dx, dy) 
```

Transalte la transformation géométrique locale des dimensions spécifiées. Cette méthode préfixe la translation à la transformation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dx | float | La valeur de la translation en x. |
| dy | float | La valeur de la translation en y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_14}


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

