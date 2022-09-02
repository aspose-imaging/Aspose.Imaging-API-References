---
title: LinearGradientBrush
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Inizializza una nuova istanza diLinearGradientBrushaspose.imaging.brushes/lineargradientbrush classe con parametri di default. Il colore iniziale è nero il colore finale è bianco langolo è 45 gradi e il rettangolo si trova in 00 con dimensione 11.
type: docs
weight: 10
url: /it/net/aspose.imaging.brushes/lineargradientbrush/lineargradientbrush/
---
## LinearGradientBrush() {#constructor}

Inizializza una nuova istanza di[`LinearGradientBrush`](../../lineargradientbrush) classe con parametri di default. Il colore iniziale è nero, il colore finale è bianco, l'angolo è 45 gradi e il rettangolo si trova in (0,0) con dimensione (1,1).

```csharp
public LinearGradientBrush()
```

### Guarda anche

* class [LinearGradientBrush](../../lineargradientbrush)
* spazio dei nomi [Aspose.Imaging.Brushes](../../lineargradientbrush)
* assemblea [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Point, Point, Color, Color) {#constructor_1}

Inizializza una nuova istanza di[`LinearGradientBrush`](../../lineargradientbrush) classe con i punti e i colori specificati.

```csharp
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | Point | UN[`Point`](../../../aspose.imaging/point) struttura che rappresenta il punto di partenza del gradiente lineare. |
| point2 | Point | UN[`Point`](../../../aspose.imaging/point) struttura che rappresenta il punto finale del gradiente lineare. |
| color1 | Color | UN[`Color`](../../../aspose.imaging/color) struttura che rappresenta il colore iniziale del gradiente lineare. |
| color2 | Color | UN[`Color`](../../../aspose.imaging/color) struttura che rappresenta il colore finale del gradiente lineare. |

### Esempi

L'esempio seguente mostra come creare una copia in scala di grigi di una cornice esistente e aggiungerla a un'immagine TIFF.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Crea un'origine file permanente, non temporanea.
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // Il gradiente lineare dall'angolo in alto a sinistra all'angolo in basso a destra dell'immagine.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(tiffImage.Width, tiffImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Riempi il fotogramma attivo con un pennello sfumato lineare.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(tiffImage.ActiveFrame);
    gr.FillRectangle(brush, tiffImage.Bounds);

    // Opzioni in scala di grigi
    Aspose.Imaging.ImageOptions.TiffOptions createTiffFrameOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());
    createTiffFrameOptions.Photometric = Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;
    createTiffFrameOptions.BitsPerSample = new ushort[] { 8 };

    // Crea una copia in scala di grigi del fotogramma attivo.
    // I dati dei pixel vengono conservati ma convertiti nel formato desiderato.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame grayscaleFrame = Aspose.Imaging.FileFormats.Tiff.TiffFrame.CreateFrameFrom(tiffImage.ActiveFrame, createTiffFrameOptions);

    // Aggiunge la cornice appena creata all'immagine TIFF.
    tiffImage.AddFrame(grayscaleFrame);

    tiffImage.Save();
}
```

### Guarda anche

* struct [Point](../../../aspose.imaging/point)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* spazio dei nomi [Aspose.Imaging.Brushes](../../lineargradientbrush)
* assemblea [Aspose.Imaging](../../../)

---

## LinearGradientBrush(PointF, PointF, Color, Color) {#constructor_2}

Inizializza una nuova istanza di[`LinearGradientBrush`](../../lineargradientbrush) classe con i punti e i colori specificati.

```csharp
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | PointF | UN[`PointF`](../../../aspose.imaging/pointf) struttura che rappresenta il punto di partenza del gradiente lineare. |
| point2 | PointF | UN[`PointF`](../../../aspose.imaging/pointf) struttura che rappresenta il punto finale del gradiente lineare. |
| color1 | Color | UN[`Color`](../../../aspose.imaging/color) struttura che rappresenta il colore iniziale del gradiente lineare. |
| color2 | Color | UN[`Color`](../../../aspose.imaging/color) struttura che rappresenta il colore finale del gradiente lineare. |

### Guarda anche

* struct [PointF](../../../aspose.imaging/pointf)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* spazio dei nomi [Aspose.Imaging.Brushes](../../lineargradientbrush)
* assemblea [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Rectangle, Color, Color, float) {#constructor_3}

Inizializza una nuova istanza di[`LinearGradientBrush`](../../lineargradientbrush) classe basata su un rettangolo, colori iniziali e finali e un angolo di orientamento.

```csharp
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | UN[`RectangleF`](../../../aspose.imaging/rectanglef) struttura che specifica i limiti del gradiente lineare. |
| color1 | Color | UN[`Color`](../../../aspose.imaging/color) struttura che rappresenta il colore iniziale per il gradiente. |
| color2 | Color | UN[`Color`](../../../aspose.imaging/color) struttura che rappresenta il colore finale per il gradiente. |
| angle | Single | L'angolo, misurato in gradi in senso orario dall'asse x, della linea di orientamento del gradiente. |

### Guarda anche

* struct [Rectangle](../../../aspose.imaging/rectangle)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* spazio dei nomi [Aspose.Imaging.Brushes](../../lineargradientbrush)
* assemblea [Aspose.Imaging](../../../)

---

## LinearGradientBrush(RectangleF, Color, Color, float) {#constructor_5}

Inizializza una nuova istanza di[`LinearGradientBrush`](../../lineargradientbrush) classe basata su un rettangolo, colori iniziali e finali e un angolo di orientamento.

```csharp
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | RectangleF | UN[`RectangleF`](../../../aspose.imaging/rectanglef) struttura che specifica i limiti del gradiente lineare. |
| color1 | Color | UN[`Color`](../../../aspose.imaging/color) struttura che rappresenta il colore iniziale per il gradiente. |
| color2 | Color | UN[`Color`](../../../aspose.imaging/color) struttura che rappresenta il colore finale per il gradiente. |
| angle | Single | L'angolo, misurato in gradi in senso orario dall'asse x, della linea di orientamento del gradiente. |

### Guarda anche

* struct [RectangleF](../../../aspose.imaging/rectanglef)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* spazio dei nomi [Aspose.Imaging.Brushes](../../lineargradientbrush)
* assemblea [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Rectangle, Color, Color, float, bool) {#constructor_4}

Inizializza una nuova istanza di[`LinearGradientBrush`](../../lineargradientbrush) classe basata su un rettangolo, colori iniziali e finali e un angolo di orientamento.

```csharp
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, 
    bool isAngleScalable)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | UN[`RectangleF`](../../../aspose.imaging/rectanglef) struttura che specifica i limiti del gradiente lineare. |
