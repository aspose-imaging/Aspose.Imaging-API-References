---
title: Graphics
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Rappresenta la grafica in base al motore grafico utilizzato nellassieme corrente.
type: docs
weight: 9360
url: /it/aspose.imaging/graphics/
---
## Graphics class

Rappresenta la grafica in base al motore grafico utilizzato nell'assieme corrente.

```csharp
public sealed class Graphics
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Graphics](graphics)(Image) | Inizializza una nuova istanza di[`Graphics`](../graphics) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Clip](../../aspose.imaging/graphics/clip) { get; set; } | Ottiene o imposta la regione della clip. |
| [CompositingQuality](../../aspose.imaging/graphics/compositingquality) { get; set; } | Ottiene o imposta la qualità della composizione. |
| [DpiX](../../aspose.imaging/graphics/dpix) { get; } | Ottiene la risoluzione orizzontale di questo Aspose.Imaging.Graphics. |
| [DpiY](../../aspose.imaging/graphics/dpiy) { get; } | Ottiene la risoluzione verticale di questo Aspose.Imaging.Graphics. |
| [Image](../../aspose.imaging/graphics/image) { get; } | Ottiene l'immagine. |
| [InterpolationMode](../../aspose.imaging/graphics/interpolationmode) { get; set; } | Ottiene o imposta la modalità di interpolazione. |
| [IsInBeginUpdateCall](../../aspose.imaging/graphics/isinbeginupdatecall) { get; } | Ottiene un valore che indica se la grafica è nello stato di chiamata BeginUpdate. |
| [PageScale](../../aspose.imaging/graphics/pagescale) { get; set; } | Ottiene o imposta il ridimensionamento tra le unità mondiali e le unità di pagina per questo Aspose.Imaging.Graphics. |
| [PageUnit](../../aspose.imaging/graphics/pageunit) { get; set; } | Ottiene o imposta l'unità di misura utilizzata per le coordinate della pagina in questo Aspose.Imaging.Graphics. |
| [SmoothingMode](../../aspose.imaging/graphics/smoothingmode) { get; set; } | Ottiene o imposta la modalità di smoothing. |
| [TextRenderingHint](../../aspose.imaging/graphics/textrenderinghint) { get; set; } | Ottiene o imposta il suggerimento per il rendering del testo. |
| [Transform](../../aspose.imaging/graphics/transform) { get; set; } | Ottiene o imposta una copia della trasformazione del mondo geometrico per questo[`Graphics`](../graphics) . |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [BeginUpdate](../../aspose.imaging/graphics/beginupdate)() | Avvia la memorizzazione nella cache delle seguenti operazioni grafiche. Gli effetti grafici applicati successivamente non verranno applicati immediatamente, ma EndUpdate causerà l'applicazione di tutti gli effetti contemporaneamente. |
| [Clear](../../aspose.imaging/graphics/clear)(Color) | Cancella la superficie grafica utilizzando il colore specificato. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc)(Pen, Rectangle, float, float) | Disegna un arco che rappresenta una porzione di un'ellisse specificata da a[`Rectangle`](../rectangle) struttura. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc_1)(Pen, RectangleF, float, float) | Disegna un arco che rappresenta una porzione di un'ellisse specificata da a[`RectangleF`](../rectanglef) struttura. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc_3)(Pen, float, float, float, float, float, float) | Disegna un arco che rappresenta una porzione di un'ellisse specificata da una coppia di coordinate, una larghezza e un'altezza. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc_2)(Pen, int, int, int, int, int, int) | Disegna un arco che rappresenta una porzione di un'ellisse specificata da una coppia di coordinate, una larghezza e un'altezza. |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier#drawbezier)(Pen, Point, Point, Point, Point) | Disegna una spline Bézier definita da quattro[`Point`](../point) strutture. |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | Disegna una spline Bézier definita da quattro[`PointF`](../pointf) strutture. |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | Disegna una spline di Bézier definita da quattro coppie ordinate di coordinate che rappresentano punti. |
| [DrawBeziers](../../aspose.imaging/graphics/drawbeziers#drawbeziers)(Pen, PointF[]) | Disegna una serie di spline di Bézier da un array di[`PointF`](../pointf) strutture. |
| [DrawBeziers](../../aspose.imaging/graphics/drawbeziers#drawbeziers_1)(Pen, Point[]) | Disegna una serie di spline di Bézier da un array di[`Point`](../point) strutture. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve)(Pen, PointF[]) | Disegna una spline cardinale chiusa definita da un array di[`PointF`](../pointf) strutture. Questo metodo utilizza una tensione predefinita di 0,5 eAlternate modalità riempimento. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve_2)(Pen, Point[]) | Disegna una spline cardinale chiusa definita da un array di[`Point`](../point) strutture. Questo metodo utilizza una tensione predefinita di 0,5 eAlternate modalità riempimento. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve_1)(Pen, PointF[], float) | Disegna una spline cardinale chiusa definita da un array di[`PointF`](../pointf) strutture che utilizzano una tensione specificata. Questo metodo utilizza un valore predefinitoAlternate modalità riempimento. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve_3)(Pen, Point[], float) | Disegna una spline cardinale chiusa definita da un array di[`Point`](../point) strutture che utilizzano una tensione specificata. Questo metodo utilizza un valore predefinitoAlternate modalità riempimento. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve)(Pen, PointF[]) | Disegna una spline cardinale attraverso una matrice specificata di[`PointF`](../pointf) strutture. Questo metodo utilizza una tensione predefinita di 0,5. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_4)(Pen, Point[]) | Disegna una spline cardinale attraverso una matrice specificata di[`Point`](../point) strutture. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_3)(Pen, PointF[], float) | Disegna una spline cardinale attraverso una matrice specificata di[`PointF`](../pointf) strutture che utilizzano una tensione specificata. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_6)(Pen, Point[], float) | Disegna una spline cardinale attraverso una matrice specificata di[`Point`](../point) strutture che utilizzano una tensione specificata. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_1)(Pen, PointF[], int, int) | Disegna una spline cardinale attraverso una matrice specificata di[`PointF`](../pointf) strutture. Il disegno inizia sfalsato dall'inizio dell'array. Questo metodo utilizza una tensione predefinita di 0,5. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_2)(Pen, PointF[], int, int, float) | Disegna una spline cardinale attraverso una matrice specificata di[`PointF`](../pointf)strutture che utilizzano una tensione specificata. Il disegno inizia sfalsato dall'inizio dell'array. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_5)(Pen, Point[], int, int, float) | Disegna una spline cardinale attraverso una matrice specificata di[`Point`](../point) strutture che utilizzano una tensione specificata. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse)(Pen, Rectangle) | Disegna un'ellisse specificata da un limite[`Rectangle`](../rectangle) struttura. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse_1)(Pen, RectangleF) | Disegna un'ellisse definita da un limite[`RectangleF`](../rectanglef) . |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse_3)(Pen, float, float, float, float) | Disegna un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, un'altezza e una larghezza. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse_2)(Pen, int, int, int, int) | Disegna un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, un'altezza e una larghezza. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage)(Image, Point) | Disegna l'oggetto specificato[`Image`](./image) , utilizzando la sua dimensione fisica originale, nella posizione specificata. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_1)(Image, PointF) | Disegna l'oggetto specificato[`Image`](./image) , utilizzando la sua dimensione fisica originale, nella posizione specificata. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_2)(Image, PointF[]) | Disegna la parte specificata dell'oggetto specificato*image* nella posizione specificata e con la dimensione specificata. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_6)(Image, Point[]) | Disegna la parte specificata dell'oggetto specificato*image* nella posizione specificata e con la dimensione specificata. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_10)(Image, Rectangle) | Disegna l'oggetto specificato[`Image`](./image) nella posizione specificata e con la dimensione specificata. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_15)(Image, RectangleF) | Disegna l'oggetto specificato[`Image`](./image) nella posizione specificata e con la dimensione specificata. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_22)(Image, float, float) | Disegna l'oggetto specificato[`Image`](./image) , utilizzando la sua dimensione fisica originale, nella posizione specificata. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_20)(Image, int, int) | Disegna l'immagine specificata, utilizzando la sua dimensione fisica originale, nella posizione specificata da una coppia di coordinate. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_3)(Image, PointF[], RectangleF) | Disegna la parte specificata dell'oggetto specificato*image* nella posizione specificata e con la dimensione specificata. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_7)(Image, Point[], Rectangle) | Disegna la parte specificata dell'oggetto specificato*image* nella posizione specificata e con la dimensione specificata. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_11)(Image, Rectangle, GraphicsUnit) | Disegna l'oggetto specificato[`Image`](./image) nella posizione specificata e con la dimensione specificata. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_16)(Image, RectangleF, GraphicsUnit) | Disegna l'oggetto specificato[`Image`](./image) nella posizione specificata e con la dimensione specificata. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | Disegna la parte specificata dell'oggetto specificato*image* nella posizione specificata e con la dimensione specificata. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | Disegna la parte specificata dell'oggetto specificato*image* nella posizione specificata e con la dimensione specificata. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | Disegna l'oggetto specificato[`Image`](./image) nella posizione specificata e con la dimensione specificata. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | Disegna l'oggetto specificato[`Image`](./image) nella posizione specificata e con la dimensione specificata. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | Disegna l'oggetto specificato[`Image`](./image) nella posizione specificata e con la dimensione specificata. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | Disegna l'oggetto specificato[`Image`](./image) nella posizione specificata e con la dimensione specificata. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_23)(Image, float, float, float, float) | Disegna l'oggetto specificato[`Image`](./image) nella posizione specificata e con la dimensione specificata. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_21)(Image, int, int, int, int) | Disegna l'oggetto specificato[`Image`](./image) nella posizione specificata e con la dimensione specificata. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | Disegna la parte specificata dell'oggetto specificato*image* nella posizione specificata e con la dimensione specificata. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | Disegna la parte specificata dell'oggetto specificato*image* nella posizione specificata e con la dimensione specificata. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | Disegna l'oggetto specificato[`Image`](./image) nella posizione specificata e con la dimensione specificata. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | Disegna l'oggetto specificato[`Image`](./image) nella posizione specificata e con la dimensione specificata. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled)(Image, Point) | Disegna un'immagine specificata utilizzando la sua dimensione fisica originale in una posizione specificata. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled_1)(Image, Rectangle) | Disegna un'immagine specificata utilizzando la sua dimensione fisica originale in una posizione specificata. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled_2)(Image, int, int) | Disegna l'immagine specificata utilizzando la sua dimensione fisica originale nella posizione specificata da una coppia di coordinate. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled_3)(Image, int, int, int, int) | Disegna un'immagine specificata utilizzando la sua dimensione fisica originale in una posizione specificata. |
| [DrawImageUnscaledAndClipped](../../aspose.imaging/graphics/drawimageunscaledandclipped)(Image, Rectangle) | Disegna l'immagine specificata senza ridimensionarla e la ritaglia, se necessario, per adattarla al rettangolo specificato. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline)(Pen, Point, Point) | Disegna una linea che collega due[`Point`](../point) strutture. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline_1)(Pen, PointF, PointF) | Disegna una linea che collega due[`PointF`](../pointf) strutture. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline_3)(Pen, float, float, float, float) | Disegna una linea che collega i due punti specificati dalle coppie di coordinate. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline_2)(Pen, int, int, int, int) | Disegna una linea che collega i due punti specificati dalle coppie di coordinate. |
| [DrawLines](../../aspose.imaging/graphics/drawlines#drawlines)(Pen, PointF[]) | Disegna una serie di segmenti di linea che collegano una matrice di[`PointF`](../pointf) strutture. |
| [DrawLines](../../aspose.imaging/graphics/drawlines#drawlines_1)(Pen, Point[]) | Disegna una serie di segmenti di linea che collegano una matrice di[`Point`](../point) strutture. |
| [DrawPath](../../aspose.imaging/graphics/drawpath)(Pen, GraphicsPath) | Disegna a[`GraphicsPath`](../graphicspath) . |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie)(Pen, Rectangle, float, float) | Disegna una forma a torta definita da un'ellisse specificata da a[`Rectangle`](../rectangle) struttura e due linee radiali. |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie_1)(Pen, RectangleF, float, float) | Disegna una forma a torta definita da un'ellisse specificata da a[`RectangleF`](../rectanglef) struttura e due linee radiali. |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie_3)(Pen, float, float, float, float, float, float) | Disegna una forma a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali. |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie_2)(Pen, int, int, int, int, int, int) | Disegna una forma a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali. |
| [DrawPolygon](../../aspose.imaging/graphics/drawpolygon#drawpolygon)(Pen, PointF[]) | Disegna un poligono definito da un array di[`PointF`](../pointf) strutture. |
| [DrawPolygon](../../aspose.imaging/graphics/drawpolygon#drawpolygon_1)(Pen, Point[]) | Disegna un poligono definito da un array di[`Point`](../point) strutture. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle)(Pen, Rectangle) | Disegna un rettangolo specificato da a[`Rectangle`](../rectangle) struttura. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle_1)(Pen, RectangleF) | Disegna un rettangolo specificato da a[`RectangleF`](../rectanglef) struttura. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle_3)(Pen, float, float, float, float) | Disegna un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle_2)(Pen, int, int, int, int) | Disegna un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza. |
| [DrawRectangles](../../aspose.imaging/graphics/drawrectangles#drawrectangles)(Pen, RectangleF[]) | Disegna una serie di rettangoli specificati da[`RectangleF`](../rectanglef) strutture. |
| [DrawRectangles](../../aspose.imaging/graphics/drawrectangles#drawrectangles_1)(Pen, Rectangle[]) | Disegna una serie di rettangoli specificati da[`Rectangle`](../rectangle) strutture. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring)(string, Font, Brush, PointF) | Disegna la stringa di testo specificata nella posizione specificata con l'oggetto specificato[`Brush`](../brush) e[`Font`](../font) oggetti. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_2)(string, Font, Brush, RectangleF) | Disegna la stringa di testo specificata nel rettangolo specificato con l'oggetto specificato[`Brush`](../brush) e[`Font`](../font) oggetti. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_4)(string, Font, Brush, float, float) | Disegna la stringa di testo specificata nella posizione specificata con l'oggetto specificato[`Brush`](../brush) e[`Font`](../font) oggetti. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_1)(string, Font, Brush, PointF, StringFormat) | Disegna la stringa di testo specificata nella posizione specificata con l'oggetto specificato[`Brush`](../brush) e[`Font`](../font) oggetti che utilizzano gli attributi di formattazione dell'oggetto specificato[`StringFormat`](../stringformat) . |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | Disegna la stringa di testo specificata nel rettangolo specificato con l'oggetto specificato[`Brush`](../brush) e[`Font`](../font) oggetti che utilizzano gli attributi di formattazione dell'oggetto specificato[`StringFormat`](../stringformat) . |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_5)(string, Font, Brush, float, float, StringFormat) | Disegna la stringa di testo specificata nella posizione specificata con l'oggetto specificato[`Brush`](../brush) e[`Font`](../font) oggetti che utilizzano gli attributi di formattazione dell'oggetto specificato[`StringFormat`](../stringformat) . |
| [EndUpdate](../../aspose.imaging/graphics/endupdate)() | Termina la memorizzazione nella cache delle operazioni grafiche avviate dopo la chiamata di BeginUpdate. Le operazioni grafiche precedenti verranno applicate contemporaneamente quando si chiama questo metodo. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve)(Brush, PointF[]) | Riempie l'interno di una curva spline cardinale chiusa definita da un array di[`PointF`](../pointf) strutture. Questo metodo utilizza una tensione predefinita di 0,5 eAlternate modalità riempimento. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_3)(Brush, Point[]) | Riempie l'interno di una curva spline cardinale chiusa definita da un array di[`Point`](../point) strutture. Questo metodo utilizza una tensione predefinita di 0,5 eAlternate modalità riempimento. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_1)(Brush, PointF[], FillMode) | Riempie l'interno di una curva spline cardinale chiusa definita da un array di[`PointF`](../pointf) strutture utilizzando la modalità di riempimento specificata. Questo metodo utilizza una tensione predefinita di 0,5. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_4)(Brush, Point[], FillMode) | Riempie l'interno di una curva spline cardinale chiusa definita da un array di[`Point`](../point) strutture utilizzando la modalità di riempimento specificata. Questo metodo utilizza una tensione predefinita di 0,5. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | Riempie l'interno di una curva spline cardinale chiusa definita da un array di[`PointF`](../pointf) strutture che utilizzano la modalità di riempimento e la tensione specificate. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_5)(Brush, Point[], FillMode, float) | Riempie l'interno di una curva spline cardinale chiusa definita da un array di[`Point`](../point) strutture che utilizzano la modalità di riempimento e la tensione specificate. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse)(Brush, Rectangle) | Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da a[`Rectangle`](../rectangle) struttura. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse_1)(Brush, RectangleF) | Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da a[`RectangleF`](../rectanglef) struttura. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse_3)(Brush, float, float, float, float) | Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, una larghezza e un'altezza. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse_2)(Brush, int, int, int, int) | Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, una larghezza e un'altezza. |
| [FillPath](../../aspose.imaging/graphics/fillpath)(Brush, GraphicsPath) | Riempie l'interno di a[`GraphicsPath`](../graphicspath) . |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie)(Brush, Rectangle, float, float) | Riempie l'interno di una sezione di torta definita da un'ellisse specificata da a[`RectangleF`](../rectanglef) struttura e due linee radiali. |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie_1)(Brush, RectangleF, float, float) | Riempie l'interno di una sezione di torta definita da un'ellisse specificata da a[`RectangleF`](../rectanglef) struttura e due linee radiali. |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie_3)(Brush, float, float, float, float, float, float) | Riempie l'interno di una sezione della torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali. |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie_2)(Brush, int, int, int, int, int, int) | Riempie l'interno di una sezione della torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali. |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon)(Brush, PointF[]) | Riempie l'interno di un poligono definito da un array di punti specificato da[`PointF`](../pointf) strutture eAlternate . |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon_2)(Brush, Point[]) | Riempie l'interno di un poligono definito da un array di punti specificato da[`Point`](../point) strutture eAlternate . |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon_1)(Brush, PointF[], FillMode) | Riempie l'interno di un poligono definito da un array di punti specificato da[`PointF`](../pointf) strutture che utilizzano la modalità di riempimento specificata. |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon_3)(Brush, Point[], FillMode) | Riempie l'interno di un poligono definito da un array di punti specificato da[`Point`](../point) strutture che utilizzano la modalità di riempimento specificata. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle)(Brush, Rectangle) | Riempie l'interno di un rettangolo specificato da a[`Rectangle`](../rectangle) struttura. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle_1)(Brush, RectangleF) | Riempie l'interno di un rettangolo specificato da a[`RectangleF`](../rectanglef) struttura. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle_3)(Brush, float, float, float, float) | Riempie l'interno di un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle_2)(Brush, int, int, int, int) | Riempie l'interno di un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza. |
| [FillRectangles](../../aspose.imaging/graphics/fillrectangles#fillrectangles)(Brush, RectangleF[]) | Riempie gli interni di una serie di rettangoli specificati da[`RectangleF`](../rectanglef) strutture. |
| [FillRectangles](../../aspose.imaging/graphics/fillrectangles#fillrectangles_1)(Brush, Rectangle[]) | Riempie gli interni di una serie di rettangoli specificati da[`Rectangle`](../rectangle) strutture. |
| [FillRegion](../../aspose.imaging/graphics/fillregion)(Brush, Region) | Riempie l'interno di a[`Region`](../region) . |
| [MeasureString](../../aspose.imaging/graphics/measurestring)(string, Font, SizeF, StringFormat) | Misura la stringa di testo specificata con i parametri specificati |
| [MultiplyTransform](../../aspose.imaging/graphics/multiplytransform#multiplytransform)(Matrix) | Moltiplica il[`Matrix`](../matrix) che rappresenta la trasformata geometrica locale di questo[`Graphics`](../graphics) dal specificato[`Matrix`](../matrix) anteponendo quello specificato[`Matrix`](../matrix) . |
| [MultiplyTransform](../../aspose.imaging/graphics/multiplytransform#multiplytransform_1)(Matrix, MatrixOrder) | Moltiplica il[`Matrix`](../matrix) che rappresenta la trasformata geometrica locale di questo[`Graphics`](../graphics) dal specificato[`Matrix`](../matrix) nell'ordine specificato. |
| [ResetTransform](../../aspose.imaging/graphics/resettransform)() | Reimposta il[`Transform`](./transform) proprietà su identità. |
| [RotateTransform](../../aspose.imaging/graphics/rotatetransform#rotatetransform)(float) | Ruota la trasformazione geometrica locale della quantità specificata. Questo metodo antepone la rotazione alla trasformazione. |
| [RotateTransform](../../aspose.imaging/graphics/rotatetransform#rotatetransform_1)(float, MatrixOrder) | Ruota la trasformazione geometrica locale della quantità specificata nell'ordine specificato. |
| [ScaleTransform](../../aspose.imaging/graphics/scaletransform#scaletransform)(float, float) | Ridimensiona la trasformazione geometrica locale degli importi specificati. Questo metodo antepone la matrice di ridimensionamento alla trasformazione. |
| [ScaleTransform](../../aspose.imaging/graphics/scaletransform#scaletransform_1)(float, float, MatrixOrder) | Ridimensiona la trasformazione geometrica locale degli importi specificati nell'ordine specificato. |
| [TranslateTransform](../../aspose.imaging/graphics/translatetransform#translatetransform)(float, float) | Converte la trasformazione geometrica locale in base alle dimensioni specificate. Questo metodo antepone la traduzione alla trasformazione. |
| [TranslateTransform](../../aspose.imaging/graphics/translatetransform#translatetransform_1)(float, float, MatrixOrder) | Converte la trasformazione geometrica locale in base alle dimensioni specificate nell'ordine specificato. |

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

* spazio dei nomi [Aspose.Imaging](../../aspose.imaging)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
