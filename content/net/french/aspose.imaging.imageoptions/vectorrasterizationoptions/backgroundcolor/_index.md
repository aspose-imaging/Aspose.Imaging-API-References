---
title: BackgroundColor
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Obtient ou définit une couleur darrière-plan.
type: docs
weight: 20
url: /fr/aspose.imaging.imageoptions/vectorrasterizationoptions/backgroundcolor/
---
## VectorRasterizationOptions.BackgroundColor property

Obtient ou définit une couleur d'arrière-plan.

```csharp
public Color BackgroundColor { get; set; }
```

### Exemples

Cet exemple montre comment charger une image WMF à partir d'un fichier et la convertir en SVG à l'aide de WmfRasterizationOptions.

```csharp
[C#]

string dir = "c:\\temp\\";

// Utiliser Aspose.Imaging.Image.Load est un moyen unifié de charger tous les types d'images, y compris WMF.
using (Aspose.Imaging.FileFormats.Wmf.WmfImage wmfImage = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "test.wmf"))
{
    Aspose.Imaging.ImageOptions.SvgOptions saveOptions = new Aspose.Imaging.ImageOptions.SvgOptions();
        
    // Le texte sera converti en formes.
    saveOptions.TextAsShapes = true;

    Aspose.Imaging.ImageOptions.WmfRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions();

    // La couleur de fond de la surface de dessin.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.WhiteSmoke;

    // La taille de la page.
    rasterizationOptions.PageSize = wmfImage.Size;

    // Si emf intégré existe, alors rend emf ; sinon rendre wmf.
    rasterizationOptions.RenderMode = Aspose.Imaging.FileFormats.Wmf.WmfRenderMode.Auto;

    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    wmfImage.Save(dir + "test.output.svg", saveOptions);
}
```

Cet exemple montre comment charger une image EMF à partir d'un fichier et la convertir en SVG à l'aide d'EmfRasterizationOptions.

```csharp
[C#]

string dir = "c:\\temp\\";

// Utiliser Aspose.Imaging.Image.Load est un moyen unifié de charger tous les types d'images, y compris EMF.
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
    Aspose.Imaging.ImageOptions.SvgOptions saveOptions = new Aspose.Imaging.ImageOptions.SvgOptions();

    // Le texte sera converti en formes.
    saveOptions.TextAsShapes = true;

    Aspose.Imaging.ImageOptions.EmfRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions();

    // La couleur de fond de la surface de dessin.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.WhiteSmoke;

    // La taille de la page.
    rasterizationOptions.PageSize = emfImage.Size;

    // Si emf intégré existe, alors rend emf ; sinon rendre wmf.
    rasterizationOptions.RenderMode = Aspose.Imaging.FileFormats.Emf.EmfRenderMode.Auto;

    // Définit la marge horizontale
    rasterizationOptions.BorderX = 50;

    // Fixe la marge verticale
    rasterizationOptions.BorderY = 50;

    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    emfImage.Save(dir + "test.output.svg", saveOptions);
}
```

Cet exemple montre comment charger une image SVG à partir d'un fichier et la pixelliser en PNG à l'aide de diverses options.

```csharp
[C#]

string dir = "c:\\temp\\";

// Utiliser Aspose.Imaging.Image.Load est un moyen unifié de charger l'image.
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = (Aspose.Imaging.FileFormats.Svg.SvgImage)Aspose.Imaging.Image.Load(dir + "test.svg"))
{
    // Afin de pixelliser SVG, nous devons spécifier les options de pixellisation.
    Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();

    // Définit la couleur par défaut d'un arrière-plan pour une image. La valeur par défaut est le blanc.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.Gray;

    // Définir la taille de la page
    rasterizationOptions.PageSize = svgImage.Size;

    // L'anticrénelage est appliqué aux lignes et aux courbes et aux bords des zones remplies.
    rasterizationOptions.SmoothingMode = Aspose.Imaging.SmoothingMode.AntiAlias;

    // Chaque caractère est dessiné en utilisant son bitmap de glyphe anticrénelé sans indice.
    rasterizationOptions.TextRenderingHint = Aspose.Imaging.TextRenderingHint.AntiAlias;

    // Réduit la taille de l'image 10 fois, c'est-à-dire que la taille de sortie sera de 10 % de la taille d'origine.
    rasterizationOptions.ScaleX = 0.1f;
    rasterizationOptions.ScaleY = 0.1f;

    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    // Enregistrer dans un fichier PNG
    svgImage.Save(dir + "test.output.png", saveOptions);
}
```

### Voir également

* struct [Color](../../../aspose.imaging/color)
* class [VectorRasterizationOptions](../../vectorrasterizationoptions)
* espace de noms [Aspose.Imaging.ImageOptions](../../vectorrasterizationoptions)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
