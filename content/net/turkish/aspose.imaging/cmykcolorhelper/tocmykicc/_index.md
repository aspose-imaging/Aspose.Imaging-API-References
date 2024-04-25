---
title: ToCmykIcc
second_title: Aspose.Imaging for .NET API Referansı
description: Özel profillerle Icc dönüştürme kullanılarak ARGB renklerinden CMYK renklerine dönüştürme.
type: docs
weight: 110
url: /tr/aspose.imaging/cmykcolorhelper/tocmykicc/
---
## ToCmykIcc(Color[], Stream, Stream) {#tocmykicc_3}

Özel profillerle Icc dönüştürme kullanılarak ARGB renklerinden CMYK renklerine dönüştürme.

```csharp
public static int[] ToCmykIcc(Color[] pixels, Stream rgbIccStream, Stream cmykIccStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pixels | Color[] | ARGB renkleri. |
| rgbIccStream | Stream | RGB Icc profilini içeren akış. |
| cmykIccStream | Stream | CMYK Icc profilini içeren akış. |

### Geri dönüş değeri

CMYK renkleri 32 bit tamsayı değerleri olarak sunulur.

### Ayrıca bakınız

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* ad alanı [Aspose.Imaging](../../cmykcolorhelper)
* toplantı [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color[]) {#tocmykicc_2}

Varsayılan profillerle Icc dönüştürme kullanılarak ARGB renklerinden CMYK renklerine dönüştürme.

```csharp
public static int[] ToCmykIcc(Color[] pixels)
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

---

## ToCmykIcc(Color) {#tocmykicc}

Varsayılan profillerle Icc dönüştürme kullanılarak ARGB renginden CMYK rengine dönüştürme.

```csharp
public static int ToCmykIcc(Color pixel)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pixel | Color | ARGB rengi. |

### Geri dönüş değeri

32 bit tamsayı değeri olarak sunulan CMYK rengi.

### Örnekler

Aşağıdaki örnek, ICC profilleri kullanılarak RGB renklerinin CMYK karşılıklarına nasıl dönüştürüleceğini gösterir.

```csharp
[C#]

Aspose.Imaging.Color[] rgbColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
    Aspose.Imaging.Color.Blue,
};

System.Console.WriteLine("Convert RGB to CMYK using default ICC profiles.");
foreach (Aspose.Imaging.Color rgbColor in rgbColors)
{
    int cmyk = Aspose.Imaging.CmykColorHelper.ToCmykIcc(rgbColor);
    int c = Aspose.Imaging.CmykColorHelper.GetC(cmyk);
    int m = Aspose.Imaging.CmykColorHelper.GetM(cmyk);
    int y = Aspose.Imaging.CmykColorHelper.GetY(cmyk);
    int k = Aspose.Imaging.CmykColorHelper.GetK(cmyk);

    System.Console.WriteLine("RGB({0},{1},{2})\t\t=> CMYK({3},{4},{5},{6})", rgbColor.R, rgbColor.G, rgbColor.B, c, m, y, k);
}

// RGB ve CMYK ICC profillerine giden yolunuzu belirtin.
string dir = "c:\\temp\\iccprofiles\\";

System.Console.WriteLine("Convert RGB to CMYK using custom ICC profiles.");
using (System.IO.Stream rgbProfileStream = System.IO.File.OpenRead(dir + "eciRGB_v2.icc"))
using (System.IO.Stream cmykProfileStream = System.IO.File.OpenRead(dir + "ISOcoated_v2_FullGamut4.icc"))
{
    foreach (Aspose.Imaging.Color rgbColor in rgbColors)
    {
        int cmyk = Aspose.Imaging.CmykColorHelper.ToCmykIcc(rgbColor, rgbProfileStream, cmykProfileStream);
        int c = Aspose.Imaging.CmykColorHelper.GetC(cmyk);
        int m = Aspose.Imaging.CmykColorHelper.GetM(cmyk);
        int y = Aspose.Imaging.CmykColorHelper.GetY(cmyk);
        int k = Aspose.Imaging.CmykColorHelper.GetK(cmyk);

        System.Console.WriteLine("RGB({0},{1},{2})\t\t=> CMYK({3},{4},{5},{6})", rgbColor.R, rgbColor.G, rgbColor.B, c, m, y, k);
    }
}

