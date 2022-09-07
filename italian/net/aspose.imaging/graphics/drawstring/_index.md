---
title: DrawString
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Disegna la stringa di testo specificata nella posizione specificata con loggetto specificatoBrushaspose.imaging/brush eFontaspose.imaging/font oggetti.
type: docs
weight: 320
url: /it/net/aspose.imaging/graphics/drawstring/
---
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

Disegna la stringa di testo specificata nella posizione specificata con l'oggetto specificato[`Brush`](../../brush) e[`Font`](../../font) oggetti.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | String | Stringa da disegnare. |
| font | Font | [`Font`](../../font) che definisce il formato del testo della stringa. |
| brush | Brush | [`Brush`](../../brush) che determina il colore e la consistenza del testo disegnato. |
| x | Single | La coordinata x dell'angolo superiore sinistro del testo disegnato. |
| y | Single | La coordinata y dell'angolo superiore sinistro del testo disegnato. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *brush* è nullo. -o- *s* è zero. |

### Guarda anche

* class [Font](../../font)
* class [Brush](../../brush)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.Imaging](../../graphics)
* assemblea [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

Disegna la stringa di testo specificata nella posizione specificata con l'oggetto specificato[`Brush`](../../brush) e[`Font`](../../font) oggetti.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | String | Stringa da disegnare. |
| font | Font | [`Font`](../../font) che definisce il formato del testo della stringa. |
| brush | Brush | [`Brush`](../../brush) che determina il colore e la consistenza del testo disegnato. |
| point | PointF | [`PointF`](../../pointf) struttura che specifica l'angolo superiore sinistro del testo disegnato. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *brush* è nullo. -o- *s* è zero. |

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

* class [Font](../../font)
* class [Brush](../../brush)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.Imaging](../../graphics)
* assemblea [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

Disegna la stringa di testo specificata nella posizione specificata con l'oggetto specificato[`Brush`](../../brush) e[`Font`](../../font) oggetti che utilizzano gli attributi di formattazione dell'oggetto specificato[`StringFormat`](../../stringformat) .

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | String | Stringa da disegnare. |
| font | Font | [`Font`](../../font) che definisce il formato del testo della stringa. |
| brush | Brush | [`Brush`](../../brush) che determina il colore e la consistenza del testo disegnato. |
| x | Single | La coordinata x dell'angolo superiore sinistro del testo disegnato. |
| y | Single | La coordinata y dell'angolo superiore sinistro del testo disegnato. |
| format | StringFormat | [`StringFormat`](../../stringformat) che specifica gli attributi di formattazione, come l'interlinea e l'allineamento, che vengono applicati al testo disegnato. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *brush* è nullo. -o- *s* è zero. |

### Guarda anche

* class [Font](../../font)
* class [Brush](../../brush)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.Imaging](../../graphics)
* assemblea [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

Disegna la stringa di testo specificata nella posizione specificata con l'oggetto specificato[`Brush`](../../brush) e[`Font`](../../font) oggetti che utilizzano gli attributi di formattazione dell'oggetto specificato[`StringFormat`](../../stringformat) .

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | String | Stringa da disegnare. |
| font | Font | [`Font`](../../font) che definisce il formato del testo della stringa. |
| brush | Brush | [`Brush`](../../brush) che determina il colore e la consistenza del testo disegnato. |
| point | PointF | [`PointF`](../../pointf) struttura che specifica l'angolo superiore sinistro del testo disegnato. |
| format | StringFormat | [`StringFormat`](../../stringformat) che specifica gli attributi di formattazione, come l'interlinea e l'allineamento, che vengono applicati al testo disegnato. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *brush* è nullo. -o- *s* è zero. |

### Guarda anche

* class [Font](../../font)
* class [Brush](../../brush)
* struct [PointF](../../pointf)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.Imaging](../../graphics)
* assemblea [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

Disegna la stringa di testo specificata nel rettangolo specificato con l'oggetto specificato[`Brush`](../../brush) e[`Font`](../../font) oggetti.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | String | Stringa da disegnare. |
| font | Font | [`Font`](../../font) che definisce il formato del testo della stringa. |
| brush | Brush | [`Brush`](../../brush) che determina il colore e la consistenza del testo disegnato. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef) struttura che specifica la posizione del testo disegnato. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *brush* è nullo. -o- *s* è zero. |

### Guarda anche

* class [Font](../../font)
* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.Imaging](../../graphics)
* assemblea [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

Disegna la stringa di testo specificata nel rettangolo specificato con l'oggetto specificato[`Brush`](../../brush) e[`Font`](../../font) oggetti che utilizzano gli attributi di formattazione dell'oggetto specificato[`StringFormat`](../../stringformat) .

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | String | Stringa da disegnare. |
| font | Font | [`Font`](../../font) che definisce il formato del testo della stringa. |
| brush | Brush | [`Brush`](../../brush) che determina il colore e la consistenza del testo disegnato. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef) struttura che specifica la posizione del testo disegnato. |
| format | StringFormat | [`StringFormat`](../../stringformat) che specifica gli attributi di formattazione, come l'interlinea e l'allineamento, che vengono applicati al testo disegnato. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *brush* è nullo. -o- *s* è nullo. -o- *brush* è zero. |

### Guarda anche

* class [Font](../../font)
* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.Imaging](../../graphics)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
