---
title: Graphics
second_title: Aspose.Imaging für .NET-API-Referenz
description: Stellt die Grafiken gemäß der Grafik-Engine dar die in der aktuellen Assembly verwendet wird.
type: docs
weight: 9360
url: /de/net/aspose.imaging/graphics/
---
## Graphics class

Stellt die Grafiken gemäß der Grafik-Engine dar, die in der aktuellen Assembly verwendet wird.

```csharp
public sealed class Graphics
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Graphics](graphics)(Image) | Initialisiert eine neue Instanz von[`Graphics`](../graphics) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Clip](../../aspose.imaging/graphics/clip) { get; set; } | Ruft den Clip-Bereich ab oder legt ihn fest. |
| [CompositingQuality](../../aspose.imaging/graphics/compositingquality) { get; set; } | Ruft die Compositing-Qualität ab oder legt sie fest. |
| [DpiX](../../aspose.imaging/graphics/dpix) { get; } | Ruft die horizontale Auflösung dieser Aspose.Imaging.Graphics ab. |
| [DpiY](../../aspose.imaging/graphics/dpiy) { get; } | Ruft die vertikale Auflösung dieser Aspose.Imaging.Graphics ab. |
| [Image](../../aspose.imaging/graphics/image) { get; } | Ruft das Bild ab. |
| [InterpolationMode](../../aspose.imaging/graphics/interpolationmode) { get; set; } | Ruft den Interpolationsmodus ab oder legt ihn fest. |
| [IsInBeginUpdateCall](../../aspose.imaging/graphics/isinbeginupdatecall) { get; } | Ruft einen Wert ab, der angibt, ob sich Grafiken im BeginUpdate-Aufrufstatus befinden. |
| [PageScale](../../aspose.imaging/graphics/pagescale) { get; set; } | Ruft die Skalierung zwischen Welteinheiten und Seiteneinheiten für diese Aspose.Imaging.Graphics ab oder legt sie fest. |
| [PageUnit](../../aspose.imaging/graphics/pageunit) { get; set; } | Ruft die Maßeinheit für Seitenkoordinaten in diesem Aspose.Imaging.Graphics ab oder legt sie fest. |
| [SmoothingMode](../../aspose.imaging/graphics/smoothingmode) { get; set; } | Ruft den Glättungsmodus ab oder legt ihn fest. |
| [TextRenderingHint](../../aspose.imaging/graphics/textrenderinghint) { get; set; } | Ruft den Textwiedergabehinweis ab oder legt ihn fest. |
| [Transform](../../aspose.imaging/graphics/transform) { get; set; } | Holt oder setzt eine Kopie der geometrischen Welttransformation dafür[`Graphics`](../graphics) . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [BeginUpdate](../../aspose.imaging/graphics/beginupdate)() | Startet das Caching der folgenden Grafikoperationen. Die danach angewendeten Grafikeffekte werden nicht sofort angewendet, sondern das EndUpdate bewirkt, dass alle Effekte auf einmal angewendet werden. |
| [Clear](../../aspose.imaging/graphics/clear)(Color) | Löscht die Grafikoberfläche mit der angegebenen Farbe. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc)(Pen, Rectangle, float, float) | Zeichnet einen Bogen, der einen Teil einer durch a angegebenen Ellipse darstellt[`Rectangle`](../rectangle) Struktur. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc_1)(Pen, RectangleF, float, float) | Zeichnet einen Bogen, der einen Teil einer durch a angegebenen Ellipse darstellt[`RectangleF`](../rectanglef) Struktur. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc_3)(Pen, float, float, float, float, float, float) | Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben wird. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc_2)(Pen, int, int, int, int, int, int) | Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben wird. |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier#drawbezier)(Pen, Point, Point, Point, Point) | Zeichnet einen durch vier definierten Bézier-Spline[`Point`](../point) Strukturen. |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | Zeichnet einen durch vier definierten Bézier-Spline[`PointF`](../pointf) Strukturen. |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | Zeichnet einen Bézier-Spline, der durch vier geordnete Koordinatenpaare definiert ist, die Punkte darstellen. |
| [DrawBeziers](../../aspose.imaging/graphics/drawbeziers#drawbeziers)(Pen, PointF[]) | Zeichnet eine Reihe von Bézier-Splines aus einem Array von[`PointF`](../pointf) Strukturen. |
| [DrawBeziers](../../aspose.imaging/graphics/drawbeziers#drawbeziers_1)(Pen, Point[]) | Zeichnet eine Reihe von Bézier-Splines aus einem Array von[`Point`](../point) Strukturen. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve)(Pen, PointF[]) | Zeichnet einen geschlossenen kardinalen Spline, der durch ein Array von definiert ist[`PointF`](../pointf) Strukturen. Diese Methode verwendet eine Standardspannung von 0,5 undAlternate Füllmodus. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve_2)(Pen, Point[]) | Zeichnet einen geschlossenen kardinalen Spline, der durch ein Array von definiert ist[`Point`](../point) Strukturen. Diese Methode verwendet eine Standardspannung von 0,5 undAlternate Füllmodus. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve_1)(Pen, PointF[], float) | Zeichnet einen geschlossenen kardinalen Spline, der durch ein Array von definiert ist[`PointF`](../pointf) Strukturen mit einer bestimmten Spannung. Diese Methode verwendet einen StandardwertAlternate Füllmodus. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve_3)(Pen, Point[], float) | Zeichnet einen geschlossenen kardinalen Spline, der durch ein Array von definiert ist[`Point`](../point) Strukturen mit einer bestimmten Spannung. Diese Methode verwendet einen StandardwertAlternate Füllmodus. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve)(Pen, PointF[]) | Zeichnet einen kardinalen Spline durch ein angegebenes Array von[`PointF`](../pointf) Strukturen. Diese Methode verwendet eine Standardspannung von 0,5. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_4)(Pen, Point[]) | Zeichnet einen kardinalen Spline durch ein angegebenes Array von[`Point`](../point) Strukturen. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_3)(Pen, PointF[], float) | Zeichnet einen kardinalen Spline durch ein angegebenes Array von[`PointF`](../pointf) Strukturen mit einer bestimmten Spannung. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_6)(Pen, Point[], float) | Zeichnet einen kardinalen Spline durch ein angegebenes Array von[`Point`](../point) Strukturen mit einer bestimmten Spannung. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_1)(Pen, PointF[], int, int) | Zeichnet einen kardinalen Spline durch ein angegebenes Array von[`PointF`](../pointf) Strukturen. Die Zeichnung beginnt versetzt vom Anfang des Arrays. Diese Methode verwendet eine Standardspannung von 0,5. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_2)(Pen, PointF[], int, int, float) | Zeichnet einen kardinalen Spline durch ein angegebenes Array von[`PointF`](../pointf)Strukturen mit einer bestimmten Spannung. Die Zeichnung beginnt versetzt vom Anfang des Arrays. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_5)(Pen, Point[], int, int, float) | Zeichnet einen kardinalen Spline durch ein angegebenes Array von[`Point`](../point) Strukturen mit einer bestimmten Spannung. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse)(Pen, Rectangle) | Zeichnet eine durch eine Begrenzung angegebene Ellipse[`Rectangle`](../rectangle) Struktur. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse_1)(Pen, RectangleF) | Zeichnet eine durch eine Begrenzung definierte Ellipse[`RectangleF`](../rectanglef) . |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse_3)(Pen, float, float, float, float) | Zeichnet eine Ellipse, die durch ein Begrenzungsrechteck definiert ist, das durch ein Koordinatenpaar, eine Höhe und eine Breite angegeben ist. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse_2)(Pen, int, int, int, int) | Zeichnet eine Ellipse, die durch ein Begrenzungsrechteck definiert ist, das durch ein Koordinatenpaar, eine Höhe und eine Breite angegeben ist. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage)(Image, Point) | Zeichnet das angegebene[`Image`](./image) , unter Verwendung seiner ursprünglichen physischen Größe, an der angegebenen Position. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_1)(Image, PointF) | Zeichnet das angegebene[`Image`](./image) , unter Verwendung seiner ursprünglichen physischen Größe, an der angegebenen Position. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_2)(Image, PointF[]) | Zeichnet den angegebenen Teil des angegebenen*image* am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_6)(Image, Point[]) | Zeichnet den angegebenen Teil des angegebenen*image* am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_10)(Image, Rectangle) | Zeichnet das angegebene[`Image`](./image) am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_15)(Image, RectangleF) | Zeichnet das angegebene[`Image`](./image) am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_22)(Image, float, float) | Zeichnet das angegebene[`Image`](./image) , unter Verwendung seiner ursprünglichen physischen Größe, an der angegebenen Position. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_20)(Image, int, int) | Zeichnet das angegebene Bild unter Verwendung seiner ursprünglichen physischen Größe an der durch ein Koordinatenpaar angegebenen Position. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_3)(Image, PointF[], RectangleF) | Zeichnet den angegebenen Teil des angegebenen*image* am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_7)(Image, Point[], Rectangle) | Zeichnet den angegebenen Teil des angegebenen*image* am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_11)(Image, Rectangle, GraphicsUnit) | Zeichnet das angegebene[`Image`](./image) am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_16)(Image, RectangleF, GraphicsUnit) | Zeichnet das angegebene[`Image`](./image) am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | Zeichnet den angegebenen Teil des angegebenen*image* am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | Zeichnet den angegebenen Teil des angegebenen*image* am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | Zeichnet das angegebene[`Image`](./image) am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | Zeichnet das angegebene[`Image`](./image) am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | Zeichnet das angegebene[`Image`](./image) am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | Zeichnet das angegebene[`Image`](./image) am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_23)(Image, float, float, float, float) | Zeichnet das angegebene[`Image`](./image) am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_21)(Image, int, int, int, int) | Zeichnet das angegebene[`Image`](./image) am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | Zeichnet den angegebenen Teil des angegebenen*image* am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | Zeichnet den angegebenen Teil des angegebenen*image* am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | Zeichnet das angegebene[`Image`](./image) am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | Zeichnet das angegebene[`Image`](./image) am angegebenen Ort und mit der angegebenen Größe. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled)(Image, Point) | Zeichnet ein bestimmtes Bild unter Verwendung seiner ursprünglichen physischen Größe an einer bestimmten Position. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled_1)(Image, Rectangle) | Zeichnet ein bestimmtes Bild unter Verwendung seiner ursprünglichen physischen Größe an einer bestimmten Position. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled_2)(Image, int, int) | Zeichnet das angegebene Bild in seiner ursprünglichen physischen Größe an der durch ein Koordinatenpaar angegebenen Position. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled_3)(Image, int, int, int, int) | Zeichnet ein bestimmtes Bild unter Verwendung seiner ursprünglichen physischen Größe an einer bestimmten Position. |
| [DrawImageUnscaledAndClipped](../../aspose.imaging/graphics/drawimageunscaledandclipped)(Image, Rectangle) | Zeichnet das angegebene Bild ohne Skalierung und schneidet es ggf. so zu, dass es in das angegebene Rechteck passt. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline)(Pen, Point, Point) | Zeichnet eine Linie, die zwei verbindet[`Point`](../point) Strukturen. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline_1)(Pen, PointF, PointF) | Zeichnet eine Linie, die zwei verbindet[`PointF`](../pointf) Strukturen. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline_3)(Pen, float, float, float, float) | Zeichnet eine Linie, die die beiden durch die Koordinatenpaare angegebenen Punkte verbindet. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline_2)(Pen, int, int, int, int) | Zeichnet eine Linie, die die beiden durch die Koordinatenpaare angegebenen Punkte verbindet. |
| [DrawLines](../../aspose.imaging/graphics/drawlines#drawlines)(Pen, PointF[]) | Zeichnet eine Reihe von Liniensegmenten, die ein Array von verbinden[`PointF`](../pointf) Strukturen. |
| [DrawLines](../../aspose.imaging/graphics/drawlines#drawlines_1)(Pen, Point[]) | Zeichnet eine Reihe von Liniensegmenten, die ein Array von verbinden[`Point`](../point) Strukturen. |
| [DrawPath](../../aspose.imaging/graphics/drawpath)(Pen, GraphicsPath) | zeichnet a[`GraphicsPath`](../graphicspath) . |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie)(Pen, Rectangle, float, float) | Zeichnet eine Tortenform, die durch eine durch a angegebene Ellipse definiert ist[`Rectangle`](../rectangle) Struktur und zwei radiale Linien. |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie_1)(Pen, RectangleF, float, float) | Zeichnet eine Tortenform, die durch eine durch a angegebene Ellipse definiert ist[`RectangleF`](../rectanglef) Struktur und zwei radiale Linien. |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie_3)(Pen, float, float, float, float, float, float) | Zeichnet eine Tortenform, die durch eine Ellipse definiert ist, die durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei radiale Linien angegeben ist. |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie_2)(Pen, int, int, int, int, int, int) | Zeichnet eine Tortenform, die durch eine Ellipse definiert ist, die durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei radiale Linien angegeben ist. |
| [DrawPolygon](../../aspose.imaging/graphics/drawpolygon#drawpolygon)(Pen, PointF[]) | Zeichnet ein Polygon, das durch ein Array von definiert ist[`PointF`](../pointf) Strukturen. |
| [DrawPolygon](../../aspose.imaging/graphics/drawpolygon#drawpolygon_1)(Pen, Point[]) | Zeichnet ein Polygon, das durch ein Array von definiert ist[`Point`](../point) Strukturen. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle)(Pen, Rectangle) | Zeichnet ein durch a angegebenes Rechteck[`Rectangle`](../rectangle) Struktur. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle_1)(Pen, RectangleF) | Zeichnet ein durch a angegebenes Rechteck[`RectangleF`](../rectanglef) Struktur. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle_3)(Pen, float, float, float, float) | Zeichnet ein durch ein Koordinatenpaar, eine Breite und eine Höhe festgelegtes Rechteck. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle_2)(Pen, int, int, int, int) | Zeichnet ein durch ein Koordinatenpaar, eine Breite und eine Höhe festgelegtes Rechteck. |
| [DrawRectangles](../../aspose.imaging/graphics/drawrectangles#drawrectangles)(Pen, RectangleF[]) | Zeichnet eine Reihe von Rechtecken, angegeben durch[`RectangleF`](../rectanglef) Strukturen. |
| [DrawRectangles](../../aspose.imaging/graphics/drawrectangles#drawrectangles_1)(Pen, Rectangle[]) | Zeichnet eine Reihe von Rechtecken, angegeben durch[`Rectangle`](../rectangle) Strukturen. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring)(string, Font, Brush, PointF) | Zeichnet die angegebene Textzeichenfolge an der angegebenen Stelle mit dem angegebenen[`Brush`](../brush) und[`Font`](../font) Objekte. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_2)(string, Font, Brush, RectangleF) | Zeichnet die angegebene Textzeichenfolge in das angegebene Rechteck mit dem angegebenen[`Brush`](../brush) und[`Font`](../font) Objekte. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_4)(string, Font, Brush, float, float) | Zeichnet die angegebene Textzeichenfolge an der angegebenen Stelle mit dem angegebenen[`Brush`](../brush) und[`Font`](../font) Objekte. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_1)(string, Font, Brush, PointF, StringFormat) | Zeichnet die angegebene Textzeichenfolge an der angegebenen Stelle mit dem angegebenen[`Brush`](../brush) und[`Font`](../font) Objekte mit den Formatierungsattributen der angegebenen[`StringFormat`](../stringformat) . |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | Zeichnet die angegebene Textzeichenfolge in das angegebene Rechteck mit dem angegebenen[`Brush`](../brush) und[`Font`](../font) Objekte mit den Formatierungsattributen der angegebenen[`StringFormat`](../stringformat) . |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_5)(string, Font, Brush, float, float, StringFormat) | Zeichnet die angegebene Textzeichenfolge an der angegebenen Stelle mit dem angegebenen[`Brush`](../brush) und[`Font`](../font) Objekte mit den Formatierungsattributen der angegebenen[`StringFormat`](../stringformat) . |
| [EndUpdate](../../aspose.imaging/graphics/endupdate)() | Beendet das Caching der Grafikoperationen, die nach dem Aufruf von BeginUpdate gestartet wurden. Die vorhergehenden Grafikoperationen werden sofort angewendet, wenn diese Methode aufgerufen wird. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve)(Brush, PointF[]) | Füllt das Innere einer geschlossenen kardinalen Spline-Kurve, die durch ein Array von definiert ist[`PointF`](../pointf) Strukturen. Diese Methode verwendet eine Standardspannung von 0,5 undAlternate Füllmodus. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_3)(Brush, Point[]) | Füllt das Innere einer geschlossenen kardinalen Spline-Kurve, die durch ein Array von definiert ist[`Point`](../point) Strukturen. Diese Methode verwendet eine Standardspannung von 0,5 undAlternate Füllmodus. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_1)(Brush, PointF[], FillMode) | Füllt das Innere einer geschlossenen kardinalen Spline-Kurve, die durch ein Array von definiert ist[`PointF`](../pointf) Strukturen mit dem angegebenen Füllmodus. Diese Methode verwendet eine Standardspannung von 0,5. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_4)(Brush, Point[], FillMode) | Füllt das Innere einer geschlossenen kardinalen Spline-Kurve, die durch ein Array von definiert ist[`Point`](../point) Strukturen mit dem angegebenen Füllmodus. Diese Methode verwendet eine Standardspannung von 0,5. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | Füllt das Innere einer geschlossenen kardinalen Spline-Kurve, die durch ein Array von definiert ist[`PointF`](../pointf) Strukturen mit dem angegebenen Füllmodus und der angegebenen Spannung. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_5)(Brush, Point[], FillMode, float) | Füllt das Innere einer geschlossenen kardinalen Spline-Kurve, die durch ein Array von definiert ist[`Point`](../point) Strukturen mit dem angegebenen Füllmodus und der angegebenen Spannung. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse)(Brush, Rectangle) | Füllt das Innere einer Ellipse, die durch ein durch a festgelegtes Begrenzungsrechteck definiert ist[`Rectangle`](../rectangle) Struktur. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse_1)(Brush, RectangleF) | Füllt das Innere einer Ellipse, die durch ein durch a festgelegtes Begrenzungsrechteck definiert ist[`RectangleF`](../rectanglef) Struktur. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse_3)(Brush, float, float, float, float) | Füllt das Innere einer Ellipse, die durch ein Begrenzungsrechteck definiert ist, das durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben wird. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse_2)(Brush, int, int, int, int) | Füllt das Innere einer Ellipse, die durch ein Begrenzungsrechteck definiert ist, das durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben wird. |
| [FillPath](../../aspose.imaging/graphics/fillpath)(Brush, GraphicsPath) | Füllt das Innere von a[`GraphicsPath`](../graphicspath) . |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie)(Brush, Rectangle, float, float) | Füllt das Innere eines Tortenabschnitts, der durch eine durch a angegebene Ellipse definiert ist[`RectangleF`](../rectanglef) Struktur und zwei radiale Linien. |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie_1)(Brush, RectangleF, float, float) | Füllt das Innere eines Tortenabschnitts, der durch eine durch a angegebene Ellipse definiert ist[`RectangleF`](../rectanglef) Struktur und zwei radiale Linien. |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie_3)(Brush, float, float, float, float, float, float) | Füllt das Innere eines Tortenabschnitts, der durch eine Ellipse definiert ist, die durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei radiale Linien angegeben wird. |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie_2)(Brush, int, int, int, int, int, int) | Füllt das Innere eines Tortenabschnitts, der durch eine Ellipse definiert ist, die durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei radiale Linien angegeben wird. |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon)(Brush, PointF[]) | Füllt das Innere eines Polygons, das durch eine Reihe von Punkten definiert ist, die durch angegeben werden[`PointF`](../pointf) Strukturen uAlternate . |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon_2)(Brush, Point[]) | Füllt das Innere eines Polygons, das durch eine Reihe von Punkten definiert ist, die durch angegeben werden[`Point`](../point) Strukturen uAlternate . |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon_1)(Brush, PointF[], FillMode) | Füllt das Innere eines Polygons, das durch eine Reihe von Punkten definiert ist, die durch angegeben werden[`PointF`](../pointf) Strukturen, die den angegebenen Füllmodus verwenden. |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon_3)(Brush, Point[], FillMode) | Füllt das Innere eines Polygons, das durch eine Reihe von Punkten definiert ist, die durch angegeben werden[`Point`](../point) Strukturen, die den angegebenen Füllmodus verwenden. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle)(Brush, Rectangle) | Füllt das Innere eines durch a angegebenen Rechtecks aus[`Rectangle`](../rectangle) Struktur. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle_1)(Brush, RectangleF) | Füllt das Innere eines durch a angegebenen Rechtecks aus[`RectangleF`](../rectanglef) Struktur. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle_3)(Brush, float, float, float, float) | Füllt das Innere eines Rechtecks aus, das durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben ist. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle_2)(Brush, int, int, int, int) | Füllt das Innere eines Rechtecks aus, das durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben ist. |
| [FillRectangles](../../aspose.imaging/graphics/fillrectangles#fillrectangles)(Brush, RectangleF[]) | Füllt das Innere einer Reihe von Rechtecken, die durch angegeben werden[`RectangleF`](../rectanglef) Strukturen. |
| [FillRectangles](../../aspose.imaging/graphics/fillrectangles#fillrectangles_1)(Brush, Rectangle[]) | Füllt das Innere einer Reihe von Rechtecken, die durch angegeben werden[`Rectangle`](../rectangle) Strukturen. |
| [FillRegion](../../aspose.imaging/graphics/fillregion)(Brush, Region) | Füllt das Innere von a[`Region`](../region) . |
| [MeasureString](../../aspose.imaging/graphics/measurestring)(string, Font, SizeF, StringFormat) | Misst die angegebene Textzeichenfolge mit angegebenen Parametern |
| [MultiplyTransform](../../aspose.imaging/graphics/multiplytransform#multiplytransform)(Matrix) | Multipliziert die[`Matrix`](../matrix) das die lokale geometrische Transformation davon darstellt[`Graphics`](../graphics) durch die angegebenen[`Matrix`](../matrix) durch Voranstellen der angegebenen[`Matrix`](../matrix) . |
| [MultiplyTransform](../../aspose.imaging/graphics/multiplytransform#multiplytransform_1)(Matrix, MatrixOrder) | Multipliziert die[`Matrix`](../matrix) das die lokale geometrische Transformation davon darstellt[`Graphics`](../graphics) durch die angegebenen[`Matrix`](../matrix) in der angegebenen Reihenfolge. |
| [ResetTransform](../../aspose.imaging/graphics/resettransform)() | Setzt die zurück[`Transform`](./transform) Eigentum an Identität. |
| [RotateTransform](../../aspose.imaging/graphics/rotatetransform#rotatetransform)(float) | Dreht die lokale geometrische Transformation um den angegebenen Betrag. Diese Methode stellt die Rotation der Transformation voran. |
| [RotateTransform](../../aspose.imaging/graphics/rotatetransform#rotatetransform_1)(float, MatrixOrder) | Dreht die lokale geometrische Transformation um den angegebenen Betrag in der angegebenen Reihenfolge. |
| [ScaleTransform](../../aspose.imaging/graphics/scaletransform#scaletransform)(float, float) | Skaliert die lokale geometrische Transformation um die angegebenen Beträge. Diese Methode stellt der Transformation die Skalierungsmatrix voran. |
| [ScaleTransform](../../aspose.imaging/graphics/scaletransform#scaletransform_1)(float, float, MatrixOrder) | Skaliert die lokale geometrische Transformation um die angegebenen Beträge in der angegebenen Reihenfolge. |
| [TranslateTransform](../../aspose.imaging/graphics/translatetransform#translatetransform)(float, float) | Verschiebt die lokale geometrische Transformation um die angegebenen Abmessungen. Diese Methode stellt die Übersetzung der Transformation voran. |
| [TranslateTransform](../../aspose.imaging/graphics/translatetransform#translatetransform_1)(float, float, MatrixOrder) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge. |

### Beispiele

Dieses Beispiel verwendet die Graphics-Klasse, um primitive Formen auf der Image-Oberfläche zu erstellen. Um den Vorgang zu demonstrieren, erstellt das Beispiel ein neues Image im PNG-Format und zeichnet primitive Formen auf der Image-Oberfläche unter Verwendung von Draw-Methoden, die von der Graphics-Klasse verfügbar gemacht werden

```csharp
[C#]

//Erzeugt eine Instanz von FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.png", System.IO.FileMode.Create))
{
    //Eine Instanz von PngOptions erstellen und ihre verschiedenen Eigenschaften festlegen
    Aspose.Imaging.ImageOptions.PngOptions pngOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    //Setzen Sie die Quelle für PngOptions
    pngOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Eine Instanz von Image erstellen 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(pngOptions, 500, 500))
    {
        //Eine Instanz der Graphics-Klasse erstellen und initialisieren
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Grafikoberfläche löschen
        graphics.Clear(Aspose.Imaging.Color.Wheat);

        //Zeichnen Sie einen Bogen, indem Sie das Stiftobjekt mit schwarzer Farbe angeben, 
        //ein Rechteck, das den Bogen, den Startwinkel und den Sweep-Winkel umgibt
        graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), new Aspose.Imaging.Rectangle(200, 200, 100, 200), 0, 300);

        //Zeichnen Sie einen Bezier, indem Sie das Stiftobjekt mit blauer Farbe und Koordinatenpunkten angeben.
        graphics.DrawBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Point(250, 100), new Aspose.Imaging.Point(300, 30), new Aspose.Imaging.Point(450, 100), new Aspose.Imaging.Point(235, 25));

        //Zeichnen Sie eine Kurve, indem Sie das Stiftobjekt mit grüner Farbe und einem Array von Punkten angeben
        graphics.DrawCurve(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new[] { new Aspose.Imaging.Point(100, 200), new Aspose.Imaging.Point(100, 350), new Aspose.Imaging.Point(200, 450) });

        //Zeichne eine Ellipse mit dem Pen-Objekt und einem umgebenden Rectangle
        graphics.DrawEllipse(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 2), new Aspose.Imaging.Rectangle(300, 300, 100, 100));

        //Zeichne eine Linie 
        graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Violet, 2), new Aspose.Imaging.Point(100, 100), new Aspose.Imaging.Point(200, 200));

        // Zeichne ein Kreissegment
        graphics.DrawPie(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Silver, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(200, 20), new Aspose.Imaging.Size(200, 200)), 0, 45);

        //Zeichnen Sie ein Polygon, indem Sie das Stiftobjekt mit roter Farbe und einem Array von Punkten angeben
        graphics.DrawPolygon(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2), new[] { new Aspose.Imaging.Point(20, 100), new Aspose.Imaging.Point(20, 200), new Aspose.Imaging.Point(220, 20) });

        //Zeichne ein Rechteck
        graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(100, 100)));

        //Ein SolidBrush-Objekt erstellen und seine verschiedenen Eigenschaften festlegen
        Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush();
        brush.Color = Color.Purple;
        brush.Opacity = 100;

        //Zeichne einen String mit dem SolidBrush-Objekt und der Schriftart an einem bestimmten Punkt
        graphics.DrawString("This image is created by Aspose.Imaging API", new Aspose.Imaging.Font("Times New Roman", 16), brush, new Aspose.Imaging.PointF(50, 400));

        // Alle Änderungen speichern.
        image.Save();
    }
}
```

### Siehe auch

* namensraum [Aspose.Imaging](../../aspose.imaging)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
