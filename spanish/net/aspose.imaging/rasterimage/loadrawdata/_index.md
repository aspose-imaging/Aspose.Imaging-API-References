---
title: LoadRawData
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Carga datos sin procesar.
type: docs
weight: 420
url: /es/net/aspose.imaging/rasterimage/loadrawdata/
---
## LoadRawData(Rectangle, RawDataSettings, IPartialRawDataLoader) {#loadrawdata}

Carga datos sin procesar.

```csharp
public void LoadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, 
    IPartialRawDataLoader rawDataLoader)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rectangle | Rectangle | El rectángulo desde el que se cargan los datos sin procesar. |
| rawDataSettings | RawDataSettings | La configuración de datos sin procesar que se usará para los datos cargados. Tenga en cuenta que si los datos no están en el formato especificado, se realizará la conversión de datos. |
| rawDataLoader | IPartialRawDataLoader | El cargador de datos sin procesar. |

### Ejemplos

El siguiente ejemplo muestra cómo extraer píxeles de los datos de imagen sin procesar mediante RawDataSettings. Por ejemplo, considere un problema de contar los píxeles completamente transparentes de una imagen.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\GrayscaleWithAlpha.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
    Aspose.Imaging.RawDataSettings settings = rasterImage.RawDataSettings;

    TransparentPixelRawDataCounter rawDataLoader = new TransparentPixelRawDataCounter(settings);

    // Carga píxeles para toda la imagen. Cualquier parte rectangular de la imagen se puede especificar como parámetro del método Aspose.Imaging.RasterImage.LoadRawData.
    rasterImage.LoadRawData(rasterImage.Bounds, settings, rawDataLoader);

    System.Console.WriteLine("The number of fully transparent pixels is {0}", rawDataLoader.Count);
    System.Console.WriteLine("The total number of pixels is {0}", image.Width * image.Height);
}

// En el caso de datos sin procesar, el contador puede verse así:
/// <summary>
/// Cuenta el número de píxeles completamente transparentes con un valor de canal alfa de 0.
/// </summary>
private class TransparentPixelRawDataCounter : IPartialRawDataLoader
{
    /// <summary>
    /// El número de píxeles completamente transparentes.
    /// </summary>
    private int count;

    /// <summary>
    /// La configuración de datos sin procesar de la imagen cargada.
    /// </summary>
    private Aspose.Imaging.RawDataSettings rawDataSettings;

    /// <summary>
    /// Obtiene el número de píxeles completamente transparentes.
    /// </summary>
    public int Count
    {
        get { return this.count; }
    }

    /// <summary>
    /// Inicializa una nueva instancia de <ver TransparentPixelRawDataCounter /> clase.
    /// </summary>
    /// <param name="settings">La configuración de datos sin procesar permite extraer componentes de color de los datos sin procesar.</param>
    public TransparentPixelRawDataCounter(Aspose.Imaging.RawDataSettings settings)
    {
        this.rawDataSettings = settings;
        this.count = 0;
    }

    /// <summary>
    /// Procesa los datos sin procesar cargados. Este método se vuelve a llamar cada vez que se carga una nueva porción de datos sin procesar.
    /// </summary>
    /// <param name="dataRectangle">El rectángulo de datos sin procesar.</param>
    /// <param name="data">Los datos sin procesar.</param>
    /// <param name="start">El punto de datos de inicio.</param>
    /// <param name="end">El punto de datos final.</param>
    public void Process(Aspose.Imaging.Rectangle dataRectangle, byte[] data, Aspose.Imaging.Point start, Aspose.Imaging.Point end)
    {
        int[] channelBits = this.rawDataSettings.PixelDataFormat.ChannelBits;

        // Aquí solo se consideran formatos simples para simplificar el código.
        // Consideremos solo imágenes con 8 bits por muestra.
        for (int i = 0; i < channelBits.Length; i++)
        {
            if (channelBits[i] != 8)
            {
                throw new System.NotSupportedException();
            }
        }

        switch (this.rawDataSettings.PixelDataFormat.PixelFormat)
        {
            case PixelFormat.Rgb:
            case PixelFormat.Bgr:
                {
                    if (channelBits.Length == 4)
                    {
                        //ARGB
                        for (int i = 0; i < data.Length; i += 4)
                        {
                            // El canal alfa se almacena en último lugar, después de los componentes de color.
                            if (data[i + 3] == 0)
                            {
                                this.count++;
                            }
                        }
                    }
                }
                break;

            case PixelFormat.Grayscale:
                {
                    if (channelBits.Length == 2)
                    {
                        // Alfa en escala de grises
                        for (int i = 0; i < data.Length; i += 2)
                        {
                            // El canal alfa se almacena en último lugar, después de los componentes de color.
                            if (data[i + 1] == 0)
                            {
                                this.count++;
                            }
                        }
                    }
                }
                break;

            default:
                throw new System.ArgumentOutOfRangeException("PixelFormat");
        }
    }

    /// <summary>
    /// Procesa los datos sin procesar cargados. Este método se vuelve a llamar cada vez que se carga una nueva porción de datos sin procesar.
    /// </summary>
    /// <param name="dataRectangle">El rectángulo de datos sin procesar.</param>
    /// <param name="data">Los datos sin procesar.</param>
    /// <param name="start">El punto de datos de inicio.</param>
    /// <param name="end">El punto de datos final.</param>
    /// <param name="loadOptions">Las opciones de carga.</param>
    public void Process(Aspose.Imaging.Rectangle dataRectangle, byte[] data, Aspose.Imaging.Point start, Aspose.Imaging.Point end, Aspose.Imaging.LoadOptions loadOptions)
    {
        this.Process(dataRectangle, data, start, end);
    }
}
```

### Ver también

* struct [Rectangle](../../rectangle)
* class [RawDataSettings](../../rawdatasettings)
* interface [IPartialRawDataLoader](../../ipartialrawdataloader)
* class [RasterImage](../../rasterimage)
* espacio de nombres [Aspose.Imaging](../../rasterimage)
* asamblea [Aspose.Imaging](../../../)

---

## LoadRawData(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) {#loadrawdata_1}

Carga datos sin procesar.

```csharp
public void LoadRawData(Rectangle rectangle, Rectangle destImageBounds, 
    RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rectangle | Rectangle | El rectángulo desde el que se cargan los datos sin procesar. |
| destImageBounds | Rectangle | Los límites de la imagen dest. |
| rawDataSettings | RawDataSettings | La configuración de datos sin procesar que se usará para los datos cargados. Tenga en cuenta que si los datos no están en el formato especificado, se realizará la conversión de datos. |
| rawDataLoader | IPartialRawDataLoader | El cargador de datos sin procesar. |

### Ver también

* struct [Rectangle](../../rectangle)
* class [RawDataSettings](../../rawdatasettings)
* interface [IPartialRawDataLoader](../../ipartialrawdataloader)
* class [RasterImage](../../rasterimage)
* espacio de nombres [Aspose.Imaging](../../rasterimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
