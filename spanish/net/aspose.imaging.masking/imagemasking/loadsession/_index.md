---
title: LoadSession
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Carga la sesión desde el flujo especificado.
type: docs
weight: 50
url: /es/net/aspose.imaging.masking/imagemasking/loadsession/
---
## LoadSession(Stream) {#loadsession}

Carga la sesión desde el flujo especificado.

```csharp
public IMaskingSession LoadSession(Stream stream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | La corriente. |

### Valor_devuelto

la sesión de enmascaramiento que puede realizar operaciones de descomposición de reentrenamiento.

### Ver también

* interface [IMaskingSession](../../imaskingsession)
* class [ImageMasking](../../imagemasking)
* espacio de nombres [Aspose.Imaging.Masking](../../imagemasking)
* asamblea [Aspose.Imaging](../../../)

---

## LoadSession(string) {#loadsession_1}

Carga la sesión desde el archivo especificado.

```csharp
public IMaskingSession LoadSession(string filePath)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo. |

### Valor_devuelto

la sesión de enmascaramiento que puede realizar operaciones de descomposición de reentrenamiento.

### Ejemplos

Guardar la sesión de enmascaramiento en un archivo para sesiones largas, así como para la posibilidad de reanudar la sesión en otro entorno.

```csharp
[C#]

string dir = "c:\\temp\\";
string sessionBackupFile = dir + "session.bak";

// Opciones de exportación de enmascaramiento
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
    
// Usar el agrupamiento de GraphCut.
maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
maskingOptions.Decompose = false;
maskingOptions.Args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

// El color de fondo será naranja.
maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
maskingOptions.ExportOptions = exportOptions;

// Comenzando una sesión por primera vez y guardando en un archivo
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    // Crea una instancia de la clase ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    using (Aspose.Imaging.Masking.IMaskingSession session = masking.CreateSession(maskingOptions))
    {
        using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = session.Decompose())
        {
            using (Aspose.Imaging.RasterImage segmentImage = maskingResult[1].GetImage())
            {
                segmentImage.Save(dir + "step1.png");
            }
        }

        session.Save(sessionBackupFile);
    }
}

// Reanudando una sesión de enmascaramiento desde un archivo
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    // Crea una instancia de la clase ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    using (Aspose.Imaging.Masking.IMaskingSession session = masking.LoadSession(sessionBackupFile))
    {
        Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

        // Analiza la imagen visualmente y establece los puntos que pertenecen a los objetos separados.
        args.ObjectsPoints = new Point[][]
                                     {
                                         new Point[]
                                             {
                                                 new Point(0, 0), new Point(0, 1), new Point(1, 0),
                                                 new Point(1, 1), new Point(2, 0), new Point(2, 1),
                                                 new Point(3, 0), new Point(3, 1)
                                             },
                                     };
        using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = session.ImproveDecomposition(args))
        {
            // Transferencia explícita de opciones de exportación, ya que no es serializable
            maskingResult.MaskingOptions.ExportOptions = exportOptions;

            using (Aspose.Imaging.RasterImage segmentImage = maskingResult[1].GetImage())
            {
                segmentImage.Save(dir + "step2.png");
            }
        }
    }
}
```

### Ver también

* interface [IMaskingSession](../../imaskingsession)
* class [ImageMasking](../../imagemasking)
* espacio de nombres [Aspose.Imaging.Masking](../../imagemasking)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
