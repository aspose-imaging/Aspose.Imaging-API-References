---
title: "Figure"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "La figura."
type: docs
weight: 44
url: /it/java/com.aspose.imaging/figure/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds)
```
public class Figure extends ObjectWithBounds
```

La figura. Un contenitore per forme.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Figure()](#Figure--) | Inizializza una nuova istanza di [Figure](../../com.aspose.imaging/figure). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getShapes()](#getShapes--) | Ottiene le forme della figura. |
| [getBounds()](#getBounds--) | Ottiene o imposta i limiti dell'oggetto. |
| [isClosed()](#isClosed--) | Ottiene un valore che indica se questa figura è chiusa. |
| [setClosed(boolean value)](#setClosed-boolean-) | Imposta un valore che indica se questa figura è chiusa. |
| [getSegments()](#getSegments--) | Ottiene tutti i segmenti della figura. |
| [addShape(Shape shape)](#addShape-com.aspose.imaging.Shape-) | Aggiunge una forma alla figura. |
| [addShapes(Shape[] shapes)](#addShapes-com.aspose.imaging.Shape---) | Aggiunge un intervallo di forme alla figura. |
| [removeShape(Shape shape)](#removeShape-com.aspose.imaging.Shape-) | Rimuove una forma dalla figura. |
| [removeShapes(Shape[] shapes)](#removeShapes-com.aspose.imaging.Shape---) | Rimuove un intervallo di forme dalla figura. |
| [reverse()](#reverse--) | Inverte l'ordine delle forme di questa figura e l'ordine dei punti delle forme. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Ottiene i limiti dell'oggetto. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Ottiene i limiti dell'oggetto. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Applica la trasformazione specificata alla forma. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se l'oggetto specificato è uguale all'oggetto corrente. |
| [hashCode()](#hashCode--) | Funziona come funzione hash predefinita. |

## Example: This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface.
Questo esempio utilizza le classi GraphicsPath e Graphics per creare e manipolare Figure su una superficie Image. L'esempio crea una nuova Image (di tipo Tiff) e disegna percorsi con l'aiuto della classe GraphicsPath. Alla fine viene chiamato il metodo DrawPath esposto dalla classe Graphics per renderizzare i percorsi sulla superficie.
``` java
// Crea un'istanza di FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.tif", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Crea un'istanza di TiffOptions e imposta le sue varie proprietà
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

    // Imposta l'origine per l'istanza di ImageOptions
    tiffOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Crea un'istanza di Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(tiffOptions, 500, 500);
    try {
        // Crea e inizializza un'istanza della classe Graphics
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Cancella la superficie Graphics
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Crea un'istanza della classe GraphicsPath
        com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

        // Crea un'istanza della classe Figure
        com.aspose.imaging.Figure figure = new com.aspose.imaging.Figure();

        // Aggiungi Shape all'oggetto Figure
        figure.addShape(new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(10, 10, 300, 300)));
        figure.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
        figure.addShape(
                new com.aspose.imaging.shapes.PieShape(new com.aspose.imaging.RectangleF(
                        new com.aspose.imaging.PointF(250, 250),
                        new com.aspose.imaging.SizeF(200, 200)),
                        0, 45));

        // Aggiungi l'oggetto Figure a GraphicsPath
        graphicspath.addFigure(figure);

        // Disegna il percorso con l'oggetto Pen di colore Nero
        graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

        // Salva tutte le modifiche.
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


Inizializza una nuova istanza di [Figure](../../com.aspose.imaging/figure). Un costruttore richiesto per la deserializzazione JSON.

### getShapes() {#getShapes--}
```
public Shape[] getShapes()
```


Ottiene le forme della figura.

**Returns:**
com.aspose.imaging.Shape[] - Le forme della figura.
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Ottiene o imposta i limiti dell'oggetto.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The object's bounds.
### isClosed() {#isClosed--}
```
public boolean isClosed()
```


Restituisce un valore che indica se questa figura è chiusa. Una figura chiusa farà differenza solo nel caso in cui le forme della prima e dell'ultima figura siano forme continue. In tal caso il primo punto della prima forma sarà collegato da una linea retta all'ultimo punto dell'ultima forma.

**Returns:**
boolean - `True` se questa figura è chiusa; altrimenti, `false`.
### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Imposta un valore che indica se questa figura è chiusa. Una figura chiusa farà differenza solo nel caso in cui le forme della prima e dell'ultima figura siano forme continue. In tal caso il primo punto della prima forma sarà collegato da una linea retta all'ultimo punto dell'ultima forma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | `True` se questa figura è chiusa; altrimenti, `false`. |

### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Ottiene tutti i segmenti della figura.

**Returns:**
com.aspose.imaging.ShapeSegment[] - I segmenti della figura.
### addShape(Shape shape) {#addShape-com.aspose.imaging.Shape-}
```
public void addShape(Shape shape)
```


Aggiunge una forma alla figura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.imaging/shape) | La shape da aggiungere. |


**Example: This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface.**
Questo esempio utilizza le classi GraphicsPath e Graphics per creare e manipolare Figure su una superficie Image. L'esempio crea una nuova Image (di tipo Tiff) e disegna percorsi con l'aiuto della classe GraphicsPath. Alla fine viene chiamato il metodo DrawPath esposto dalla classe Graphics per renderizzare i percorsi sulla superficie.
``` java
// Crea un'istanza di FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.tif", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Crea un'istanza di TiffOptions e imposta le sue varie proprietà
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

    // Imposta l'origine per l'istanza di ImageOptions
    tiffOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Crea un'istanza di Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(tiffOptions, 500, 500);
    try {
        // Crea e inizializza un'istanza della classe Graphics
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Cancella la superficie Graphics
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Crea un'istanza della classe GraphicsPath
        com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

        // Crea un'istanza della classe Figure
        com.aspose.imaging.Figure figure = new com.aspose.imaging.Figure();

        // Aggiungi Shape all'oggetto Figure
        figure.addShape(new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(10, 10, 300, 300)));
        figure.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
        figure.addShape(
                new com.aspose.imaging.shapes.PieShape(new com.aspose.imaging.RectangleF(
                        new com.aspose.imaging.PointF(250, 250),
                        new com.aspose.imaging.SizeF(200, 200)),
                        0, 45));

        // Aggiungi l'oggetto Figure a GraphicsPath
        graphicspath.addFigure(figure);

        // Disegna il percorso con l'oggetto Pen di colore Nero
        graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

        // Salva tutte le modifiche.
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


Aggiunge un intervallo di forme alla figura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.imaging/shape) | Le shape da aggiungere. |

### removeShape(Shape shape) {#removeShape-com.aspose.imaging.Shape-}
```
public void removeShape(Shape shape)
```


Rimuove una forma dalla figura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.imaging/shape) | La shape da rimuovere. |

### removeShapes(Shape[] shapes) {#removeShapes-com.aspose.imaging.Shape---}
```
public void removeShapes(Shape[] shapes)
```


Rimuove un intervallo di forme dalla figura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.imaging/shape) | L'intervallo di shape da rimuovere. |

### reverse() {#reverse--}
```
public void reverse()
```


Inverte l'ordine delle forme di questa figura e l'ordine dei punti delle forme.

### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Ottiene i limiti dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La matrice da applicare prima che i limiti vengano calcolati. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Ottiene i limiti dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La matrice da applicare prima che i limiti vengano calcolati. |
| pen | [Pen](../../com.aspose.imaging/pen) | La penna da usare per l'oggetto. Questo può influenzare le dimensioni dei limiti dell'oggetto. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


Applica la trasformazione specificata alla forma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | La trasformazione da applicare. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se l'oggetto specificato è uguale all'oggetto corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'oggetto confrontato. |

**Returns:**
boolean - Il risultato di equals
### hashCode() {#hashCode--}
```
public int hashCode()
```


Funziona come funzione hash predefinita.

**Returns:**
int - Un codice hash per l'oggetto corrente.
