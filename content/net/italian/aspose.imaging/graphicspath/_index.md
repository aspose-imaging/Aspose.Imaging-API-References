---
title: GraphicsPath
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Rappresenta una serie di linee e curve collegate. Questa classe non può essere ereditata.
type: docs
weight: 9370
url: /it/aspose.imaging/graphicspath/
---
## GraphicsPath class

Rappresenta una serie di linee e curve collegate. Questa classe non può essere ereditata.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [GraphicsPath](graphicspath#constructor)() | Inizializza una nuova istanza di[`GraphicsPath`](../graphicspath) classe. |
| [GraphicsPath](graphicspath#constructor_1)(Figure[]) | Inizializza una nuova istanza di[`GraphicsPath`](../graphicspath) classe. |
| [GraphicsPath](graphicspath#constructor_3)(FillMode) | Inizializza una nuova istanza di[`GraphicsPath`](../graphicspath) classe. |
| [GraphicsPath](graphicspath#constructor_2)(Figure[], FillMode) | Inizializza una nuova istanza di[`GraphicsPath`](../graphicspath) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [Bounds](../../aspose.imaging/graphicspath/bounds) { get; } | Ottiene o imposta i limiti dell'oggetto. |
| [Figures](../../aspose.imaging/graphicspath/figures) { get; } | Ottiene le cifre del percorso. |
| [FillMode](../../aspose.imaging/graphicspath/fillmode) { get; set; } | Ottiene o imposta a[`FillMode`](../fillmode) enumerazione che determina come gli interni delle forme in questo[`GraphicsPath`](../graphicspath) sono riempiti. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddFigure](../../aspose.imaging/graphicspath/addfigure)(Figure) | Aggiunge una nuova figura. |
| [AddFigures](../../aspose.imaging/graphicspath/addfigures)(Figure[]) | Aggiunge nuove figure. |
| [AddPath](../../aspose.imaging/graphicspath/addpath#addpath)(GraphicsPath) | Aggiunge l'oggetto specificato[`GraphicsPath`](../graphicspath) a questo percorso. |
| [AddPath](../../aspose.imaging/graphicspath/addpath#addpath_1)(GraphicsPath, bool) | Aggiunge l'oggetto specificato[`GraphicsPath`](../graphicspath) a questo percorso. |
| [DeepClone](../../aspose.imaging/graphicspath/deepclone)() | Esegue un clone profondo di questo percorso grafico. |
| [Flatten](../../aspose.imaging/graphicspath/flatten#flatten)() | Converte ogni curva in questo percorso in una sequenza di segmenti di linea collegati. |
| [Flatten](../../aspose.imaging/graphicspath/flatten#flatten_1)(Matrix) | Applica la trasformazione specificata e quindi converte ogni curva in questa[`GraphicsPath`](../graphicspath) in una sequenza di segmenti di linea collegati. |
| [Flatten](../../aspose.imaging/graphicspath/flatten#flatten_2)(Matrix, float) | Converte ogni curva in questo[`GraphicsPath`](../graphicspath) in una sequenza di segmenti di linea collegati. |
| override [GetBounds](../../aspose.imaging/graphicspath/getbounds#getbounds)(Matrix) | Ottiene i limiti dell'oggetto. |
| override [GetBounds](../../aspose.imaging/graphicspath/getbounds#getbounds_1)(Matrix, Pen) | Ottiene i limiti dell'oggetto. |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible)(Point, Pen) | Indica se il punto specificato è contenuto all'interno (sotto) il contorno di questo[`GraphicsPath`](../graphicspath) quando disegnato con il specificato[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_2)(PointF, Pen) | Indica se il punto specificato è contenuto all'interno (sotto) il contorno di questo[`GraphicsPath`](../graphicspath) quando disegnato con il specificato[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_6)(float, float, Pen) | Indica se il punto specificato è contenuto all'interno (sotto) il contorno di questo[`GraphicsPath`](../graphicspath) quando disegnato con il specificato[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_4)(int, int, Pen) | Indica se il punto specificato è contenuto all'interno (sotto) il contorno di questo[`GraphicsPath`](../graphicspath) quando disegnato con il specificato[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_1)(Point, Pen, Graphics) | Indica se il punto specificato è contenuto all'interno (sotto) il contorno di questo[`GraphicsPath`](../graphicspath) quando disegnato con il specificato[`Pen`](../pen) e usando il specificato[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_3)(PointF, Pen, Graphics) | Indica se il punto specificato è contenuto all'interno (sotto) il contorno di questo[`GraphicsPath`](../graphicspath) quando disegnato con il specificato[`Pen`](../pen) e usando il specificato[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_7)(float, float, Pen, Graphics) | Indica se il punto specificato è contenuto all'interno (sotto) il contorno di questo[`GraphicsPath`](../graphicspath) quando disegnato con il specificato[`Pen`](../pen) e usando il specificato[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_5)(int, int, Pen, Graphics) | Indica se il punto specificato è contenuto all'interno (sotto) il contorno di questo[`GraphicsPath`](../graphicspath) quando disegnato con il specificato[`Pen`](../pen) e usando il specificato[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible)(Point) | Indica se il punto specificato è contenuto all'interno di questo[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_2)(PointF) | Indica se il punto specificato è contenuto all'interno di questo[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_6)(float, float) | Indica se il punto specificato è contenuto all'interno di questo[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_4)(int, int) | Indica se il punto specificato è contenuto all'interno di questo[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_1)(Point, Graphics) | Indica se il punto specificato è contenuto all'interno di questo[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_3)(PointF, Graphics) | Indica se il punto specificato è contenuto all'interno di questo[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_7)(float, float, Graphics) | Indica se il punto specificato è contenuto all'interno di questo[`GraphicsPath`](../graphicspath) nella regione di clip visibile dell'oggetto specificato[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_5)(int, int, Graphics) | Indica se il punto specificato è contenuto all'interno di questo[`GraphicsPath`](../graphicspath) , utilizzando il specificato[`Graphics`](../graphics) . |
| [RemoveFigure](../../aspose.imaging/graphicspath/removefigure)(Figure) | Rimuove una figura. |
| [RemoveFigures](../../aspose.imaging/graphicspath/removefigures)(Figure[]) | Rimuove le figure. |
| [Reset](../../aspose.imaging/graphicspath/reset)() | Svuota il percorso grafico e imposta il[`FillMode`](../fillmode) aAlternate . |
| [Reverse](../../aspose.imaging/graphicspath/reverse)() | Inverte l'ordine di figure, forme e punti in ogni forma di questo[`GraphicsPath`](../graphicspath) . |
| override [Transform](../../aspose.imaging/graphicspath/transform)(Matrix) | Applica la trasformazione specificata alla forma. |
| [Warp](../../aspose.imaging/graphicspath/warp#warp)(PointF[], RectangleF) | Applica una trasformata warp, definita da un rettangolo e un parallelogramma, a questo[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.imaging/graphicspath/warp#warp_1)(PointF[], RectangleF, Matrix) | Applica una trasformata warp, definita da un rettangolo e un parallelogramma, a questo[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.imaging/graphicspath/warp#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | Applica una trasformata warp, definita da un rettangolo e un parallelogramma, a questo[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.imaging/graphicspath/warp#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | Applica una trasformata warp, definita da un rettangolo e un parallelogramma, a questo[`GraphicsPath`](../graphicspath) . |
| [Widen](../../aspose.imaging/graphicspath/widen#widen)(Pen) | Aggiunge un contorno aggiuntivo al percorso. |
| [Widen](../../aspose.imaging/graphicspath/widen#widen_1)(Pen, Matrix) | Aggiunge un contorno aggiuntivo al file[`GraphicsPath`](../graphicspath) . |
| [Widen](../../aspose.imaging/graphicspath/widen#widen_2)(Pen, Matrix, float) | Sostituisce questo[`GraphicsPath`](../graphicspath)con curve che racchiudono l'area che viene riempita quando questo percorso viene disegnato dalla penna specificata. |

### Esempi

Questi esempi utilizzano la classe GraphicsPath e Graphics per creare e manipolare figure su un'area Image. Esempio crea una nuova immagine (di tipo Tiff), cancella la superficie e disegna percorsi con l'aiuto della classe GraphicsPath. Alla fine viene chiamato il metodo DrawPath esposto dalla classe Graphics per eseguire il rendering dei tracciati sulla superficie.

```csharp
[C#]

//Crea un'istanza di FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.tiff", System.IO.FileMode.Create))
{
    //Crea un'istanza di TiffOptions e imposta le sue varie proprietà
    Aspose.Imaging.ImageOptions.TiffOptions tiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    //Imposta l'origine per l'istanza di ImageOptions
    tiffOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Crea un'istanza di Image 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(tiffOptions, 500, 500))
    {
        //Crea e inizializza un'istanza della classe Graphics
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Cancella superficie grafica
        graphics.Clear(Color.Wheat);

        //Crea un'istanza della classe GraphicsPath
        Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

        //Crea un'istanza della classe Figure
        Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();

        //Aggiungi forme all'oggetto Figura
        figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(10f, 10f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new Aspose.Imaging.RectangleF(50f, 50f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.PieShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.PointF(250f, 250f), new Aspose.Imaging.SizeF(200f, 200f)), 0f, 45f));

        //Aggiungi l'oggetto Figure a GraphicsPath
        graphicspath.AddFigure(figure);

        //Disegna il percorso con l'oggetto Penna di colore Nero
        graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

        // salva tutte le modifiche.
        image.Save();
    }
}
```

### Guarda anche

* class [ObjectWithBounds](../objectwithbounds)
* spazio dei nomi [Aspose.Imaging](../../aspose.imaging)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
