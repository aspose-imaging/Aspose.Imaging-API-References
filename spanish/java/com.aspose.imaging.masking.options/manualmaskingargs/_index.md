---
title: "ManualMaskingArgs"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa los argumentos que se especifican para el método de enmascarado manual"
type: docs
weight: 15
url: /es/java/com.aspose.imaging.masking.options/manualmaskingargs/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.masking.options.IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs)
```
public class ManualMaskingArgs implements IMaskingArgs
```

Representa los argumentos que se especifican para el método de enmascarado manual
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ManualMaskingArgs()](#ManualMaskingArgs--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getMask()](#getMask--) | Obtiene el conjunto de formas gráficas que forman la máscara. |
| [setMask(GraphicsPath value)](#setMask-com.aspose.imaging.GraphicsPath-) | Establece el conjunto de formas gráficas que forman la máscara. |

## Example: This example shows how to decompose a raster image into multiple images using image masking and a manual mask.
Este ejemplo muestra cómo descomponer una imagen raster en múltiples imágenes usando enmascaramiento de imágenes y una máscara manual. El enmascaramiento de imágenes es una técnica de procesamiento de imágenes que se utiliza para separar el fondo de los objetos de la imagen en primer plano.
``` java
String dir = "c:\\temp\\";

// Define una máscara manual.
com.aspose.imaging.GraphicsPath manualMask = new com.aspose.imaging.GraphicsPath();
com.aspose.imaging.Figure figure = new com.aspose.imaging.Figure();
figure.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 40, 40)));
figure.addShape(new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(10, 20, 50, 30)));
manualMask.addFigure(figure);

// Establece la máscara manual.
com.aspose.imaging.masking.options.ManualMaskingArgs args = new com.aspose.imaging.masking.options.ManualMaskingArgs();
args.setMask(manualMask);

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Blue hills.png");
try {
    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // Utiliza el algoritmo de agrupamiento manual.
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.Manual);

    // Todas las formas que componen una máscara se combinarán en una sola.
    maskingOptions.setDecompose(false);
    maskingOptions.setArgs(args);

    // Un tamaño máximo esperado de la imagen PNG TrueColor con Alpha.
    int estimatedMaxImageSize = image.getWidth() * image.getHeight() * 4;

    // Cada clúster (segmento) se almacenará en un archivo PNG separado.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[estimatedMaxImageSize])));

    // El color de fondo será naranja.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // El área de la imagen fuente a la que se aplicará el enmascaramiento.
    maskingOptions.setMaskingArea(new com.aspose.imaging.Rectangle(50, 50, 120, 120));

    // Crea una instancia de la clase ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Divide la imagen fuente en varios clústeres (segmentos).
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);

    try
    {
        // Obtenga imágenes del resultado del enmascarado y guárdelas en PNG.
        for (int i = 0; i < maskingResults.getLength(); i++) {
            String outputFileName = String.format("Blue hills.Segment%s.png", maskingResults.get_Item(i).getObjectNumber());
            Image resultImage = maskingResults.get_Item(i).getImage();
            try {
                resultImage.save(dir + outputFileName);
            } finally {
                resultImage.close();
            }
        }
    }
    finally
    {
        maskingResults.close();
    }
} finally {
    image.close();
}
```

### ManualMaskingArgs() {#ManualMaskingArgs--}
```
public ManualMaskingArgs()
```


### getMask() {#getMask--}
```
public final GraphicsPath getMask()
```


Obtiene el conjunto de formas gráficas que forman la máscara.

Valor: La máscara.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - the set of graphic shapes that form mask.
### setMask(GraphicsPath value) {#setMask-com.aspose.imaging.GraphicsPath-}
```
public final void setMask(GraphicsPath value)
```


Establece el conjunto de formas gráficas que forman la máscara.

Valor: La máscara.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.imaging/graphicspath) | el conjunto de formas gráficas que forman la máscara. |

