---
title: LoadRawData
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Carica dati grezzi.
type: docs
weight: 420
url: /it/aspose.imaging/rasterimage/loadrawdata/
---
## LoadRawData(Rectangle, RawDataSettings, IPartialRawDataLoader) {#loadrawdata}

Carica dati grezzi.

```csharp
public void LoadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, 
    IPartialRawDataLoader rawDataLoader)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | Rectangle | Il rettangolo da cui caricare i dati grezzi. |
| rawDataSettings | RawDataSettings | Le impostazioni dei dati grezzi da utilizzare per i dati caricati. Nota se i dati non sono nel formato specificato, verrà eseguita la conversione dei dati. |
| rawDataLoader | IPartialRawDataLoader | Il caricatore di dati grezzi. |

### Esempi

L'esempio seguente mostra come estrarre i pixel dai dati dell'immagine grezza usando RawDataSettings. Si consideri ad esempio un problema di conteggio dei pixel completamente trasparenti di un'immagine.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\GrayscaleWithAlpha.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
    Aspose.Imaging.RawDataSettings settings = rasterImage.RawDataSettings;

    TransparentPixelRawDataCounter rawDataLoader = new TransparentPixelRawDataCounter(settings);

    // Carica pixel per l'intera immagine. Qualsiasi parte rettangolare dell'immagine può essere specificata come parametro del metodo Aspose.Imaging.RasterImage.LoadRawData.
    rasterImage.LoadRawData(rasterImage.Bounds, settings, rawDataLoader);

    System.Console.WriteLine("The number of fully transparent pixels is {0}", rawDataLoader.Count);
    System.Console.WriteLine("The total number of pixels is {0}", image.Width * image.Height);
}

// In caso di dati grezzi, il contatore potrebbe essere simile a questo:
/// <summary>
/// Conta il numero di pixel completamente trasparenti con valore del canale alfa pari a 0.
/// </summary>
private class TransparentPixelRawDataCounter : IPartialRawDataLoader
{
    /// <summary>
    /// Il numero di pixel completamente trasparenti.
    /// </summary>
    private int count;

    /// <summary>
    /// Le impostazioni dei dati grezzi dell'immagine caricata.
    /// </summary>
    private Aspose.Imaging.RawDataSettings rawDataSettings;

    /// <summary>
    /// Ottiene il numero di pixel completamente trasparenti.
    /// </summary>
    public int Count
    {
        get { return this.count; }
    }

    /// <summary>
    /// Inizializza una nuova istanza di <vedi TransparentPixelRawDataCounter /> classe.
    /// </summary>
    /// <param name="settings">Le impostazioni dei dati grezzi consentono di estrarre componenti di colore dai dati grezzi.</param>
    public TransparentPixelRawDataCounter(Aspose.Imaging.RawDataSettings settings)
    {
        this.rawDataSettings = settings;
        this.count = 0;
    }

    /// <summary>
    /// Elabora i dati grezzi caricati. Questo metodo viene richiamato ogni volta che viene caricata una nuova porzione di dati grezzi.
    /// </summary>
    /// <param name="dataRectangle">Il rettangolo dei dati grezzi.</param>
    /// <param name="data">I dati grezzi.</param>
    /// <param name="start">Il punto dati iniziale.</param>
    /// <param name="end">Il punto dati finale.</param>
    public void Process(Aspose.Imaging.Rectangle dataRectangle, byte[] data, Aspose.Imaging.Point start, Aspose.Imaging.Point end)
    {
        int[] channelBits = this.rawDataSettings.PixelDataFormat.ChannelBits;

        // Qui vengono presi in considerazione solo i formati semplici per semplificare il codice.
        // Consideriamo solo immagini con 8 bit per campione.
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
                            // Il canale alfa viene memorizzato per ultimo, dopo i componenti del colore.
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
                        // Alfa in scala di grigi
                        for (int i = 0; i < data.Length; i += 2)
                        {
                            // Il canale alfa viene memorizzato per ultimo, dopo i componenti del colore.
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
    /// Elabora i dati grezzi caricati. Questo metodo viene richiamato ogni volta che viene caricata una nuova porzione di dati grezzi.
    /// </summary>
    /// <param name="dataRectangle">Il rettangolo dei dati grezzi.</param>
    /// <param name="data">I dati grezzi.</param>
    /// <param name="start">Il punto dati iniziale.</param>
    /// <param name="end">Il punto dati finale.</param>
    /// <param name="loadOptions">Le opzioni di caricamento.</param>
    public void Process(Aspose.Imaging.Rectangle dataRectangle, byte[] data, Aspose.Imaging.Point start, Aspose.Imaging.Point end, Aspose.Imaging.LoadOptions loadOptions)
    {
        this.Process(dataRectangle, data, start, end);
    }
}
```

### Guarda anche

* struct [Rectangle](../../rectangle)
* class [RawDataSettings](../../rawdatasettings)
* interface [IPartialRawDataLoader](../../ipartialrawdataloader)
* class [RasterImage](../../rasterimage)
* spazio dei nomi [Aspose.Imaging](../../rasterimage)
* assemblea [Aspose.Imaging](../../../)

---

## LoadRawData(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) {#loadrawdata_1}

Carica dati grezzi.

```csharp
public void LoadRawData(Rectangle rectangle, Rectangle destImageBounds, 
    RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | Rectangle | Il rettangolo da cui caricare i dati grezzi. |
| destImageBounds | Rectangle | L'immagine più lontana si limita. |
| rawDataSettings | RawDataSettings | Le impostazioni dei dati grezzi da utilizzare per i dati caricati. Nota se i dati non sono nel formato specificato, verrà eseguita la conversione dei dati. |
| rawDataLoader | IPartialRawDataLoader | Il caricatore di dati grezzi. |

### Guarda anche

* struct [Rectangle](../../rectangle)
* class [RawDataSettings](../../rawdatasettings)
* interface [IPartialRawDataLoader](../../ipartialrawdataloader)
* class [RasterImage](../../rasterimage)
* spazio dei nomi [Aspose.Imaging](../../rasterimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
