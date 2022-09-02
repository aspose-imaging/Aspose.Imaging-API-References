---
title: Region
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Décrit lintérieur dune forme graphique composée de rectangles et de chemins. Cette classe ne peut pas être héritée.
type: docs
weight: 10850
url: /fr/net/aspose.imaging/region/
---
## Region class

Décrit l'intérieur d'une forme graphique composée de rectangles et de chemins. Cette classe ne peut pas être héritée.

```csharp
public sealed class Region
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Region](region#constructor)() | Initialise un nouveau[`Region`](../region) . |
| [Region](region#constructor_1)(GraphicsPath) | Initialise un nouveau[`Region`](../region) avec le spécifié[`GraphicsPath`](../graphicspath) . |
| [Region](region#constructor_2)(Rectangle) | Initialise un nouveau[`Region`](../region) à partir du spécifié[`Rectangle`](../rectangle) structure. |
| [Region](region#constructor_3)(RectangleF) | Initialise un nouveau[`Region`](../region) à partir du spécifié[`RectangleF`](../rectanglef) structure. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Complement](../../aspose.imaging/region/complement#complement)(GraphicsPath) | Met à jour ceci[`Region`](../region) pour contenir la partie du spécifié[`GraphicsPath`](../graphicspath) qui ne se croise pas avec ça[`Region`](../region) . |
| [Complement](../../aspose.imaging/region/complement#complement_1)(Rectangle) | Met à jour ceci[`Region`](../region) pour contenir la partie du spécifié[`Rectangle`](../rectangle) structure qui ne se croise pas avec cette[`Region`](../region) . |
| [Complement](../../aspose.imaging/region/complement#complement_2)(RectangleF) | Met à jour ceci[`Region`](../region) pour contenir la partie du spécifié[`RectangleF`](../rectanglef) structure qui ne se croise pas avec cette[`Region`](../region) . |
| [Complement](../../aspose.imaging/region/complement#complement_3)(Region) | Met à jour ceci[`Region`](../region) pour contenir la partie du spécifié[`Region`](../region) qui ne se croise pas avec ça[`Region`](../region) . |
| [DeepClone](../../aspose.imaging/region/deepclone)() | Crée une copie profonde exacte de ceci[`Region`](../region) . |
| [Equals](../../aspose.imaging/region/equals#equals)(Region, Graphics) | Teste si le spécifié[`Region`](../region) est identique à celui-ci[`Region`](../region) sur la surface de dessin spécifiée. |
| [Exclude](../../aspose.imaging/region/exclude#exclude)(GraphicsPath) | Met à jour ceci[`Region`](../region) ne contenir que la partie de son intérieur qui ne croise pas le spécifié[`GraphicsPath`](../graphicspath) . |
| [Exclude](../../aspose.imaging/region/exclude#exclude_1)(Rectangle) | Met à jour ceci[`Region`](../region) ne contenir que la partie de son intérieur qui ne croise pas le spécifié[`Rectangle`](../rectangle) structure. |
| [Exclude](../../aspose.imaging/region/exclude#exclude_2)(RectangleF) | Met à jour ceci[`Region`](../region) ne contenir que la partie de son intérieur qui ne croise pas le spécifié[`RectangleF`](../rectanglef) structure. |
| [Exclude](../../aspose.imaging/region/exclude#exclude_3)(Region) | Met à jour ceci[`Region`](../region) ne contenir que la partie de son intérieur qui ne croise pas le spécifié[`Region`](../region) . |
| [Intersect](../../aspose.imaging/region/intersect#intersect)(GraphicsPath) | Met à jour ceci[`Region`](../region) à l'intersection de lui-même avec le spécifié[`GraphicsPath`](../graphicspath) . |
| [Intersect](../../aspose.imaging/region/intersect#intersect_1)(Rectangle) | Met à jour ceci[`Region`](../region) à l'intersection de lui-même avec le spécifié[`Rectangle`](../rectangle) structure. |
| [Intersect](../../aspose.imaging/region/intersect#intersect_2)(RectangleF) | Met à jour ceci[`Region`](../region) à l'intersection de lui-même avec le spécifié[`RectangleF`](../rectanglef) structure. |
| [Intersect](../../aspose.imaging/region/intersect#intersect_3)(Region) | Met à jour ceci[`Region`](../region) à l'intersection de lui-même avec le spécifié[`Region`](../region) . |
| [IsEmpty](../../aspose.imaging/region/isempty)(Graphics) | Teste si cela[`Region`](../region) a un intérieur vide sur la surface de dessin spécifiée. |
| [IsInfinite](../../aspose.imaging/region/isinfinite)(Graphics) | Teste si cela[`Region`](../region) a un intérieur infini sur la surface de dessin spécifiée. |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible)(Point) | Teste si le spécifié[`Point`](../point) structure est contenue dans ce[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_2)(PointF) | Teste si le spécifié[`PointF`](../pointf) structure est contenue dans ce[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_4)(Rectangle) | Teste si une partie de la valeur spécifiée[`Rectangle`](../rectangle) structure est contenue dans ce[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_6)(RectangleF) | Teste si une partie de la valeur spécifiée[`RectangleF`](../rectanglef) structure est contenue dans ce[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_11)(float, float) | Teste si le point spécifié est contenu dans ce[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_1)(Point, Graphics) | Teste si le spécifié[`Point`](../point) structure est contenue dans ce[`Region`](../region)lorsqu'il est dessiné en utilisant le spécifié[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_3)(PointF, Graphics) | Teste si le spécifié[`PointF`](../pointf) structure est contenue dans ce[`Region`](../region)lorsqu'il est dessiné en utilisant le spécifié[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_5)(Rectangle, Graphics) | Teste si une partie de la valeur spécifiée[`Rectangle`](../rectangle) structure est contenue dans ce[`Region`](../region)lorsqu'il est dessiné en utilisant le spécifié[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_7)(RectangleF, Graphics) | Teste si une partie de la valeur spécifiée[`RectangleF`](../rectanglef) structure est contenue dans ce[`Region`](../region)lorsqu'il est dessiné en utilisant le spécifié[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_12)(float, float, Graphics) | Teste si le point spécifié est contenu dans ce[`Region`](../region)lorsqu'il est dessiné en utilisant le spécifié[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_8)(int, int, Graphics) | Teste si le point spécifié est contenu dans ce[`Region`](../region) objet lorsqu'il est dessiné à l'aide de l'objet spécifié[`Graphics`](../graphics) objet. |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_13)(float, float, float, float) | Teste si une partie du rectangle spécifié est contenue dans ce[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_9)(int, int, int, int) | Teste si une partie du rectangle spécifié est contenue dans ce[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_14)(float, float, float, float, Graphics) | Teste si une partie du rectangle spécifié est contenue dans ce[`Region`](../region)lorsqu'il est dessiné en utilisant le spécifié[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_10)(int, int, int, int, Graphics) | Teste si une partie du rectangle spécifié est contenue dans ce[`Region`](../region)lorsqu'il est dessiné en utilisant le spécifié[`Graphics`](../graphics) . |
| [MakeEmpty](../../aspose.imaging/region/makeempty)() | Initialise ceci[`Region`](../region) à un intérieur vide. |
| [MakeInfinite](../../aspose.imaging/region/makeinfinite)() | Initialise ceci[`Region`](../region) objet à un intérieur infini. |
| [Transform](../../aspose.imaging/region/transform)(Matrix) | Transforme ceci[`Region`](../region) par le spécifié[`Matrix`](../matrix) . |
| [Translate](../../aspose.imaging/region/translate#translate_1)(float, float) | Décale les coordonnées de ce[`Region`](../region) par le montant spécifié. |
| [Translate](../../aspose.imaging/region/translate#translate)(int, int) | Décale les coordonnées de ce[`Region`](../region) par le montant spécifié. |
| [Union](../../aspose.imaging/region/union#union)(GraphicsPath) | Met à jour ceci[`Region`](../region) à l'union de lui-même et du spécifié[`GraphicsPath`](../graphicspath) . |
| [Union](../../aspose.imaging/region/union#union_1)(Rectangle) | Met à jour ceci[`Region`](../region) à l'union de lui-même et du spécifié[`Rectangle`](../rectangle) structure. |
| [Union](../../aspose.imaging/region/union#union_2)(RectangleF) | Met à jour ceci[`Region`](../region) à l'union de lui-même et du spécifié[`RectangleF`](../rectanglef) structure. |
| [Union](../../aspose.imaging/region/union#union_3)(Region) | Met à jour ceci[`Region`](../region) à l'union de lui-même et du spécifié[`Region`](../region) . |
| [Xor](../../aspose.imaging/region/xor#xor)(GraphicsPath) | Met à jour ceci[`Region`](../region) à l'union moins l'intersection de lui-même avec le spécifié[`GraphicsPath`](../graphicspath) . |
| [Xor](../../aspose.imaging/region/xor#xor_1)(Rectangle) | Met à jour ceci[`Region`](../region) à l'union moins l'intersection de lui-même avec le spécifié[`Rectangle`](../rectangle) structure. |
| [Xor](../../aspose.imaging/region/xor#xor_2)(RectangleF) | Met à jour ceci[`Region`](../region) à l'union moins l'intersection de lui-même avec le spécifié[`RectangleF`](../rectanglef) structure. |
| [Xor](../../aspose.imaging/region/xor#xor_3)(Region) | Met à jour ceci[`Region`](../region) à l'union moins l'intersection de lui-même avec le spécifié[`Region`](../region) . |

### Voir également

* espace de noms [Aspose.Imaging](../../aspose.imaging)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
