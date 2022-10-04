---
title: NormalizeAngle
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Normalise langle. Cette méthode est applicable aux documents texte numérisés pour se débarrasser de la numérisation biaisée. Cette méthode utiliseGetSkewAngleaspose.imaging/rasterimage/getskewangle etRotateaspose.imaging/rasterimage/rotate méthodes.
type: docs
weight: 430
url: /fr/net/aspose.imaging/rasterimage/normalizeangle/
---
## NormalizeAngle() {#normalizeangle}

Normalise l'angle. Cette méthode est applicable aux documents texte numérisés pour se débarrasser de la numérisation biaisée. Cette méthode utilise[`GetSkewAngle`](../getskewangle) et[`Rotate`](../rotate) méthodes.

```csharp
public void NormalizeAngle()
```

### Voir également

* class [RasterImage](../../rasterimage)
* espace de noms [Aspose.Imaging](../../rasterimage)
* Assemblée [Aspose.Imaging](../../../)

---

## NormalizeAngle(bool, Color) {#normalizeangle_1}

Normalise l'angle. Cette méthode est applicable aux documents texte numérisés pour se débarrasser de la numérisation biaisée. Cette méthode utilise[`GetSkewAngle`](../getskewangle) et[`Rotate`](../rotate) méthodes.

```csharp
public virtual void NormalizeAngle(bool resizeProportionally, Color backgroundColor)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| resizeProportionally | Boolean | si réglé sur`vrai` la taille de votre image sera modifiée en fonction des projections du rectangle pivoté (points d'angle) dans un autre cas qui laisse les dimensions intactes et seul le contenu de l'image interne est pivoté. |
| backgroundColor | Color | Couleur du fond. |

### Exemples

L'inclinaison est un artefact qui peut apparaître pendant le processus de numérisation du document lorsque le texte/les images du document sont légèrement pivotés. Cela peut avoir diverses causes, mais la plus courante est que le papier est égaré lors d'une numérisation. Par conséquent, le redressement est le processus de détection et de résolution de ce problème sur les fichiers numérisés (c'est-à-dire bitmap) afin que les documents redressés aient le texte/les images correctement et horizontalement ajustés.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3567\\";

string inputFilePath = dir + "skewed.png";
string outputFilePath = dir + "skewed.out.png";

// Débarrassez-vous de l'analyse biaisée avec les paramètres par défaut
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(inputFilePath))
{
    // Redresser
    image.NormalizeAngle(false /*do not resize*/, Aspose.Imaging.Color.LightGray /*background color*/);
    image.Save(outputFilePath);
}
```

### Voir également

* struct [Color](../../color)
* class [RasterImage](../../rasterimage)
* espace de noms [Aspose.Imaging](../../rasterimage)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->