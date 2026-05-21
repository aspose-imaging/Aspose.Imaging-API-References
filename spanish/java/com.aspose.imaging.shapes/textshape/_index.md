---
title: "TextShape"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa una forma de texto."
type: docs
weight: 18
url: /es/java/com.aspose.imaging.shapes/textshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.RectangleProjectedShape](../../com.aspose.imaging.shapes/rectangleprojectedshape)
```
public final class TextShape extends RectangleProjectedShape
```

Representa una forma de texto.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextShape()](#TextShape--) | Inicializa una nueva instancia de la clase `TextShape`. |
| [TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)](#TextShape-java.lang.String-com.aspose.imaging.RectangleF-com.aspose.imaging.Font-com.aspose.imaging.StringFormat-) | Inicializa una nueva instancia de la clase `TextShape`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getText()](#getText--) | Obtiene o establece el texto dibujado. |
| [setText(String value)](#setText-java.lang.String-) | Obtiene o establece el texto dibujado. |
| [getFont()](#getFont--) | Obtiene o establece la fuente utilizada para dibujar el texto. |
| [setFont(Font value)](#setFont-com.aspose.imaging.Font-) | Obtiene o establece la fuente utilizada para dibujar el texto. |
| [getTextFormat()](#getTextFormat--) | Obtiene o establece el formato del texto. |
| [setTextFormat(StringFormat value)](#setTextFormat-com.aspose.imaging.StringFormat-) | Obtiene o establece el formato del texto. |
| [getCenter()](#getCenter--) | Obtiene el centro de la forma. |
| [getBounds()](#getBounds--) | Obtiene los límites del objeto. |
| [getSegments()](#getSegments--) | Obtiene los segmentos de la forma. |
| [hasSegments()](#hasSegments--) | Obtiene un valor que indica si la forma tiene segmentos. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Obtiene los límites del objeto. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Obtiene los límites del objeto. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Aplica la transformación especificada a la forma. |
| [equals(Object o)](#equals-java.lang.Object-) | Comprueba si los objetos son iguales. |
| [hashCode()](#hashCode--) | Obtiene el código hash del objeto actual. |
### TextShape() {#TextShape--}
```
public TextShape()
```


Inicializa una nueva instancia de la clase `TextShape`.

### TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat) {#TextShape-java.lang.String-com.aspose.imaging.RectangleF-com.aspose.imaging.Font-com.aspose.imaging.StringFormat-}
```
public TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)
```


Inicializa una nueva instancia de la clase `TextShape`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | El texto a dibujar. |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | El rectángulo de texto. |
| font | [Font](../../com.aspose.imaging/font) | La fuente a usar. |
| stringFormat | [StringFormat](../../com.aspose.imaging/stringformat) | El formato de cadena. |

### getText() {#getText--}
```
public String getText()
```


Obtiene o establece el texto dibujado.

Valor: El texto dibujado.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Obtiene o establece el texto dibujado.

Valor: El texto dibujado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getFont() {#getFont--}
```
public Font getFont()
```


Obtiene o establece la fuente utilizada para dibujar el texto.

Valor: La fuente utilizada para dibujar el texto.

**Returns:**
[Font](../../com.aspose.imaging/font)
### setFont(Font value) {#setFont-com.aspose.imaging.Font-}
```
public void setFont(Font value)
```


Obtiene o establece la fuente utilizada para dibujar el texto.

Valor: La fuente utilizada para dibujar el texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Font](../../com.aspose.imaging/font) |  |

### getTextFormat() {#getTextFormat--}
```
public StringFormat getTextFormat()
```


Obtiene o establece el formato del texto.

Valor: El formato de texto.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat)
### setTextFormat(StringFormat value) {#setTextFormat-com.aspose.imaging.StringFormat-}
```
public void setTextFormat(StringFormat value)
```


Obtiene o establece el formato del texto.

Valor: El formato de texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [StringFormat](../../com.aspose.imaging/stringformat) |  |

### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Obtiene el centro de la forma.

Valor: El centro de la forma.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Obtiene los límites del objeto.

Valor: Los límites del objeto.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Obtiene los segmentos de la forma.

Valor: Los segmentos de la forma.

**Returns:**
com.aspose.imaging.ShapeSegment[]
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Obtiene un valor que indica si la forma tiene segmentos.

Valor: `True` si la forma tiene segmentos; de lo contrario, `false`.

**Returns:**
boolean
### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Obtiene los límites del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La matriz a aplicar antes de que se calculen los límites. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Obtiene los límites del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La matriz a aplicar antes de que se calculen los límites. |
| pen | [Pen](../../com.aspose.imaging/pen) | El lápiz a usar para el objeto. Esto puede influir en el tamaño de los límites del objeto. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


Aplica la transformación especificada a la forma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | La transformación a aplicar. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Comprueba si los objetos son iguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| o | java.lang.Object | El otro objeto. |

**Returns:**
boolean - El resultado de la comparación de igualdad.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtiene el código hash del objeto actual.

**Returns:**
int - El código hash.
