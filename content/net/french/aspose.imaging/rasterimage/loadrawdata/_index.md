---
title: LoadRawData
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Charge les données brutes.
type: docs
weight: 420
url: /fr/aspose.imaging/rasterimage/loadrawdata/
---
## LoadRawData(Rectangle, RawDataSettings, IPartialRawDataLoader) {#loadrawdata}

Charge les données brutes.

```csharp
public void LoadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, 
    IPartialRawDataLoader rawDataLoader)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| rectangle | Rectangle | Le rectangle à partir duquel charger les données brutes. |
| rawDataSettings | RawDataSettings | Les paramètres de données brutes à utiliser pour les données chargées. Notez que si les données ne sont pas au format spécifié, la conversion des données sera effectuée. |
| rawDataLoader | IPartialRawDataLoader | Le chargeur de données brutes. |

### Exemples

L'exemple suivant montre comment extraire des pixels des données d'image brutes à l'aide de RawDataSettings. Par exemple, considérons un problème de comptage de pixels entièrement transparents d'une image.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\GrayscaleWithAlpha.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
    Aspose.Imaging.RawDataSettings settings = rasterImage.RawDataSettings;

    TransparentPixelRawDataCounter rawDataLoader = new TransparentPixelRawDataCounter(settings);

    // Charge les pixels pour toute l'image. Toute partie rectangulaire de l'image peut être spécifiée en tant que paramètre de la méthode Aspose.Imaging.RasterImage.LoadRawData.
    rasterImage.LoadRawData(rasterImage.Bounds, settings, rawDataLoader);

    System.Console.WriteLine("The number of fully transparent pixels is {0}", rawDataLoader.Count);
    System.Console.WriteLine("The total number of pixels is {0}", image.Width * image.Height);
}

// En cas de données brutes, le compteur peut ressembler à ceci :
/// <summary>
/// Compte le nombre de pixels entièrement transparents avec une valeur de canal alpha de 0.
/// </summary>
private class TransparentPixelRawDataCounter : IPartialRawDataLoader
{
    /// <summary>
    /// Le nombre de pixels entièrement transparents.
    /// </summary>
    private int count;

    /// <summary>
    /// Les paramètres de données brutes de l'image chargée.
    /// </summary>
    private Aspose.Imaging.RawDataSettings rawDataSettings;

    /// <summary>
    /// Obtient le nombre de pixels entièrement transparents.
    /// </summary>
    public int Count
    {
        get { return this.count; }
    }

    /// <summary>
    /// Initialise une nouvelle instance de <voir TransparentPixelRawDataCounter /> classer.
    /// </summary>
    /// <param name="settings">Les paramètres des données brutes permettent d'extraire les composants de couleur des données brutes.</param>
    public TransparentPixelRawDataCounter(Aspose.Imaging.RawDataSettings settings)
    {
        this.rawDataSettings = settings;
        this.count = 0;
    }

    /// <summary>
    /// Traite les données brutes chargées. Cette méthode est rappelée à chaque fois qu'une nouvelle portion de données brutes est chargée.
    /// </summary>
    /// <param name="dataRectangle">Le rectangle de données brutes.</param>
    /// <param name="data">Les données brutes.</param>
    /// <param name="start">Le point de données de départ.</param>
    /// <param name="end">Le point de données final.</param>
    public void Process(Aspose.Imaging.Rectangle dataRectangle, byte[] data, Aspose.Imaging.Point start, Aspose.Imaging.Point end)
    {
        int[] channelBits = this.rawDataSettings.PixelDataFormat.ChannelBits;

        // Seuls les formats simples sont considérés ici pour simplifier le code.
        // Considérons uniquement les images avec 8 bits par échantillon.
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
                            // Le canal alpha est stocké en dernier, après les composants de couleur.
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
                        // Niveaux de gris Alpha
                        for (int i = 0; i < data.Length; i += 2)
                        {
                            // Le canal alpha est stocké en dernier, après les composants de couleur.
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
    /// Traite les données brutes chargées. Cette méthode est rappelée à chaque fois qu'une nouvelle portion de données brutes est chargée.
    /// </summary>
    /// <param name="dataRectangle">Le rectangle de données brutes.</param>
    /// <param name="data">Les données brutes.</param>
    /// <param name="start">Le point de données de départ.</param>
    /// <param name="end">Le point de données final.</param>
    /// <param name="loadOptions">Les options de chargement.</param>
    public void Process(Aspose.Imaging.Rectangle dataRectangle, byte[] data, Aspose.Imaging.Point start, Aspose.Imaging.Point end, Aspose.Imaging.LoadOptions loadOptions)
    {
        this.Process(dataRectangle, data, start, end);
    }
}
```

### Voir également

* struct [Rectangle](../../rectangle)
* class [RawDataSettings](../../rawdatasettings)
* interface [IPartialRawDataLoader](../../ipartialrawdataloader)
* class [RasterImage](../../rasterimage)
* espace de noms [Aspose.Imaging](../../rasterimage)
* Assemblée [Aspose.Imaging](../../../)

---

## LoadRawData(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) {#loadrawdata_1}

Charge les données brutes.

```csharp
public void LoadRawData(Rectangle rectangle, Rectangle destImageBounds, 
    RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| rectangle | Rectangle | Le rectangle à partir duquel charger les données brutes. |
| destImageBounds | Rectangle | L'image dest délimite. |
| rawDataSettings | RawDataSettings | Les paramètres de données brutes à utiliser pour les données chargées. Notez que si les données ne sont pas au format spécifié, la conversion des données sera effectuée. |
| rawDataLoader | IPartialRawDataLoader | Le chargeur de données brutes. |

### Voir également

* struct [Rectangle](../../rectangle)
* class [RawDataSettings](../../rawdatasettings)
* interface [IPartialRawDataLoader](../../ipartialrawdataloader)
* class [RasterImage](../../rasterimage)
* espace de noms [Aspose.Imaging](../../rasterimage)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
