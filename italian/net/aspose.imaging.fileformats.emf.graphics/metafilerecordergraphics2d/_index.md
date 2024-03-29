---
title: MetafileRecorderGraphics2D
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: La grafica del registratore di metafile
type: docs
weight: 6500
url: /it/net/aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/
---
## MetafileRecorderGraphics2D class

La grafica del registratore di metafile

```csharp
public abstract class MetafileRecorderGraphics2D
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/backgroundcolor) { get; set; } | Ottiene o imposta il colore dello sfondo. |
| [Clip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clip) { get; set; } | Ottiene o imposta una regione che limita l'area di disegno di questa grafica |
| [ClipBounds](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clipbounds) { get; } | Ottiene i limiti della clip. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Clear](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clear)() | Cancella lo stato dell'oggetto grafico |
| [DrawArc](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawarc)(Pen, Rectangle, float, float) | Disegna un arco che rappresenta una porzione di un'ellisse specificata da una struttura Rectangle. |
| [DrawCubicBezier](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawcubicbezier)(Pen, Point, Point, Point, Point) | Disegna il bezier cubico. |
| [DrawEllipse](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawellipse)(Pen, Rectangle) | Disegna l'ellisse. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage#drawimage)(RasterImage, Point) | Disegna l'immagine specificata, utilizzando la sua dimensione fisica originale, nella posizione specificata. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage#drawimage_2)(byte[], Rectangle, GraphicsUnit) | Disegna l'immagine. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage#drawimage_3)(Stream, Rectangle, GraphicsUnit) | Disegna l'immagine. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage#drawimage_1)(RasterImage, Rectangle, Rectangle, GraphicsUnit) | Disegna la parte specificata dell'immagine specificata nella posizione specificata e con la dimensione specificata. |
| [DrawLine](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawline#drawline)(Pen, Point, Point) | Disegna la linea. |
| [DrawLine](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawline#drawline_1)(Pen, int, int, int, int) | Disegna la linea. |
| [DrawPath](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpath)(Pen, GraphicsPath) | Disegna il percorso. |
| [DrawPie](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpie)(Pen, Rectangle, float, float) | Disegna la torta. |
| [DrawPolyCubicBezier](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolycubicbezier)(Pen, Point[]) | Disegna il bezier policubico. |
| [DrawPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolygon)(Pen, Point[]) | Disegna il poligono. |
| [DrawPolyline](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolyline)(Pen, Point[]) | Disegna la polilinea. |
| [DrawRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawrectangle#drawrectangle)(Pen, Rectangle) | Disegna il rettangolo. |
| [DrawRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawrectangle#drawrectangle_1)(Pen, int, int, int, int) | Disegna il rettangolo. |
| [DrawString](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawstring#drawstring)(string, Font, Color, int, int) | Disegna la stringa. |
| [DrawString](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawstring#drawstring_1)(string, Font, Color, int, int, float) | Disegna la stringa. |
| [ExcludeClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/excludeclip#excludeclip)(Rectangle) | Aggiorna l'area di ritaglio di questa grafica per escludere l'area specificata da una struttura Rectangle. |
| [ExcludeClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/excludeclip#excludeclip_1)(Region) | Aggiorna l'area di ritaglio di questa grafica per escludere l'area specificata da una regione. |
| [FillEllipse](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillellipse)(Brush, Rectangle) | Riempie l'ellisse. |
| [FillPath](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpath)(Pen, Brush, GraphicsPath) | Riempie il percorso. |
| [FillPie](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpie)(Brush, Rectangle, float, float) | Riempie la torta. |
| [FillPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpolygon#fillpolygon)(Brush, Point[]) | Riempie il poligono. |
| [FillPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpolygon#fillpolygon_1)(Brush, Point[], FillMode) | Riempie il poligono. |
| [FillRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillrectangle)(Brush, Rectangle) | Riempie il rettangolo. |
| [GetTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/gettransform)() | Ottiene la trasformazione del mondo. |
| [IntersectClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/intersectclip#intersectclip)(RectangleF) | Aggiorna l'area di ritaglio di questa grafica all'intersezione dell'area di ritaglio corrente e la struttura Rectangle specificata. |
| [IntersectClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/intersectclip#intersectclip_1)(Region) | Aggiorna l'area di ritaglio di questa grafica all'intersezione dell'area di ritaglio corrente e l'area specificata. |
| [MultiplyTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/multiplytransform#multiplytransform)(Matrix) | Moltiplica la trasformazione del mondo di questa grafica e specifica la matrice. |
| [MultiplyTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/multiplytransform#multiplytransform_1)(Matrix, MatrixOrder) | Moltiplica la trasformazione del mondo di questa grafica e specifica la matrice nell'ordine specificato. |
| [ResetClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/resetclip)() | Reimposta la clip. |
| [RotateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/rotatetransform#rotatetransform)(float) | Applica la rotazione specificata alla matrice di trasformazione di questo Graphics. |
| [RotateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/rotatetransform#rotatetransform_1)(float, PointF, MatrixOrder) | Applica la rotazione specificata alla matrice di trasformazione di questa grafica nell'ordine specificato. |
| [ScaleTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/scaletransform#scaletransform)(float, float) | Applica l'operazione di ridimensionamento specificata alla matrice di trasformazione di questa grafica anteponendola alla matrice di trasformazione dell'oggetto. |
| [ScaleTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/scaletransform#scaletransform_1)(float, float, MatrixOrder) | Applica l'operazione di ridimensionamento specificata alla matrice di trasformazione di questa grafica nell'ordine specificato. |
| [SetTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/settransform)(Matrix) | Imposta la trasformazione. |
| [TranslateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/translatetransform#translatetransform)(float, float) | Modifica l'origine del sistema di coordinate anteponendo la traslazione specificata alla matrice di trasformazione di questa grafica. |
| [TranslateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/translatetransform#translatetransform_1)(float, float, MatrixOrder) | Modifica l'origine del sistema di coordinate applicando la traslazione specificata alla matrice di trasformazione di questa grafica nell'ordine specificato. |

### Guarda anche

* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.Graphics](../../aspose.imaging.fileformats.emf.graphics)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
