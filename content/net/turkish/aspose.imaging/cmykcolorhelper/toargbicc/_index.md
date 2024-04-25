---
title: ToArgbIcc
second_title: Aspose.Imaging for .NET API Referansı
description: Varsayılan profillerle Icc dönüştürme kullanılarak CMYK renklerinden ARGB renklerine dönüştürme.
type: docs
weight: 80
url: /tr/aspose.imaging/cmykcolorhelper/toargbicc/
---
## ToArgbIcc(int[]) {#toargbicc_2}

Varsayılan profillerle Icc dönüştürme kullanılarak CMYK renklerinden ARGB renklerine dönüştürme.

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| cmykPixels | Int32[] | CMYK pikselleri, 32 bit tamsayı değerleri olarak sunulur. |

### Geri dönüş değeri

ARGB renkleri.

### Ayrıca bakınız

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* ad alanı [Aspose.Imaging](../../cmykcolorhelper)
* toplantı [Aspose.Imaging](../../../)

---

## ToArgbIcc(int[], Stream, Stream) {#toargbicc_3}

Özel profillerle Icc dönüştürme kullanılarak CMYK renklerinden ARGB renklerine dönüştürme.

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels, Stream cmykIccStream, Stream rgbIccStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| cmykPixels | Int32[] | CMYK renkleri 32 bit tamsayı değerleri olarak sunulur. |
| cmykIccStream | Stream | CMYK Icc profilini içeren akış. |
| rgbIccStream | Stream | RGB Icc profilini içeren akış. |

### Geri dönüş değeri

ARGB renkleri.

### Ayrıca bakınız

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* ad alanı [Aspose.Imaging](../../cmykcolorhelper)
* toplantı [Aspose.Imaging](../../../)

---

## ToArgbIcc(int) {#toargbicc}

Varsayılan profillerle Icc dönüştürme kullanılarak CMYK renginden ARGB Rengine dönüştürme.

```csharp
public static Color ToArgbIcc(int cmykPixel)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| cmykPixel | Int32 | 32 bit tamsayı değeri olarak sunulan CMYK rengi. |

### Geri dönüş değeri

ARGB rengi.

### Örnekler

Aşağıdaki örnek, ICC profillerini kullanarak CMYK renklerinin RGB karşılıklarına nasıl dönüştürüleceğini gösterir.

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),   // Camgöbeği
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),   // Macenta
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),   // Sarı
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),   // Siyah
};

System.Console.WriteLine("Convert CMYK to RGB using default ICC profiles.");
foreach (int cmykColor in cmykColors)
{
    Aspose.Imaging.Color rgbColor = Aspose.Imaging.CmykColorHelper.ToArgbIcc(cmykColor);
    int c = Aspose.Imaging.CmykColorHelper.GetC(cmykColor);
    int m = Aspose.Imaging.CmykColorHelper.GetM(cmykColor);
    int y = Aspose.Imaging.CmykColorHelper.GetY(cmykColor);
    int k = Aspose.Imaging.CmykColorHelper.GetK(cmykColor);
        
    System.Console.WriteLine("CMYK({0},{1},{2},{3})\t\t=> RGB({4},{5},{6})", c, m, y, k, rgbColor.R, rgbColor.G, rgbColor.B);
}

// Özel RGB ve CMYK ICC profillerine giden yolunuzu belirtin.
string dir = "c:\\temp\\iccprofiles\\";

System.Console.WriteLine("Convert CMYK to RGB using custom ICC profiles.");
using (System.IO.Stream rgbProfileStream = System.IO.File.OpenRead(dir + "eciRGB_v2.icc"))
using (System.IO.Stream cmykProfileStream = System.IO.File.OpenRead(dir + "ISOcoated_v2_FullGamut4.icc"))
{
    foreach (int cmykColor in cmykColors)
    {
        Aspose.Imaging.Color rgbColor = Aspose.Imaging.CmykColorHelper.ToArgbIcc(cmykColor);
        int c = Aspose.Imaging.CmykColorHelper.GetC(cmykColor);
        int m = Aspose.Imaging.CmykColorHelper.GetM(cmykColor);
        int y = Aspose.Imaging.CmykColorHelper.GetY(cmykColor);
        int k = Aspose.Imaging.CmykColorHelper.GetK(cmykColor);
            
        System.Console.WriteLine("CMYK({0},{1},{2},{3})\t\t=> RGB({4},{5},{6})", c, m, y, k, rgbColor.R, rgbColor.G, rgbColor.B);
    }
}

// Çıktı şöyle görünür:
//Varsayılan ICC profillerini kullanarak CMYK'yi RGB'ye dönüştürün.            
//CMYK(255,0,0,0) => RGB(46,188,220)
//CMYK(0,255,0,0) => RGB(231,52,142)
//CMYK(0,0,255,0) => RGB(244,253,63)
//CMYK(0,0,0,255) => RGB(21,21,21)
//Özel ICC profillerini kullanarak CMYK'yi RGB'ye dönüştürün.
//CMYK(255,0,0,0) => RGB(46,188,220)
//CMYK(0,255,0,0) => RGB(231,52,142)
//(0,0,255,0) => RGB(244,253,63)
//CMYK(0,0,0,255) => RGB(21,21,21)
```

