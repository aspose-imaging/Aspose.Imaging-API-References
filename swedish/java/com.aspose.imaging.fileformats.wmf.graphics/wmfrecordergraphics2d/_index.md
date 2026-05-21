---
title: "WmfRecorderGraphics2D"
second_title: "Aspose.Imaging för Java API-referens"
description: "Wmf‑inspelaren."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.fileformats.wmf.graphics/wmfrecordergraphics2d/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.graphics.MetafileRecorderGraphics2D](../../com.aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d)
```
public final class WmfRecorderGraphics2D extends MetafileRecorderGraphics2D
```

Wmf‑inspelaren.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WmfRecorderGraphics2D(Rectangle frame, int inch)](#WmfRecorderGraphics2D-com.aspose.imaging.Rectangle-int-) | Initierar en ny instans av klassen `WmfRecorderGraphics2D`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBackgroundMode()](#getBackgroundMode--) | Hämtar eller anger bakgrundsläget. |
| [setBackgroundMode(int value)](#setBackgroundMode-int-) | Hämtar eller anger bakgrundsläget. |
| [endRecording()](#endRecording--) | Avslutar inspelningen. |
| [fromWmfImage(WmfImage wmfImage)](#fromWmfImage-com.aspose.imaging.fileformats.wmf.WmfImage-) | Hämtar en instans av Wmf‑inspelaren för den befintliga Wmf‑bilden. |

## Example: This example shows how to create a WMF image and draw some geometric shapes using WmfRecorderGraphics2D.

``` java
String dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;

// Detta är standardupplösningen för skärmen.
int dpi = 96;

com.aspose.imaging.Rectangle frame = new com.aspose.imaging.Rectangle(0, 0, imageWidth, imageHeight);

// Skapa en WMF‑bild.
com.aspose.imaging.fileformats.wmf.graphics.WmfRecorderGraphics2D graphics =
        new com.aspose.imaging.fileformats.wmf.graphics.WmfRecorderGraphics2D(frame, dpi);

// Rita en svart rektangel längs bildens kanter med en 1‑pixel bred svart penna.
graphics.drawRectangle(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 1), 0, 0, imageWidth, imageHeight);

// Fyll en rektangel med färgen white‑smoke.
graphics.fillRectangle(
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhiteSmoke()),
        new com.aspose.imaging.Rectangle(10, 10, 580, 380));

// Rita två diagonala linjer med en 1‑pixel bred darkgreen‑penna.
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, 0, imageWidth, imageHeight);
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, imageHeight, imageWidth, 0);

// Rita en båge inom rektangeln {0, 0, 200, 200} med en 2‑pixel bred blå penna.
graphics.drawArc(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2), new com.aspose.imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Fyll en båge
graphics.fillPie(
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getLightSkyBlue()),
        new com.aspose.imaging.Rectangle(0, 0, 150, 150), 90, 270);

// Rita en kubisk Bézier med en 2‑pixel bred röd penna.
graphics.drawCubicBezier(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(200, 133),
        new com.aspose.imaging.Point(400, 166),
        new com.aspose.imaging.Point(600, 400));

// Rita en rasterbild av angiven storlek på den angivna platsen.
// Bilden skalas för att passa den önskade rektangeln.
com.aspose.imaging.RasterImage imageToDraw = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "sample.bmp");
{
    graphics.drawImage(imageToDraw,
            new com.aspose.imaging.Rectangle(400, 200, 100, 50),
            new com.aspose.imaging.Rectangle(0, 0, imageWidth, imageHeight),
            com.aspose.imaging.GraphicsUnit.Pixel);
}

// Rita en textsträng
graphics.drawString("Hello World!", new com.aspose.imaging.Font("Arial", 48, com.aspose.imaging.FontStyle.Regular), com.aspose.imaging.Color.getDarkRed(), 200, 300);

// Skapa en bana för att fylla
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

// Fyll banan med en gul pensel och en grön penna för att rita konturen
graphics.fillPath(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getYellow()), pathToFill);

// Skapa en bana för att rita
com.aspose.imaging.GraphicsPath pathToDraw = new com.aspose.imaging.GraphicsPath();
com.aspose.imaging.Figure figureToDraw = new com.aspose.imaging.Figure();
pathToDraw.addFigure(figureToDraw);

figureToDraw.addShapes(new com.aspose.imaging.Shape[]
        {
                new com.aspose.imaging.shapes.ArcShape(new com.aspose.imaging.RectangleF(200, 200, 200, 200), 0, 360),
        });

// Rita banan med en 5‑pixel bred orange penna.
graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 5), pathToDraw);

// För att rasterisera SVG måste vi specificera rasteriseringsalternativ.
com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
saveOptions.setVectorRasterizationOptions(rasterizationOptions);

// Hämta den slutgiltiga WMF‑bilden som inkluderar alla ritkommandon
com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = graphics.endRecording();
try {
    wmfImage.save(dir + "test.output.wmf");
} finally {
    wmfImage.dispose();
}
```

### WmfRecorderGraphics2D(Rectangle frame, int inch) {#WmfRecorderGraphics2D-com.aspose.imaging.Rectangle-int-}
```
public WmfRecorderGraphics2D(Rectangle frame, int inch)
```


Initierar en ny instans av klassen `WmfRecorderGraphics2D`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| frame | [Rectangle](../../com.aspose.imaging/rectangle) | Destinationsrektangel, mätt i twips, för att visa metafilen. |
| tum | int | Antalet pixlar per tum. |

### getBackgroundMode() {#getBackgroundMode--}
```
public int getBackgroundMode()
```


Hämtar eller anger bakgrundsläget.

Värde: Bakgrundsläget.

**Returns:**
int
### setBackgroundMode(int value) {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```


Hämtar eller anger bakgrundsläget.

Värde: Bakgrundsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### endRecording() {#endRecording--}
```
public WmfImage endRecording()
```


Avslutar inspelningen.

**Returns:**
[WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) - The result image.
### fromWmfImage(WmfImage wmfImage) {#fromWmfImage-com.aspose.imaging.fileformats.wmf.WmfImage-}
```
public static WmfRecorderGraphics2D fromWmfImage(WmfImage wmfImage)
```


Hämtar en instans av Wmf‑inspelaren för den befintliga Wmf‑bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| wmfImage | [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) | Wmf‑bilden att hämta en inspelare för. |

**Returns:**
[WmfRecorderGraphics2D](../../com.aspose.imaging.fileformats.wmf.graphics/wmfrecordergraphics2d) - An instance of the [WmfRecorderGraphics2D](../../com.aspose.imaging.fileformats.wmf.graphics/wmfrecordergraphics2d) class.
