---
title: Mask
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene o establece el conjunto de formas gráficas que forman mask.
type: docs
weight: 20
url: /es/net/aspose.imaging.masking.options/manualmaskingargs/mask/
---
## ManualMaskingArgs.Mask property

Obtiene o establece el conjunto de formas gráficas que forman mask.

```csharp
public GraphicsPath Mask { get; set; }
```

### El valor de la propiedad

La máscara.

### Ejemplos

Este ejemplo muestra cómo descomponer una imagen ráster en múltiples imágenes utilizando el enmascaramiento de imágenes y una máscara manual. El enmascaramiento de imágenes es una técnica de procesamiento de imágenes que se utiliza para separar el fondo de los objetos de imagen de primer plano.

```csharp
[C#]

string dir = "c:\\temp\\";

// Definir una máscara manual.
Aspose.Imaging.GraphicsPath manualMask = new Aspose.Imaging.GraphicsPath();
Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();
figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new RectangleF(50, 50, 40, 40)));
figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new RectangleF(10, 20, 50, 30)));
manualMask.AddFigure(figure);

// Cada grupo (segmento) se almacenará en un archivo PNG separado.
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

// Establecer la máscara manual.
Aspose.Imaging.Masking.Options.ManualMaskingArgs args = new Aspose.Imaging.Masking.Options.ManualMaskingArgs();
args.Mask = manualMask;

using (RasterImage image = (RasterImage)Image.Load(dir + "Blue hills.png"))
{
    Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();

    // Usar algoritmo de agrupamiento manual.
    maskingOptions.Method = Masking.Options.SegmentationMethod.Manual;

    // Todas las formas que componen una máscara se combinarán en una sola. 
    maskingOptions.Decompose = false;
    maskingOptions.Args = args;

    // El color de fondo será naranja.
    maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
    maskingOptions.ExportOptions = exportOptions;

    // El área de la imagen de origen a la que se aplicará el enmascaramiento.
    maskingOptions.MaskingArea = new Rectangle(50, 50, 120, 120);

    // Crea una instancia de la clase ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // Divide la imagen de origen en varios grupos (segmentos).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // Obtenga imágenes del resultado de enmascaramiento y guárdelas en PNG.
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

### Ver también

* class [GraphicsPath](../../../aspose.imaging/graphicspath)
* class [ManualMaskingArgs](../../manualmaskingargs)
* espacio de nombres [Aspose.Imaging.Masking.Options](../../manualmaskingargs)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->