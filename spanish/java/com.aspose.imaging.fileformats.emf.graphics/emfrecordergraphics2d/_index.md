---
title: "EmfRecorderGraphics2D"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Los gráficos del grabador Emf"
type: docs
weight: 10
url: /es/java/com.aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.graphics.MetafileRecorderGraphics2D](../../com.aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d)
```
public final class EmfRecorderGraphics2D extends MetafileRecorderGraphics2D
```

Los gráficos del grabador Emf
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfRecorderGraphics2D(Rectangle frame, Size deviceSize, Size deviceSizeMm)](#EmfRecorderGraphics2D-com.aspose.imaging.Rectangle-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Inicializa una nueva instancia de la clase `EmfRecorderGraphics2D`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBackgroundMode()](#getBackgroundMode--) | Obtiene o establece el modo de fondo. |
| [setBackgroundMode(int value)](#setBackgroundMode-int-) | Obtiene o establece el modo de fondo. |
| [endRecording()](#endRecording--) | Finaliza la grabación. |
| [fromEmfImage(EmfImage emfImage)](#fromEmfImage-com.aspose.imaging.fileformats.emf.EmfImage-) | Obtiene una instancia de [EmfRecorderGraphics2D](../../com.aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d) que contiene todos los registros de la imagen Emf. |

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

### EmfRecorderGraphics2D(Rectangle frame, Size deviceSize, Size deviceSizeMm) {#EmfRecorderGraphics2D-com.aspose.imaging.Rectangle-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public EmfRecorderGraphics2D(Rectangle frame, Size deviceSize, Size deviceSizeMm)
```


Inicializa una nueva instancia de la clase `EmfRecorderGraphics2D`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| frame | [Rectangle](../../com.aspose.imaging/rectangle) | El marco. |
| deviceSize | [Size](../../com.aspose.imaging/size) | Tamaño del dispositivo. |
| deviceSizeMm | [Size](../../com.aspose.imaging/size) | El tamaño del dispositivo en mm. |

### getBackgroundMode() {#getBackgroundMode--}
```
public int getBackgroundMode()
```


Obtiene o establece el modo de fondo.

**Returns:**
int - El modo de fondo.
### setBackgroundMode(int value) {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```


Obtiene o establece el modo de fondo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El modo de fondo. |

### endRecording() {#endRecording--}
```
public EmfImage endRecording()
```


Finaliza la grabación.

**Returns:**
[EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) - The result image.
### fromEmfImage(EmfImage emfImage) {#fromEmfImage-com.aspose.imaging.fileformats.emf.EmfImage-}
```
public static EmfRecorderGraphics2D fromEmfImage(EmfImage emfImage)
```


Obtiene una instancia de [EmfRecorderGraphics2D](../../com.aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d) que contiene todos los registros de la imagen Emf.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| emfImage | [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) | La imagen Emf de la que leer los registros. |

**Returns:**
[EmfRecorderGraphics2D](../../com.aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d) - An instance of the [EmfRecorderGraphics2D](../../com.aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d)

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

