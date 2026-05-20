---
title: "TextShape"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente une forme de texte."
type: docs
weight: 18
url: /fr/java/com.aspose.imaging.shapes/textshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.RectangleProjectedShape](../../com.aspose.imaging.shapes/rectangleprojectedshape)
```
public final class TextShape extends RectangleProjectedShape
```

Représente une forme de texte.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextShape()](#TextShape--) | Initialise une nouvelle instance de la classe `TextShape`. |
| [TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)](#TextShape-java.lang.String-com.aspose.imaging.RectangleF-com.aspose.imaging.Font-com.aspose.imaging.StringFormat-) | Initialise une nouvelle instance de la classe `TextShape`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getText()](#getText--) | Obtient ou définit le texte dessiné. |
| [setText(String value)](#setText-java.lang.String-) | Obtient ou définit le texte dessiné. |
| [getFont()](#getFont--) | Obtient ou définit la police utilisée pour dessiner le texte. |
| [setFont(Font value)](#setFont-com.aspose.imaging.Font-) | Obtient ou définit la police utilisée pour dessiner le texte. |
| [getTextFormat()](#getTextFormat--) | Obtient ou définit le format du texte. |
| [setTextFormat(StringFormat value)](#setTextFormat-com.aspose.imaging.StringFormat-) | Obtient ou définit le format du texte. |
| [getCenter()](#getCenter--) | Obtient le centre de la forme. |
| [getBounds()](#getBounds--) | Obtient les limites de l'objet. |
| [getSegments()](#getSegments--) | Obtient les segments de la forme. |
| [hasSegments()](#hasSegments--) | Obtient une valeur indiquant si la forme possède des segments. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Obtient les limites de l'objet. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Obtient les limites de l'objet. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Applique la transformation spécifiée à la forme. |
| [equals(Object o)](#equals-java.lang.Object-) | Vérifie si les objets sont égaux. |
| [hashCode()](#hashCode--) | Obtient le code de hachage de l'objet actuel. |
### TextShape() {#TextShape--}
```
public TextShape()
```


Initialise une nouvelle instance de la classe `TextShape`.

### TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat) {#TextShape-java.lang.String-com.aspose.imaging.RectangleF-com.aspose.imaging.Font-com.aspose.imaging.StringFormat-}
```
public TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)
```


Initialise une nouvelle instance de la classe `TextShape`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Le texte à dessiner. |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Le rectangle de texte. |
| font | [Font](../../com.aspose.imaging/font) | La police à utiliser. |
| stringFormat | [StringFormat](../../com.aspose.imaging/stringformat) | Le format de chaîne. |

### getText() {#getText--}
```
public String getText()
```


Obtient ou définit le texte dessiné.

Valeur : le texte dessiné.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Obtient ou définit le texte dessiné.

Valeur : le texte dessiné.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getFont() {#getFont--}
```
public Font getFont()
```


Obtient ou définit la police utilisée pour dessiner le texte.

Valeur : la police utilisée pour dessiner le texte.

**Returns:**
[Font](../../com.aspose.imaging/font)
### setFont(Font value) {#setFont-com.aspose.imaging.Font-}
```
public void setFont(Font value)
```


Obtient ou définit la police utilisée pour dessiner le texte.

Valeur : la police utilisée pour dessiner le texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Font](../../com.aspose.imaging/font) |  |

### getTextFormat() {#getTextFormat--}
```
public StringFormat getTextFormat()
```


Obtient ou définit le format du texte.

Valeur : le format du texte.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat)
### setTextFormat(StringFormat value) {#setTextFormat-com.aspose.imaging.StringFormat-}
```
public void setTextFormat(StringFormat value)
```


Obtient ou définit le format du texte.

Valeur : le format du texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [StringFormat](../../com.aspose.imaging/stringformat) |  |

### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Obtient le centre de la forme.

Valeur: le centre de la forme.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Obtient les limites de l'objet.

Valeur: les limites de l'objet.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Obtient les segments de la forme.

Valeur : les segments de la forme.

**Returns:**
com.aspose.imaging.ShapeSegment[]
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Obtient une valeur indiquant si la forme possède des segments.

Valeur: `True` si la forme possède des segments ; sinon, `false`.

**Returns:**
boolean
### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Obtient les limites de l'objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La matrice à appliquer avant que les limites ne soient calculées. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Obtient les limites de l'objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La matrice à appliquer avant que les limites ne soient calculées. |
| pen | [Pen](../../com.aspose.imaging/pen) | Le stylo à utiliser pour l'objet. Cela peut influencer la taille des limites de l'objet. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


Applique la transformation spécifiée à la forme.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | La transformation à appliquer. |

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
int - Le code de hachage.
