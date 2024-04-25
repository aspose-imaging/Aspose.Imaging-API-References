---
title: Pen
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Definisce un oggetto utilizzato per disegnare linee curve e figure.
type: docs
weight: 10690
url: /it/aspose.imaging/pen/
---
## Pen class

Definisce un oggetto utilizzato per disegnare linee, curve e figure.

```csharp
public class Pen : TransparencySupporter
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Pen](pen#constructor)(Brush) | Inizializza una nuova istanza di[`Pen`](../pen) classe con il specificato[`Brush`](./brush) . |
| [Pen](pen#constructor_2)(Color) | Inizializza una nuova istanza di[`Pen`](../pen) classe con il colore specificato. |
| [Pen](pen#constructor_1)(Brush, float) | Inizializza una nuova istanza di[`Pen`](../pen) classe con il specificato[`Brush`](./brush) e[`Width`](./width) . |
| [Pen](pen#constructor_3)(Color, float) | Inizializza una nuova istanza di[`Pen`](../pen) classe con il specificato[`Color`](./color) e[`Width`](./width) proprietà. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Alignment](../../aspose.imaging/pen/alignment) { get; set; } | Ottiene o imposta l'allineamento per questo[`Pen`](../pen) . |
| [Brush](../../aspose.imaging/pen/brush) { get; set; } | Ottiene o imposta il[`Brush`](./brush) che determina gli attributi di questo[`Pen`](../pen) . |
| [Color](../../aspose.imaging/pen/color) { get; set; } | Ottiene o imposta il colore di questo[`Pen`](../pen) . |
| [CompoundArray](../../aspose.imaging/pen/compoundarray) { get; set; } | Ottiene o imposta una matrice di valori che specifica una penna composta. Una penna composta disegna una linea composta composta da linee e spazi paralleli. |
| [CustomEndCap](../../aspose.imaging/pen/customendcap) { get; set; } | Ottiene o imposta un limite personalizzato da utilizzare alla fine delle linee tracciate con questo[`Pen`](../pen) . |
| [CustomStartCap](../../aspose.imaging/pen/customstartcap) { get; set; } | Ottiene o imposta un limite personalizzato da utilizzare all'inizio delle linee disegnate con questo[`Pen`](../pen) . |
| [DashCap](../../aspose.imaging/pen/dashcap) { get; set; } | Ottiene o imposta lo stile del cappuccio utilizzato alla fine dei trattini che compongono le linee tratteggiate disegnate con questo[`Pen`](../pen) . |
| [DashOffset](../../aspose.imaging/pen/dashoffset) { get; set; } | Ottiene o imposta la distanza dall'inizio di una linea all'inizio di una sequenza di trattini. |
| [DashPattern](../../aspose.imaging/pen/dashpattern) { get; set; } | Ottiene o imposta una matrice di trattini e spazi personalizzati. |
| [DashStyle](../../aspose.imaging/pen/dashstyle) { get; set; } | Ottiene o imposta lo stile utilizzato per le linee tratteggiate disegnate con questo[`Pen`](../pen) . |
| [EndCap](../../aspose.imaging/pen/endcap) { get; set; } | Ottiene o imposta lo stile del cappuccio utilizzato alla fine delle righe disegnate con questo[`Pen`](../pen) . |
| [LineJoin](../../aspose.imaging/pen/linejoin) { get; set; } | Ottiene o imposta lo stile di unione per le estremità di due linee consecutive disegnate con questo[`Pen`](../pen) . |
| [MiterLimit](../../aspose.imaging/pen/miterlimit) { get; set; } | Ottiene o imposta il limite dello spessore del giunto su un angolo smussato. |
| [Opacity](../../aspose.imaging/transparencysupporter/opacity) { get; set; } | Ottiene o imposta l'opacità dell'oggetto. Il valore deve essere compreso tra 0 e 1. Il valore 0 significa che l'oggetto è completamente visibile, il valore 1 significa che l'oggetto è completamente opaco. |
| [PenType](../../aspose.imaging/pen/pentype) { get; } | Ottiene lo stile delle linee disegnate con questo[`Pen`](../pen) . |
| [StartCap](../../aspose.imaging/pen/startcap) { get; set; } | Ottiene o imposta lo stile del cappuccio utilizzato all'inizio delle linee disegnate con questo[`Pen`](../pen) . |
| [Transform](../../aspose.imaging/pen/transform) { get; set; } | Ottiene o imposta una copia della trasformazione geometrica per questo[`Pen`](../pen) . |
| [Width](../../aspose.imaging/pen/width) { get; set; } | Ottiene o imposta la larghezza di questo[`Pen`](../pen) , in unità dell'oggetto Graphics utilizzato per il disegno. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [MultiplyTransform](../../aspose.imaging/pen/multiplytransform#multiplytransform)(Matrix) | Moltiplica la matrice di trasformazione per questo[`Pen`](../pen) dal specificato[`Matrix`](../matrix) . |
| [MultiplyTransform](../../aspose.imaging/pen/multiplytransform#multiplytransform_1)(Matrix, MatrixOrder) | Moltiplica la matrice di trasformazione per questo[`Pen`](../pen) dal specificato[`Matrix`](../matrix) nell'ordine specificato. |
| [ResetTransform](../../aspose.imaging/pen/resettransform)() | Reimposta la matrice di trasformazione geometrica per questo[`Pen`](../pen) all'identità. |
| [RotateTransform](../../aspose.imaging/pen/rotatetransform#rotatetransform)(float) | Ruota la trasformazione geometrica locale dell'angolo specificato. Questo metodo antepone la rotazione alla trasformazione. |
| [RotateTransform](../../aspose.imaging/pen/rotatetransform#rotatetransform_1)(float, MatrixOrder) | Ruota la trasformazione geometrica locale dell'angolo specificato nell'ordine specificato. |
| [ScaleTransform](../../aspose.imaging/pen/scaletransform#scaletransform)(float, float) | Ridimensiona la trasformazione geometrica locale in base ai fattori specificati. Questo metodo antepone la matrice di ridimensionamento alla trasformazione. |
| [ScaleTransform](../../aspose.imaging/pen/scaletransform#scaletransform_1)(float, float, MatrixOrder) | Ridimensiona la trasformazione geometrica locale in base ai fattori specificati nell'ordine specificato. |
| [SetLineCap](../../aspose.imaging/pen/setlinecap)(LineCap, LineCap, DashCap) | Imposta i valori che determinano lo stile del cappuccio utilizzato per terminare le linee tracciate da questo[`Pen`](../pen) . |
| [TranslateTransform](../../aspose.imaging/pen/translatetransform#translatetransform)(float, float) | Converte la trasformazione geometrica locale in base alle dimensioni specificate. Questo metodo antepone la traduzione alla trasformazione. |
| [TranslateTransform](../../aspose.imaging/pen/translatetransform#translatetransform_1)(float, float, MatrixOrder) | Converte la trasformazione geometrica locale in base alle dimensioni specificate nell'ordine specificato. |

### Esempi

Questo esempio mostra la creazione e l'utilizzo di oggetti Pen. L'esempio crea una nuova immagine e disegna rettangoli sulla superficie dell'immagine.

```csharp
[C#]

//Crea un'istanza di BmpOptions e imposta le sue varie proprietà
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//Crea un'istanza di FileCreateSource e assegnala come origine per l'istanza di BmpOptions
//Il secondo parametro booleano determina se il file da creare è Temporale o meno
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\sample.bmp", false);

//Crea un'istanza di Image nel percorso specificato
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //Crea un'istanza di Graphics e inizializzala con l'oggetto Image
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    //Cancella la superficie grafica con il colore bianco
    graphics.Clear(Aspose.Imaging.Color.White);

    //Crea un'istanza di Pen con colore rosso e larghezza 5
    Aspose.Imaging.Pen pen = new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 5f);

    //Crea un'istanza di HatchBrush e imposta le sue proprietà
    Aspose.Imaging.Brushes.HatchBrush brush = new Aspose.Imaging.Brushes.HatchBrush();
    brush.BackgroundColor = Aspose.Imaging.Color.Wheat;
    brush.ForegroundColor = Aspose.Imaging.Color.Red;

    //Crea un'istanza di Pen
    //inizializzalo con l'oggetto HatchBrush e la larghezza
    Aspose.Imaging.Pen brusedpen = new Pen(brush, 5);

    //Disegna rettangoli specificando l'oggetto Penna
    graphics.DrawRectangles(pen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(210, 210), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 310), new Aspose.Imaging.Size(100, 100))
    });

    //Disegna rettangoli specificando l'oggetto Penna
    graphics.DrawRectangles(brusedpen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 310), new Aspose.Imaging.Size(100, 100))
    });

    // salva tutte le modifiche.
    image.Save();
}
```

### Guarda anche

* class [TransparencySupporter](../transparencysupporter)
* spazio dei nomi [Aspose.Imaging](../../aspose.imaging)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
