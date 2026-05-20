---
title: "HatchBrush"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Definisce un pennello rettangolare con uno stile di tratteggio, un colore di primo piano e un colore di sfondo."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.brushes/hatchbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush)
```
public final class HatchBrush extends Brush
```

Definisce un pennello rettangolare con uno stile di tratteggio, un colore di primo piano e un colore di sfondo. Questa classe non può essere ereditata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [HatchBrush()](#HatchBrush--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getForegroundColor()](#getForegroundColor--) | Restituisce il colore delle linee di tratteggio. |
| [setForegroundColor(Color value)](#setForegroundColor-com.aspose.imaging.Color-) | Imposta il colore delle linee di tratteggio. |
| [getBackgroundColor()](#getBackgroundColor--) | Restituisce il colore degli spazi tra le linee di tratteggio. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Imposta il colore degli spazi tra le linee di tratteggio. |
| [getHatchStyle()](#getHatchStyle--) | Restituisce lo stile di tratteggio di questo pennello. |
| [setHatchStyle(int value)](#setHatchStyle-int-) | Imposta lo stile a trama di questo pennello. |

## Example: This example shows the creation and usage Pen objects.
Questo esempio mostra la creazione e l'uso degli oggetti Pen. L'esempio crea una nuova Image e disegna rettangoli sulla superficie dell'Image.
``` java

// Crea un'istanza di BmpOptions e imposta le sue varie proprietà
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// Crea un'istanza di FileCreateSource e assegnala come Source per l'istanza di BmpOptions
// Il secondo parametro Boolean determina se il file da creare è IsTemporal o meno
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Crea un'istanza di Image nel percorso specificato.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Crea un'istanza di Graphics e inizializzala con l'oggetto Image.
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // Cancella la superficie di Graphics con White Color.
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // Crea un'istanza di Pen con colore Red e larghezza 5.
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // Crea un'istanza di HatchBrush e imposta le sue proprietà.
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // Crea un'istanza di Pen e inizializzala con l'oggetto HatchBrush e la larghezza.
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // Disegna rettangoli specificando l'oggetto Pen.
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // Disegna rettangoli specificando l'oggetto Pen.
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // Salva tutte le modifiche.
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


Restituisce il colore delle linee di tratteggio.

**Returns:**
[Color](../../com.aspose.imaging/color) - The color of hatch lines.
### setForegroundColor(Color value) {#setForegroundColor-com.aspose.imaging.Color-}
```
public void setForegroundColor(Color value)
```


Imposta il colore delle linee di tratteggio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Il colore delle linee a trama. |


**Example: This example shows the creation and usage Pen objects.**
Questo esempio mostra la creazione e l'uso degli oggetti Pen. L'esempio crea una nuova Image e disegna rettangoli sulla superficie dell'Image.
``` java

// Crea un'istanza di BmpOptions e imposta le sue varie proprietà
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// Crea un'istanza di FileCreateSource e assegnala come Source per l'istanza di BmpOptions
// Il secondo parametro Boolean determina se il file da creare è IsTemporal o meno
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Crea un'istanza di Image nel percorso specificato.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Crea un'istanza di Graphics e inizializzala con l'oggetto Image.
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // Cancella la superficie di Graphics con White Color.
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // Crea un'istanza di Pen con colore Red e larghezza 5.
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // Crea un'istanza di HatchBrush e imposta le sue proprietà.
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // Crea un'istanza di Pen e inizializzala con l'oggetto HatchBrush e la larghezza.
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // Disegna rettangoli specificando l'oggetto Pen.
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // Disegna rettangoli specificando l'oggetto Pen.
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // Salva tutte le modifiche.
    image.save();
} finally {
    image.dispose();
}
```

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Restituisce il colore degli spazi tra le linee di tratteggio.

**Returns:**
[Color](../../com.aspose.imaging/color) - The color of spaces between the hatch lines.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Imposta il colore degli spazi tra le linee di tratteggio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Il colore degli spazi tra le linee a trama. |


**Example: This example shows the creation and usage Pen objects.**
Questo esempio mostra la creazione e l'uso degli oggetti Pen. L'esempio crea una nuova Image e disegna rettangoli sulla superficie dell'Image.
``` java

// Crea un'istanza di BmpOptions e imposta le sue varie proprietà
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// Crea un'istanza di FileCreateSource e assegnala come Source per l'istanza di BmpOptions
// Il secondo parametro Boolean determina se il file da creare è IsTemporal o meno
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Crea un'istanza di Image nel percorso specificato.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Crea un'istanza di Graphics e inizializzala con l'oggetto Image.
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // Cancella la superficie di Graphics con White Color.
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // Crea un'istanza di Pen con colore Red e larghezza 5.
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // Crea un'istanza di HatchBrush e imposta le sue proprietà.
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // Crea un'istanza di Pen e inizializzala con l'oggetto HatchBrush e la larghezza.
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // Disegna rettangoli specificando l'oggetto Pen.
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // Disegna rettangoli specificando l'oggetto Pen.
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // Salva tutte le modifiche.
    image.save();
} finally {
    image.dispose();
}
```

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


Restituisce lo stile di tratteggio di questo pennello.

**Returns:**
int
### setHatchStyle(int value) {#setHatchStyle-int-}
```
public void setHatchStyle(int value)
```


Imposta lo stile a trama di questo pennello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

