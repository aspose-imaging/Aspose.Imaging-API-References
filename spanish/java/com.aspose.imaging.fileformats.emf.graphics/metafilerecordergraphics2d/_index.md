---
title: "MetafileRecorderGraphics2D"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Los gráficos del grabador de metarchivos"
type: docs
weight: 11
url: /es/java/com.aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/
---
**Inheritance:**
java.lang.Object
```
public abstract class MetafileRecorderGraphics2D
```

Los gráficos del grabador de metarchivos
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MetafileRecorderGraphics2D()](#MetafileRecorderGraphics2D--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getClip()](#getClip--) | Obtiene o establece una Región que limita la región de dibujo de este Graphics |
| [setClip(Region value)](#setClip-com.aspose.imaging.Region-) | Obtiene o establece una Región que limita la región de dibujo de este Graphics |
| [getClipBounds()](#getClipBounds--) | Obtiene los límites del recorte. |
| [getBackgroundColor()](#getBackgroundColor--) | Obtiene el color del fondo. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Establece el color del fondo. |
| [clear()](#clear--) | Borra el estado del objeto gráfico |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)](#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | Dibuja un arco que representa una porción de una elipse especificada por una estructura Rectangle. |
| [drawCubicBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)](#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Dibuja el bezier cúbico. |
| [drawPolyCubicBezier(Pen pen, Point[] points)](#drawPolyCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | Dibuja el bezier cúbico poligonal. |
| [drawEllipse(Pen pen, Rectangle rect)](#drawEllipse-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-) | Dibuja la elipse. |
| [fillEllipse(Brush brush, Rectangle rect)](#fillEllipse-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-) | Rellena la elipse. |
| [drawImage(RasterImage image, Point location)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-) | Dibuja la Imagen especificada, usando su tamaño físico original, en la ubicación especificada. |
| [drawImage(byte[] imageBytes, Rectangle destRect, int srcUnit)](#drawImage-byte---com.aspose.imaging.Rectangle-int-) | Dibuja la imagen. |
| [drawImage(InputStream stream, Rectangle destRect, int srcUnit)](#drawImage-java.io.InputStream-com.aspose.imaging.Rectangle-int-) | Dibuja la imagen. |
| [drawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, int srcUnit)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-int-) | Dibuja la porción especificada de la Imagen especificada en la ubicación especificada y con el tamaño especificado. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.imaging.Pen-int-int-int-int-) | Dibuja la línea. |
| [drawLine(Pen pen, Point pt1, Point pt2)](#drawLine-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Dibuja la línea. |
| [drawPolyline(Pen pen, Point[] points)](#drawPolyline-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | Dibuja la polilínea. |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-) | Dibuja la ruta. |
| [fillPath(Pen pen, Brush brush, GraphicsPath path)](#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-) | Rellena la ruta. |
| [drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | Dibuja el sector. |
| [fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-) | Rellena el pastel. |
| [drawPolygon(Pen pen, Point[] points)](#drawPolygon-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | Dibuja el polígono. |
| [fillPolygon(Brush brush, Point[] points)](#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---) | Rellena el polígono. |
| [fillPolygon(Brush brush, Point[] points, int fillMode)](#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---int-) | Rellena el polígono. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-) | Dibuja el rectángulo. |
| [drawRectangle(Pen pen, Rectangle rectangle)](#drawRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-) | Dibuja el rectángulo. |
| [fillRectangle(Brush brush, Rectangle rectangle)](#fillRectangle-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-) | Rellena el rectángulo. |
| [drawString(String string, Font font, Color color, int x, int y)](#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-) | Dibuja la cadena. |
| [drawString(String string, Font font, Color color, int x, int y, float angle)](#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-float-) | Dibuja la cadena. |
| [excludeClip(Rectangle rect)](#excludeClip-com.aspose.imaging.Rectangle-) | Actualiza la región de recorte de este Graphics para excluir el área especificada por una estructura Rectangle. |
| [excludeClip(Region region)](#excludeClip-com.aspose.imaging.Region-) | Actualiza la región de recorte de este Graphics para excluir el área especificada por una Region. |
| [intersectClip(RectangleF rect)](#intersectClip-com.aspose.imaging.RectangleF-) | Actualiza la región de recorte de este Graphics a la intersección de la región de recorte actual y la estructura Rectangle especificada. |
| [intersectClip(Region region)](#intersectClip-com.aspose.imaging.Region-) | Actualiza la región de recorte de este Graphics a la intersección de la región de recorte actual y la Region especificada. |
| [resetClip()](#resetClip--) | Restablece el recorte. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.imaging.Matrix-) | Multiplica la transformación mundial de este Graphics y especifica la Matrix. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.imaging.Matrix-int-) | Multiplica la transformación mundial de este Graphics y especifica la Matrix en el orden especificado. |
| [translateTransform(float x, float y)](#translateTransform-float-float-) | Cambia el origen del sistema de coordenadas anteponiendo la traslación especificada a la matriz de transformación de este Graphics. |
| [translateTransform(float x, float y, int order)](#translateTransform-float-float-int-) | Cambia el origen del sistema de coordenadas aplicando la traslación especificada a la matriz de transformación de este Graphics en el orden especificado. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Aplica la rotación especificada a la matriz de transformación de este Graphics. |
| [rotateTransform(float angle, PointF center, int order)](#rotateTransform-float-com.aspose.imaging.PointF-int-) | Aplica la rotación especificada a la matriz de transformación de este Graphics en el orden especificado. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Aplica la operación de escalado especificada a la matriz de transformación de este Graphics anteponiéndola a la matriz de transformación del objeto. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Aplica la operación de escalado especificada a la matriz de transformación de este Graphics en el orden especificado. |
| [getTransform()](#getTransform--) | Obtiene la transformación mundial. |
| [setTransform(Matrix transform)](#setTransform-com.aspose.imaging.Matrix-) | Establece la transformación. |

## Example: This example shows how to create a EMF image and draw some geometric shapes on it using EmfRecorderGraphics2D.

``` java
String dir = "c:\\temp\\";

// El tamaño de la imagen en píxeles
int deviceWidth = 600;
int deviceHeight = 400;

// El tamaño de la imagen en milímetros
int deviceWidthMm = (int) (deviceWidth / 100f);
int deviceHeightMm = (int) (deviceHeight / 100f);

com.aspose.imaging.Rectangle frame = new com.aspose.imaging.Rectangle(0, 0, deviceWidth, deviceHeight);

// Crea una imagen EMF.
com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D graphics =
        new com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D(
                frame,
                new com.aspose.imaging.Size(deviceWidth, deviceHeight),
                new com.aspose.imaging.Size(deviceWidthMm, deviceHeightMm));

// Dibuja un rectángulo negro a lo largo de los bordes de la imagen usando un lápiz negro de 1 píxel de ancho.
graphics.drawRectangle(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 1), 0, 0, deviceWidth, deviceHeight);

// Rellena un rectángulo con el color blanco ahumado.
graphics.fillRectangle(
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhiteSmoke()),
        new com.aspose.imaging.Rectangle(10, 10, 580, 380));

// Dibuja dos líneas diagonales usando un lápiz verde oscuro de 1 píxel de ancho.
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, 0, deviceWidth, deviceHeight);
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, deviceHeight, deviceWidth, 0);

// Dibuja un arco dentro del rectángulo {0, 0, 200, 200} usando un lápiz azul de 2 píxeles de ancho.
graphics.drawArc(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2), new com.aspose.imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Rellena un arco
graphics.fillPie(
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getLightSkyBlue()),
        new com.aspose.imaging.Rectangle(0, 0, 150, 150), 90, 270);

// Dibuja un Bézier cúbico usando un lápiz rojo de 2 píxeles de ancho.
graphics.drawCubicBezier(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(200, 133),
        new com.aspose.imaging.Point(400, 166),
        new com.aspose.imaging.Point(600, 400));

// Dibuja una imagen raster del tamaño especificado en la ubicación especificada.
// La imagen se escala para ajustarse al rectángulo deseado.
com.aspose.imaging.RasterImage imageToDraw = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    graphics.drawImage(imageToDraw,
            new com.aspose.imaging.Rectangle(400, 200, 100, 50),
            new com.aspose.imaging.Rectangle(0, 0, deviceWidth, deviceHeight),
            com.aspose.imaging.GraphicsUnit.Pixel);
} finally {
    imageToDraw.dispose();
}

// Dibuja una cadena de texto
graphics.drawString("Hello World!",
        new com.aspose.imaging.Font("Arial", 48, com.aspose.imaging.FontStyle.Regular),
        com.aspose.imaging.Color.getDarkRed(), 200, 300);

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
                new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(0, 100, 200, 200)),
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

// Para rasterizar SVG necesitamos especificar opciones de rasterización.
com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
saveOptions.setVectorRasterizationOptions(rasterizationOptions);

// Obtén la imagen WMF final que incluye todos los comandos de dibujo
com.aspose.imaging.fileformats.emf.EmfImage emfImage = graphics.endRecording();
try {
    emfImage.save(dir + "test.output.emf");
} finally {
    emfImage.dispose();
}
```

### MetafileRecorderGraphics2D() {#MetafileRecorderGraphics2D--}
```
public MetafileRecorderGraphics2D()
```


### getClip() {#getClip--}
```
public Region getClip()
```


Obtiene o establece una Región que limita la región de dibujo de este Graphics

**Returns:**
[Region](../../com.aspose.imaging/region) - The clip region.
### setClip(Region value) {#setClip-com.aspose.imaging.Region-}
```
public void setClip(Region value)
```


Obtiene o establece una Región que limita la región de dibujo de este Graphics

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Region](../../com.aspose.imaging/region) | La región de recorte. |

### getClipBounds() {#getClipBounds--}
```
public RectangleF getClipBounds()
```


Obtiene los límites del recorte.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The clip bounds.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Obtiene el color del fondo.

**Returns:**
[Color](../../com.aspose.imaging/color) - The color of the background.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Establece el color del fondo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | El color del fondo. |

### clear() {#clear--}
```
public void clear()
```


Borra el estado del objeto gráfico

### drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle) {#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public void drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)
```


Dibuja un arco que representa una porción de una elipse especificada por una estructura Rectangle.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pluma que determina el color, ancho y estilo de la figura. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Los límites de la elipse. |
| startAngle | float | Ángulo en grados medido en sentido horario desde el eje x hasta el punto inicial del arco. |
| arcAngle | float | Ángulo en grados medido en sentido horario desde el parámetro startAngle hasta el punto final del arco. |

### drawCubicBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4) {#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public void drawCubicBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```


Dibuja el bezier cúbico.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pluma que determina el color, ancho y estilo de la figura. |
| pt1 | [Point](../../com.aspose.imaging/point) | El punto de inicio de la curva. |
| pt2 | [Point](../../com.aspose.imaging/point) | El primer punto de control de la curva. |
| pt3 | [Point](../../com.aspose.imaging/point) | El segundo punto de control de la curva. |
| pt4 | [Point](../../com.aspose.imaging/point) | El punto final de la curva. |

### drawPolyCubicBezier(Pen pen, Point[] points) {#drawPolyCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawPolyCubicBezier(Pen pen, Point[] points)
```


Dibuja el bezier cúbico poligonal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pluma que determina el color, ancho y estilo de la figura. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Los puntos. |

### drawEllipse(Pen pen, Rectangle rect) {#drawEllipse-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-}
```
public void drawEllipse(Pen pen, Rectangle rect)
```


Dibuja la elipse.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pluma que determina el color, ancho y estilo de la figura. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Los límites de la elipse. |

### fillEllipse(Brush brush, Rectangle rect) {#fillEllipse-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-}
```
public void fillEllipse(Brush brush, Rectangle rect)
```


Rellena la elipse.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Pincel que determina las características del relleno. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Los límites de la elipse. |

### drawImage(RasterImage image, Point location) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-}
```
public void drawImage(RasterImage image, Point location)
```


Dibuja la Imagen especificada, usando su tamaño físico original, en la ubicación especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen a dibujar. |
| location | [Point](../../com.aspose.imaging/point) | La ubicación de la esquina superior izquierda de la imagen dibujada. |

### drawImage(byte[] imageBytes, Rectangle destRect, int srcUnit) {#drawImage-byte---com.aspose.imaging.Rectangle-int-}
```
public final void drawImage(byte[] imageBytes, Rectangle destRect, int srcUnit)
```


Dibuja la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageBytes | byte[] | Los bytes de la imagen. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo de destino. |
| srcUnit | int | La unidad de origen. |

### drawImage(InputStream stream, Rectangle destRect, int srcUnit) {#drawImage-java.io.InputStream-com.aspose.imaging.Rectangle-int-}
```
public final void drawImage(InputStream stream, Rectangle destRect, int srcUnit)
```


Dibuja la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo de destino. |
| srcUnit | int | La unidad de origen. |

### drawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, int srcUnit) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-int-}
```
public void drawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, int srcUnit)
```


Dibuja la porción especificada de la Imagen especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen a dibujar. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | Estructura Rectangle que especifica la ubicación y el tamaño de la imagen dibujada. La imagen se escala para ajustarse al rectángulo. |
| srcRect | [Rectangle](../../com.aspose.imaging/rectangle) | Estructura Rectangle que especifica la porción del objeto imagen a dibujar. |
| srcUnit | int | Las unidades de medida utilizadas por el parámetro srcRect. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.imaging.Pen-int-int-int-int-}
```
public void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


Dibuja la línea.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pluma que determina el color, ancho y estilo de la figura. |
| x1 | int | La coordenada x del primer punto. |
| y1 | int | La coordenada y del primer punto. |
| x2 | int | La coordenada x del segundo punto. |
| y2 | int | La coordenada y del segundo punto. |

### drawLine(Pen pen, Point pt1, Point pt2) {#drawLine-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public void drawLine(Pen pen, Point pt1, Point pt2)
```


Dibuja la línea.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pluma que determina el color, ancho y estilo de la figura. |
| pt1 | [Point](../../com.aspose.imaging/point) | El primer punto. |
| pt2 | [Point](../../com.aspose.imaging/point) | El segundo punto. |

### drawPolyline(Pen pen, Point[] points) {#drawPolyline-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawPolyline(Pen pen, Point[] points)
```


Dibuja la polilínea.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pluma que determina el color, ancho y estilo de la figura. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Los puntos. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-}
```
public void drawPath(Pen pen, GraphicsPath path)
```


Dibuja la ruta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pluma que determina el color, ancho y estilo de la figura. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | La ruta a dibujar. |

### fillPath(Pen pen, Brush brush, GraphicsPath path) {#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-}
```
public void fillPath(Pen pen, Brush brush, GraphicsPath path)
```


Rellena la ruta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pluma que determina el color, ancho y estilo de la figura. |
| brush | [Brush](../../com.aspose.imaging/brush) | Pincel que determina las características del relleno. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | La ruta a rellenar. |

### drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public void drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Dibuja el sector.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pluma que determina el color, ancho y estilo de la figura. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Los límites de la elipse. |
| startAngle | float | Ángulo en grados medido en sentido horario desde el eje x hasta el punto inicial del arco. |
| sweepAngle | float | Ángulo en grados medido en sentido horario desde el parámetro startAngle hasta el punto final del arco. |

### fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-}
```
public void fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```


Rellena el pastel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Pincel que determina las características del relleno. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Los límites de la elipse. |
| startAngle | float | Ángulo en grados medido en sentido horario desde el eje x hasta el punto inicial del arco. |
| sweepAngle | float | Ángulo en grados medido en sentido horario desde el parámetro startAngle hasta el punto final del arco. |

### drawPolygon(Pen pen, Point[] points) {#drawPolygon-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawPolygon(Pen pen, Point[] points)
```


Dibuja el polígono.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pluma que determina el color, ancho y estilo de la figura. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Los puntos. |

### fillPolygon(Brush brush, Point[] points) {#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---}
```
public void fillPolygon(Brush brush, Point[] points)
```


Rellena el polígono.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Pincel que determina las características del relleno. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Los puntos. |

### fillPolygon(Brush brush, Point[] points, int fillMode) {#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---int-}
```
public void fillPolygon(Brush brush, Point[] points, int fillMode)
```


Rellena el polígono.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Pincel que determina las características del relleno. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Los puntos. |
| fillMode | int | El modo de relleno. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-}
```
public void drawRectangle(Pen pen, int x, int y, int width, int height)
```


Dibuja el rectángulo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pluma que determina el color, ancho y estilo de la figura. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo a dibujar. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo a dibujar. |
| width | int | El ancho del rectángulo a dibujar. |
| height | int | La altura del rectángulo a dibujar. |

### drawRectangle(Pen pen, Rectangle rectangle) {#drawRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-}
```
public void drawRectangle(Pen pen, Rectangle rectangle)
```


Dibuja el rectángulo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pluma que determina el color, ancho y estilo de la figura. |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo a dibujar. |

### fillRectangle(Brush brush, Rectangle rectangle) {#fillRectangle-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-}
```
public void fillRectangle(Brush brush, Rectangle rectangle)
```


Rellena el rectángulo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Pincel que determina las características del relleno. |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo a rellenar. |

### drawString(String string, Font font, Color color, int x, int y) {#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-}
```
public void drawString(String string, Font font, Color color, int x, int y)
```


Dibuja la cadena.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cadena | java.lang.String | La cadena. |
| font | [Font](../../com.aspose.imaging/font) | Fuente que define el formato de texto de la cadena. |
| color | [Color](../../com.aspose.imaging/color) | El color del texto. |
| x | int | La coordenada x de la esquina superior izquierda del texto dibujado. |
| y | int | La coordenada y de la esquina superior izquierda del texto dibujado. |


**Example: This example shows how to load a EMF image from a file and draw a text string over it.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D graphics =
            com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D.fromEmfImage(emfImage);

    // Primero, obtenga el tamaño de la imagen
    int width = emfImage.getWidth();
    int height = emfImage.getHeight();

    // Segundo, calcule una transformación para colocar una cadena de texto a lo largo de la diagonal principal de la imagen -
    // desde la esquina superior izquierda hasta la esquina inferior derecha.
    float emFontSize = 96f;
    float d = (float) java.lang.Math.sqrt(width * width + height * height);
    float scaleFactor = d / (emFontSize * 5f);

    float tan = ((float) height) / width;
    double radians = java.lang.Math.atan(tan);
    double degrees = (180 * radians) / java.lang.Math.PI;

    com.aspose.imaging.Matrix transform = new com.aspose.imaging.Matrix();
    transform.rotate((float) degrees);
    transform.scale(scaleFactor, scaleFactor);

    // Luego, establezca la transformación.
    graphics.setTransform(transform);

    // Finalmente, coloque una marca de agua (cadena de texto de color rosa) a lo largo de la diagonal principal.
    graphics.drawString("WATERMARK", new com.aspose.imaging.Font(
                    "Courier New", emFontSize),
            com.aspose.imaging.Color.getLightPink(), 0, 0/*, (float)degrees*/);

    // Guarde la imagen con la marca de agua en otro archivo EMF.
    com.aspose.imaging.fileformats.emf.EmfImage scaledEmfImage = graphics.endRecording();
    try {
        scaledEmfImage.save(dir + "test.scaled.emf");
    } finally {
        scaledEmfImage.dispose();
    }
} finally {
    emfImage.dispose();
}
```

### drawString(String string, Font font, Color color, int x, int y, float angle) {#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-float-}
```
public void drawString(String string, Font font, Color color, int x, int y, float angle)
```


Dibuja la cadena.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cadena | java.lang.String | La cadena. |
| font | [Font](../../com.aspose.imaging/font) | Fuente que define el formato de texto de la cadena. |
| color | [Color](../../com.aspose.imaging/color) | El color del texto. |
| x | int | La coordenada x de la esquina superior izquierda del texto dibujado. |
| y | int | La coordenada y de la esquina superior izquierda del texto dibujado. |
| angle | float | El ángulo en grados, entre el vector de escapada y el eje x del dispositivo. El vector de escapada es paralelo a la línea base de una fila de texto. |

### excludeClip(Rectangle rect) {#excludeClip-com.aspose.imaging.Rectangle-}
```
public void excludeClip(Rectangle rect)
```


Actualiza la región de recorte de este Graphics para excluir el área especificada por una estructura Rectangle.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Estructura de rectángulo que especifica el rectángulo a excluir de la región de recorte. |

### excludeClip(Region region) {#excludeClip-com.aspose.imaging.Region-}
```
public void excludeClip(Region region)
```


Actualiza la región de recorte de este Graphics para excluir el área especificada por una Region.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Región que especifica la región a excluir de la región de recorte. |

### intersectClip(RectangleF rect) {#intersectClip-com.aspose.imaging.RectangleF-}
```
public void intersectClip(RectangleF rect)
```


Actualiza la región de recorte de este Graphics a la intersección de la región de recorte actual y la estructura Rectangle especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Estructura de rectángulo para intersectar con la región de recorte actual. |

### intersectClip(Region region) {#intersectClip-com.aspose.imaging.Region-}
```
public void intersectClip(Region region)
```


Actualiza la región de recorte de este Graphics a la intersección de la región de recorte actual y la Region especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Región para intersectar con la región actual. |

### resetClip() {#resetClip--}
```
public void resetClip()
```


Restablece el recorte.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.imaging.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multiplica la transformación mundial de este Graphics y especifica la Matrix.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La matriz que multiplica la transformación del mundo. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.imaging.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multiplica la transformación mundial de este Graphics y especifica la Matrix en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La matriz que multiplica la transformación del mundo. |
| order | int | El orden de la multiplicación. |

### translateTransform(float x, float y) {#translateTransform-float-float-}
```
public void translateTransform(float x, float y)
```


Cambia el origen del sistema de coordenadas anteponiendo la traslación especificada a la matriz de transformación de este Graphics.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x de la traslación. |
| y | float | La coordenada y de la traslación. |

### translateTransform(float x, float y, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float x, float y, int order)
```


Cambia el origen del sistema de coordenadas aplicando la traslación especificada a la matriz de transformación de este Graphics en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x de la traslación. |
| y | float | La coordenada y de la traslación. |
| order | int | Especifica si la traducción se antepone o se agrega a la matriz de transformación. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Aplica la rotación especificada a la matriz de transformación de este Graphics.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | Ángulo de rotación en grados. |

### rotateTransform(float angle, PointF center, int order) {#rotateTransform-float-com.aspose.imaging.PointF-int-}
```
public void rotateTransform(float angle, PointF center, int order)
```


Aplica la rotación especificada a la matriz de transformación de este Graphics en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | Ángulo de rotación en grados. |
| center | [PointF](../../com.aspose.imaging/pointf) | El centro de rotación. |
| order | int | Especifica si la rotación se agrega o se antepone a la transformación de la matriz. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Aplica la operación de escalado especificada a la matriz de transformación de este Graphics anteponiéndola a la matriz de transformación del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sx | float | Factor de escala en la dirección x. |
| sy | float | Factor de escala en la dirección y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Aplica la operación de escalado especificada a la matriz de transformación de este Graphics en el orden especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sx | float | Factor de escala en la dirección x. |
| sy | float | Factor de escala en la dirección y. |
| order | int | Especifica si la operación de escalado se antepone o se agrega a la matriz de transformación. |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Obtiene la transformación mundial.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - The transform matrix.
### setTransform(Matrix transform) {#setTransform-com.aspose.imaging.Matrix-}
```
public void setTransform(Matrix transform)
```


Establece la transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | La nueva matriz de transformación. |


**Example: This example shows how to load a EMF image from a file and draw a text string over it.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D graphics =
            com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D.fromEmfImage(emfImage);

    // Primero, obtenga el tamaño de la imagen
    int width = emfImage.getWidth();
    int height = emfImage.getHeight();

    // Segundo, calcule una transformación para colocar una cadena de texto a lo largo de la diagonal principal de la imagen -
    // desde la esquina superior izquierda hasta la esquina inferior derecha.
    float emFontSize = 96f;
    float d = (float) java.lang.Math.sqrt(width * width + height * height);
    float scaleFactor = d / (emFontSize * 5f);

    float tan = ((float) height) / width;
    double radians = java.lang.Math.atan(tan);
    double degrees = (180 * radians) / java.lang.Math.PI;

    com.aspose.imaging.Matrix transform = new com.aspose.imaging.Matrix();
    transform.rotate((float) degrees);
    transform.scale(scaleFactor, scaleFactor);

    // Luego, establezca la transformación.
    graphics.setTransform(transform);

    // Finalmente, coloque una marca de agua (cadena de texto de color rosa) a lo largo de la diagonal principal.
    graphics.drawString("WATERMARK", new com.aspose.imaging.Font(
                    "Courier New", emFontSize),
            com.aspose.imaging.Color.getLightPink(), 0, 0/*, (float)degrees*/);

    // Guarde la imagen con la marca de agua en otro archivo EMF.
    com.aspose.imaging.fileformats.emf.EmfImage scaledEmfImage = graphics.endRecording();
    try {
        scaledEmfImage.save(dir + "test.scaled.emf");
    } finally {
        scaledEmfImage.dispose();
    }
} finally {
    emfImage.dispose();
}
```

