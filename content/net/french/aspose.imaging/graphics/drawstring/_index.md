---
title: DrawString
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Dessine la chaîne de texte spécifiée à lemplacement spécifié avec leBrushaspose.imaging/brush etFontaspose.imaging/font objets.
type: docs
weight: 320
url: /fr/aspose.imaging/graphics/drawstring/
---
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec le[`Brush`](../../brush) et[`Font`](../../font) objets.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| s | String | Chaîne à dessiner. |
| font | Font | [`Font`](../../font) qui définit le format de texte de la chaîne. |
| brush | Brush | [`Brush`](../../brush) qui détermine la couleur et la texture du texte dessiné. |
| x | Single | Coordonnée x du coin supérieur gauche du texte dessiné. |
| y | Single | Coordonnée y du coin supérieur gauche du texte dessiné. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* est nul. -ou- *s* est nul. |

### Voir également

* class [Font](../../font)
* class [Brush](../../brush)
* class [Graphics](../../graphics)
* espace de noms [Aspose.Imaging](../../graphics)
* Assemblée [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec le[`Brush`](../../brush) et[`Font`](../../font) objets.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| s | String | Chaîne à dessiner. |
| font | Font | [`Font`](../../font) qui définit le format de texte de la chaîne. |
| brush | Brush | [`Brush`](../../brush) qui détermine la couleur et la texture du texte dessiné. |
| point | PointF | [`PointF`](../../pointf) structure qui spécifie le coin supérieur gauche du texte dessiné. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* est nul. -ou- *s* est nul. |

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

* class [Font](../../font)
* class [Brush](../../brush)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* espace de noms [Aspose.Imaging](../../graphics)
* Assemblée [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec le[`Brush`](../../brush) et[`Font`](../../font) objets utilisant les attributs de mise en forme du spécifié[`StringFormat`](../../stringformat) .

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| s | String | Chaîne à dessiner. |
| font | Font | [`Font`](../../font) qui définit le format de texte de la chaîne. |
| brush | Brush | [`Brush`](../../brush) qui détermine la couleur et la texture du texte dessiné. |
| x | Single | Coordonnée x du coin supérieur gauche du texte dessiné. |
| y | Single | Coordonnée y du coin supérieur gauche du texte dessiné. |
| format | StringFormat | [`StringFormat`](../../stringformat) qui spécifie les attributs de mise en forme, tels que l'interligne et l'alignement, qui sont appliqués au texte dessiné. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* est nul. -ou- *s* est nul. |

### Voir également

* class [Font](../../font)
* class [Brush](../../brush)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* espace de noms [Aspose.Imaging](../../graphics)
* Assemblée [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec le[`Brush`](../../brush) et[`Font`](../../font) objets utilisant les attributs de mise en forme du spécifié[`StringFormat`](../../stringformat) .

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| s | String | Chaîne à dessiner. |
| font | Font | [`Font`](../../font) qui définit le format de texte de la chaîne. |
| brush | Brush | [`Brush`](../../brush) qui détermine la couleur et la texture du texte dessiné. |
| point | PointF | [`PointF`](../../pointf) structure qui spécifie le coin supérieur gauche du texte dessiné. |
| format | StringFormat | [`StringFormat`](../../stringformat) qui spécifie les attributs de mise en forme, tels que l'interligne et l'alignement, qui sont appliqués au texte dessiné. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* est nul. -ou- *s* est nul. |

### Voir également

* class [Font](../../font)
* class [Brush](../../brush)
* struct [PointF](../../pointf)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* espace de noms [Aspose.Imaging](../../graphics)
* Assemblée [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

Dessine la chaîne de texte spécifiée dans le rectangle spécifié avec le[`Brush`](../../brush) et[`Font`](../../font) objets.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| s | String | Chaîne à dessiner. |
| font | Font | [`Font`](../../font) qui définit le format de texte de la chaîne. |
| brush | Brush | [`Brush`](../../brush) qui détermine la couleur et la texture du texte dessiné. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef) structure qui spécifie l'emplacement du texte dessiné. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* est nul. -ou- *s* est nul. |

### Voir également

* class [Font](../../font)
* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* espace de noms [Aspose.Imaging](../../graphics)
* Assemblée [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

Dessine la chaîne de texte spécifiée dans le rectangle spécifié avec le[`Brush`](../../brush) et[`Font`](../../font) objets utilisant les attributs de mise en forme du spécifié[`StringFormat`](../../stringformat) .

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| s | String | Chaîne à dessiner. |
| font | Font | [`Font`](../../font) qui définit le format de texte de la chaîne. |
| brush | Brush | [`Brush`](../../brush) qui détermine la couleur et la texture du texte dessiné. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef) structure qui spécifie l'emplacement du texte dessiné. |
| format | StringFormat | [`StringFormat`](../../stringformat) qui spécifie les attributs de mise en forme, tels que l'interligne et l'alignement, qui sont appliqués au texte dessiné. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* est nul. -ou- *s* est nul. -ou- *brush* est nul. |

### Voir également

* class [Font](../../font)
* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* espace de noms [Aspose.Imaging](../../graphics)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
