---
title: "Matrix"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Remplace la matrice GDI."
type: docs
weight: 72
url: /fr/java/com.aspose.imaging/matrix/
---
**Inheritance:**
java.lang.Object
```
public class Matrix
```

Remplace la matrice GDI+.

--------------------

La plupart des algorithmes proviennent de AffineTransform.java de Sun. Noms Java des éléments de matrice utilisés en interne. Correspondance des noms Java aux noms .net avec description : m00 M11 Échelle X m10 M12 Cisaillement Y m01 M21 Cisaillement X m11 M22 Échelle Y m02 M31 Translation X m12 M32 Translation Y
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Matrix()](#Matrix--) | Initialise une nouvelle instance de la classe Matrix en tant que matrice identité. |
| [Matrix(float m11, float m12, float m21, float m22, float m31, float m32)](#Matrix-float-float-float-float-float-float-) | Initialise une nouvelle instance de la classe [Matrix](../../com.aspose.imaging/matrix). |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.imaging.RectangleF-com.aspose.imaging.PointF---) | Initialise une nouvelle instance de la classe [Matrix](../../com.aspose.imaging/matrix) avec la transformation géométrique définie par le rectangle spécifié et le tableau de points. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.imaging.Rectangle-com.aspose.imaging.Point---) | Initialise une nouvelle instance de la classe [Matrix](../../com.aspose.imaging/matrix) avec la transformation géométrique définie par le rectangle spécifié et le tableau de points. |
| [Matrix(Matrix origin)](#Matrix-com.aspose.imaging.Matrix-) | Crée une copie de la classe [Matrix](../../com.aspose.imaging/matrix). |
## Champs

| Champ | Description |
| --- | --- |
| [TYPE_IDENTITY](#TYPE-IDENTITY) | Une transformation identité est celle dans laquelle les coordonnées de sortie sont toujours identiques aux coordonnées d'entrée. |
| [TYPE_TRANSLATION](#TYPE-TRANSLATION) | Une translation déplace les coordonnées d'une quantité constante en x et y sans modifier la longueur ou l'angle des vecteurs. |
| [TYPE_UNIFORM_SCALE](#TYPE-UNIFORM-SCALE) | Une échelle uniforme multiplie la longueur des vecteurs par la même quantité dans les directions x et y sans changer l'angle entre les vecteurs. |
| [TYPE_GENERAL_SCALE](#TYPE-GENERAL-SCALE) | Une échelle générale multiplie la longueur des vecteurs par des valeurs différentes dans les directions x et y sans changer l'angle entre les vecteurs perpendiculaires. |
| [TYPE_MASK_SCALE](#TYPE-MASK-SCALE) | Cette constante est un masque de bits pour n'importe quel bit d'indicateur d'échelle. |
| [TYPE_FLIP](#TYPE-FLIP) | Ce bit d'indicateur indique que la transformation définie par cet objet effectue un retournement en miroir autour d'un axe, ce qui transforme le système de coordonnées normalement droit en un système gauche, en plus des conversions indiquées par les autres bits d'indicateur. |
| [TYPE_QUADRANT_ROTATION](#TYPE-QUADRANT-ROTATION) | Ce bit d'indicateur indique que la transformation définie par cet objet effectue une rotation de quadrant par un multiple de 90 degrés, en plus des conversions indiquées par les autres bits d'indicateur. |
| [TYPE_GENERAL_ROTATION](#TYPE-GENERAL-ROTATION) | Ce bit d'indicateur indique que la transformation définie par cet objet effectue une rotation d'un angle arbitraire, en plus des conversions indiquées par les autres bits d'indicateur. |
| [TYPE_MASK_ROTATION](#TYPE-MASK-ROTATION) | Cette constante est un masque de bits pour n'importe quel bit d'indicateur de rotation. |
| [TYPE_GENERAL_TRANSFORM](#TYPE-GENERAL-TRANSFORM) | Cette constante indique que la transformation définie par cet objet effectue une conversion arbitraire des coordonnées d'entrée. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [isEquals(Matrix a, Matrix b)](#isEquals-com.aspose.imaging.Matrix-com.aspose.imaging.Matrix-) | Détermine si deux matrices sont égales. |
| [getM11()](#getM11--) | Obtient l'élément de la matrice à la première ligne, première colonne. |
| [getM12()](#getM12--) | Obtient l'élément de la matrice à la première ligne, deuxième colonne. |
| [getM21()](#getM21--) | Obtient l'élément de la matrice à la deuxième ligne, première colonne. |
| [getM22()](#getM22--) | Obtient l'élément de la matrice à la deuxième ligne, deuxième colonne. |
| [getM31()](#getM31--) | Obtient l'élément de la matrice à la troisième ligne, première colonne. |
| [getM32()](#getM32--) | Obtient l'élément de la matrice à la troisième ligne, première colonne. |
| [toString()](#toString--) | Renvoie une chaîne qui représente cette instance. |
| [getElements()](#getElements--) | Obtient une copie des éléments de la matrice. |
| [transformPoints(PointF[] points)](#transformPoints-com.aspose.imaging.PointF---) | Applique la transformation géométrique représentée par ce [Matrix](../../com.aspose.imaging/matrix) à un tableau spécifié de points. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | Applique le vecteur d'échelle spécifié (scaleX et scaleY) à ce [Matrix](../../com.aspose.imaging/matrix) en utilisant l'ordre spécifié. |
| [scale(float sx, float sy)](#scale-float-float-) | Applique le vecteur d'échelle spécifié (scaleX et scaleY) à ce Matrix en utilisant l'ordre (par défaut) Prepend. |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | Applique le vecteur de translation spécifié à ce Matrix dans l'ordre spécifié. |
| [translate(float tx, float ty)](#translate-float-float-) | Applique le vecteur de translation spécifié à ce [Matrix](../../com.aspose.imaging/matrix) en utilisant l'ordre (par défaut) Prepend. |
| [multiply(Matrix tTx, int order)](#multiply-com.aspose.imaging.Matrix-int-) | Multiplie ce Matrix par la matrice spécifiée dans le paramètre matrix, et dans l'ordre spécifié dans le paramètre order. |
| [multiply(Matrix tTx)](#multiply-com.aspose.imaging.Matrix-) | Multiplie ce Matrix par la matrice spécifiée dans le paramètre matrix en utilisant l'ordre (par défaut) Prepend. |
| [rotate(float angle, int order)](#rotate-float-int-) | Applique une rotation horaire d'une valeur spécifiée dans le paramètre angle, autour de l'origine (coordonnées x et y nulles) pour ce Matrix dans l'ordre spécifié. |
| [rotate(float angle)](#rotate-float-) | Applique une rotation horaire d'une valeur spécifiée dans le paramètre angle, autour de l'origine (coordonnées x et y nulles) pour ce Matrix dans l'ordre par défaut (Prepend). |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.imaging.PointF-int-) | Applique une rotation horaire autour du point spécifié à ce Matrix dans l'ordre spécifié. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.imaging.PointF-) | Applique une rotation horaire autour du point spécifié à ce Matrix dans l'ordre par défaut (Prepend). |
| [reset()](#reset--) | Réinitialise cette matrice pour qu’elle contienne les éléments de la matrice identité. |
| [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette instance. |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si l'`Object` spécifié est égal à cette instance. |
| [isIdentity()](#isIdentity--) | Renvoie `true` si cet `AffineTransform` est une transformation identité. |
### Matrix() {#Matrix--}
```
public Matrix()
```


Initialise une nouvelle instance de la classe Matrix en tant que matrice identité.

### Matrix(float m11, float m12, float m21, float m22, float m31, float m32) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```


Initialise une nouvelle instance de la classe [Matrix](../../com.aspose.imaging/matrix).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| m11 | float | m00 M11 Échelle X |
| m12 | float | m10 M12 Cisaillement Y |
| m21 | float | m01 M21 Cisaillement X |
| m22 | float | m11 M22 Échelle Y |
| m31 | float | m02 M31 Translation X |
| m32 | float | m12 M32 Translation Y |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.imaging.RectangleF-com.aspose.imaging.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


Initialise une nouvelle instance de la classe [Matrix](../../com.aspose.imaging/matrix) avec la transformation géométrique définie par le rectangle spécifié et le tableau de points.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Une structure [RectangleF](../../com.aspose.imaging/rectanglef) qui représente le rectangle à transformer. |
| plgpts | [PointF\[\]](../../com.aspose.imaging/pointf) | Un tableau de trois structures [PointF](../../com.aspose.imaging/pointf) qui représente les points d’un parallélogramme vers lequel les coins supérieur gauche, supérieur droit et inférieur gauche du rectangle doivent être transformés. Le coin inférieur droit du parallélogramme est implicite à partir des trois premiers coins. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.imaging.Rectangle-com.aspose.imaging.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


Initialise une nouvelle instance de la classe [Matrix](../../com.aspose.imaging/matrix) avec la transformation géométrique définie par le rectangle spécifié et le tableau de points.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Une structure [Rectangle](../../com.aspose.imaging/rectangle) qui représente le rectangle à transformer. |
| plgpts | [Point\[\]](../../com.aspose.imaging/point) | Un tableau de trois structures [Point](../../com.aspose.imaging/point) qui représente les points d’un parallélogramme vers lequel les coins supérieur gauche, supérieur droit et inférieur gauche du rectangle doivent être transformés. Le coin inférieur droit du parallélogramme est implicite à partir des trois premiers coins. |

### Matrix(Matrix origin) {#Matrix-com.aspose.imaging.Matrix-}
```
public Matrix(Matrix origin)
```


Crée une copie de la classe [Matrix](../../com.aspose.imaging/matrix).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| origin | [Matrix](../../com.aspose.imaging/matrix) | Une matrice de base pour la copie |

### TYPE_IDENTITY {#TYPE-IDENTITY}
```
public static final int TYPE_IDENTITY
```


Une transformation identité est celle dans laquelle les coordonnées de sortie sont toujours les mêmes que les coordonnées d’entrée. Si cette transformation n’est pas une transformation identité, le type sera soit la constante GENERAL\_TRANSFORM, soit une combinaison des bits de drapeau appropriés pour les diverses conversions de coordonnées que cette transformation effectue.

### TYPE_TRANSLATION {#TYPE-TRANSLATION}
```
public static final int TYPE_TRANSLATION
```


Une translation déplace les coordonnées d'une quantité constante en x et y sans modifier la longueur ou l'angle des vecteurs.

### TYPE_UNIFORM_SCALE {#TYPE-UNIFORM-SCALE}
```
public static final int TYPE_UNIFORM_SCALE
```


Une échelle uniforme multiplie la longueur des vecteurs par la même valeur dans les directions x et y sans modifier l’angle entre les vecteurs. Ce bit de drapeau est mutuellement exclusif avec le drapeau TypeGeneralScale.

### TYPE_GENERAL_SCALE {#TYPE-GENERAL-SCALE}
```
public static final int TYPE_GENERAL_SCALE
```


Une échelle générale multiplie la longueur des vecteurs par des valeurs différentes dans les directions x et y sans modifier l’angle entre les vecteurs perpendiculaires. Ce bit de drapeau est mutuellement exclusif avec le drapeau TypeUniformScale.

### TYPE_MASK_SCALE {#TYPE-MASK-SCALE}
```
public static final int TYPE_MASK_SCALE
```


Cette constante est un masque de bits pour n'importe quel bit d'indicateur d'échelle.

### TYPE_FLIP {#TYPE-FLIP}
```
public static final int TYPE_FLIP
```


Ce bit de drapeau indique que la transformation définie par cet objet effectue un retournement miroir autour d’un axe qui transforme le système de coordonnées normalement droitier en un système gaucher, en plus des conversions indiquées par les autres bits de drapeau. Un système de coordonnées droitier est celui où l’axe X positif tourne dans le sens inverse des aiguilles d’une montre pour se superposer à l’axe Y positif, similaire à la direction dans laquelle les doigts de votre main droite se courbent lorsque vous regardez votre pouce de face. Un système de coordonnées gaucher est celui où l’axe X positif tourne dans le sens des aiguilles d’une montre pour se superposer à l’axe Y positif, similaire à la direction dans laquelle les doigts de votre main gauche se courbent. Il n’existe aucun moyen mathématique de déterminer l’angle de la transformation de retournement ou de miroir d’origine, puisque tous les angles de retournement sont identiques lorsqu’une rotation d’ajustement appropriée est appliquée. NOTE : TypeFlip a été ajouté après que GENERAL\_TRANSFORM était en circulation publique et les bits de drapeau ne pouvaient plus être renumérotés commodément sans introduire une incompatibilité binaire dans le code externe.

### TYPE_QUADRANT_ROTATION {#TYPE-QUADRANT-ROTATION}
```
public static final int TYPE_QUADRANT_ROTATION
```


Ce bit de drapeau indique que la transformation définie par cet objet effectue une rotation de quadrant d’un multiple de 90 degrés en plus des conversions indiquées par les autres bits de drapeau. Une rotation modifie les angles des vecteurs de la même quantité, quel que soit le sens d’origine du vecteur, et sans changer la longueur du vecteur. Ce bit de drapeau est mutuellement exclusif avec le drapeau TypeGeneralRotation.

### TYPE_GENERAL_ROTATION {#TYPE-GENERAL-ROTATION}
```
public static final int TYPE_GENERAL_ROTATION
```


Ce bit d'indicateur indique que la transformation définie par cet objet effectue une rotation d'un angle arbitraire en plus des conversions indiquées par les autres bits d'indicateur. Une rotation modifie les angles des vecteurs du même montant, quel que soit le sens d'origine du vecteur, et sans changer la longueur du vecteur. Ce bit d'indicateur est mutuellement exclusif avec le

### TYPE_MASK_ROTATION {#TYPE-MASK-ROTATION}
```
public static final int TYPE_MASK_ROTATION
```


Cette constante est un masque de bits pour n'importe quel bit d'indicateur de rotation.

### TYPE_GENERAL_TRANSFORM {#TYPE-GENERAL-TRANSFORM}
```
public static final int TYPE_GENERAL_TRANSFORM
```


Cette constante indique que la transformation définie par cet objet effectue une conversion arbitraire des coordonnées d'entrée. Si cette transformation peut être classée par l'une des constantes ci‑dessus, le type sera soit la constante TypeIdentity, soit une combinaison des bits d'indicateur appropriés pour les diverses conversions de coordonnées que cette transformation effectue.

### isEquals(Matrix a, Matrix b) {#isEquals-com.aspose.imaging.Matrix-com.aspose.imaging.Matrix-}
```
public static boolean isEquals(Matrix a, Matrix b)
```


Détermine si deux matrices sont égales.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [Matrix](../../com.aspose.imaging/matrix) | La première matrice à comparer. |
| b | [Matrix](../../com.aspose.imaging/matrix) | La deuxième matrice à comparer. |

**Returns:**
boolean - Vrai si les matrices sont égales.
### getM11() {#getM11--}
```
public final float getM11()
```


Obtient l'élément de matrice à la première ligne première colonne. Représente l'échelle le long de l'axe X.

**Returns:**
float - l'élément de matrice à la première ligne première colonne.
### getM12() {#getM12--}
```
public final float getM12()
```


Obtient l'élément de matrice à la première ligne deuxième colonne. Représente le cisaillement le long de l'axe Y.

**Returns:**
float - l'élément de matrice à la première ligne deuxième colonne.
### getM21() {#getM21--}
```
public final float getM21()
```


Obtient l'élément de matrice à la deuxième ligne première colonne. Représente le cisaillement le long de l'axe X.

**Returns:**
float - l'élément de matrice à la deuxième ligne première colonne.
### getM22() {#getM22--}
```
public final float getM22()
```


Obtient l'élément de matrice à la deuxième ligne deuxième colonne. Représente l'échelle le long de l'axe Y.

**Returns:**
float - l'élément de matrice à la deuxième ligne deuxième colonne.
### getM31() {#getM31--}
```
public final float getM31()
```


Obtient l'élément de matrice à la troisième ligne première colonne. Représente la translation le long de l'axe X.

**Returns:**
float - l'élément de matrice à la troisième ligne première colonne.
### getM32() {#getM32--}
```
public final float getM32()
```


Obtient l'élément de matrice à la troisième ligne première colonne. Représente la translation le long de l'axe Y.

**Returns:**
float - l'élément de matrice à la troisième ligne première colonne.
### toString() {#toString--}
```
public String toString()
```


Renvoie une chaîne qui représente cette instance.

**Returns:**
java.lang.String - Une chaîne qui représente cette instance.
### getElements() {#getElements--}
```
public final float[] getElements()
```


Obtient une copie des éléments de la matrice.

**Returns:**
float[] - Une copie des éléments de la matrice.
### transformPoints(PointF[] points) {#transformPoints-com.aspose.imaging.PointF---}
```
public final void transformPoints(PointF[] points)
```


Applique la transformation géométrique représentée par ce [Matrix](../../com.aspose.imaging/matrix) à un tableau spécifié de points.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Les points. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public final void scale(float scaleX, float scaleY, int order)
```


Applique le vecteur d'échelle spécifié (scaleX et scaleY) à ce [Matrix](../../com.aspose.imaging/matrix) en utilisant l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| scaleX | float | L'échelle X. |
| scaleY | float | L'échelle Y. |
| ordre | int | L'ordre. |

### scale(float sx, float sy) {#scale-float-float-}
```
public final void scale(float sx, float sy)
```


Applique le vecteur d'échelle spécifié (scaleX et scaleY) à ce Matrix en utilisant l'ordre (par défaut) Prepend.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sx | float | Le sx. Le sx. Le sx. |
| sy | float | Le sy. Le sy. Le sy. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public final void translate(float offsetX, float offsetY, int order)
```


Applique le vecteur de translation spécifié à ce Matrix dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| offsetX | float | Le offset X. |
| offsetY | float | Le offset Y. |
| ordre | int | L'ordre. |

### translate(float tx, float ty) {#translate-float-float-}
```
public final void translate(float tx, float ty)
```


Applique le vecteur de translation spécifié à ce [Matrix](../../com.aspose.imaging/matrix) en utilisant l'ordre (par défaut) Prepend.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tx | float | Le tx. Le tx. Le tx. |
| ty | float | Le ty. Le ty. Le ty. |

### multiply(Matrix tTx, int order) {#multiply-com.aspose.imaging.Matrix-int-}
```
public final void multiply(Matrix tTx, int order)
```


Multiplie ce Matrix par la matrice spécifiée dans le paramètre matrix, et dans l'ordre spécifié dans le paramètre order.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tTx | [Matrix](../../com.aspose.imaging/matrix) | Le tx. Le tx. Le tx. |
| ordre | int | L'ordre. L'ordre. L'ordre. |

### multiply(Matrix tTx) {#multiply-com.aspose.imaging.Matrix-}
```
public final void multiply(Matrix tTx)
```


Multiplie ce Matrix par la matrice spécifiée dans le paramètre matrix en utilisant l'ordre (par défaut) Prepend.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tTx | [Matrix](../../com.aspose.imaging/matrix) | La matrice avec laquelle multiplier. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public final void rotate(float angle, int order)
```


Applique une rotation horaire d'une valeur spécifiée dans le paramètre angle, autour de l'origine (coordonnées x et y nulles) pour ce Matrix dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation. |
| ordre | int | L'ordre de la matrice. |

### rotate(float angle) {#rotate-float-}
```
public final void rotate(float angle)
```


Applique une rotation horaire d'une valeur spécifiée dans le paramètre angle, autour de l'origine (coordonnées x et y nulles) pour ce Matrix dans l'ordre par défaut (Prepend).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.imaging.PointF-int-}
```
public final void rotateAt(float angle, PointF point, int order)
```


Applique une rotation horaire autour du point spécifié à ce Matrix dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle. |
| point | [PointF](../../com.aspose.imaging/pointf) | Le point. |
| ordre | int | L'ordre. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.imaging.PointF-}
```
public final void rotateAt(float angle, PointF point)
```


Applique une rotation horaire autour du point spécifié à ce Matrix dans l'ordre par défaut (Prepend).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle. |
| point | [PointF](../../com.aspose.imaging/pointf) | Le point. |

### reset() {#reset--}
```
public final void reset()
```


Réinitialise cette matrice pour qu’elle contienne les éléments de la matrice identité.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour cette instance.

**Returns:**
int - Un code de hachage pour cette instance, adapté à une utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si l'`Object` spécifié est égal à cette instance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'`Object` à comparer avec cette instance. |

**Returns:**
booléen - `true` si l'`Object` spécifié est égal à cette instance ; sinon, `false`.
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


Renvoie `true` si cet `AffineTransform` est une transformation identité.

**Returns:**
booléen - `true` si ce `AffineTransform` est une transformation identité ; `false` sinon.
