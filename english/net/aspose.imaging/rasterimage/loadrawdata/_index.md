---
title: RasterImage.LoadRawData
second_title: Aspose.Imaging for .NET API Reference
description: RasterImage method. Loads raw data
type: docs
weight: 430
url: /net/aspose.imaging/rasterimage/loadrawdata/
---
## LoadRawData(Rectangle, RawDataSettings, IPartialRawDataLoader) {#loadrawdata}

Loads raw data.

```csharp
public void LoadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, 
    IPartialRawDataLoader rawDataLoader)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | Rectangle | The rectangle to load raw data from. |
| rawDataSettings | RawDataSettings | The raw data settings to use for loaded data. Note if data is not in the format specified then data conversion will be performed. |
| rawDataLoader | IPartialRawDataLoader | The raw data loader. |

## Examples

The following example shows how to extract pixels from the raw image data using RawDataSettings. For example, consider a problem of counting of fully transparent pixels of an image.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\GrayscaleWithAlpha.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
    Aspose.Imaging.RawDataSettings settings = rasterImage.RawDataSettings;

    TransparentPixelRawDataCounter rawDataLoader = new TransparentPixelRawDataCounter(settings);

    // Load pixels for the whole image. Any rectangular part of the image can be specified as a parameter of the Aspose.Imaging.RasterImage.LoadRawData method.
    rasterImage.LoadRawData(rasterImage.Bounds, settings, rawDataLoader);

    System.Console.WriteLine("The number of fully transparent pixels is {0}", rawDataLoader.Count);
    System.Console.WriteLine("The total number of pixels is {0}", image.Width * image.Height);
}

// In case of raw data, the counter may look like this:
/// <summary>
/// Counts the number of fully transparent pixels with alpha channel value of 0.
/// </summary>
private class TransparentPixelRawDataCounter : IPartialRawDataLoader
{
    /// <summary>
    /// The number of fully transparent pixels.
    /// </summary>
    private int count;

    /// <summary>
    /// The raw data settings of the loaded image.
    /// </summary>
    private Aspose.Imaging.RawDataSettings rawDataSettings;

    /// <summary>
    /// Gets the number of fully transparent pixels.
    /// </summary>
    public int Count
    {
        get { return this.count; }
    }

    /// <summary>
    /// Initializes a new instance of the <see TransparentPixelRawDataCounter /> class.
    /// </summary>
    /// <param name="settings">The raw data settings allow to extract color components from raw data.</param>
    public TransparentPixelRawDataCounter(Aspose.Imaging.RawDataSettings settings)
    {
        this.rawDataSettings = settings;
        this.count = 0;
    }

    /// <summary>
    /// Processes the loaded raw data. This method is called back every time when a new portion of raw data is loaded.
    /// </summary>
    /// <param name="dataRectangle">The raw data rectangle.</param>
    /// <param name="data">The raw data.</param>
    /// <param name="start">The start data point.</param>
    /// <param name="end">The end data point.</param>
    public void Process(Aspose.Imaging.Rectangle dataRectangle, byte[] data, Aspose.Imaging.Point start, Aspose.Imaging.Point end)
    {
        int[] channelBits = this.rawDataSettings.PixelDataFormat.ChannelBits;

        // Only simple formats are consdired here to simplify the code.
        // Let's consider only images with 8 bits per sample.
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
                            // The alpha channel is stored last, after the color components.
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
                        // Grayscale Alpha
                        for (int i = 0; i < data.Length; i += 2)
                        {
                            // The alpha channel is stored last, after the color components.
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
    /// Processes the loaded raw data. This method is called back every time when a new portion of raw data is loaded.
    /// </summary>
    /// <param name="dataRectangle">The raw data rectangle.</param>
    /// <param name="data">The raw data.</param>
    /// <param name="start">The start data point.</param>
    /// <param name="end">The end data point.</param>
    /// <param name="loadOptions">The load options.</param>
    public void Process(Aspose.Imaging.Rectangle dataRectangle, byte[] data, Aspose.Imaging.Point start, Aspose.Imaging.Point end, Aspose.Imaging.LoadOptions loadOptions)
    {
        this.Process(dataRectangle, data, start, end);
    }
}
```

### See Also

* struct [Rectangle](../../rectangle/)
* class [RawDataSettings](../../rawdatasettings/)
* interface [IPartialRawDataLoader](../../ipartialrawdataloader/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)

---

## LoadRawData(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) {#loadrawdata_1}

Loads raw data.

```csharp
public void LoadRawData(Rectangle rectangle, Rectangle destImageBounds, 
    RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | Rectangle | The rectangle to load raw data from. |
| destImageBounds | Rectangle | The dest image bounds. |
| rawDataSettings | RawDataSettings | The raw data settings to use for loaded data. Note if data is not in the format specified then data conversion will be performed. |
| rawDataLoader | IPartialRawDataLoader | The raw data loader. |

### See Also

* struct [Rectangle](../../rectangle/)
* class [RawDataSettings](../../rawdatasettings/)
* interface [IPartialRawDataLoader](../../ipartialrawdataloader/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


