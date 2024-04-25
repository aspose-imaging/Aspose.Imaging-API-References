---
title: Graphics
second_title: Aspose.Imaging för .NET API-referens
description: Representerar grafiken enligt den grafikmotor som används i den aktuella sammansättningen.
type: docs
weight: 9360
url: /sv/aspose.imaging/graphics/
---
## Graphics class

Representerar grafiken enligt den grafikmotor som används i den aktuella sammansättningen.

```csharp
public sealed class Graphics
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Graphics](graphics)(Image) | Initierar en ny instans av[`Graphics`](../graphics) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Clip](../../aspose.imaging/graphics/clip) { get; set; } | Hämtar eller ställer in klippområdet. |
| [CompositingQuality](../../aspose.imaging/graphics/compositingquality) { get; set; } | Hämtar eller ställer in kompositkvaliteten. |
| [DpiX](../../aspose.imaging/graphics/dpix) { get; } | Får den horisontella upplösningen för denna Aspose.Imaging.Graphics. |
| [DpiY](../../aspose.imaging/graphics/dpiy) { get; } | Får den vertikala upplösningen för denna Aspose.Imaging.Graphics. |
| [Image](../../aspose.imaging/graphics/image) { get; } | Hämtar bilden. |
| [InterpolationMode](../../aspose.imaging/graphics/interpolationmode) { get; set; } | Hämtar eller ställer in interpolationsläget. |
| [IsInBeginUpdateCall](../../aspose.imaging/graphics/isinbeginupdatecall) { get; } | Får ett värde som indikerar om grafik är i BeginUpdate-anropstillstånd. |
| [PageScale](../../aspose.imaging/graphics/pagescale) { get; set; } | Hämtar eller ställer in skalningen mellan världsenheter och sidenheter för denna Aspose.Imaging.Graphics. |
| [PageUnit](../../aspose.imaging/graphics/pageunit) { get; set; } | Hämtar eller ställer in måttenheten som används för sidkoordinater i denna Aspose.Imaging.Graphics. |
| [SmoothingMode](../../aspose.imaging/graphics/smoothingmode) { get; set; } | Hämtar eller ställer in utjämningsläget. |
| [TextRenderingHint](../../aspose.imaging/graphics/textrenderinghint) { get; set; } | Hämtar eller ställer in textåtergivningstipset. |
| [Transform](../../aspose.imaging/graphics/transform) { get; set; } | Hämtar eller ställer in en kopia av den geometriska världsomvandlingen för detta[`Graphics`](../graphics) . |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [BeginUpdate](../../aspose.imaging/graphics/beginupdate)() | Startar cachelagring av följande grafikoperationer. De grafiska effekterna som appliceras efteråt kommer inte att tillämpas omedelbart, istället kommer EndUpdate att orsaka att alla effekter appliceras på en gång. |
| [Clear](../../aspose.imaging/graphics/clear)(Color) | Rensar grafikytan med den angivna färgen. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc)(Pen, Rectangle, float, float) | Ritar en båge som representerar en del av en ellips specificerad av a[`Rectangle`](../rectangle) struktur. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc_1)(Pen, RectangleF, float, float) | Ritar en båge som representerar en del av en ellips specificerad av a[`RectangleF`](../rectanglef) struktur. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc_3)(Pen, float, float, float, float, float, float) | Ritar en båge som representerar en del av en ellips specificerad av ett par koordinater, en bredd och en höjd. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc_2)(Pen, int, int, int, int, int, int) | Ritar en båge som representerar en del av en ellips specificerad av ett par koordinater, en bredd och en höjd. |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier#drawbezier)(Pen, Point, Point, Point, Point) | Ritar en Bézier-spline definierad av fyra[`Point`](../point) strukturer. |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | Ritar en Bézier-spline definierad av fyra[`PointF`](../pointf) strukturer. |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | Ritar en Bézier-spline definierad av fyra ordnade par av koordinater som representerar punkter. |
| [DrawBeziers](../../aspose.imaging/graphics/drawbeziers#drawbeziers)(Pen, PointF[]) | Ritar en serie Bézier-splines från en uppsättning av[`PointF`](../pointf) strukturer. |
| [DrawBeziers](../../aspose.imaging/graphics/drawbeziers#drawbeziers_1)(Pen, Point[]) | Ritar en serie Bézier-splines från en uppsättning av[`Point`](../point) strukturer. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve)(Pen, PointF[]) | Ritar en sluten kardinalspline definierad av en array av[`PointF`](../pointf) strukturer. Denna metod använder en standardspänning på 0,5 ochAlternate fyllningsläge. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve_2)(Pen, Point[]) | Ritar en sluten kardinalspline definierad av en array av[`Point`](../point) strukturer. Denna metod använder en standardspänning på 0,5 ochAlternate fyllningsläge. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve_1)(Pen, PointF[], float) | Ritar en sluten kardinalspline definierad av en array av[`PointF`](../pointf) strukturer med en specificerad spänning. Denna metod använder en standardAlternate fyllningsläge. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve_3)(Pen, Point[], float) | Ritar en sluten kardinalspline definierad av en array av[`Point`](../point) strukturer med en specificerad spänning. Denna metod använder en standardAlternate fyllningsläge. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve)(Pen, PointF[]) | Ritar en kardinal spline genom en specificerad array av[`PointF`](../pointf) strukturer. Den här metoden använder en standardspänning på 0.5. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_4)(Pen, Point[]) | Ritar en kardinal spline genom en specificerad array av[`Point`](../point) strukturer. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_3)(Pen, PointF[], float) | Ritar en kardinal spline genom en specificerad array av[`PointF`](../pointf) strukturer med en specificerad spänning. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_6)(Pen, Point[], float) | Ritar en kardinal spline genom en specificerad array av[`Point`](../point) strukturer med en specificerad spänning. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_1)(Pen, PointF[], int, int) | Ritar en kardinal spline genom en specificerad array av[`PointF`](../pointf) strukturer. Ritningen börjar offset från början av arrayen. Denna metod använder en standardspänning på 0,5. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_2)(Pen, PointF[], int, int, float) | Ritar en kardinal spline genom en specificerad array av[`PointF`](../pointf)strukturer med en specificerad spänning. Ritningen börjar offset från början av arrayen. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_5)(Pen, Point[], int, int, float) | Ritar en kardinal spline genom en specificerad array av[`Point`](../point) strukturer med en specificerad spänning. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse)(Pen, Rectangle) | Ritar en ellips specificerad av en begränsning[`Rectangle`](../rectangle) struktur. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse_1)(Pen, RectangleF) | Ritar en ellips definierad av en avgränsning[`RectangleF`](../rectanglef) . |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse_3)(Pen, float, float, float, float) | Ritar en ellips definierad av en avgränsande rektangel specificerad av ett par koordinater, en höjd och en bredd. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse_2)(Pen, int, int, int, int) | Ritar en ellips definierad av en avgränsande rektangel specificerad av ett par koordinater, en höjd och en bredd. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage)(Image, Point) | Ritar det angivna[`Image`](./image) , med sin ursprungliga fysiska storlek, på den angivna platsen. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_1)(Image, PointF) | Ritar det angivna[`Image`](./image) , med sin ursprungliga fysiska storlek, på den angivna platsen. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_2)(Image, PointF[]) | Ritar den angivna delen av den angivna*image* på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_6)(Image, Point[]) | Ritar den angivna delen av den angivna*image* på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_10)(Image, Rectangle) | Ritar det angivna[`Image`](./image) på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_15)(Image, RectangleF) | Ritar det angivna[`Image`](./image) på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_22)(Image, float, float) | Ritar det angivna[`Image`](./image) , med sin ursprungliga fysiska storlek, på den angivna platsen. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_20)(Image, int, int) | Ritar den angivna bilden, med dess ursprungliga fysiska storlek, på den plats som anges av ett koordinatpar. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_3)(Image, PointF[], RectangleF) | Ritar den angivna delen av den angivna*image* på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_7)(Image, Point[], Rectangle) | Ritar den angivna delen av den angivna*image* på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_11)(Image, Rectangle, GraphicsUnit) | Ritar det angivna[`Image`](./image) på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_16)(Image, RectangleF, GraphicsUnit) | Ritar det angivna[`Image`](./image) på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | Ritar den angivna delen av den angivna*image* på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | Ritar den angivna delen av den angivna*image* på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | Ritar det angivna[`Image`](./image) på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | Ritar det angivna[`Image`](./image) på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | Ritar det angivna[`Image`](./image) på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | Ritar det angivna[`Image`](./image) på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_23)(Image, float, float, float, float) | Ritar det angivna[`Image`](./image) på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_21)(Image, int, int, int, int) | Ritar det angivna[`Image`](./image) på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | Ritar den angivna delen av den angivna*image* på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | Ritar den angivna delen av den angivna*image* på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | Ritar det angivna[`Image`](./image) på angiven plats och med angiven storlek. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | Ritar det angivna[`Image`](./image) på angiven plats och med angiven storlek. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled)(Image, Point) | Ritar en angiven bild med dess ursprungliga fysiska storlek på en angiven plats. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled_1)(Image, Rectangle) | Ritar en angiven bild med dess ursprungliga fysiska storlek på en angiven plats. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled_2)(Image, int, int) | Ritar den angivna bilden med dess ursprungliga fysiska storlek på den plats som anges av ett koordinatpar. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled_3)(Image, int, int, int, int) | Ritar en angiven bild med dess ursprungliga fysiska storlek på en angiven plats. |
| [DrawImageUnscaledAndClipped](../../aspose.imaging/graphics/drawimageunscaledandclipped)(Image, Rectangle) | Ritar den angivna bilden utan skalning och klipper den vid behov så att den passar i den angivna rektangeln. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline)(Pen, Point, Point) | Ritar en linje som förbinder två[`Point`](../point) strukturer. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline_1)(Pen, PointF, PointF) | Ritar en linje som förbinder två[`PointF`](../pointf) strukturer. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline_3)(Pen, float, float, float, float) | Ritar en linje som förbinder de två punkter som anges av koordinatparen. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline_2)(Pen, int, int, int, int) | Ritar en linje som förbinder de två punkter som anges av koordinatparen. |
| [DrawLines](../../aspose.imaging/graphics/drawlines#drawlines)(Pen, PointF[]) | Ritar en serie linjesegment som förbinder en array av[`PointF`](../pointf) strukturer. |
| [DrawLines](../../aspose.imaging/graphics/drawlines#drawlines_1)(Pen, Point[]) | Ritar en serie linjesegment som förbinder en array av[`Point`](../point) strukturer. |
| [DrawPath](../../aspose.imaging/graphics/drawpath)(Pen, GraphicsPath) | Ritar en[`GraphicsPath`](../graphicspath) . |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie)(Pen, Rectangle, float, float) | Ritar en pajform definierad av en ellips specificerad av a[`Rectangle`](../rectangle) struktur och två radiella linjer. |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie_1)(Pen, RectangleF, float, float) | Ritar en pajform definierad av en ellips specificerad av a[`RectangleF`](../rectanglef) struktur och två radiella linjer. |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie_3)(Pen, float, float, float, float, float, float) | Ritar en cirkelform som definieras av en ellips specificerad av ett koordinatpar, en bredd, en höjd och två radiella linjer. |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie_2)(Pen, int, int, int, int, int, int) | Ritar en cirkelform som definieras av en ellips specificerad av ett koordinatpar, en bredd, en höjd och två radiella linjer. |
| [DrawPolygon](../../aspose.imaging/graphics/drawpolygon#drawpolygon)(Pen, PointF[]) | Ritar en polygon som definieras av en array av[`PointF`](../pointf) strukturer. |
| [DrawPolygon](../../aspose.imaging/graphics/drawpolygon#drawpolygon_1)(Pen, Point[]) | Ritar en polygon som definieras av en array av[`Point`](../point) strukturer. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle)(Pen, Rectangle) | Ritar en rektangel specificerad av a[`Rectangle`](../rectangle) struktur. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle_1)(Pen, RectangleF) | Ritar en rektangel specificerad av a[`RectangleF`](../rectanglef) struktur. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle_3)(Pen, float, float, float, float) | Ritar en rektangel specificerad av ett koordinatpar, en bredd och en höjd. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle_2)(Pen, int, int, int, int) | Ritar en rektangel specificerad av ett koordinatpar, en bredd och en höjd. |
| [DrawRectangles](../../aspose.imaging/graphics/drawrectangles#drawrectangles)(Pen, RectangleF[]) | Ritar en serie rektanglar specificerade av[`RectangleF`](../rectanglef) strukturer. |
| [DrawRectangles](../../aspose.imaging/graphics/drawrectangles#drawrectangles_1)(Pen, Rectangle[]) | Ritar en serie rektanglar specificerade av[`Rectangle`](../rectangle) strukturer. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring)(string, Font, Brush, PointF) | Ritar den angivna textsträngen på den angivna platsen med den angivna[`Brush`](../brush) och[`Font`](../font) objekt. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_2)(string, Font, Brush, RectangleF) | Ritar den angivna textsträngen i den angivna rektangeln med den angivna[`Brush`](../brush) och[`Font`](../font) objekt. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_4)(string, Font, Brush, float, float) | Ritar den angivna textsträngen på den angivna platsen med den angivna[`Brush`](../brush) och[`Font`](../font) objekt. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_1)(string, Font, Brush, PointF, StringFormat) | Ritar den angivna textsträngen på den angivna platsen med den angivna[`Brush`](../brush) och[`Font`](../font) objekt som använder formateringsattributen för de angivna[`StringFormat`](../stringformat) . |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | Ritar den angivna textsträngen i den angivna rektangeln med den angivna[`Brush`](../brush) och[`Font`](../font) objekt som använder formateringsattributen för de angivna[`StringFormat`](../stringformat) . |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_5)(string, Font, Brush, float, float, StringFormat) | Ritar den angivna textsträngen på den angivna platsen med den angivna[`Brush`](../brush) och[`Font`](../font) objekt som använder formateringsattributen för de angivna[`StringFormat`](../stringformat) . |
| [EndUpdate](../../aspose.imaging/graphics/endupdate)() | Avslutar cachelagring av grafikoperationerna som startade efter att BeginUpdate anropades. De föregående grafikoperationerna kommer att tillämpas på en gång när den här metoden anropas. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve)(Brush, PointF[]) | Fyller det inre av en sluten kardinalsplinekurva som definieras av en array av[`PointF`](../pointf) strukturer. Denna metod använder en standardspänning på 0,5 ochAlternate fyllningsläge. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_3)(Brush, Point[]) | Fyller det inre av en sluten kardinalsplinekurva som definieras av en array av[`Point`](../point) strukturer. Denna metod använder en standardspänning på 0,5 ochAlternate fyllningsläge. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_1)(Brush, PointF[], FillMode) | Fyller det inre av en sluten kardinalsplinekurva som definieras av en array av[`PointF`](../pointf) strukturer med det angivna fyllningsläget. Den här metoden använder en standardspänning på 0.5. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_4)(Brush, Point[], FillMode) | Fyller det inre av en sluten kardinalsplinekurva som definieras av en array av[`Point`](../point) strukturer med det angivna fyllningsläget. Den här metoden använder en standardspänning på 0.5. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | Fyller det inre av en sluten kardinalsplinekurva som definieras av en array av[`PointF`](../pointf) strukturer som använder det angivna fyllningsläget och spänningen. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_5)(Brush, Point[], FillMode, float) | Fyller det inre av en sluten kardinalsplinekurva som definieras av en array av[`Point`](../point) strukturer som använder det angivna fyllningsläget och spänningen. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse)(Brush, Rectangle) | Fyller det inre av en ellips definierad av en avgränsande rektangel specificerad av en[`Rectangle`](../rectangle) struktur. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse_1)(Brush, RectangleF) | Fyller det inre av en ellips definierad av en avgränsande rektangel specificerad av en[`RectangleF`](../rectanglef) struktur. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse_3)(Brush, float, float, float, float) | Fyller det inre av en ellips definierad av en avgränsande rektangel specificerad av ett par koordinater, en bredd och en höjd. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse_2)(Brush, int, int, int, int) | Fyller det inre av en ellips definierad av en avgränsande rektangel specificerad av ett par koordinater, en bredd och en höjd. |
| [FillPath](../../aspose.imaging/graphics/fillpath)(Brush, GraphicsPath) | Fyller det inre av en[`GraphicsPath`](../graphicspath) . |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie)(Brush, Rectangle, float, float) | Fyller det inre av en pajsektion definierad av en ellips specificerad av en[`RectangleF`](../rectanglef) struktur och två radiella linjer. |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie_1)(Brush, RectangleF, float, float) | Fyller det inre av en pajsektion definierad av en ellips specificerad av en[`RectangleF`](../rectanglef) struktur och två radiella linjer. |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie_3)(Brush, float, float, float, float, float, float) | Fyller det inre av en pajsektion definierad av en ellips specificerad av ett par koordinater, en bredd, en höjd och två radiella linjer. |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie_2)(Brush, int, int, int, int, int, int) | Fyller det inre av en pajsektion definierad av en ellips specificerad av ett par koordinater, en bredd, en höjd och två radiella linjer. |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon)(Brush, PointF[]) | Fyller det inre av en polygon som definieras av en matris med punkter som specificeras av[`PointF`](../pointf) strukturer ochAlternate . |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon_2)(Brush, Point[]) | Fyller det inre av en polygon som definieras av en matris med punkter som specificeras av[`Point`](../point) strukturer ochAlternate . |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon_1)(Brush, PointF[], FillMode) | Fyller det inre av en polygon som definieras av en matris med punkter som specificeras av[`PointF`](../pointf) strukturer som använder det angivna fyllningsläget. |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon_3)(Brush, Point[], FillMode) | Fyller det inre av en polygon som definieras av en matris med punkter som specificeras av[`Point`](../point) strukturer som använder det angivna fyllningsläget. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle)(Brush, Rectangle) | Fyller det inre av en rektangel specificerad av a[`Rectangle`](../rectangle) struktur. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle_1)(Brush, RectangleF) | Fyller det inre av en rektangel specificerad av a[`RectangleF`](../rectanglef) struktur. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle_3)(Brush, float, float, float, float) | Fyller det inre av en rektangel specificerad av ett par koordinater, en bredd och en höjd. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle_2)(Brush, int, int, int, int) | Fyller det inre av en rektangel specificerad av ett par koordinater, en bredd och en höjd. |
| [FillRectangles](../../aspose.imaging/graphics/fillrectangles#fillrectangles)(Brush, RectangleF[]) | Fyller det inre av en serie rektanglar som anges av[`RectangleF`](../rectanglef) strukturer. |
| [FillRectangles](../../aspose.imaging/graphics/fillrectangles#fillrectangles_1)(Brush, Rectangle[]) | Fyller det inre av en serie rektanglar som anges av[`Rectangle`](../rectangle) strukturer. |
| [FillRegion](../../aspose.imaging/graphics/fillregion)(Brush, Region) | Fyller det inre av en[`Region`](../region) . |
| [MeasureString](../../aspose.imaging/graphics/measurestring)(string, Font, SizeF, StringFormat) | Mäter den angivna textsträngen med specificerade parametrar |
| [MultiplyTransform](../../aspose.imaging/graphics/multiplytransform#multiplytransform)(Matrix) | Multiplicerar[`Matrix`](../matrix) som representerar den lokala geometriska transformationen av detta[`Graphics`](../graphics) av den angivna[`Matrix`](../matrix) genom att föregå det angivna[`Matrix`](../matrix) . |
| [MultiplyTransform](../../aspose.imaging/graphics/multiplytransform#multiplytransform_1)(Matrix, MatrixOrder) | Multiplicerar[`Matrix`](../matrix) som representerar den lokala geometriska transformationen av detta[`Graphics`](../graphics) av den angivna[`Matrix`](../matrix) i angiven ordning. |
| [ResetTransform](../../aspose.imaging/graphics/resettransform)() | Återställer[`Transform`](./transform) egenskap till identitet. |
| [RotateTransform](../../aspose.imaging/graphics/rotatetransform#rotatetransform)(float) | Roterar den lokala geometriska transformationen med angivet belopp. Denna metod förutsätter rotationen till transformationen. |
| [RotateTransform](../../aspose.imaging/graphics/rotatetransform#rotatetransform_1)(float, MatrixOrder) | Roterar den lokala geometriska transformationen med angivet belopp i angiven ordning. |
| [ScaleTransform](../../aspose.imaging/graphics/scaletransform#scaletransform)(float, float) | Skalar den lokala geometriska transformationen med de angivna mängderna. Den här metoden lägger in skalningsmatrisen i transformationen. |
| [ScaleTransform](../../aspose.imaging/graphics/scaletransform#scaletransform_1)(float, float, MatrixOrder) | Skalar den lokala geometriska transformationen med de angivna mängderna i angiven ordning. |
| [TranslateTransform](../../aspose.imaging/graphics/translatetransform#translatetransform)(float, float) | Översätter den lokala geometriska transformationen med de angivna måtten. Denna metod lägger till översättningen till transformen. |
| [TranslateTransform](../../aspose.imaging/graphics/translatetransform#translatetransform_1)(float, float, MatrixOrder) | Översätter den lokala geometriska transformationen med de angivna måtten i angiven ordning. |

### Exempel

Det här exemplet använder klassen Graphics för att skapa primitiva former på bildytan. För att demonstrera operationen skapar exemplet en ny bild i PNG-format och ritar primitiva former på bildytan med ritmetoder exponerade av grafikklassen

```csharp
[C#]

//Skapar en instans av FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.png", System.IO.FileMode.Create))
{
    //Skapa en instans av PngOptions och ställ in dess olika egenskaper
    Aspose.Imaging.ImageOptions.PngOptions pngOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    //Ställ in källan för PngOptions
    pngOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Skapa en instans av bild 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(pngOptions, 500, 500))
    {
        //Skapa och initiera en instans av klassen Graphics
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Rensa grafikytan
        graphics.Clear(Aspose.Imaging.Color.Wheat);

        //Rita en båge genom att ange Pen-objektet som har svart färg, 
        //a rektangel som omger bågen, startvinkeln och svepvinkeln
        graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), new Aspose.Imaging.Rectangle(200, 200, 100, 200), 0, 300);

        //Rita en Bezier genom att ange Pen-objektet som har blå färg och koordinatpunkter.
        graphics.DrawBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Point(250, 100), new Aspose.Imaging.Point(300, 30), new Aspose.Imaging.Point(450, 100), new Aspose.Imaging.Point(235, 25));

        //Rita en kurva genom att ange att Pen-objektet har grön färg och en array av punkter
        graphics.DrawCurve(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new[] { new Aspose.Imaging.Point(100, 200), new Aspose.Imaging.Point(100, 350), new Aspose.Imaging.Point(200, 450) });

        //Rita en ellips med hjälp av Pen-objektet och en omgivande rektangel
        graphics.DrawEllipse(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 2), new Aspose.Imaging.Rectangle(300, 300, 100, 100));

        //Dra ett streck 
        graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Violet, 2), new Aspose.Imaging.Point(100, 100), new Aspose.Imaging.Point(200, 200));

        //Rita ett pajsegment
        graphics.DrawPie(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Silver, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(200, 20), new Aspose.Imaging.Size(200, 200)), 0, 45);

        //Rita en polygon genom att ange att Pen-objektet har röd färg och en array av punkter
        graphics.DrawPolygon(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2), new[] { new Aspose.Imaging.Point(20, 100), new Aspose.Imaging.Point(20, 200), new Aspose.Imaging.Point(220, 20) });

        //Rita en rektangel
        graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(100, 100)));

        //Skapa ett SolidBrush-objekt och ställ in dess olika egenskaper
        Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush();
        brush.Color = Color.Purple;
        brush.Opacity = 100;

        //Rita en sträng med SolidBrush-objektet och Font, vid en viss punkt
        graphics.DrawString("This image is created by Aspose.Imaging API", new Aspose.Imaging.Font("Times New Roman", 16), brush, new Aspose.Imaging.PointF(50, 400));

        // spara alla ändringar.
        image.Save();
    }
}
```

### Se även

* namnutrymme [Aspose.Imaging](../../aspose.imaging)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
