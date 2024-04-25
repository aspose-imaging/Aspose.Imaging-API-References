---
title: Rectangle
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Stocke un ensemble de quatre nombres entiers qui représentent lemplacement et la taille dun rectangle.
type: docs
weight: 10830
url: /fr/aspose.imaging/rectangle/
---
## Rectangle structure

Stocke un ensemble de quatre nombres entiers qui représentent l'emplacement et la taille d'un rectangle.

```csharp
public struct Rectangle
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Rectangle](rectangle#constructor)(Point, Size) | Initialise une nouvelle instance du[`Rectangle`](../rectangle) structure avec l'emplacement et la taille spécifiés. |
| [Rectangle](rectangle#constructor_1)(int, int, int, int) | Initialise une nouvelle instance du[`Rectangle`](../rectangle) structure avec l'emplacement et la taille spécifiés. |

## Propriétés

| Nom | La description |
| --- | --- |
| static [Empty](../../aspose.imaging/rectangle/empty) { get; } | Obtient une nouvelle instance du[`Rectangle`](../rectangle) structure qui a[`X`](./x) ,[`Y`](./y) ,[`Width`](./width) et[`Height`](./height) valeurs mises à zéro. |
| [Bottom](../../aspose.imaging/rectangle/bottom) { get; set; } | Obtient ou définit la coordonnée y qui est la somme des[`Y`](./y) et[`Height`](./height) valeurs de propriété de ce[`Rectangle`](../rectangle) structure. |
| [Height](../../aspose.imaging/rectangle/height) { get; set; } | Obtient ou définit la hauteur de ce[`Rectangle`](../rectangle) structure. |
| [IsEmpty](../../aspose.imaging/rectangle/isempty) { get; } | Obtient une valeur indiquant si toutes les propriétés numériques de ce[`Rectangle`](../rectangle) ont des valeurs de zéro. |
| [Left](../../aspose.imaging/rectangle/left) { get; set; } | Obtient ou définit la coordonnée x du bord gauche de ce[`Rectangle`](../rectangle) structure. |
| [Location](../../aspose.imaging/rectangle/location) { get; set; } | Obtient ou définit les coordonnées du coin supérieur gauche de cette[`Rectangle`](../rectangle) structure. |
| [Right](../../aspose.imaging/rectangle/right) { get; set; } | Obtient ou définit la coordonnée x qui est la somme de[`X`](./x) et[`Width`](./width) valeurs de propriété de ce[`Rectangle`](../rectangle) structure. |
| [Size](../../aspose.imaging/rectangle/size) { get; set; } | Obtient ou définit la taille de ce[`Rectangle`](../rectangle) . |
| [Top](../../aspose.imaging/rectangle/top) { get; set; } | Obtient ou définit la coordonnée y du bord supérieur de ce[`Rectangle`](../rectangle) structure. |
| [Width](../../aspose.imaging/rectangle/width) { get; set; } | Obtient ou définit la largeur de cette[`Rectangle`](../rectangle) structure. |
| [X](../../aspose.imaging/rectangle/x) { get; set; } | Obtient ou définit la coordonnée x du coin supérieur gauche de cette[`Rectangle`](../rectangle) structure. |
| [Y](../../aspose.imaging/rectangle/y) { get; set; } | Obtient ou définit la coordonnée y du coin supérieur gauche de ce[`Rectangle`](../rectangle) structure. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [Ceiling](../../aspose.imaging/rectangle/ceiling)(RectangleF) | Convertit le spécifié[`RectangleF`](../rectanglef) structurer à un[`Rectangle`](../rectangle) structure en arrondissant[`RectangleF`](../rectanglef) valeurs aux valeurs entières immédiatement supérieures. |
| static [FromLeftTopRightBottom](../../aspose.imaging/rectangle/fromlefttoprightbottom)(int, int, int, int) | Crée un[`Rectangle`](../rectangle) structure avec les emplacements de bord spécifiés. |
| static [FromPoints](../../aspose.imaging/rectangle/frompoints)(Point, Point) | Crée un nouveau[`Rectangle`](../rectangle) à partir de deux points spécifiés. Deux verticales du créé[`Rectangle`](../rectangle) sera égal au passé*point1* et*point2* . Il s'agirait généralement des sommets opposés. |
| static [Inflate](../../aspose.imaging/rectangle/inflate)(Rectangle, int, int) | Crée et renvoie une copie gonflée du spécifié[`Rectangle`](../rectangle) structure. La copie est gonflée du montant spécifié. L'original[`Rectangle`](../rectangle) la structure reste inchangée. |
| static [Intersect](../../aspose.imaging/rectangle/intersect)(Rectangle, Rectangle) | Renvoie un tiers[`Rectangle`](../rectangle) structure qui représente l'intersection de deux autres[`Rectangle`](../rectangle) structures. S'il n'y a pas d'intersection, un vide[`Rectangle`](../rectangle) est renvoyé. |
| static [Round](../../aspose.imaging/rectangle/round)(RectangleF) | Convertit le spécifié[`RectangleF`](../rectanglef) à un[`Rectangle`](../rectangle) en arrondissant le[`RectangleF`](../rectanglef)valeurs aux valeurs entières les plus proches. |
| static [Truncate](../../aspose.imaging/rectangle/truncate)(RectangleF) | Convertit le spécifié[`RectangleF`](../rectanglef) à un[`Rectangle`](../rectangle) en tronquant le[`RectangleF`](../rectanglef) valeurs. |
| static [Union](../../aspose.imaging/rectangle/union)(Rectangle, Rectangle) | Obtient un[`Rectangle`](../rectangle) structure qui contient l'union de deux[`Rectangle`](../rectangle) structures. |
| [Contains](../../aspose.imaging/rectangle/contains#contains)(Point) | Détermine si le point spécifié est contenu dans ce[`Rectangle`](../rectangle) structure. |
| [Contains](../../aspose.imaging/rectangle/contains#contains_1)(Rectangle) | Détermine si la région rectangulaire représentée par*rect* est entièrement contenu dans ce[`Rectangle`](../rectangle) structure. |
| [Contains](../../aspose.imaging/rectangle/contains#contains_2)(int, int) | Détermine si le point spécifié est contenu dans ce[`Rectangle`](../rectangle) structure. |
| override [Equals](../../aspose.imaging/rectangle/equals)(object) | Teste si*obj* est un[`Rectangle`](../rectangle)structure avec le même emplacement et la même taille que celle-ci[`Rectangle`](../rectangle) structure. |
| override [GetHashCode](../../aspose.imaging/rectangle/gethashcode)() | Renvoie le code de hachage pour ce[`Rectangle`](../rectangle) structure. |
| [Inflate](../../aspose.imaging/rectangle/inflate#inflate)(Size) | Gonfle ça[`Rectangle`](../rectangle) par le montant spécifié. |
| [Inflate](../../aspose.imaging/rectangle/inflate#inflate_1)(int, int) | Gonfle ça[`Rectangle`](../rectangle) par le montant spécifié. |
| [Intersect](../../aspose.imaging/rectangle/intersect)(Rectangle) | Remplace ceci[`Rectangle`](../rectangle) avec l'intersection de lui-même et du spécifié[`Rectangle`](../rectangle) . |
| [IntersectsWith](../../aspose.imaging/rectangle/intersectswith)(Rectangle) | Détermine si ce rectangle coupe avec*rect* . |
| [Normalize](../../aspose.imaging/rectangle/normalize)() | Normalise le rectangle en rendant sa largeur et sa hauteur positives, gauche moins que droite et haut moins que bas. |
| [Offset](../../aspose.imaging/rectangle/offset#offset)(Point) | Ajuste l'emplacement de ce rectangle du montant spécifié. |
| [Offset](../../aspose.imaging/rectangle/offset#offset_1)(int, int) | Ajuste l'emplacement de ce rectangle du montant spécifié. |
| override [ToString](../../aspose.imaging/rectangle/tostring)() | Convertit les attributs de ce[`Rectangle`](../rectangle) en une chaîne lisible par l'homme. |
| [operator ==](../../aspose.imaging/rectangle/op_equality) | Teste si deux[`Rectangle`](../rectangle)les structures ont un emplacement et une taille égaux. |
| [operator !=](../../aspose.imaging/rectangle/op_inequality) | Teste si deux[`Rectangle`](../rectangle) les structures diffèrent par leur emplacement ou leur taille. |

### Voir également

* espace de noms [Aspose.Imaging](../../aspose.imaging)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
