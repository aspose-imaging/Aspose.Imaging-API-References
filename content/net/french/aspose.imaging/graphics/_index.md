---
title: Graphics
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Représente les graphiques selon le moteur graphique utilisé dans lassemblage courant.
type: docs
weight: 9360
url: /fr/aspose.imaging/graphics/
---
## Graphics class

Représente les graphiques selon le moteur graphique utilisé dans l'assemblage courant.

```csharp
public sealed class Graphics
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Graphics](graphics)(Image) | Initialise une nouvelle instance du[`Graphics`](../graphics) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Clip](../../aspose.imaging/graphics/clip) { get; set; } | Obtient ou définit la région du clip. |
| [CompositingQuality](../../aspose.imaging/graphics/compositingquality) { get; set; } | Obtient ou définit la qualité de composition. |
| [DpiX](../../aspose.imaging/graphics/dpix) { get; } | Obtient la résolution horizontale de cet Aspose.Imaging.Graphics. |
| [DpiY](../../aspose.imaging/graphics/dpiy) { get; } | Obtient la résolution verticale de cet Aspose.Imaging.Graphics. |
| [Image](../../aspose.imaging/graphics/image) { get; } | Obtient l'image. |
| [InterpolationMode](../../aspose.imaging/graphics/interpolationmode) { get; set; } | Obtient ou définit le mode d'interpolation. |
| [IsInBeginUpdateCall](../../aspose.imaging/graphics/isinbeginupdatecall) { get; } | Obtient une valeur indiquant si les graphiques sont dans l'état d'appel BeginUpdate. |
| [PageScale](../../aspose.imaging/graphics/pagescale) { get; set; } | Obtient ou définit la mise à l'échelle entre les unités mondiales et les unités de page pour ce Aspose.Imaging.Graphics. |
| [PageUnit](../../aspose.imaging/graphics/pageunit) { get; set; } | Obtient ou définit l'unité de mesure utilisée pour les coordonnées de page dans ce Aspose.Imaging.Graphics. |
| [SmoothingMode](../../aspose.imaging/graphics/smoothingmode) { get; set; } | Obtient ou définit le mode de lissage. |
| [TextRenderingHint](../../aspose.imaging/graphics/textrenderinghint) { get; set; } | Obtient ou définit l'indice de rendu du texte. |
| [Transform](../../aspose.imaging/graphics/transform) { get; set; } | Obtient ou définit une copie de la transformation du monde géométrique pour ce[`Graphics`](../graphics) . |

## Méthodes

| Nom | La description |
| --- | --- |
| [BeginUpdate](../../aspose.imaging/graphics/beginupdate)() | Démarre la mise en cache des opérations graphiques suivantes. Les effets graphiques appliqués par la suite ne seront pas appliqués immédiatement, mais EndUpdate entraînera l'application de tous les effets en même temps. |
| [Clear](../../aspose.imaging/graphics/clear)(Color) | Efface la surface graphique en utilisant la couleur spécifiée. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc)(Pen, Rectangle, float, float) | Dessine un arc représentant une portion d'ellipse spécifiée par un[`Rectangle`](../rectangle) structure. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc_1)(Pen, RectangleF, float, float) | Dessine un arc représentant une portion d'ellipse spécifiée par un[`RectangleF`](../rectanglef) structure. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc_3)(Pen, float, float, float, float, float, float) | Dessine un arc représentant une portion d'ellipse spécifiée par une paire de coordonnées, une largeur et une hauteur. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc_2)(Pen, int, int, int, int, int, int) | Dessine un arc représentant une portion d'ellipse spécifiée par une paire de coordonnées, une largeur et une hauteur. |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier#drawbezier)(Pen, Point, Point, Point, Point) | Dessine une spline de Bézier définie par quatre[`Point`](../point) structures. |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | Dessine une spline de Bézier définie par quatre[`PointF`](../pointf) structures. |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | Dessine une spline de Bézier définie par quatre paires ordonnées de coordonnées qui représentent des points. |
| [DrawBeziers](../../aspose.imaging/graphics/drawbeziers#drawbeziers)(Pen, PointF[]) | Dessine une série de splines de Bézier à partir d'un tableau de[`PointF`](../pointf) structures. |
| [DrawBeziers](../../aspose.imaging/graphics/drawbeziers#drawbeziers_1)(Pen, Point[]) | Dessine une série de splines de Bézier à partir d'un tableau de[`Point`](../point) structures. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve)(Pen, PointF[]) | Dessine une spline cardinale fermée définie par un tableau de[`PointF`](../pointf) structures. Cette méthode utilise une tension par défaut de 0,5 etAlternate mode de remplissage. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve_2)(Pen, Point[]) | Dessine une spline cardinale fermée définie par un tableau de[`Point`](../point) structures. Cette méthode utilise une tension par défaut de 0,5 etAlternate mode de remplissage. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve_1)(Pen, PointF[], float) | Dessine une spline cardinale fermée définie par un tableau de[`PointF`](../pointf) structures utilisant une tension spécifiée. Cette méthode utilise une valeur par défautAlternate mode de remplissage. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve_3)(Pen, Point[], float) | Dessine une spline cardinale fermée définie par un tableau de[`Point`](../point) structures utilisant une tension spécifiée. Cette méthode utilise une valeur par défautAlternate mode de remplissage. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve)(Pen, PointF[]) | Dessine une spline cardinale à travers un tableau spécifié de[`PointF`](../pointf) structures. Cette méthode utilise une tension par défaut de 0,5. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_4)(Pen, Point[]) | Dessine une spline cardinale à travers un tableau spécifié de[`Point`](../point) structures. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_3)(Pen, PointF[], float) | Dessine une spline cardinale à travers un tableau spécifié de[`PointF`](../pointf) structures utilisant une tension spécifiée. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_6)(Pen, Point[], float) | Dessine une spline cardinale à travers un tableau spécifié de[`Point`](../point) structures utilisant une tension spécifiée. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_1)(Pen, PointF[], int, int) | Dessine une spline cardinale à travers un tableau spécifié de[`PointF`](../pointf) structures. Le dessin commence décalé depuis le début du tableau. Cette méthode utilise une tension par défaut de 0,5. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_2)(Pen, PointF[], int, int, float) | Dessine une spline cardinale à travers un tableau spécifié de[`PointF`](../pointf)structures utilisant une tension spécifiée. Le dessin commence décalé par rapport au début du tableau. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_5)(Pen, Point[], int, int, float) | Dessine une spline cardinale à travers un tableau spécifié de[`Point`](../point) structures utilisant une tension spécifiée. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse)(Pen, Rectangle) | Dessine une ellipse spécifiée par une limite[`Rectangle`](../rectangle) structure. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse_1)(Pen, RectangleF) | Dessine une ellipse définie par une limite[`RectangleF`](../rectanglef) . |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse_3)(Pen, float, float, float, float) | Dessine une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une hauteur et une largeur. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse_2)(Pen, int, int, int, int) | Dessine une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une hauteur et une largeur. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage)(Image, Point) | Dessine le spécifié[`Image`](./image) , en utilisant sa taille physique d'origine, à l'emplacement spécifié. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_1)(Image, PointF) | Dessine le spécifié[`Image`](./image) , en utilisant sa taille physique d'origine, à l'emplacement spécifié. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_2)(Image, PointF[]) | Dessine la partie spécifiée de la valeur spécifiée*image* à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_6)(Image, Point[]) | Dessine la partie spécifiée de la valeur spécifiée*image* à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_10)(Image, Rectangle) | Dessine le spécifié[`Image`](./image) à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_15)(Image, RectangleF) | Dessine le spécifié[`Image`](./image) à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_22)(Image, float, float) | Dessine le spécifié[`Image`](./image) , en utilisant sa taille physique d'origine, à l'emplacement spécifié. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_20)(Image, int, int) | Dessine l'image spécifiée, en utilisant sa taille physique d'origine, à l'emplacement spécifié par une paire de coordonnées. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_3)(Image, PointF[], RectangleF) | Dessine la partie spécifiée de la valeur spécifiée*image* à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_7)(Image, Point[], Rectangle) | Dessine la partie spécifiée de la valeur spécifiée*image* à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_11)(Image, Rectangle, GraphicsUnit) | Dessine le spécifié[`Image`](./image) à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_16)(Image, RectangleF, GraphicsUnit) | Dessine le spécifié[`Image`](./image) à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | Dessine la partie spécifiée de la valeur spécifiée*image* à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | Dessine la partie spécifiée de la valeur spécifiée*image* à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | Dessine le spécifié[`Image`](./image) à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | Dessine le spécifié[`Image`](./image) à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | Dessine le spécifié[`Image`](./image) à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | Dessine le spécifié[`Image`](./image) à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_23)(Image, float, float, float, float) | Dessine le spécifié[`Image`](./image) à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_21)(Image, int, int, int, int) | Dessine le spécifié[`Image`](./image) à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | Dessine la partie spécifiée de la valeur spécifiée*image* à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | Dessine la partie spécifiée de la valeur spécifiée*image* à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | Dessine le spécifié[`Image`](./image) à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | Dessine le spécifié[`Image`](./image) à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled)(Image, Point) | Dessine une image spécifiée en utilisant sa taille physique d'origine à un emplacement spécifié. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled_1)(Image, Rectangle) | Dessine une image spécifiée en utilisant sa taille physique d'origine à un emplacement spécifié. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled_2)(Image, int, int) | Dessine l'image spécifiée en utilisant sa taille physique d'origine à l'emplacement spécifié par une paire de coordonnées. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled_3)(Image, int, int, int, int) | Dessine une image spécifiée en utilisant sa taille physique d'origine à un emplacement spécifié. |
| [DrawImageUnscaledAndClipped](../../aspose.imaging/graphics/drawimageunscaledandclipped)(Image, Rectangle) | Dessine l'image spécifiée sans mise à l'échelle et la découpe, si nécessaire, pour qu'elle tienne dans le rectangle spécifié. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline)(Pen, Point, Point) | Dessine une ligne reliant deux[`Point`](../point) structures. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline_1)(Pen, PointF, PointF) | Dessine une ligne reliant deux[`PointF`](../pointf) structures. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline_3)(Pen, float, float, float, float) | Dessine une ligne reliant les deux points spécifiés par les paires de coordonnées. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline_2)(Pen, int, int, int, int) | Dessine une ligne reliant les deux points spécifiés par les paires de coordonnées. |
| [DrawLines](../../aspose.imaging/graphics/drawlines#drawlines)(Pen, PointF[]) | Dessine une série de segments de ligne qui relient un tableau de[`PointF`](../pointf) structures. |
| [DrawLines](../../aspose.imaging/graphics/drawlines#drawlines_1)(Pen, Point[]) | Dessine une série de segments de ligne qui relient un tableau de[`Point`](../point) structures. |
| [DrawPath](../../aspose.imaging/graphics/drawpath)(Pen, GraphicsPath) | dessine un[`GraphicsPath`](../graphicspath) . |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie)(Pen, Rectangle, float, float) | Dessine une forme circulaire définie par une ellipse spécifiée par un[`Rectangle`](../rectangle) structure et deux lignes radiales. |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie_1)(Pen, RectangleF, float, float) | Dessine une forme circulaire définie par une ellipse spécifiée par un[`RectangleF`](../rectanglef) structure et deux lignes radiales. |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie_3)(Pen, float, float, float, float, float, float) | Dessine une forme circulaire définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales. |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie_2)(Pen, int, int, int, int, int, int) | Dessine une forme circulaire définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales. |
| [DrawPolygon](../../aspose.imaging/graphics/drawpolygon#drawpolygon)(Pen, PointF[]) | Dessine un polygone défini par un tableau de[`PointF`](../pointf) structures. |
| [DrawPolygon](../../aspose.imaging/graphics/drawpolygon#drawpolygon_1)(Pen, Point[]) | Dessine un polygone défini par un tableau de[`Point`](../point) structures. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle)(Pen, Rectangle) | Dessine un rectangle spécifié par un[`Rectangle`](../rectangle) structure. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle_1)(Pen, RectangleF) | Dessine un rectangle spécifié par un[`RectangleF`](../rectanglef) structure. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle_3)(Pen, float, float, float, float) | Dessine un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle_2)(Pen, int, int, int, int) | Dessine un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [DrawRectangles](../../aspose.imaging/graphics/drawrectangles#drawrectangles)(Pen, RectangleF[]) | Dessine une série de rectangles spécifiés par[`RectangleF`](../rectanglef) structures. |
| [DrawRectangles](../../aspose.imaging/graphics/drawrectangles#drawrectangles_1)(Pen, Rectangle[]) | Dessine une série de rectangles spécifiés par[`Rectangle`](../rectangle) structures. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring)(string, Font, Brush, PointF) | Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec le[`Brush`](../brush) et[`Font`](../font) objets. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_2)(string, Font, Brush, RectangleF) | Dessine la chaîne de texte spécifiée dans le rectangle spécifié avec le[`Brush`](../brush) et[`Font`](../font) objets. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_4)(string, Font, Brush, float, float) | Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec le[`Brush`](../brush) et[`Font`](../font) objets. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_1)(string, Font, Brush, PointF, StringFormat) | Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec le[`Brush`](../brush) et[`Font`](../font) objets utilisant les attributs de mise en forme du spécifié[`StringFormat`](../stringformat) . |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | Dessine la chaîne de texte spécifiée dans le rectangle spécifié avec le[`Brush`](../brush) et[`Font`](../font) objets utilisant les attributs de mise en forme du spécifié[`StringFormat`](../stringformat) . |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_5)(string, Font, Brush, float, float, StringFormat) | Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec le[`Brush`](../brush) et[`Font`](../font) objets utilisant les attributs de mise en forme du spécifié[`StringFormat`](../stringformat) . |
| [EndUpdate](../../aspose.imaging/graphics/endupdate)() | Termine la mise en cache des opérations graphiques démarrées après l'appel de BeginUpdate. Les opérations graphiques précédentes seront appliquées immédiatement lors de l'appel de cette méthode. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve)(Brush, PointF[]) | Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de[`PointF`](../pointf) structures. Cette méthode utilise une tension par défaut de 0,5 etAlternate mode de remplissage. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_3)(Brush, Point[]) | Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de[`Point`](../point) structures. Cette méthode utilise une tension par défaut de 0,5 etAlternate mode de remplissage. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_1)(Brush, PointF[], FillMode) | Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de[`PointF`](../pointf) structures utilisant le mode de remplissage spécifié. Cette méthode utilise une tension par défaut de 0,5. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_4)(Brush, Point[], FillMode) | Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de[`Point`](../point) structures utilisant le mode de remplissage spécifié. Cette méthode utilise une tension par défaut de 0,5. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de[`PointF`](../pointf) structures utilisant le mode de remplissage et la tension spécifiés. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_5)(Brush, Point[], FillMode, float) | Remplit l'intérieur d'une courbe spline cardinale fermée définie par un tableau de[`Point`](../point) structures utilisant le mode de remplissage et la tension spécifiés. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse)(Brush, Rectangle) | Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par un[`Rectangle`](../rectangle) structure. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse_1)(Brush, RectangleF) | Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par un[`RectangleF`](../rectanglef) structure. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse_3)(Brush, float, float, float, float) | Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse_2)(Brush, int, int, int, int) | Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [FillPath](../../aspose.imaging/graphics/fillpath)(Brush, GraphicsPath) | Remplit l'intérieur d'un[`GraphicsPath`](../graphicspath) . |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie)(Brush, Rectangle, float, float) | Remplit l'intérieur d'une section circulaire définie par une ellipse spécifiée par un[`RectangleF`](../rectanglef) structure et deux lignes radiales. |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie_1)(Brush, RectangleF, float, float) | Remplit l'intérieur d'une section circulaire définie par une ellipse spécifiée par un[`RectangleF`](../rectanglef) structure et deux lignes radiales. |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie_3)(Brush, float, float, float, float, float, float) | Remplit l'intérieur d'une section circulaire définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales. |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie_2)(Brush, int, int, int, int, int, int) | Remplit l'intérieur d'une section circulaire définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales. |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon)(Brush, PointF[]) | Remplit l'intérieur d'un polygone défini par un tableau de points spécifié par[`PointF`](../pointf) structures etAlternate . |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon_2)(Brush, Point[]) | Remplit l'intérieur d'un polygone défini par un tableau de points spécifié par[`Point`](../point) structures etAlternate . |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon_1)(Brush, PointF[], FillMode) | Remplit l'intérieur d'un polygone défini par un tableau de points spécifié par[`PointF`](../pointf) structures utilisant le mode de remplissage spécifié. |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon_3)(Brush, Point[], FillMode) | Remplit l'intérieur d'un polygone défini par un tableau de points spécifié par[`Point`](../point) structures utilisant le mode de remplissage spécifié. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle)(Brush, Rectangle) | Remplit l'intérieur d'un rectangle spécifié par un[`Rectangle`](../rectangle) structure. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle_1)(Brush, RectangleF) | Remplit l'intérieur d'un rectangle spécifié par un[`RectangleF`](../rectanglef) structure. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle_3)(Brush, float, float, float, float) | Remplit l'intérieur d'un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle_2)(Brush, int, int, int, int) | Remplit l'intérieur d'un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [FillRectangles](../../aspose.imaging/graphics/fillrectangles#fillrectangles)(Brush, RectangleF[]) | Remplit l'intérieur d'une série de rectangles spécifiés par[`RectangleF`](../rectanglef) structures. |
| [FillRectangles](../../aspose.imaging/graphics/fillrectangles#fillrectangles_1)(Brush, Rectangle[]) | Remplit l'intérieur d'une série de rectangles spécifiés par[`Rectangle`](../rectangle) structures. |
| [FillRegion](../../aspose.imaging/graphics/fillregion)(Brush, Region) | Remplit l'intérieur d'un[`Region`](../region) . |
| [MeasureString](../../aspose.imaging/graphics/measurestring)(string, Font, SizeF, StringFormat) | Mesure la chaîne de texte spécifiée avec les paramètres spécifiés |
| [MultiplyTransform](../../aspose.imaging/graphics/multiplytransform#multiplytransform)(Matrix) | Multiplie le[`Matrix`](../matrix) qui représente la transformée géométrique locale de ce[`Graphics`](../graphics) par le spécifié[`Matrix`](../matrix) en préfixant le spécifié[`Matrix`](../matrix) . |
| [MultiplyTransform](../../aspose.imaging/graphics/multiplytransform#multiplytransform_1)(Matrix, MatrixOrder) | Multiplie le[`Matrix`](../matrix) qui représente la transformée géométrique locale de ce[`Graphics`](../graphics) par le spécifié[`Matrix`](../matrix) dans l'ordre spécifié. |
| [ResetTransform](../../aspose.imaging/graphics/resettransform)() | Réinitialise le[`Transform`](./transform) propriété à l'identité. |
| [RotateTransform](../../aspose.imaging/graphics/rotatetransform#rotatetransform)(float) | Fait pivoter la transformation géométrique locale de la quantité spécifiée. Cette méthode ajoute la rotation à la transformation. |
| [RotateTransform](../../aspose.imaging/graphics/rotatetransform#rotatetransform_1)(float, MatrixOrder) | Fait pivoter la transformation géométrique locale de la quantité spécifiée dans l'ordre spécifié. |
| [ScaleTransform](../../aspose.imaging/graphics/scaletransform#scaletransform)(float, float) | Met à l'échelle la transformation géométrique locale selon les quantités spécifiées. Cette méthode ajoute la matrice de mise à l'échelle à la transformation. |
| [ScaleTransform](../../aspose.imaging/graphics/scaletransform#scaletransform_1)(float, float, MatrixOrder) | Met à l'échelle la transformation géométrique locale selon les quantités spécifiées dans l'ordre spécifié. |
| [TranslateTransform](../../aspose.imaging/graphics/translatetransform#translatetransform)(float, float) | Traduit la transformation géométrique locale par les dimensions spécifiées. Cette méthode ajoute la traduction au début de la transformation. |
| [TranslateTransform](../../aspose.imaging/graphics/translatetransform#translatetransform_1)(float, float, MatrixOrder) | Traduit la transformation géométrique locale par les dimensions spécifiées dans l'ordre spécifié. |

### Exemples

Cet exemple utilise la classe Graphics pour créer des formes primitives sur la surface Image. Pour illustrer l'opération, l'exemple crée une nouvelle image au format PNG et dessine des formes primitives sur la surface de l'image à l'aide des méthodes Draw exposées par la classe Graphics

```csharp
[C#]

// Crée une instance de FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.png", System.IO.FileMode.Create))
{
    //Créer une instance de PngOptions et définir ses différentes propriétés
    Aspose.Imaging.ImageOptions.PngOptions pngOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    //Définir la source pour PngOptions
    pngOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Créer une instance de Image 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(pngOptions, 500, 500))
    {
        //Créer et initialiser une instance de la classe Graphics
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Effacer la surface graphique
        graphics.Clear(Aspose.Imaging.Color.Wheat);

        // Dessine un arc en spécifiant l'objet Pen de couleur noire, 
        //un rectangle entourant l'arc, l'angle de départ et l'angle de balayage
        graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), new Aspose.Imaging.Rectangle(200, 200, 100, 200), 0, 300);

        // Dessinez un Bézier en spécifiant l'objet Pen ayant la couleur bleue et les points de coordonnées.
        graphics.DrawBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Point(250, 100), new Aspose.Imaging.Point(300, 30), new Aspose.Imaging.Point(450, 100), new Aspose.Imaging.Point(235, 25));

        // Dessinez une courbe en spécifiant l'objet Pen de couleur verte et un tableau de points
        graphics.DrawCurve(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new[] { new Aspose.Imaging.Point(100, 200), new Aspose.Imaging.Point(100, 350), new Aspose.Imaging.Point(200, 450) });

        // Dessine une ellipse à l'aide de l'objet Pen et d'un rectangle environnant
        graphics.DrawEllipse(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 2), new Aspose.Imaging.Rectangle(300, 300, 100, 100));

        //Tracer une ligne 
        graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Violet, 2), new Aspose.Imaging.Point(100, 100), new Aspose.Imaging.Point(200, 200));

        // Dessine un segment de tarte
        graphics.DrawPie(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Silver, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(200, 20), new Aspose.Imaging.Size(200, 200)), 0, 45);

        // Dessinez un polygone en spécifiant l'objet Pen de couleur rouge et un tableau de points
        graphics.DrawPolygon(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2), new[] { new Aspose.Imaging.Point(20, 100), new Aspose.Imaging.Point(20, 200), new Aspose.Imaging.Point(220, 20) });

        // Dessine un rectangle
        graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(100, 100)));

        //Créer un objet SolidBrush et définir ses différentes propriétés
        Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush();
        brush.Color = Color.Purple;
        brush.Opacity = 100;

        // Dessine une chaîne à l'aide de l'objet SolidBrush et de la police, à un point spécifique
        graphics.DrawString("This image is created by Aspose.Imaging API", new Aspose.Imaging.Font("Times New Roman", 16), brush, new Aspose.Imaging.PointF(50, 400));

        // Enregistrer toutes les modifications.
        image.Save();
    }
}
```

### Voir également

* espace de noms [Aspose.Imaging](../../aspose.imaging)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
