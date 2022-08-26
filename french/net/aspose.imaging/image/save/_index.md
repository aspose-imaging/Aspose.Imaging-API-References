---
title: Save
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Enregistre les données dimage dans le flux sous-jacent.
type: docs
weight: 240
url: /fr/net/aspose.imaging/image/save/
---
## Save() {#save}

Enregistre les données d'image dans le flux sous-jacent.

```csharp
public void Save()
```

### Exemples

L'exemple suivant montre comment enregistrer une image BMP entière ou une partie de celle-ci dans un fichier ou un flux.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Convertir en une image noir-blanc
    bmpImage.BinarizeOtsu();

    // Enregistrer au même emplacement avec les options par défaut.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Une palette ne contient que deux couleurs : Noir et Blanc dans ce cas.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // Pour toutes les images monochromes (y compris celles en noir et blanc), il suffit d'allouer 1 bit par pixel.
    saveOptions.BitsPerPixel = 1;

    // Enregistrer à un autre emplacement avec les options spécifiées.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Enregistre uniquement la partie centrale de l'image.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Enregistre l'intégralité de l'image dans un flux mémoire
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Enregistre la partie centrale de l'image dans un flux mémoire
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//La sortie peut ressembler à ceci :
//La taille de l'image entière en octets : 24062
//La taille de la partie centrale de l'image en octets : 6046
```

### Voir également

* class [Image](../../image)
* espace de noms [Aspose.Imaging](../../image)
* Assemblée [Aspose.Imaging](../../../)

---

## Save(string) {#save_4}

Enregistre l'image à l'emplacement de fichier spécifié.

```csharp
public override void Save(string filePath)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Chemin d'accès au fichier dans lequel enregistrer l'image. |

### Voir également

* class [Image](../../image)
* espace de noms [Aspose.Imaging](../../image)
* Assemblée [Aspose.Imaging](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier spécifié en fonction des options d'enregistrement.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier. |
| options | ImageOptionsBase | Les options. |

### Exemples

L'exemple suivant charge une image BMP à partir d'un fichier, puis enregistre l'image dans un fichier PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Enregistre l'intégralité de l'image dans un fichier PNG.
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    image.Save(dir + "output.png", saveOptions);
}
```

Cet exemple montre les étapes simples pour enregistrer une image. Pour illustrer cette opération, nous chargeons un fichier existant à partir d'un emplacement de disque, effectuons une opération de rotation sur l'image et enregistrons l'image au format PSD en utilisant le chemin du fichier

```csharp
[C#]

string dir = "c:\\temp\\";

//Créer une instance de la classe d'image et l'initialiser avec un fichier existant via le chemin du fichier
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    //Faire pivoter l'image à 180 degrés autour de l'axe X
    image.RotateFlip(Aspose.Imaging.RotateFlipType.Rotate180FlipX);

    // Enregistrez l'image au format PSD dans le chemin du fichier avec les paramètres PsdOptions par défaut
    image.Save(dir + "output.psd", new Aspose.Imaging.ImageOptions.PsdOptions());
}
```

L'exemple suivant montre comment enregistrer une image BMP entière ou une partie de celle-ci dans un fichier ou un flux.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Convertir en une image noir-blanc
    bmpImage.BinarizeOtsu();

    // Enregistrer au même emplacement avec les options par défaut.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Une palette ne contient que deux couleurs : Noir et Blanc dans ce cas.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // Pour toutes les images monochromes (y compris celles en noir et blanc), il suffit d'allouer 1 bit par pixel.
    saveOptions.BitsPerPixel = 1;

    // Enregistrer à un autre emplacement avec les options spécifiées.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Enregistre uniquement la partie centrale de l'image.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Enregistre l'intégralité de l'image dans un flux mémoire
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Enregistre la partie centrale de l'image dans un flux mémoire
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//La sortie peut ressembler à ceci :
//La taille de l'image entière en octets : 24062
//La taille de la partie centrale de l'image en octets : 6046
```

### Voir également

* class [ImageOptionsBase](../../imageoptionsbase)
* class [Image](../../image)
* espace de noms [Aspose.Imaging](../../image)
* Assemblée [Aspose.Imaging](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier spécifié en fonction des options d'enregistrement.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier. |
| options | ImageOptionsBase | Les options. |
| boundsRectangle | Rectangle | L'image de destination délimite le rectangle. Définissez le rectangle vide pour utiliser les limites de la source. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | options |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception) | L'enregistrement de l'image a échoué. |

### Exemples

L'exemple suivant charge une image BMP à partir d'un fichier, puis enregistre une partie rectangulaire de l'image dans un fichier PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Enregistre la moitié supérieure de l'image dans un fichier PNG.
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(0, 0, image.Width, image.Height / 2);
    image.Save(dir + "output.png", saveOptions, bounds);
}
```

L'exemple suivant montre comment enregistrer une image BMP entière ou une partie de celle-ci dans un fichier ou un flux.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Convertir en une image noir-blanc
    bmpImage.BinarizeOtsu();

    // Enregistrer au même emplacement avec les options par défaut.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Une palette ne contient que deux couleurs : Noir et Blanc dans ce cas.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // Pour toutes les images monochromes (y compris celles en noir et blanc), il suffit d'allouer 1 bit par pixel.
    saveOptions.BitsPerPixel = 1;

    // Enregistrer à un autre emplacement avec les options spécifiées.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Enregistre uniquement la partie centrale de l'image.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Enregistre l'intégralité de l'image dans un flux mémoire
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Enregistre la partie centrale de l'image dans un flux mémoire
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//La sortie peut ressembler à ceci :
//La taille de l'image entière en octets : 24062
//La taille de la partie centrale de l'image en octets : 6046
```

