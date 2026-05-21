---
title: "GraphicsPath"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa una serie de líneas y curvas conectadas."
type: docs
weight: 52
url: /es/java/com.aspose.imaging/graphicspath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds)
```
public final class GraphicsPath extends ObjectWithBounds
```

Representa una serie de líneas y curvas conectadas. Esta clase no puede ser heredada.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [GraphicsPath()](#GraphicsPath--) | Inicializa una nueva instancia de la clase `GraphicsPath`. |
| [GraphicsPath(Figure[] figures)](#GraphicsPath-com.aspose.imaging.Figure---) | Inicializa una nueva instancia de la clase `GraphicsPath`. |
| [GraphicsPath(Figure[] figures, int fillMode)](#GraphicsPath-com.aspose.imaging.Figure---int-) | Inicializa una nueva instancia de la clase `GraphicsPath`. |
| [GraphicsPath(int fillMode)](#GraphicsPath-int-) | Inicializa una nueva instancia de la clase `GraphicsPath`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFillMode()](#getFillMode--) | Obtiene una enumeración `com.aspose.imaging.FillMode` que determina cómo se rellenan los interiores de las formas en este `com.aspose.imaging.GraphicsPath`. |
| [setFillMode(int value)](#setFillMode-int-) | Establece una enumeración `com.aspose.imaging.FillMode` que determina cómo se rellenan los interiores de las formas en este `com.aspose.imaging.GraphicsPath`. |
| [getFigures()](#getFigures--) | Obtiene las figuras de la ruta. |
| [getBounds()](#getBounds--) | Obtiene o establece los límites del objeto. |
| [reset()](#reset--) | Vacía la ruta gráfica y establece el `com.aspose.imaging.FillMode` a `F:com.aspose.imaging.fillMode.alternate`. |
| [reverse()](#reverse--) | Invierte el orden de las figuras, formas y puntos en cada forma de este `com.aspose.imaging.graphicsPath`. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Indica si el punto especificado está contenido dentro de este `com.aspose.imaging.graphicsPath`. |
| [isVisible(PointF point)](#isVisible-com.aspose.imaging.PointF-) | Indica si el punto especificado está contenido dentro de este `com.aspose.imaging.graphicsPath`. |
| [isVisible(int x, int y)](#isVisible-int-int-) | Indica si el punto especificado está contenido dentro de este `com.aspose.imaging.graphicsPath`. |
| [isVisible(Point point)](#isVisible-com.aspose.imaging.Point-) | Indica si el punto especificado está contenido dentro de este `com.aspose.imaging.graphicsPath`. |
| [isVisible(float x, float y, Graphics graphics)](#isVisible-float-float-com.aspose.imaging.Graphics-) | Indica si el punto especificado está contenido dentro de este `com.aspose.imaging.GraphicsPath` en la región de recorte visible del `com.aspose.imaging.graphics` especificado. |
| [isVisible(PointF pt, Graphics graphics)](#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-) | Indica si el punto especificado está contenido dentro de este `com.aspose.imaging.graphicsPath`. |
| [isVisible(int x, int y, Graphics graphics)](#isVisible-int-int-com.aspose.imaging.Graphics-) | Indica si el punto especificado está contenido dentro de este `com.aspose.imaging.GraphicsPath`, usando el `com.aspose.imaging.graphics` especificado. |
| [isVisible(Point pt, Graphics graphics)](#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-) | Indica si el punto especificado está contenido dentro de este `com.aspose.imaging.graphicsPath`. |
| [isOutlineVisible(float x, float y, Pen pen)](#isOutlineVisible-float-float-com.aspose.imaging.Pen-) | Indica si el punto especificado está contenido dentro (bajo) del contorno de este `com.aspose.imaging.GraphicsPath` cuando se dibuja con el `com.aspose.imaging.pen` especificado. |
| [isOutlineVisible(PointF point, Pen pen)](#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-) | Indica si el punto especificado está contenido dentro (bajo) del contorno de este `com.aspose.imaging.GraphicsPath` cuando se dibuja con el `com.aspose.imaging.pen` especificado. |
| [isOutlineVisible(float x, float y, Pen pen, Graphics graphics)](#isOutlineVisible-float-float-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Indica si el punto especificado está contenido dentro (bajo) del contorno de este `com.aspose.imaging.GraphicsPath` cuando se dibuja con el `com.aspose.imaging.Pen` especificado y usando el `com.aspose.imaging.graphics` especificado. |
| [isOutlineVisible(PointF pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Indica si el punto especificado está contenido dentro (bajo) del contorno de este `com.aspose.imaging.GraphicsPath` cuando se dibuja con el `com.aspose.imaging.Pen` especificado y usando el `com.aspose.imaging.graphics` especificado. |
| [isOutlineVisible(int x, int y, Pen pen)](#isOutlineVisible-int-int-com.aspose.imaging.Pen-) | Indica si el punto especificado está contenido dentro (bajo) del contorno de este `com.aspose.imaging.GraphicsPath` cuando se dibuja con el `com.aspose.imaging.pen` especificado. |
| [isOutlineVisible(Point point, Pen pen)](#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-) | Indica si el punto especificado está contenido dentro (bajo) del contorno de este `com.aspose.imaging.GraphicsPath` cuando se dibuja con el `com.aspose.imaging.pen` especificado. |
| [isOutlineVisible(int x, int y, Pen pen, Graphics graphics)](#isOutlineVisible-int-int-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Indica si el punto especificado está contenido dentro (bajo) del contorno de este `com.aspose.imaging.GraphicsPath` cuando se dibuja con el `com.aspose.imaging.Pen` especificado y usando el `com.aspose.imaging.graphics` especificado. |
| [isOutlineVisible(Point pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Indica si el punto especificado está contenido dentro (bajo) del contorno de este `com.aspose.imaging.GraphicsPath` cuando se dibuja con el `com.aspose.imaging.Pen` especificado y usando el `com.aspose.imaging.graphics` especificado. |
| [flatten()](#flatten--) | Convierte cada curva de esta ruta en una secuencia de segmentos de línea conectados. |
| [flatten(Matrix matrix)](#flatten-com.aspose.imaging.Matrix-) | Aplica la transformación especificada y luego convierte cada curva de este `com.aspose.imaging.GraphicsPath` en una secuencia de segmentos de línea conectados. |
| [flatten(Matrix matrix, float flatness)](#flatten-com.aspose.imaging.Matrix-float-) | Convierte cada curva de este `com.aspose.imaging.GraphicsPath` en una secuencia de segmentos de línea conectados. |
| [widen(Pen pen)](#widen-com.aspose.imaging.Pen-) | Añade un contorno adicional a la ruta. |
| [widen(Pen pen, Matrix matrix)](#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-) | Añade un contorno adicional al `com.aspose.imaging.graphicsPath`. |
| [widen(Pen pen, Matrix matrix, float flatness)](#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-float-) | Reemplaza este `com.aspose.imaging.GraphicsPath` con curvas que encierran el área que se rellena cuando esta ruta se dibuja con el pen especificado. |
| [warp(PointF[] destPoints, RectangleF srcRect)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-) | Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este `com.aspose.imaging.graphicsPath`. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-) | Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este `com.aspose.imaging.graphicsPath`. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-) | Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este `com.aspose.imaging.graphicsPath`. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-float-) | Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este `com.aspose.imaging.graphicsPath`. |
| [addFigure(Figure figure)](#addFigure-com.aspose.imaging.Figure-) | Añade una nueva figura. |
| [addFigures(Figure[] figures)](#addFigures-com.aspose.imaging.Figure---) | Añade nuevas figuras. |
| [removeFigure(Figure figure)](#removeFigure-com.aspose.imaging.Figure-) | Elimina una figura. |
| [removeFigures(Figure[] figures)](#removeFigures-com.aspose.imaging.Figure---) | Elimina figuras. |
| [addPath(GraphicsPath addingPath)](#addPath-com.aspose.imaging.GraphicsPath-) | Añade al final el `com.aspose.imaging.GraphicsPath` especificado a esta ruta. |
| [addPath(GraphicsPath addingPath, boolean connect)](#addPath-com.aspose.imaging.GraphicsPath-boolean-) | Añade al final el `com.aspose.imaging.GraphicsPath` especificado a esta ruta. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Obtiene los límites del objeto. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Obtiene los límites del objeto. |
| [deepClone()](#deepClone--) | Realiza una clonación profunda de esta ruta gráfica. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Aplica la transformación especificada a la forma. |
| [equals(Object o)](#equals-java.lang.Object-) | Comprueba si los objetos son iguales. |
| [hashCode()](#hashCode--) | Obtiene el código hash del objeto actual. |

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

### GraphicsPath() {#GraphicsPath--}
```
public GraphicsPath()
```


Inicializa una nueva instancia de la clase `GraphicsPath`.

### GraphicsPath(Figure[] figures) {#GraphicsPath-com.aspose.imaging.Figure---}
```
public GraphicsPath(Figure[] figures)
```


Inicializa una nueva instancia de la clase `GraphicsPath`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | Las figuras desde las que inicializar. |

### GraphicsPath(Figure[] figures, int fillMode) {#GraphicsPath-com.aspose.imaging.Figure---int-}
```
public GraphicsPath(Figure[] figures, int fillMode)
```


Inicializa una nueva instancia de la clase `GraphicsPath`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | Las figuras desde las que inicializar. |
| fillMode | int | El modo de relleno. |

### GraphicsPath(int fillMode) {#GraphicsPath-int-}
```
public GraphicsPath(int fillMode)
```


Inicializa una nueva instancia de la clase `GraphicsPath`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fillMode | int | El modo de relleno. |

### getFillMode() {#getFillMode--}
```
public int getFillMode()
```


Obtiene una enumeración `com.aspose.imaging.FillMode` que determina cómo se rellenan los interiores de las formas en este `com.aspose.imaging.GraphicsPath`.

**Returns:**
int - El modo de relleno. Una enumeración `com.aspose.imaging.FillMode` que especifica cómo se rellenan los interiores de las formas en este `com.aspose.imaging.GraphicsPath`.
### setFillMode(int value) {#setFillMode-int-}
```
public void setFillMode(int value)
```


Establece una enumeración `com.aspose.imaging.FillMode` que determina cómo se rellenan los interiores de las formas en este `com.aspose.imaging.GraphicsPath`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El modo de relleno. |

### getFigures() {#getFigures--}
```
public Figure[] getFigures()
```


Obtiene las figuras de la ruta.

**Returns:**
com.aspose.imaging.Figure[] - Las figuras de la ruta.
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Obtiene o establece los límites del objeto.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The object's bounds.
### reset() {#reset--}
```
public void reset()
```


Vacía la ruta gráfica y establece el `com.aspose.imaging.FillMode` a `F:com.aspose.imaging.fillMode.alternate`.

### reverse() {#reverse--}
```
public void reverse()
```


Invierte el orden de las figuras, formas y puntos en cada forma de este `com.aspose.imaging.graphicsPath`.

### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Indica si el punto especificado está contenido dentro de este `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro de este `com.aspose.imaging.GraphicsPath`; de lo contrario, false.
### isVisible(PointF point) {#isVisible-com.aspose.imaging.PointF-}
```
public boolean isVisible(PointF point)
```


Indica si el punto especificado está contenido dentro de este `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Un `com.aspose.imaging.PointF` que representa el punto a probar. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro de este `com.aspose.imaging.GraphicsPath`; de lo contrario, false.
### isVisible(int x, int y) {#isVisible-int-int-}
```
public boolean isVisible(int x, int y)
```


Indica si el punto especificado está contenido dentro de este `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x del punto a probar. |
| y | int | La coordenada y del punto a probar. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro de este `com.aspose.imaging.GraphicsPath`; de lo contrario, false.
### isVisible(Point point) {#isVisible-com.aspose.imaging.Point-}
```
public boolean isVisible(Point point)
```


Indica si el punto especificado está contenido dentro de este `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Un `com.aspose.imaging.Point` que representa el punto a probar. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro de este `com.aspose.imaging.GraphicsPath`; de lo contrario, false.
### isVisible(float x, float y, Graphics graphics) {#isVisible-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, Graphics graphics)
```


Indica si el punto especificado está contenido dentro de este `com.aspose.imaging.GraphicsPath` en la región de recorte visible del `com.aspose.imaging.graphics` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | El `com.aspose.imaging.Graphics` para el cual probar la visibilidad. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro de este `com.aspose.imaging.GraphicsPath`; de lo contrario, false.
### isVisible(PointF pt, Graphics graphics) {#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(PointF pt, Graphics graphics)
```


Indica si el punto especificado está contenido dentro de este `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.imaging/pointf) | Un `com.aspose.imaging.PointF` que representa el punto a probar. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | El `com.aspose.imaging.Graphics` para el cual probar la visibilidad. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro de esto; de lo contrario, false.
### isVisible(int x, int y, Graphics graphics) {#isVisible-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, Graphics graphics)
```


Indica si el punto especificado está contenido dentro de este `com.aspose.imaging.GraphicsPath`, usando el `com.aspose.imaging.graphics` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x del punto a probar. |
| y | int | La coordenada y del punto a probar. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | El `com.aspose.imaging.Graphics` para el cual probar la visibilidad. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro de este `com.aspose.imaging.GraphicsPath`; de lo contrario, false.
### isVisible(Point pt, Graphics graphics) {#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Point pt, Graphics graphics)
```


Indica si el punto especificado está contenido dentro de este `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pt | [Point](../../com.aspose.imaging/point) | Un `com.aspose.imaging.Point` que representa el punto a probar. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | El `com.aspose.imaging.Graphics` para el cual probar la visibilidad. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro de este `com.aspose.imaging.GraphicsPath`; de lo contrario, false.
### isOutlineVisible(float x, float y, Pen pen) {#isOutlineVisible-float-float-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(float x, float y, Pen pen)
```


Indica si el punto especificado está contenido dentro (bajo) del contorno de este `com.aspose.imaging.GraphicsPath` cuando se dibuja con el `com.aspose.imaging.pen` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |
| pen | [Pen](../../com.aspose.imaging/pen) | El `com.aspose.imaging.Pen` a probar. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro del contorno de este `com.aspose.imaging.GraphicsPath` cuando se dibuja con el `com.aspose.imaging.Pen` especificado; de lo contrario, false.
### isOutlineVisible(PointF point, Pen pen) {#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(PointF point, Pen pen)
```


Indica si el punto especificado está contenido dentro (bajo) del contorno de este `com.aspose.imaging.GraphicsPath` cuando se dibuja con el `com.aspose.imaging.pen` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Un `com.aspose.imaging.PointF` que especifica la ubicación a probar. |
| pen | [Pen](../../com.aspose.imaging/pen) | El `com.aspose.imaging.Pen` a probar. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro del contorno de este `com.aspose.imaging.GraphicsPath` cuando se dibuja con el `com.aspose.imaging.Pen` especificado; de lo contrario, false.
### isOutlineVisible(float x, float y, Pen pen, Graphics graphics) {#isOutlineVisible-float-float-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(float x, float y, Pen pen, Graphics graphics)
```


Indica si el punto especificado está contenido dentro (bajo) del contorno de este `com.aspose.imaging.GraphicsPath` cuando se dibuja con el `com.aspose.imaging.Pen` especificado y usando el `com.aspose.imaging.graphics` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del punto a probar. |
| y | float | La coordenada y del punto a probar. |
| pen | [Pen](../../com.aspose.imaging/pen) | El `com.aspose.imaging.Pen` a probar. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | El `com.aspose.imaging.Graphics` para el cual probar la visibilidad. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro (bajo) del contorno de este `com.aspose.imaging.GraphicsPath` tal como se dibuja con el `com.aspose.imaging.Pen` especificado; de lo contrario, false.
### isOutlineVisible(PointF pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(PointF pt, Pen pen, Graphics graphics)
```


Indica si el punto especificado está contenido dentro (bajo) del contorno de este `com.aspose.imaging.GraphicsPath` cuando se dibuja con el `com.aspose.imaging.Pen` especificado y usando el `com.aspose.imaging.graphics` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.imaging/pointf) | Un `com.aspose.imaging.PointF` que especifica la ubicación a probar. |
| pen | [Pen](../../com.aspose.imaging/pen) | El `com.aspose.imaging.Pen` a probar. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | El `com.aspose.imaging.Graphics` para el cual probar la visibilidad. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro (bajo) del contorno de este `com.aspose.imaging.GraphicsPath` tal como se dibuja con el `com.aspose.imaging.Pen` especificado; de lo contrario, false.
### isOutlineVisible(int x, int y, Pen pen) {#isOutlineVisible-int-int-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(int x, int y, Pen pen)
```


Indica si el punto especificado está contenido dentro (bajo) del contorno de este `com.aspose.imaging.GraphicsPath` cuando se dibuja con el `com.aspose.imaging.pen` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x del punto a probar. |
| y | int | La coordenada y del punto a probar. |
| pen | [Pen](../../com.aspose.imaging/pen) | El `com.aspose.imaging.Pen` a probar. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro del contorno de este `com.aspose.imaging.GraphicsPath` cuando se dibuja con el `com.aspose.imaging.Pen` especificado; de lo contrario, false.
### isOutlineVisible(Point point, Pen pen) {#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(Point point, Pen pen)
```


Indica si el punto especificado está contenido dentro (bajo) del contorno de este `com.aspose.imaging.GraphicsPath` cuando se dibuja con el `com.aspose.imaging.pen` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Un `com.aspose.imaging.Point` que especifica la ubicación a probar. |
| pen | [Pen](../../com.aspose.imaging/pen) | El `com.aspose.imaging.Pen` a probar. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro del contorno de este `com.aspose.imaging.GraphicsPath` cuando se dibuja con el `com.aspose.imaging.Pen` especificado; de lo contrario, false.
### isOutlineVisible(int x, int y, Pen pen, Graphics graphics) {#isOutlineVisible-int-int-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(int x, int y, Pen pen, Graphics graphics)
```


Indica si el punto especificado está contenido dentro (bajo) del contorno de este `com.aspose.imaging.GraphicsPath` cuando se dibuja con el `com.aspose.imaging.Pen` especificado y usando el `com.aspose.imaging.graphics` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x del punto a probar. |
| y | int | La coordenada y del punto a probar. |
| pen | [Pen](../../com.aspose.imaging/pen) | El `com.aspose.imaging.Pen` a probar. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | El `com.aspose.imaging.Graphics` para el cual probar la visibilidad. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro del contorno de este `com.aspose.imaging.GraphicsPath` tal como se dibuja con el `com.aspose.imaging.Pen` especificado; de lo contrario, false.
### isOutlineVisible(Point pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(Point pt, Pen pen, Graphics graphics)
```


Indica si el punto especificado está contenido dentro (bajo) del contorno de este `com.aspose.imaging.GraphicsPath` cuando se dibuja con el `com.aspose.imaging.Pen` especificado y usando el `com.aspose.imaging.graphics` especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pt | [Point](../../com.aspose.imaging/point) | Un `com.aspose.imaging.Point` que especifica la ubicación a probar. |
| pen | [Pen](../../com.aspose.imaging/pen) | El `com.aspose.imaging.Pen` a probar. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | El `com.aspose.imaging.Graphics` para el cual probar la visibilidad. |

**Returns:**
boolean - Este método devuelve true si el punto especificado está contenido dentro del contorno de este `com.aspose.imaging.GraphicsPath` tal como se dibuja con el `com.aspose.imaging.Pen` especificado; de lo contrario, false.
### flatten() {#flatten--}
```
public void flatten()
```


Convierte cada curva de esta ruta en una secuencia de segmentos de línea conectados.

### flatten(Matrix matrix) {#flatten-com.aspose.imaging.Matrix-}
```
public void flatten(Matrix matrix)
```


Aplica la transformación especificada y luego convierte cada curva de este `com.aspose.imaging.GraphicsPath` en una secuencia de segmentos de línea conectados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Una `com.aspose.imaging.Matrix` mediante la cual transformar este `com.aspose.imaging.GraphicsPath` antes de aplanar. |

### flatten(Matrix matrix, float flatness) {#flatten-com.aspose.imaging.Matrix-float-}
```
public void flatten(Matrix matrix, float flatness)
```


Convierte cada curva de este `com.aspose.imaging.GraphicsPath` en una secuencia de segmentos de línea conectados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Una `com.aspose.imaging.Matrix` mediante la cual transformar este `com.aspose.imaging.GraphicsPath` antes de aplanar. |
| planitud | float | Especifica el error máximo permitido entre la curva y su aproximación aplanada. Un valor de 0.25 es el predeterminado. Reducir el valor de planitud aumentará el número de segmentos de línea en la aproximación. |

### widen(Pen pen) {#widen-com.aspose.imaging.Pen-}
```
public void widen(Pen pen)
```


Añade un contorno adicional a la ruta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Un `com.aspose.imaging.Pen` que especifica el ancho entre el contorno original de la ruta y el nuevo contorno que crea este método. |

### widen(Pen pen, Matrix matrix) {#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-}
```
public void widen(Pen pen, Matrix matrix)
```


Añade un contorno adicional al `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Un `com.aspose.imaging.Pen` que especifica el ancho entre el contorno original de la ruta y el nuevo contorno que crea este método. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Una `com.aspose.imaging.Matrix` que especifica una transformación a aplicar a la ruta antes de ensancharla. |

### widen(Pen pen, Matrix matrix, float flatness) {#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-float-}
```
public void widen(Pen pen, Matrix matrix, float flatness)
```


Reemplaza este `com.aspose.imaging.GraphicsPath` con curvas que encierran el área que se rellena cuando esta ruta se dibuja con el pen especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Un `com.aspose.imaging.Pen` que especifica el ancho entre el contorno original de la ruta y el nuevo contorno que crea este método. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Una `com.aspose.imaging.Matrix` que especifica una transformación a aplicar a la ruta antes de ensancharla. |
| planitud | float | Un valor que especifica la planitud para curvas. |

### warp(PointF[] destPoints, RectangleF srcRect) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-}
```
public void warp(PointF[] destPoints, RectangleF srcRect)
```


Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | Una matriz de estructuras `com.aspose.imaging.PointF` que definen un paralelogramo al que se transforma el rectángulo definido por `srcRect`. La matriz puede contener tres o cuatro elementos. Si la matriz contiene tres elementos, la esquina inferior derecha del paralelogramo se deduce de los tres primeros puntos. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | Un `com.aspose.imaging.RectangleF` que representa el rectángulo que se transforma al paralelogramo definido por `destPoints`. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```


Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | Una matriz de estructuras `com.aspose.imaging.PointF` que definen un paralelogramo al que se transforma el rectángulo definido por `srcRect`. La matriz puede contener tres o cuatro elementos. Si la matriz contiene tres elementos, la esquina inferior derecha del paralelogramo se deduce de los tres primeros puntos. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | Un `com.aspose.imaging.RectangleF` que representa el rectángulo que se transforma al paralelogramo definido por `destPoints`. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Una `com.aspose.imaging.Matrix` que especifica una transformación geométrica a aplicar a la ruta. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)
```


Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | Una matriz de estructuras `com.aspose.imaging.PointF` que define un paralelogramo al que se transforma el rectángulo definido por `srcRect`. La matriz puede contener tres o cuatro elementos. Si la matriz contiene tres elementos, la esquina inferior derecha del paralelogramo se deduce de los tres primeros puntos. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | Un `com.aspose.imaging.RectangleF` que representa el rectángulo que se transforma al paralelogramo definido por `destPoints`. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Una `com.aspose.imaging.Matrix` que especifica una transformación geométrica a aplicar a la ruta. |
| warpMode | int | Una enumeración `com.aspose.imaging.WarpMode` que especifica si esta operación de deformación usa modo perspectiva o bilineal. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-float-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)
```


Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | Una matriz de estructuras `com.aspose.imaging.PointF` que definen un paralelogramo al que se transforma el rectángulo definido por `srcRect`. La matriz puede contener tres o cuatro elementos. Si la matriz contiene tres elementos, la esquina inferior derecha del paralelogramo se deduce de los tres primeros puntos. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | Un `com.aspose.imaging.RectangleF` que representa el rectángulo que se transforma al paralelogramo definido por `destPoints`. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Una `com.aspose.imaging.Matrix` que especifica una transformación geométrica a aplicar a la ruta. |
| warpMode | int | Una enumeración `com.aspose.imaging.WarpMode` que especifica si esta operación de deformación usa modo perspectiva o bilineal. |
| planitud | float | Un valor de 0 a 1 que especifica cuán plana es la ruta resultante. Para obtener más información, consulte los métodos `com.aspose.imaging.GraphicsPath.flatten`. |

### addFigure(Figure figure) {#addFigure-com.aspose.imaging.Figure-}
```
public void addFigure(Figure figure)
```


Añade una nueva figura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.imaging/figure) | La figura a añadir. |


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

### addFigures(Figure[] figures) {#addFigures-com.aspose.imaging.Figure---}
```
public void addFigures(Figure[] figures)
```


Añade nuevas figuras.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | Las figuras a añadir. |


**Example: This example creates a new Image and draws a variety of shapes using Figures and GraphicsPath o...**
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

### removeFigure(Figure figure) {#removeFigure-com.aspose.imaging.Figure-}
```
public void removeFigure(Figure figure)
```


Elimina una figura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.imaging/figure) | La figura a eliminar. |

### removeFigures(Figure[] figures) {#removeFigures-com.aspose.imaging.Figure---}
```
public void removeFigures(Figure[] figures)
```


Elimina figuras.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | Las figuras a eliminar. |

### addPath(GraphicsPath addingPath) {#addPath-com.aspose.imaging.GraphicsPath-}
```
public void addPath(GraphicsPath addingPath)
```


Añade al final el `com.aspose.imaging.GraphicsPath` especificado a esta ruta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | El `com.aspose.imaging.GraphicsPath` a añadir. |

### addPath(GraphicsPath addingPath, boolean connect) {#addPath-com.aspose.imaging.GraphicsPath-boolean-}
```
public void addPath(GraphicsPath addingPath, boolean connect)
```


Añade al final el `com.aspose.imaging.GraphicsPath` especificado a esta ruta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | El `com.aspose.imaging.GraphicsPath` a añadir. |
| conectar | boolean | Un valor Booleano que indica si la primera figura en la ruta añadida forma parte de la última figura en esta ruta. Un valor true indica que la primera figura en la ruta añadida forma parte de la última figura en esta ruta. Un valor false indica que la primera figura en la ruta añadida está separada de la última figura en esta ruta. |

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
### deepClone() {#deepClone--}
```
public GraphicsPath deepClone()
```


Realiza una clonación profunda de esta ruta gráfica.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - A deep clone of the graphics path.
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
