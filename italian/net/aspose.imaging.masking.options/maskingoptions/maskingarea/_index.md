---
title: MaskingArea
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ottiene o imposta larea di mascheratura.
type: docs
weight: 60
url: /it/net/aspose.imaging.masking.options/maskingoptions/maskingarea/
---
## MaskingOptions.MaskingArea property

Ottiene o imposta l'area di mascheratura.

```csharp
public Rectangle MaskingArea { get; set; }
```

### Valore della proprietà

L'area di mascheratura che è un'area parziale dell'immagine sorgente. Il valore Rectangle.Empty indica l'area dell'immagine sorgente completa.

### Esempi

Questo esempio mostra come scomporre un'immagine raster in più immagini utilizzando la mascheratura dell'immagine e una maschera manuale. Il mascheramento dell'immagine è una tecnica di elaborazione delle immagini che viene utilizzata per dividere lo sfondo dagli oggetti dell'immagine in primo piano.

```csharp
[C#]

string dir = "c:\\temp\\";

// Definisci una maschera manuale.
Aspose.Imaging.GraphicsPath manualMask = new Aspose.Imaging.GraphicsPath();
Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();
figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new RectangleF(50, 50, 40, 40)));
figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new RectangleF(10, 20, 50, 30)));
manualMask.AddFigure(figure);

// Ogni cluster (segmento) verrà archiviato in un file PNG separato.
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

// Imposta la maschera manuale.
Aspose.Imaging.Masking.Options.ManualMaskingArgs args = new Aspose.Imaging.Masking.Options.ManualMaskingArgs();
args.Mask = manualMask;

using (RasterImage image = (RasterImage)Image.Load(dir + "Blue hills.png"))
{
    Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();

    // Usa l'algoritmo di clustering manuale.
    maskingOptions.Method = Masking.Options.SegmentationMethod.Manual;

    // Tutte le forme che compongono una maschera verranno combinate in una sola. 
    maskingOptions.Decompose = false;
    maskingOptions.Args = args;

    // Il colore dello sfondo sarà arancione.
    maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
    maskingOptions.ExportOptions = exportOptions;

    // L'area dell'immagine sorgente a cui verrà applicata la mascheratura.
    maskingOptions.MaskingArea = new Rectangle(50, 50, 120, 120);

    // Crea un'istanza della classe ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // Dividi l'immagine di origine in diversi cluster (segmenti).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // Ottieni immagini dal risultato della mascheratura e salvale in PNG.
        for (int i = 0; i < maskingResult.Length; i++)
        {
            string outputFileName = string.Format("Blue hills.Segment{0}.png", maskingResult[i].ObjectNumber);
            using (Aspose.Imaging.Image resultImage = maskingResult[i].GetImage())
            {
                resultImage.Save(dir + outputFileName);
            }
        }
    }
}
```

### Guarda anche

* struct [Rectangle](../../../aspose.imaging/rectangle)
* class [MaskingOptions](../../maskingoptions)
* spazio dei nomi [Aspose.Imaging.Masking.Options](../../maskingoptions)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->