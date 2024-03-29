---
title: ToCmyk
second_title: Aspose.Imaging for .NET API Referansı
description: ARGB renklerinden CMYK renklerine dönüştürme.
type: docs
weight: 90
url: /tr/net/aspose.imaging/cmykcolorhelper/tocmyk/
---
## ToCmyk(int[]) {#tocmyk_3}

ARGB renklerinden CMYK renklerine dönüştürme.

```csharp
public static int[] ToCmyk(int[] argbPixels)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| argbPixels | Int32[] | 32 bit tamsayı değerleri olarak sunulan ARGB renkleri. |

### Geri dönüş değeri

CMYK renkleri 32 bit tamsayı değerleri olarak sunulur.

### Ayrıca bakınız

* class [CmykColorHelper](../../cmykcolorhelper)
* ad alanı [Aspose.Imaging](../../cmykcolorhelper)
* toplantı [Aspose.Imaging](../../../)

---

## ToCmyk(int) {#tocmyk_1}

ARGB renginden CMYK rengine dönüştürme.

```csharp
public static int ToCmyk(int argbPixel)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| argbPixel | Int32 | 32 bit tamsayı değeri olarak sunulan ARGB rengi. |

### Geri dönüş değeri

32 bit tamsayı değeri olarak sunulan CMYK rengi.

### Ayrıca bakınız

* class [CmykColorHelper](../../cmykcolorhelper)
* ad alanı [Aspose.Imaging](../../cmykcolorhelper)
* toplantı [Aspose.Imaging](../../../)

---

## ToCmyk(Color) {#tocmyk}

ARGB renginden CMYK rengine dönüştürme.

```csharp
public static int ToCmyk(Color pixel)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pixel | Color | ARGB rengi. |

### Geri dönüş değeri

32 bit tamsayı değeri olarak sunulan CMYK rengi.

### Örnekler

Aşağıdaki örnek, Aspose.Imaging.RasterImage.SaveCmyk32Pixels yöntemini kullanarak bir raster görüntünün orta alanını siyah piksellerle doldurur.

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // CMYK renk uzayında siyahın tamsayı temsilini alın.
    int blackCmyk = Aspose.Imaging.CmykColorHelper.ToCmyk(Color.Black);

    // Siyah kare.
    int[] pixels = new int[(rasterImage.Width / 2) * (rasterImage.Height / 2)];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = blackCmyk;
    }

    // Resmin ortasına siyah kareyi çizin.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(rasterImage.Width / 4, rasterImage.Height / 4, rasterImage.Width / 2, rasterImage.Height / 2);
    rasterImage.SaveCmyk32Pixels(area, pixels);

    rasterImage.Save(dir + "sample.SaveCmyk32Pixels.png");
}
```

Aşağıdaki örnek, RGB renklerinin ICC profilleri uygulamadan CMYK karşılıklarına nasıl dönüştürüleceğini gösterir.

```csharp
[C#]

Aspose.Imaging.Color[] rgbColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
    Aspose.Imaging.Color.Blue,
};

System.Console.WriteLine("Convert RGB to CMYK without using ICC profiles.");
foreach (Aspose.Imaging.Color rgbColor in rgbColors)
{
    int cmyk = Aspose.Imaging.CmykColorHelper.ToCmyk(rgbColor);
    int c = Aspose.Imaging.CmykColorHelper.GetC(cmyk);
    int m = Aspose.Imaging.CmykColorHelper.GetM(cmyk);
    int y = Aspose.Imaging.CmykColorHelper.GetY(cmyk);
    int k = Aspose.Imaging.CmykColorHelper.GetK(cmyk);

    System.Console.WriteLine("RGB({0},{1},{2})\t\t=> CMYK({3},{4},{5},{6})", rgbColor.R, rgbColor.G, rgbColor.B, c, m, y, k);
}

// Çıktı şöyle görünür:
//ICC profillerini kullanmadan RGB'yi CMYK'ye dönüştürün.
//RGB(255,0,0) => CMYK(0,255,255,0)
//RGB(0,128,0) => CMYK(255,0,255,127)
//RGB(0,0,255) => CMYK(255,255,0,0)
```

### Ayrıca bakınız

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* ad alanı [Aspose.Imaging](../../cmykcolorhelper)
* toplantı [Aspose.Imaging](../../../)

---

## ToCmyk(Color[]) {#tocmyk_2}

ARGB renklerinden CMYK renklerine dönüştürme.

```csharp
public static int[] ToCmyk(Color[] pixels)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pixels | Color[] | ARGB renkleri. |

### Geri dönüş değeri

CMYK renkleri 32 bit tamsayı değerleri olarak sunulur.

### Ayrıca bakınız

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* ad alanı [Aspose.Imaging](../../cmykcolorhelper)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
