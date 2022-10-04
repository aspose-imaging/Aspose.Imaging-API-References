---
title: MaxMemoryForCache
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Obtient ou définit la mémoire maximale disponible pour le cache en mémoire. La valeur spécifiée est le nombre de mégaoctets.
type: docs
weight: 70
url: /fr/net/aspose.imaging/cache/maxmemoryforcache/
---
## Cache.MaxMemoryForCache property

Obtient ou définit la mémoire maximale disponible pour le cache en mémoire. La valeur spécifiée est le nombre de mégaoctets.

```csharp
public static int MaxMemoryForCache { get; set; }
```

### Valeur de la propriété

La mémoire maximale pour le cache.

### Remarques

La valeur 0 consommera toute la mémoire disponible et ne servira pas de limite supérieure.

### Exemples

Cet exemple illustre l'utilisation de Aspose.Imaging.Cache

```csharp
[C#]

// Par défaut, le dossier de cache est défini sur le répertoire temporaire local de l'utilisateur.
// Vous pouvez également spécifier un autre dossier de cache que celui par défaut comme suit :
// Cache.CacheFolder = @"D:\\MaTemp" ;

// Le mode automatique est flexible et efficace
Aspose.Imaging.Cache.CacheType = Aspose.Imaging.CacheType.Auto;

// La valeur par défaut est 0, ce qui signifie qu'il n'y a pas de limite supérieure
Aspose.Imaging.Cache.MaxDiskSpaceForCache = 1073741824; // 1 gigaoctet
Aspose.Imaging.Cache.MaxMemoryForCache = 1073741824; // 1 gigaoctet

// Il n'est pas recommandé de modifier la propriété suivante car cela peut grandement affecter les performances
Aspose.Imaging.Cache.ExactReallocateOnly = false;

// A tout moment, vous pouvez vérifier le nombre d'octets actuellement alloués pour la mémoire ou le disque 
// cache en examinant les propriétés suivantes
long l1 = Aspose.Imaging.Cache.AllocatedDiskBytesCount;
long l2 = Aspose.Imaging.Cache.AllocatedMemoryBytesCount;

// Effectuez un traitement d'image comme ci-dessous
Aspose.Imaging.ImageOptions.GifOptions options = new Aspose.Imaging.ImageOptions.GifOptions();
options.Palette = new ColorPalette(new Aspose.Imaging.Color[] { Aspose.Imaging.Color.Red, Aspose.Imaging.Color.Blue, Aspose.Imaging.Color.Black, Aspose.Imaging.Color.White });
options.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(options, 100, 100))
{
    Aspose.Imaging.Color[] pixels = new Aspose.Imaging.Color[10000];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Aspose.Imaging.Color.White;
    }

    image.SavePixels(image.Bounds, pixels);

    // après avoir exécuté le code ci-dessus, 40 000 octets seront alloués en mémoire.
    long diskBytes = Aspose.Imaging.Cache.AllocatedDiskBytesCount;
    long memoryBytes = Aspose.Imaging.Cache.AllocatedMemoryBytesCount;
}

// Les propriétés d'allocation peuvent être utilisées pour vérifier si tous les objets Aspose.Imaging ont été correctement éliminés.
// Si vous avez oublié d'appeler dispose sur un objet, les valeurs du cache seront différentes de 0.            
l1 = Aspose.Imaging.Cache.AllocatedDiskBytesCount;
l2 = Aspose.Imaging.Cache.AllocatedMemoryBytesCount;
```

### Voir également

* class [Cache](../../cache)
* espace de noms [Aspose.Imaging](../../cache)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->