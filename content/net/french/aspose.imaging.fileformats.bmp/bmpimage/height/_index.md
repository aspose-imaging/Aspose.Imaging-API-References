---
title: Height
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Obtient la hauteur de limage.
type: docs
weight: 60
url: /fr/aspose.imaging.fileformats.bmp/bmpimage/height/
---
## BmpImage.Height property

Obtient la hauteur de l'image.

```csharp
public override int Height { get; }
```

### Valeur de la propriété

La hauteur de l'image.

### Exemples

L'exemple suivant obtient les informations générales sur l'image, y compris le format de pixel, la taille de l'image, la résolution, la compression, etc.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;                

    System.Console.WriteLine("The pixel format: {0}", bmpImage.RawDataFormat);                
    System.Console.WriteLine("The raw line size in bytes: {0}", bmpImage.RawLineSize);
    System.Console.WriteLine("The bitmap compression: {0}", bmpImage.Compression);
    System.Console.WriteLine("The bitmap width: {0}", bmpImage.Width);
    System.Console.WriteLine("The bitmap height: {0}", bmpImage.Height);
    System.Console.WriteLine("The number of bits per pixel: {0}", bmpImage.BitsPerPixel);

    double hres = bmpImage.HorizontalResolution;
    double vres = bmpImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", hres);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", vres);

    if (hres != 96.0 || vres != 96.0)
    {
        // Vous pouvez envisager d'utiliser la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        bmpImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", bmpImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", bmpImage.VerticalResolution);
    }

    //La sortie peut ressembler à ceci :
    //Le format pixel : Rgb24Bpp, canaux utilisés : 8,8,8
    // La taille de la ligne brute en octets : 1 500
    //La compression bitmap : Rgb
    //La largeur du bitmap : 500
    // La hauteur du bitmap : 375
    //Le nombre de bits par pixel : 24
    //La résolution horizontale, en pixels par pouce : 0
    //La résolution verticale, en pixels par pouce : 0
    //Définir les valeurs de résolution à 96 dpi
    //La résolution horizontale, en pixels par pouce : 96,012
    //La résolution verticale, en pixels par pouce : 96,012
}
```

L'exemple suivant montre comment la compression bitmap affecte la taille de l'image de sortie.

```csharp
[C#]

Aspose.Imaging.FileFormats.Bmp.BitmapCompression[] compressions = new Aspose.Imaging.FileFormats.Bmp.BitmapCompression[]
{
    Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb,
    Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rle8,
};

Aspose.Imaging.Color[] paletterColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
};

// Crée une palette monochrome qui ne contient que des couleurs rouges et vertes.
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

foreach (Aspose.Imaging.FileFormats.Bmp.BitmapCompression compression in compressions)
{
    // Crée une image BMP 8-bpp de 100 x 100 px.
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 8, palette, compression, 0.0, 0.0))
    {
        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

        // Remplit toute l'image en rouge.
        Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
        gr.FillRectangle(redBrush, bmpImage.Bounds);

        // Enregistre l'image dans un flux pour obtenir la taille de l'image de sortie.
        using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
        {
            bmpImage.Save(stream);

            System.Console.WriteLine("---------------------------------------------");
            System.Console.WriteLine("The compression={0}", bmpImage.Compression);
            System.Console.WriteLine("The number of bits per pixel={0}", bmpImage.BitsPerPixel);
            System.Console.WriteLine("The image dimensions={0} x {1}", bmpImage.Width, bmpImage.Height);
            System.Console.WriteLine("The raw line size={0}", bmpImage.RawLineSize);
            System.Console.WriteLine("The output size in bytes={0}", stream.Length);
        }
    }
}

// La sortie ressemble à ceci :
// ---------------------------------------------
// La compression = Rgb
// Le nombre de bits par pixel = 8
// Les dimensions de l'image = 100 x 100
// La taille de la ligne brute = 100
// La taille de sortie en octets = 11078
// ---------------------------------------------
// La compression = Rle8
// Le nombre de bits par pixel = 8
// Les dimensions de l'image = 100 x 100
// La taille de la ligne brute = 100
// La taille de sortie en octets = 856
```

### Voir également

* class [BmpImage](../../bmpimage)
* espace de noms [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