### Ayrıca bakınız

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* ad alanı [Aspose.Imaging](../../cmykcolorhelper)
* toplantı [Aspose.Imaging](../../../)

---

## ToArgbIcc(int, Stream, Stream) {#toargbicc_1}

Özel profille Icc dönüştürme kullanılarak CMYK renginden ARGB rengine dönüştürme.

```csharp
public static Color ToArgbIcc(int cmykPixel, Stream cmykIccStream, Stream rgbIccStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| cmykPixel | Int32 | 32 bit tamsayı değeri olarak sunulan CMYK rengi. |
| cmykIccStream | Stream | CMYK Icc profilini içeren akış. |
| rgbIccStream | Stream | RGB Icc profilini içeren akış. |

### Geri dönüş değeri

ARGB rengi.

### Örnekler

Aşağıdaki örnek, ICC profillerini kullanarak CMYK renklerinin RGB karşılıklarına nasıl dönüştürüleceğini gösterir.

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),   // Camgöbeği
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),   // Macenta
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),   // Sarı
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),   // Siyah
};

System.Console.WriteLine("Convert CMYK to RGB using default ICC profiles.");
foreach (int cmykColor in cmykColors)
{
    Aspose.Imaging.Color rgbColor = Aspose.Imaging.CmykColorHelper.ToArgbIcc(cmykColor);
    int c = Aspose.Imaging.CmykColorHelper.GetC(cmykColor);
    int m = Aspose.Imaging.CmykColorHelper.GetM(cmykColor);
    int y = Aspose.Imaging.CmykColorHelper.GetY(cmykColor);
    int k = Aspose.Imaging.CmykColorHelper.GetK(cmykColor);
        
    System.Console.WriteLine("CMYK({0},{1},{2},{3})\t\t=> RGB({4},{5},{6})", c, m, y, k, rgbColor.R, rgbColor.G, rgbColor.B);
}

// Özel RGB ve CMYK ICC profillerine giden yolunuzu belirtin.
string dir = "c:\\temp\\iccprofiles\\";

System.Console.WriteLine("Convert CMYK to RGB using custom ICC profiles.");
using (System.IO.Stream rgbProfileStream = System.IO.File.OpenRead(dir + "eciRGB_v2.icc"))
using (System.IO.Stream cmykProfileStream = System.IO.File.OpenRead(dir + "ISOcoated_v2_FullGamut4.icc"))
{
    foreach (int cmykColor in cmykColors)
    {
        Aspose.Imaging.Color rgbColor = Aspose.Imaging.CmykColorHelper.ToArgbIcc(cmykColor);
        int c = Aspose.Imaging.CmykColorHelper.GetC(cmykColor);
        int m = Aspose.Imaging.CmykColorHelper.GetM(cmykColor);
        int y = Aspose.Imaging.CmykColorHelper.GetY(cmykColor);
        int k = Aspose.Imaging.CmykColorHelper.GetK(cmykColor);
            
        System.Console.WriteLine("CMYK({0},{1},{2},{3})\t\t=> RGB({4},{5},{6})", c, m, y, k, rgbColor.R, rgbColor.G, rgbColor.B);
    }
}

// Çıktı şöyle görünür:
//Varsayılan ICC profillerini kullanarak CMYK'yi RGB'ye dönüştürün.            
//CMYK(255,0,0,0) => RGB(46,188,220)
//CMYK(0,255,0,0) => RGB(231,52,142)
//CMYK(0,0,255,0) => RGB(244,253,63)
//CMYK(0,0,0,255) => RGB(21,21,21)
//Özel ICC profillerini kullanarak CMYK'yi RGB'ye dönüştürün.
//CMYK(255,0,0,0) => RGB(46,188,220)
//CMYK(0,255,0,0) => RGB(231,52,142)
//(0,0,255,0) => RGB(244,253,63)
//CMYK(0,0,0,255) => RGB(21,21,21)
```

### Ayrıca bakınız

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* ad alanı [Aspose.Imaging](../../cmykcolorhelper)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
