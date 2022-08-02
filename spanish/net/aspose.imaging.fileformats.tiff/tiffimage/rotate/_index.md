---
title: Rotate
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Rotar imagen alrededor del centro.
type: docs
weight: 370
url: /es/net/aspose.imaging.fileformats.tiff/tiffimage/rotate/
---
## TiffImage.Rotate method

Rotar imagen alrededor del centro.

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| angle | Single | El ángulo de rotación en grados. Los valores positivos girarán en el sentido de las agujas del reloj. |
| resizeProportionally | Boolean | si se establece en`verdadero` cambiará el tamaño de la imagen de acuerdo con las proyecciones del rectángulo rotado (puntos de las esquinas) en otro caso, eso deja las dimensiones intactas y solo se rotan los contenidos internos de la imagen. |
| backgroundColor | Color | Color del fondo. |

### Ejemplos

El siguiente ejemplo muestra cómo girar una imagen TIFF alrededor del centro 45 grados en el sentido de las agujas del reloj.

```csharp
[C#]

string dir = "c:\\temp\\";
Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    
// Crear una fuente de archivo permanente, no temporal.
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "rotated.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // El degradado lineal desde la esquina superior izquierda hasta la esquina inferior derecha de la imagen.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(tiffImage.Width, tiffImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Rellena el cuadro activo con el pincel de degradado lineal.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(tiffImage);
    gr.FillRectangle(brush, tiffImage.Bounds);

    // Gira la imagen alrededor del centro 45 grados en el sentido de las agujas del reloj. 
    // El tamaño de la imagen cambió según el rectángulo rotado (puntos de las esquinas).
    tiffImage.Rotate(45f, true, Aspose.Imaging.Color.Black);
    tiffImage.Save();

    // Gira la imagen alrededor del centro 45 grados en el sentido de las agujas del reloj.
    // Deje intactas las dimensiones de la imagen y solo se gira el contenido interno de la imagen.
    tiffImage.Rotate(45f, false, Aspose.Imaging.Color.Gray);
    tiffImage.Save(dir + "rotated.preservesize.tif");
}
```

### Ver también

* struct [Color](../../../aspose.imaging/color)
* class [TiffImage](../../tiffimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->