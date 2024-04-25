---
title: WebPImage
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Initialise une nouvelle instance duWebPImageaspose.imaging.fileformats.webp/webpimage class du flux.
type: docs
weight: 10
url: /fr/aspose.imaging.fileformats.webp/webpimage/webpimage/
---
## WebPImage(Stream) {#constructor_4}

Initialise une nouvelle instance du[`WebPImage`](../../webpimage) class du flux.

```csharp
public WebPImage(Stream stream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | L'image WebP du flux. |

### Exemples

Cet exemple montre comment charger une image WebP à partir d'un flux de fichiers et l'enregistrer au format PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// Charge une image WebP à partir d'un flux de fichiers.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "test.webp"))
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(stream))
{
    // Enregistrer en PNG
    // Notez que seul le cadre actif sera stocké en PNG, car PNG n'est pas un format multipage.
    webPImage.Save(dir + "test.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Voir également

* class [WebPImage](../../webpimage)
* espace de noms [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* Assemblée [Aspose.Imaging](../../../)

---

## WebPImage(Stream, LoadOptions) {#constructor_5}

Initialise une nouvelle instance du[`WebPImage`](../../webpimage) classe du flux.

```csharp
public WebPImage(Stream stream, LoadOptions loadOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | L'image WebP du flux. |
| loadOptions | LoadOptions | Les options de chargement. |

### Voir également

* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* espace de noms [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* Assemblée [Aspose.Imaging](../../../)

---

## WebPImage(string) {#constructor_6}

Initialise une nouvelle instance du[`WebPImage`](../../webpimage) classe du fichier.

```csharp
public WebPImage(string path)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| path | String | Le chemin d'accès au fichier WebP Image |

### Exemples

Cet exemple montre comment charger une image WebP à partir d'un fichier et l'enregistrer au format PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// Charge une image WebP à partir d'un fichier.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(dir + "test.webp"))
{
    // Enregistrer en PNG
    // Notez que seul le cadre actif sera stocké en PNG, car PNG n'est pas un format multipage.
    webPImage.Save(dir + "test.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Voir également

* class [WebPImage](../../webpimage)
* espace de noms [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* Assemblée [Aspose.Imaging](../../../)

---

## WebPImage(string, LoadOptions) {#constructor_7}

Initialise une nouvelle instance du[`WebPImage`](../../webpimage) classe du fichier.

```csharp
public WebPImage(string path, LoadOptions loadOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| path | String | Le chemin d'accès au fichier WebP Image |
| loadOptions | LoadOptions | Les options de chargement. |

### Voir également

* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* espace de noms [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* Assemblée [Aspose.Imaging](../../../)

---

## WebPImage(RasterImage) {#constructor}

Initialise une nouvelle instance du[`WebPImage`](../../webpimage) classe de rasterImage.

```csharp
public WebPImage(RasterImage rasterImage)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| rasterImage | RasterImage | L'image tramée. |

### Exemples

Cet exemple montre comment créer une image WebP à partir d'une autre image raster.

```csharp
[C#]

string dir = "c:\\temp\\";

// Charge une image PNG de 100x100 px.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Remplit toute l'image en rouge.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // Crée une image WebP basée sur l'image PNG.
    using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(pngImage))
    {
        // Enregistrer dans un fichier WebP avec les options par défaut
        webPImage.Save(dir + "output.webp", new Aspose.Imaging.ImageOptions.WebPOptions());
    }
}
```

### Voir également

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [WebPImage](../../webpimage)
* espace de noms [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* Assemblée [Aspose.Imaging](../../../)

---

## WebPImage(RasterImage, LoadOptions) {#constructor_1}

Initialise une nouvelle instance du[`WebPImage`](../../webpimage) classe de rasterImage.

```csharp
public WebPImage(RasterImage rasterImage, LoadOptions loadOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| rasterImage | RasterImage | L'image tramée. |
| loadOptions | LoadOptions | Les options de chargement. |

### Voir également

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* espace de noms [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* Assemblée [Aspose.Imaging](../../../)

---

## WebPImage(int, int, WebPOptions) {#constructor_2}

Initialise une nouvelle instance du[`WebPImage`](../../webpimage) classe avec image vide.

```csharp
public WebPImage(int width, int height, WebPOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| width | Int32 | La largeur de l'image |
| height | Int32 | La hauteur de l'image. |
| options | WebPOptions | Les options. |

### Exemples

Cet exemple montre comment créer une image WebP avec les options spécifiées à partir de rien.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.WebPOptions createOptions = new Aspose.Imaging.ImageOptions.WebPOptions();
createOptions.Lossless = true;
createOptions.Quality = 100f;
//createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "output.webp");

// Crée une image WebP de 100x100 px.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(webPImage);

    // Remplit toute l'image en rouge.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, webPImage.Bounds);

    // Enregistrer dans un fichier WebP
    webPImage.Save(dir + "output.webp");
}
```

Cet exemple montre comment créer une image WebP animée à plusieurs images avec les options spécifiées.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.WebPOptions createOptions = new Aspose.Imaging.ImageOptions.WebPOptions();
createOptions.Lossless = true;
createOptions.Quality = 100f;
createOptions.AnimBackgroundColor = (uint)Aspose.Imaging.Color.Gray.ToArgb();

// Le cadre par défaut plus 36 + 36 cadres supplémentaires.
createOptions.AnimLoopCount = 36 + 36 + 1;

// Crée une image WebP de 100x100 px.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    // Le premier cercle est rouge
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // Le deuxième cercle est noir
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // Augmente progressivement l'angle de la forme d'arc rouge.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush1, block.Bounds, 0, angle);

        webPImage.AddBlock(block);
    }

    // Augmente progressivement l'angle de l'arc noir et efface l'arc rouge.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);

        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush2, block.Bounds, 0, angle);
        graphics.FillPie(brush1, block.Bounds, angle, 360 - angle);

        webPImage.AddBlock(block);
    }

    // Enregistrer dans un fichier WebP
    webPImage.Save(dir + "output.webp");
}
```

### Voir également

* class [WebPOptions](../../../aspose.imaging.imageoptions/webpoptions)
* class [WebPImage](../../webpimage)
* espace de noms [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* Assemblée [Aspose.Imaging](../../../)

---

## WebPImage(int, int, WebPOptions, LoadOptions) {#constructor_3}

Initialise une nouvelle instance du[`WebPImage`](../../webpimage) classe avec image vide.

```csharp
public WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| width | Int32 | La largeur de l'image |
| height | Int32 | La hauteur de l'image. |
| options | WebPOptions | Les options. |
| loadOptions | LoadOptions | Les options de chargement. |

### Voir également

* class [WebPOptions](../../../aspose.imaging.imageoptions/webpoptions)
* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* espace de noms [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
