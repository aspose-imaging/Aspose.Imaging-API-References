---
title: RectangleShape
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Inizializza una nuova istanza diRectangleShapeaspose.imaging.shapes/rectangleshape classe.
type: docs
weight: 10
url: /it/aspose.imaging.shapes/rectangleshape/rectangleshape/
---
## RectangleShape() {#constructor}

Inizializza una nuova istanza di[`RectangleShape`](../../rectangleshape) classe.

```csharp
public RectangleShape()
```

### Guarda anche

* class [RectangleShape](../../rectangleshape)
* spazio dei nomi [Aspose.Imaging.Shapes](../../rectangleshape)
* assemblea [Aspose.Imaging](../../../)

---

## RectangleShape(RectangleF) {#constructor_1}

Inizializza una nuova istanza di[`RectangleShape`](../../rectangleshape) classe.

```csharp
public RectangleShape(RectangleF rectangle)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | RectangleF | Il rettangolo. |

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

Questo esempio crea una nuova immagine e disegna una varietà di forme usando Figures e GraphicsPath nell'area dell'immagine

```csharp
[C#]

//Crea un'istanza di BmpOptions e ne imposta le varie proprietà            
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//Crea un'istanza di FileCreateSource e assegnala come origine per l'istanza di BmpOptions
//Il secondo parametro booleano determina se il file da creare è Temporale o meno
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"c:\temp\output.bmp", false);

//Crea un'istanza di Image 
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //Crea e inizializza un'istanza della classe Graphics
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    //Cancella superficie grafica
    graphics.Clear(Color.Wheat);

    //Crea un'istanza della classe GraphicsPath
    Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

    //Crea un'istanza della classe Figure
    Aspose.Imaging.Figure figure1 = new Aspose.Imaging.Figure();

    //Aggiungi forma all'oggetto Figura
    figure1.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.Imaging.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Crea un'istanza della classe Figure
    Aspose.Imaging.Figure figure2 = new Aspose.Imaging.Figure();

    //Aggiungi forma all'oggetto Figura
    figure2.AddShape(new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.Imaging.Shapes.PolygonShape(new[] { new Aspose.Imaging.PointF(150, 10), new Aspose.Imaging.PointF(150, 200), new Aspose.Imaging.PointF(250, 300), new Aspose.Imaging.PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(200, 200))));

    //Aggiungi l'oggetto Figure a GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //Disegna il percorso con l'oggetto Penna di colore Nero
    graphics.DrawPath(new Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

    // salva tutte le modifiche.
    image.Save();
}
```

### Guarda anche

* struct [RectangleF](../../../aspose.imaging/rectanglef)
* class [RectangleShape](../../rectangleshape)
* spazio dei nomi [Aspose.Imaging.Shapes](../../rectangleshape)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
