---
title: StreamSource
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Initialise une nouvelle instance duStreamSourceaspose.imaging.sources/streamsource classe.
type: docs
weight: 10
url: /fr/net/aspose.imaging.sources/streamsource/streamsource/
---
## StreamSource(Stream) {#constructor}

Initialise une nouvelle instance du[`StreamSource`](../../streamsource) classe.

```csharp
public StreamSource(Stream stream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux à ouvrir. |

### Exemples

Cet exemple montre comment charger les informations de pixel dans un tableau de type couleur, manipuler le tableau et le redéfinir sur l'image. Pour effectuer ces opérations, cet exemple crée un nouveau fichier Image (au format GIF) utilisant l'objet MemoryStream.

```csharp
[C#]

//Créer une instance de MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Créer une instance de GifOptions et définir ses différentes propriétés, y compris la propriété Source
    Aspose.Imaging.ImageOptions.GifOptions gifOptions = new Aspose.Imaging.ImageOptions.GifOptions();
    gifOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Créer une instance de Image
    using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(gifOptions, 500, 500))
    {
        // Récupère les pixels de l'image en spécifiant la zone comme limite de l'image
        Aspose.Imaging.Color[] pixels = image.LoadPixels(image.Bounds);

        // Boucle sur le tableau et définit la couleur du pixel indexé alternatif
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                // Définit la couleur du pixel indexé sur jaune
                pixels[index] = Aspose.Imaging.Color.Yellow;
            }
            else
            {
                // Définit la couleur du pixel indexé sur bleu
                pixels[index] = Aspose.Imaging.Color.Blue;
            }
        }

        //Appliquer les changements de pixel à l'image
        image.SavePixels(image.Bounds, pixels);

        // Enregistrer toutes les modifications.
        image.Save();
    }

    // Écrire MemoryStream dans le fichier
    using (System.IO.FileStream fileStream = new System.IO.FileStream(@"C:\temp\output.gif", System.IO.FileMode.Create))
    {
        stream.WriteTo(fileStream);
    }   
}
```

### Voir également

* class [StreamSource](../../streamsource)
* espace de noms [Aspose.Imaging.Sources](../../streamsource)
* Assemblée [Aspose.Imaging](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

Initialise une nouvelle instance du[`StreamSource`](../../streamsource) classe.

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux à ouvrir. |
| disposeStream | Boolean | si réglé sur`vrai` le flux sera éliminé. |

### Exemples

Cet exemple montre l'utilisation de System.IO.Stream pour créer un nouveau fichier image (un type JPEG)

```csharp
[C#]

// Crée une instance de JpegOptions et définit ses différentes propriétés
Aspose.Imaging.ImageOptions.JpegOptions jpegOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

//Créer une instance de System.IO.Stream
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.jpeg", System.IO.FileMode.Create);

//Définir la propriété source pour l'instance de JpegOptions
// Le deuxième paramètre booléen détermine si le flux est éliminé une fois sorti de la portée
jpegOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream, true);

// Crée une instance de Image et appelle la méthode Create avec JpegOptions comme paramètre pour initialiser l'objet Image   
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(jpegOptions, 500, 500))
{
    // faire du traitement d'image
}
```

### Voir également

* class [StreamSource](../../streamsource)
* espace de noms [Aspose.Imaging.Sources](../../streamsource)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
