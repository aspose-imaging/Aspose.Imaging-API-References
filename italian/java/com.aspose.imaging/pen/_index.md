---
title: "Pen"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Definisce un oggetto utilizzato per disegnare linee, curve e figure."
type: docs
weight: 81
url: /it/java/com.aspose.imaging/pen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.TransparencySupporter](../../com.aspose.imaging/transparencysupporter)
```
public class Pen extends TransparencySupporter
```

Definisce un oggetto utilizzato per disegnare linee, curve e figure.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.imaging.Color-) | Inizializza una nuova istanza della classe `Pen` con il colore specificato. |
| [Pen(Color color, float width)](#Pen-com.aspose.imaging.Color-float-) | Inizializza una nuova istanza della classe `Pen` con le proprietà `Color` e `Pen.Width` specificate. |
| [Pen(Brush brush)](#Pen-com.aspose.imaging.Brush-) | Inizializza una nuova istanza della classe `Pen` con il `Brush` specificato. |
| [Pen(Brush brush, float width)](#Pen-com.aspose.imaging.Brush-float-) | Inizializza una nuova istanza della classe `Pen` con il `Brush` e il `Pen.Width` specificati. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getWidth()](#getWidth--) | Restituisce la larghezza di questo `Pen`, in unità dell'oggetto Graphics utilizzato per il disegno. |
| [setWidth(float value)](#setWidth-float-) | Imposta la larghezza di questo `Pen`, in unità dell'oggetto Graphics utilizzato per il disegno. |
| [getStartCap()](#getStartCap--) | Restituisce lo stile di estremità usato all'inizio delle linee disegnate con questo `Pen`. |
| [setStartCap(int value)](#setStartCap-int-) | Imposta lo stile di estremità usato all'inizio delle linee disegnate con questo `Pen`. |
| [getEndCap()](#getEndCap--) | Restituisce lo stile di estremità usato alla fine delle linee disegnate con questo `Pen`. |
| [setEndCap(int value)](#setEndCap-int-) | Imposta lo stile di estremità usato alla fine delle linee disegnate con questo `Pen`. |
| [getDashCap()](#getDashCap--) | Restituisce lo stile di estremità usato alla fine dei tratti che compongono le linee tratteggiate disegnate con questo `Pen`. |
| [setDashCap(int value)](#setDashCap-int-) | Imposta lo stile di estremità usato alla fine dei tratti che compongono le linee tratteggiate disegnate con questo `Pen`. |
| [getLineJoin()](#getLineJoin--) | Restituisce lo stile di giunzione per le estremità di due linee consecutive disegnate con questo `Pen`. |
| [setLineJoin(int value)](#setLineJoin-int-) | Imposta lo stile di giunzione per le estremità di due linee consecutive disegnate con questo `Pen`. |
| [getCustomStartCap()](#getCustomStartCap--) | Restituisce un'estremità personalizzata da usare all'inizio delle linee disegnate con questo `Pen`. |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.imaging.CustomLineCap-) | Imposta un'estremità personalizzata da usare all'inizio delle linee disegnate con questo `Pen`. |
| [getCustomEndCap()](#getCustomEndCap--) | Restituisce un'estremità personalizzata da usare alla fine delle linee disegnate con questo `Pen`. |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.imaging.CustomLineCap-) | Imposta un'estremità personalizzata da usare alla fine delle linee disegnate con questo `Pen`. |
| [getMiterLimit()](#getMiterLimit--) | Restituisce il limite dello spessore della giunzione su un angolo a spigolo. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Imposta il limite dello spessore della giunzione su un angolo a spigolo. |
| [getAlignment()](#getAlignment--) | Ottiene l'allineamento per questo `Pen`. |
| [setAlignment(int value)](#setAlignment-int-) | Imposta l'allineamento per questo `Pen`. |
| [getTransform()](#getTransform--) | Ottiene una copia della trasformazione geometrica per questo `Pen`. |
| [setTransform(Matrix value)](#setTransform-com.aspose.imaging.Matrix-) | Imposta una copia della trasformazione geometrica per questo `Pen`. |
| [getPenType()](#getPenType--) | Ottiene lo stile delle linee disegnate con questo `Pen`. |
| [getColor()](#getColor--) | Ottiene il colore di questo `Pen`. |
| [setColor(Color value)](#setColor-com.aspose.imaging.Color-) | Imposta il colore di questo `Pen`. |
| [getBrush()](#getBrush--) | Ottiene il `Brush` che determina gli attributi di questo `Pen`. |
| [setBrush(Brush value)](#setBrush-com.aspose.imaging.Brush-) | Imposta il `Brush` che determina gli attributi di questo `Pen`. |
| [getDashStyle()](#getDashStyle--) | Ottiene lo stile usato per le linee tratteggiate disegnate con questo `Pen`. |
| [setDashStyle(int value)](#setDashStyle-int-) | Imposta lo stile usato per le linee tratteggiate disegnate con questo `Pen`. |
| [getDashOffset()](#getDashOffset--) | Ottiene la distanza dall'inizio di una linea all'inizio di un modello di tratteggio. |
| [setDashOffset(float value)](#setDashOffset-float-) | Imposta la distanza dall'inizio di una linea all'inizio di un modello di tratteggio. |
| [getDashPattern()](#getDashPattern--) | Ottiene un array di trattini e spazi personalizzati. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | Imposta un array di trattini e spazi personalizzati. |
| [getCompoundArray()](#getCompoundArray--) | Ottiene un array di valori che specifica una penna composta. |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | Imposta un array di valori che specifica una penna composta. |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | Imposta i valori che determinano lo stile dell'estremità usato per terminare le linee disegnate da questo `Pen`. |
| [resetTransform()](#resetTransform--) | Reimposta la matrice di trasformazione geometrica per questo `Pen` all'identità. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.imaging.Matrix-) | Moltiplica la matrice di trasformazione per questo `Pen` per la `Matrix` specificata. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.imaging.Matrix-int-) | Moltiplica la matrice di trasformazione per questo `Pen` per la `Matrix` specificata nell'ordine specificato. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Trasla la trasformazione geometrica locale per le dimensioni specificate. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Trasla la trasformazione geometrica locale per le dimensioni specificate nell'ordine specificato. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Scala la trasformazione geometrica locale per i fattori specificati. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Scala la trasformazione geometrica locale dei fattori specificati nell'ordine specificato. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Ruota la trasformazione geometrica locale dell'angolo specificato. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Ruota la trasformazione geometrica locale dell'angolo specificato nell'ordine specificato. |
| [equals(Object o)](#equals-java.lang.Object-) | Verifica se gli oggetti sono uguali. |
| [hashCode()](#hashCode--) |  |

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

### Pen(Color color) {#Pen-com.aspose.imaging.Color-}
```
public Pen(Color color)
```


Inizializza una nuova istanza della classe `Pen` con il colore specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | Una struttura `Color` che indica il colore di questo `Pen`. |

### Pen(Color color, float width) {#Pen-com.aspose.imaging.Color-float-}
```
public Pen(Color color, float width)
```


Inizializza una nuova istanza della classe `Pen` con le proprietà `Color` e `Pen.Width` specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | Una struttura `Color` che indica il colore di questo `Pen`. |
| width | float | Un valore che indica la larghezza di questo `Pen`. |

### Pen(Brush brush) {#Pen-com.aspose.imaging.Brush-}
```
public Pen(Brush brush)
```


Inizializza una nuova istanza della classe `Pen` con il `Brush` specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Un `Brush` che determina le proprietà di riempimento di questo `Pen`. |

### Pen(Brush brush, float width) {#Pen-com.aspose.imaging.Brush-float-}
```
public Pen(Brush brush, float width)
```


Inizializza una nuova istanza della classe `Pen` con il `Brush` e il `Pen.Width` specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Un `Brush` che determina le caratteristiche di questo `Pen`. |
| width | float | La larghezza del nuovo `Pen`. |

### getWidth() {#getWidth--}
```
public float getWidth()
```


Restituisce la larghezza di questo `Pen`, in unità dell'oggetto Graphics utilizzato per il disegno.

**Returns:**
float - La larghezza di questo `Pen`.
### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Imposta la larghezza di questo `Pen`, in unità dell'oggetto Graphics utilizzato per il disegno.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | La larghezza di questo `Pen`. |

### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


Restituisce lo stile di estremità usato all'inizio delle linee disegnate con questo `Pen`.

**Returns:**
int - Uno dei valori `LineCap` che rappresenta lo stile di estremità usato all'inizio delle linee disegnate con questo `Pen`.
### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


Imposta lo stile di estremità usato all'inizio delle linee disegnate con questo `Pen`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Uno dei valori `LineCap` che rappresenta lo stile di estremità usato all'inizio delle linee disegnate con questo `Pen`. |

### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


Restituisce lo stile di estremità usato alla fine delle linee disegnate con questo `Pen`.

**Returns:**
int - Uno dei valori `LineCap` che rappresenta lo stile di estremità usato alla fine delle linee disegnate con questo `Pen`.
### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


Imposta lo stile di estremità usato alla fine delle linee disegnate con questo `Pen`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Uno dei valori `LineCap` che rappresenta lo stile di estremità usato alla fine delle linee disegnate con questo `Pen`. |

### getDashCap() {#getDashCap--}
```
public int getDashCap()
```


Restituisce lo stile di estremità usato alla fine dei tratti che compongono le linee tratteggiate disegnate con questo `Pen`.

**Returns:**
int - Uno dei valori `DashCap` che rappresenta lo stile di estremità usato all'inizio e alla fine dei tratti che compongono le linee tratteggiate disegnate con questo `Pen`.
### setDashCap(int value) {#setDashCap-int-}
```
public void setDashCap(int value)
```


Imposta lo stile di estremità usato alla fine dei tratti che compongono le linee tratteggiate disegnate con questo `Pen`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Uno dei valori `DashCap` che rappresenta lo stile di estremità usato all'inizio e alla fine dei tratti che compongono le linee tratteggiate disegnate con questo `Pen`. |

### getLineJoin() {#getLineJoin--}
```
public int getLineJoin()
```


Restituisce lo stile di giunzione per le estremità di due linee consecutive disegnate con questo `Pen`.

**Returns:**
int - Un `LineJoin` che rappresenta lo stile di giunzione per le estremità di due linee consecutive disegnate con questo `Pen`.
### setLineJoin(int value) {#setLineJoin-int-}
```
public void setLineJoin(int value)
```


Imposta lo stile di giunzione per le estremità di due linee consecutive disegnate con questo `Pen`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Un `LineJoin` che rappresenta lo stile di giunzione per le estremità di due linee consecutive disegnate con questo `Pen`. |

### getCustomStartCap() {#getCustomStartCap--}
```
public CustomLineCap getCustomStartCap()
```


Restituisce un'estremità personalizzata da usare all'inizio delle linee disegnate con questo `Pen`.

**Returns:**
[CustomLineCap](../../com.aspose.imaging/customlinecap) - A `CustomLineCap` that represents the cap used at the beginning of lines drawn with this `Pen`.
### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.imaging.CustomLineCap-}
```
public void setCustomStartCap(CustomLineCap value)
```


Imposta un'estremità personalizzata da usare all'inizio delle linee disegnate con questo `Pen`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.imaging/customlinecap) | Un `CustomLineCap` che rappresenta il cap usato all'inizio delle linee disegnate con questo `Pen`. |

### getCustomEndCap() {#getCustomEndCap--}
```
public CustomLineCap getCustomEndCap()
```


Restituisce un'estremità personalizzata da usare alla fine delle linee disegnate con questo `Pen`.

**Returns:**
[CustomLineCap](../../com.aspose.imaging/customlinecap) - A `CustomLineCap` that represents the cap used at the end of lines drawn with this `Pen`.
### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.imaging.CustomLineCap-}
```
public void setCustomEndCap(CustomLineCap value)
```


Imposta un'estremità personalizzata da usare alla fine delle linee disegnate con questo `Pen`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.imaging/customlinecap) | Un `CustomLineCap` che rappresenta il cap usato alla fine delle linee disegnate con questo `Pen`. |

### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


Restituisce il limite dello spessore della giunzione su un angolo a spigolo.

**Returns:**
float - Il limite dello spessore della giunzione su un angolo a spigolo.
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


Imposta il limite dello spessore della giunzione su un angolo a spigolo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Il limite dello spessore della giunzione su un angolo a spigolo. |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Ottiene l'allineamento per questo `Pen`.

**Returns:**
int - Un `PenAlignment` che rappresenta l'allineamento per questo `Pen`.
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Imposta l'allineamento per questo `Pen`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Un `PenAlignment` che rappresenta l'allineamento per questo `Pen`. |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Ottiene una copia della trasformazione geometrica per questo `Pen`.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - A copy of the `Matrix` that represents the geometric transformation for this `Pen`.
### setTransform(Matrix value) {#setTransform-com.aspose.imaging.Matrix-}
```
public void setTransform(Matrix value)
```


Imposta una copia della trasformazione geometrica per questo `Pen`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) | Una copia della `Matrix` che rappresenta la trasformazione geometrica per questo `Pen`. |

### getPenType() {#getPenType--}
```
public int getPenType()
```


Ottiene lo stile delle linee disegnate con questo `Pen`.

**Returns:**
int - Un'enumerazione `PenType` che specifica lo stile delle linee disegnate con questo `Pen`.
### getColor() {#getColor--}
```
public Color getColor()
```


Ottiene il colore di questo `Pen`.

**Returns:**
[Color](../../com.aspose.imaging/color) - A `Color` structure that represents the color of this `Pen`.
### setColor(Color value) {#setColor-com.aspose.imaging.Color-}
```
public void setColor(Color value)
```


Imposta il colore di questo `Pen`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Una struttura `Color` che rappresenta il colore di questo `Pen`. |

### getBrush() {#getBrush--}
```
public Brush getBrush()
```


Ottiene il `Brush` che determina gli attributi di questo `Pen`.

**Returns:**
[Brush](../../com.aspose.imaging/brush) - A `Brush` that determines attributes of this `Pen`.
### setBrush(Brush value) {#setBrush-com.aspose.imaging.Brush-}
```
public void setBrush(Brush value)
```


Imposta il `Brush` che determina gli attributi di questo `Pen`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Brush](../../com.aspose.imaging/brush) | Un `Brush` che determina gli attributi di questo `Pen`. |

### getDashStyle() {#getDashStyle--}
```
public int getDashStyle()
```


Ottiene lo stile usato per le linee tratteggiate disegnate con questo `Pen`.

**Returns:**
int - Un `DashStyle` che rappresenta lo stile usato per le linee tratteggiate disegnate con questo `Pen`.
### setDashStyle(int value) {#setDashStyle-int-}
```
public void setDashStyle(int value)
```


Imposta lo stile usato per le linee tratteggiate disegnate con questo `Pen`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Un `DashStyle` che rappresenta lo stile usato per le linee tratteggiate disegnate con questo `Pen`. |

### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


Ottiene la distanza dall'inizio di una linea all'inizio di un modello di tratteggio.

**Returns:**
float - La distanza dall'inizio di una linea all'inizio di un modello di tratteggio.
### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


Imposta la distanza dall'inizio di una linea all'inizio di un modello di tratteggio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | La distanza dall'inizio di una linea all'inizio di un modello di tratteggio. |

### getDashPattern() {#getDashPattern--}
```
public float[] getDashPattern()
```


Ottiene un array di trattini e spazi personalizzati.

**Returns:**
float[] - Un array di numeri reali che specifica le lunghezze di trattini e spazi alternati nelle linee tratteggiate.
### setDashPattern(float[] value) {#setDashPattern-float---}
```
public void setDashPattern(float[] value)
```


Imposta un array di trattini e spazi personalizzati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float[] | Un array di numeri reali che specifica le lunghezze di trattini e spazi alternati nelle linee tratteggiate. |

### getCompoundArray() {#getCompoundArray--}
```
public float[] getCompoundArray()
```


Ottiene un array di valori che specifica una penna composta. Una penna composta disegna una linea composta da linee parallele e spazi.

**Returns:**
float[] - Un array di numeri reali che specifica l'array composto. Gli elementi dell'array devono essere in ordine crescente, non inferiori a 0 e non superiori a 1.
### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public void setCompoundArray(float[] value)
```


Imposta un array di valori che specifica una penna composta. Una penna composta disegna una linea composta da linee parallele e spazi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float[] | Un array di numeri reali che specifica l'array composto. Gli elementi dell'array devono essere in ordine crescente, non inferiori a 0 e non superiori a 1. |

### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public void setLineCap(int startCap, int endCap, int dashCap)
```


Imposta i valori che determinano lo stile dell'estremità usato per terminare le linee disegnate da questo `Pen`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startCap | int | Un `LineCap` che rappresenta lo stile del cap da usare all'inizio delle linee disegnate con questo `Pen`. |
| endCap | int | Un `LineCap` che rappresenta lo stile del cap da usare alla fine delle linee disegnate con questo `Pen`. |
| dashCap | int | Un `LineCap` che rappresenta lo stile del cap da usare all'inizio o alla fine delle linee tratteggiate disegnate con questo `Pen`. |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Reimposta la matrice di trasformazione geometrica per questo `Pen` all'identità.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.imaging.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Moltiplica la matrice di trasformazione per questo `Pen` per la `Matrix` specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | L'oggetto `Matrix` con cui moltiplicare la matrice di trasformazione. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.imaging.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Moltiplica la matrice di trasformazione per questo `Pen` per la `Matrix` specificata nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Il `Matrix` con cui moltiplicare la matrice di trasformazione. |
| order | int | L'ordine in cui eseguire l'operazione di moltiplicazione. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Trasla la trasformazione geometrica locale delle dimensioni specificate. Questo metodo antepone la traslazione alla trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dx | float | Il valore della traslazione in x. |
| dy | float | Il valore della traslazione in y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Trasla la trasformazione geometrica locale per le dimensioni specificate nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dx | float | Il valore della traslazione in x. |
| dy | float | Il valore della traslazione in y. |
| order | int | L'ordine (anteporre o aggiungere) con cui applicare la traslazione. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Scala la trasformazione geometrica locale dei fattori specificati. Questo metodo antepone la matrice di scala alla trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sx | float | Il fattore con cui scalare la trasformazione nella direzione dell'asse x. |
| sy | float | Il fattore con cui scalare la trasformazione nella direzione dell'asse y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Scala la trasformazione geometrica locale dei fattori specificati nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sx | float | Il fattore con cui scalare la trasformazione nella direzione dell'asse x. |
| sy | float | Il fattore con cui scalare la trasformazione nella direzione dell'asse y. |
| order | int | Un `MatrixOrder` che specifica se aggiungere o anteporre la matrice di scala. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Ruota la trasformazione geometrica locale dell'angolo specificato. Questo metodo antepone la rotazione alla trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | L'angolo di rotazione. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Ruota la trasformazione geometrica locale dell'angolo specificato nell'ordine specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | L'angolo di rotazione. |
| order | int | Un `MatrixOrder` che specifica se aggiungere o anteporre la matrice di rotazione. |

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
int
