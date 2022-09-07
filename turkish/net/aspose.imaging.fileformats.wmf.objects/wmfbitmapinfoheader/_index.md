---
title: WmfBitmapInfoHeader
second_title: Aspose.Imaging for .NET API Referansı
description: BitmapInfoHeader Nesnesi aygıttan bağımsız bir bitmapin DIB boyutları ve renk biçimi hakkında bilgi içerir.
type: docs
weight: 8470
url: /tr/net/aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/
---
## WmfBitmapInfoHeader class

BitmapInfoHeader Nesnesi, aygıttan bağımsız bir bitmap'in (DIB) boyutları ve renk biçimi hakkında bilgi içerir.

```csharp
public class WmfBitmapInfoHeader : WmfBitmapBaseHeader
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [WmfBitmapInfoHeader](wmfbitmapinfoheader)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BitCount](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/bitcount) { get; set; } | Her pikselin biçimini ve DIB'deki maksimum renk sayısını tanımlayan 16 bitlik işaretsiz bir tamsayı alır veya ayarlar. Bu değer [`BitCount`](../wmfbitmapbaseheader/bitcount) Numaralandırma (bölüm 2.1.1.3). |
| [ColorImportant](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/colorimportant) { get; set; } | DIB'yi görüntülemek için gereken renk dizinlerinin sayısını tanımlayan 32 bitlik işaretsiz bir tamsayı alır veya ayarlar. Bu değer sıfırsa, tüm renk dizinleri gereklidir |
| [ColorUsed](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/colorused) { get; set; } | DIB tarafından kullanılan renk tablosundaki dizinlerin sayısını belirten 32 bitlik işaretsiz bir tamsayı alır veya ayarlar, aşağıdaki gibi : Bu değer sıfırsa, DIB, BitCount değerine karşılık gelen maksimum renk sayısını kullanır. Bu değer sıfır değilse ve BitCount değeri 16'dan küçükse, bu değer DIB tarafından kullanılan renk sayısını belirtir. Bu değer sıfırdan farklıysa ve BitCount değeri 16 veya daha büyükse, bu değer rengin boyutunu belirtir. table sistem paletinin performansını optimize etmek için kullanılır. Not Bu değer sıfır değilse ve BitCount değerine dayalı olarak renk tablosunun olası maksimum boyutundan büyükse, maksimum renk tablosu boyutunun varsayılması GEREKİR. |
| [Compression](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/compression) { get; set; } | DIB'nin sıkıştırma modunu tanımlayan 32 bitlik işaretsiz bir tamsayı alır veya ayarlar. Bu değer, Sıkıştırma Numaralandırmasında OLMALIDIR (bölüm 2.1.1.7). DIB, Yükseklik değeriyle belirtildiği gibi yukarıdan aşağıya bir bit eşlem ise, bu değer sıkıştırılmış bir biçim belirtmemelidir ZORUNLU. |
| [HeaderSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/headersize) { get; set; } | this nesnesinin boyutunu bayt cinsinden tanımlayan 32 bitlik işaretsiz bir tamsayı alır veya ayarlar. |
| [Height](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/height) { get; set; } | DIB'nin yüksekliğini piksel cinsinden tanımlayan 32 bit işaretli tamsayıyı alır veya ayarlar. Bu değer sıfır OLMAMALIDIR. Bu değer pozitifse, DIB aşağıdan yukarıya bir bit eşlemdir ve kökeni sol alt köşedir. Bu değer negatifse, DIB yukarıdan aşağıya bir bit eşlemdir ve kökeni sol üst köşedir. Yukarıdan aşağıya bitmaps sıkıştırmayı desteklemez. Sıkıştırma değeri JPEG veya PNG biçimini belirtiyorsa, bu alan sıkıştırılmış görüntü dosyasının yüksekliğini belirtmelidir ÖNEMLİDİR. |
| [ImageSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/imagesize) { get; set; } | Resmin boyutunu bayt cinsinden tanımlayan 32 bitlik işaretsiz bir tamsayı alır veya ayarlar. Sıkıştırma değeri BI_RGB ise, bu değer sıfır OLMALIDIR ve yoksayılmalıdır. Sıkıştırma değeri BI_JPEG veya BI_PNG ise, bu değer, sırasıyla JPEG veya PNG görüntü arabelleğinin, boyutunu belirtmelidir. |
| [Planes](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/planes) { get; set; } | of sayısını tanımlayan 16 bitlik işaretsiz bir tamsayı alır veya ayarlarplanes hedef cihaz için. Bu değer MUTLAKA 0x0001. olmalıdır |
| [Width](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/width) { get; set; } | DIB'nin genişliğini piksel cinsinden tanımlayan 32 bitlik işaretli bir tamsayı alır veya ayarlar. Bu değer pozitif OLMALIDIR. Sıkıştırma değeri JPEG veya PNG biçimini belirtiyorsa, bu alan sıkıştırılmış görüntü dosyasının genişliğini belirtmelidir GEREKİR. |
| [XPelsPerMeter](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/xpelspermeter) { get; set; } | DIB için target aygıtının metre başına piksel cinsinden yatay çözünürlüğünü tanımlayan 32 bit işaretli bir tamsayı alır veya ayarlar |
| [YPelsPerMeter](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/ypelspermeter) { get; set; } | DIB için target aygıtının dikey çözünürlüğünü metre başına piksel cinsinden tanımlayan 32 bit işaretli bir tamsayı alır veya ayarlar |

## Alanlar

| İsim | Tanım |
| --- | --- |
| const [StructureSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/structuresize) | yapı size |

### Ayrıca bakınız

* class [WmfBitmapBaseHeader](../wmfbitmapbaseheader)
* ad alanı [Aspose.Imaging.FileFormats.Wmf.Objects](../../aspose.imaging.fileformats.wmf.objects)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
