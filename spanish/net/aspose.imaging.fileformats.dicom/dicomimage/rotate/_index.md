---
title: Rotate
second_title: Aspose.Imaging para la referencia de la API de .NET
description: RasterCahcedMultipageImage.Rotate imagen alrededor del centro.
type: docs
weight: 300
url: /es/net/aspose.imaging.fileformats.dicom/dicomimage/rotate/
---
## DicomImage.Rotate method

!:RasterCahcedMultipageImage.Rotate imagen alrededor del centro.

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| angle | Single | El ángulo de rotación en grados. Los valores positivos girarán en el sentido de las agujas del reloj. |
| resizeProportionally | Boolean | si se establece en`verdadero` cambiará el tamaño de su imagen de acuerdo con las proyecciones del rectángulo rotado (puntos de esquina) en otro caso que deja las dimensiones intactas y solo `internal` el contenido de la imagen se gira. |
| backgroundColor | Color | Color del fondo. |

### Ejemplos

Este ejemplo muestra cómo girar todas las páginas de una imagen DICOM y guardarlas todas en una imagen TIFF de varios fotogramas.

```csharp
[C#]

string dir = "c:\\temp\\";

// Cargar una imagen DICOM desde un flujo de archivos.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "multiframe.dicom"))
{
    using (Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = new Aspose.Imaging.FileFormats.Dicom.DicomImage(stream))
    {
        // Gira la imagen alrededor del centro 60 grados en el sentido de las agujas del reloj.
        // Usa el gris como color de fondo.
        dicomImage.Rotate(60, true, Aspose.Imaging.Color.Gray);

        Aspose.Imaging.ImageOptions.TiffOptions createOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
        createOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Deflate;

        // Tenga en cuenta que si la imagen es colorida, se convertirá automáticamente al formato de escala de grises de acuerdo con las opciones a continuación
        createOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;
        createOptions.BitsPerSample = new ushort[] { 8 };

        // Crea una matriz de marcos TIFF.
        // El número de cuadros es igual al número de páginas DJVU.
        Aspose.Imaging.FileFormats.Tiff.TiffFrame[] tiffFrames = new Aspose.Imaging.FileFormats.Tiff.TiffFrame[dicomImage.DicomPages.Length];

        // Guarde cada página como un marco TIFF individual.
        foreach (Aspose.Imaging.FileFormats.Dicom.DicomPage dicomPage in dicomImage.DicomPages)
        {
            // Crear un marco TIFF basado en la página DICOM.
            tiffFrames[dicomPage.Index] = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(dicomPage, createOptions);
        }

        // Componga una imagen TIFF a partir de los marcos.
        using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(tiffFrames))
        {
            // Guardar en un archivo.
            tiffImage.Save(dir + "multiframe.tif");
        }
    }
}
```

### Ver también

* struct [Color](../../../aspose.imaging/color)
* class [DicomImage](../../dicomimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Dicom](../../dicomimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
