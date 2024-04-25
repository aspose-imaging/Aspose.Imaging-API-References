---
title: BitmapV5Header
second_title: Aspose.Imaging for .NET API Referansı
description: BitmapV5Header yapısı bitmap bilgisi başlık dosyasıdır. BITMAPINFOHEADER yapısının genişletilmiş bir versiyonudur. bV5Height negatifse ve yukarıdan aşağıya bir DIByi gösterirse bV5Compression ya BI_RGB ya da BI_BITFIELDS olmalıdır. Yukarıdan aşağıya DIBler sıkıştırılamaz. Bağımsız Renk Yönetimi arabirimi ICM 2.0 Uluslararası Renk Konsorsiyumu ICC renk profillerinin DIBlere DIBler bağlanmasına veya gömülmesine olanak tanır. Daha fazla bilgi için Yapıları Kullanma konusuna bakın. Bir DIB belleğe yüklendiğinde profil verileri varsa renk tablosunu izlemeli ve bV5ProfileData BITMAPV5HEADER yapısının başlangıcından itibaren profil verilerinin ofsetini sağlamalıdır. bV5ProfileDatada depolanan değer BITMAPV5HEADER bağımsız değişkeni verilen sizeof operatörü tarafından döndürülen değerden farklı olacaktır çünkü bV5ProfileData BITMAPV5HEADER yapısının başlangıcından profil verilerinin başlangıcına kadar bayt cinsinden ofsettir. Bitmap bitleri bellekteki renk tablosunu takip etmez. Uygulamalar DIByi belleğe yükledikten sonra bV5ProfileData üyesini değiştirmelidir. Paketlenmiş DIBler için profil verileri dosya formatına benzer bitmap bitlerini izlemelidir. bV5ProfileData üyesi yine de BITMAPV5HEADERin başlangıcından itibaren profil verilerinin ofsetini vermelidir. Uygulamalar profil verilerine yalnızca bV5Size BITMAPV5HEADERın boyutuna ve bV5CSType PROFILE_EMBEDDED veya PROFILE_LINKEDe eşit olduğunda erişmelidir.
type: docs
weight: 1370
url: /tr/aspose.imaging.fileformats.bmp/bitmapv5header/
---
## BitmapV5Header class

BitmapV5Header yapısı, bitmap bilgisi başlık dosyasıdır. BITMAPINFOHEADER yapısının genişletilmiş bir versiyonudur. bV5Height negatifse ve yukarıdan aşağıya bir DIB'yi gösterirse, bV5Compression ya BI_RGB ya da BI_BITFIELDS olmalıdır. Yukarıdan aşağıya DIB'ler sıkıştırılamaz. Bağımsız Renk Yönetimi arabirimi (ICM) 2.0, Uluslararası Renk Konsorsiyumu (ICC) renk profillerinin DIB'lere (DIB'ler) bağlanmasına veya gömülmesine olanak tanır. Daha fazla bilgi için Yapıları Kullanma konusuna bakın. Bir DIB belleğe yüklendiğinde, profil verileri (varsa) renk tablosunu izlemeli, ve bV5ProfileData, BITMAPV5HEADER yapısının başlangıcından itibaren profil verilerinin ofsetini sağlamalıdır. bV5ProfileData'da depolanan değer, BITMAPV5HEADER bağımsız değişkeni verilen sizeof operatörü tarafından döndürülen değerden farklı olacaktır, çünkü bV5ProfileData, BITMAPV5HEADER yapısının başlangıcından profil verilerinin başlangıcına kadar bayt cinsinden ofsettir. (Bitmap bitleri bellekteki renk tablosunu takip etmez). Uygulamalar, DIB'yi belleğe yükledikten sonra bV5ProfileData üyesini değiştirmelidir. Paketlenmiş DIB'ler için profil verileri, dosya formatına benzer bitmap bitlerini izlemelidir. bV5ProfileData üyesi yine de BITMAPV5HEADER'in başlangıcından itibaren profil verilerinin ofsetini vermelidir. Uygulamalar profil verilerine yalnızca bV5Size, BITMAPV5HEADER'ın boyutuna ve bV5CSType, PROFILE_EMBEDDED veya PROFILE_LINKED'e eşit olduğunda erişmelidir.

