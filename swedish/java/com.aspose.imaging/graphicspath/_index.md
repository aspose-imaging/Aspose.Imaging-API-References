---
title: "GraphicsPath"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar en serie av sammanlänkade linjer och kurvor."
type: docs
weight: 52
url: /sv/java/com.aspose.imaging/graphicspath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds)
```
public final class GraphicsPath extends ObjectWithBounds
```

Representerar en serie av sammankopplade linjer och kurvor. Denna klass kan inte ärvas.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [GraphicsPath()](#GraphicsPath--) | Initierar en ny instans av klassen `GraphicsPath`. |
| [GraphicsPath(Figure[] figures)](#GraphicsPath-com.aspose.imaging.Figure---) | Initierar en ny instans av klassen `GraphicsPath`. |
| [GraphicsPath(Figure[] figures, int fillMode)](#GraphicsPath-com.aspose.imaging.Figure---int-) | Initierar en ny instans av klassen `GraphicsPath`. |
| [GraphicsPath(int fillMode)](#GraphicsPath-int-) | Initierar en ny instans av klassen `GraphicsPath`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFillMode()](#getFillMode--) | Hämtar en `com.aspose.imaging.FillMode`‑enumeration som bestämmer hur interiören av former i detta `com.aspose.imaging.GraphicsPath` fylls. |
| [setFillMode(int value)](#setFillMode-int-) | Ställer in en `com.aspose.imaging.FillMode`-enumeration som bestämmer hur interiören av former i detta `com.aspose.imaging.GraphicsPath` fylls. |
| [getFigures()](#getFigures--) | Hämtar sökvägsfigurerna. |
| [getBounds()](#getBounds--) | Hämtar eller anger objektets gränser. |
| [reset()](#reset--) | Tömmer grafikvägen och ställer in `com.aspose.imaging.FillMode` till `F:com.aspose.imaging.fillMode.alternate`. |
| [reverse()](#reverse--) | Vänder ordningen på figurer, former och punkter i varje form i detta `com.aspose.imaging.graphicsPath`. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Anger om den angivna punkten finns inom detta `com.aspose.imaging.graphicsPath`. |
| [isVisible(PointF point)](#isVisible-com.aspose.imaging.PointF-) | Anger om den angivna punkten finns inom detta `com.aspose.imaging.graphicsPath`. |
| [isVisible(int x, int y)](#isVisible-int-int-) | Anger om den angivna punkten finns inom detta `com.aspose.imaging.graphicsPath`. |
| [isVisible(Point point)](#isVisible-com.aspose.imaging.Point-) | Anger om den angivna punkten finns inom detta `com.aspose.imaging.graphicsPath`. |
| [isVisible(float x, float y, Graphics graphics)](#isVisible-float-float-com.aspose.imaging.Graphics-) | Anger om den angivna punkten finns inom detta `com.aspose.imaging.GraphicsPath` i den synliga klippregionen för den angivna `com.aspose.imaging.graphics`. |
| [isVisible(PointF pt, Graphics graphics)](#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-) | Anger om den angivna punkten finns inom detta `com.aspose.imaging.graphicsPath`. |
| [isVisible(int x, int y, Graphics graphics)](#isVisible-int-int-com.aspose.imaging.Graphics-) | Anger om den angivna punkten finns inom detta `com.aspose.imaging.GraphicsPath`, med den angivna `com.aspose.imaging.graphics`. |
| [isVisible(Point pt, Graphics graphics)](#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-) | Anger om den angivna punkten finns inom detta `com.aspose.imaging.graphicsPath`. |
| [isOutlineVisible(float x, float y, Pen pen)](#isOutlineVisible-float-float-com.aspose.imaging.Pen-) | Anger om den angivna punkten finns inom (under) konturen av detta `com.aspose.imaging.GraphicsPath` när den ritas med den angivna `com.aspose.imaging.pen`. |
| [isOutlineVisible(PointF point, Pen pen)](#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-) | Anger om den angivna punkten finns inom (under) konturen av detta `com.aspose.imaging.GraphicsPath` när den ritas med den angivna `com.aspose.imaging.pen`. |
| [isOutlineVisible(float x, float y, Pen pen, Graphics graphics)](#isOutlineVisible-float-float-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Anger om den angivna punkten finns inom (under) konturen av detta `com.aspose.imaging.GraphicsPath` när den ritas med den angivna `com.aspose.imaging.Pen` och med den angivna `com.aspose.imaging.graphics`. |
| [isOutlineVisible(PointF pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Anger om den angivna punkten finns inom (under) konturen av detta `com.aspose.imaging.GraphicsPath` när den ritas med den angivna `com.aspose.imaging.Pen` och med den angivna `com.aspose.imaging.graphics`. |
| [isOutlineVisible(int x, int y, Pen pen)](#isOutlineVisible-int-int-com.aspose.imaging.Pen-) | Anger om den angivna punkten finns inom (under) konturen av detta `com.aspose.imaging.GraphicsPath` när den ritas med den angivna `com.aspose.imaging.pen`. |
| [isOutlineVisible(Point point, Pen pen)](#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-) | Anger om den angivna punkten finns inom (under) konturen av detta `com.aspose.imaging.GraphicsPath` när den ritas med den angivna `com.aspose.imaging.pen`. |
| [isOutlineVisible(int x, int y, Pen pen, Graphics graphics)](#isOutlineVisible-int-int-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Anger om den angivna punkten finns inom (under) konturen av detta `com.aspose.imaging.GraphicsPath` när den ritas med den angivna `com.aspose.imaging.Pen` och med den angivna `com.aspose.imaging.graphics`. |
| [isOutlineVisible(Point pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Anger om den angivna punkten finns inom (under) konturen av detta `com.aspose.imaging.GraphicsPath` när den ritas med den angivna `com.aspose.imaging.Pen` och med den angivna `com.aspose.imaging.graphics`. |
| [flatten()](#flatten--) | Omvandlar varje kurva i denna sökväg till en sekvens av sammanhängande linjesegment. |
| [flatten(Matrix matrix)](#flatten-com.aspose.imaging.Matrix-) | Tillämpar den angivna transformen och omvandlar sedan varje kurva i detta `com.aspose.imaging.GraphicsPath` till en sekvens av sammanhängande linjesegment. |
| [flatten(Matrix matrix, float flatness)](#flatten-com.aspose.imaging.Matrix-float-) | Omvandlar varje kurva i detta `com.aspose.imaging.GraphicsPath` till en sekvens av sammanhängande linjesegment. |
| [widen(Pen pen)](#widen-com.aspose.imaging.Pen-) | Lägger till en extra kontur till sökvägen. |
| [widen(Pen pen, Matrix matrix)](#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-) | Lägger till en extra kontur till `com.aspose.imaging.graphicsPath`. |
| [widen(Pen pen, Matrix matrix, float flatness)](#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-float-) | Ersätter detta `com.aspose.imaging.GraphicsPath` med kurvor som omsluter området som fylls när denna sökväg ritas med den angivna pennan. |
| [warp(PointF[] destPoints, RectangleF srcRect)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-) | Tillämpar en warp‑transform, definierad av en rektangel och ett parallellogram, på detta `com.aspose.imaging.graphicsPath`. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-) | Tillämpar en warp‑transform, definierad av en rektangel och ett parallellogram, på detta `com.aspose.imaging.graphicsPath`. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-) | Tillämpar en warp‑transform, definierad av en rektangel och ett parallellogram, på detta `com.aspose.imaging.graphicsPath`. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-float-) | Tillämpar en warp‑transform, definierad av en rektangel och ett parallellogram, på detta `com.aspose.imaging.graphicsPath`. |
| [addFigure(Figure figure)](#addFigure-com.aspose.imaging.Figure-) | Lägger till en ny figur. |
| [addFigures(Figure[] figures)](#addFigures-com.aspose.imaging.Figure---) | Lägger till nya figurer. |
| [removeFigure(Figure figure)](#removeFigure-com.aspose.imaging.Figure-) | Tar bort en figur. |
| [removeFigures(Figure[] figures)](#removeFigures-com.aspose.imaging.Figure---) | Tar bort figurer. |
| [addPath(GraphicsPath addingPath)](#addPath-com.aspose.imaging.GraphicsPath-) | Lägger till den angivna `com.aspose.imaging.GraphicsPath` till denna sökväg. |
| [addPath(GraphicsPath addingPath, boolean connect)](#addPath-com.aspose.imaging.GraphicsPath-boolean-) | Lägger till den angivna `com.aspose.imaging.GraphicsPath` till denna sökväg. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Hämtar objektets gränser. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Hämtar objektets gränser. |
| [deepClone()](#deepClone--) | Utför en djup kloning av denna grafikväg. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Tillämpar den angivna transformationen på formen. |
| [equals(Object o)](#equals-java.lang.Object-) | Kontrollera om objekt är lika. |
| [hashCode()](#hashCode--) | Hämta hashkoden för det aktuella objektet. |

## Example: This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface.
Detta exempel använder GraphicsPath och Graphics-klassen för att skapa och manipulera figurer på en Image-ytan. Exemplet skapar en ny Image (av typen Tiff) och ritar banor med hjälp av GraphicsPath-klassen. I slutet anropas DrawPath‑metoden som exponeras av Graphics-klassen för att rendera banorna på ytan.
``` java
// Skapa en instans av FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.tif", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Skapa en instans av TiffOptions och ställ in dess olika egenskaper
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

    // Ange källan för instansen av ImageOptions
    tiffOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Skapa en instans av Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(tiffOptions, 500, 500);
    try {
        // Skapa och initiera en instans av Graphics-klassen
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Rensa Graphics-ytan
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Skapa en instans av GraphicsPath-klassen
        com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

        // Skapa en instans av Figure-klassen
        com.aspose.imaging.Figure figure = new com.aspose.imaging.Figure();

        // Lägg till Shapes till Figure-objektet
        figure.addShape(new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(10, 10, 300, 300)));
        figure.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
        figure.addShape(
                new com.aspose.imaging.shapes.PieShape(new com.aspose.imaging.RectangleF(
                        new com.aspose.imaging.PointF(250, 250),
                        new com.aspose.imaging.SizeF(200, 200)),
                        0, 45));

        // Lägg till Figure-objektet i GraphicsPath
        graphicspath.addFigure(figure);

        // Rita bana med Pen-objekt av färgen Black
        graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

        // Spara alla ändringar.
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


Initierar en ny instans av klassen `GraphicsPath`.

### GraphicsPath(Figure[] figures) {#GraphicsPath-com.aspose.imaging.Figure---}
```
public GraphicsPath(Figure[] figures)
```


Initierar en ny instans av klassen `GraphicsPath`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | Figurerna att initiera från. |

### GraphicsPath(Figure[] figures, int fillMode) {#GraphicsPath-com.aspose.imaging.Figure---int-}
```
public GraphicsPath(Figure[] figures, int fillMode)
```


Initierar en ny instans av klassen `GraphicsPath`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | Figurerna att initiera från. |
| fillMode | int | Fyllningsläget. |

### GraphicsPath(int fillMode) {#GraphicsPath-int-}
```
public GraphicsPath(int fillMode)
```


Initierar en ny instans av klassen `GraphicsPath`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fillMode | int | Fyllningsläget. |

### getFillMode() {#getFillMode--}
```
public int getFillMode()
```


Hämtar en `com.aspose.imaging.FillMode`‑enumeration som bestämmer hur interiören av former i detta `com.aspose.imaging.GraphicsPath` fylls.

**Returns:**
int - Fyllningsläget. En `com.aspose.imaging.FillMode`-enumeration som specificerar hur innanmålen av former i detta `com.aspose.imaging.GraphicsPath` fylls.
### setFillMode(int value) {#setFillMode-int-}
```
public void setFillMode(int value)
```


Ställer in en `com.aspose.imaging.FillMode`-enumeration som bestämmer hur interiören av former i detta `com.aspose.imaging.GraphicsPath` fylls.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Fyllningsläget. |

### getFigures() {#getFigures--}
```
public Figure[] getFigures()
```


Hämtar sökvägsfigurerna.

**Returns:**
com.aspose.imaging.Figure[] - Sökvägsfigurerna.
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Hämtar eller anger objektets gränser.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The object's bounds.
### reset() {#reset--}
```
public void reset()
```


Tömmer grafikvägen och ställer in `com.aspose.imaging.FillMode` till `F:com.aspose.imaging.fillMode.alternate`.

### reverse() {#reverse--}
```
public void reverse()
```


Vänder ordningen på figurer, former och punkter i varje form i detta `com.aspose.imaging.graphicsPath`.

### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Anger om den angivna punkten finns inom detta `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för punkten som ska testas. |
| y | float | Y-koordinaten för punkten som ska testas. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom detta `com.aspose.imaging.GraphicsPath`; annars false.
### isVisible(PointF point) {#isVisible-com.aspose.imaging.PointF-}
```
public boolean isVisible(PointF point)
```


Anger om den angivna punkten finns inom detta `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Ett `com.aspose.imaging.PointF` som representerar punkten som ska testas. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom detta `com.aspose.imaging.GraphicsPath`; annars false.
### isVisible(int x, int y) {#isVisible-int-int-}
```
public boolean isVisible(int x, int y)
```


Anger om den angivna punkten finns inom detta `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | X-koordinaten för punkten som ska testas. |
| y | int | Y-koordinaten för punkten som ska testas. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom detta `com.aspose.imaging.GraphicsPath`; annars false.
### isVisible(Point point) {#isVisible-com.aspose.imaging.Point-}
```
public boolean isVisible(Point point)
```


Anger om den angivna punkten finns inom detta `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Ett `com.aspose.imaging.Point` som representerar punkten som ska testas. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom detta `com.aspose.imaging.GraphicsPath`; annars false.
### isVisible(float x, float y, Graphics graphics) {#isVisible-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, Graphics graphics)
```


Anger om den angivna punkten finns inom detta `com.aspose.imaging.GraphicsPath` i den synliga klippregionen för den angivna `com.aspose.imaging.graphics`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för punkten som ska testas. |
| y | float | Y-koordinaten för punkten som ska testas. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Den `com.aspose.imaging.Graphics` som synligheten ska testas för. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom detta `com.aspose.imaging.GraphicsPath`; annars false.
### isVisible(PointF pt, Graphics graphics) {#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(PointF pt, Graphics graphics)
```


Anger om den angivna punkten finns inom detta `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.imaging/pointf) | Ett `com.aspose.imaging.PointF` som representerar punkten som ska testas. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Den `com.aspose.imaging.Graphics` som synligheten ska testas för. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom detta; annars false.
### isVisible(int x, int y, Graphics graphics) {#isVisible-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, Graphics graphics)
```


Anger om den angivna punkten finns inom detta `com.aspose.imaging.GraphicsPath`, med den angivna `com.aspose.imaging.graphics`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | X-koordinaten för punkten som ska testas. |
| y | int | Y-koordinaten för punkten som ska testas. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Den `com.aspose.imaging.Graphics` som synligheten ska testas för. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom detta `com.aspose.imaging.GraphicsPath`; annars false.
### isVisible(Point pt, Graphics graphics) {#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Point pt, Graphics graphics)
```


Anger om den angivna punkten finns inom detta `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pt | [Point](../../com.aspose.imaging/point) | Ett `com.aspose.imaging.Point` som representerar punkten som ska testas. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Den `com.aspose.imaging.Graphics` som synligheten ska testas för. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom detta `com.aspose.imaging.GraphicsPath`; annars false.
### isOutlineVisible(float x, float y, Pen pen) {#isOutlineVisible-float-float-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(float x, float y, Pen pen)
```


Anger om den angivna punkten finns inom (under) konturen av detta `com.aspose.imaging.GraphicsPath` när den ritas med den angivna `com.aspose.imaging.pen`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för punkten som ska testas. |
| y | float | Y-koordinaten för punkten som ska testas. |
| pen | [Pen](../../com.aspose.imaging/pen) | Den `com.aspose.imaging.Pen` som ska testas. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom konturen av detta `com.aspose.imaging.GraphicsPath` när den ritas med den angivna `com.aspose.imaging.Pen`; annars false.
### isOutlineVisible(PointF point, Pen pen) {#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(PointF point, Pen pen)
```


Anger om den angivna punkten finns inom (under) konturen av detta `com.aspose.imaging.GraphicsPath` när den ritas med den angivna `com.aspose.imaging.pen`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Ett `com.aspose.imaging.PointF` som specificerar platsen som ska testas. |
| pen | [Pen](../../com.aspose.imaging/pen) | Den `com.aspose.imaging.Pen` som ska testas. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom konturen av detta `com.aspose.imaging.GraphicsPath` när den ritas med den angivna `com.aspose.imaging.Pen`; annars false.
### isOutlineVisible(float x, float y, Pen pen, Graphics graphics) {#isOutlineVisible-float-float-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(float x, float y, Pen pen, Graphics graphics)
```


Anger om den angivna punkten finns inom (under) konturen av detta `com.aspose.imaging.GraphicsPath` när den ritas med den angivna `com.aspose.imaging.Pen` och med den angivna `com.aspose.imaging.graphics`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för punkten som ska testas. |
| y | float | Y-koordinaten för punkten som ska testas. |
| pen | [Pen](../../com.aspose.imaging/pen) | Den `com.aspose.imaging.Pen` som ska testas. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Den `com.aspose.imaging.Graphics` som synligheten ska testas för. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom (under) konturen av detta `com.aspose.imaging.GraphicsPath` som ritas med den angivna `com.aspose.imaging.Pen`; annars false.
### isOutlineVisible(PointF pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(PointF pt, Pen pen, Graphics graphics)
```


Anger om den angivna punkten finns inom (under) konturen av detta `com.aspose.imaging.GraphicsPath` när den ritas med den angivna `com.aspose.imaging.Pen` och med den angivna `com.aspose.imaging.graphics`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.imaging/pointf) | Ett `com.aspose.imaging.PointF` som specificerar platsen som ska testas. |
| pen | [Pen](../../com.aspose.imaging/pen) | Den `com.aspose.imaging.Pen` som ska testas. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Den `com.aspose.imaging.Graphics` som synligheten ska testas för. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom (under) konturen av detta `com.aspose.imaging.GraphicsPath` som ritas med den angivna `com.aspose.imaging.Pen`; annars false.
### isOutlineVisible(int x, int y, Pen pen) {#isOutlineVisible-int-int-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(int x, int y, Pen pen)
```


Anger om den angivna punkten finns inom (under) konturen av detta `com.aspose.imaging.GraphicsPath` när den ritas med den angivna `com.aspose.imaging.pen`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | X-koordinaten för punkten som ska testas. |
| y | int | Y-koordinaten för punkten som ska testas. |
| pen | [Pen](../../com.aspose.imaging/pen) | Den `com.aspose.imaging.Pen` som ska testas. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom konturen av detta `com.aspose.imaging.GraphicsPath` när den ritas med den angivna `com.aspose.imaging.Pen`; annars false.
### isOutlineVisible(Point point, Pen pen) {#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(Point point, Pen pen)
```


Anger om den angivna punkten finns inom (under) konturen av detta `com.aspose.imaging.GraphicsPath` när den ritas med den angivna `com.aspose.imaging.pen`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Ett `com.aspose.imaging.Point` som specificerar platsen som ska testas. |
| pen | [Pen](../../com.aspose.imaging/pen) | Den `com.aspose.imaging.Pen` som ska testas. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom konturen av detta `com.aspose.imaging.GraphicsPath` när den ritas med den angivna `com.aspose.imaging.Pen`; annars false.
### isOutlineVisible(int x, int y, Pen pen, Graphics graphics) {#isOutlineVisible-int-int-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(int x, int y, Pen pen, Graphics graphics)
```


Anger om den angivna punkten finns inom (under) konturen av detta `com.aspose.imaging.GraphicsPath` när den ritas med den angivna `com.aspose.imaging.Pen` och med den angivna `com.aspose.imaging.graphics`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | X-koordinaten för punkten som ska testas. |
| y | int | Y-koordinaten för punkten som ska testas. |
| pen | [Pen](../../com.aspose.imaging/pen) | Den `com.aspose.imaging.Pen` som ska testas. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Den `com.aspose.imaging.Graphics` som synligheten ska testas för. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom konturen av detta `com.aspose.imaging.GraphicsPath` som ritas med den angivna `com.aspose.imaging.Pen`; annars false.
### isOutlineVisible(Point pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(Point pt, Pen pen, Graphics graphics)
```


Anger om den angivna punkten finns inom (under) konturen av detta `com.aspose.imaging.GraphicsPath` när den ritas med den angivna `com.aspose.imaging.Pen` och med den angivna `com.aspose.imaging.graphics`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pt | [Point](../../com.aspose.imaging/point) | Ett `com.aspose.imaging.Point` som specificerar platsen som ska testas. |
| pen | [Pen](../../com.aspose.imaging/pen) | Den `com.aspose.imaging.Pen` som ska testas. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Den `com.aspose.imaging.Graphics` som synligheten ska testas för. |

**Returns:**
boolean - Denna metod returnerar true om den angivna punkten finns inom konturen av detta `com.aspose.imaging.GraphicsPath` som ritas med den angivna `com.aspose.imaging.Pen`; annars false.
### flatten() {#flatten--}
```
public void flatten()
```


Omvandlar varje kurva i denna sökväg till en sekvens av sammanhängande linjesegment.

### flatten(Matrix matrix) {#flatten-com.aspose.imaging.Matrix-}
```
public void flatten(Matrix matrix)
```


Tillämpar den angivna transformen och omvandlar sedan varje kurva i detta `com.aspose.imaging.GraphicsPath` till en sekvens av sammanhängande linjesegment.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | En `com.aspose.imaging.Matrix` som används för att transformera detta `com.aspose.imaging.GraphicsPath` före plattning. |

### flatten(Matrix matrix, float flatness) {#flatten-com.aspose.imaging.Matrix-float-}
```
public void flatten(Matrix matrix, float flatness)
```


Omvandlar varje kurva i detta `com.aspose.imaging.GraphicsPath` till en sekvens av sammanhängande linjesegment.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | En `com.aspose.imaging.Matrix` som används för att transformera detta `com.aspose.imaging.GraphicsPath` före plattning. |
| platthet | float | Anger det maximalt tillåtna felet mellan kurvan och dess plattade approximation. Ett värde på 0,25 är standard. Att minska platthetsvärdet kommer att öka antalet linjesegment i approximationen. |

### widen(Pen pen) {#widen-com.aspose.imaging.Pen-}
```
public void widen(Pen pen)
```


Lägger till en extra kontur till sökvägen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | En `com.aspose.imaging.Pen` som specificerar bredden mellan den ursprungliga konturen av sökvägen och den nya kontur som denna metod skapar. |

### widen(Pen pen, Matrix matrix) {#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-}
```
public void widen(Pen pen, Matrix matrix)
```


Lägger till en extra kontur till `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | En `com.aspose.imaging.Pen` som specificerar bredden mellan den ursprungliga konturen av sökvägen och den nya kontur som denna metod skapar. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | En `com.aspose.imaging.Matrix` som specificerar en transformation att tillämpa på sökvägen före breddning. |

### widen(Pen pen, Matrix matrix, float flatness) {#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-float-}
```
public void widen(Pen pen, Matrix matrix, float flatness)
```


Ersätter detta `com.aspose.imaging.GraphicsPath` med kurvor som omsluter området som fylls när denna sökväg ritas med den angivna pennan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | En `com.aspose.imaging.Pen` som specificerar bredden mellan den ursprungliga konturen av sökvägen och den nya kontur som denna metod skapar. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | En `com.aspose.imaging.Matrix` som specificerar en transformation att tillämpa på sökvägen före breddning. |
| platthet | float | Ett värde som specificerar plattheten för kurvor. |

### warp(PointF[] destPoints, RectangleF srcRect) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-}
```
public void warp(PointF[] destPoints, RectangleF srcRect)
```


Tillämpar en warp‑transform, definierad av en rektangel och ett parallellogram, på detta `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | En array av `com.aspose.imaging.PointF`-strukturer som definierar ett parallellogram som rektangeln definierad av `srcRect` transformeras till. Arrayen kan innehålla antingen tre eller fyra element. Om arrayen innehåller tre element, innebärs det nedre högra hörnet av parallellogrammet av de första tre punkterna. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | Ett `com.aspose.imaging.RectangleF` som representerar rektangeln som transformeras till parallellogrammet definierat av `destPoints`. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```


Tillämpar en warp‑transform, definierad av en rektangel och ett parallellogram, på detta `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | En array av `com.aspose.imaging.PointF`-strukturer som definierar ett parallellogram som rektangeln definierad av `srcRect` transformeras till. Arrayen kan innehålla antingen tre eller fyra element. Om arrayen innehåller tre element, innebärs det nedre högra hörnet av parallellogrammet av de första tre punkterna. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | Ett `com.aspose.imaging.RectangleF` som representerar rektangeln som transformeras till parallellogrammet definierat av `destPoints`. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | En `com.aspose.imaging.Matrix` som specificerar en geometrisk transformation att tillämpa på sökvägen. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)
```


Tillämpar en warp‑transform, definierad av en rektangel och ett parallellogram, på detta `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | En array av `com.aspose.imaging.PointF`-strukturer som definierar ett parallellogram som rektangeln definierad av `srcRect` transformeras till. Arrayen kan innehålla antingen tre eller fyra element. Om arrayen innehåller tre element, innebärs det nedre högra hörnet av parallellogrammet av de första tre punkterna. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | Ett `com.aspose.imaging.RectangleF` som representerar rektangeln som transformeras till parallellogrammet definierat av `destPoints`. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | En `com.aspose.imaging.Matrix` som specificerar en geometrisk transformation att tillämpa på sökvägen. |
| warpMode | int | En `com.aspose.imaging.WarpMode`-enumeration som specificerar om denna warp-operation använder perspektiv- eller bilineärt läge. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-float-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)
```


Tillämpar en warp‑transform, definierad av en rektangel och ett parallellogram, på detta `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | En array av `com.aspose.imaging.PointF`-strukturer som definierar ett parallellogram som rektangeln definierad av `srcRect` transformeras till. Arrayen kan innehålla antingen tre eller fyra element. Om arrayen innehåller tre element, innebärs det nedre högra hörnet av parallellogrammet av de första tre punkterna. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | Ett `com.aspose.imaging.RectangleF` som representerar rektangeln som transformeras till parallellogrammet definierat av `destPoints`. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | En `com.aspose.imaging.Matrix` som specificerar en geometrisk transformation att tillämpa på sökvägen. |
| warpMode | int | En `com.aspose.imaging.WarpMode`-enumeration som specificerar om denna warp-operation använder perspektiv- eller bilineärt läge. |
| platthet | float | Ett värde från 0 till 1 som anger hur platt den resulterande vägen är. För mer information, se metoderna `com.aspose.imaging.GraphicsPath.flatten`. |

### addFigure(Figure figure) {#addFigure-com.aspose.imaging.Figure-}
```
public void addFigure(Figure figure)
```


Lägger till en ny figur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.imaging/figure) | Figuren att lägga till. |


**Example: This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface.**
Detta exempel använder GraphicsPath och Graphics-klassen för att skapa och manipulera figurer på en Image-ytan. Exemplet skapar en ny Image (av typen Tiff) och ritar banor med hjälp av GraphicsPath-klassen. I slutet anropas DrawPath‑metoden som exponeras av Graphics-klassen för att rendera banorna på ytan.
``` java
// Skapa en instans av FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.tif", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Skapa en instans av TiffOptions och ställ in dess olika egenskaper
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

    // Ange källan för instansen av ImageOptions
    tiffOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Skapa en instans av Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(tiffOptions, 500, 500);
    try {
        // Skapa och initiera en instans av Graphics-klassen
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Rensa Graphics-ytan
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Skapa en instans av GraphicsPath-klassen
        com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

        // Skapa en instans av Figure-klassen
        com.aspose.imaging.Figure figure = new com.aspose.imaging.Figure();

        // Lägg till Shapes till Figure-objektet
        figure.addShape(new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(10, 10, 300, 300)));
        figure.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
        figure.addShape(
                new com.aspose.imaging.shapes.PieShape(new com.aspose.imaging.RectangleF(
                        new com.aspose.imaging.PointF(250, 250),
                        new com.aspose.imaging.SizeF(200, 200)),
                        0, 45));

        // Lägg till Figure-objektet i GraphicsPath
        graphicspath.addFigure(figure);

        // Rita bana med Pen-objekt av färgen Black
        graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

        // Spara alla ändringar.
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


Lägger till nya figurer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | Figurerna att lägga till. |


**Example: This example creates a new Image and draws a variety of shapes using Figures and GraphicsPath o...**
Detta exempel skapar en ny Image och ritar en mängd olika former med hjälp av Figures och GraphicsPath på Image-ytan.
``` java
//Skapar en instans av BmpOptions och sätter dess olika egenskaper.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//Skapa en instans av FileCreateSource och tilldela den som Source för BmpOptions‑instansen.
//Den andra booleska parametern avgör om filen som ska skapas är temporär eller inte.
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\output.bmp", false));

//Skapa en instans av Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //Skapa och initiera en instans av Graphics-klassen
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //Rensa Graphics-ytan
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //Skapa en instans av GraphicsPath-klassen
    com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

    //Skapa en instans av Figure-klassen
    com.aspose.imaging.Figure figure1 = new com.aspose.imaging.Figure();

    //Lägg till Shape i Figure-objektet.
    figure1.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
    figure1.addShape(new com.aspose.imaging.shapes.PieShape(
            new com.aspose.imaging.RectangleF(
                    new com.aspose.imaging.PointF(110, 110),
                    new com.aspose.imaging.SizeF(200, 200)), 0, 90));

    //Skapa en instans av Figure-klassen
    com.aspose.imaging.Figure figure2 = new com.aspose.imaging.Figure();

    //Lägg till Shape i Figure-objektet.
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

    //Lägg till Figure-objektet i GraphicsPath
    graphicspath.addFigures(new com.aspose.imaging.Figure[]{figure1, figure2});

    //Rita bana med Pen-objekt av färgen Black
    graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

    // spara alla ändringar.
    image.save();
} finally {
    image.dispose();
}
```

### removeFigure(Figure figure) {#removeFigure-com.aspose.imaging.Figure-}
```
public void removeFigure(Figure figure)
```


Tar bort en figur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.imaging/figure) | Figuren att ta bort. |

### removeFigures(Figure[] figures) {#removeFigures-com.aspose.imaging.Figure---}
```
public void removeFigures(Figure[] figures)
```


Tar bort figurer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | Figurerna att ta bort. |

### addPath(GraphicsPath addingPath) {#addPath-com.aspose.imaging.GraphicsPath-}
```
public void addPath(GraphicsPath addingPath)
```


Lägger till den angivna `com.aspose.imaging.GraphicsPath` till denna sökväg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | `com.aspose.imaging.GraphicsPath` att lägga till. |

### addPath(GraphicsPath addingPath, boolean connect) {#addPath-com.aspose.imaging.GraphicsPath-boolean-}
```
public void addPath(GraphicsPath addingPath, boolean connect)
```


Lägger till den angivna `com.aspose.imaging.GraphicsPath` till denna sökväg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | `com.aspose.imaging.GraphicsPath` att lägga till. |
| anslut | boolean | Ett booleskt värde som anger om den första figuren i den tillagda vägen är en del av den sista figuren i denna väg. Ett värde av true anger att den första figuren i den tillagda vägen är en del av den sista figuren i denna väg. Ett värde av false anger att den första figuren i den tillagda vägen är separerad från den sista figuren i denna väg. |

### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Hämtar objektets gränser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Matriser att tillämpa innan gränser beräknas. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Hämtar objektets gränser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Matriser att tillämpa innan gränser beräknas. |
| pen | [Pen](../../com.aspose.imaging/pen) | Pennan att använda för objektet. Detta kan påverka objektets gränsstorlek. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### deepClone() {#deepClone--}
```
public GraphicsPath deepClone()
```


Utför en djup kloning av denna grafikväg.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - A deep clone of the graphics path.
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


Tillämpar den angivna transformationen på formen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | Transformationen att tillämpa. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Kontrollera om objekt är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| o | java.lang.Object | Det andra objektet. |

**Returns:**
boolean - Resultatet av likhetsjämförelsen.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hämta hashkoden för det aktuella objektet.

**Returns:**
int - Hashkoden.
