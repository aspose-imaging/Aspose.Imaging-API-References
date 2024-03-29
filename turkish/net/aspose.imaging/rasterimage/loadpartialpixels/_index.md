---
title: LoadPartialPixels
second_title: Aspose.Imaging for .NET API Referansı
description: Pikselleri paketlere göre kısmen yükler.
type: docs
weight: 400
url: /tr/net/aspose.imaging/rasterimage/loadpartialpixels/
---
## RasterImage.LoadPartialPixels method

Pikselleri paketlere göre kısmen yükler.

```csharp
public void LoadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| desiredRectangle | Rectangle | İstenilen dikdörtgen. |
| pixelLoader | IPartialPixelLoader | Piksel yükleyici. |

### Örnekler

Aşağıdaki örnek, kendi kısmi işlemcinizi kullanarak bir raster görüntünün piksellerini nasıl yükleyeceğinizi ve işleyeceğinizi gösterir. Örneğin, bir görüntünün tamamen saydam piksellerini sayma problemini ele alalım. Kısmi yükleme mekanizması kullanarak şeffaf saymak için Aspose.Imaging.IPartialPixelLoader uygulayan ayrı bir TransparentPixelCounter sınıfı tanıtılmıştır.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\alpha.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Aspose.Imaging.IPartialPixelLoader'ın bir örneğini oluşturun ve bunu Aspose.Imaging.RasterImage.LoadPartialPixels'e iletin
    TransparentPixelCounter counter = new TransparentPixelCounter();

    // Tüm görüntü için pikselleri yükleyin. Resmin herhangi bir dikdörtgen kısmı Aspose.Imaging.RasterImage.LoadPartialPixels yönteminin ilk parametresi olarak belirtilebilir.
    rasterImage.LoadPartialPixels(rasterImage.Bounds, counter);

    System.Console.WriteLine("The number of fully transparent pixels is {0}", counter.Count);
    System.Console.WriteLine("The total number of pixels is {0}", image.Width * image.Height);
}

// Sayaç şöyle görünebilir:
/// <summary>
/// Alfa kanalı değeri 0 olan tamamen saydam piksellerin sayısını sayar.
/// </summary>
private class TransparentPixelCounter : IPartialPixelLoader
{
    /// <summary>
    /// Tamamen saydam piksellerin sayısı.
    /// </summary>
    private int count;

    /// <summary>
    /// Tamamen saydam piksellerin sayısını alır.
    /// </summary>
    public int Count
    {
        get { return this.count; }
    }

    /// <summary>
    /// Yüklenen pikselleri işler. Bu yöntem, yeni bir piksel bölümü yüklendiğinde her zaman geri çağrılır.
    /// </summary>
    /// <param name="pixelsRectangle">Piksel dikdörtgeni.</param>
    /// <param name="pikseller">32 bit ARGB pikselleri.</param>
    /// <param name="start">Başlangıç piksel noktası.</param>
    /// <param name="end">Bitiş piksel noktası.</param>
    public void Process(Aspose.Imaging.Rectangle pixelsRectangle, Aspose.Imaging.Color[] pixels, Aspose.Imaging.Point start, Aspose.Imaging.Point end)
    {
        foreach (Color pixel in pixels)
        {
            if (pixel.A == 0)
            {
                this.count++;
            }
        }
    }
}
```

### Ayrıca bakınız

* struct [Rectangle](../../rectangle)
* interface [IPartialPixelLoader](../../ipartialpixelloader)
* class [RasterImage](../../rasterimage)
* ad alanı [Aspose.Imaging](../../rasterimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