| color1 | Color | UN[`Color`](../../../aspose.imaging/color) struttura che rappresenta il colore iniziale per il gradiente. |
| color2 | Color | UN[`Color`](../../../aspose.imaging/color) struttura che rappresenta il colore finale per il gradiente. |
| angle | Single | L'angolo, misurato in gradi in senso orario dall'asse x, della linea di orientamento del gradiente. |
| isAngleScalable | Boolean | se impostato su`VERO` l'angolo viene modificato durante le trasformazioni con questo[`LinearGradientBrush`](../../lineargradientbrush). |

### Guarda anche

* struct [Rectangle](../../../aspose.imaging/rectangle)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* spazio dei nomi [Aspose.Imaging.Brushes](../../lineargradientbrush)
* assemblea [Aspose.Imaging](../../../)

---

## LinearGradientBrush(RectangleF, Color, Color, float, bool) {#constructor_6}

Inizializza una nuova istanza di[`LinearGradientBrush`](../../lineargradientbrush) classe basata su un rettangolo, colori iniziali e finali e un angolo di orientamento.

```csharp
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, 
    bool isAngleScalable)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | RectangleF | UN[`RectangleF`](../../../aspose.imaging/rectanglef) struttura che specifica i limiti del gradiente lineare. |
| color1 | Color | UN[`Color`](../../../aspose.imaging/color) struttura che rappresenta il colore iniziale per il gradiente. |
| color2 | Color | UN[`Color`](../../../aspose.imaging/color) struttura che rappresenta il colore finale per il gradiente. |
| angle | Single | L'angolo, misurato in gradi in senso orario dall'asse x, della linea di orientamento del gradiente. |
| isAngleScalable | Boolean | se impostato su`VERO` l'angolo viene modificato durante le trasformazioni con questo[`LinearGradientBrush`](../../lineargradientbrush). |

### Guarda anche

* struct [RectangleF](../../../aspose.imaging/rectanglef)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* spazio dei nomi [Aspose.Imaging.Brushes](../../lineargradientbrush)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
