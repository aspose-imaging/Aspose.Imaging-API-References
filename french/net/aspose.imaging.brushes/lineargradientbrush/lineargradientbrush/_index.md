---
title: LinearGradientBrush
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Initialise une nouvelle instance duLinearGradientBrushaspose.imaging.brushes/lineargradientbrush classe avec les paramètres par défaut. La couleur de départ est le noir la couleur de fin est le blanc langle est de 45 degrés et le rectangle est situé en 00 avec la taille 11.
type: docs
weight: 10
url: /fr/net/aspose.imaging.brushes/lineargradientbrush/lineargradientbrush/
---
## LinearGradientBrush() {#constructor}

Initialise une nouvelle instance du[`LinearGradientBrush`](../../lineargradientbrush) classe avec les paramètres par défaut. La couleur de départ est le noir, la couleur de fin est le blanc, l'angle est de 45 degrés et le rectangle est situé en (0,0) avec la taille (1,1).

```csharp
public LinearGradientBrush()
```

### Voir également

* class [LinearGradientBrush](../../lineargradientbrush)
* espace de noms [Aspose.Imaging.Brushes](../../lineargradientbrush)
* Assemblée [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Point, Point, Color, Color) {#constructor_1}

Initialise une nouvelle instance du[`LinearGradientBrush`](../../lineargradientbrush) classe avec les points et couleurs spécifiés.

```csharp
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| point1 | Point | UN[`Point`](../../../aspose.imaging/point) structure qui représente le point de départ du gradient linéaire. |
| point2 | Point | UN[`Point`](../../../aspose.imaging/point) structure qui représente le point final du gradient linéaire. |
| color1 | Color | UN[`Color`](../../../aspose.imaging/color) structure qui représente la couleur de départ du dégradé linéaire. |
| color2 | Color | UN[`Color`](../../../aspose.imaging/color) structure qui représente la couleur finale du dégradé linéaire. |

### Exemples

L'exemple suivant montre comment créer une copie en niveaux de gris d'un cadre existant et l'ajouter à une image TIFF.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Crée une source de fichier permanente et non temporaire.
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // Le dégradé linéaire du coin supérieur gauche au coin inférieur droit de l'image.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(tiffImage.Width, tiffImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Remplir le cadre actif avec un pinceau dégradé linéaire.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(tiffImage.ActiveFrame);
    gr.FillRectangle(brush, tiffImage.Bounds);

    // Options de niveaux de gris
    Aspose.Imaging.ImageOptions.TiffOptions createTiffFrameOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());
    createTiffFrameOptions.Photometric = Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;
    createTiffFrameOptions.BitsPerSample = new ushort[] { 8 };

    // Crée une copie en niveaux de gris du cadre actif.
    // Les données de pixel sont conservées mais converties au format souhaité.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame grayscaleFrame = Aspose.Imaging.FileFormats.Tiff.TiffFrame.CreateFrameFrom(tiffImage.ActiveFrame, createTiffFrameOptions);

    // Ajoute le cadre nouvellement créé à l'image TIFF.
    tiffImage.AddFrame(grayscaleFrame);

    tiffImage.Save();
}
```

### Voir également

* struct [Point](../../../aspose.imaging/point)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* espace de noms [Aspose.Imaging.Brushes](../../lineargradientbrush)
* Assemblée [Aspose.Imaging](../../../)

---

## LinearGradientBrush(PointF, PointF, Color, Color) {#constructor_2}

Initialise une nouvelle instance du[`LinearGradientBrush`](../../lineargradientbrush) classe avec les points et couleurs spécifiés.

```csharp
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| point1 | PointF | UN[`PointF`](../../../aspose.imaging/pointf) structure qui représente le point de départ du gradient linéaire. |
| point2 | PointF | UN[`PointF`](../../../aspose.imaging/pointf) structure qui représente le point final du gradient linéaire. |
| color1 | Color | UN[`Color`](../../../aspose.imaging/color) structure qui représente la couleur de départ du dégradé linéaire. |
| color2 | Color | UN[`Color`](../../../aspose.imaging/color) structure qui représente la couleur finale du dégradé linéaire. |

### Voir également

* struct [PointF](../../../aspose.imaging/pointf)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* espace de noms [Aspose.Imaging.Brushes](../../lineargradientbrush)
* Assemblée [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Rectangle, Color, Color, float) {#constructor_3}

Initialise une nouvelle instance du[`LinearGradientBrush`](../../lineargradientbrush) classe basée sur un rectangle, des couleurs de début et de fin et un angle d'orientation.

```csharp
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| rect | Rectangle | UN[`RectangleF`](../../../aspose.imaging/rectanglef) structure qui spécifie les limites du gradient linéaire. |
| color1 | Color | UN[`Color`](../../../aspose.imaging/color) structure qui représente la couleur de départ du dégradé. |
| color2 | Color | UN[`Color`](../../../aspose.imaging/color) structure qui représente la couleur de fin du dégradé. |
| angle | Single | Angle, mesuré en degrés dans le sens des aiguilles d'une montre à partir de l'axe des x, de la ligne d'orientation du dégradé. |

### Voir également

* struct [Rectangle](../../../aspose.imaging/rectangle)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* espace de noms [Aspose.Imaging.Brushes](../../lineargradientbrush)
* Assemblée [Aspose.Imaging](../../../)

---

## LinearGradientBrush(RectangleF, Color, Color, float) {#constructor_5}

Initialise une nouvelle instance du[`LinearGradientBrush`](../../lineargradientbrush) classe basée sur un rectangle, des couleurs de début et de fin et un angle d'orientation.

```csharp
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| rect | RectangleF | UN[`RectangleF`](../../../aspose.imaging/rectanglef) structure qui spécifie les limites du gradient linéaire. |
| color1 | Color | UN[`Color`](../../../aspose.imaging/color) structure qui représente la couleur de départ du dégradé. |
| color2 | Color | UN[`Color`](../../../aspose.imaging/color) structure qui représente la couleur de fin du dégradé. |
| angle | Single | Angle, mesuré en degrés dans le sens des aiguilles d'une montre à partir de l'axe des x, de la ligne d'orientation du dégradé. |

### Voir également

* struct [RectangleF](../../../aspose.imaging/rectanglef)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* espace de noms [Aspose.Imaging.Brushes](../../lineargradientbrush)
* Assemblée [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Rectangle, Color, Color, float, bool) {#constructor_4}

Initialise une nouvelle instance du[`LinearGradientBrush`](../../lineargradientbrush) classe basée sur un rectangle, des couleurs de début et de fin et un angle d'orientation.

```csharp
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, 
    bool isAngleScalable)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| rect | Rectangle | UN[`RectangleF`](../../../aspose.imaging/rectanglef) structure qui spécifie les limites du gradient linéaire. |
