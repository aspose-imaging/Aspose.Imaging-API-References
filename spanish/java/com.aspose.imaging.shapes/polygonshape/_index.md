---
title: "PolygonShape"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa una forma de polígono."
type: docs
weight: 15
url: /es/java/com.aspose.imaging.shapes/polygonshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape)

**All Implemented Interfaces:**
[com.aspose.imaging.IOrderedShape](../../com.aspose.imaging/iorderedshape)
```
public class PolygonShape extends Shape implements IOrderedShape
```

Representa una forma de polígono.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PolygonShape()](#PolygonShape--) | Inicializa una nueva instancia de la clase `PolygonShape`. |
| [PolygonShape(PointF[] points)](#PolygonShape-com.aspose.imaging.PointF---) | Inicializa una nueva instancia de la clase `PolygonShape`. |
| [PolygonShape(PointF[] points, boolean isClosed)](#PolygonShape-com.aspose.imaging.PointF---boolean-) | Inicializa una nueva instancia de la clase `PolygonShape`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPoints()](#getPoints--) | Obtiene o establece los puntos de la curva. |
| [setPoints(PointF[] value)](#setPoints-com.aspose.imaging.PointF---) | Obtiene o establece los puntos de la curva. |
| [isClosed()](#isClosed--) | Obtiene o establece un valor que indica si la forma está cerrada. |
| [setClosed(boolean value)](#setClosed-boolean-) | Obtiene o establece un valor que indica si la forma está cerrada. |
| [getBounds()](#getBounds--) | Obtiene los límites del objeto. |
| [getCenter()](#getCenter--) | Obtiene el centro de la forma. |
| [getSegments()](#getSegments--) | Obtiene los segmentos de la forma. |
| [hasSegments()](#hasSegments--) | Obtiene un valor que indica si la forma tiene segmentos. |
| [getStartPoint()](#getStartPoint--) | Obtiene el punto inicial de la forma. |
| [getEndPoint()](#getEndPoint--) | Obtiene el punto final de la forma. |
| [reverse()](#reverse--) | Invierte el orden de los puntos de esta forma. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Obtiene los límites del objeto. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Obtiene los límites del objeto. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Aplica la transformación especificada a la forma. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el objeto especificado es igual al objeto actual. |
| [hashCode()](#hashCode--) | Sirve como la función hash predeterminada. |

## Example: This example creates a new Image and draws a variety of shapes using Figures and GraphicsPath o...
Este ejemplo crea una nueva Image y dibuja una variedad de formas usando Figures y GraphicsPath en la superficie de la Image.
``` java
//Crea una instancia de BmpOptions y establece sus diversas propiedades.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//Crea una instancia de FileCreateSource y asígnala como Source para la instancia de BmpOptions
//El segundo parámetro Boolean determina si el archivo a crear es IsTemporal o no
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\output.bmp", false));

//Crear una instancia de Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //Crear e inicializar una instancia de la clase Graphics
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //Borrar la superficie de Graphics
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //Crear una instancia de la clase GraphicsPath
    com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

    //Crear una instancia de la clase Figure
    com.aspose.imaging.Figure figure1 = new com.aspose.imaging.Figure();

    //Agregar Shape al objeto Figure.
    figure1.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
    figure1.addShape(new com.aspose.imaging.shapes.PieShape(
            new com.aspose.imaging.RectangleF(
                    new com.aspose.imaging.PointF(110, 110),
                    new com.aspose.imaging.SizeF(200, 200)), 0, 90));

    //Crear una instancia de la clase Figure
    com.aspose.imaging.Figure figure2 = new com.aspose.imaging.Figure();

    //Agregar Shape al objeto Figure.
    figure2.addShape(new com.aspose.imaging.shapes.ArcShape(new com.aspose.imaging.RectangleF(10, 10, 300, 300), 0, 45));
    figure2.addShape(new com.aspose.imaging.shapes.PolygonShape(
            new com.aspose.imaging.PointF[]
                    {
                            new com.aspose.imaging.PointF(150, 10),
                            new com.aspose.imaging.PointF(150, 200),
                            new com.aspose.imaging.PointF(250, 300),
                            new com.aspose.imaging.PointF(350, 400)}, true));
    figure2.addShape(new com.aspose.imaging.shapes.RectangleShape(
            new com.aspose.imaging.RectangleF(
                    new com.aspose.imaging.PointF(250, 250),
                    new com.aspose.imaging.SizeF(200, 200))));

    //Agregar el objeto Figure a GraphicsPath
    graphicspath.addFigures(new com.aspose.imaging.Figure[]{figure1, figure2});

    //Dibujar la ruta con un objeto Pen de color Negro
    graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

    // guardar todos los cambios.
    image.save();
} finally {
    image.dispose();
}
```

### PolygonShape() {#PolygonShape--}
```
public PolygonShape()
```


Inicializa una nueva instancia de la clase `PolygonShape`.

### PolygonShape(PointF[] points) {#PolygonShape-com.aspose.imaging.PointF---}
```
public PolygonShape(PointF[] points)
```


Inicializa una nueva instancia de la clase `PolygonShape`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | La matriz de puntos. |

### PolygonShape(PointF[] points, boolean isClosed) {#PolygonShape-com.aspose.imaging.PointF---boolean-}
```
public PolygonShape(PointF[] points, boolean isClosed)
```


Inicializa una nueva instancia de la clase `PolygonShape`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | La matriz de puntos. |
| isClosed | boolean | Si se establece en `true` el polígono está cerrado. |

### getPoints() {#getPoints--}
```
public PointF[] getPoints()
```


Obtiene o establece los puntos de la curva.

Valor: Los puntos de la curva.

**Returns:**
com.aspose.imaging.PointF[]
### setPoints(PointF[] value) {#setPoints-com.aspose.imaging.PointF---}
```
public void setPoints(PointF[] value)
```


Obtiene o establece los puntos de la curva.

Valor: Los puntos de la curva.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

### isClosed() {#isClosed--}
```
public boolean isClosed()
```


Obtiene o establece un valor que indica si la forma está cerrada.

Valor: `true` si la forma está cerrada; de lo contrario, `false`.

**Returns:**
boolean
### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Obtiene o establece un valor que indica si la forma está cerrada.

Valor: `true` si la forma está cerrada; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Obtiene los límites del objeto.

Valor: Los límites del objeto.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Obtiene el centro de la forma.

Valor: El centro de la forma.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
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
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Obtiene el punto inicial de la forma.

Valor: El punto inicial de la forma.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getEndPoint() {#getEndPoint--}
```
public PointF getEndPoint()
```


Obtiene el punto final de la forma.

Valor: El punto final de la forma.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### reverse() {#reverse--}
```
public void reverse()
```


Invierte el orden de los puntos de esta forma.

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

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si el objeto especificado es igual al objeto actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El objeto comparado. |

**Returns:**
boolean - El resultado de equals
### hashCode() {#hashCode--}
```
public int hashCode()
```


Sirve como la función hash predeterminada.

**Returns:**
int - Un código hash para el objeto actual.
