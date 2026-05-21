---
title: "GraphicsPath"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta una serie di linee e curve collegate."
type: docs
weight: 52
url: /it/java/com.aspose.imaging/graphicspath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds)
```
public final class GraphicsPath extends ObjectWithBounds
```

Rappresenta una serie di linee e curve collegate. Questa classe non può essere ereditata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GraphicsPath()](#GraphicsPath--) | Inizializza una nuova istanza della classe `GraphicsPath`. |
| [GraphicsPath(Figure[] figures)](#GraphicsPath-com.aspose.imaging.Figure---) | Inizializza una nuova istanza della classe `GraphicsPath`. |
| [GraphicsPath(Figure[] figures, int fillMode)](#GraphicsPath-com.aspose.imaging.Figure---int-) | Inizializza una nuova istanza della classe `GraphicsPath`. |
| [GraphicsPath(int fillMode)](#GraphicsPath-int-) | Inizializza una nuova istanza della classe `GraphicsPath`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFillMode()](#getFillMode--) | Ottiene un'enumerazione `com.aspose.imaging.FillMode` che determina come vengono riempiti gli interni delle forme in questo `com.aspose.imaging.GraphicsPath`. |
| [setFillMode(int value)](#setFillMode-int-) | Imposta un'enumerazione `com.aspose.imaging.FillMode` che determina come vengono riempiti gli interni delle forme in questo `com.aspose.imaging.GraphicsPath`. |
| [getFigures()](#getFigures--) | Ottiene le figure del percorso. |
| [getBounds()](#getBounds--) | Ottiene o imposta i limiti dell'oggetto. |
| [reset()](#reset--) | Svuota il percorso grafico e imposta `com.aspose.imaging.FillMode` su `F:com.aspose.imaging.fillMode.alternate`. |
| [reverse()](#reverse--) | Inverte l'ordine delle figure, delle forme e dei punti in ogni forma di questo `com.aspose.imaging.graphicsPath`. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Indica se il punto specificato è contenuto all'interno di questo `com.aspose.imaging.graphicsPath`. |
| [isVisible(PointF point)](#isVisible-com.aspose.imaging.PointF-) | Indica se il punto specificato è contenuto all'interno di questo `com.aspose.imaging.graphicsPath`. |
| [isVisible(int x, int y)](#isVisible-int-int-) | Indica se il punto specificato è contenuto all'interno di questo `com.aspose.imaging.graphicsPath`. |
| [isVisible(Point point)](#isVisible-com.aspose.imaging.Point-) | Indica se il punto specificato è contenuto all'interno di questo `com.aspose.imaging.graphicsPath`. |
| [isVisible(float x, float y, Graphics graphics)](#isVisible-float-float-com.aspose.imaging.Graphics-) | Indica se il punto specificato è contenuto all'interno di questo `com.aspose.imaging.GraphicsPath` nella regione di ritaglio visibile del `com.aspose.imaging.graphics` specificato. |
| [isVisible(PointF pt, Graphics graphics)](#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-) | Indica se il punto specificato è contenuto all'interno di questo `com.aspose.imaging.graphicsPath`. |
| [isVisible(int x, int y, Graphics graphics)](#isVisible-int-int-com.aspose.imaging.Graphics-) | Indica se il punto specificato è contenuto all'interno di questo `com.aspose.imaging.GraphicsPath`, utilizzando il `com.aspose.imaging.graphics` specificato. |
| [isVisible(Point pt, Graphics graphics)](#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-) | Indica se il punto specificato è contenuto all'interno di questo `com.aspose.imaging.graphicsPath`. |
| [isOutlineVisible(float x, float y, Pen pen)](#isOutlineVisible-float-float-com.aspose.imaging.Pen-) | Indica se il punto specificato è contenuto all'interno (sotto) del contorno di questo `com.aspose.imaging.GraphicsPath` quando viene disegnato con la `com.aspose.imaging.pen` specificata. |
| [isOutlineVisible(PointF point, Pen pen)](#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-) | Indica se il punto specificato è contenuto all'interno (sotto) del contorno di questo `com.aspose.imaging.GraphicsPath` quando viene disegnato con la `com.aspose.imaging.pen` specificata. |
| [isOutlineVisible(float x, float y, Pen pen, Graphics graphics)](#isOutlineVisible-float-float-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Indica se il punto specificato è contenuto all'interno (sotto) del contorno di questo `com.aspose.imaging.GraphicsPath` quando viene disegnato con la `com.aspose.imaging.Pen` specificata e utilizzando il `com.aspose.imaging.graphics` specificato. |
| [isOutlineVisible(PointF pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Indica se il punto specificato è contenuto all'interno (sotto) del contorno di questo `com.aspose.imaging.GraphicsPath` quando viene disegnato con la `com.aspose.imaging.Pen` specificata e utilizzando il `com.aspose.imaging.graphics` specificato. |
| [isOutlineVisible(int x, int y, Pen pen)](#isOutlineVisible-int-int-com.aspose.imaging.Pen-) | Indica se il punto specificato è contenuto all'interno (sotto) del contorno di questo `com.aspose.imaging.GraphicsPath` quando viene disegnato con la `com.aspose.imaging.pen` specificata. |
| [isOutlineVisible(Point point, Pen pen)](#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-) | Indica se il punto specificato è contenuto all'interno (sotto) del contorno di questo `com.aspose.imaging.GraphicsPath` quando viene disegnato con la `com.aspose.imaging.pen` specificata. |
| [isOutlineVisible(int x, int y, Pen pen, Graphics graphics)](#isOutlineVisible-int-int-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Indica se il punto specificato è contenuto all'interno (sotto) del contorno di questo `com.aspose.imaging.GraphicsPath` quando viene disegnato con la `com.aspose.imaging.Pen` specificata e utilizzando il `com.aspose.imaging.graphics` specificato. |
| [isOutlineVisible(Point pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Indica se il punto specificato è contenuto all'interno (sotto) del contorno di questo `com.aspose.imaging.GraphicsPath` quando viene disegnato con la `com.aspose.imaging.Pen` specificata e utilizzando il `com.aspose.imaging.graphics` specificato. |
| [flatten()](#flatten--) | Converte ogni curva in questo percorso in una sequenza di segmenti di linea connessi. |
| [flatten(Matrix matrix)](#flatten-com.aspose.imaging.Matrix-) | Applica la trasformazione specificata e poi converte ogni curva in questo `com.aspose.imaging.GraphicsPath` in una sequenza di segmenti di linea connessi. |
| [flatten(Matrix matrix, float flatness)](#flatten-com.aspose.imaging.Matrix-float-) | Converte ogni curva in questo `com.aspose.imaging.GraphicsPath` in una sequenza di segmenti di linea connessi. |
| [widen(Pen pen)](#widen-com.aspose.imaging.Pen-) | Aggiunge un contorno aggiuntivo al percorso. |
| [widen(Pen pen, Matrix matrix)](#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-) | Aggiunge un contorno aggiuntivo al `com.aspose.imaging.graphicsPath`. |
| [widen(Pen pen, Matrix matrix, float flatness)](#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-float-) | Sostituisce questo `com.aspose.imaging.GraphicsPath` con curve che racchiudono l'area riempita quando questo percorso è disegnato con la penna specificata. |
| [warp(PointF[] destPoints, RectangleF srcRect)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-) | Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo `com.aspose.imaging.graphicsPath`. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-) | Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo `com.aspose.imaging.graphicsPath`. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-) | Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo `com.aspose.imaging.graphicsPath`. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-float-) | Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo `com.aspose.imaging.graphicsPath`. |
| [addFigure(Figure figure)](#addFigure-com.aspose.imaging.Figure-) | Aggiunge una nuova figura. |
| [addFigures(Figure[] figures)](#addFigures-com.aspose.imaging.Figure---) | Aggiunge nuove figure. |
| [removeFigure(Figure figure)](#removeFigure-com.aspose.imaging.Figure-) | Rimuove una figura. |
| [removeFigures(Figure[] figures)](#removeFigures-com.aspose.imaging.Figure---) | Rimuove figure. |
| [addPath(GraphicsPath addingPath)](#addPath-com.aspose.imaging.GraphicsPath-) | Aggiunge alla fine il `com.aspose.imaging.GraphicsPath` specificato a questo percorso. |
| [addPath(GraphicsPath addingPath, boolean connect)](#addPath-com.aspose.imaging.GraphicsPath-boolean-) | Aggiunge alla fine il `com.aspose.imaging.GraphicsPath` specificato a questo percorso. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Ottiene i limiti dell'oggetto. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Ottiene i limiti dell'oggetto. |
| [deepClone()](#deepClone--) | Esegue una clonazione profonda di questo percorso grafico. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Applica la trasformazione specificata alla forma. |
| [equals(Object o)](#equals-java.lang.Object-) | Verifica se gli oggetti sono uguali. |
| [hashCode()](#hashCode--) | Ottieni il codice hash dell'oggetto corrente. |

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

### GraphicsPath() {#GraphicsPath--}
```
public GraphicsPath()
```


Inizializza una nuova istanza della classe `GraphicsPath`.

### GraphicsPath(Figure[] figures) {#GraphicsPath-com.aspose.imaging.Figure---}
```
public GraphicsPath(Figure[] figures)
```


Inizializza una nuova istanza della classe `GraphicsPath`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | Le figure da cui inizializzare. |

### GraphicsPath(Figure[] figures, int fillMode) {#GraphicsPath-com.aspose.imaging.Figure---int-}
```
public GraphicsPath(Figure[] figures, int fillMode)
```


Inizializza una nuova istanza della classe `GraphicsPath`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | Le figure da cui inizializzare. |
| fillMode | int | La modalità di riempimento. |

### GraphicsPath(int fillMode) {#GraphicsPath-int-}
```
public GraphicsPath(int fillMode)
```


Inizializza una nuova istanza della classe `GraphicsPath`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fillMode | int | La modalità di riempimento. |

### getFillMode() {#getFillMode--}
```
public int getFillMode()
```


Ottiene un'enumerazione `com.aspose.imaging.FillMode` che determina come vengono riempiti gli interni delle forme in questo `com.aspose.imaging.GraphicsPath`.

**Returns:**
int - La modalità di riempimento. Un'enumerazione `com.aspose.imaging.FillMode` che specifica come vengono riempiti gli interni delle forme in questo `com.aspose.imaging.GraphicsPath`.
### setFillMode(int value) {#setFillMode-int-}
```
public void setFillMode(int value)
```


Imposta un'enumerazione `com.aspose.imaging.FillMode` che determina come vengono riempiti gli interni delle forme in questo `com.aspose.imaging.GraphicsPath`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La modalità di riempimento. |

### getFigures() {#getFigures--}
```
public Figure[] getFigures()
```


Ottiene le figure del percorso.

**Returns:**
com.aspose.imaging.Figure[] - Le figure del percorso.
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Ottiene o imposta i limiti dell'oggetto.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The object's bounds.
### reset() {#reset--}
```
public void reset()
```


Svuota il percorso grafico e imposta `com.aspose.imaging.FillMode` su `F:com.aspose.imaging.fillMode.alternate`.

### reverse() {#reverse--}
```
public void reverse()
```


Inverte l'ordine delle figure, delle forme e dei punti in ogni forma di questo `com.aspose.imaging.graphicsPath`.

### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Indica se il punto specificato è contenuto all'interno di questo `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo `com.aspose.imaging.GraphicsPath`; altrimenti, false.
### isVisible(PointF point) {#isVisible-com.aspose.imaging.PointF-}
```
public boolean isVisible(PointF point)
```


Indica se il punto specificato è contenuto all'interno di questo `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Un `com.aspose.imaging.PointF` che rappresenta il punto da testare. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo `com.aspose.imaging.GraphicsPath`; altrimenti, false.
### isVisible(int x, int y) {#isVisible-int-int-}
```
public boolean isVisible(int x, int y)
```


Indica se il punto specificato è contenuto all'interno di questo `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del punto da testare. |
| y | int | La coordinata y del punto da testare. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo `com.aspose.imaging.GraphicsPath`; altrimenti, false.
### isVisible(Point point) {#isVisible-com.aspose.imaging.Point-}
```
public boolean isVisible(Point point)
```


Indica se il punto specificato è contenuto all'interno di questo `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Un `com.aspose.imaging.Point` che rappresenta il punto da testare. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo `com.aspose.imaging.GraphicsPath`; altrimenti, false.
### isVisible(float x, float y, Graphics graphics) {#isVisible-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, Graphics graphics)
```


Indica se il punto specificato è contenuto all'interno di questo `com.aspose.imaging.GraphicsPath` nella regione di ritaglio visibile del `com.aspose.imaging.graphics` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Il `com.aspose.imaging.Graphics` per il quale testare la visibilità. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo `com.aspose.imaging.GraphicsPath`; altrimenti, false.
### isVisible(PointF pt, Graphics graphics) {#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(PointF pt, Graphics graphics)
```


Indica se il punto specificato è contenuto all'interno di questo `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.imaging/pointf) | Un `com.aspose.imaging.PointF` che rappresenta il punto da testare. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Il `com.aspose.imaging.Graphics` per il quale testare la visibilità. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo; altrimenti, false.
### isVisible(int x, int y, Graphics graphics) {#isVisible-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, Graphics graphics)
```


Indica se il punto specificato è contenuto all'interno di questo `com.aspose.imaging.GraphicsPath`, utilizzando il `com.aspose.imaging.graphics` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del punto da testare. |
| y | int | La coordinata y del punto da testare. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Il `com.aspose.imaging.Graphics` per il quale testare la visibilità. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo `com.aspose.imaging.GraphicsPath`; altrimenti, false.
### isVisible(Point pt, Graphics graphics) {#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Point pt, Graphics graphics)
```


Indica se il punto specificato è contenuto all'interno di questo `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pt | [Point](../../com.aspose.imaging/point) | Un `com.aspose.imaging.Point` che rappresenta il punto da testare. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Il `com.aspose.imaging.Graphics` per il quale testare la visibilità. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo `com.aspose.imaging.GraphicsPath`; altrimenti, false.
### isOutlineVisible(float x, float y, Pen pen) {#isOutlineVisible-float-float-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(float x, float y, Pen pen)
```


Indica se il punto specificato è contenuto all'interno (sotto) del contorno di questo `com.aspose.imaging.GraphicsPath` quando viene disegnato con la `com.aspose.imaging.pen` specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |
| pen | [Pen](../../com.aspose.imaging/pen) | Il `com.aspose.imaging.Pen` da testare. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto nel contorno di questo `com.aspose.imaging.GraphicsPath` quando disegnato con il `com.aspose.imaging.Pen` specificato; altrimenti, false.
### isOutlineVisible(PointF point, Pen pen) {#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(PointF point, Pen pen)
```


Indica se il punto specificato è contenuto all'interno (sotto) del contorno di questo `com.aspose.imaging.GraphicsPath` quando viene disegnato con la `com.aspose.imaging.pen` specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Un `com.aspose.imaging.PointF` che specifica la posizione da testare. |
| pen | [Pen](../../com.aspose.imaging/pen) | Il `com.aspose.imaging.Pen` da testare. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto nel contorno di questo `com.aspose.imaging.GraphicsPath` quando disegnato con il `com.aspose.imaging.Pen` specificato; altrimenti, false.
### isOutlineVisible(float x, float y, Pen pen, Graphics graphics) {#isOutlineVisible-float-float-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(float x, float y, Pen pen, Graphics graphics)
```


Indica se il punto specificato è contenuto all'interno (sotto) del contorno di questo `com.aspose.imaging.GraphicsPath` quando viene disegnato con la `com.aspose.imaging.Pen` specificata e utilizzando il `com.aspose.imaging.graphics` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |
| pen | [Pen](../../com.aspose.imaging/pen) | Il `com.aspose.imaging.Pen` da testare. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Il `com.aspose.imaging.Graphics` per il quale testare la visibilità. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto (sotto) il contorno di questo `com.aspose.imaging.GraphicsPath` così disegnato con il `com.aspose.imaging.Pen` specificato; altrimenti, false.
### isOutlineVisible(PointF pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(PointF pt, Pen pen, Graphics graphics)
```


Indica se il punto specificato è contenuto all'interno (sotto) del contorno di questo `com.aspose.imaging.GraphicsPath` quando viene disegnato con la `com.aspose.imaging.Pen` specificata e utilizzando il `com.aspose.imaging.graphics` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.imaging/pointf) | Un `com.aspose.imaging.PointF` che specifica la posizione da testare. |
| pen | [Pen](../../com.aspose.imaging/pen) | Il `com.aspose.imaging.Pen` da testare. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Il `com.aspose.imaging.Graphics` per il quale testare la visibilità. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto (sotto) il contorno di questo `com.aspose.imaging.GraphicsPath` così disegnato con il `com.aspose.imaging.Pen` specificato; altrimenti, false.
### isOutlineVisible(int x, int y, Pen pen) {#isOutlineVisible-int-int-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(int x, int y, Pen pen)
```


Indica se il punto specificato è contenuto all'interno (sotto) del contorno di questo `com.aspose.imaging.GraphicsPath` quando viene disegnato con la `com.aspose.imaging.pen` specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del punto da testare. |
| y | int | La coordinata y del punto da testare. |
| pen | [Pen](../../com.aspose.imaging/pen) | Il `com.aspose.imaging.Pen` da testare. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto nel contorno di questo `com.aspose.imaging.GraphicsPath` quando disegnato con il `com.aspose.imaging.Pen` specificato; altrimenti, false.
### isOutlineVisible(Point point, Pen pen) {#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(Point point, Pen pen)
```


Indica se il punto specificato è contenuto all'interno (sotto) del contorno di questo `com.aspose.imaging.GraphicsPath` quando viene disegnato con la `com.aspose.imaging.pen` specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Un `com.aspose.imaging.Point` che specifica la posizione da testare. |
| pen | [Pen](../../com.aspose.imaging/pen) | Il `com.aspose.imaging.Pen` da testare. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto nel contorno di questo `com.aspose.imaging.GraphicsPath` quando disegnato con il `com.aspose.imaging.Pen` specificato; altrimenti, false.
### isOutlineVisible(int x, int y, Pen pen, Graphics graphics) {#isOutlineVisible-int-int-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(int x, int y, Pen pen, Graphics graphics)
```


Indica se il punto specificato è contenuto all'interno (sotto) del contorno di questo `com.aspose.imaging.GraphicsPath` quando viene disegnato con la `com.aspose.imaging.Pen` specificata e utilizzando il `com.aspose.imaging.graphics` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del punto da testare. |
| y | int | La coordinata y del punto da testare. |
| pen | [Pen](../../com.aspose.imaging/pen) | Il `com.aspose.imaging.Pen` da testare. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Il `com.aspose.imaging.Graphics` per il quale testare la visibilità. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto nel contorno di questo `com.aspose.imaging.GraphicsPath` così disegnato con il `com.aspose.imaging.Pen` specificato; altrimenti, false.
### isOutlineVisible(Point pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(Point pt, Pen pen, Graphics graphics)
```


Indica se il punto specificato è contenuto all'interno (sotto) del contorno di questo `com.aspose.imaging.GraphicsPath` quando viene disegnato con la `com.aspose.imaging.Pen` specificata e utilizzando il `com.aspose.imaging.graphics` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pt | [Point](../../com.aspose.imaging/point) | Un `com.aspose.imaging.Point` che specifica la posizione da testare. |
| pen | [Pen](../../com.aspose.imaging/pen) | Il `com.aspose.imaging.Pen` da testare. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Il `com.aspose.imaging.Graphics` per il quale testare la visibilità. |

**Returns:**
boolean - Questo metodo restituisce true se il punto specificato è contenuto nel contorno di questo `com.aspose.imaging.GraphicsPath` così disegnato con il `com.aspose.imaging.Pen` specificato; altrimenti, false.
### flatten() {#flatten--}
```
public void flatten()
```


Converte ogni curva in questo percorso in una sequenza di segmenti di linea connessi.

### flatten(Matrix matrix) {#flatten-com.aspose.imaging.Matrix-}
```
public void flatten(Matrix matrix)
```


Applica la trasformazione specificata e poi converte ogni curva in questo `com.aspose.imaging.GraphicsPath` in una sequenza di segmenti di linea connessi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Un `com.aspose.imaging.Matrix` con il quale trasformare questo `com.aspose.imaging.GraphicsPath` prima di appiattire. |

### flatten(Matrix matrix, float flatness) {#flatten-com.aspose.imaging.Matrix-float-}
```
public void flatten(Matrix matrix, float flatness)
```


Converte ogni curva in questo `com.aspose.imaging.GraphicsPath` in una sequenza di segmenti di linea connessi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Un `com.aspose.imaging.Matrix` con il quale trasformare questo `com.aspose.imaging.GraphicsPath` prima di appiattire. |
| flatness | float | Specifica l'errore massimo consentito tra la curva e la sua approssimazione appiattita. Un valore di 0,25 è quello predefinito. Ridurre il valore di flatness aumenterà il numero di segmenti lineari nell'approssimazione. |

### widen(Pen pen) {#widen-com.aspose.imaging.Pen-}
```
public void widen(Pen pen)
```


Aggiunge un contorno aggiuntivo al percorso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Un `com.aspose.imaging.Pen` che specifica la larghezza tra il contorno originale del percorso e il nuovo contorno creato da questo metodo. |

### widen(Pen pen, Matrix matrix) {#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-}
```
public void widen(Pen pen, Matrix matrix)
```


Aggiunge un contorno aggiuntivo al `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Un `com.aspose.imaging.Pen` che specifica la larghezza tra il contorno originale del percorso e il nuovo contorno creato da questo metodo. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Un `com.aspose.imaging.Matrix` che specifica una trasformazione da applicare al percorso prima di allargare. |

### widen(Pen pen, Matrix matrix, float flatness) {#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-float-}
```
public void widen(Pen pen, Matrix matrix, float flatness)
```


Sostituisce questo `com.aspose.imaging.GraphicsPath` con curve che racchiudono l'area riempita quando questo percorso è disegnato con la penna specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Un `com.aspose.imaging.Pen` che specifica la larghezza tra il contorno originale del percorso e il nuovo contorno creato da questo metodo. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Un `com.aspose.imaging.Matrix` che specifica una trasformazione da applicare al percorso prima di allargare. |
| flatness | float | Un valore che specifica la flatness per le curve. |

### warp(PointF[] destPoints, RectangleF srcRect) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-}
```
public void warp(PointF[] destPoints, RectangleF srcRect)
```


Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | Un array di strutture `com.aspose.imaging.PointF` che definiscono un parallelogramma a cui è trasformato il rettangolo definito da `srcRect`. L'array può contenere tre o quattro elementi. Se l'array contiene tre elementi, l'angolo inferiore destro del parallelogramma è implicito nei primi tre punti. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | Un `com.aspose.imaging.RectangleF` che rappresenta il rettangolo trasformato nel parallelogramma definito da `destPoints`. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```


Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | Un array di strutture `com.aspose.imaging.PointF` che definiscono un parallelogramma a cui è trasformato il rettangolo definito da `srcRect`. L'array può contenere tre o quattro elementi. Se l'array contiene tre elementi, l'angolo inferiore destro del parallelogramma è implicito nei primi tre punti. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | Un `com.aspose.imaging.RectangleF` che rappresenta il rettangolo trasformato nel parallelogramma definito da `destPoints`. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Un `com.aspose.imaging.Matrix` che specifica una trasformazione geometrica da applicare al percorso. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)
```


Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | Un array di strutture `com.aspose.imaging.PointF` che definisce un parallelogramma a cui è trasformato il rettangolo definito da `srcRect`. L'array può contenere tre o quattro elementi. Se l'array contiene tre elementi, l'angolo inferiore destro del parallelogramma è implicito nei primi tre punti. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | Un `com.aspose.imaging.RectangleF` che rappresenta il rettangolo trasformato nel parallelogramma definito da `destPoints`. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Un `com.aspose.imaging.Matrix` che specifica una trasformazione geometrica da applicare al percorso. |
| warpMode | int | Un'enumerazione `com.aspose.imaging.WarpMode` che specifica se questa operazione di deformazione utilizza la modalità prospettiva o bilineare. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-float-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)
```


Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | Un array di strutture `com.aspose.imaging.PointF` che definiscono un parallelogramma a cui è trasformato il rettangolo definito da `srcRect`. L'array può contenere tre o quattro elementi. Se l'array contiene tre elementi, l'angolo inferiore destro del parallelogramma è implicito nei primi tre punti. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | Un `com.aspose.imaging.RectangleF` che rappresenta il rettangolo trasformato nel parallelogramma definito da `destPoints`. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Un `com.aspose.imaging.Matrix` che specifica una trasformazione geometrica da applicare al percorso. |
| warpMode | int | Un'enumerazione `com.aspose.imaging.WarpMode` che specifica se questa operazione di deformazione utilizza la modalità prospettiva o bilineare. |
| flatness | float | Un valore da 0 a 1 che specifica quanto piatta è il percorso risultante. Per ulteriori informazioni, vedere i metodi `com.aspose.imaging.GraphicsPath.flatten`. |

### addFigure(Figure figure) {#addFigure-com.aspose.imaging.Figure-}
```
public void addFigure(Figure figure)
```


Aggiunge una nuova figura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.imaging/figure) | La figura da aggiungere. |


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

### addFigures(Figure[] figures) {#addFigures-com.aspose.imaging.Figure---}
```
public void addFigures(Figure[] figures)
```


Aggiunge nuove figure.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | Le figure da aggiungere. |


**Example: This example creates a new Image and draws a variety of shapes using Figures and GraphicsPath o...**
Questo esempio crea una nuova Image e disegna una varietà di forme usando Figures e GraphicsPath sulla superficie dell'Image.
``` java
//Crea un'istanza di BmpOptions e imposta le sue varie proprietà.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//Crea un'istanza di FileCreateSource e assegnala come Source per l'istanza di BmpOptions
//Il secondo parametro Boolean determina se il file da creare è IsTemporal o meno
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\output.bmp", false));

//Crea un'istanza di Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //Crea e inizializza un'istanza della classe Graphics
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //Cancella la superficie Graphics
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //Crea un'istanza della classe GraphicsPath
    com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

    //Crea un'istanza della classe Figure
    com.aspose.imaging.Figure figure1 = new com.aspose.imaging.Figure();

    //Aggiungi Shape all'oggetto Figure.
    figure1.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
    figure1.addShape(new com.aspose.imaging.shapes.PieShape(
            new com.aspose.imaging.RectangleF(
                    new com.aspose.imaging.PointF(110, 110),
                    new com.aspose.imaging.SizeF(200, 200)), 0, 90));

    //Crea un'istanza della classe Figure
    com.aspose.imaging.Figure figure2 = new com.aspose.imaging.Figure();

    //Aggiungi Shape all'oggetto Figure.
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

    //Aggiungi l'oggetto Figure a GraphicsPath
    graphicspath.addFigures(new com.aspose.imaging.Figure[]{figure1, figure2});

    //Disegna il percorso con l'oggetto Pen di colore Nero
    graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

    // salva tutte le modifiche.
    image.save();
} finally {
    image.dispose();
}
```

### removeFigure(Figure figure) {#removeFigure-com.aspose.imaging.Figure-}
```
public void removeFigure(Figure figure)
```


Rimuove una figura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.imaging/figure) | La figura da rimuovere. |

### removeFigures(Figure[] figures) {#removeFigures-com.aspose.imaging.Figure---}
```
public void removeFigures(Figure[] figures)
```


Rimuove figure.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | Le figure da rimuovere. |

### addPath(GraphicsPath addingPath) {#addPath-com.aspose.imaging.GraphicsPath-}
```
public void addPath(GraphicsPath addingPath)
```


Aggiunge alla fine il `com.aspose.imaging.GraphicsPath` specificato a questo percorso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Il `com.aspose.imaging.GraphicsPath` da aggiungere. |

### addPath(GraphicsPath addingPath, boolean connect) {#addPath-com.aspose.imaging.GraphicsPath-boolean-}
```
public void addPath(GraphicsPath addingPath, boolean connect)
```


Aggiunge alla fine il `com.aspose.imaging.GraphicsPath` specificato a questo percorso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Il `com.aspose.imaging.GraphicsPath` da aggiungere. |
| connetti | boolean | Un valore Booleano che specifica se la prima figura nel percorso aggiunto fa parte dell'ultima figura in questo percorso. Un valore true indica che la prima figura nel percorso aggiunto fa parte dell'ultima figura in questo percorso. Un valore false indica che la prima figura nel percorso aggiunto è separata dall'ultima figura in questo percorso. |

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
### deepClone() {#deepClone--}
```
public GraphicsPath deepClone()
```


Esegue una clonazione profonda di questo percorso grafico.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - A deep clone of the graphics path.
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


Applica la trasformazione specificata alla forma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | La trasformazione da applicare. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Verifica se gli oggetti sono uguali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| o | java.lang.Object | L'altro oggetto. |

**Returns:**
boolean - Il risultato del confronto di uguaglianza.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Ottieni il codice hash dell'oggetto corrente.

**Returns:**
int - Il codice hash.
