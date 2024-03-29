---
title: ToArgb
second_title: Aspose.Imaging for .NET API Referansı
description: CMYK renklerinden ARGB renklerine dönüştürme.
type: docs
weight: 60
url: /tr/net/aspose.imaging/cmykcolorhelper/toargb/
---
## ToArgb(int[]) {#toargb_1}

CMYK renklerinden ARGB renklerine dönüştürme.

```csharp
public static Color[] ToArgb(int[] cmykPixels)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| cmykPixels | Int32[] | CMYK renkleri 32 bit tamsayı değerleri olarak sunulur. |

### Geri dönüş değeri

ARGB renkleri.

### Ayrıca bakınız

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* ad alanı [Aspose.Imaging](../../cmykcolorhelper)
* toplantı [Aspose.Imaging](../../../)

---

## ToArgb(int) {#toargb}

CMYK renginden ARGB rengine dönüştürme.

```csharp
public static Color ToArgb(int cmykPixel)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| cmykPixel | Int32 | 32 bit tamsayı değeri olarak sunulan CMYK rengi. |

### Geri dönüş değeri

ARGB rengi.

### Örnekler

Aşağıdaki örnek, ICC profillerini kullanmadan basit formülleri izleyerek CMYK renklerinin RGB karşılıklarına hızlı bir şekilde nasıl dönüştürüleceğini gösterir.

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),   // Camgöbeği
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),   // Macenta
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),   // Sarı
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),   // Siyah
};

System.Console.WriteLine("Convert CMYK to RGB without using ICC profiles.");
foreach (int cmykColor in cmykColors)
{
    Aspose.Imaging.Color rgbColor = Aspose.Imaging.CmykColorHelper.ToArgb(cmykColor);
    int c = Aspose.Imaging.CmykColorHelper.GetC(cmykColor);
    int m = Aspose.Imaging.CmykColorHelper.GetM(cmykColor);
    int y = Aspose.Imaging.CmykColorHelper.GetY(cmykColor);
    int k = Aspose.Imaging.CmykColorHelper.GetK(cmykColor);

    System.Console.WriteLine("CMYK({0},{1},{2},{3})\t\t=> RGB({4},{5},{6})", c, m, y, k, rgbColor.R, rgbColor.G, rgbColor.B);
}

// Çıktı şöyle görünür:
//ICC profillerini kullanmadan CMYK'yi RGB'ye dönüştürün.
//CMYK(255,0,0,0) => RGB(0,255,255)
//CMYK(0,255,0,0) => RGB(255,0,255)
//CMYK(0,0,255,0) => RGB(255,255,0)
//CMYK(0,0,0,255) => RGB(0,0,0)
```

### Ayrıca bakınız

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* ad alanı [Aspose.Imaging](../../cmykcolorhelper)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
