---
title: "SvgGraphics2D"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Proporciona comandos de dibujo para componer una imagen Svg."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.fileformats.svg.graphics/svggraphics2d/
---
**Inheritance:**
java.lang.Object
```
public class SvgGraphics2D
```

Proporciona comandos de dibujo para componer una imagen Svg.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [SvgGraphics2D(int width, int height, int dpi)](#SvgGraphics2D-int-int-int-) | Inicializa una nueva instancia de la clase [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d). |
| [SvgGraphics2D(SvgImage image)](#SvgGraphics2D-com.aspose.imaging.fileformats.svg.SvgImage-) | Inicializa una nueva instancia de la clase [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d). |
## Métodos

| Método | Descripción |
| --- | --- |
| [drawImage(RasterImage image, Point origin)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-) | Dibuja la imagen especificada en la ubicación especificada. |
| [drawImage(RasterImage image, Point origin, Size size)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Dibuja la imagen especificada del tamaño especificado en la ubicación especificada. |
| [drawImage(Rectangle srcRect, Rectangle destRect, RasterImage image)](#drawImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RasterImage-) | Dibuja la porción especificada de la imagen especificada en la ubicación especificada y con el tamaño especificado. |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)](#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | Dibuja un arco que representa una porción de una elipse especificada por una estructura Rectangle. |
| [fillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle)](#fillArc-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-) | Rellena un arco que representa una porción de una elipse especificada por una estructura Rectangle. |
| [drawCubicBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)](#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Dibuja el bezier cúbico. |
| [drawString(Font font, String text, Point origin, Color textColor)](#drawString-com.aspose.imaging.Font-java.lang.String-com.aspose.imaging.Point-com.aspose.imaging.Color-) | Dibuja la cadena de texto. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.imaging.Pen-int-int-int-int-) | Dibuja la línea. |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-) | Dibuja la ruta. |
| [fillPath(Pen pen, Brush brush, GraphicsPath path)](#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-) | Rellena la ruta. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-) | Dibuja el rectángulo. |
| [fillRectangle(Pen pen, Brush brush, int x, int y, int width, int height)](#fillRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Brush-int-int-int-int-) | Rellena el rectángulo. |
| [endRecording()](#endRecording--) | Obtiene la imagen Svg final que incluye todos los comandos de dibujo realizados a través del objeto [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d). |

## Example: This example shows how to create an SVG image of the specified size and draw different shapes on it using SvgGraphics2D.

``` java
String dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;
int dpi = 96;

com.aspose.imaging.fileformats.svg.graphics.SvgGraphics2D graphics = new com.aspose.imaging.fileformats.svg.graphics.SvgGraphics2D(imageWidth, imageHeight, dpi);

// Dibuja un rectángulo negro a lo largo de los bordes de la imagen usando un lápiz negro de 1 píxel de ancho.
graphics.drawRectangle(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 1), 0, 0, imageWidth, imageHeight);

// Rellena un rectángulo con el color blanco ahumado.
graphics.fillRectangle(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getWhiteSmoke(), 1),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhiteSmoke()), 10, 10, 580, 380);

// Dibuja dos líneas diagonales usando un lápiz verde oscuro de 1 píxel de ancho.
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, 0, imageWidth, imageHeight);
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, imageHeight, imageWidth, 0);

// Dibuja un arco dentro del rectángulo {0, 0, 200, 200} usando un lápiz azul de 2 píxeles de ancho.
graphics.drawArc(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
        new com.aspose.imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Rellena un arco
graphics.fillArc(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getLightCoral(), 10),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getLightSkyBlue()),
        new com.aspose.imaging.Rectangle(0, 0, 150, 150), 90, 270);

// Dibuja un Bézier cúbico usando un lápiz rojo de 2 píxeles de ancho.
graphics.drawCubicBezier(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
        new com.aspose.imaging.PointF(0, 0),
        new com.aspose.imaging.PointF(200, 133),
        new com.aspose.imaging.PointF(400, 166),
        new com.aspose.imaging.PointF(600, 400));

// Dibuja una imagen raster del tamaño especificado en la ubicación especificada.
// La imagen se escala para ajustarse al rectángulo deseado.
com.aspose.imaging.RasterImage imageToDraw = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    graphics.drawImage(imageToDraw, new com.aspose.imaging.Point(400, 200), new com.aspose.imaging.Size(100, 50));
} finally {
    imageToDraw.dispose();
}

// Dibuja una cadena de texto
graphics.drawString(
        new com.aspose.imaging.Font("Arial", 48, com.aspose.imaging.FontStyle.Regular),
        "Hello World!",
        new com.aspose.imaging.Point(200, 300),
        com.aspose.imaging.Color.getDarkRed());

// Crea una ruta para rellenar
com.aspose.imaging.Figure figureToFill = new com.aspose.imaging.Figure();
figureToFill.setClosed(true);

com.aspose.imaging.GraphicsPath pathToFill = new com.aspose.imaging.GraphicsPath();
pathToFill.addFigure(figureToFill);

figureToFill.addShapes(new com.aspose.imaging.Shape[]
        {
                new com.aspose.imaging.shapes.ArcShape(new com.aspose.imaging.RectangleF(400, 0, 200, 100), 45, 300),
                new com.aspose.imaging.shapes.BezierShape(
                        new com.aspose.imaging.PointF[]
                                {
                                        new com.aspose.imaging.PointF(300, 200),
                                        new com.aspose.imaging.PointF(400, 200),
                                        new com.aspose.imaging.PointF(500, 100),
                                        new com.aspose.imaging.PointF(600, 200),
                                }),
                new com.aspose.imaging.shapes.PolygonShape(
                        new com.aspose.imaging.PointF[]
                                {
                                        new com.aspose.imaging.PointF(300, 100),
                                }),
                new com.aspose.imaging.shapes.RectangleShape(
                        new com.aspose.imaging.RectangleF(0, 100, 200, 200)),
        });

// Rellena la ruta usando un pincel amarillo y un lápiz verde para dibujar el contorno
graphics.fillPath(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getYellow()), pathToFill);

// Crea una ruta para dibujar
com.aspose.imaging.GraphicsPath pathToDraw = new com.aspose.imaging.GraphicsPath();
com.aspose.imaging.Figure figureToDraw = new com.aspose.imaging.Figure();
pathToDraw.addFigure(figureToDraw);

figureToDraw.addShapes(new com.aspose.imaging.Shape[]
        {
                new com.aspose.imaging.shapes.ArcShape(new com.aspose.imaging.RectangleF(200, 200, 200, 200), 0, 360),
        });

// Dibuja la ruta usando un lápiz naranja de 5 píxeles de ancho.
graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 5), pathToDraw);

// Obtenga la imagen SVG final que incluye todos los comandos de dibujo
com.aspose.imaging.fileformats.svg.SvgImage svgImage = graphics.endRecording();
try {
    svgImage.save(dir + "test.output.svg");
} finally {
    svgImage.dispose();
}
```

### SvgGraphics2D(int width, int height, int dpi) {#SvgGraphics2D-int-int-int-}
```
public SvgGraphics2D(int width, int height, int dpi)
```


Inicializa una nueva instancia de la clase [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | El ancho de la imagen Svg de salida. |
| height | int | El ancho de la imagen Svg de salida. |
| dpi | int | La resolución del dispositivo, p. ej. 96 puntos por pulgada. |

### SvgGraphics2D(SvgImage image) {#SvgGraphics2D-com.aspose.imaging.fileformats.svg.SvgImage-}
```
public SvgGraphics2D(SvgImage image)
```


Inicializa una nueva instancia de la clase [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) | La imagen sobre la que se realizan operaciones de dibujo. |

### drawImage(RasterImage image, Point origin) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-}
```
public final void drawImage(RasterImage image, Point origin)
```


Dibuja la imagen especificada en la ubicación especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen dibujada. |
| origin | [Point](../../com.aspose.imaging/point) | La ubicación de la imagen dibujada. |

### drawImage(RasterImage image, Point origin, Size size) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public final void drawImage(RasterImage image, Point origin, Size size)
```


Dibuja la imagen especificada del tamaño especificado en la ubicación especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen dibujada. |
| origin | [Point](../../com.aspose.imaging/point) | La ubicación de la imagen dibujada. |
| size | [Size](../../com.aspose.imaging/size) | El tamaño deseado de la imagen dibujada. |

### drawImage(Rectangle srcRect, Rectangle destRect, RasterImage image) {#drawImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RasterImage-}
```
public final void drawImage(Rectangle srcRect, Rectangle destRect, RasterImage image)
```


Dibuja la porción especificada de la imagen especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcRect | [Rectangle](../../com.aspose.imaging/rectangle) | La porción del objeto imagen a dibujar. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | La ubicación y el tamaño de la imagen dibujada. La imagen se escala para ajustarse al rectángulo. |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen a dibujar. |

### drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle) {#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public final void drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)
```


Dibuja un arco que representa una porción de una elipse especificada por una estructura Rectangle.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | El lápiz para dibujar el contorno de la figura. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Los límites de la elipse. |
| startAngle | float | El ángulo en grados medido en sentido horario desde el eje x hasta el punto de inicio del arco. |
| arcAngle | float | El ángulo en grados medido en sentido horario desde el parámetro startAngle hasta el punto final del arco. |

### fillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle) {#fillArc-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-}
```
public final void fillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle)
```


Rellena un arco que representa una porción de una elipse especificada por una estructura Rectangle.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | El lápiz para dibujar el contorno de la figura. |
| brush | [Brush](../../com.aspose.imaging/brush) | El pincel para rellenar el interior de la figura. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Los límites de la elipse. |
| startAngle | float | El ángulo en grados medido en sentido horario desde el eje x hasta el punto de inicio del arco. |
| arcAngle | float | El ángulo en grados medido en sentido horario desde el parámetro startAngle hasta el punto final del arco. |

### drawCubicBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4) {#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public final void drawCubicBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```


Dibuja el bezier cúbico.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | El lápiz que determina el color, el ancho y el estilo de la figura. |
| pt1 | [PointF](../../com.aspose.imaging/pointf) | El punto de inicio de la curva. |
| pt2 | [PointF](../../com.aspose.imaging/pointf) | El primer punto de control de la curva. |
| pt3 | [PointF](../../com.aspose.imaging/pointf) | El segundo punto de control de la curva. |
| pt4 | [PointF](../../com.aspose.imaging/pointf) | El punto final de la curva. |

### drawString(Font font, String text, Point origin, Color textColor) {#drawString-com.aspose.imaging.Font-java.lang.String-com.aspose.imaging.Point-com.aspose.imaging.Color-}
```
public final void drawString(Font font, String text, Point origin, Color textColor)
```


Dibuja la cadena de texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| font | [Font](../../com.aspose.imaging/font) | La fuente utilizada para renderizar texto. |
| text | java.lang.String | La cadena de texto Unicode. |
| origin | [Point](../../com.aspose.imaging/point) | La esquina superior izquierda de la ejecución de texto. |
| textColor | [Color](../../com.aspose.imaging/color) | El color del texto. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.imaging.Pen-int-int-int-int-}
```
public final void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


Dibuja la línea.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | El lápiz que determina el color, el ancho y el estilo de la figura. |
| x1 | int | La coordenada x del primer punto. |
| y1 | int | La coordenada y del primer punto. |
| x2 | int | La coordenada x del segundo punto. |
| y2 | int | La coordenada y del segundo punto. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-}
```
public final void drawPath(Pen pen, GraphicsPath path)
```


Dibuja la ruta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | El lápiz para dibujar el contorno de la figura. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | La ruta a dibujar. |

### fillPath(Pen pen, Brush brush, GraphicsPath path) {#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-}
```
public final void fillPath(Pen pen, Brush brush, GraphicsPath path)
```


Rellena la ruta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | El lápiz para dibujar el contorno de la figura. |
| brush | [Brush](../../com.aspose.imaging/brush) | El pincel para rellenar el interior de la figura. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | La ruta a dibujar. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-}
```
public final void drawRectangle(Pen pen, int x, int y, int width, int height)
```


Dibuja el rectángulo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | El lápiz para dibujar el contorno de la figura. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo a dibujar. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo a dibujar. |
| width | int | El ancho del rectángulo a dibujar. |
| height | int | La altura del rectángulo a dibujar. |

### fillRectangle(Pen pen, Brush brush, int x, int y, int width, int height) {#fillRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Brush-int-int-int-int-}
```
public final void fillRectangle(Pen pen, Brush brush, int x, int y, int width, int height)
```


Rellena el rectángulo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | El lápiz para dibujar el contorno de la figura. |
| brush | [Brush](../../com.aspose.imaging/brush) | El pincel para rellenar el interior de la figura. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo a dibujar. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo a dibujar. |
| width | int | El ancho del rectángulo a dibujar. |
| height | int | La altura del rectángulo a dibujar. |

### endRecording() {#endRecording--}
```
public final SvgImage endRecording()
```


Obtiene la imagen Svg final que incluye todos los comandos de dibujo realizados a través del objeto [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d).

**Returns:**
[SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) - The final Svg image.
