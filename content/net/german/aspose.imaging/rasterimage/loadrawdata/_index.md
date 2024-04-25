---
title: LoadRawData
second_title: Aspose.Imaging für .NET-API-Referenz
description: Lädt Rohdaten.
type: docs
weight: 420
url: /de/aspose.imaging/rasterimage/loadrawdata/
---
## LoadRawData(Rectangle, RawDataSettings, IPartialRawDataLoader) {#loadrawdata}

Lädt Rohdaten.

```csharp
public void LoadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, 
    IPartialRawDataLoader rawDataLoader)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | Rectangle | Das Rechteck, aus dem Rohdaten geladen werden sollen. |
| rawDataSettings | RawDataSettings | Die für geladene Daten zu verwendenden Rohdateneinstellungen. Beachten Sie, dass die Datenkonvertierung durchgeführt wird, wenn die Daten nicht im angegebenen Format vorliegen. |
| rawDataLoader | IPartialRawDataLoader | Der Rohdatenlader. |

### Beispiele

Das folgende Beispiel zeigt, wie mit RawDataSettings Pixel aus den Rohbilddaten extrahiert werden. Betrachten wir zum Beispiel ein Problem des Zählens von vollständig transparenten Pixeln eines Bildes.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\GrayscaleWithAlpha.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
    Aspose.Imaging.RawDataSettings settings = rasterImage.RawDataSettings;

    TransparentPixelRawDataCounter rawDataLoader = new TransparentPixelRawDataCounter(settings);

    // Pixel für das ganze Bild laden. Jeder rechteckige Teil des Bildes kann als Parameter der Aspose.Imaging.RasterImage.LoadRawData-Methode angegeben werden.
    rasterImage.LoadRawData(rasterImage.Bounds, settings, rawDataLoader);

    System.Console.WriteLine("The number of fully transparent pixels is {0}", rawDataLoader.Count);
    System.Console.WriteLine("The total number of pixels is {0}", image.Width * image.Height);
}

// Bei Rohdaten kann der Zähler so aussehen:
/// <summary>
/// Zählt die Anzahl der vollständig transparenten Pixel mit einem Alphakanalwert von 0.
/// </summary>
private class TransparentPixelRawDataCounter : IPartialRawDataLoader
{
    /// <summary>
    /// Die Anzahl der vollständig transparenten Pixel.
    /// </summary>
    private int count;

    /// <summary>
    /// Die Rohdateneinstellungen des geladenen Bildes.
    /// </summary>
    private Aspose.Imaging.RawDataSettings rawDataSettings;

    /// <summary>
    /// Ruft die Anzahl der vollständig transparenten Pixel ab.
    /// </summary>
    public int Count
    {
        get { return this.count; }
    }

    /// <summary>
    /// Initialisiert eine neue Instanz des <siehe TransparentPixelRawDataCounter /> Klasse.
    /// </summary>
    /// <param name="settings">Die Rohdateneinstellungen ermöglichen das Extrahieren von Farbkomponenten aus den Rohdaten.</param>
    public TransparentPixelRawDataCounter(Aspose.Imaging.RawDataSettings settings)
    {
        this.rawDataSettings = settings;
        this.count = 0;
    }

    /// <summary>
    /// Verarbeitet die geladenen Rohdaten. Diese Methode wird jedes Mal aufgerufen, wenn ein neuer Teil der Rohdaten geladen wird.
    /// </summary>
    /// <param name="dataRectangle">Das Rohdatenrechteck.</param>
    /// <param name="data">Die Rohdaten.</param>
    /// <param name="start">Der Startdatenpunkt.</param>
    /// <param name="end">Der Enddatenpunkt.</param>
    public void Process(Aspose.Imaging.Rectangle dataRectangle, byte[] data, Aspose.Imaging.Point start, Aspose.Imaging.Point end)
    {
        int[] channelBits = this.rawDataSettings.PixelDataFormat.ChannelBits;

        // Hier werden nur einfache Formate berücksichtigt, um den Code zu vereinfachen.
        // Betrachten wir nur Bilder mit 8 Bit pro Sample.
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
                            // Der Alphakanal wird zuletzt nach den Farbkomponenten gespeichert.
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
                        // Graustufen-Alpha
                        for (int i = 0; i < data.Length; i += 2)
                        {
                            // Der Alphakanal wird zuletzt nach den Farbkomponenten gespeichert.
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
    /// Verarbeitet die geladenen Rohdaten. Diese Methode wird jedes Mal aufgerufen, wenn ein neuer Teil der Rohdaten geladen wird.
    /// </summary>
    /// <param name="dataRectangle">Das Rohdatenrechteck.</param>
    /// <param name="data">Die Rohdaten.</param>
    /// <param name="start">Der Startdatenpunkt.</param>
    /// <param name="end">Der Enddatenpunkt.</param>
    /// <param name="loadOptions">Die Ladeoptionen.</param>
    public void Process(Aspose.Imaging.Rectangle dataRectangle, byte[] data, Aspose.Imaging.Point start, Aspose.Imaging.Point end, Aspose.Imaging.LoadOptions loadOptions)
    {
        this.Process(dataRectangle, data, start, end);
    }
}
```

### Siehe auch

* struct [Rectangle](../../rectangle)
* class [RawDataSettings](../../rawdatasettings)
* interface [IPartialRawDataLoader](../../ipartialrawdataloader)
* class [RasterImage](../../rasterimage)
* namensraum [Aspose.Imaging](../../rasterimage)
* Montage [Aspose.Imaging](../../../)

---

## LoadRawData(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) {#loadrawdata_1}

Lädt Rohdaten.

```csharp
public void LoadRawData(Rectangle rectangle, Rectangle destImageBounds, 
    RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | Rectangle | Das Rechteck, aus dem Rohdaten geladen werden sollen. |
| destImageBounds | Rectangle | Die dest-Image-Grenzen. |
| rawDataSettings | RawDataSettings | Die für geladene Daten zu verwendenden Rohdateneinstellungen. Beachten Sie, dass die Datenkonvertierung durchgeführt wird, wenn die Daten nicht im angegebenen Format vorliegen. |
| rawDataLoader | IPartialRawDataLoader | Der Rohdatenlader. |

### Siehe auch

* struct [Rectangle](../../rectangle)
* class [RawDataSettings](../../rawdatasettings)
* interface [IPartialRawDataLoader](../../ipartialrawdataloader)
* class [RasterImage](../../rasterimage)
* namensraum [Aspose.Imaging](../../rasterimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
