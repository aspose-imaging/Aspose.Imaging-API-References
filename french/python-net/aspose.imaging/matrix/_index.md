---
title: "Classe Matrix"
type: docs
weight: 6070
url: /fr/python-net/aspose.imaging/matrix/
---

**Summary:** Replaces the GDI+ Matrix.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Matrix

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Matrix()](#Matrix__1) | Initialise une nouvelle instance de la classe Matrix en tant que matrice identité. |
| [Matrix(m11, m12, m21, m22, m31, m32)](#Matrix_m11_m12_m21_m22_m31_m32_2) | Initialise une nouvelle instance de la classe [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [Matrix(origin)](#Matrix_origin_3) | Crée une copie de la classe [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_4) | Initialise une nouvelle instance de la classe [Matrix](/imaging/python-net/aspose.imaging/matrix/) pour la transformation géométrique définie par le rectangle spécifié et le tableau de points. |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_5) | Initialise une nouvelle instance de la classe [Matrix](/imaging/python-net/aspose.imaging/matrix/) pour la transformation géométrique définie par le rectangle spécifié et le tableau de points. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| TYPE_FLIP [static] | int | r | Ce bit de drapeau indique que la transformation définie par cet objet<br/>            effectue un retournement en miroir autour d'un axe qui transforme le<br/>            système de coordonnées normalement droitier en un système gaucher<br/>            en plus des conversions indiquées par les autres bits de drapeau.<br/>            Un système de coordonnées droitier est celui où l'axe X positif<br/>            tourne dans le sens antihoraire pour se superposer à l'axe Y positif<br/>            similaire à la direction dans laquelle les doigts de votre main droite<br/>            se courbent lorsque vous regardez votre pouce de face.<br/>            Un système de coordonnées gaucher est celui où l'axe X positif<br/>            tourne dans le sens horaire pour se superposer à l'axe Y positif similaire<br/>            à la direction dans laquelle les doigts de votre main gauche se courbent.<br/>            Il n'existe aucun moyen mathématique de déterminer l'angle de la<br/>            transformation de retournement ou de miroir d'origine puisque tous les angles<br/>            de retournement sont identiques avec une rotation d'ajustement appropriée.<br/>            NOTE : TypeFlip a été ajouté après que GENERAL_TRANSFORM était en diffusion publique<br/>            et les bits de drapeau ne pouvaient plus être renumérotés commodément<br/>            sans introduire d'incompatibilité binaire dans le code externe. |
| TYPE_GENERAL_ROTATION [static] | int | r | Ce bit de drapeau indique que la transformation définie par cet objet<br/>            effectue une rotation d'un angle arbitraire en plus des<br/>            conversions indiquées par les autres bits de drapeau.<br/>            Une rotation modifie les angles des vecteurs du même montant<br/>            quel que soit le sens d'origine du vecteur et sans<br/>            changer la longueur du vecteur.<br/>            Ce bit de drapeau est mutuellement exclusif avec le |
| TYPE_GENERAL_SCALE [static] | int | r | Une mise à l'échelle générale multiplie la longueur des vecteurs par des valeurs différentes<br/>            dans les directions x et y sans changer l'angle<br/>            entre les vecteurs perpendiculaires.<br/>            Ce bit de drapeau est mutuellement exclusif avec le drapeau TypeUniformScale. |
| TYPE_GENERAL_TRANSFORM [static] | int | r | Cette constante indique que la transformation définie par cet objet<br/>            effectue une conversion arbitraire des coordonnées d'entrée.<br/>            Si cette transformation peut être classée par l'une des constantes ci‑dessus,<br/>            le type sera soit la constante TypeIdentity soit une<br/>            combinaison des bits de drapeau appropriés pour les diverses conversions de coordonnées<br/>            que cette transformation effectue. |
| TYPE_IDENTITY [static] | int | r | Une transformation identité est celle dans laquelle les coordonnées de sortie sont<br/>            toujours les mêmes que les coordonnées d'entrée.<br/>            Si cette transformation n'est pas la transformation identité,<br/>            le type sera soit la constante GENERAL_TRANSFORM soit une<br/>            combinaison des bits de drapeau appropriés pour les diverses conversions de coordonnées<br/>            que cette transformation effectue. |
| TYPE_MASK_ROTATION [static] | int | r | Cette constante est un masque de bits pour n'importe lequel des bits de drapeau de rotation. |
| TYPE_MASK_SCALE [static] | int | r | Cette constante est un masque de bits pour n'importe lequel des bits de drapeau d'échelle. |
| TYPE_QUADRANT_ROTATION [static] | int | r | Ce bit de drapeau indique que la transformation définie par cet objet<br/>            effectue une rotation de quadrant par un multiple de 90 degrés en<br/>            plus des conversions indiquées par les autres bits de drapeau.<br/>            Une rotation modifie les angles des vecteurs du même montant<br/>            quel que soit le sens d'origine du vecteur et sans<br/>            changer la longueur du vecteur.<br/>            Ce bit de drapeau est mutuellement exclusif avec le drapeau TypeGeneralRotation. |
| TYPE_TRANSLATION [static] | int | r | Une translation déplace les coordonnées d'une quantité constante en x<br/>            et y sans changer la longueur ou l'angle des vecteurs. |
| TYPE_UNIFORM_SCALE [static] | int | r | Une mise à l'échelle uniforme multiplie la longueur des vecteurs du même montant<br/>            dans les directions x et y sans changer l'angle entre<br/> vecteurs. |
| elements | float[] | r | Obtient un tableau de valeurs à virgule flottante qui représente les éléments de ce [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| m11 | float | r | Obtient l'élément de matrice à la première ligne première colonne. Représente l'échelle le long de l'axe X. |
| m12 | float | r | Obtient l'élément de matrice à la première ligne deuxième colonne. Représente le cisaillement le long de l'axe Y. |
| m21 | float | r | Obtient l'élément de la matrice à la deuxième ligne première colonne. Représente le cisaillement le long de l'axe X. |
| m22 | float | r | Obtient l'élément de la matrice à la deuxième ligne deuxième colonne. Représente l'échelle le long de l'axe Y. |
| m31 | float | r | Obtient l'élément de la matrice à la troisième ligne première colonne. Représente la translation le long de l'axe X. |
| m32 | float | r | Obtient l'élément de la matrice à la troisième ligne première colonne. Représente la translation le long de l'axe Y. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_rect(rect, plgpts)](#create_with_rect_rect_plgpts_1) | Initialise une nouvelle instance de la classe [Matrix](/imaging/python-net/aspose.imaging/matrix/) pour la transformation géométrique définie par le rectangle spécifié et le tableau de points. |
| [create_with_rect_f(rect, plgpts)](#create_with_rect_f_rect_plgpts_2) | Initialise une nouvelle instance de la classe [Matrix](/imaging/python-net/aspose.imaging/matrix/) pour la transformation géométrique définie par le rectangle spécifié et le tableau de points. |
| [get_elements()](#get_elements__3) | Obtient une copie des éléments de la matrice. |
| [multiply(t_tx)](#multiply_t_tx_4) | Multiplie cette Matrix par la matrice spécifiée dans le paramètre matrix en utilisant l'ordre (par défaut) Prepend. |
| [multiply(t_tx, order)](#multiply_t_tx_order_5) | Multiplie cette Matrix par la matrice spécifiée dans le paramètre matrix, et dans l'ordre spécifié dans le paramètre order. |
| reset() | Réinitialise cette Matrix pour qu'elle contienne les éléments de la matrice identité. |
| [rotate(angle)](#rotate_angle_6) | Applique une rotation horaire d'une valeur spécifiée dans le paramètre angle, autour de l'origine (coordonnées x et y nulles) pour cette Matrix dans l'ordre par défaut (Prepend). |
| [rotate(angle, order)](#rotate_angle_order_7) | Applique une rotation horaire d'une valeur spécifiée dans le paramètre angle, autour de l'origine (coordonnées x et y nulles) pour cette Matrix dans l'ordre spécifié. |
| [rotate_at(angle, point)](#rotate_at_angle_point_8) | Applique une rotation horaire autour du point spécifié à cette Matrix dans l'ordre par défaut (Prepend). |
| [rotate_at(angle, point, order)](#rotate_at_angle_point_order_9) | Applique une rotation horaire autour du point spécifié à cette Matrix dans l'ordre spécifié. |
| [scale(scale_x, scale_y, order)](#scale_scale_x_scale_y_order_10) | Applique le vecteur d'échelle spécifié (scaleX et scaleY) à cette [Matrix](/imaging/python-net/aspose.imaging/matrix/) en utilisant l'ordre spécifié. |
| [scale(sx, sy)](#scale_sx_sy_11) | Applique le vecteur d'échelle spécifié (scaleX et scaleY) à cette Matrix en utilisant l'ordre (par défaut) Prepend. |
| [transform_points(points)](#transform_points_points_12) | Applique la transformation géométrique représentée par cette [Matrix](/imaging/python-net/aspose.imaging/matrix/) à un tableau de points spécifié. |
| [translate(offset_x, offset_y, order)](#translate_offset_x_offset_y_order_13) | Applique le vecteur de translation spécifié à cette Matrix dans l'ordre spécifié. |
| [translate(tx, ty)](#translate_tx_ty_14) | Applique le vecteur de translation spécifié à cette [Matrix](/imaging/python-net/aspose.imaging/matrix/) en utilisant l'ordre (par défaut) Prepend. |


### Constructor: Matrix() {#Matrix__1}


```
 Matrix() 
```

Initialise une nouvelle instance de la classe Matrix en tant que matrice identité.

### Constructor: Matrix(m11, m12, m21, m22, m31, m32) {#Matrix_m11_m12_m21_m22_m31_m32_2}


```
 Matrix(m11, m12, m21, m22, m31, m32) 
```

Initialise une nouvelle instance de la classe [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| m11 | float | m00     M11     Échelle X |
| m12 | float | m10     M12     Cisaillement Y |
| m21 | float | m01     M21     Cisaillement X |
| m22 | float | m11     M22     Échelle Y |
| m31 | float | m02     M31     Translation X |
| m32 | float | m12     M32     Translation Y |

### Constructor: Matrix(origin) {#Matrix_origin_3}


```
 Matrix(origin) 
```

Crée une copie de la classe [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| origin | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Une matrice de base pour la copie |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_4}


```
 Matrix(rect, plgpts) 
```

Initialise une nouvelle instance de la classe [Matrix](/imaging/python-net/aspose.imaging/matrix/) pour la transformation géométrique définie par le rectangle spécifié et le tableau de points.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui représente le rectangle à transformer. |
| plgpts | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Un tableau de trois structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représente les points d'un parallélogramme vers lequel les coins supérieur-gauche, supérieur-droit et inférieur-gauche du rectangle doivent être transformés. Le coin inférieur-droit du parallélogramme est implicite à partir des trois premiers coins. |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_5}


```
 Matrix(rect, plgpts) 
```

Initialise une nouvelle instance de la classe [Matrix](/imaging/python-net/aspose.imaging/matrix/) pour la transformation géométrique définie par le rectangle spécifié et le tableau de points.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui représente le rectangle à transformer. |
| plgpts | [Point[]](/imaging/python-net/aspose.imaging/point/) | Un tableau de trois structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représente les points d'un parallélogramme vers lequel les coins supérieur-gauche, supérieur-droit et inférieur-gauche du rectangle doivent être transformés. Le coin inférieur-droit du parallélogramme est implicite à partir des trois premiers coins. |

### Method: create_with_rect(rect, plgpts)  [static] {#create_with_rect_rect_plgpts_1}


```
 create_with_rect(rect, plgpts) 
```

Initialise une nouvelle instance de la classe [Matrix](/imaging/python-net/aspose.imaging/matrix/) pour la transformation géométrique définie par le rectangle spécifié et le tableau de points.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui représente le rectangle à transformer. |
| plgpts | [Point[]](/imaging/python-net/aspose.imaging/point/) | Un tableau de trois structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représente les points d'un parallélogramme vers lequel les coins supérieur-gauche, supérieur-droit et inférieur-gauche du rectangle doivent être transformés. Le coin inférieur-droit du parallélogramme est implicite à partir des trois premiers coins. |

**Returns**

| Type | Description |
| :- | :- |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) |  |


### Method: create_with_rect_f(rect, plgpts)  [static] {#create_with_rect_f_rect_plgpts_2}


```
 create_with_rect_f(rect, plgpts) 
```

Initialise une nouvelle instance de la classe [Matrix](/imaging/python-net/aspose.imaging/matrix/) pour la transformation géométrique définie par le rectangle spécifié et le tableau de points.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Une structure [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) qui représente le rectangle à transformer. |
| plgpts | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Un tableau de trois structures [PointF](/imaging/python-net/aspose.imaging/pointf/) qui représente les points d'un parallélogramme vers lequel les coins supérieur-gauche, supérieur-droit et inférieur-gauche du rectangle doivent être transformés. Le coin inférieur-droit du parallélogramme est implicite à partir des trois premiers coins. |

**Returns**

| Type | Description |
| :- | :- |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) |  |


### Method: get_elements() {#get_elements__3}


```
 get_elements() 
```

Obtient une copie des éléments de la matrice.

**Returns**

| Type | Description |
| :- | :- |
| float[] | Une copie des éléments de la matrice. |


### Method: multiply(t_tx) {#multiply_t_tx_4}


```
 multiply(t_tx) 
```

Multiplie cette Matrix par la matrice spécifiée dans le paramètre matrix en utilisant l'ordre (par défaut) Prepend.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| t_tx | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La matrice avec laquelle multiplier. |

### Method: multiply(t_tx, order) {#multiply_t_tx_order_5}


```
 multiply(t_tx, order) 
```

Multiplie cette Matrix par la matrice spécifiée dans le paramètre matrix, et dans l'ordre spécifié dans le paramètre order.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| t_tx | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Le tx. Le tx. Le tx. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | L'ordre. L'ordre. L'ordre. |

### Method: rotate(angle) {#rotate_angle_6}


```
 rotate(angle) 
```

Applique une rotation horaire d'une valeur spécifiée dans le paramètre angle, autour de l'origine (coordonnées x et y nulles) pour cette Matrix dans l'ordre par défaut (Prepend).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle de rotation. |

### Method: rotate(angle, order) {#rotate_angle_order_7}


```
 rotate(angle, order) 
```

Applique une rotation horaire d'une valeur spécifiée dans le paramètre angle, autour de l'origine (coordonnées x et y nulles) pour cette Matrix dans l'ordre spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle de rotation. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | L'ordre de la matrice. |

### Method: rotate_at(angle, point) {#rotate_at_angle_point_8}


```
 rotate_at(angle, point) 
```

Applique une rotation horaire autour du point spécifié à cette Matrix dans l'ordre par défaut (Prepend).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Le point. |

### Method: rotate_at(angle, point, order) {#rotate_at_angle_point_order_9}


```
 rotate_at(angle, point, order) 
```

Applique une rotation horaire autour du point spécifié à cette Matrix dans l'ordre spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle. |
| point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | Le point. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | L'ordre. |

### Method: scale(scale_x, scale_y, order) {#scale_scale_x_scale_y_order_10}


```
 scale(scale_x, scale_y, order) 
```

Applique le vecteur d'échelle spécifié (scaleX et scaleY) à cette [Matrix](/imaging/python-net/aspose.imaging/matrix/) en utilisant l'ordre spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| scale_x | float | L'échelle X. |
| scale_y | float | L'échelle Y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | L'ordre. |

### Method: scale(sx, sy) {#scale_sx_sy_11}


```
 scale(sx, sy) 
```

Applique le vecteur d'échelle spécifié (scaleX et scaleY) à cette Matrix en utilisant l'ordre (par défaut) Prepend.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| sx | float | Le sx. Le sx. Le sx. |
| sy | float | Le sy. Le sy. Le sy. |

### Method: transform_points(points) {#transform_points_points_12}


```
 transform_points(points) 
```

Applique la transformation géométrique représentée par cette [Matrix](/imaging/python-net/aspose.imaging/matrix/) à un tableau de points spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Les points. |

### Method: translate(offset_x, offset_y, order) {#translate_offset_x_offset_y_order_13}


```
 translate(offset_x, offset_y, order) 
```

Applique le vecteur de translation spécifié à cette Matrix dans l'ordre spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| offset_x | float | Le décalage X. |
| offset_y | float | Le décalage Y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | L'ordre. |

### Method: translate(tx, ty) {#translate_tx_ty_14}


```
 translate(tx, ty) 
```

Applique le vecteur de translation spécifié à cette [Matrix](/imaging/python-net/aspose.imaging/matrix/) en utilisant l'ordre (par défaut) Prepend.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tx | float | Le tx. Le tx. Le tx. |
| ty | float | Le ty. Le ty. Le ty. |

