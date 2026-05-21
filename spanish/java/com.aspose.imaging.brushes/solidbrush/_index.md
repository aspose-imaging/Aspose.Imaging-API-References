---
title: "SolidBrush"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El pincel sólido está destinado a dibujar continuamente con un color específico."
type: docs
weight: 17
url: /es/java/com.aspose.imaging.brushes/solidbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush)
```
public final class SolidBrush extends Brush
```

El pincel sólido está destinado a dibujar continuamente con un color específico. Esta clase no puede heredarse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [SolidBrush()](#SolidBrush--) | Inicializa una nueva instancia de la clase `SolidBrush`. |
| [SolidBrush(Color color)](#SolidBrush-com.aspose.imaging.Color-) | Inicializa una nueva instancia de la clase `SolidBrush`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getColor()](#getColor--) | Obtiene o establece el color del pincel. |
| [setColor(Color value)](#setColor-com.aspose.imaging.Color-) | Obtiene o establece el color del pincel. |
| [hashCode()](#hashCode--) |  |
| [equals(Object object)](#equals-java.lang.Object-) |  |

## Example: This example uses Graphics class to create primitive shapes on the Image surface.
Este ejemplo utiliza la clase Graphics para crear formas primitivas en la superficie de la Imagen. Para demostrar la operación, el ejemplo crea una nueva Imagen en formato PNG y dibuja formas primitivas en la superficie de la Imagen usando los métodos Draw expuestos por la clase Graphics.
``` java
// Crea una instancia de FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.png", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Crea una instancia de PngOptions y establece sus diversas propiedades
    com.aspose.imaging.imageoptions.PngOptions pngOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Establece la Fuente para PngOptions
    pngOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Crear una instancia de Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(pngOptions, 500, 500);
    try {
        // Crear e inicializar una instancia de la clase Graphics
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Borrar la superficie de Graphics
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Dibuja un arco especificando el objeto Pen que tiene el color Black com.aspose.imaging.Color,
        // un Rectángulo que rodea el arco, ángulo de inicio y ángulo de barrido
        graphics.drawArc(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2),
                new com.aspose.imaging.Rectangle(200, 200, 100, 200),
                0,
                300);

        // Dibuja una curva Bézier especificando el objeto Pen que tiene el color Blue com.aspose.imaging.Color y los puntos de coordenadas.
        graphics.drawBezier(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
                new com.aspose.imaging.Point(250, 100),
                new com.aspose.imaging.Point(300, 30),
                new com.aspose.imaging.Point(450, 100),
                new com.aspose.imaging.Point(235, 25));

        // Dibuja una curva especificando el objeto Pen que tiene el color Green com.aspose.imaging.Color y una matriz de puntos
        graphics.drawCurve(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(100, 200),
                                new com.aspose.imaging.Point(100, 350),
                                new com.aspose.imaging.Point(200, 450)
                        });

        // Dibuja una elipse usando el objeto Pen y un rectángulo circundante
        graphics.drawEllipse(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getYellow(), 2),
                new com.aspose.imaging.Rectangle(300, 300, 100, 100));

        // Dibuja una línea
        graphics.drawLine(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getViolet(), 2),
                new com.aspose.imaging.Point(100, 100),
                new com.aspose.imaging.Point(200, 200));

        // Dibuja un segmento de pastel
        graphics.drawPie(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getSilver(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(200, 20), new com.aspose.imaging.Size(200, 200)),
                0,
                45);

        // Dibuja un polígono especificando el objeto Pen que tiene el color Red com.aspose.imaging.Color y una matriz de puntos
        graphics.drawPolygon(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(20, 100),
                                new com.aspose.imaging.Point(20, 200),
                                new com.aspose.imaging.Point(220, 20)
                        });

        // Dibuja un rectángulo
        graphics.drawRectangle(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(250, 250), new com.aspose.imaging.Size(100, 100)));

        // Crea un objeto SolidBrush y establece sus diversas propiedades
        com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush();
        brush.setColor(com.aspose.imaging.Color.getPurple());

        // Dibuja una cadena usando el objeto SolidBrush y Font, en un punto específico
        graphics.drawString(
                "This image is created by Aspose.Imaging API",
                new com.aspose.imaging.Font("Times New Roman", 16),
                brush,
                new com.aspose.imaging.PointF(50, 400));

        // Guardar todos los cambios.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### SolidBrush() {#SolidBrush--}
```
public SolidBrush()
```


Inicializa una nueva instancia de la clase `SolidBrush`.

### SolidBrush(Color color) {#SolidBrush-com.aspose.imaging.Color-}
```
public SolidBrush(Color color)
```


Inicializa una nueva instancia de la clase `SolidBrush`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | El color del pincel sólido. |

### getColor() {#getColor--}
```
public Color getColor()
```


Obtiene o establece el color del pincel.

Valor: El color del pincel.

**Returns:**
[Color](../../com.aspose.imaging/color)

**Example: This example uses Graphics class to create primitive shapes on the Image surface.**
Este ejemplo utiliza la clase Graphics para crear formas primitivas en la superficie de la Imagen. Para demostrar la operación, el ejemplo crea una nueva Imagen en formato PNG y dibuja formas primitivas en la superficie de la Imagen usando los métodos Draw expuestos por la clase Graphics.
``` java
// Crea una instancia de FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.png", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Crea una instancia de PngOptions y establece sus diversas propiedades
    com.aspose.imaging.imageoptions.PngOptions pngOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Establece la Fuente para PngOptions
    pngOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Crear una instancia de Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(pngOptions, 500, 500);
    try {
        // Crear e inicializar una instancia de la clase Graphics
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Borrar la superficie de Graphics
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Dibuja un arco especificando el objeto Pen que tiene el color Black com.aspose.imaging.Color,
        // un Rectángulo que rodea el arco, ángulo de inicio y ángulo de barrido
        graphics.drawArc(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2),
                new com.aspose.imaging.Rectangle(200, 200, 100, 200),
                0,
                300);

        // Dibuja una curva Bézier especificando el objeto Pen que tiene el color Blue com.aspose.imaging.Color y los puntos de coordenadas.
        graphics.drawBezier(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
                new com.aspose.imaging.Point(250, 100),
                new com.aspose.imaging.Point(300, 30),
                new com.aspose.imaging.Point(450, 100),
                new com.aspose.imaging.Point(235, 25));

        // Dibuja una curva especificando el objeto Pen que tiene el color Green com.aspose.imaging.Color y una matriz de puntos
        graphics.drawCurve(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(100, 200),
                                new com.aspose.imaging.Point(100, 350),
                                new com.aspose.imaging.Point(200, 450)
                        });

        // Dibuja una elipse usando el objeto Pen y un rectángulo circundante
        graphics.drawEllipse(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getYellow(), 2),
                new com.aspose.imaging.Rectangle(300, 300, 100, 100));

        // Dibuja una línea
        graphics.drawLine(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getViolet(), 2),
                new com.aspose.imaging.Point(100, 100),
                new com.aspose.imaging.Point(200, 200));

        // Dibuja un segmento de pastel
        graphics.drawPie(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getSilver(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(200, 20), new com.aspose.imaging.Size(200, 200)),
                0,
                45);

        // Dibuja un polígono especificando el objeto Pen que tiene el color Red com.aspose.imaging.Color y una matriz de puntos
        graphics.drawPolygon(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(20, 100),
                                new com.aspose.imaging.Point(20, 200),
                                new com.aspose.imaging.Point(220, 20)
                        });

        // Dibuja un rectángulo
        graphics.drawRectangle(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(250, 250), new com.aspose.imaging.Size(100, 100)));

        // Crea un objeto SolidBrush y establece sus diversas propiedades
        com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush();
        brush.setColor(com.aspose.imaging.Color.getPurple());

        // Dibuja una cadena usando el objeto SolidBrush y Font, en un punto específico
        graphics.drawString(
                "This image is created by Aspose.Imaging API",
                new com.aspose.imaging.Font("Times New Roman", 16),
                brush,
                new com.aspose.imaging.PointF(50, 400));

        // Guardar todos los cambios.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### setColor(Color value) {#setColor-com.aspose.imaging.Color-}
```
public void setColor(Color value)
```


Obtiene o establece el color del pincel.

Valor: El color del pincel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtiene el código hash del objeto actual.

**Returns:**
int
### equals(Object object) {#equals-java.lang.Object-}
```
public boolean equals(Object object)
```


Comprueba si los objetos son iguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| objeto | java.lang.Object |  |

**Returns:**
boolean
