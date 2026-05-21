---
title: "Figure"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La figura."
type: docs
weight: 44
url: /es/java/com.aspose.imaging/figure/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds)
```
public class Figure extends ObjectWithBounds
```

La figura. Un contenedor para formas.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Figure()](#Figure--) | Inicializa una nueva instancia de [Figure](../../com.aspose.imaging/figure). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getShapes()](#getShapes--) | Obtiene las formas de la figura. |
| [getBounds()](#getBounds--) | Obtiene o establece los límites del objeto. |
| [isClosed()](#isClosed--) | Obtiene un valor que indica si esta figura está cerrada. |
| [setClosed(boolean value)](#setClosed-boolean-) | Establece un valor que indica si esta figura está cerrada. |
| [getSegments()](#getSegments--) | Obtiene todos los segmentos de la figura. |
| [addShape(Shape shape)](#addShape-com.aspose.imaging.Shape-) | Agrega una forma a la figura. |
| [addShapes(Shape[] shapes)](#addShapes-com.aspose.imaging.Shape---) | Agrega un rango de formas a la figura. |
| [removeShape(Shape shape)](#removeShape-com.aspose.imaging.Shape-) | Elimina una forma de la figura. |
| [removeShapes(Shape[] shapes)](#removeShapes-com.aspose.imaging.Shape---) | Elimina un rango de formas de la figura. |
| [reverse()](#reverse--) | Invierte el orden de las formas de esta figura y el orden de los puntos de las formas. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Obtiene los límites del objeto. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Obtiene los límites del objeto. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Aplica la transformación especificada a la forma. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el objeto especificado es igual al objeto actual. |
| [hashCode()](#hashCode--) | Sirve como la función hash predeterminada. |

## Example: This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface.
Estos ejemplos utilizan la clase GraphicsPath y la clase Graphics para crear y manipular Figuras en una superficie de Imagen. El ejemplo crea una nueva Imagen (de tipo Tiff) y dibuja rutas con la ayuda de la clase GraphicsPath. Al final se llama al método DrawPath expuesto por la clase Graphics para renderizar las rutas en la superficie.
``` java
// Crear una instancia de FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.tif", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Crear una instancia de TiffOptions y establecer sus diversas propiedades
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

    // Establecer la fuente para la instancia de ImageOptions
    tiffOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Crear una instancia de Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(tiffOptions, 500, 500);
    try {
        // Crear e inicializar una instancia de la clase Graphics
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Borrar la superficie de Graphics
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Crear una instancia de la clase GraphicsPath
        com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

        // Crear una instancia de la clase Figure
        com.aspose.imaging.Figure figure = new com.aspose.imaging.Figure();

        // Agregar Formas al objeto Figure
        figure.addShape(new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(10, 10, 300, 300)));
        figure.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
        figure.addShape(
                new com.aspose.imaging.shapes.PieShape(new com.aspose.imaging.RectangleF(
                        new com.aspose.imaging.PointF(250, 250),
                        new com.aspose.imaging.SizeF(200, 200)),
                        0, 45));

        // Agregar el objeto Figure a GraphicsPath
        graphicspath.addFigure(figure);

        // Dibujar la ruta con un objeto Pen de color Negro
        graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

        // Guardar todos los cambios.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### Figure() {#Figure--}
```
public Figure()
```


Inicializa una nueva instancia de [Figure](../../com.aspose.imaging/figure). Un constructor requerido para la deserialización JSON.

### getShapes() {#getShapes--}
```
public Shape[] getShapes()
```


Obtiene las formas de la figura.

**Returns:**
com.aspose.imaging.Shape[] - Las formas de la figura.
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Obtiene o establece los límites del objeto.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The object's bounds.
### isClosed() {#isClosed--}
```
public boolean isClosed()
```


Obtiene un valor que indica si esta figura está cerrada. Una figura cerrada solo hará una diferencia en el caso en que las primeras y últimas formas de la figura sean formas continuas. En tal caso, el primer punto de la primera forma se conectará mediante una línea recta desde el último punto de la última forma.

**Returns:**
boolean - `True` si esta figura está cerrada; de lo contrario, `false`.
### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Establece un valor que indica si esta figura está cerrada. Una figura cerrada solo hará una diferencia en el caso en que las primeras y últimas formas de la figura sean formas continuas. En tal caso, el primer punto de la primera forma se conectará mediante una línea recta desde el último punto de la última forma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | `True` si esta figura está cerrada; de lo contrario, `false`. |

### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Obtiene todos los segmentos de la figura.

**Returns:**
com.aspose.imaging.ShapeSegment[] - Los segmentos de la figura.
### addShape(Shape shape) {#addShape-com.aspose.imaging.Shape-}
```
public void addShape(Shape shape)
```


Agrega una forma a la figura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.imaging/shape) | La forma a agregar. |


**Example: This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface.**
Estos ejemplos utilizan la clase GraphicsPath y la clase Graphics para crear y manipular Figuras en una superficie de Imagen. El ejemplo crea una nueva Imagen (de tipo Tiff) y dibuja rutas con la ayuda de la clase GraphicsPath. Al final se llama al método DrawPath expuesto por la clase Graphics para renderizar las rutas en la superficie.
``` java
// Crear una instancia de FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.tif", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Crear una instancia de TiffOptions y establecer sus diversas propiedades
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

    // Establecer la fuente para la instancia de ImageOptions
    tiffOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Crear una instancia de Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(tiffOptions, 500, 500);
    try {
        // Crear e inicializar una instancia de la clase Graphics
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Borrar la superficie de Graphics
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Crear una instancia de la clase GraphicsPath
        com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

        // Crear una instancia de la clase Figure
        com.aspose.imaging.Figure figure = new com.aspose.imaging.Figure();

        // Agregar Formas al objeto Figure
        figure.addShape(new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(10, 10, 300, 300)));
        figure.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
        figure.addShape(
                new com.aspose.imaging.shapes.PieShape(new com.aspose.imaging.RectangleF(
                        new com.aspose.imaging.PointF(250, 250),
                        new com.aspose.imaging.SizeF(200, 200)),
                        0, 45));

        // Agregar el objeto Figure a GraphicsPath
        graphicspath.addFigure(figure);

        // Dibujar la ruta con un objeto Pen de color Negro
        graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

        // Guardar todos los cambios.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### addShapes(Shape[] shapes) {#addShapes-com.aspose.imaging.Shape---}
```
public void addShapes(Shape[] shapes)
```


Agrega un rango de formas a la figura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.imaging/shape) | Las formas a agregar. |

### removeShape(Shape shape) {#removeShape-com.aspose.imaging.Shape-}
```
public void removeShape(Shape shape)
```


Elimina una forma de la figura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.imaging/shape) | La forma a eliminar. |

### removeShapes(Shape[] shapes) {#removeShapes-com.aspose.imaging.Shape---}
```
public void removeShapes(Shape[] shapes)
```


Elimina un rango de formas de la figura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.imaging/shape) | El rango de formas a eliminar. |

### reverse() {#reverse--}
```
public void reverse()
```


Invierte el orden de las formas de esta figura y el orden de los puntos de las formas.

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
