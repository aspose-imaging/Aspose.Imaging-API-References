---
title: "Pen"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Définit un objet utilisé pour dessiner des lignes, des courbes et des figures."
type: docs
weight: 81
url: /fr/java/com.aspose.imaging/pen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.TransparencySupporter](../../com.aspose.imaging/transparencysupporter)
```
public class Pen extends TransparencySupporter
```

Définit un objet utilisé pour dessiner des lignes, des courbes et des figures.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.imaging.Color-) | Initialise une nouvelle instance de la classe `Pen` avec la couleur spécifiée. |
| [Pen(Color color, float width)](#Pen-com.aspose.imaging.Color-float-) | Initialise une nouvelle instance de la classe `Pen` avec les propriétés `Color` et `Pen.Width` spécifiées. |
| [Pen(Brush brush)](#Pen-com.aspose.imaging.Brush-) | Initialise une nouvelle instance de la classe `Pen` avec le `Brush` spécifié. |
| [Pen(Brush brush, float width)](#Pen-com.aspose.imaging.Brush-float-) | Initialise une nouvelle instance de la classe `Pen` avec le `Brush` et le `Pen.Width` spécifiés. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Obtient la largeur de ce `Pen`, en unités de l'objet Graphics utilisé pour le dessin. |
| [setWidth(float value)](#setWidth-float-) | Définit la largeur de ce `Pen`, en unités de l'objet Graphics utilisé pour le dessin. |
| [getStartCap()](#getStartCap--) | Obtient le style de terminaison utilisé au début des lignes dessinées avec ce `Pen`. |
| [setStartCap(int value)](#setStartCap-int-) | Définit le style de terminaison utilisé au début des lignes dessinées avec ce `Pen`. |
| [getEndCap()](#getEndCap--) | Obtient le style de terminaison utilisé à la fin des lignes dessinées avec ce `Pen`. |
| [setEndCap(int value)](#setEndCap-int-) | Définit le style de terminaison utilisé à la fin des lignes dessinées avec ce `Pen`. |
| [getDashCap()](#getDashCap--) | Obtient le style de terminaison utilisé à la fin des tirets qui composent les lignes pointillées dessinées avec ce `Pen`. |
| [setDashCap(int value)](#setDashCap-int-) | Définit le style de terminaison utilisé à la fin des tirets qui composent les lignes pointillées dessinées avec ce `Pen`. |
| [getLineJoin()](#getLineJoin--) | Obtient le style de jointure pour les extrémités de deux lignes consécutives dessinées avec ce `Pen`. |
| [setLineJoin(int value)](#setLineJoin-int-) | Définit le style de jointure pour les extrémités de deux lignes consécutives dessinées avec ce `Pen`. |
| [getCustomStartCap()](#getCustomStartCap--) | Obtient une terminaison personnalisée à utiliser au début des lignes dessinées avec ce `Pen`. |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.imaging.CustomLineCap-) | Définit une terminaison personnalisée à utiliser au début des lignes dessinées avec ce `Pen`. |
| [getCustomEndCap()](#getCustomEndCap--) | Obtient une terminaison personnalisée à utiliser à la fin des lignes dessinées avec ce `Pen`. |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.imaging.CustomLineCap-) | Définit une terminaison personnalisée à utiliser à la fin des lignes dessinées avec ce `Pen`. |
| [getMiterLimit()](#getMiterLimit--) | Obtient la limite de l'épaisseur de la jointure sur un coin en onglet. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Définit la limite de l'épaisseur de la jointure sur un coin en onglet. |
| [getAlignment()](#getAlignment--) | Obtient l'alignement de ce `Pen`. |
| [setAlignment(int value)](#setAlignment-int-) | Définit l'alignement de ce `Pen`. |
| [getTransform()](#getTransform--) | Obtient une copie de la transformation géométrique de ce `Pen`. |
| [setTransform(Matrix value)](#setTransform-com.aspose.imaging.Matrix-) | Définit une copie de la transformation géométrique de ce `Pen`. |
| [getPenType()](#getPenType--) | Obtient le style des lignes dessinées avec ce `Pen`. |
| [getColor()](#getColor--) | Obtient la couleur de ce `Pen`. |
| [setColor(Color value)](#setColor-com.aspose.imaging.Color-) | Définit la couleur de ce `Pen`. |
| [getBrush()](#getBrush--) | Obtient le `Brush` qui détermine les attributs de ce `Pen`. |
| [setBrush(Brush value)](#setBrush-com.aspose.imaging.Brush-) | Définit le `Brush` qui détermine les attributs de ce `Pen`. |
| [getDashStyle()](#getDashStyle--) | Obtient le style utilisé pour les lignes pointillées dessinées avec ce `Pen`. |
| [setDashStyle(int value)](#setDashStyle-int-) | Définit le style utilisé pour les lignes pointillées dessinées avec ce `Pen`. |
| [getDashOffset()](#getDashOffset--) | Obtient la distance du début d'une ligne au début d'un motif de tirets. |
| [setDashOffset(float value)](#setDashOffset-float-) | Définit la distance du début d'une ligne au début d'un motif de tirets. |
| [getDashPattern()](#getDashPattern--) | Obtient un tableau de tirets et d'espaces personnalisés. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | Définit un tableau de tirets et d'espaces personnalisés. |
| [getCompoundArray()](#getCompoundArray--) | Obtient un tableau de valeurs qui spécifie un stylo composé. |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | Définit un tableau de valeurs qui spécifie un stylo composé. |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | Définit les valeurs qui déterminent le style de cap utilisé pour terminer les lignes dessinées par ce `Pen`. |
| [resetTransform()](#resetTransform--) | Réinitialise la matrice de transformation géométrique de ce `Pen` à l'identité. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.imaging.Matrix-) | Multiplie la matrice de transformation de ce `Pen` par la `Matrix` spécifiée. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.imaging.Matrix-int-) | Multiplie la matrice de transformation de ce `Pen` par la `Matrix` spécifiée dans l'ordre spécifié. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Déplace la transformation géométrique locale selon les dimensions spécifiées. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Déplace la transformation géométrique locale selon les dimensions spécifiées dans l'ordre spécifié. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Redimensionne la transformation géométrique locale par les facteurs spécifiés. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Mise à l'échelle de la transformation géométrique locale par les facteurs spécifiés dans l'ordre spécifié. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Fait pivoter la transformation géométrique locale par l'angle spécifié. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Fait pivoter la transformation géométrique locale par l'angle spécifié dans l'ordre spécifié. |
| [equals(Object o)](#equals-java.lang.Object-) | Vérifie si les objets sont égaux. |
| [hashCode()](#hashCode--) |  |

## Example: This example shows the creation and usage Pen objects.
Cet exemple montre la création et l'utilisation d'objets Pen. L'exemple crée une nouvelle Image et dessine des rectangles sur la surface de l'Image.
``` java

// Créez une instance de BmpOptions et définissez ses différentes propriétés
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// Créez une instance de FileCreateSource et affectez‑la comme Source pour l'instance de BmpOptions
// Le deuxième paramètre booléen détermine si le fichier à créer est IsTemporal ou non
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Créer une instance de Image au chemin spécifié.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Créer une instance de Graphics et l'initialiser avec l'objet Image.
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // Effacer la surface Graphics avec la couleur blanche.
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // Créer une instance de Pen avec la couleur rouge et une largeur de 5.
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // Créer une instance de HatchBrush et définir ses propriétés.
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // Créer une instance de Pen et l'initialiser avec l'objet HatchBrush et la largeur.
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // Dessiner des rectangles en spécifiant l'objet Pen.
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // Dessiner des rectangles en spécifiant l'objet Pen.
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // Enregistrer toutes les modifications.
    image.save();
} finally {
    image.dispose();
}
```

### Pen(Color color) {#Pen-com.aspose.imaging.Color-}
```
public Pen(Color color)
```


Initialise une nouvelle instance de la classe `Pen` avec la couleur spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | Une structure `Color` qui indique la couleur de ce `Pen`. |

### Pen(Color color, float width) {#Pen-com.aspose.imaging.Color-float-}
```
public Pen(Color color, float width)
```


Initialise une nouvelle instance de la classe `Pen` avec les propriétés `Color` et `Pen.Width` spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | Une structure `Color` qui indique la couleur de ce `Pen`. |
| width | float | Une valeur indiquant la largeur de ce `Pen`. |

### Pen(Brush brush) {#Pen-com.aspose.imaging.Brush-}
```
public Pen(Brush brush)
```


Initialise une nouvelle instance de la classe `Pen` avec le `Brush` spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Un `Brush` qui détermine les propriétés de remplissage de ce `Pen`. |

### Pen(Brush brush, float width) {#Pen-com.aspose.imaging.Brush-float-}
```
public Pen(Brush brush, float width)
```


Initialise une nouvelle instance de la classe `Pen` avec le `Brush` et le `Pen.Width` spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Un `Brush` qui détermine les caractéristiques de ce `Pen`. |
| width | float | La largeur du nouveau `Pen`. |

### getWidth() {#getWidth--}
```
public float getWidth()
```


Obtient la largeur de ce `Pen`, en unités de l'objet Graphics utilisé pour le dessin.

**Returns:**
float - La largeur de ce `Pen`.
### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Définit la largeur de ce `Pen`, en unités de l'objet Graphics utilisé pour le dessin.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | La largeur de ce `Pen`. |

### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


Obtient le style de terminaison utilisé au début des lignes dessinées avec ce `Pen`.

**Returns:**
int - L'une des valeurs `LineCap` qui représente le style de terminaison utilisé au début des lignes tracées avec ce `Pen`.
### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


Définit le style de terminaison utilisé au début des lignes dessinées avec ce `Pen`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | L'une des valeurs `LineCap` qui représente le style de terminaison utilisé au début des lignes tracées avec ce `Pen`. |

### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


Obtient le style de terminaison utilisé à la fin des lignes dessinées avec ce `Pen`.

**Returns:**
int - L'une des valeurs `LineCap` qui représente le style de terminaison utilisé à la fin des lignes tracées avec ce `Pen`.
### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


Définit le style de terminaison utilisé à la fin des lignes dessinées avec ce `Pen`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | L'une des valeurs `LineCap` qui représente le style de terminaison utilisé à la fin des lignes tracées avec ce `Pen`. |

### getDashCap() {#getDashCap--}
```
public int getDashCap()
```


Obtient le style de terminaison utilisé à la fin des tirets qui composent les lignes pointillées dessinées avec ce `Pen`.

**Returns:**
int - L'une des valeurs `DashCap` qui représente le style de terminaison utilisé au début et à la fin des tirets qui composent les lignes pointillées tracées avec ce `Pen`.
### setDashCap(int value) {#setDashCap-int-}
```
public void setDashCap(int value)
```


Définit le style de terminaison utilisé à la fin des tirets qui composent les lignes pointillées dessinées avec ce `Pen`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | L'une des valeurs `DashCap` qui représente le style de terminaison utilisé au début et à la fin des tirets qui composent les lignes pointillées tracées avec ce `Pen`. |

### getLineJoin() {#getLineJoin--}
```
public int getLineJoin()
```


Obtient le style de jointure pour les extrémités de deux lignes consécutives dessinées avec ce `Pen`.

**Returns:**
int - Un `LineJoin` qui représente le style de jointure pour les extrémités de deux lignes consécutives tracées avec ce `Pen`.
### setLineJoin(int value) {#setLineJoin-int-}
```
public void setLineJoin(int value)
```


Définit le style de jointure pour les extrémités de deux lignes consécutives dessinées avec ce `Pen`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Un `LineJoin` qui représente le style de jointure pour les extrémités de deux lignes consécutives tracées avec ce `Pen`. |

### getCustomStartCap() {#getCustomStartCap--}
```
public CustomLineCap getCustomStartCap()
```


Obtient une terminaison personnalisée à utiliser au début des lignes dessinées avec ce `Pen`.

**Returns:**
[CustomLineCap](../../com.aspose.imaging/customlinecap) - A `CustomLineCap` that represents the cap used at the beginning of lines drawn with this `Pen`.
### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.imaging.CustomLineCap-}
```
public void setCustomStartCap(CustomLineCap value)
```


Définit une terminaison personnalisée à utiliser au début des lignes dessinées avec ce `Pen`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.imaging/customlinecap) | Un `CustomLineCap` qui représente le cap utilisé au début des lignes tracées avec ce `Pen`. |

### getCustomEndCap() {#getCustomEndCap--}
```
public CustomLineCap getCustomEndCap()
```


Obtient une terminaison personnalisée à utiliser à la fin des lignes dessinées avec ce `Pen`.

**Returns:**
[CustomLineCap](../../com.aspose.imaging/customlinecap) - A `CustomLineCap` that represents the cap used at the end of lines drawn with this `Pen`.
### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.imaging.CustomLineCap-}
```
public void setCustomEndCap(CustomLineCap value)
```


Définit une terminaison personnalisée à utiliser à la fin des lignes dessinées avec ce `Pen`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.imaging/customlinecap) | Un `CustomLineCap` qui représente le cap utilisé à la fin des lignes tracées avec ce `Pen`. |

### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


Obtient la limite de l'épaisseur de la jointure sur un coin en onglet.

**Returns:**
float - La limite de l'épaisseur de la jointure sur un coin en onglet.
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


Définit la limite de l'épaisseur de la jointure sur un coin en onglet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | La limite de l'épaisseur de la jointure sur un coin en onglet. |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Obtient l'alignement de ce `Pen`.

**Returns:**
int - Un `PenAlignment` qui représente l'alignement pour ce `Pen`.
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Définit l'alignement de ce `Pen`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Un `PenAlignment` qui représente l'alignement pour ce `Pen`. |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Obtient une copie de la transformation géométrique de ce `Pen`.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - A copy of the `Matrix` that represents the geometric transformation for this `Pen`.
### setTransform(Matrix value) {#setTransform-com.aspose.imaging.Matrix-}
```
public void setTransform(Matrix value)
```


Définit une copie de la transformation géométrique de ce `Pen`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) | Une copie de la `Matrix` qui représente la transformation géométrique pour ce `Pen`. |

### getPenType() {#getPenType--}
```
public int getPenType()
```


Obtient le style des lignes dessinées avec ce `Pen`.

**Returns:**
int - Une énumération `PenType` qui spécifie le style des lignes tracées avec ce `Pen`.
### getColor() {#getColor--}
```
public Color getColor()
```


Obtient la couleur de ce `Pen`.

**Returns:**
[Color](../../com.aspose.imaging/color) - A `Color` structure that represents the color of this `Pen`.
### setColor(Color value) {#setColor-com.aspose.imaging.Color-}
```
public void setColor(Color value)
```


Définit la couleur de ce `Pen`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Une structure `Color` qui représente la couleur de ce `Pen`. |

### getBrush() {#getBrush--}
```
public Brush getBrush()
```


Obtient le `Brush` qui détermine les attributs de ce `Pen`.

**Returns:**
[Brush](../../com.aspose.imaging/brush) - A `Brush` that determines attributes of this `Pen`.
### setBrush(Brush value) {#setBrush-com.aspose.imaging.Brush-}
```
public void setBrush(Brush value)
```


Définit le `Brush` qui détermine les attributs de ce `Pen`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Brush](../../com.aspose.imaging/brush) | Un `Brush` qui détermine les attributs de ce `Pen`. |

### getDashStyle() {#getDashStyle--}
```
public int getDashStyle()
```


Obtient le style utilisé pour les lignes pointillées dessinées avec ce `Pen`.

**Returns:**
int - Un `DashStyle` qui représente le style utilisé pour les lignes en pointillé tracées avec ce `Pen`.
### setDashStyle(int value) {#setDashStyle-int-}
```
public void setDashStyle(int value)
```


Définit le style utilisé pour les lignes pointillées dessinées avec ce `Pen`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Un `DashStyle` qui représente le style utilisé pour les lignes en pointillé tracées avec ce `Pen`. |

### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


Obtient la distance du début d'une ligne au début d'un motif de tirets.

**Returns:**
float - La distance du début d'une ligne au commencement d'un motif de tirets.
### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


Définit la distance du début d'une ligne au début d'un motif de tirets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | La distance du début d'une ligne au commencement d'un motif de tirets. |

### getDashPattern() {#getDashPattern--}
```
public float[] getDashPattern()
```


Obtient un tableau de tirets et d'espaces personnalisés.

**Returns:**
float[] - Un tableau de nombres réels qui spécifie les longueurs des tirets et espaces alternés dans les lignes en pointillé.
### setDashPattern(float[] value) {#setDashPattern-float---}
```
public void setDashPattern(float[] value)
```


Définit un tableau de tirets et d'espaces personnalisés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float[] | Un tableau de nombres réels qui spécifie les longueurs des tirets et espaces alternés dans les lignes en pointillé. |

### getCompoundArray() {#getCompoundArray--}
```
public float[] getCompoundArray()
```


Obtient un tableau de valeurs qui spécifie un stylo composé. Un stylo composé trace une ligne composée constituée de lignes parallèles et d'espaces.

**Returns:**
float[] - Un tableau de nombres réels qui spécifie le tableau composé. Les éléments du tableau doivent être en ordre croissant, pas moins que 0, et pas plus que 1.
### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public void setCompoundArray(float[] value)
```


Définit un tableau de valeurs qui spécifie un stylo composé. Un stylo composé trace une ligne composée constituée de lignes parallèles et d'espaces.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float[] | Un tableau de nombres réels qui spécifie le tableau composé. Les éléments du tableau doivent être en ordre croissant, pas moins que 0, et pas plus que 1. |

### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public void setLineCap(int startCap, int endCap, int dashCap)
```


Définit les valeurs qui déterminent le style de cap utilisé pour terminer les lignes dessinées par ce `Pen`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| startCap | int | Un `LineCap` qui représente le style de cap à utiliser au début des lignes tracées avec ce `Pen`. |
| endCap | int | Un `LineCap` qui représente le style de cap à utiliser à la fin des lignes tracées avec ce `Pen`. |
| dashCap | int | Un `LineCap` qui représente le style de cap à utiliser au début ou à la fin des lignes en pointillé tracées avec ce `Pen`. |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Réinitialise la matrice de transformation géométrique de ce `Pen` à l'identité.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.imaging.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multiplie la matrice de transformation de ce `Pen` par la `Matrix` spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | L'objet `Matrix` par lequel multiplier la matrice de transformation. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.imaging.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multiplie la matrice de transformation de ce `Pen` par la `Matrix` spécifiée dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Le `Matrix` par lequel multiplier la matrice de transformation. |
| ordre | int | L'ordre dans lequel effectuer l'opération de multiplication. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Effectue une translation de la transformation géométrique locale selon les dimensions spécifiées. Cette méthode préfixe la translation à la transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dx | float | La valeur de la translation en x. |
| dy | float | La valeur de la translation en y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Déplace la transformation géométrique locale selon les dimensions spécifiées dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dx | float | La valeur de la translation en x. |
| dy | float | La valeur de la translation en y. |
| ordre | int | L'ordre (préfixer ou ajouter) dans lequel appliquer la translation. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Met à l'échelle la transformation géométrique locale selon les facteurs spécifiés. Cette méthode préfixe la matrice d'échelle à la transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sx | float | Le facteur par lequel mettre à l'échelle la transformation dans la direction de l'axe x. |
| sy | float | Le facteur par lequel mettre à l'échelle la transformation dans la direction de l'axe y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Mise à l'échelle de la transformation géométrique locale par les facteurs spécifiés dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sx | float | Le facteur par lequel mettre à l'échelle la transformation dans la direction de l'axe x. |
| sy | float | Le facteur par lequel mettre à l'échelle la transformation dans la direction de l'axe y. |
| ordre | int | Un `MatrixOrder` qui spécifie s'il faut ajouter ou préfixer la matrice d'échelle. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Fait pivoter la transformation géométrique locale selon l'angle spécifié. Cette méthode préfixe la rotation à la transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Fait pivoter la transformation géométrique locale par l'angle spécifié dans l'ordre spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation. |
| ordre | int | Un `MatrixOrder` qui spécifie s'il faut ajouter ou préfixer la matrice de rotation. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Vérifie si les objets sont égaux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| o | java.lang.Object | L'autre objet. |

**Returns:**
boolean - Le résultat de la comparaison d'égalité.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtient le code de hachage de l'objet actuel.

**Returns:**
int
