---
title: Graphics
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Representa los gráficos según el motor gráfico utilizado en el ensamblaje actual.
type: docs
weight: 9360
url: /es/net/aspose.imaging/graphics/
---
## Graphics class

Representa los gráficos según el motor gráfico utilizado en el ensamblaje actual.

```csharp
public sealed class Graphics
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Graphics](graphics)(Image) | Inicializa una nueva instancia del[`Graphics`](../graphics) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Clip](../../aspose.imaging/graphics/clip) { get; set; } | Obtiene o establece la región del clip. |
| [CompositingQuality](../../aspose.imaging/graphics/compositingquality) { get; set; } | Obtiene o establece la calidad de composición. |
| [DpiX](../../aspose.imaging/graphics/dpix) { get; } | Obtiene la resolución horizontal de este Aspose.Imaging.Graphics. |
| [DpiY](../../aspose.imaging/graphics/dpiy) { get; } | Obtiene la resolución vertical de este Aspose.Imaging.Graphics. |
| [Image](../../aspose.imaging/graphics/image) { get; } | Obtiene la imagen. |
| [InterpolationMode](../../aspose.imaging/graphics/interpolationmode) { get; set; } | Obtiene o establece el modo de interpolación. |
| [IsInBeginUpdateCall](../../aspose.imaging/graphics/isinbeginupdatecall) { get; } | Obtiene un valor que indica si los gráficos están en estado de llamada BeginUpdate. |
| [PageScale](../../aspose.imaging/graphics/pagescale) { get; set; } | Obtiene o establece la escala entre unidades mundiales y unidades de página para este Aspose.Imaging.Graphics. |
| [PageUnit](../../aspose.imaging/graphics/pageunit) { get; set; } | Obtiene o establece la unidad de medida utilizada para las coordenadas de página en este Aspose.Imaging.Graphics. |
| [SmoothingMode](../../aspose.imaging/graphics/smoothingmode) { get; set; } | Obtiene o establece el modo de suavizado. |
| [TextRenderingHint](../../aspose.imaging/graphics/textrenderinghint) { get; set; } | Obtiene o establece la sugerencia de representación de texto. |
| [Transform](../../aspose.imaging/graphics/transform) { get; set; } | Obtiene o establece una copia de la transformación del mundo geométrico para este[`Graphics`](../graphics) . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [BeginUpdate](../../aspose.imaging/graphics/beginupdate)() | Inicia el almacenamiento en caché de las siguientes operaciones gráficas. Los efectos gráficos aplicados después no se aplicarán inmediatamente, sino que EndUpdate hará que se apliquen todos los efectos a la vez. |
| [Clear](../../aspose.imaging/graphics/clear)(Color) | Borra la superficie gráfica utilizando el color especificado. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc)(Pen, Rectangle, float, float) | Dibuja un arco que representa una parte de una elipse especificada por un[`Rectangle`](../rectangle) estructura. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc_1)(Pen, RectangleF, float, float) | Dibuja un arco que representa una parte de una elipse especificada por un[`RectangleF`](../rectanglef) estructura. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc_3)(Pen, float, float, float, float, float, float) | Dibuja un arco que representa una parte de una elipse especificada por un par de coordenadas, un ancho y una altura. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc_2)(Pen, int, int, int, int, int, int) | Dibuja un arco que representa una parte de una elipse especificada por un par de coordenadas, un ancho y una altura. |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier#drawbezier)(Pen, Point, Point, Point, Point) | Dibuja una spline de Bézier definida por cuatro[`Point`](../point) estructuras. |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | Dibuja una spline de Bézier definida por cuatro[`PointF`](../pointf) estructuras. |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | Dibuja una spline de Bézier definida por cuatro pares ordenados de coordenadas que representan puntos. |
| [DrawBeziers](../../aspose.imaging/graphics/drawbeziers#drawbeziers)(Pen, PointF[]) | Dibuja una serie de splines de Bézier a partir de una matriz de[`PointF`](../pointf) estructuras. |
| [DrawBeziers](../../aspose.imaging/graphics/drawbeziers#drawbeziers_1)(Pen, Point[]) | Dibuja una serie de splines de Bézier a partir de una matriz de[`Point`](../point) estructuras. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve)(Pen, PointF[]) | Dibuja una spline cardinal cerrada definida por una matriz de[`PointF`](../pointf) estructuras Este método utiliza una tensión predeterminada de 0,5 yAlternate modo de relleno. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve_2)(Pen, Point[]) | Dibuja una spline cardinal cerrada definida por una matriz de[`Point`](../point) estructuras Este método utiliza una tensión predeterminada de 0,5 yAlternate modo de relleno. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve_1)(Pen, PointF[], float) | Dibuja una spline cardinal cerrada definida por una matriz de[`PointF`](../pointf) estructuras usando una tensión específica. Este método utiliza un valor predeterminadoAlternate modo de relleno. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve_3)(Pen, Point[], float) | Dibuja una spline cardinal cerrada definida por una matriz de[`Point`](../point) estructuras usando una tensión específica. Este método utiliza un valor predeterminadoAlternate modo de relleno. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve)(Pen, PointF[]) | Dibuja una spline cardinal a través de una matriz específica de[`PointF`](../pointf) estructuras Este método utiliza una tensión predeterminada de 0.5. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_4)(Pen, Point[]) | Dibuja una spline cardinal a través de una matriz específica de[`Point`](../point) estructuras. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_3)(Pen, PointF[], float) | Dibuja una spline cardinal a través de una matriz específica de[`PointF`](../pointf) estructuras usando una tensión especificada. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_6)(Pen, Point[], float) | Dibuja una spline cardinal a través de una matriz específica de[`Point`](../point) estructuras usando una tensión especificada. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_1)(Pen, PointF[], int, int) | Dibuja una spline cardinal a través de una matriz específica de[`PointF`](../pointf) estructuras El dibujo comienza desplazado desde el principio de la matriz. Este método utiliza una tensión predeterminada de 0,5. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_2)(Pen, PointF[], int, int, float) | Dibuja una spline cardinal a través de una matriz específica de[`PointF`](../pointf)estructuras usando una tensión específica. El dibujo comienza desplazado desde el principio de la matriz. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_5)(Pen, Point[], int, int, float) | Dibuja una spline cardinal a través de una matriz específica de[`Point`](../point) estructuras usando una tensión especificada. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse)(Pen, Rectangle) | Dibuja una elipse especificada por un límite[`Rectangle`](../rectangle) estructura. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse_1)(Pen, RectangleF) | Dibuja una elipse definida por un límite[`RectangleF`](../rectanglef) . |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse_3)(Pen, float, float, float, float) | Dibuja una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, una altura y un ancho. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse_2)(Pen, int, int, int, int) | Dibuja una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, una altura y un ancho. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage)(Image, Point) | Dibuja el especificado[`Image`](./image) , utilizando su tamaño físico original, en la ubicación especificada. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_1)(Image, PointF) | Dibuja el especificado[`Image`](./image) , utilizando su tamaño físico original, en la ubicación especificada. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_2)(Image, PointF[]) | Dibuja la parte especificada de la especificada*image* en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_6)(Image, Point[]) | Dibuja la parte especificada de la especificada*image* en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_10)(Image, Rectangle) | Dibuja el especificado[`Image`](./image) en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_15)(Image, RectangleF) | Dibuja el especificado[`Image`](./image) en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_22)(Image, float, float) | Dibuja el especificado[`Image`](./image) , utilizando su tamaño físico original, en la ubicación especificada. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_20)(Image, int, int) | Dibuja la imagen especificada, utilizando su tamaño físico original, en la ubicación especificada por un par de coordenadas. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_3)(Image, PointF[], RectangleF) | Dibuja la parte especificada de la especificada*image* en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_7)(Image, Point[], Rectangle) | Dibuja la parte especificada de la especificada*image* en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_11)(Image, Rectangle, GraphicsUnit) | Dibuja el especificado[`Image`](./image) en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_16)(Image, RectangleF, GraphicsUnit) | Dibuja el especificado[`Image`](./image) en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | Dibuja la parte especificada de la especificada*image* en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | Dibuja la parte especificada de la especificada*image* en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | Dibuja el especificado[`Image`](./image) en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | Dibuja el especificado[`Image`](./image) en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | Dibuja el especificado[`Image`](./image) en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | Dibuja el especificado[`Image`](./image) en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_23)(Image, float, float, float, float) | Dibuja el especificado[`Image`](./image) en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_21)(Image, int, int, int, int) | Dibuja el especificado[`Image`](./image) en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | Dibuja la parte especificada de la especificada*image* en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | Dibuja la parte especificada de la especificada*image* en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | Dibuja el especificado[`Image`](./image) en la ubicación especificada y con el tamaño especificado. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | Dibuja el especificado[`Image`](./image) en la ubicación especificada y con el tamaño especificado. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled)(Image, Point) | Dibuja una imagen específica utilizando su tamaño físico original en una ubicación específica. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled_1)(Image, Rectangle) | Dibuja una imagen específica utilizando su tamaño físico original en una ubicación específica. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled_2)(Image, int, int) | Dibuja la imagen especificada usando su tamaño físico original en la ubicación especificada por un par de coordenadas. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled_3)(Image, int, int, int, int) | Dibuja una imagen específica utilizando su tamaño físico original en una ubicación específica. |
| [DrawImageUnscaledAndClipped](../../aspose.imaging/graphics/drawimageunscaledandclipped)(Image, Rectangle) | Dibuja la imagen especificada sin escalar y la recorta, si es necesario, para que quepa en el rectángulo especificado. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline)(Pen, Point, Point) | Dibuja una línea que conecta dos[`Point`](../point) estructuras. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline_1)(Pen, PointF, PointF) | Dibuja una línea que conecta dos[`PointF`](../pointf) estructuras. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline_3)(Pen, float, float, float, float) | Dibuja una línea que conecta los dos puntos especificados por los pares de coordenadas. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline_2)(Pen, int, int, int, int) | Dibuja una línea que conecta los dos puntos especificados por los pares de coordenadas. |
| [DrawLines](../../aspose.imaging/graphics/drawlines#drawlines)(Pen, PointF[]) | Dibuja una serie de segmentos de línea que conectan una matriz de[`PointF`](../pointf) estructuras. |
| [DrawLines](../../aspose.imaging/graphics/drawlines#drawlines_1)(Pen, Point[]) | Dibuja una serie de segmentos de línea que conectan una matriz de[`Point`](../point) estructuras. |
| [DrawPath](../../aspose.imaging/graphics/drawpath)(Pen, GraphicsPath) | Dibuja un[`GraphicsPath`](../graphicspath) . |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie)(Pen, Rectangle, float, float) | Dibuja una forma circular definida por una elipse especificada por un[`Rectangle`](../rectangle) estructura y dos líneas radiales. |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie_1)(Pen, RectangleF, float, float) | Dibuja una forma circular definida por una elipse especificada por un[`RectangleF`](../rectanglef) estructura y dos líneas radiales. |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie_3)(Pen, float, float, float, float, float, float) | Dibuja una forma circular definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales. |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie_2)(Pen, int, int, int, int, int, int) | Dibuja una forma circular definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales. |
| [DrawPolygon](../../aspose.imaging/graphics/drawpolygon#drawpolygon)(Pen, PointF[]) | Dibuja un polígono definido por una matriz de[`PointF`](../pointf) estructuras. |
| [DrawPolygon](../../aspose.imaging/graphics/drawpolygon#drawpolygon_1)(Pen, Point[]) | Dibuja un polígono definido por una matriz de[`Point`](../point) estructuras. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle)(Pen, Rectangle) | Dibuja un rectángulo especificado por un[`Rectangle`](../rectangle) estructura. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle_1)(Pen, RectangleF) | Dibuja un rectángulo especificado por un[`RectangleF`](../rectanglef) estructura. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle_3)(Pen, float, float, float, float) | Dibuja un rectángulo especificado por un par de coordenadas, un ancho y una altura. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle_2)(Pen, int, int, int, int) | Dibuja un rectángulo especificado por un par de coordenadas, un ancho y una altura. |
| [DrawRectangles](../../aspose.imaging/graphics/drawrectangles#drawrectangles)(Pen, RectangleF[]) | Dibuja una serie de rectángulos especificados por[`RectangleF`](../rectanglef) estructuras. |
| [DrawRectangles](../../aspose.imaging/graphics/drawrectangles#drawrectangles_1)(Pen, Rectangle[]) | Dibuja una serie de rectángulos especificados por[`Rectangle`](../rectangle) estructuras. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring)(string, Font, Brush, PointF) | Dibuja la cadena de texto especificada en la ubicación especificada con el[`Brush`](../brush) y[`Font`](../font) objetos. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_2)(string, Font, Brush, RectangleF) | Dibuja la cadena de texto especificada en el rectángulo especificado con el[`Brush`](../brush) y[`Font`](../font) objetos. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_4)(string, Font, Brush, float, float) | Dibuja la cadena de texto especificada en la ubicación especificada con el[`Brush`](../brush) y[`Font`](../font) objetos. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_1)(string, Font, Brush, PointF, StringFormat) | Dibuja la cadena de texto especificada en la ubicación especificada con el[`Brush`](../brush) y[`Font`](../font) objetos usando los atributos de formato del especificado[`StringFormat`](../stringformat) . |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | Dibuja la cadena de texto especificada en el rectángulo especificado con el[`Brush`](../brush) y[`Font`](../font) objetos usando los atributos de formato del especificado[`StringFormat`](../stringformat) . |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_5)(string, Font, Brush, float, float, StringFormat) | Dibuja la cadena de texto especificada en la ubicación especificada con el[`Brush`](../brush) y[`Font`](../font) objetos usando los atributos de formato del especificado[`StringFormat`](../stringformat) . |
| [EndUpdate](../../aspose.imaging/graphics/endupdate)() | Finaliza el almacenamiento en caché de las operaciones gráficas iniciadas después de llamar a BeginUpdate. Las operaciones gráficas anteriores se aplicarán inmediatamente al llamar a este método. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve)(Brush, PointF[]) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de[`PointF`](../pointf) estructuras Este método utiliza una tensión predeterminada de 0,5 yAlternate modo de relleno. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_3)(Brush, Point[]) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de[`Point`](../point) estructuras Este método utiliza una tensión predeterminada de 0,5 yAlternate modo de relleno. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_1)(Brush, PointF[], FillMode) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de[`PointF`](../pointf) estructuras utilizando el modo de relleno especificado. Este método utiliza una tensión predeterminada de 0.5. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_4)(Brush, Point[], FillMode) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de[`Point`](../point) estructuras utilizando el modo de relleno especificado. Este método utiliza una tensión predeterminada de 0.5. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de[`PointF`](../pointf) estructuras utilizando el modo de relleno y la tensión especificados. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_5)(Brush, Point[], FillMode, float) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de[`Point`](../point) estructuras utilizando el modo de relleno y la tensión especificados. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse)(Brush, Rectangle) | Rellena el interior de una elipse definida por un rectángulo delimitador especificado por un[`Rectangle`](../rectangle) estructura. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse_1)(Brush, RectangleF) | Rellena el interior de una elipse definida por un rectángulo delimitador especificado por un[`RectangleF`](../rectanglef) estructura. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse_3)(Brush, float, float, float, float) | Rellena el interior de una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, un ancho y una altura. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse_2)(Brush, int, int, int, int) | Rellena el interior de una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, un ancho y una altura. |
| [FillPath](../../aspose.imaging/graphics/fillpath)(Brush, GraphicsPath) | Llena el interior de un[`GraphicsPath`](../graphicspath) . |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie)(Brush, Rectangle, float, float) | Rellena el interior de una sección circular definida por una elipse especificada por un[`RectangleF`](../rectanglef) estructura y dos líneas radiales. |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie_1)(Brush, RectangleF, float, float) | Rellena el interior de una sección circular definida por una elipse especificada por un[`RectangleF`](../rectanglef) estructura y dos líneas radiales. |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie_3)(Brush, float, float, float, float, float, float) | Rellena el interior de una sección circular definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales. |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie_2)(Brush, int, int, int, int, int, int) | Rellena el interior de una sección circular definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales. |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon)(Brush, PointF[]) | Rellena el interior de un polígono definido por una matriz de puntos especificada por[`PointF`](../pointf) estructuras yAlternate . |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon_2)(Brush, Point[]) | Rellena el interior de un polígono definido por una matriz de puntos especificada por[`Point`](../point) estructuras yAlternate . |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon_1)(Brush, PointF[], FillMode) | Rellena el interior de un polígono definido por una matriz de puntos especificada por[`PointF`](../pointf) estructuras utilizando el modo de relleno especificado. |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon_3)(Brush, Point[], FillMode) | Rellena el interior de un polígono definido por una matriz de puntos especificada por[`Point`](../point) estructuras utilizando el modo de relleno especificado. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle)(Brush, Rectangle) | Rellena el interior de un rectángulo especificado por un[`Rectangle`](../rectangle) estructura. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle_1)(Brush, RectangleF) | Rellena el interior de un rectángulo especificado por un[`RectangleF`](../rectanglef) estructura. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle_3)(Brush, float, float, float, float) | Rellena el interior de un rectángulo especificado por un par de coordenadas, un ancho y un alto. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle_2)(Brush, int, int, int, int) | Rellena el interior de un rectángulo especificado por un par de coordenadas, un ancho y un alto. |
| [FillRectangles](../../aspose.imaging/graphics/fillrectangles#fillrectangles)(Brush, RectangleF[]) | Rellena los interiores de una serie de rectángulos especificados por[`RectangleF`](../rectanglef) estructuras. |
| [FillRectangles](../../aspose.imaging/graphics/fillrectangles#fillrectangles_1)(Brush, Rectangle[]) | Rellena los interiores de una serie de rectángulos especificados por[`Rectangle`](../rectangle) estructuras. |
| [FillRegion](../../aspose.imaging/graphics/fillregion)(Brush, Region) | Llena el interior de un[`Region`](../region) . |
| [MeasureString](../../aspose.imaging/graphics/measurestring)(string, Font, SizeF, StringFormat) | Mide la cadena de texto especificada con los parámetros especificados |
| [MultiplyTransform](../../aspose.imaging/graphics/multiplytransform#multiplytransform)(Matrix) | Multiplica el[`Matrix`](../matrix) que representa la transformada geométrica local de este[`Graphics`](../graphics) por el especificado[`Matrix`](../matrix) anteponiendo el especificado[`Matrix`](../matrix) . |
| [MultiplyTransform](../../aspose.imaging/graphics/multiplytransform#multiplytransform_1)(Matrix, MatrixOrder) | Multiplica el[`Matrix`](../matrix) que representa la transformada geométrica local de este[`Graphics`](../graphics) por el especificado[`Matrix`](../matrix) en el orden especificado. |
| [ResetTransform](../../aspose.imaging/graphics/resettransform)() | Restablece el[`Transform`](./transform) propiedad a identidad. |
| [RotateTransform](../../aspose.imaging/graphics/rotatetransform#rotatetransform)(float) | Gira la transformación geométrica local en la cantidad especificada. Este método antepone la rotación a transform. |
| [RotateTransform](../../aspose.imaging/graphics/rotatetransform#rotatetransform_1)(float, MatrixOrder) | Gira la transformación geométrica local en la cantidad especificada en el orden especificado. |
| [ScaleTransform](../../aspose.imaging/graphics/scaletransform#scaletransform)(float, float) | Escala la transformación geométrica local en las cantidades especificadas. Este método antepone la matriz de escala al transform. |
| [ScaleTransform](../../aspose.imaging/graphics/scaletransform#scaletransform_1)(float, float, MatrixOrder) | Escala la transformación geométrica local en las cantidades especificadas en el orden especificado. |
| [TranslateTransform](../../aspose.imaging/graphics/translatetransform#translatetransform)(float, float) | Traduce la transformación geométrica local por las dimensiones especificadas. Este método antepone la traducción a transform. |
| [TranslateTransform](../../aspose.imaging/graphics/translatetransform#translatetransform_1)(float, float, MatrixOrder) | Traduce la transformación geométrica local por las dimensiones especificadas en el orden especificado. |

### Ejemplos

Este ejemplo usa la clase Graphics para crear formas primitivas en la superficie de la imagen. Para demostrar la operación, el ejemplo crea una nueva imagen en formato PNG y dibuja formas primitivas en la superficie de la imagen utilizando los métodos de dibujo expuestos por la clase Graphics.

```csharp
[C#]

//Crea una instancia de FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.png", System.IO.FileMode.Create))
{
    //Cree una instancia de PngOptions y configure sus diversas propiedades
    Aspose.Imaging.ImageOptions.PngOptions pngOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    //Establecer la fuente para PngOptions
    pngOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Crear una instancia de Imagen 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(pngOptions, 500, 500))
    {
        //Crear e inicializar una instancia de la clase Graphics
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Borrar superficie gráfica
        graphics.Clear(Aspose.Imaging.Color.Wheat);

        // Dibuje un Arco especificando el objeto Pluma que tiene color Negro, 
        //un rectángulo que rodea el arco, el ángulo de inicio y el ángulo de barrido
        graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), new Aspose.Imaging.Rectangle(200, 200, 100, 200), 0, 300);

        //Dibuje un Bézier especificando el objeto Pen que tiene color azul y puntos de coordenadas.
        graphics.DrawBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Point(250, 100), new Aspose.Imaging.Point(300, 30), new Aspose.Imaging.Point(450, 100), new Aspose.Imaging.Point(235, 25));

        //Dibuje una curva especificando el objeto Pen que tiene color verde y una matriz de puntos
        graphics.DrawCurve(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new[] { new Aspose.Imaging.Point(100, 200), new Aspose.Imaging.Point(100, 350), new Aspose.Imaging.Point(200, 450) });

        //Dibuja una Elipse usando el objeto Pluma y un Rectángulo circundante
        graphics.DrawEllipse(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 2), new Aspose.Imaging.Rectangle(300, 300, 100, 100));

        //Dibuja una línea 
        graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Violet, 2), new Aspose.Imaging.Point(100, 100), new Aspose.Imaging.Point(200, 200));

        //Dibujar un segmento circular
        graphics.DrawPie(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Silver, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(200, 20), new Aspose.Imaging.Size(200, 200)), 0, 45);

        //Dibuje un polígono especificando el objeto Pen que tiene color rojo y una matriz de puntos
        graphics.DrawPolygon(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2), new[] { new Aspose.Imaging.Point(20, 100), new Aspose.Imaging.Point(20, 200), new Aspose.Imaging.Point(220, 20) });

        //Dibujar un Rectángulo
        graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(100, 100)));

        //Crear un objeto SolidBrush y establecer sus diversas propiedades
        Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush();
        brush.Color = Color.Purple;
        brush.Opacity = 100;

        //Dibuje una cadena usando el objeto SolidBrush y la fuente, en un punto específico
        graphics.DrawString("This image is created by Aspose.Imaging API", new Aspose.Imaging.Font("Times New Roman", 16), brush, new Aspose.Imaging.PointF(50, 400));

        // guarda todos los cambios.
        image.Save();
    }
}
```

### Ver también

* espacio de nombres [Aspose.Imaging](../../aspose.imaging)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
