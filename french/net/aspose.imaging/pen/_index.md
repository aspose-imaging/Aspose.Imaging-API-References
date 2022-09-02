---
title: Pen
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Définit un objet utilisé pour dessiner des lignes des courbes et des figures.
type: docs
weight: 10690
url: /fr/net/aspose.imaging/pen/
---
## Pen class

Définit un objet utilisé pour dessiner des lignes, des courbes et des figures.

```csharp
public class Pen : TransparencySupporter
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Pen](pen#constructor)(Brush) | Initialise une nouvelle instance du[`Pen`](../pen) classe avec le spécifié[`Brush`](./brush) . |
| [Pen](pen#constructor_2)(Color) | Initialise une nouvelle instance du[`Pen`](../pen) classe avec la couleur spécifiée. |
| [Pen](pen#constructor_1)(Brush, float) | Initialise une nouvelle instance du[`Pen`](../pen) classe avec le spécifié[`Brush`](./brush) et[`Width`](./width) . |
| [Pen](pen#constructor_3)(Color, float) | Initialise une nouvelle instance du[`Pen`](../pen) classe avec le spécifié[`Color`](./color) et[`Width`](./width) propriétés. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Alignment](../../aspose.imaging/pen/alignment) { get; set; } | Obtient ou définit l'alignement pour ce[`Pen`](../pen) . |
| [Brush](../../aspose.imaging/pen/brush) { get; set; } | Obtient ou définit le[`Brush`](./brush) qui détermine les attributs de ce[`Pen`](../pen) . |
| [Color](../../aspose.imaging/pen/color) { get; set; } | Obtient ou définit la couleur de ce[`Pen`](../pen) . |
| [CompoundArray](../../aspose.imaging/pen/compoundarray) { get; set; } | Obtient ou définit un tableau de valeurs qui spécifie un stylo composé. Un stylo composé dessine une ligne composée composée de lignes parallèles et d'espaces. |
| [CustomEndCap](../../aspose.imaging/pen/customendcap) { get; set; } | Obtient ou définit une limite personnalisée à utiliser à la fin des lignes dessinées avec ce[`Pen`](../pen) . |
| [CustomStartCap](../../aspose.imaging/pen/customstartcap) { get; set; } | Obtient ou définit une limite personnalisée à utiliser au début des lignes dessinées avec ce[`Pen`](../pen) . |
| [DashCap](../../aspose.imaging/pen/dashcap) { get; set; } | Obtient ou définit le style de majuscule utilisé à la fin des tirets qui composent les lignes pointillées dessinées avec ce[`Pen`](../pen) . |
| [DashOffset](../../aspose.imaging/pen/dashoffset) { get; set; } | Obtient ou définit la distance entre le début d'une ligne et le début d'un motif en tirets. |
| [DashPattern](../../aspose.imaging/pen/dashpattern) { get; set; } | Obtient ou définit un tableau de tirets et d'espaces personnalisés. |
| [DashStyle](../../aspose.imaging/pen/dashstyle) { get; set; } | Obtient ou définit le style utilisé pour les lignes en pointillés dessinées avec ce[`Pen`](../pen) . |
| [EndCap](../../aspose.imaging/pen/endcap) { get; set; } | Obtient ou définit le style de majuscule utilisé à la fin des lignes dessinées avec ce[`Pen`](../pen) . |
| [LineJoin](../../aspose.imaging/pen/linejoin) { get; set; } | Obtient ou définit le style de jointure pour les extrémités de deux lignes consécutives dessinées avec ce[`Pen`](../pen) . |
| [MiterLimit](../../aspose.imaging/pen/miterlimit) { get; set; } | Obtient ou définit la limite de l'épaisseur de la jointure sur un coin en onglet. |
| [Opacity](../../aspose.imaging/transparencysupporter/opacity) { get; set; } | Obtient ou définit l'opacité de l'objet. La valeur doit être comprise entre 0 et 1. La valeur 0 signifie que l'objet est entièrement visible, la valeur 1 signifie que l'objet est entièrement opaque. |
| [PenType](../../aspose.imaging/pen/pentype) { get; } | Obtient le style des lignes dessinées avec ceci[`Pen`](../pen) . |
| [StartCap](../../aspose.imaging/pen/startcap) { get; set; } | Obtient ou définit le style de majuscule utilisé au début des lignes dessinées avec ce[`Pen`](../pen) . |
| [Transform](../../aspose.imaging/pen/transform) { get; set; } | Obtient ou définit une copie de la transformation géométrique pour ce[`Pen`](../pen) . |
| [Width](../../aspose.imaging/pen/width) { get; set; } | Obtient ou définit la largeur de cette[`Pen`](../pen) , en unités de l'objet Graphics utilisé pour le dessin. |

## Méthodes

| Nom | La description |
| --- | --- |
| [MultiplyTransform](../../aspose.imaging/pen/multiplytransform#multiplytransform)(Matrix) | Multiplie la matrice de transformation pour cette[`Pen`](../pen) par le spécifié[`Matrix`](../matrix) . |
| [MultiplyTransform](../../aspose.imaging/pen/multiplytransform#multiplytransform_1)(Matrix, MatrixOrder) | Multiplie la matrice de transformation pour cette[`Pen`](../pen) par le spécifié[`Matrix`](../matrix) dans l'ordre spécifié. |
| [ResetTransform](../../aspose.imaging/pen/resettransform)() | Réinitialise la matrice de transformation géométrique pour ce[`Pen`](../pen) à l'identité. |
| [RotateTransform](../../aspose.imaging/pen/rotatetransform#rotatetransform)(float) | Fait pivoter la transformation géométrique locale selon l'angle spécifié. Cette méthode ajoute la rotation à la transformation. |
| [RotateTransform](../../aspose.imaging/pen/rotatetransform#rotatetransform_1)(float, MatrixOrder) | Fait pivoter la transformation géométrique locale de l'angle spécifié dans l'ordre spécifié. |
| [ScaleTransform](../../aspose.imaging/pen/scaletransform#scaletransform)(float, float) | Met à l'échelle la transformation géométrique locale par les facteurs spécifiés. Cette méthode ajoute la matrice de mise à l'échelle à la transformation. |
| [ScaleTransform](../../aspose.imaging/pen/scaletransform#scaletransform_1)(float, float, MatrixOrder) | Met à l'échelle la transformation géométrique locale par les facteurs spécifiés dans l'ordre spécifié. |
| [SetLineCap](../../aspose.imaging/pen/setlinecap)(LineCap, LineCap, DashCap) | Définit les valeurs qui déterminent le style de capuchon utilisé pour terminer les lignes dessinées par ce[`Pen`](../pen) . |
| [TranslateTransform](../../aspose.imaging/pen/translatetransform#translatetransform)(float, float) | Traduit la transformation géométrique locale par les dimensions spécifiées. Cette méthode ajoute la traduction à la transformation. |
| [TranslateTransform](../../aspose.imaging/pen/translatetransform#translatetransform_1)(float, float, MatrixOrder) | Traduit la transformation géométrique locale par les dimensions spécifiées dans l'ordre spécifié. |

### Exemples

Cet exemple montre la création et l'utilisation des objets Pen. L'exemple crée une nouvelle image et dessine des rectangles sur la surface de l'image.

```csharp
[C#]

//Créer une instance de BmpOptions et définir ses différentes propriétés
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//Créer une instance de FileCreateSource et l'affecter comme Source pour l'instance de BmpOptions
// Le deuxième paramètre booléen détermine si le fichier à créer est temporel ou non
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\sample.bmp", false);

//Créer une instance de Image au chemin spécifié
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //Créer une instance de Graphics et l'initialiser avec l'objet Image
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    //Effacer la surface graphique avec la couleur blanche
    graphics.Clear(Aspose.Imaging.Color.White);

    //Crée une instance de Pen avec la couleur Rouge et la largeur 5
    Aspose.Imaging.Pen pen = new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 5f);

    //Créer une instance de HatchBrush et définir ses propriétés
    Aspose.Imaging.Brushes.HatchBrush brush = new Aspose.Imaging.Brushes.HatchBrush();
    brush.BackgroundColor = Aspose.Imaging.Color.Wheat;
    brush.ForegroundColor = Aspose.Imaging.Color.Red;

    //Créer une instance de Pen
    // l'initialise avec l'objet HatchBrush et sa largeur
    Aspose.Imaging.Pen brusedpen = new Pen(brush, 5);

    // Dessiner des rectangles en spécifiant l'objet Pen
    graphics.DrawRectangles(pen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(210, 210), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 310), new Aspose.Imaging.Size(100, 100))
    });

    // Dessiner des rectangles en spécifiant l'objet Pen
    graphics.DrawRectangles(brusedpen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 310), new Aspose.Imaging.Size(100, 100))
    });

    // Enregistrer toutes les modifications.
    image.Save();
}
```

### Voir également

* class [TransparencySupporter](../transparencysupporter)
* espace de noms [Aspose.Imaging](../../aspose.imaging)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