```csharp
public class BitmapV5Header : BitmapV4Header
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AlphaMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/alphamask) { get; set; } | Her pikselin alfa bileşenini belirten renk maskesini alır veya ayarlar. |
| [BitmapColorsImportant](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcolorsimportant) { get; set; } | Önemli palet renklerinin sayısını alır veya ayarlar. |
| [BitmapColorsUsed](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcolorsused) { get; set; } | Kullanılan palet renklerinin sayısını alır veya ayarlar. |
| [BitmapCompression](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcompression) { get; set; } | Bitmap sıkıştırmasını alır veya ayarlar. |
| [BitmapHeight](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapheight) { get; set; } | Bitmap yüksekliğini alır veya ayarlar. |
| [BitmapImageSize](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapimagesize) { get; set; } | Alır veya ayarlar, bitmap ham veri boyutunu bayt cinsinden belirtir. |
| [BitmapPlanes](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapplanes) { get; set; } | Uçak sayısını alır veya ayarlar. |
| [BitmapWidth](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapwidth) { get; set; } | Bitmap genişliğini alır veya ayarlar. |
| [BitmapXPelsPerMeter](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapxpelspermeter) { get; set; } | Yatay piksel çözünürlüğünü alır veya ayarlar. |
| [BitmapYPelsPerMeter](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapypelspermeter) { get; set; } | Dikey piksel çözünürlüğünü alır veya ayarlar. |
| [BitsPerPixel](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitsperpixel) { get; set; } | Piksel sayısı başına bit alır veya ayarlar. |
| [BlueMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/bluemask) { get; set; } | Yalnızca bV4Compression BI_BITFIELDS olarak ayarlandığında geçerli olan, her pikselin mavi bileşenini belirten renk maskesini alır veya ayarlar. |
| [CSType](../../aspose.imaging.fileformats.bmp/bitmapv4header/cstype) { get; set; } | DIB'nin renk uzayını alır veya ayarlar. |
| [Endpoints](../../aspose.imaging.fileformats.bmp/bitmapv4header/endpoints) { get; set; } | CoordinatesTriple sınıfını alır veya ayarlar. |
| [ExtraBitMasks](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/extrabitmasks) { get; set; } | Fazladan bit maskelerini alır veya ayarlar. Yalnızca DIB başlığının BITMAPINFOHEADER olması ve[`BitmapCompression`](../bitmapinfoheader/bitmapcompression) ikisinden birine ayarlandıBitfields (RGB) veyaAlphaBitfields (RGBA). |
| [GammaBlue](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammablue) { get; set; } | Gama mavisini alır veya ayarlar. |
| [GammaGreen](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammagreen) { get; set; } | Gama yeşilini alır veya ayarlar. |
| [GammaRed](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammared) { get; set; } | Gama kırmızısını alır veya ayarlar. |
| [GreenMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/greenmask) { get; set; } | Yalnızca bV4Compression BI_BITFIELDS olarak ayarlandığında geçerli olan, her pikselin yeşil bileşenini belirten renk maskesini alır veya ayarlar. |
| [HeaderSize](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/headersize) { get; set; } | Bu yapının boyutunu bayt cinsinden alır veya ayarlar. |
| [Intent](../../aspose.imaging.fileformats.bmp/bitmapv5header/intent) { get; set; } | Bitmap için oluşturma amacını alır veya ayarlar. |
| [ProfileData](../../aspose.imaging.fileformats.bmp/bitmapv5header/profiledata) { get; set; } | Profil verilerini alır veya ayarlar. |
| [ProfileSize](../../aspose.imaging.fileformats.bmp/bitmapv5header/profilesize) { get; set; } | Profilin boyutunu alır veya ayarlar. |
| [RedMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/redmask) { get; set; } | Yalnızca bV4Compression BI_BITFIELDS olarak ayarlandığında geçerli olan, her pikselin kırmızı bileşenini belirten renk maskesini alır veya ayarlar. |
| [Reserved](../../aspose.imaging.fileformats.bmp/bitmapv5header/reserved) { get; set; } | Ayrılmış üyeyi alır veya ayarlar. |

### Ayrıca bakınız

* class [BitmapV4Header](../bitmapv4header)
* ad alanı [Aspose.Imaging.FileFormats.Bmp](../../aspose.imaging.fileformats.bmp)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
