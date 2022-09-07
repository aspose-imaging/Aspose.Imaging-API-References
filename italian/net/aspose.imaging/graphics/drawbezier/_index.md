---
title: DrawBezier
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Disegna una spline di Bézier definita da quattro coppie ordinate di coordinate che rappresentano punti.
type: docs
weight: 170
url: /it/net/aspose.imaging/graphics/drawbezier/
---
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

Disegna una spline di Bézier definita da quattro coppie ordinate di coordinate che rappresentano punti.

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) che determina il colore, la larghezza e lo stile della curva. |
| x1 | Single | La coordinata x del punto iniziale della curva. |
| y1 | Single | La coordinata y del punto iniziale della curva. |
| x2 | Single | La coordinata x del primo punto di controllo della curva. |
| y2 | Single | La coordinata y del primo punto di controllo della curva. |
| x3 | Single | La coordinata x del secondo punto di controllo della curva. |
| y3 | Single | La coordinata y del secondo punto di controllo della curva. |
| x4 | Single | La coordinata x del punto finale della curva. |
| y4 | Single | La coordinata y del punto finale della curva. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *pen* è zero. |

### Guarda anche

* class [Pen](../../pen)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.Imaging](../../graphics)
* assemblea [Aspose.Imaging](../../../)

---

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

Disegna una spline Bézier definita da quattro[`PointF`](../../pointf) strutture.

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) che determina il colore, la larghezza e lo stile della curva. |
| pt1 | PointF | [`PointF`](../../pointf) struttura che rappresenta il punto di partenza della curva. |
| pt2 | PointF | [`PointF`](../../pointf) struttura che rappresenta il primo punto di controllo della curva. |
| pt3 | PointF | [`PointF`](../../pointf) struttura che rappresenta il secondo punto di controllo della curva. |
| pt4 | PointF | [`PointF`](../../pointf) struttura che rappresenta il punto finale della curva. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *pen* è zero. |

### Guarda anche

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.Imaging](../../graphics)
* assemblea [Aspose.Imaging](../../../)

---

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

Disegna una spline Bézier definita da quattro[`Point`](../../point) strutture.

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) struttura che determina il colore, la larghezza e lo stile della curva. |
| pt1 | Point | [`Point`](../../point) struttura che rappresenta il punto di partenza della curva. |
| pt2 | Point | [`Point`](../../point) struttura che rappresenta il primo punto di controllo della curva. |
| pt3 | Point | [`Point`](../../point) struttura che rappresenta il secondo punto di controllo della curva. |
| pt4 | Point | [`Point`](../../point) struttura che rappresenta il punto finale della curva. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *pen* è zero. |

### Esempi

Questo esempio usa la classe Graphics per creare forme primitive nell'area dell'immagine. Per dimostrare l'operazione, l'esempio crea una nuova immagine in formato PNG e disegna forme primitive sulla superficie dell'immagine utilizzando i metodi Draw esposti dalla classe Graphics

```csharp
[C#]

//Crea un'istanza di FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.png", System.IO.FileMode.Create))
{
    //Crea un'istanza di PngOptions e imposta le sue varie proprietà
    Aspose.Imaging.ImageOptions.PngOptions pngOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    //Imposta la sorgente per PngOptions
    pngOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Crea un'istanza di Image 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(pngOptions, 500, 500))
    {
        //Crea e inizializza un'istanza della classe Graphics
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Cancella superficie grafica
        graphics.Clear(Aspose.Imaging.Color.Wheat);

        //Disegna un arco specificando l'oggetto Penna con colore Nero, 
        //un rettangolo che circonda l'arco, l'angolo iniziale e l'angolo di sweep
        graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), new Aspose.Imaging.Rectangle(200, 200, 100, 200), 0, 300);

        //Disegna un Bezier specificando l'oggetto Penna con colore blu e punti coordinati.
        graphics.DrawBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Point(250, 100), new Aspose.Imaging.Point(300, 30), new Aspose.Imaging.Point(450, 100), new Aspose.Imaging.Point(235, 25));

        //Disegna una curva specificando l'oggetto Penna con colore verde e una matrice di punti
        graphics.DrawCurve(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new[] { new Aspose.Imaging.Point(100, 200), new Aspose.Imaging.Point(100, 350), new Aspose.Imaging.Point(200, 450) });

        //Disegna un'ellisse usando l'oggetto Penna e un rettangolo circostante
        graphics.DrawEllipse(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 2), new Aspose.Imaging.Rectangle(300, 300, 100, 100));

        //Disegna una linea 
        graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Violet, 2), new Aspose.Imaging.Point(100, 100), new Aspose.Imaging.Point(200, 200));

        //Disegna un segmento di torta
        graphics.DrawPie(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Silver, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(200, 20), new Aspose.Imaging.Size(200, 200)), 0, 45);

        //Disegna un poligono specificando l'oggetto Penna con colore rosso e una matrice di punti
        graphics.DrawPolygon(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2), new[] { new Aspose.Imaging.Point(20, 100), new Aspose.Imaging.Point(20, 200), new Aspose.Imaging.Point(220, 20) });

        //Disegna un rettangolo
        graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(100, 100)));

        //Crea un oggetto SolidBrush e imposta le sue varie proprietà
        Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush();
        brush.Color = Color.Purple;
        brush.Opacity = 100;

        //Disegna una stringa usando l'oggetto SolidBrush e Font, in un punto specifico
        graphics.DrawString("This image is created by Aspose.Imaging API", new Aspose.Imaging.Font("Times New Roman", 16), brush, new Aspose.Imaging.PointF(50, 400));

        // salva tutte le modifiche.
        image.Save();
    }
}
```

### Guarda anche

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.Imaging](../../graphics)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
