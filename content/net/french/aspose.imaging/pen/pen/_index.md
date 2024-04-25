---
title: Pen
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Initialise une nouvelle instance duPenaspose.imaging/pen classe avec la couleur spécifiée.
type: docs
weight: 10
url: /fr/aspose.imaging/pen/pen/
---
## Pen(Color) {#constructor_2}

Initialise une nouvelle instance du[`Pen`](../../pen) classe avec la couleur spécifiée.

```csharp
public Pen(Color color)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| color | Color | UN[`Color`](../color) structure qui indique la couleur de ce[`Pen`](../../pen). |

### Voir également

* struct [Color](../../color)
* class [Pen](../../pen)
* espace de noms [Aspose.Imaging](../../pen)
* Assemblée [Aspose.Imaging](../../../)

---

## Pen(Color, float) {#constructor_3}

Initialise une nouvelle instance du[`Pen`](../../pen) classe avec le spécifié[`Color`](../color) et[`Width`](../width) propriétés.

```csharp
public Pen(Color color, float width)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| color | Color | UN[`Color`](../color) structure qui indique la couleur de ce[`Pen`](../../pen). |
| width | Single | Une valeur indiquant la largeur de ce[`Pen`](../../pen). |

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

* struct [Color](../../color)
* class [Pen](../../pen)
* espace de noms [Aspose.Imaging](../../pen)
* Assemblée [Aspose.Imaging](../../../)

---

## Pen(Brush) {#constructor}

Initialise une nouvelle instance du[`Pen`](../../pen) classe avec le spécifié[`Brush`](../brush) .

```csharp
public Pen(Brush brush)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| brush | Brush | UN[`Brush`](../brush) qui détermine les propriétés de remplissage de ce[`Pen`](../../pen). |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* est nul. |

### Voir également

* class [Brush](../../brush)
* class [Pen](../../pen)
* espace de noms [Aspose.Imaging](../../pen)
* Assemblée [Aspose.Imaging](../../../)

---

## Pen(Brush, float) {#constructor_1}

Initialise une nouvelle instance du[`Pen`](../../pen) classe avec le spécifié[`Brush`](../brush) et[`Width`](../width) .

```csharp
public Pen(Brush brush, float width)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| brush | Brush | UN[`Brush`](../brush) qui détermine les caractéristiques de ce[`Pen`](../../pen). |
| width | Single | La largeur du nouveau[`Pen`](../../pen). |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* est nul. |

### Voir également

* class [Brush](../../brush)
* class [Pen](../../pen)
* espace de noms [Aspose.Imaging](../../pen)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
