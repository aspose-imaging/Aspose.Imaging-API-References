---
title: BitmapInfoHeader
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Obtient len-tête dinformations bitmap.
type: docs
weight: 20
url: /fr/net/aspose.imaging.fileformats.bmp/bmpimage/bitmapinfoheader/
---
## BmpImage.BitmapInfoHeader property

Obtient l'en-tête d'informations bitmap.

```csharp
public BitmapInfoHeader BitmapInfoHeader { get; }
```

### Valeur de la propriété

L'en-tête d'informations bitmap.

### Exemples

L'exemple suivant récupère les informations de l'en-tête BMP et les imprime sur la console.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
    Aspose.Imaging.FileFormats.Bmp.BitmapInfoHeader header = bmpImage.BitmapInfoHeader;

    System.Console.WriteLine("The number of palette colors that are required for displaying the bitmap: {0}", header.BitmapColorsImportant);
    System.Console.WriteLine("The number of palette colors used in the bitmap: {0}", header.BitmapColorsUsed);
    System.Console.WriteLine("The bitmap compression: {0}", header.BitmapCompression);
    System.Console.WriteLine("The bitmap height: {0}", header.BitmapHeight);
    System.Console.WriteLine("The bitmap width: {0}", header.BitmapWidth);
    System.Console.WriteLine("The bitmap raw data size in bytes: {0}", header.BitmapImageSize);
    System.Console.WriteLine("The number of planes: {0}", header.BitmapPlanes);
    System.Console.WriteLine("The horizontal resolution of the bitmap, in pixels-per-meter: {0}", header.BitmapXPelsPerMeter);
    System.Console.WriteLine("The vertical resolution of the bitmap, in pixels-per-meter: {0}", header.BitmapYPelsPerMeter);
    System.Console.WriteLine("The number of bits per pixel: {0}", header.BitsPerPixel);
    System.Console.WriteLine("The extra bits masks: {0}", header.ExtraBitMasks);
    System.Console.WriteLine("The header size in bytes: {0}", header.HeaderSize);
}

//La sortie peut ressembler à ceci :
//Le nombre de couleurs de palette nécessaires pour afficher le bitmap : 0
//Le nombre de couleurs de palette utilisées dans le bitmap : 0
//La compression bitmap : 0
// La hauteur du bitmap : 375
//La largeur du bitmap : 500
// La taille des données brutes du bitmap en octets : 562 500
//Le nombre d'avions : 1
//La résolution horizontale du bitmap, en pixels par mètre : 0
//La résolution verticale du bitmap, en pixels par mètre : 0
//Le nombre de bits par pixel : 24
//Les masques de bits supplémentaires : 
// La taille de l'en-tête en octets : 40
```

### Voir également

* class [BitmapInfoHeader](../../bitmapinfoheader)
* class [BmpImage](../../bmpimage)
* espace de noms [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
