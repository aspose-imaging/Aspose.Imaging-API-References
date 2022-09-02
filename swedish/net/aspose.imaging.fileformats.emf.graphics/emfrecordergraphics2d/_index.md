---
title: EmfRecorderGraphics2D
second_title: Aspose.Imaging för .NET API-referens
description: Emf-inspelarens grafik
type: docs
weight: 6490
url: /sv/net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/
---
## EmfRecorderGraphics2D class

Emf-inspelarens grafik

```csharp
public sealed class EmfRecorderGraphics2D : MetafileRecorderGraphics2D
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfRecorderGraphics2D](emfrecordergraphics2d)(Rectangle, Size, Size) | Initierar en ny instans av[`EmfRecorderGraphics2D`](../emfrecordergraphics2d) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/backgroundcolor) { get; set; } | Hämtar eller ställer in färgen på bakgrunden. |
| [BackgroundMode](../../aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/backgroundmode) { get; set; } | Hämtar eller ställer in bakgrundsläget. |
| [Clip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clip) { get; set; } | Hämtar eller ställer in en region som begränsar ritområdet för denna Graphics |
| [ClipBounds](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clipbounds) { get; } | Får klippets gränser. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [FromEmfImage](../../aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/fromemfimage)(EmfImage) | Hämtar en instans av[`EmfRecorderGraphics2D`](../emfrecordergraphics2d) som innehåller alla poster från Emf-bilden. |
| [Clear](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clear)() | Rensar tillståndet för grafikobjektet |
| [DrawArc](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawarc)(Pen, Rectangle, float, float) | Ritar en båge som representerar en del av en ellips specificerad av en rektangelstruktur. |
| [DrawCubicBezier](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawcubicbezier)(Pen, Point, Point, Point, Point) | Ritar den kubiska beziern. |
| [DrawEllipse](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawellipse)(Pen, Rectangle) | Ritar ellipsen. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage)(RasterImage, Point) | Ritar den angivna bilden, med dess ursprungliga fysiska storlek, på den angivna platsen. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage)(byte[], Rectangle, GraphicsUnit) | Ritar bilden. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage)(Stream, Rectangle, GraphicsUnit) | Ritar bilden. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage)(RasterImage, Rectangle, Rectangle, GraphicsUnit) | Ritar den angivna delen av den angivna bilden på den angivna platsen och med den angivna storleken. |
| [DrawLine](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawline)(Pen, Point, Point) | Ritar linjen. |
| [DrawLine](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawline)(Pen, int, int, int, int) | Ritar linjen. |
| [DrawPath](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpath)(Pen, GraphicsPath) | Ritar banan. |
| [DrawPie](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpie)(Pen, Rectangle, float, float) | Ritar pajen. |
| [DrawPolyCubicBezier](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolycubicbezier)(Pen, Point[]) | Ritar poly cubic bezier. |
| [DrawPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolygon)(Pen, Point[]) | Ritar polygonen. |
| [DrawPolyline](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolyline)(Pen, Point[]) | Ritar polylinjen. |
| [DrawRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawrectangle)(Pen, Rectangle) | Ritar rektangeln. |
| [DrawRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawrectangle)(Pen, int, int, int, int) | Ritar rektangeln. |
| [DrawString](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawstring)(string, Font, Color, int, int) | Ritar strängen. |
| [DrawString](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawstring)(string, Font, Color, int, int, float) | Ritar strängen. |
| [EndRecording](../../aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/endrecording)() | Avslutar inspelningen. |
| [ExcludeClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/excludeclip)(Rectangle) | Uppdaterar klippområdet för denna grafik för att utesluta området som specificeras av en rektangelstruktur. |
| [ExcludeClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/excludeclip)(Region) | Uppdaterar klippområdet för denna grafik för att utesluta området som anges av en region. |
| [FillEllipse](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillellipse)(Brush, Rectangle) | Fyller ellipsen. |
| [FillPath](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpath)(Pen, Brush, GraphicsPath) | Fyller sökvägen. |
| [FillPie](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpie)(Brush, Rectangle, float, float) | Fyller pajen. |
| [FillPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpolygon)(Brush, Point[]) | Fyller polygonen. |
| [FillPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpolygon)(Brush, Point[], FillMode) | Fyller polygonen. |
| [FillRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillrectangle)(Brush, Rectangle) | Fyller rektangeln. |
| [GetTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/gettransform)() | Får världen att förändras. |
| [IntersectClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/intersectclip)(RectangleF) | Uppdaterar klippområdet för denna grafik till skärningspunkten mellan det aktuella klippområdet och den specificerade rektangelstrukturen. |
| [IntersectClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/intersectclip)(Region) | Uppdaterar klippområdet för denna grafik till skärningspunkten mellan den aktuella klippregionen och den angivna regionen. |
| [MultiplyTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/multiplytransform)(Matrix) | Multiplicerar världsomvandlingen av denna grafik och specificerar matrisen. |
| [MultiplyTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/multiplytransform)(Matrix, MatrixOrder) | Multiplicerar världsomvandlingen av denna grafik och specificerar matrisen i angiven ordning. |
| [ResetClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/resetclip)() | Återställer klippet. |
| [RotateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/rotatetransform)(float) | Tillämpar den angivna rotationen på transformationsmatrisen för denna grafik. |
| [RotateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/rotatetransform)(float, PointF, MatrixOrder) | Tillämpar den angivna rotationen på transformationsmatrisen för denna grafik i angiven ordning. |
| [ScaleTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/scaletransform)(float, float) | Tillämpar den angivna skalningsoperationen på transformationsmatrisen för denna grafik genom att prependera den till objektets transformationsmatris. |
| [ScaleTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/scaletransform)(float, float, MatrixOrder) | Tillämpar den angivna skalningsoperationen på transformationsmatrisen för denna grafik i angiven ordning. |
| [SetTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/settransform)(Matrix) | Ställer in transformationen. |
| [TranslateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/translatetransform)(float, float) | Ändrar ursprunget för koordinatsystemet genom att lägga till den specificerade översättningen till transformationsmatrisen för denna grafik. |
| [TranslateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/translatetransform)(float, float, MatrixOrder) | Ändrar ursprunget för koordinatsystemet genom att tillämpa den specificerade översättningen på transformationsmatrisen för denna grafik i angiven ordning. |

### Se även

* class [MetafileRecorderGraphics2D](../metafilerecordergraphics2d)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.Graphics](../../aspose.imaging.fileformats.emf.graphics)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
