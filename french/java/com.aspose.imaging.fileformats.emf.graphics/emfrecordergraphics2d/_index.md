---
title: "EmfRecorderGraphics2D"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les graphiques d'enregistrement Emf"
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.graphics.MetafileRecorderGraphics2D](../../com.aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d)
```
public final class EmfRecorderGraphics2D extends MetafileRecorderGraphics2D
```

Les graphiques d'enregistrement Emf
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfRecorderGraphics2D(Rectangle frame, Size deviceSize, Size deviceSizeMm)](#EmfRecorderGraphics2D-com.aspose.imaging.Rectangle-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Initialise une nouvelle instance de la classe `EmfRecorderGraphics2D`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBackgroundMode()](#getBackgroundMode--) | Obtient ou définit le mode d'arrière-plan. |
| [setBackgroundMode(int value)](#setBackgroundMode-int-) | Obtient ou définit le mode d'arrière-plan. |
| [endRecording()](#endRecording--) | Met fin à l'enregistrement. |
| [fromEmfImage(EmfImage emfImage)](#fromEmfImage-com.aspose.imaging.fileformats.emf.EmfImage-) | Obtient une instance de la [EmfRecorderGraphics2D](../../com.aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d) contenant tous les enregistrements de l'image Emf. |

## Example: This example shows how to create a EMF image and draw some geometric shapes on it using EmfRecorderGraphics2D.

``` java
String dir = "c:\\temp\\";

// La taille de l'image en pixels
int deviceWidth = 600;
int deviceHeight = 400;

// La taille de l'image en millimètres
int deviceWidthMm = (int) (deviceWidth / 100f);
int deviceHeightMm = (int) (deviceHeight / 100f);

com.aspose.imaging.Rectangle frame = new com.aspose.imaging.Rectangle(0, 0, deviceWidth, deviceHeight);

// Crée une image EMF.
com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D graphics =
        new com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D(
                frame,
                new com.aspose.imaging.Size(deviceWidth, deviceHeight),
                new com.aspose.imaging.Size(deviceWidthMm, deviceHeightMm));

// Dessinez un rectangle noir le long des bordures de l'image en utilisant un stylo noir d'une largeur de 1 pixel.
graphics.drawRectangle(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 1), 0, 0, deviceWidth, deviceHeight);

// Remplissez un rectangle avec la couleur white-smoke.
graphics.fillRectangle(
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhiteSmoke()),
        new com.aspose.imaging.Rectangle(10, 10, 580, 380));

// Dessinez deux lignes diagonales en utilisant un stylo darkgreen d'une largeur de 1 pixel.
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, 0, deviceWidth, deviceHeight);
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, deviceHeight, deviceWidth, 0);

// Dessinez un arc à l'intérieur du rectangle {0, 0, 200, 200} en utilisant un stylo bleu d'une largeur de 2 pixels.
graphics.drawArc(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2), new com.aspose.imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Remplissez un arc
graphics.fillPie(
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getLightSkyBlue()),
        new com.aspose.imaging.Rectangle(0, 0, 150, 150), 90, 270);

// Dessinez un Bézier cubique en utilisant un stylo rouge d'une largeur de 2 pixels.
graphics.drawCubicBezier(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(200, 133),
        new com.aspose.imaging.Point(400, 166),
        new com.aspose.imaging.Point(600, 400));

// Dessinez une image raster de la taille spécifiée à l'emplacement spécifié.
// L'image est mise à l'échelle pour s'adapter au rectangle souhaité.
com.aspose.imaging.RasterImage imageToDraw = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    graphics.drawImage(imageToDraw,
            new com.aspose.imaging.Rectangle(400, 200, 100, 50),
            new com.aspose.imaging.Rectangle(0, 0, deviceWidth, deviceHeight),
            com.aspose.imaging.GraphicsUnit.Pixel);
} finally {
    imageToDraw.dispose();
}

// Dessinez une chaîne de texte
graphics.drawString("Hello World!",
        new com.aspose.imaging.Font("Arial", 48, com.aspose.imaging.FontStyle.Regular),
        com.aspose.imaging.Color.getDarkRed(), 200, 300);

// Créez un chemin à remplir
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

// Remplissez le chemin en utilisant un pinceau jaune et un stylo vert pour tracer le contour
graphics.fillPath(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getYellow()), pathToFill);

// Créez un chemin à dessiner
com.aspose.imaging.GraphicsPath pathToDraw = new com.aspose.imaging.GraphicsPath();
com.aspose.imaging.Figure figureToDraw = new com.aspose.imaging.Figure();
pathToDraw.addFigure(figureToDraw);

figureToDraw.addShapes(new com.aspose.imaging.Shape[]
        {
                new com.aspose.imaging.shapes.ArcShape(new com.aspose.imaging.RectangleF(200, 200, 200, 200), 0, 360),
        });

// Dessinez le chemin en utilisant un stylo orange d'une largeur de 5 pixels.
graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 5), pathToDraw);

// Pour rasteriser le SVG, nous devons spécifier les options de rasterisation.
com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
saveOptions.setVectorRasterizationOptions(rasterizationOptions);

// Obtenez l'image WMF finale qui inclut toutes les commandes de dessin
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


Initialise une nouvelle instance de la classe `EmfRecorderGraphics2D`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| frame | [Rectangle](../../com.aspose.imaging/rectangle) | Le cadre. |
| deviceSize | [Size](../../com.aspose.imaging/size) | Taille de l'appareil. |
| deviceSizeMm | [Size](../../com.aspose.imaging/size) | La taille de l'appareil en mm. |

### getBackgroundMode() {#getBackgroundMode--}
```
public int getBackgroundMode()
```


Obtient ou définit le mode d'arrière-plan.

**Returns:**
int - Le mode d'arrière-plan.
### setBackgroundMode(int value) {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```


Obtient ou définit le mode d'arrière-plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le mode d'arrière-plan. |

### endRecording() {#endRecording--}
```
public EmfImage endRecording()
```


Met fin à l'enregistrement.

**Returns:**
[EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) - The result image.
### fromEmfImage(EmfImage emfImage) {#fromEmfImage-com.aspose.imaging.fileformats.emf.EmfImage-}
```
public static EmfRecorderGraphics2D fromEmfImage(EmfImage emfImage)
```


Obtient une instance de la [EmfRecorderGraphics2D](../../com.aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d) contenant tous les enregistrements de l'image Emf.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| emfImage | [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) | L'image Emf à partir de laquelle lire les enregistrements. |

**Returns:**
[EmfRecorderGraphics2D](../../com.aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d) - An instance of the [EmfRecorderGraphics2D](../../com.aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d)

**Example: This example shows how to load a EMF image from a file and draw a text string over it.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D graphics =
            com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D.fromEmfImage(emfImage);

    // Tout d'abord, obtenez la taille de l'image
    int width = emfImage.getWidth();
    int height = emfImage.getHeight();

    // Deuxièmement, calculez une transformation pour placer une chaîne de texte le long de la diagonale principale de l'image -
    // du coin supérieur gauche au coin inférieur droit.
    float emFontSize = 96f;
    float d = (float) java.lang.Math.sqrt(width * width + height * height);
    float scaleFactor = d / (emFontSize * 5f);

    float tan = ((float) height) / width;
    double radians = java.lang.Math.atan(tan);
    double degrees = (180 * radians) / java.lang.Math.PI;

    com.aspose.imaging.Matrix transform = new com.aspose.imaging.Matrix();
    transform.rotate((float) degrees);
    transform.scale(scaleFactor, scaleFactor);

    // Ensuite, définissez la transformation.
    graphics.setTransform(transform);

    // Enfin, placez un filigrane (chaîne de texte de couleur rose) le long de la diagonale principale.
    graphics.drawString("WATERMARK", new com.aspose.imaging.Font(
                    "Courier New", emFontSize),
            com.aspose.imaging.Color.getLightPink(), 0, 0/*, (float)degrees*/);

    // Enregistrez l'image avec le filigrane dans un autre fichier EMF.
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

