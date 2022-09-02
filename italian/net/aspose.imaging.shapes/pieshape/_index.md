---
title: PieShape
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Rappresenta una forma a torta.
type: docs
weight: 10990
url: /it/net/aspose.imaging.shapes/pieshape/
---
## PieShape class

Rappresenta una forma a torta.

```csharp
public class PieShape : EllipseShape
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PieShape](pieshape#constructor)() | Inizializza una nuova istanza di[`PieShape`](../pieshape) classe. |
| [PieShape](pieshape#constructor_1)(RectangleF, float, float) | Inizializza una nuova istanza di[`PieShape`](../pieshape) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [Bounds](../../aspose.imaging.shapes/rectangleprojectedshape/bounds) { get; } | Ottiene i limiti dell'oggetto. |
| override [Center](../../aspose.imaging.shapes/rectangleprojectedshape/center) { get; } | Ottiene il centro della forma. |
| override [HasSegments](../../aspose.imaging.shapes/rectangleprojectedshape/hassegments) { get; } | Ottiene un valore che indica se la forma ha segmenti. |
| [LeftBottom](../../aspose.imaging.shapes/rectangleprojectedshape/leftbottom) { get; } | Ottiene il punto del rettangolo in basso a sinistra. |
| [LeftTop](../../aspose.imaging.shapes/rectangleprojectedshape/lefttop) { get; } | Ottiene il punto del rettangolo in alto a sinistra. |
| [RectangleHeight](../../aspose.imaging.shapes/rectangleprojectedshape/rectangleheight) { get; } | Ottiene l'altezza del rettangolo. |
| [RectangleWidth](../../aspose.imaging.shapes/rectangleprojectedshape/rectanglewidth) { get; } | Ottiene la larghezza del rettangolo. |
| [RightBottom](../../aspose.imaging.shapes/rectangleprojectedshape/rightbottom) { get; } | Ottiene il punto del rettangolo in basso a destra. |
| [RightTop](../../aspose.imaging.shapes/rectangleprojectedshape/righttop) { get; } | Ottiene il punto rettangolo in alto a destra. |
| override [Segments](../../aspose.imaging.shapes/pieshape/segments) { get; } | Ottiene i segmenti della forma. |
| [StartAngle](../../aspose.imaging.shapes/pieshape/startangle) { get; set; } | Ottiene o imposta l'angolo iniziale. |
| [SweepAngle](../../aspose.imaging.shapes/pieshape/sweepangle) { get; set; } | Ottiene o imposta l'angolo di sweep. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [GetBounds](../../aspose.imaging.shapes/rectangleprojectedshape/getbounds)(Matrix) | Ottiene i limiti dell'oggetto. |
| override [GetBounds](../../aspose.imaging.shapes/rectangleprojectedshape/getbounds)(Matrix, Pen) | Ottiene i limiti dell'oggetto. |
| override [Transform](../../aspose.imaging.shapes/rectangleprojectedshape/transform)(Matrix) | Applica la trasformazione specificata alla forma. |

### Esempi

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

* class [EllipseShape](../ellipseshape)
* spazio dei nomi [Aspose.Imaging.Shapes](../../aspose.imaging.shapes)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
