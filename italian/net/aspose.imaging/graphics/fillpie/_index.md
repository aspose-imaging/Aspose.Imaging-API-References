---
title: FillPie
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Riempie linterno di una sezione di torta definita da unellisse specificata da aRectangleFaspose.imaging/rectanglef struttura e due linee radiali.
type: docs
weight: 370
url: /it/net/aspose.imaging/graphics/fillpie/
---
## FillPie(Brush, Rectangle, float, float) {#fillpie}

Riempie l'interno di una sezione di torta definita da un'ellisse specificata da a[`RectangleF`](../../rectanglef) struttura e due linee radiali.

```csharp
public void FillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush) che determina le caratteristiche del riempimento. |
| rect | Rectangle | [`Rectangle`](../../rectangle)struttura che rappresenta il rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione della torta. |
| startAngle | Single | Angolo in gradi misurato in senso orario dall'asse x al primo lato della sezione della torta. |
| sweepAngle | Single | Angolo in gradi misurato in senso orario dal*startAngle* parametro al secondo lato della sezione della torta. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *brush* è zero. |

### Esempi

L'esempio seguente mostra come comporre un'immagine GIF animata da singoli blocchi GIF.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea un'immagine GIF 100 x 100 px.
// Il primo blocco è completamente nero per impostazione predefinita.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
    // Il primo cerchio è rosso
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // Il secondo cerchio è nero
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // Aumenta gradualmente l'angolo della forma dell'arco rosso.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush1, block.Bounds, 0, angle);

        gifImage.AddBlock(block);
    }

    // Aumenta gradualmente l'angolo dell'arco nero e cancella l'arco rosso.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush2, block.Bounds, 0, angle);
        gr.FillPie(brush1, block.Bounds, angle, 360 - angle);

        gifImage.AddBlock(block);
    }

    gifImage.Save(dir + "animated_radar.gif");
}
```

### Guarda anche

* class [Brush](../../brush)
* struct [Rectangle](../../rectangle)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.Imaging](../../graphics)
* assemblea [Aspose.Imaging](../../../)

---

## FillPie(Brush, RectangleF, float, float) {#fillpie_1}

Riempie l'interno di una sezione di torta definita da un'ellisse specificata da a[`RectangleF`](../../rectanglef) struttura e due linee radiali.

```csharp
public void FillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush) che determina le caratteristiche del riempimento. |
| rect | RectangleF | [`RectangleF`](../../rectanglef)struttura che rappresenta il rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione della torta. |
| startAngle | Single | Angolo in gradi misurato in senso orario dall'asse x al primo lato della sezione della torta. |
| sweepAngle | Single | Angolo in gradi misurato in senso orario dal*startAngle* parametro al secondo lato della sezione della torta. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *brush* è zero. |

### Guarda anche

* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.Imaging](../../graphics)
* assemblea [Aspose.Imaging](../../../)

---

## FillPie(Brush, float, float, float, float, float, float) {#fillpie_3}

Riempie l'interno di una sezione della torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali.

```csharp
public void FillPie(Brush brush, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush) che determina le caratteristiche del riempimento. |
| x | Single | Coordinata x dell'angolo superiore sinistro del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione della torta. |
| y | Single | La coordinata y dell'angolo superiore sinistro del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione della torta. |
| width | Single | Larghezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione della torta. |
| height | Single | Altezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione della torta. |
| startAngle | Single | Angolo in gradi misurato in senso orario dall'asse x al primo lato della sezione della torta. |
| sweepAngle | Single | Angolo in gradi misurato in senso orario dal*startAngle* parametro al secondo lato della sezione della torta. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *brush* è zero. |

### Guarda anche

* class [Brush](../../brush)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.Imaging](../../graphics)
* assemblea [Aspose.Imaging](../../../)

---

## FillPie(Brush, int, int, int, int, int, int) {#fillpie_2}

Riempie l'interno di una sezione della torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali.

```csharp
public void FillPie(Brush brush, int x, int y, int width, int height, int startAngle, 
    int sweepAngle)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush) che determina le caratteristiche del riempimento. |
| x | Int32 | Coordinata x dell'angolo superiore sinistro del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione della torta. |
| y | Int32 | La coordinata y dell'angolo superiore sinistro del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione della torta. |
| width | Int32 | Larghezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione della torta. |
| height | Int32 | Altezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione della torta. |
| startAngle | Int32 | Angolo in gradi misurato in senso orario dall'asse x al primo lato della sezione della torta. |
| sweepAngle | Int32 | Angolo in gradi misurato in senso orario dal*startAngle* parametro al secondo lato della sezione della torta. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *brush* è zero. |

### Guarda anche

* class [Brush](../../brush)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.Imaging](../../graphics)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
