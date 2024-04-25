---
title: LoadRawData
second_title: Aspose.Imaging for .NET API Referansı
description: Ham verileri yükler.
type: docs
weight: 420
url: /tr/aspose.imaging/rasterimage/loadrawdata/
---
## LoadRawData(Rectangle, RawDataSettings, IPartialRawDataLoader) {#loadrawdata}

Ham verileri yükler.

```csharp
public void LoadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, 
    IPartialRawDataLoader rawDataLoader)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rectangle | Rectangle | Ham verilerin yükleneceği dikdörtgen. |
| rawDataSettings | RawDataSettings | Yüklenen veriler için kullanılacak ham veri ayarları. Veriler belirtilen biçimde değilse, veri dönüştürme işleminin gerçekleştirileceğini unutmayın. |
| rawDataLoader | IPartialRawDataLoader | Ham veri yükleyici. |

### Örnekler

Aşağıdaki örnek, RawDataSettings kullanılarak ham görüntü verilerinden piksellerin nasıl çıkarılacağını gösterir. Örneğin, bir görüntünün tamamen saydam piksellerini sayma problemini ele alalım.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\GrayscaleWithAlpha.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
    Aspose.Imaging.RawDataSettings settings = rasterImage.RawDataSettings;

    TransparentPixelRawDataCounter rawDataLoader = new TransparentPixelRawDataCounter(settings);

    // Tüm görüntü için pikselleri yükleyin. Resmin herhangi bir dikdörtgen kısmı Aspose.Imaging.RasterImage.LoadRawData yönteminin bir parametresi olarak belirtilebilir.
    rasterImage.LoadRawData(rasterImage.Bounds, settings, rawDataLoader);

    System.Console.WriteLine("The number of fully transparent pixels is {0}", rawDataLoader.Count);
    System.Console.WriteLine("The total number of pixels is {0}", image.Width * image.Height);
}

// Ham veri olması durumunda sayaç şöyle görünebilir:
/// <summary>
/// Alfa kanalı değeri 0 olan tamamen saydam piksellerin sayısını sayar.
/// </summary>
private class TransparentPixelRawDataCounter : IPartialRawDataLoader
{
    /// <summary>
    /// Tamamen saydam piksellerin sayısı.
    /// </summary>
    private int count;

    /// <summary>
    /// Yüklenen görüntünün ham veri ayarları.
    /// </summary>
    private Aspose.Imaging.RawDataSettings rawDataSettings;

    /// <summary>
    /// Tamamen saydam piksellerin sayısını alır.
    /// </summary>
    public int Count
    {
        get { return this.count; }
    }

    /// <summary>
    /// <see TransparentPixelRawDataCounter /> sınıf.
    /// </summary>
    /// <param name="settings">Ham veri ayarları, ham verilerden renk bileşenlerinin çıkarılmasına izin verir.</param>
    public TransparentPixelRawDataCounter(Aspose.Imaging.RawDataSettings settings)
    {
        this.rawDataSettings = settings;
        this.count = 0;
    }

    /// <summary>
    /// Yüklenen ham verileri işler. Bu yöntem, ham verilerin yeni bir kısmı yüklendiğinde her zaman geri çağrılır.
    /// </summary>
    /// <param name="dataRectangle">Ham veri dikdörtgeni.</param>
    /// <param name="data">Ham veriler.</param>
    /// <param name="start">Başlangıç veri noktası.</param>
    /// <param name="end">Bitiş veri noktası.</param>
    public void Process(Aspose.Imaging.Rectangle dataRectangle, byte[] data, Aspose.Imaging.Point start, Aspose.Imaging.Point end)
    {
        int[] channelBits = this.rawDataSettings.PixelDataFormat.ChannelBits;

        // Kodu basitleştirmek için burada yalnızca basit biçimler göz önünde bulundurulmuştur.
        // Örnek başına sadece 8 bitlik görüntüleri ele alalım.
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
                            // Alfa kanalı, renk bileşenlerinden sonra en son saklanır.
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
                        // Gri Tonlamalı Alfa
                        for (int i = 0; i < data.Length; i += 2)
                        {
                            // Alfa kanalı, renk bileşenlerinden sonra en son saklanır.
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
    /// Yüklenen ham verileri işler. Bu yöntem, ham verilerin yeni bir kısmı yüklendiğinde her zaman geri çağrılır.
    /// </summary>
    /// <param name="dataRectangle">Ham veri dikdörtgeni.</param>
    /// <param name="data">Ham veriler.</param>
    /// <param name="start">Başlangıç veri noktası.</param>
    /// <param name="end">Bitiş veri noktası.</param>
    /// <param name="loadOptions">Yükleme seçenekleri.</param>
    public void Process(Aspose.Imaging.Rectangle dataRectangle, byte[] data, Aspose.Imaging.Point start, Aspose.Imaging.Point end, Aspose.Imaging.LoadOptions loadOptions)
    {
        this.Process(dataRectangle, data, start, end);
    }
}
```

### Ayrıca bakınız

* struct [Rectangle](../../rectangle)
* class [RawDataSettings](../../rawdatasettings)
* interface [IPartialRawDataLoader](../../ipartialrawdataloader)
* class [RasterImage](../../rasterimage)
* ad alanı [Aspose.Imaging](../../rasterimage)
* toplantı [Aspose.Imaging](../../../)

---

## LoadRawData(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) {#loadrawdata_1}

Ham verileri yükler.

```csharp
public void LoadRawData(Rectangle rectangle, Rectangle destImageBounds, 
    RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rectangle | Rectangle | Ham verilerin yükleneceği dikdörtgen. |
| destImageBounds | Rectangle | Hedef görüntü sınırları. |
| rawDataSettings | RawDataSettings | Yüklenen veriler için kullanılacak ham veri ayarları. Veriler belirtilen biçimde değilse, veri dönüştürme işleminin gerçekleştirileceğini unutmayın. |
| rawDataLoader | IPartialRawDataLoader | Ham veri yükleyici. |

### Ayrıca bakınız

* struct [Rectangle](../../rectangle)
* class [RawDataSettings](../../rawdatasettings)
* interface [IPartialRawDataLoader](../../ipartialrawdataloader)
* class [RasterImage](../../rasterimage)
* ad alanı [Aspose.Imaging](../../rasterimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
