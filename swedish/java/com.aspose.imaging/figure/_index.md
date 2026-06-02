---
title: "Figure"
second_title: "Aspose.Imaging för Java API-referens"
description: "Figuren."
type: docs
weight: 44
url: /sv/java/com.aspose.imaging/figure/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds)
```
public class Figure extends ObjectWithBounds
```

Figuren. En behållare för former.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Figure()](#Figure--) | Initierar en ny [Figure](../../com.aspose.imaging/figure) instans. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getShapes()](#getShapes--) | Hämtar figurens former. |
| [getBounds()](#getBounds--) | Hämtar eller anger objektets gränser. |
| [isClosed()](#isClosed--) | Hämtar ett värde som indikerar om denna figur är sluten. |
| [setClosed(boolean value)](#setClosed-boolean-) | Anger ett värde som indikerar om denna figur är sluten. |
| [getSegments()](#getSegments--) | Hämtar hela figurens segment. |
| [addShape(Shape shape)](#addShape-com.aspose.imaging.Shape-) | Lägger till en form i figuren. |
| [addShapes(Shape[] shapes)](#addShapes-com.aspose.imaging.Shape---) | Lägger till ett intervall av former i figuren. |
| [removeShape(Shape shape)](#removeShape-com.aspose.imaging.Shape-) | Tar bort en form från figuren. |
| [removeShapes(Shape[] shapes)](#removeShapes-com.aspose.imaging.Shape---) | Tar bort ett intervall av former från figuren. |
| [reverse()](#reverse--) | Vänder på figurens formordning och formens punktordning. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Hämtar objektets gränser. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Hämtar objektets gränser. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Tillämpar den angivna transformationen på formen. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om det angivna objektet är lika med det aktuella objektet. |
| [hashCode()](#hashCode--) | Fungerar som standardhashfunktion. |

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

### Figure() {#Figure--}
```
public Figure()
```


Initierar en ny [Figure](../../com.aspose.imaging/figure)-instans. En konstruktor som krävs för JSON-deserialisering.

### getShapes() {#getShapes--}
```
public Shape[] getShapes()
```


Hämtar figurens former.

**Returns:**
com.aspose.imaging.Shape[] - Figurens former.
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Hämtar eller anger objektets gränser.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The object's bounds.
### isClosed() {#isClosed--}
```
public boolean isClosed()
```


Hämtar ett värde som indikerar om denna figur är sluten. En sluten figur gör endast skillnad när den första och den sista figurens former är kontinuerliga former. I så fall kommer den första punkten i den första formen att kopplas ihop med en rak linje från den sista punkten i den sista formen.

**Returns:**
boolean - `True` om denna figur är sluten; annars, `false`.
### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Ställer in ett värde som indikerar om denna figur är sluten. En sluten figur gör endast skillnad när den första och den sista figurens former är kontinuerliga former. I så fall kommer den första punkten i den första formen att kopplas ihop med en rak linje från den sista punkten i den sista formen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | `True` om denna figur är sluten; annars, `false`. |

### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Hämtar hela figurens segment.

**Returns:**
com.aspose.imaging.ShapeSegment[] - Figurens segment.
### addShape(Shape shape) {#addShape-com.aspose.imaging.Shape-}
```
public void addShape(Shape shape)
```


Lägger till en form i figuren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.imaging/shape) | Formen att lägga till. |


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

### addShapes(Shape[] shapes) {#addShapes-com.aspose.imaging.Shape---}
```
public void addShapes(Shape[] shapes)
```


Lägger till ett intervall av former i figuren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.imaging/shape) | Formerna att lägga till. |

### removeShape(Shape shape) {#removeShape-com.aspose.imaging.Shape-}
```
public void removeShape(Shape shape)
```


Tar bort en form från figuren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.imaging/shape) | Formen att ta bort. |

### removeShapes(Shape[] shapes) {#removeShapes-com.aspose.imaging.Shape---}
```
public void removeShapes(Shape[] shapes)
```


Tar bort ett intervall av former från figuren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.imaging/shape) | Omfånget av former att ta bort. |

### reverse() {#reverse--}
```
public void reverse()
```


Vänder på figurens formordning och formens punktordning.

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
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


Tillämpar den angivna transformationen på formen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | Transformationen att tillämpa. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om det angivna objektet är lika med det aktuella objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Det jämförda objektet. |

**Returns:**
boolean - Resultatet av equals
### hashCode() {#hashCode--}
```
public int hashCode()
```


Fungerar som standardhashfunktion.

**Returns:**
int - En hashkod för det aktuella objektet.