### Voir également

* class [ImageOptionsBase](../../imageoptionsbase)
* struct [Rectangle](../../rectangle)
* class [Image](../../image)
* espace de noms [Aspose.Imaging](../../image)
* Assemblée [Aspose.Imaging](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_2}

Enregistre les données de l'image dans le flux spécifié dans le format de fichier spécifié en fonction des options d'enregistrement.

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux dans lequel enregistrer les données de l'image. |
| optionsBase | ImageOptionsBase | Les options de sauvegarde. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | Impossible d'enregistrer au format spécifié car il n'est pas pris en charge pour le moment.;optionsBase |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception) | L'exportation de l'image a échoué. |

### Exemples

L'exemple suivant charge une image à partir d'un fichier, puis enregistre l'image dans un flux de fichiers PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    using (System.IO.Stream outputStream = System.IO.File.Open(dir + "output.png", System.IO.FileMode.Create))
    {
        // Enregistre l'intégralité de l'image dans un flux de fichiers.
        image.Save(outputStream, saveOptions);
    }
}
```

Cet exemple montre le processus d'enregistrement d'une image dans MemoryStream. Pour illustrer cette opération, l'exemple charge un fichier existant à partir d'un emplacement de disque, effectue une opération de rotation sur l'image et enregistre l'image au format PSD

```csharp
[C#]

//Créer une instance de MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Créer une instance de la classe d'image et l'initialiser avec un fichier existant via le chemin du fichier
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"C:\temp\sample.bmp"))
    {
        //Faire pivoter l'image à 180 degrés autour de l'axe X
        image.RotateFlip(Aspose.Imaging.RotateFlipType.Rotate180FlipX);

        // Enregistrez l'image au format PSD dans MemoryStream avec les paramètres PsdOptions par défaut
        image.Save(stream, new Aspose.Imaging.ImageOptions.PsdOptions());
    }
}
```

L'exemple suivant montre comment enregistrer une image BMP entière ou une partie de celle-ci dans un fichier ou un flux.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Convertir en une image noir-blanc
    bmpImage.BinarizeOtsu();

    // Enregistrer au même emplacement avec les options par défaut.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Une palette ne contient que deux couleurs : Noir et Blanc dans ce cas.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // Pour toutes les images monochromes (y compris celles en noir et blanc), il suffit d'allouer 1 bit par pixel.
    saveOptions.BitsPerPixel = 1;

    // Enregistrer à un autre emplacement avec les options spécifiées.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Enregistre uniquement la partie centrale de l'image.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Enregistre l'intégralité de l'image dans un flux mémoire
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Enregistre la partie centrale de l'image dans un flux mémoire
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//La sortie peut ressembler à ceci :
//La taille de l'image entière en octets : 24062
//La taille de la partie centrale de l'image en octets : 6046
```

### Voir également

* class [ImageOptionsBase](../../imageoptionsbase)
* class [Image](../../image)
* espace de noms [Aspose.Imaging](../../image)
* Assemblée [Aspose.Imaging](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Enregistre les données de l'image dans le flux spécifié dans le format de fichier spécifié en fonction des options d'enregistrement.

```csharp
public virtual void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux dans lequel enregistrer les données de l'image. |
| optionsBase | ImageOptionsBase | Les options de sauvegarde. |
| boundsRectangle | Rectangle | L'image de destination délimite le rectangle. Définissez le rectangle vide pour utiliser les limites de la source. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | Impossible d'enregistrer au format spécifié car il n'est pas pris en charge pour le moment.;optionsBase |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception) | L'exportation de l'image a échoué. |

### Exemples

L'exemple suivant charge une image à partir d'un fichier, puis enregistre une partie rectangulaire de l'image dans un flux de fichier PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(0, 0, image.Width, image.Height / 2);
    using (System.IO.Stream outputStream = System.IO.File.Open(dir + "sample.output.png", System.IO.FileMode.Create))
    {
        // Enregistre la moitié supérieure de l'image dans un flux de fichier.
        image.Save(outputStream, saveOptions, bounds);
    }
}
```

L'exemple suivant montre comment enregistrer une image BMP entière ou une partie de celle-ci dans un fichier ou un flux.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Convertir en une image noir-blanc
    bmpImage.BinarizeOtsu();

    // Enregistrer au même emplacement avec les options par défaut.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Une palette ne contient que deux couleurs : Noir et Blanc dans ce cas.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // Pour toutes les images monochromes (y compris celles en noir et blanc), il suffit d'allouer 1 bit par pixel.
    saveOptions.BitsPerPixel = 1;

    // Enregistrer à un autre emplacement avec les options spécifiées.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Enregistre uniquement la partie centrale de l'image.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Enregistre l'intégralité de l'image dans un flux mémoire
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Enregistre la partie centrale de l'image dans un flux mémoire
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//La sortie peut ressembler à ceci :
//La taille de l'image entière en octets : 24062
//La taille de la partie centrale de l'image en octets : 6046
```

### Voir également

* class [ImageOptionsBase](../../imageoptionsbase)
* struct [Rectangle](../../rectangle)
* class [Image](../../image)
* espace de noms [Aspose.Imaging](../../image)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
