---
title: "SvgGraphics2D"
second_title: "Aspose.Imaging för Java API-referens"
description: "Tillhandahåller ritkommandon för att komponera en Svg‑bild."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.fileformats.svg.graphics/svggraphics2d/
---
**Inheritance:**
java.lang.Object
```
public class SvgGraphics2D
```

Tillhandahåller ritkommandon för att komponera en Svg‑bild.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [SvgGraphics2D(int width, int height, int dpi)](#SvgGraphics2D-int-int-int-) | Initierar en ny instans av klassen [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d). |
| [SvgGraphics2D(SvgImage image)](#SvgGraphics2D-com.aspose.imaging.fileformats.svg.SvgImage-) | Initierar en ny instans av klassen [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [drawImage(RasterImage image, Point origin)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-) | Ritar den angivna bilden på den angivna platsen. |
| [drawImage(RasterImage image, Point origin, Size size)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Ritar den angivna bilden i den angivna storleken på den angivna platsen. |
| [drawImage(Rectangle srcRect, Rectangle destRect, RasterImage image)](#drawImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RasterImage-) | Ritar den angivna delen av den angivna bilden på den angivna platsen och med den angivna storleken. |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)](#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | Ritar en båge som representerar en del av en ellips specificerad av en rektangelstruktur. |
| [fillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle)](#fillArc-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-) | Fyller en båge som representerar en del av en ellips specificerad av en rektangelstruktur. |
| [drawCubicBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)](#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Ritar den kubiska Bézier-kurvan. |
| [drawString(Font font, String text, Point origin, Color textColor)](#drawString-com.aspose.imaging.Font-java.lang.String-com.aspose.imaging.Point-com.aspose.imaging.Color-) | Ritar textsträngen. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.imaging.Pen-int-int-int-int-) | Ritar linjen. |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-) | Ritar banan. |
| [fillPath(Pen pen, Brush brush, GraphicsPath path)](#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-) | Fyller banan. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-) | Ritar rektangeln. |
| [fillRectangle(Pen pen, Brush brush, int x, int y, int width, int height)](#fillRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Brush-int-int-int-int-) | Fyller rektangeln. |
| [endRecording()](#endRecording--) | Hämtar den slutgiltiga Svg-bilden som inkluderar alla ritkommandon som utförts via objektet [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d). |

## Example: This example shows how to create an SVG image of the specified size and draw different shapes on it using SvgGraphics2D.

``` java
String dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;
int dpi = 96;

com.aspose.imaging.fileformats.svg.graphics.SvgGraphics2D graphics = new com.aspose.imaging.fileformats.svg.graphics.SvgGraphics2D(imageWidth, imageHeight, dpi);

// Rita en svart rektangel längs bildens kanter med en 1‑pixel bred svart penna.
graphics.drawRectangle(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 1), 0, 0, imageWidth, imageHeight);

// Fyll en rektangel med färgen white‑smoke.
graphics.fillRectangle(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getWhiteSmoke(), 1),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhiteSmoke()), 10, 10, 580, 380);

// Rita två diagonala linjer med en 1‑pixel bred darkgreen‑penna.
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, 0, imageWidth, imageHeight);
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, imageHeight, imageWidth, 0);

// Rita en båge inom rektangeln {0, 0, 200, 200} med en 2‑pixel bred blå penna.
graphics.drawArc(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
        new com.aspose.imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Fyll en båge
graphics.fillArc(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getLightCoral(), 10),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getLightSkyBlue()),
        new com.aspose.imaging.Rectangle(0, 0, 150, 150), 90, 270);

// Rita en kubisk Bézier med en 2‑pixel bred röd penna.
graphics.drawCubicBezier(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
        new com.aspose.imaging.PointF(0, 0),
        new com.aspose.imaging.PointF(200, 133),
        new com.aspose.imaging.PointF(400, 166),
        new com.aspose.imaging.PointF(600, 400));

// Rita en rasterbild av angiven storlek på den angivna platsen.
// Bilden skalas för att passa den önskade rektangeln.
com.aspose.imaging.RasterImage imageToDraw = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    graphics.drawImage(imageToDraw, new com.aspose.imaging.Point(400, 200), new com.aspose.imaging.Size(100, 50));
} finally {
    imageToDraw.dispose();
}

// Rita en textsträng
graphics.drawString(
        new com.aspose.imaging.Font("Arial", 48, com.aspose.imaging.FontStyle.Regular),
        "Hello World!",
        new com.aspose.imaging.Point(200, 300),
        com.aspose.imaging.Color.getDarkRed());

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
                new com.aspose.imaging.shapes.RectangleShape(
                        new com.aspose.imaging.RectangleF(0, 100, 200, 200)),
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

// Hämta den slutgiltiga SVG-bilden som inkluderar alla ritkommandon
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


Initierar en ny instans av klassen [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Bredden på den utgående Svg-bilden. |
| höjd | int | Bredden på den utgående Svg-bilden. |
| dpi | int | Enhetens upplösning, t.ex. 96 punkter per tum. |

### SvgGraphics2D(SvgImage image) {#SvgGraphics2D-com.aspose.imaging.fileformats.svg.SvgImage-}
```
public SvgGraphics2D(SvgImage image)
```


Initierar en ny instans av klassen [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) | Bilden som ritoperationer ska utföras på. |

### drawImage(RasterImage image, Point origin) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-}
```
public final void drawImage(RasterImage image, Point origin)
```


Ritar den angivna bilden på den angivna platsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Den ritade bilden. |
| origin | [Point](../../com.aspose.imaging/point) | Platsen för den ritade bilden. |

### drawImage(RasterImage image, Point origin, Size size) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public final void drawImage(RasterImage image, Point origin, Size size)
```


Ritar den angivna bilden i den angivna storleken på den angivna platsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Den ritade bilden. |
| origin | [Point](../../com.aspose.imaging/point) | Platsen för den ritade bilden. |
| size | [Size](../../com.aspose.imaging/size) | Den önskade storleken på den ritade bilden. |

### drawImage(Rectangle srcRect, Rectangle destRect, RasterImage image) {#drawImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RasterImage-}
```
public final void drawImage(Rectangle srcRect, Rectangle destRect, RasterImage image)
```


Ritar den angivna delen av den angivna bilden på den angivna platsen och med den angivna storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcRect | [Rectangle](../../com.aspose.imaging/rectangle) | Den del av bildobjektet som ska ritas. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | Platsen och storleken på den ritade bilden. Bilden skalas för att passa rektangeln. |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bilden som ska ritas. |

### drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle) {#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public final void drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)
```


Ritar en båge som representerar en del av en ellips specificerad av en rektangelstruktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pennan för att rita figurens kontur. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Ellipsens gränser. |
| startAngle | float | Vinkeln i grader, mätt medurs från x-axeln till startpunkten för bågen. |
| arcAngle | float | Vinkeln i grader, mätt medurs från startAngle‑parametern till slutpunkten för bågen. |

### fillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle) {#fillArc-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-}
```
public final void fillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle)
```


Fyller en båge som representerar en del av en ellips specificerad av en rektangelstruktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pennan för att rita figurens kontur. |
| brush | [Brush](../../com.aspose.imaging/brush) | Penseln för att fylla figurens inre. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Ellipsens gränser. |
| startAngle | float | Vinkeln i grader, mätt medurs från x-axeln till startpunkten för bågen. |
| arcAngle | float | Vinkeln i grader, mätt medurs från startAngle‑parametern till slutpunkten för bågen. |

### drawCubicBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4) {#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public final void drawCubicBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```


Ritar den kubiska Bézier-kurvan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pennan som bestämmer figurens färg, bredd och stil. |
| pt1 | [PointF](../../com.aspose.imaging/pointf) | Startpunkten för kurvan. |
| pt2 | [PointF](../../com.aspose.imaging/pointf) | Den första kontrollpunkten för kurvan. |
| pt3 | [PointF](../../com.aspose.imaging/pointf) | Den andra kontrollpunkten för kurvan. |
| pt4 | [PointF](../../com.aspose.imaging/pointf) | Slutpunkten för kurvan. |

### drawString(Font font, String text, Point origin, Color textColor) {#drawString-com.aspose.imaging.Font-java.lang.String-com.aspose.imaging.Point-com.aspose.imaging.Color-}
```
public final void drawString(Font font, String text, Point origin, Color textColor)
```


Ritar textsträngen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| font | [Font](../../com.aspose.imaging/font) | Teckensnittet som används för att rendera text. |
| text | java.lang.String | Unicode-textsträngen. |
| origin | [Point](../../com.aspose.imaging/point) | Det övre vänstra hörnet av textkörningen. |
| textColor | [Color](../../com.aspose.imaging/color) | Textfärgen. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.imaging.Pen-int-int-int-int-}
```
public final void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


Ritar linjen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pennan som bestämmer figurens färg, bredd och stil. |
| x1 | int | X-koordinaten för den första punkten. |
| y1 | int | Y-koordinaten för den första punkten. |
| x2 | int | X-koordinaten för den andra punkten. |
| y2 | int | Y-koordinaten för den andra punkten. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-}
```
public final void drawPath(Pen pen, GraphicsPath path)
```


Ritar banan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pennan för att rita figurens kontur. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Sökvägen att rita. |

### fillPath(Pen pen, Brush brush, GraphicsPath path) {#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-}
```
public final void fillPath(Pen pen, Brush brush, GraphicsPath path)
```


Fyller banan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pennan för att rita figurens kontur. |
| brush | [Brush](../../com.aspose.imaging/brush) | Penseln för att fylla figurens inre. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Sökvägen att rita. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-}
```
public final void drawRectangle(Pen pen, int x, int y, int width, int height)
```


Ritar rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pennan för att rita figurens kontur. |
| x | int | X-koordinaten för den övre vänstra hörnet av rektangeln som ska ritas. |
| y | int | Y-koordinaten för den övre vänstra hörnet av rektangeln som ska ritas. |
| bredd | int | Bredden på rektangeln som ska ritas. |
| höjd | int | Höjden på rektangeln som ska ritas. |

### fillRectangle(Pen pen, Brush brush, int x, int y, int width, int height) {#fillRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Brush-int-int-int-int-}
```
public final void fillRectangle(Pen pen, Brush brush, int x, int y, int width, int height)
```


Fyller rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pennan för att rita figurens kontur. |
| brush | [Brush](../../com.aspose.imaging/brush) | Penseln för att fylla figurens inre. |
| x | int | X-koordinaten för den övre vänstra hörnet av rektangeln som ska ritas. |
| y | int | Y-koordinaten för den övre vänstra hörnet av rektangeln som ska ritas. |
| bredd | int | Bredden på rektangeln som ska ritas. |
| höjd | int | Höjden på rektangeln som ska ritas. |

### endRecording() {#endRecording--}
```
public final SvgImage endRecording()
```


Hämtar den slutgiltiga Svg-bilden som inkluderar alla ritkommandon som utförts via objektet [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d).

**Returns:**
[SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) - The final Svg image.