| color1 | Color | UN[`Color`](../../../aspose.imaging/color) structure qui représente la couleur de départ du dégradé. |
| color2 | Color | UN[`Color`](../../../aspose.imaging/color) structure qui représente la couleur de fin du dégradé. |
| angle | Single | Angle, mesuré en degrés dans le sens des aiguilles d'une montre à partir de l'axe des x, de la ligne d'orientation du dégradé. |
| isAngleScalable | Boolean | si réglé sur`vrai` l'angle est modifié lors des transformations avec ceci[`LinearGradientBrush`](../../lineargradientbrush). |

### Voir également

* struct [Rectangle](../../../aspose.imaging/rectangle)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* espace de noms [Aspose.Imaging.Brushes](../../lineargradientbrush)
* Assemblée [Aspose.Imaging](../../../)

---

## LinearGradientBrush(RectangleF, Color, Color, float, bool) {#constructor_6}

Initialise une nouvelle instance du[`LinearGradientBrush`](../../lineargradientbrush) classe basée sur un rectangle, des couleurs de début et de fin et un angle d'orientation.

```csharp
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, 
    bool isAngleScalable)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| rect | RectangleF | UN[`RectangleF`](../../../aspose.imaging/rectanglef) structure qui spécifie les limites du gradient linéaire. |
| color1 | Color | UN[`Color`](../../../aspose.imaging/color) structure qui représente la couleur de départ du dégradé. |
| color2 | Color | UN[`Color`](../../../aspose.imaging/color) structure qui représente la couleur de fin du dégradé. |
| angle | Single | Angle, mesuré en degrés dans le sens des aiguilles d'une montre à partir de l'axe des x, de la ligne d'orientation du dégradé. |
| isAngleScalable | Boolean | si réglé sur`vrai` l'angle est modifié lors des transformations avec ceci[`LinearGradientBrush`](../../lineargradientbrush). |

### Voir également

* struct [RectangleF](../../../aspose.imaging/rectanglef)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* espace de noms [Aspose.Imaging.Brushes](../../lineargradientbrush)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
