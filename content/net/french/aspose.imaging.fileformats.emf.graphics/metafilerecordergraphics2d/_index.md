---
title: MetafileRecorderGraphics2D
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lenregistreur de métafichiers graphics
type: docs
weight: 6500
url: /fr/aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/
---
## MetafileRecorderGraphics2D class

L'enregistreur de métafichiers graphics

```csharp
public abstract class MetafileRecorderGraphics2D
```

## Propriétés

| Nom | La description |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/backgroundcolor) { get; set; } | Obtient ou définit la couleur de l'arrière-plan. |
| [Clip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clip) { get; set; } | Obtient ou définit une région qui limite la zone de dessin de ce Graphics |
| [ClipBounds](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clipbounds) { get; } | Obtient les limites du clip. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Clear](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clear)() | Efface l'état de l'objet graphique |
| [DrawArc](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawarc)(Pen, Rectangle, float, float) | Dessine un arc représentant une portion d'ellipse spécifiée par une structure Rectangle. |
| [DrawCubicBezier](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawcubicbezier)(Pen, Point, Point, Point, Point) | Dessine le cube de Bézier. |
| [DrawEllipse](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawellipse)(Pen, Rectangle) | Dessine l'ellipse. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage#drawimage)(RasterImage, Point) | Dessine l'image spécifiée, en utilisant sa taille physique d'origine, à l'emplacement spécifié. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage#drawimage_2)(byte[], Rectangle, GraphicsUnit) | Dessine l'image. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage#drawimage_3)(Stream, Rectangle, GraphicsUnit) | Dessine l'image. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage#drawimage_1)(RasterImage, Rectangle, Rectangle, GraphicsUnit) | Dessine la partie spécifiée de l'image spécifiée à l'emplacement spécifié et avec la taille spécifiée. |
| [DrawLine](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawline#drawline)(Pen, Point, Point) | Dessine la ligne. |
| [DrawLine](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawline#drawline_1)(Pen, int, int, int, int) | Dessine la ligne. |
| [DrawPath](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpath)(Pen, GraphicsPath) | Dessine le chemin. |
| [DrawPie](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpie)(Pen, Rectangle, float, float) | Dessine le gâteau. |
| [DrawPolyCubicBezier](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolycubicbezier)(Pen, Point[]) | Dessine le Bézier polycubique. |
| [DrawPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolygon)(Pen, Point[]) | Dessine le polygone. |
| [DrawPolyline](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolyline)(Pen, Point[]) | Dessine la polyligne. |
| [DrawRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawrectangle#drawrectangle)(Pen, Rectangle) | Dessine le rectangle. |
| [DrawRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawrectangle#drawrectangle_1)(Pen, int, int, int, int) | Dessine le rectangle. |
| [DrawString](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawstring#drawstring)(string, Font, Color, int, int) | Dessine la chaîne. |
| [DrawString](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawstring#drawstring_1)(string, Font, Color, int, int, float) | Dessine la chaîne. |
| [ExcludeClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/excludeclip#excludeclip)(Rectangle) | Met à jour la zone de découpage de ce Graphics pour exclure la zone spécifiée par une structure Rectangle. |
| [ExcludeClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/excludeclip#excludeclip_1)(Region) | Met à jour la zone de découpage de ce graphique pour exclure la zone spécifiée par une région. |
| [FillEllipse](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillellipse)(Brush, Rectangle) | Remplit l'ellipse. |
| [FillPath](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpath)(Pen, Brush, GraphicsPath) | Remplit le chemin. |
| [FillPie](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpie)(Brush, Rectangle, float, float) | Remplit le gâteau. |
| [FillPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpolygon#fillpolygon)(Brush, Point[]) | Remplit le polygone. |
| [FillPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpolygon#fillpolygon_1)(Brush, Point[], FillMode) | Remplit le polygone. |
| [FillRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillrectangle)(Brush, Rectangle) | Remplit le rectangle. |
| [GetTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/gettransform)() | Obtient la transformation du monde. |
| [IntersectClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/intersectclip#intersectclip)(RectangleF) | Met à jour la région de découpage de ce Graphics à l'intersection de la région de découpage actuelle et de la structure Rectangle spécifiée. |
| [IntersectClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/intersectclip#intersectclip_1)(Region) | Met à jour la région de découpage de ce Graphics à l'intersection de la région de découpage actuelle et de la région spécifiée. |
| [MultiplyTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/multiplytransform#multiplytransform)(Matrix) | Multiplie la transformation mondiale de ce graphique et spécifie la matrice. |
| [MultiplyTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/multiplytransform#multiplytransform_1)(Matrix, MatrixOrder) | Multiplie la transformation mondiale de ce graphique et spécifie la matrice dans l'ordre spécifié. |
| [ResetClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/resetclip)() | Réinitialise le clip. |
| [RotateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/rotatetransform#rotatetransform)(float) | Applique la rotation spécifiée à la matrice de transformation de ce Graphics. |
| [RotateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/rotatetransform#rotatetransform_1)(float, PointF, MatrixOrder) | Applique la rotation spécifiée à la matrice de transformation de ce graphique dans l'ordre spécifié. |
| [ScaleTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/scaletransform#scaletransform)(float, float) | Applique l'opération de mise à l'échelle spécifiée à la matrice de transformation de ce graphique en l'ajoutant à la matrice de transformation de l'objet. |
| [ScaleTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/scaletransform#scaletransform_1)(float, float, MatrixOrder) | Applique l'opération de mise à l'échelle spécifiée à la matrice de transformation de ce graphique dans l'ordre spécifié. |
| [SetTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/settransform)(Matrix) | Définit la transformation. |
| [TranslateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/translatetransform#translatetransform)(float, float) | Modifie l'origine du système de coordonnées en ajoutant la traduction spécifiée au début de la matrice de transformation de ce Graphics. |
| [TranslateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/translatetransform#translatetransform_1)(float, float, MatrixOrder) | Modifie l'origine du système de coordonnées en appliquant la translation spécifiée à la matrice de transformation de ce graphique dans l'ordre spécifié. |

### Voir également

* espace de noms [Aspose.Imaging.FileFormats.Emf.Graphics](../../aspose.imaging.fileformats.emf.graphics)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
