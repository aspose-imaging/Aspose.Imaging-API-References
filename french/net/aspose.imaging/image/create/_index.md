---
title: Create
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Crée une nouvelle image en utilisant les options de création spécifiées.
type: docs
weight: 10
url: /fr/net/aspose.imaging/image/create/
---
## Create(ImageOptionsBase, int, int) {#create}

Crée une nouvelle image en utilisant les options de création spécifiées.

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | Les options d'image. |
| width | Int32 | La largeur. |
| height | Int32 | La hauteur. |

### Return_Value

L'image nouvellement créée.

### Exemples

Cet exemple crée un nouveau fichier image à un emplacement du disque spécifié par la propriété Source de l'instance BmpOptions. Plusieurs propriétés pour l'instance BmpOptions sont définies avant de créer l'image réelle. Surtout la propriété Source, qui fait référence à l'emplacement réel du disque dans ce cas.

```csharp
[C#]

//Créer une instance de BmpOptions et définir ses différentes propriétés
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//Créer une instance de FileCreateSource et l'affecter comme Source pour l'instance de BmpOptions
// Le deuxième paramètre booléen détermine si le fichier à créer est temporel ou non
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\output.bmp", false);

//Créer une instance de Image et l'initialiser avec une instance de BmpOptions en appelant la méthode Create
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    // faire du traitement d'image

    // Enregistrer toutes les modifications
    image.Save();
}
```

### Voir également

* class [ImageOptionsBase](../../imageoptionsbase)
* class [Image](../../image)
* espace de noms [Aspose.Imaging](../../image)
* Assemblée [Aspose.Imaging](../../../)

---

## Create(Image[]) {#create_1}

Crée une nouvelle image en utilisant les images spécifiées comme pages

```csharp
public static Image Create(Image[] images)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| images | Image[] | Les images. |

### Return_Value

L'image comme IMultipageImage

### Voir également

* class [Image](../../image)
* espace de noms [Aspose.Imaging](../../image)
* Assemblée [Aspose.Imaging](../../../)

---

## Create(Image[], bool) {#create_2}

Crée une nouvelle image les images spécifiées en tant que pages.

```csharp
public static Image Create(Image[] images, bool disposeImages)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| images | Image[] | Les images. |
| disposeImages | Boolean | si réglé sur`vrai` [disposer des images]. |

### Return_Value

L'image comme IMultipageImage

### Voir également

* class [Image](../../image)
* espace de noms [Aspose.Imaging](../../image)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
