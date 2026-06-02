---
title: "SolidBrush"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il pennello solido è destinato al disegno continuo con un colore specifico."
type: docs
weight: 17
url: /it/java/com.aspose.imaging.brushes/solidbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush)
```
public final class SolidBrush extends Brush
```

Il pennello solido è destinato al disegno continuo con un colore specifico. Questa classe non può essere ereditata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SolidBrush()](#SolidBrush--) | Inizializza una nuova istanza della classe `SolidBrush`. |
| [SolidBrush(Color color)](#SolidBrush-com.aspose.imaging.Color-) | Inizializza una nuova istanza della classe `SolidBrush`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getColor()](#getColor--) | Ottiene o imposta il colore del pennello. |
| [setColor(Color value)](#setColor-com.aspose.imaging.Color-) | Ottiene o imposta il colore del pennello. |
| [hashCode()](#hashCode--) |  |
| [equals(Object object)](#equals-java.lang.Object-) |  |

## Example: This example uses Graphics class to create primitive shapes on the Image surface.
Questo esempio utilizza la classe Graphics per creare forme primitive sulla superficie dell'Image. Per dimostrare l'operazione, l'esempio crea una nuova Image in formato PNG e disegna forme primitive sulla superficie dell'Image usando i metodi Draw esposti dalla classe Graphics.
``` java
// Crea un'istanza di FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.png", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Crea un'istanza di PngOptions e imposta le sue varie proprietà
    com.aspose.imaging.imageoptions.PngOptions pngOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Imposta la sorgente per PngOptions
    pngOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Crea un'istanza di Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(pngOptions, 500, 500);
    try {
        // Crea e inizializza un'istanza della classe Graphics
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Cancella la superficie Graphics
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Disegna un arco specificando l'oggetto Pen con colore Black com.aspose.imaging.Color,
        // un rettangolo che circonda l'arco, angolo iniziale e angolo di sweep
        graphics.drawArc(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2),
                new com.aspose.imaging.Rectangle(200, 200, 100, 200),
                0,
                300);

        // Disegna un Bezier specificando l'oggetto Pen con colore Blue com.aspose.imaging.Color e i punti di coordinate.
        graphics.drawBezier(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
                new com.aspose.imaging.Point(250, 100),
                new com.aspose.imaging.Point(300, 30),
                new com.aspose.imaging.Point(450, 100),
                new com.aspose.imaging.Point(235, 25));

        // Disegna una curva specificando l'oggetto Pen con colore Green com.aspose.imaging.Color e un array di punti.
        graphics.drawCurve(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(100, 200),
                                new com.aspose.imaging.Point(100, 350),
                                new com.aspose.imaging.Point(200, 450)
                        });

        // Disegna un'ellisse usando l'oggetto Pen e un rettangolo circostante.
        graphics.drawEllipse(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getYellow(), 2),
                new com.aspose.imaging.Rectangle(300, 300, 100, 100));

        // Disegna una linea
        graphics.drawLine(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getViolet(), 2),
                new com.aspose.imaging.Point(100, 100),
                new com.aspose.imaging.Point(200, 200));

        // Disegna un segmento di torta
        graphics.drawPie(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getSilver(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(200, 20), new com.aspose.imaging.Size(200, 200)),
                0,
                45);

        // Disegna un poligono specificando l'oggetto Pen con colore Red com.aspose.imaging.Color e un array di punti.
        graphics.drawPolygon(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(20, 100),
                                new com.aspose.imaging.Point(20, 200),
                                new com.aspose.imaging.Point(220, 20)
                        });

        // Disegna un rettangolo
        graphics.drawRectangle(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(250, 250), new com.aspose.imaging.Size(100, 100)));

        // Crea un oggetto SolidBrush e imposta le sue varie proprietà
        com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush();
        brush.setColor(com.aspose.imaging.Color.getPurple());

        // Disegna una stringa usando l'oggetto SolidBrush e Font, in un punto specifico
        graphics.drawString(
                "This image is created by Aspose.Imaging API",
                new com.aspose.imaging.Font("Times New Roman", 16),
                brush,
                new com.aspose.imaging.PointF(50, 400));

        // Salva tutte le modifiche.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### SolidBrush() {#SolidBrush--}
```
public SolidBrush()
```


Inizializza una nuova istanza della classe `SolidBrush`.

### SolidBrush(Color color) {#SolidBrush-com.aspose.imaging.Color-}
```
public SolidBrush(Color color)
```


Inizializza una nuova istanza della classe `SolidBrush`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | Il colore del pennello solido. |

### getColor() {#getColor--}
```
public Color getColor()
```


Ottiene o imposta il colore del pennello.

Valore: Il colore del pennello.

**Returns:**
[Color](../../com.aspose.imaging/color)

**Example: This example uses Graphics class to create primitive shapes on the Image surface.**
Questo esempio utilizza la classe Graphics per creare forme primitive sulla superficie dell'Image. Per dimostrare l'operazione, l'esempio crea una nuova Image in formato PNG e disegna forme primitive sulla superficie dell'Image usando i metodi Draw esposti dalla classe Graphics.
``` java
// Crea un'istanza di FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.png", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Crea un'istanza di PngOptions e imposta le sue varie proprietà
    com.aspose.imaging.imageoptions.PngOptions pngOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Imposta la sorgente per PngOptions
    pngOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Crea un'istanza di Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(pngOptions, 500, 500);
    try {
        // Crea e inizializza un'istanza della classe Graphics
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Cancella la superficie Graphics
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Disegna un arco specificando l'oggetto Pen con colore Black com.aspose.imaging.Color,
        // un rettangolo che circonda l'arco, angolo iniziale e angolo di sweep
        graphics.drawArc(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2),
                new com.aspose.imaging.Rectangle(200, 200, 100, 200),
                0,
                300);

        // Disegna un Bezier specificando l'oggetto Pen con colore Blue com.aspose.imaging.Color e i punti di coordinate.
        graphics.drawBezier(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
                new com.aspose.imaging.Point(250, 100),
                new com.aspose.imaging.Point(300, 30),
                new com.aspose.imaging.Point(450, 100),
                new com.aspose.imaging.Point(235, 25));

        // Disegna una curva specificando l'oggetto Pen con colore Green com.aspose.imaging.Color e un array di punti.
        graphics.drawCurve(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(100, 200),
                                new com.aspose.imaging.Point(100, 350),
                                new com.aspose.imaging.Point(200, 450)
                        });

        // Disegna un'ellisse usando l'oggetto Pen e un rettangolo circostante.
        graphics.drawEllipse(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getYellow(), 2),
                new com.aspose.imaging.Rectangle(300, 300, 100, 100));

        // Disegna una linea
        graphics.drawLine(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getViolet(), 2),
                new com.aspose.imaging.Point(100, 100),
                new com.aspose.imaging.Point(200, 200));

        // Disegna un segmento di torta
        graphics.drawPie(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getSilver(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(200, 20), new com.aspose.imaging.Size(200, 200)),
                0,
                45);

        // Disegna un poligono specificando l'oggetto Pen con colore Red com.aspose.imaging.Color e un array di punti.
        graphics.drawPolygon(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(20, 100),
                                new com.aspose.imaging.Point(20, 200),
                                new com.aspose.imaging.Point(220, 20)
                        });

        // Disegna un rettangolo
        graphics.drawRectangle(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(250, 250), new com.aspose.imaging.Size(100, 100)));

        // Crea un oggetto SolidBrush e imposta le sue varie proprietà
        com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush();
        brush.setColor(com.aspose.imaging.Color.getPurple());

        // Disegna una stringa usando l'oggetto SolidBrush e Font, in un punto specifico
        graphics.drawString(
                "This image is created by Aspose.Imaging API",
                new com.aspose.imaging.Font("Times New Roman", 16),
                brush,
                new com.aspose.imaging.PointF(50, 400));

        // Salva tutte le modifiche.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### setColor(Color value) {#setColor-com.aspose.imaging.Color-}
```
public void setColor(Color value)
```


Ottiene o imposta il colore del pennello.

Valore: Il colore del pennello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### hashCode() {#hashCode--}
```
public int hashCode()
```


Ottieni il codice hash dell'oggetto corrente.

**Returns:**
int
### equals(Object object) {#equals-java.lang.Object-}
```
public boolean equals(Object object)
```


Verifica se gli oggetti sono uguali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| oggetto | java.lang.Object |  |

**Returns:**
boolean