// Çıktı şöyle görünür:
//Varsayılan ICC profillerini kullanarak RGB'yi CMYK'ya dönüştürün.
//RGB(255,0,0) => CMYK(0,254,249,15)
//RGB(0,128,0) => CMYK(247,21,254,85)
//RGB(0,0,255) => CMYK(254,195,0,134)
//Özel ICC profillerini kullanarak RGB'yi CMYK'ya dönüştürün.
//RGB(255,0,0) => CMYK(0,207,219,0)
//RGB(0,128,0) => CMYK(238,16,254,80)
//RGB(0,0,255) => CMYK(242.182,0,0)
```

### Ayrıca bakınız

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* ad alanı [Aspose.Imaging](../../cmykcolorhelper)
* toplantı [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color, Stream, Stream) {#tocmykicc_1}

Özel profillerle Icc dönüştürme kullanılarak ARGB renginden CMYK rengine dönüştürme.

```csharp
public static int ToCmykIcc(Color pixel, Stream rgbIccStream, Stream cmykIccStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pixel | Color | ARGB rengi. |
| rgbIccStream | Stream | RGB Icc profilini içeren akış. |
| cmykIccStream | Stream | CMYK Icc profilini içeren akış. |

### Geri dönüş değeri

32 bit tamsayı değeri olarak sunulan CMYK rengi.

### Örnekler

Aşağıdaki örnek, ICC profilleri kullanılarak RGB renklerinin CMYK karşılıklarına nasıl dönüştürüleceğini gösterir.

```csharp
[C#]

Aspose.Imaging.Color[] rgbColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
    Aspose.Imaging.Color.Blue,
};

System.Console.WriteLine("Convert RGB to CMYK using default ICC profiles.");
foreach (Aspose.Imaging.Color rgbColor in rgbColors)
{
    int cmyk = Aspose.Imaging.CmykColorHelper.ToCmykIcc(rgbColor);
    int c = Aspose.Imaging.CmykColorHelper.GetC(cmyk);
    int m = Aspose.Imaging.CmykColorHelper.GetM(cmyk);
    int y = Aspose.Imaging.CmykColorHelper.GetY(cmyk);
    int k = Aspose.Imaging.CmykColorHelper.GetK(cmyk);

    System.Console.WriteLine("RGB({0},{1},{2})\t\t=> CMYK({3},{4},{5},{6})", rgbColor.R, rgbColor.G, rgbColor.B, c, m, y, k);
}

// RGB ve CMYK ICC profillerine giden yolunuzu belirtin.
string dir = "c:\\temp\\iccprofiles\\";

System.Console.WriteLine("Convert RGB to CMYK using custom ICC profiles.");
using (System.IO.Stream rgbProfileStream = System.IO.File.OpenRead(dir + "eciRGB_v2.icc"))
using (System.IO.Stream cmykProfileStream = System.IO.File.OpenRead(dir + "ISOcoated_v2_FullGamut4.icc"))
{
    foreach (Aspose.Imaging.Color rgbColor in rgbColors)
    {
        int cmyk = Aspose.Imaging.CmykColorHelper.ToCmykIcc(rgbColor, rgbProfileStream, cmykProfileStream);
        int c = Aspose.Imaging.CmykColorHelper.GetC(cmyk);
        int m = Aspose.Imaging.CmykColorHelper.GetM(cmyk);
        int y = Aspose.Imaging.CmykColorHelper.GetY(cmyk);
        int k = Aspose.Imaging.CmykColorHelper.GetK(cmyk);

        System.Console.WriteLine("RGB({0},{1},{2})\t\t=> CMYK({3},{4},{5},{6})", rgbColor.R, rgbColor.G, rgbColor.B, c, m, y, k);
    }
}

// Çıktı şöyle görünür:
//Varsayılan ICC profillerini kullanarak RGB'yi CMYK'ya dönüştürün.
//RGB(255,0,0) => CMYK(0,254,249,15)
//RGB(0,128,0) => CMYK(247,21,254,85)
//RGB(0,0,255) => CMYK(254,195,0,134)
//Özel ICC profillerini kullanarak RGB'yi CMYK'ya dönüştürün.
//RGB(255,0,0) => CMYK(0,207,219,0)
//RGB(0,128,0) => CMYK(238,16,254,80)
//RGB(0,0,255) => CMYK(242.182,0,0)
```

### Ayrıca bakınız

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* ad alanı [Aspose.Imaging](../../cmykcolorhelper)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
