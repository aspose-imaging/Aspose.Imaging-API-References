---
title: DrawRectangle
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Disegna un rettangolo specificato da aRectangleFaspose.imaging/rectanglef struttura.
type: docs
weight: 300
url: /it/net/aspose.imaging/graphics/drawrectangle/
---
## DrawRectangle(Pen, RectangleF) {#drawrectangle_1}

Disegna un rettangolo specificato da a[`RectangleF`](../../rectanglef) struttura.

```csharp
public void DrawRectangle(Pen pen, RectangleF rect)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | Pen | UN[`Pen`](../../pen) che determina il colore, la larghezza e lo stile del rettangolo. |
| rect | RectangleF | UN[`RectangleF`](../../rectanglef) struttura che rappresenta il rettangolo da disegnare. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *pen* è zero. |

### Guarda anche

* class [Pen](../../pen)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.Imaging](../../graphics)
* assemblea [Aspose.Imaging](../../../)

---

## DrawRectangle(Pen, Rectangle) {#drawrectangle}

Disegna un rettangolo specificato da a[`Rectangle`](../../rectangle) struttura.

```csharp
public void DrawRectangle(Pen pen, Rectangle rect)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | Pen | UN[`Pen`](../../pen) che determina il colore, la larghezza e lo stile del rettangolo. |
| rect | Rectangle | UN[`Rectangle`](../../rectangle) struttura che rappresenta il rettangolo da disegnare. |

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
* struct [Rectangle](../../rectangle)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.Imaging](../../graphics)
* assemblea [Aspose.Imaging](../../../)

---

## DrawRectangle(Pen, float, float, float, float) {#drawrectangle_3}

Disegna un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza.

```csharp
public void DrawRectangle(Pen pen, float x, float y, float width, float height)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | Pen | UN[`Pen`](../../pen) che determina il colore, la larghezza e lo stile del rettangolo. |
| x | Single | La coordinata x dell'angolo superiore sinistro del rettangolo da disegnare. |
| y | Single | La coordinata y dell'angolo superiore sinistro del rettangolo da disegnare. |
| width | Single | La larghezza del rettangolo da disegnare. |
| height | Single | L'altezza del rettangolo da disegnare. |

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

## DrawRectangle(Pen, int, int, int, int) {#drawrectangle_2}

Disegna un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza.

```csharp
public void DrawRectangle(Pen pen, int x, int y, int width, int height)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) che determina il colore, la larghezza e lo stile del rettangolo. |
| x | Int32 | La coordinata x dell'angolo superiore sinistro del rettangolo da disegnare. |
| y | Int32 | La coordinata y dell'angolo superiore sinistro del rettangolo da disegnare. |
| width | Int32 | Larghezza del rettangolo da disegnare. |
| height | Int32 | Altezza del rettangolo da disegnare. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *pen* è zero. |

### Guarda anche

* class [Pen](../../pen)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.Imaging](../../graphics)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
