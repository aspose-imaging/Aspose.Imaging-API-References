---
title: WmfRecorderGraphics2D
second_title: Aspose.Imaging para la referencia de la API de .NET
description: La grabadora Wmf.
type: docs
weight: 8370
url: /es/net/aspose.imaging.fileformats.wmf.graphics/wmfrecordergraphics2d/
---
## WmfRecorderGraphics2D class

La grabadora Wmf.

```csharp
public sealed class WmfRecorderGraphics2D : MetafileRecorderGraphics2D
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [WmfRecorderGraphics2D](wmfrecordergraphics2d)(Rectangle, int) | Inicializa una nueva instancia del[`WmfRecorderGraphics2D`](../wmfrecordergraphics2d) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/backgroundcolor) { get; set; } | Obtiene o establece el color del fondo. |
| [BackgroundMode](../../aspose.imaging.fileformats.wmf.graphics/wmfrecordergraphics2d/backgroundmode) { get; set; } | Obtiene o establece el modo de fondo. |
| [Clip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clip) { get; set; } | Obtiene o establece una Región que limita la región de dibujo de este Graphics |
| [ClipBounds](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clipbounds) { get; } | Obtiene los límites del clip. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromWmfImage](../../aspose.imaging.fileformats.wmf.graphics/wmfrecordergraphics2d/fromwmfimage)(WmfImage) | Obtiene una instancia de la grabadora Wmf para la imagen Wmf existente. |
| [Clear](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clear)() | Borra el estado del objeto gráfico |
| [DrawArc](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawarc)(Pen, Rectangle, float, float) | Dibuja un arco que representa una parte de una elipse especificada por una estructura Rectangle. |
| [DrawCubicBezier](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawcubicbezier)(Pen, Point, Point, Point, Point) | Dibuja el bezier cúbico. |
| [DrawEllipse](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawellipse)(Pen, Rectangle) | Dibuja la elipse. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage)(RasterImage, Point) | Dibuja la Imagen especificada, utilizando su tamaño físico original, en la ubicación especificada. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage)(byte[], Rectangle, GraphicsUnit) | Dibuja la imagen. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage)(Stream, Rectangle, GraphicsUnit) | Dibuja la imagen. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage)(RasterImage, Rectangle, Rectangle, GraphicsUnit) | Dibuja la parte especificada de la imagen especificada en la ubicación especificada y con el tamaño especificado. |
| [DrawLine](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawline)(Pen, Point, Point) | Dibuja la línea. |
| [DrawLine](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawline)(Pen, int, int, int, int) | Dibuja la línea. |
| [DrawPath](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpath)(Pen, GraphicsPath) | Dibuja el camino. |
| [DrawPie](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpie)(Pen, Rectangle, float, float) | Dibuja el pastel. |
| [DrawPolyCubicBezier](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolycubicbezier)(Pen, Point[]) | Dibuja el bezier policúbico. |
| [DrawPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolygon)(Pen, Point[]) | Dibuja el polígono. |
| [DrawPolyline](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolyline)(Pen, Point[]) | Dibuja la polilínea. |
| [DrawRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawrectangle)(Pen, Rectangle) | Dibuja el rectángulo. |
| [DrawRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawrectangle)(Pen, int, int, int, int) | Dibuja el rectángulo. |
| [DrawString](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawstring)(string, Font, Color, int, int) | Dibuja la cadena. |
| [DrawString](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawstring)(string, Font, Color, int, int, float) | Dibuja la cadena. |
| [EndRecording](../../aspose.imaging.fileformats.wmf.graphics/wmfrecordergraphics2d/endrecording)() | Finaliza la grabación. |
| [ExcludeClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/excludeclip)(Rectangle) | Actualiza la región de recorte de este gráfico para excluir el área especificada por una estructura de rectángulo. |
| [ExcludeClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/excludeclip)(Region) | Actualiza la región de recorte de este Gráfico para excluir el área especificada por una Región. |
| [FillEllipse](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillellipse)(Brush, Rectangle) | Rellena la elipse. |
| [FillPath](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpath)(Pen, Brush, GraphicsPath) | Rellena la ruta. |
| [FillPie](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpie)(Brush, Rectangle, float, float) | Llena el pastel. |
| [FillPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpolygon)(Brush, Point[]) | Rellena el polígono. |
| [FillPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpolygon)(Brush, Point[], FillMode) | Rellena el polígono. |
| [FillRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillrectangle)(Brush, Rectangle) | Rellena el rectángulo. |
| [GetTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/gettransform)() | Obtiene la transformación del mundo. |
| [IntersectClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/intersectclip)(RectangleF) | Actualiza la región de recorte de este gráfico a la intersección de la región de recorte actual y la estructura de rectángulo especificada. |
| [IntersectClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/intersectclip)(Region) | Actualiza la región de recorte de este Gráfico a la intersección de la región de recorte actual y la Región especificada. |
| [MultiplyTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/multiplytransform)(Matrix) | Multiplica la transformación mundial de este Gráfico y especifica la Matriz. |
| [MultiplyTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/multiplytransform)(Matrix, MatrixOrder) | Multiplica la transformación mundial de este Gráfico y especifica la Matriz en el orden especificado. |
| [ResetClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/resetclip)() | Reinicia el clip. |
| [RotateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/rotatetransform)(float) | Aplica la rotación especificada a la matriz de transformación de este Graphics. |
| [RotateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/rotatetransform)(float, PointF, MatrixOrder) | Aplica la rotación especificada a la matriz de transformación de este Gráfico en el orden especificado. |
| [ScaleTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/scaletransform)(float, float) | Aplica la operación de escalado especificada a la matriz de transformación de este Graphics anteponiéndola a la matriz de transformación del objeto. |
| [ScaleTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/scaletransform)(float, float, MatrixOrder) | Aplica la operación de escalado especificada a la matriz de transformación de este gráfico en el orden especificado. |
| [SetTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/settransform)(Matrix) | Establece la transformación. |
| [TranslateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/translatetransform)(float, float) | Cambia el origen del sistema de coordenadas anteponiendo la traslación especificada a la matriz de transformación de este Graphics. |
| [TranslateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/translatetransform)(float, float, MatrixOrder) | Cambia el origen del sistema de coordenadas aplicando la traslación especificada a la matriz de transformación de este Gráfico en el orden especificado. |

### Ver también

* class [MetafileRecorderGraphics2D](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d)
* espacio de nombres [Aspose.Imaging.FileFormats.Wmf.Graphics](../../aspose.imaging.fileformats.wmf.graphics)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
