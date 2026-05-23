---
title: "aspose.imaging.fileformats.bmp"
type: docs
weight: 140
url: /tr/python-net/aspose.imaging.fileformats.bmp/
---


Modül, Bmp dosya formatı işleme işlemini yönetir.

## **Classes**
| **Sınıf** | **Açıklama** |
| :- | :- |
| [BitmapCoreHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcoreheader/) | DIB'nin boyutları ve renk formatı.<br/>            Başlık adı BITMAPCOREHEADER, diğer adıyla OS21XBITMAPHEADER. |
| [BitmapInfoHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) | BITMAPINFOHEADER'ı belirtir. <br/>                İşletim Sistemi Desteği: Windows NT, 3.1x veya sonrası.<br/>                Özellikler: 16 bpp ve 32 bpp formatları ekler. RLE sıkıştırması ekler. |
| [BitmapV4Header](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapv4header/) | BitmapV4Header yapısı bitmap bilgi başlık dosyasıdır. BITMAPINFOHEADER yapısının genişletilmiş bir sürümüdür.<br/>            <br/>BitmapV4Header yapısı, bir JPEG veya PNG görüntüsünün StretchDIBits'e kaynak görüntü olarak aktarılmasına izin verecek şekilde genişletilmiştir.<br/> |
| [BitmapV5Header](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapv5header/) | BitmapV5Header yapısı bitmap bilgi başlık dosyasıdır. BITMAPINFOHEADER yapısının genişletilmiş bir sürümüdür.<br/>            <br/>bV5Height negatif ise, bu bir üstten alta DIB'i gösterir ve bV5Compression, BI_RGB veya BI_BITFIELDS olmalıdır. Üstten alta DIB'ler sıkıştırılamaz.<br/>            Bağımsız Renk Yönetimi arayüzü (ICM) 2.0, Uluslararası Renk Konsorsiyumu (ICC) renk profillerinin DIB'lere (DIB'ler) bağlanmasına veya gömülmesine izin verir. <br/>            Daha fazla bilgi için Yapıları Kullanma bölümüne bakın. Bir DIB belleğe yüklendiğinde, profil verileri (varsa) renk tablosunun ardından gelmelidir, <br/>            ve bV5ProfileData, profil verilerinin BITMAPV5HEADER yapısının başlangıcından itibaren olan offsetini sağlamalıdır. <br/>            bV5ProfileData içinde saklanan değer, BITMAPV5HEADER argümanı verildiğinde sizeof operatörü tarafından döndürülen değerden farklı olacaktır, <br/>            çünkü bV5ProfileData, BITMAPV5HEADER yapısının başlangıcından profil verisinin başlangıcına kadar olan bayt offsetidir. <br/>            (Bitmap bitleri bellekte renk tablosunun ardından gelmez). Uygulamalar, DIB belleğe yüklendikten sonra bV5ProfileData üyesini değiştirmelidir.<br/>            Paketlenmiş DIB'lerde, profil verileri dosya formatına benzer şekilde bitmap bitlerinin ardından gelmelidir. <br/>            bV5ProfileData üyesi, profil verilerinin BITMAPV5HEADER başlangıcından offsetini hâlâ vermelidir.<br/>            Uygulamalar, profil verilerine yalnızca bV5Size, BITMAPV5HEADER boyutuna eşit olduğunda ve bV5CSType PROFILE_EMBEDDED veya PROFILE_LINKED olduğunda erişmelidir.<br/> |
| [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) | Bitmap (BMP) ve Device Independent Bitmap (DIB) dosyalarını zahmetsizce işleyebilir, raster görüntülerin verimli manipülasyonu ve işlenmesini kolaylaştırabilirsiniz.<br/>            Görüntüler üzerinde çeşitli işlemler gerçekleştirerek, bu API iş akışını basitleştirir, geliştiricilere BMP ve DIB formatlarıyla çalışmak için güvenilir bir araç seti sunar.<br/> |
| [Os22XBitmapHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/os22xbitmapheader/) | OS/2 2.x OS22XBITMAPHEADER, diğer adıyla BITMAPCOREHEADER2. |
## **Enumerations**
| **Sıralama** | **Açıklama** |
| :- | :- |
| [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | Farklı bitmap sıkıştırma yöntemlerini belirtir. |
