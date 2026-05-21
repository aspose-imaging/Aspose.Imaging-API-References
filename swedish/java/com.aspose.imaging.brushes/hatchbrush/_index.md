---
title: "HatchBrush"
second_title: "Aspose.Imaging för Java API-referens"
description: "Definierar en rektangulär pensel med ett hatch‑mönster, en förgrundsfärg och en bakgrundsfärg."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.brushes/hatchbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush)
```
public final class HatchBrush extends Brush
```

Definierar en rektangulär pensel med ett hatch‑mönster, en förgrundsfärg och en bakgrundsfärg. Denna klass kan inte ärvas.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [HatchBrush()](#HatchBrush--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getForegroundColor()](#getForegroundColor--) | Hämtar färgen på hatch‑linjerna. |
| [setForegroundColor(Color value)](#setForegroundColor-com.aspose.imaging.Color-) | Ställer in färgen på hatch‑linjerna. |
| [getBackgroundColor()](#getBackgroundColor--) | Hämtar färgen på utrymmena mellan hatch‑linjerna. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Ställer in färgen på utrymmena mellan hatch‑linjerna. |
| [getHatchStyle()](#getHatchStyle--) | Hämtar hatch‑stilen för denna pensel. |
| [setHatchStyle(int value)](#setHatchStyle-int-) | Ställer in hakstil för denna pensel. |

## Example: This example shows the creation and usage Pen objects.
Detta exempel visar skapandet och användningen av Pen-objekt. Exemplet skapar en ny Image och ritar rektanglar på Image-ytan.
``` java

// Skapa en instans av BmpOptions och sätt dess olika egenskaper.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// Skapa en instans av FileCreateSource och tilldela den som Source för BmpOptions‑instansen.
// Den andra booleska parametern avgör om filen som ska skapas är temporär eller inte.
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Skapa en instans av Image på angiven sökväg
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Skapa en instans av Graphics och initiera den med Image-objektet
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // Rensa Graphics-ytan med vit färg
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // Skapa en instans av Pen med färgen Röd och bredd 5
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // Skapa en instans av HatchBrush och ställ in dess egenskaper
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // Skapa en instans av Pen och initiera den med HatchBrush-objektet och bredd
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // Rita rektanglar genom att ange Pen-objektet
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // Rita rektanglar genom att ange Pen-objektet
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // Spara alla ändringar.
    image.save();
} finally {
    image.dispose();
}
```

### HatchBrush() {#HatchBrush--}
```
public HatchBrush()
```


### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Hämtar färgen på hatch‑linjerna.

**Returns:**
[Color](../../com.aspose.imaging/color) - The color of hatch lines.
### setForegroundColor(Color value) {#setForegroundColor-com.aspose.imaging.Color-}
```
public void setForegroundColor(Color value)
```


Ställer in färgen på hatch‑linjerna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Färgen på haklinjerna. |


**Example: This example shows the creation and usage Pen objects.**
Detta exempel visar skapandet och användningen av Pen-objekt. Exemplet skapar en ny Image och ritar rektanglar på Image-ytan.
``` java

// Skapa en instans av BmpOptions och sätt dess olika egenskaper.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// Skapa en instans av FileCreateSource och tilldela den som Source för BmpOptions‑instansen.
// Den andra booleska parametern avgör om filen som ska skapas är temporär eller inte.
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Skapa en instans av Image på angiven sökväg
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Skapa en instans av Graphics och initiera den med Image-objektet
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // Rensa Graphics-ytan med vit färg
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // Skapa en instans av Pen med färgen Röd och bredd 5
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // Skapa en instans av HatchBrush och ställ in dess egenskaper
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // Skapa en instans av Pen och initiera den med HatchBrush-objektet och bredd
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // Rita rektanglar genom att ange Pen-objektet
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // Rita rektanglar genom att ange Pen-objektet
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // Spara alla ändringar.
    image.save();
} finally {
    image.dispose();
}
```

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Hämtar färgen på utrymmena mellan hatch‑linjerna.

**Returns:**
[Color](../../com.aspose.imaging/color) - The color of spaces between the hatch lines.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Ställer in färgen på utrymmena mellan hatch‑linjerna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Färgen på utrymmena mellan haklinjerna. |


**Example: This example shows the creation and usage Pen objects.**
Detta exempel visar skapandet och användningen av Pen-objekt. Exemplet skapar en ny Image och ritar rektanglar på Image-ytan.
``` java

// Skapa en instans av BmpOptions och sätt dess olika egenskaper.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// Skapa en instans av FileCreateSource och tilldela den som Source för BmpOptions‑instansen.
// Den andra booleska parametern avgör om filen som ska skapas är temporär eller inte.
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Skapa en instans av Image på angiven sökväg
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Skapa en instans av Graphics och initiera den med Image-objektet
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // Rensa Graphics-ytan med vit färg
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // Skapa en instans av Pen med färgen Röd och bredd 5
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // Skapa en instans av HatchBrush och ställ in dess egenskaper
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // Skapa en instans av Pen och initiera den med HatchBrush-objektet och bredd
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // Rita rektanglar genom att ange Pen-objektet
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // Rita rektanglar genom att ange Pen-objektet
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // Spara alla ändringar.
    image.save();
} finally {
    image.dispose();
}
```

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


Hämtar hatch‑stilen för denna pensel.

**Returns:**
int
### setHatchStyle(int value) {#setHatchStyle-int-}
```
public void setHatchStyle(int value)
```


Ställer in hakstil för denna pensel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

