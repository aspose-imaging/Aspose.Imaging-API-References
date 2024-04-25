---
title: Pen
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Inizializza una nuova istanza diPenaspose.imaging/pen classe con il colore specificato.
type: docs
weight: 10
url: /it/aspose.imaging/pen/pen/
---
## Pen(Color) {#constructor_2}

Inizializza una nuova istanza di[`Pen`](../../pen) classe con il colore specificato.

```csharp
public Pen(Color color)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| color | Color | UN[`Color`](../color) struttura che ne indica il colore[`Pen`](../../pen). |

### Guarda anche

* struct [Color](../../color)
* class [Pen](../../pen)
* spazio dei nomi [Aspose.Imaging](../../pen)
* assemblea [Aspose.Imaging](../../../)

---

## Pen(Color, float) {#constructor_3}

Inizializza una nuova istanza di[`Pen`](../../pen) classe con il specificato[`Color`](../color) e[`Width`](../width) proprietà.

```csharp
public Pen(Color color, float width)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| color | Color | UN[`Color`](../color) struttura che ne indica il colore[`Pen`](../../pen). |
| width | Single | Un valore che indica la larghezza di questo[`Pen`](../../pen). |

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

* struct [Color](../../color)
* class [Pen](../../pen)
* spazio dei nomi [Aspose.Imaging](../../pen)
* assemblea [Aspose.Imaging](../../../)

---

## Pen(Brush) {#constructor}

Inizializza una nuova istanza di[`Pen`](../../pen) classe con il specificato[`Brush`](../brush) .

```csharp
public Pen(Brush brush)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | Brush | UN[`Brush`](../brush) che determina le proprietà di riempimento di questo[`Pen`](../../pen). |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *brush* è zero. |

### Guarda anche

* class [Brush](../../brush)
* class [Pen](../../pen)
* spazio dei nomi [Aspose.Imaging](../../pen)
* assemblea [Aspose.Imaging](../../../)

---

## Pen(Brush, float) {#constructor_1}

Inizializza una nuova istanza di[`Pen`](../../pen) classe con il specificato[`Brush`](../brush) e[`Width`](../width) .

```csharp
public Pen(Brush brush, float width)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | Brush | UN[`Brush`](../brush) che ne determina le caratteristiche[`Pen`](../../pen). |
| width | Single | La larghezza del nuovo[`Pen`](../../pen). |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *brush* è zero. |

### Guarda anche

* class [Brush](../../brush)
* class [Pen](../../pen)
* spazio dei nomi [Aspose.Imaging](../../pen)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
