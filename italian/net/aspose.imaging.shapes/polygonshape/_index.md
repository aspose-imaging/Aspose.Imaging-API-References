---
title: PolygonShape
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Rappresenta una forma poligonale.
type: docs
weight: 11000
url: /it/net/aspose.imaging.shapes/polygonshape/
---
## PolygonShape class

Rappresenta una forma poligonale.

```csharp
public class PolygonShape : Shape, IOrderedShape
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PolygonShape](polygonshape#constructor)() | Inizializza una nuova istanza di[`PolygonShape`](../polygonshape) classe. |
| [PolygonShape](polygonshape#constructor_1)(PointF[]) | Inizializza una nuova istanza di[`PolygonShape`](../polygonshape) classe. |
| [PolygonShape](polygonshape#constructor_2)(PointF[], bool) | Inizializza una nuova istanza di[`PolygonShape`](../polygonshape) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [Bounds](../../aspose.imaging.shapes/polygonshape/bounds) { get; } | Ottiene i limiti dell'oggetto. |
| override [Center](../../aspose.imaging.shapes/polygonshape/center) { get; } | Ottiene il centro della forma. |
| virtual [EndPoint](../../aspose.imaging.shapes/polygonshape/endpoint) { get; } | Ottiene il punto forma finale. |
| override [HasSegments](../../aspose.imaging.shapes/polygonshape/hassegments) { get; } | Ottiene un valore che indica se la forma ha segmenti. |
| [IsClosed](../../aspose.imaging.shapes/polygonshape/isclosed) { get; set; } | Ottiene o imposta un valore che indica se la forma è chiusa. |
| [Points](../../aspose.imaging.shapes/polygonshape/points) { get; set; } | Ottiene o imposta i punti della curva. |
| override [Segments](../../aspose.imaging.shapes/polygonshape/segments) { get; } | Ottiene i segmenti della forma. |
| virtual [StartPoint](../../aspose.imaging.shapes/polygonshape/startpoint) { get; } | Ottiene il punto della forma iniziale. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [GetBounds](../../aspose.imaging.shapes/polygonshape/getbounds#getbounds)(Matrix) | Ottiene i limiti dell'oggetto. |
| override [GetBounds](../../aspose.imaging.shapes/polygonshape/getbounds#getbounds_1)(Matrix, Pen) | Ottiene i limiti dell'oggetto. |
| [Reverse](../../aspose.imaging.shapes/polygonshape/reverse)() | Inverte l'ordine dei punti per questa forma. |
| override [Transform](../../aspose.imaging.shapes/polygonshape/transform)(Matrix) | Applica la trasformazione specificata alla forma. |

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

* class [Shape](../../aspose.imaging/shape)
* interface [IOrderedShape](../../aspose.imaging/iorderedshape)
* spazio dei nomi [Aspose.Imaging.Shapes](../../aspose.imaging.shapes)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
