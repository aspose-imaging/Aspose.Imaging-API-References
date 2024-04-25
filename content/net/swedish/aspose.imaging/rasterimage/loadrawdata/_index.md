---
title: LoadRawData
second_title: Aspose.Imaging för .NET API-referens
description: Laddar rådata.
type: docs
weight: 420
url: /sv/aspose.imaging/rasterimage/loadrawdata/
---
## LoadRawData(Rectangle, RawDataSettings, IPartialRawDataLoader) {#loadrawdata}

Laddar rådata.

```csharp
public void LoadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, 
    IPartialRawDataLoader rawDataLoader)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | Rectangle | Rektangeln att ladda rådata från. |
| rawDataSettings | RawDataSettings | De rådatainställningar som ska användas för inlästa data. Observera att om data inte är i det angivna formatet kommer datakonvertering att utföras. |
| rawDataLoader | IPartialRawDataLoader | Rådataladdaren. |

### Exempel

Följande exempel visar hur man extraherar pixlar från råbildsdata med RawDataSettings. Tänk till exempel på ett problem med räkning av helt genomskinliga pixlar i en bild.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\GrayscaleWithAlpha.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
    Aspose.Imaging.RawDataSettings settings = rasterImage.RawDataSettings;

    TransparentPixelRawDataCounter rawDataLoader = new TransparentPixelRawDataCounter(settings);

    // Ladda pixlar för hela bilden. Vilken rektangulär del av bilden som helst kan anges som en parameter för metoden Aspose.Imaging.RasterImage.LoadRawData.
    rasterImage.LoadRawData(rasterImage.Bounds, settings, rawDataLoader);

    System.Console.WriteLine("The number of fully transparent pixels is {0}", rawDataLoader.Count);
    System.Console.WriteLine("The total number of pixels is {0}", image.Width * image.Height);
}

// Vid rådata kan räknaren se ut så här:
/// <summary>
/// Räknar antalet helt genomskinliga pixlar med alfakanalvärdet 0.
/// </summary>
private class TransparentPixelRawDataCounter : IPartialRawDataLoader
{
    /// <summary>
    /// Antalet helt genomskinliga pixlar.
    /// </summary>
    private int count;

    /// <summary>
    /// Rådatainställningarna för den laddade bilden.
    /// </summary>
    private Aspose.Imaging.RawDataSettings rawDataSettings;

    /// <summary>
    /// Får antalet helt genomskinliga pixlar.
    /// </summary>
    public int Count
    {
        get { return this.count; }
    }

    /// <summary>
    /// Initierar en ny instans av <see TransparentPixelRawDataCounter /> klass.
    /// </summary>
    /// <param name="inställningar">Inställningarna för rådata gör det möjligt att extrahera färgkomponenter från rådata.</param>
    public TransparentPixelRawDataCounter(Aspose.Imaging.RawDataSettings settings)
    {
        this.rawDataSettings = settings;
        this.count = 0;
    }

    /// <summary>
    /// Bearbetar den inlästa rådatan. Denna metod kallas tillbaka varje gång när en ny del av rådata laddas.
    /// </summary>
    /// <param name="dataRectangle">Rådatarektangeln.</param>
    /// <param name="data">Rådata.</param>
    /// <param name="start">Startdatapunkten.</param>
    /// <param name="end">Slutdatapunkten.</param>
    public void Process(Aspose.Imaging.Rectangle dataRectangle, byte[] data, Aspose.Imaging.Point start, Aspose.Imaging.Point end)
    {
        int[] channelBits = this.rawDataSettings.PixelDataFormat.ChannelBits;

        // Endast enkla format är tänkta här för att förenkla koden.
        // Låt oss endast betrakta bilder med 8 bitar per sampel.
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
                        // ARGB
                        for (int i = 0; i < data.Length; i += 4)
                        {
                            // Alfakanalen lagras sist, efter färgkomponenterna.
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
                        // Gråskala Alpha
                        for (int i = 0; i < data.Length; i += 2)
                        {
                            // Alfakanalen lagras sist, efter färgkomponenterna.
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
    /// Bearbetar den inlästa rådatan. Denna metod kallas tillbaka varje gång när en ny del av rådata laddas.
    /// </summary>
    /// <param name="dataRectangle">Rådatarektangeln.</param>
    /// <param name="data">Rådata.</param>
    /// <param name="start">Startdatapunkten.</param>
    /// <param name="end">Slutdatapunkten.</param>
    /// <param name="loadOptions">Laddningsalternativen.</param>
    public void Process(Aspose.Imaging.Rectangle dataRectangle, byte[] data, Aspose.Imaging.Point start, Aspose.Imaging.Point end, Aspose.Imaging.LoadOptions loadOptions)
    {
        this.Process(dataRectangle, data, start, end);
    }
}
```

### Se även

* struct [Rectangle](../../rectangle)
* class [RawDataSettings](../../rawdatasettings)
* interface [IPartialRawDataLoader](../../ipartialrawdataloader)
* class [RasterImage](../../rasterimage)
* namnutrymme [Aspose.Imaging](../../rasterimage)
* hopsättning [Aspose.Imaging](../../../)

---

## LoadRawData(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) {#loadrawdata_1}

Laddar rådata.

```csharp
public void LoadRawData(Rectangle rectangle, Rectangle destImageBounds, 
    RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | Rectangle | Rektangeln att ladda rådata från. |
| destImageBounds | Rectangle | Dest-bilden gränsar. |
| rawDataSettings | RawDataSettings | De rådatainställningar som ska användas för inlästa data. Observera att om data inte är i det angivna formatet kommer datakonvertering att utföras. |
| rawDataLoader | IPartialRawDataLoader | Rådataladdaren. |

### Se även

* struct [Rectangle](../../rectangle)
* class [RawDataSettings](../../rawdatasettings)
* interface [IPartialRawDataLoader](../../ipartialrawdataloader)
* class [RasterImage](../../rasterimage)
* namnutrymme [Aspose.Imaging](../../rasterimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
