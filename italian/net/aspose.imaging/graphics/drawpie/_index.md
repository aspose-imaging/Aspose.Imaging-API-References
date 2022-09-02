---
title: DrawPie
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Disegna una forma a torta definita da unellisse specificata da aRectangleFaspose.imaging/rectanglef struttura e due linee radiali.
type: docs
weight: 280
url: /it/net/aspose.imaging/graphics/drawpie/
---
## DrawPie(Pen, RectangleF, float, float) {#drawpie_1}

Disegna una forma a torta definita da un'ellisse specificata da a[`RectangleF`](../../rectanglef) struttura e due linee radiali.

```csharp
public void DrawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) che determina il colore, la larghezza e lo stile della forma della torta. |
| rect | RectangleF | [`RectangleF`](../../rectanglef) struttura che rappresenta il rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| startAngle | Single | Angolo misurato in gradi in senso orario dall'asse x al primo lato della forma a torta. |
| sweepAngle | Single | Angolo misurato in gradi in senso orario dal*startAngle* parametro al secondo lato della forma della torta. |

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

## DrawPie(Pen, float, float, float, float, float, float) {#drawpie_3}

Disegna una forma a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali.

```csharp
public void DrawPie(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) che determina il colore, la larghezza e lo stile della forma della torta. |
| x | Single | Coordinata x dell'angolo superiore sinistro del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| y | Single | La coordinata y dell'angolo superiore sinistro del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| width | Single | Larghezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| height | Single | Altezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| startAngle | Single | Angolo misurato in gradi in senso orario dall'asse x al primo lato della forma a torta. |
| sweepAngle | Single | Angolo misurato in gradi in senso orario dal*startAngle* parametro al secondo lato della forma della torta. |

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

## DrawPie(Pen, Rectangle, float, float) {#drawpie}

Disegna una forma a torta definita da un'ellisse specificata da a[`Rectangle`](../../rectangle) struttura e due linee radiali.

```csharp
public void DrawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) che determina il colore, la larghezza e lo stile della forma della torta. |
| rect | Rectangle | [`Rectangle`](../../rectangle) struttura che rappresenta il rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| startAngle | Single | Angolo misurato in gradi in senso orario dall'asse x al primo lato della forma a torta. |
| sweepAngle | Single | Angolo misurato in gradi in senso orario dal*startAngle* parametro al secondo lato della forma della torta. |

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

## DrawPie(Pen, int, int, int, int, int, int) {#drawpie_2}

Disegna una forma a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali.

```csharp
public void DrawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) che determina il colore, la larghezza e lo stile della forma della torta. |
| x | Int32 | Coordinata x dell'angolo superiore sinistro del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| y | Int32 | La coordinata y dell'angolo superiore sinistro del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| width | Int32 | Larghezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| height | Int32 | Altezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| startAngle | Int32 | Angolo misurato in gradi in senso orario dall'asse x al primo lato della forma a torta. |
| sweepAngle | Int32 | Angolo misurato in gradi in senso orario dal*startAngle* parametro al secondo lato della forma della torta. |

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
