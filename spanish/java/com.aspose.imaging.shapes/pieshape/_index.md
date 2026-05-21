---
title: "PieShape"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa una forma de sector."
type: docs
weight: 14
url: /es/java/com.aspose.imaging.shapes/pieshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.RectangleProjectedShape](../../com.aspose.imaging.shapes/rectangleprojectedshape), [com.aspose.imaging.shapes.RectangleShape](../../com.aspose.imaging.shapes/rectangleshape), [com.aspose.imaging.shapes.EllipseShape](../../com.aspose.imaging.shapes/ellipseshape)
```
public class PieShape extends EllipseShape
```

Representa una forma de sector.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PieShape()](#PieShape--) | Inicializa una nueva instancia de la clase `PieShape`. |
| [PieShape(RectangleF rectangle, float startAngle, float sweepAngle)](#PieShape-com.aspose.imaging.RectangleF-float-float-) | Inicializa una nueva instancia de la clase `PieShape`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getStartAngle()](#getStartAngle--) | Obtiene o establece el ángulo de inicio. |
| [setStartAngle(float value)](#setStartAngle-float-) | Obtiene o establece el ángulo de inicio. |
| [getSweepAngle()](#getSweepAngle--) | Obtiene o establece el ángulo de barrido. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Obtiene o establece el ángulo de barrido. |
| [getSegments()](#getSegments--) | Obtiene los segmentos de la forma. |
| [equals(Object o)](#equals-java.lang.Object-) | Comprueba si los objetos son iguales. |
| [hashCode()](#hashCode--) | Obtiene el código hash del objeto actual. |

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

### PieShape() {#PieShape--}
```
public PieShape()
```


Inicializa una nueva instancia de la clase `PieShape`.

### PieShape(RectangleF rectangle, float startAngle, float sweepAngle) {#PieShape-com.aspose.imaging.RectangleF-float-float-}
```
public PieShape(RectangleF rectangle, float startAngle, float sweepAngle)
```


Inicializa una nueva instancia de la clase `PieShape`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | El rectángulo. |
| startAngle | float | El ángulo de inicio. |
| sweepAngle | float | El ángulo de barrido. |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Obtiene o establece el ángulo de inicio.

Valor: El ángulo de inicio.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Obtiene o establece el ángulo de inicio.

Valor: El ángulo de inicio.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Obtiene o establece el ángulo de barrido.

Valor: El ángulo de barrido.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Obtiene o establece el ángulo de barrido.

Valor: El ángulo de barrido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Obtiene los segmentos de la forma.

Valor: Los segmentos de la forma.

**Returns:**
com.aspose.imaging.ShapeSegment[]
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
