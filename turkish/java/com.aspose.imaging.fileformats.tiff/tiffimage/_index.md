---
title: "TiffImage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Etiketli Görüntü Dosyası Formatı (TIFF) raster görüntülerini API'mizle işleyin, çeşitli çözünürlükler için kapsamlı destek ve EXIF veri manipülasyonu ve alfa kanalları gibi gelişmiş düzenleme yetenekleri sunar."
type: docs
weight: 13
url: /tr/java/com.aspose.imaging.fileformats.tiff/tiffimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext), [com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public class TiffImage extends RasterCachedMultipageImage implements IMultipageImageExt, IMetadataContainer
```

Etiketli Görüntü Dosyası Formatı (TIFF) raster görüntülerini API'mizle işleyin, çeşitli çözünürlükler için kapsamlı destek ve EXIF veri manipülasyonu ve alfa kanalları gibi gelişmiş düzenleme yetenekleri sunar. Tarama görüntülerinin açılarını normalleştirin, yeniden boyutlandırın, gri tonlamaya dönüştürün ve filtreleri, gama düzeltmelerini ve görüntü parametresi ayarlamalarını kolaylıkla uygulayın. Çok çerçeveli TIFF dosyalarını sorunsuz bir şekilde yönetin, grafik yolları oluşturun, şekiller ekleyin ve görüntüleri farklı formatlarda zahmetsizce kaydedin.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TiffImage(TiffFrame frame)](#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame-) | [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage) sınıfının yeni bir nesnesini başlatın, çerçeve parametresini belirterek. |
| [TiffImage(TiffFrame[] frames)](#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame---) | [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage) sınıfının yeni bir örneğini oluşturun, parametre olarak bir çerçeve listesi sağlayarak. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Görüntüyle ilişkili dosya formatı değerini alın. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Bileşenlerin ön çarpım gerektirip gerektirmediğini belirtin, görsel öğelerin verimli işlenmesini sağlayarak. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Bileşenlerin ön çarpım gerektirip gerektirmediğini belirtin, görsel öğelerin verimli işlenmesini sağlayarak. |
| [getByteOrder()](#getByteOrder--) | TIFF dosyaları için bayt sırasını sorunsuz bir şekilde değiştirin, veri yorumlaması üzerinde hassas kontrol sağlayarak. |
| [setByteOrder(int value)](#setByteOrder-int-) | TIFF dosyaları için bayt sırasını sorunsuz bir şekilde değiştirin, veri yorumlaması üzerinde hassas kontrol sağlayarak. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Belirtilen [Image](../../com.aspose.imaging/image) nesnesinin inç başına piksel cinsinden yatay çözünürlüğünü alın, hassas ayarlama ve render yeteneklerini kolaylaştırarak. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Belirtilen [Image](../../com.aspose.imaging/image) nesnesinin inç başına piksel cinsinden yatay çözünürlüğünü değiştirir, hassas ayarlama ve render yeteneklerini kolaylaştırarak. |
| [getVerticalResolution()](#getVerticalResolution--) | Belirlenen [Image](../../com.aspose.imaging/image) nesnesinin inç başına piksel cinsinden dikey çözünürlüğüne erişin, hassas ayarlamalar ve render iyileştirmeleri sağlayarak. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Belirlenen [Image](../../com.aspose.imaging/image) nesnesinin inç başına piksel cinsinden dikey çözünürlüğüne erişin, hassas ayarlamalar ve render iyileştirmeleri sağlayarak. |
| [getActiveFrame()](#getActiveFrame--) | Aktif çerçeveyi sorunsuz bir şekilde yönetin, belirlenen bağlam içinde dinamik gezinme ve manipülasyonu kolaylaştırarak. |
| [setActiveFrame(TiffFrame value)](#setActiveFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Aktif çerçeveyi sorunsuz bir şekilde yönetin, belirlenen bağlam içinde dinamik gezinme ve manipülasyonu kolaylaştırarak. |
| [getFrames()](#getFrames--) | TIFF görüntüsü içindeki bireysel çerçevelere kapsamlı erişim ve manipülasyon sağlayan bir [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) örnekleri dizisini alın. |
| [getPageCount()](#getPageCount--) | Belirtilen belgede bulunan sayfaların toplam sayısını alın, çok sayfalı içeriğin verimli gezinmesi ve yönetimini kolaylaştırarak. |
| [getPages()](#getPages--) | Belgenin sayfalarına sorunsuz bir şekilde erişin, içerik yapısı içinde dinamik gezinme ve manipülasyonu sağlayarak. |
| [hasAlpha()](#hasAlpha--) | Görüntünün bir alfa kanalı olup olmadığını belirleyin, render ve birleştirme işlemleri için kritik bilgi sağlayarak. |
| [removeMetadata()](#removeMetadata--) | Bu `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) değerini `null` olarak ayarlayarak bu görüntü örneği meta verilerini kaldırır. |
| [getOriginalOptions()](#getOriginalOptions--) | Orijinal dosya ayarlarından türetilen seçenekleri alın, bit derinliği ve orijinal görüntünün diğer temel özellikleri gibi ana parametrelerin sorunsuz korunmasını kolaylaştırarak. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Mevcut görüntüye yeni bir sayfa ekleyin, içeriğini ve çok yönlülüğünü genişleterek. |
| [alignResolutions()](#alignResolutions--) | Yatay ve dikey çözünürlükleri senkronize etmek için AlignResolutions yardımcı yöntemini uygulayın, görüntü boyutlarında tutarlılık sağlayarak. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Belirtilen [RasterImage](../../com.aspose.imaging/rasterimage) için çözünürlüğü belirler, görüntü render'ı ve görüntüleme özellikleri üzerinde hassas kontrol sağlar. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.imaging.Color-) | Tarama metin belgeleri için özel olarak tasarlanmış NormalizeAngle yöntemini kullanarak eğik taramaları düzelterek doğru hizalama sağlayın. |
| [addFrame(TiffFrame frame)](#addFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Belirtilen çerçeveyi sorunsuz bir şekilde görüntüye ekleyerek içeriğini ve çok yönlülüğünü genişletin. |
| [add(TiffImage image)](#add-com.aspose.imaging.fileformats.tiff.TiffImage-) | Belirtilen görüntüden çerçeveleri sorunsuz bir şekilde mevcut çerçeveye ekleyerek içeriklerini birleştirin ve kompozisyon esnekliğini artırın. |
| [addFrames(TiffFrame[] frames)](#addFrames-com.aspose.imaging.fileformats.tiff.TiffFrame---) | Çerçeve dizisini sorunsuz bir şekilde görüntüye bütünleştirerek içeriğini ve çok yönlülüğünü zenginleştirin. |
| [insertFrame(int index, TiffFrame frame)](#insertFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Yeni çerçeveyi çerçeve dizisindeki belirtilen indekse ekleyerek çerçeve düzeni üzerinde hassas kontrol sağlayın. |
| [replaceFrame(int index, TiffFrame newFrame)](#replaceFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Belirtilen konumdaki çerçeveyi sorunsuz bir şekilde başka bir çerçeveyle değiştirerek görüntü dizisinde dinamik çerçeve yönetimini kolaylaştırın. |
| [removeFrame(int index)](#removeFrame-int-) | İndeksiyle tanımlanan çerçeveyi görüntü dizisinden zahmetsizce kaldırarak uygulamanızda çerçeve yönetimini basitleştirin. |
| [removeFrame(TiffFrame frame)](#removeFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Belirtilen çerçeveyi görüntü dizisinden verimli bir şekilde kaldırarak uygulamanızda çerçeve yönetimini kolaylaştırın. |
| [resizeProportional(int newWidth, int newHeight, int resizeType)](#resizeProportional-int-int-int-) | Görüntüyü orantılı yeniden boyutlandırma işlemiyle, boyutlarını ayarlarken en‑boy oranını koruyarak gerçekleştirin. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Görüntünün genişliğini en‑boy oranını koruyarak ayarlayın, optimal görsel sunum için orantılı yeniden boyutlandırma sağlayın. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Görüntünün yüksekliğini orantılı olarak ayarlayarak, tutarlı görsel bütünlük için en‑boy oranını koruyun. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Aktif çerçeve üzerinde yalnızca döndürme, çevirme veya her ikisinin bir kombinasyonunu gerçekleştirin. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Mevcut görüntüde renk bandı artefaktlarını azaltmak ve görsel kalitesini artırmak için dithering uygulayın. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Belirtilen dikdörtgen bölgeyi kullanarak görüntüyü kırpın, istenen içeriği hassas bir şekilde seçmenizi sağlar. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Görüntüyü, sol, sağ, üst ve alt yönlerde kaydırmalar belirterek kırpma işlemi yapın. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Önceden tanımlı bir eşik kullanarak görüntüye ikileştirme uygulayın, böylece belirgin ön plan ve arka plan bölgeleriyle ikili bir görüntü elde edin. |
| [binarizeOtsu()](#binarizeOtsu--) | Görüntüde ikileştirme yapmak için Otsu eşikleme yöntemini kullanın, görüntünün histogramına göre optimal eşik değerini otomatik olarak belirleyin. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Görüntüde Bradley'ın adaptif eşikleme algoritması ve integral görüntü eşikleme kullanarak ikileştirme uygulayın. |
| [grayscale()](#grayscale--) | Görüntüyü gri tonlamalı temsiline dönüştürün, her pikselin yoğunluğu temsil ettiği tek kanallı bir görüntü elde edin. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Görüntüye gama düzeltmesi uygulayarak piksel yoğunluklarını ayarlayın ve istenen renk dengesini elde edin. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Kırmızı, yeşil ve mavi kanallar için ayrı katsayılar kullanarak görüntüde gama düzeltmesi yapın, renk dengesi ve kontrastı ince ayarlarla düzenlemenizi sağlar. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Görüntü için `brightness` ayarını uygulayın, genel parlaklık seviyelerinin değiştirilmesine izin verir. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | [Image](../../com.aspose.imaging/image) örneğinin kontrastını artırarak ışık ve karanlık alanlar arasındaki farkları büyütün. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Belirtilen dikdörtgen içindeki içeriği filtreleyin, seçilen bölgeyi geliştirmek veya değiştirmek için belirlenmiş bir görüntü işleme filtresi uygulayın. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Görüntünün boyutunu belirtilen ayarlara göre ayarlayın, boyutlar, en‑boy oranı ve ölçekleme davranışı üzerinde hassas kontrol sağlar. |

## Example: Create Graphics Path from Path Resources in TIFF image.

``` java
try (TiffImage image = (TiffImage)Image.load("Bottle.tif"))
{
    // TIFF görüntüsünden PathResources kullanarak GraphicsPath oluşturun
    GraphicsPath graphicsPath = PathResourceConverter.toGraphicsPath(
            image.getActiveFrame().getPathResources().toArray(new PathResource[0]), 
            image.getActiveFrame().getSize());
    Graphics graphics = new Graphics(image);

    // Kırmızı bir çizgi çizin ve görüntüyü kaydedin
    graphics.drawPath(new Pen(Color.getRed(), 10), graphicsPath);
    image.save("BottleWithRedBorder.tif");
}
```


## Example: Create Path Resources using Graphics Path.

``` java
static void main()
{
    try (TiffImage image = (TiffImage)Image.load("Bottle.tif"))
    {
        // GraphicsPath için dikdörtgen Figure oluşturun
        Figure figure = new Figure();
        figure.addShape(createBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // Figure'ımızı kullanarak GraphicsPath oluşturun
        GraphicsPath graphicsPath = new GraphicsPath();
        graphicsPath.addFigure(figure);

        // GraphicsPath kullanarak PathResources ayarlayın
        PathResource[] pathResource = PathResourceConverter.fromGraphicsPath(graphicsPath, image.getSize());
        image.getActiveFrame().setPathResources(Arrays.asList(pathResource));

        // Görüntüyü kaydedin
        image.save("BottleWithRectanglePath.tif");
    }
}

private static BezierShape createBezierShape(float ... coordinates)
{
    PointF[] bezierPoints = coordinatesToBezierPoints(coordinates);
    return new BezierShape(bezierPoints, true);
}

private static PointF[] coordinatesToBezierPoints(float[] coordinates)
{
    PointF[] bezierPoints = new PointF[3 * coordinates.length / 2];
    int i = 0;
    for (int coordinateIndex = 0; coordinateIndex < coordinates.length - 1; coordinateIndex += 2)
        for (int index = 0; index < 3; index++)
        {
            bezierPoints[i++] = new PointF(coordinates[coordinateIndex], coordinates[coordinateIndex + 1]);
        }
                
    return bezierPoints;
}
```

### TiffImage(TiffFrame frame) {#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public TiffImage(TiffFrame frame)
```


Yeni bir [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage) sınıfı nesnesi başlatın, frame parametresini belirterek. Bu yapıcı, bir TiffImage örneği oluşturmayı kolaylaştırır ve geliştiricilerin yüklenecek veya işlenecek çerçeveyi belirtmelerine olanak tanır, uygulamalarında TIFF görüntü işleme görevlerini sadeleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Resmi başlatmak için kullanılacak tiff çerçevesi. |

### TiffImage(TiffFrame[] frames) {#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame---}
```
public TiffImage(TiffFrame[] frames)
```


Yeni bir [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage) sınıfı örneği oluşturun, çerçevelerin bir listesini parametre olarak sağlayarak. Bu yapıcı, bir TiffImage nesnesinin birden fazla çerçeveyle başlatılmasını sağlar ve yazılım uygulamalarında TIFF görüntü dizilerinin verimli bir şekilde işlenmesini ve yönetilmesini kolaylaştırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| frames | [TiffFrame\[\]](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Çerçeveler. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Görüntüyle ilişkili dosya formatı değerini alın. Bu özellik, görüntü meta verisi alımının kritik bir yönü olarak hizmet eder ve yazılım uygulamalarının görüntü verisinin formatını verimli bir şekilde tanımlamasına ve yorumlamasına olanak tanır.

**Returns:**
long - dosya formatı değeri
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Bileşenlerin ön çarpım gerektirip gerektirmediğini belirtin, görsel öğelerin verimli bir şekilde işlenmesini sağlayın. Bu özelliği değiştirerek renderleme süreçlerini iyileştirin, grafik iş akışlarını optimize edilmiş performans için sadeleştirin.

**Returns:**
boolean - bileşenlerin ön çarpılması gerekiyorsa `true`; aksi takdirde `false`.
### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Bileşenlerin ön çarpım gerektirip gerektirmediğini belirtin, görsel öğelerin verimli bir şekilde işlenmesini sağlayın. Bu özelliği değiştirerek renderleme süreçlerini iyileştirin, grafik iş akışlarını optimize edilmiş performans için sadeleştirin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | `true` bileşenlerin ön çarpılması gerekiyorsa; aksi takdirde `false`. |


**Example: The following example creates a new TIFF image, saves the specified semi-transparent pixels, then loads those pixels and gets final colors in the premultiplied form.**

``` java
int imageWidth = 3;
int imageHeight = 2;

com.aspose.imaging.Color[] colors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.fromArgb(127, 255, 0, 0),
                com.aspose.imaging.Color.fromArgb(127, 0, 255, 0),
                com.aspose.imaging.Color.fromArgb(127, 0, 0, 255),
                com.aspose.imaging.Color.fromArgb(127, 255, 255, 0),
                com.aspose.imaging.Color.fromArgb(127, 255, 0, 255),
                com.aspose.imaging.Color.fromArgb(127, 0, 255, 255),
        };

com.aspose.imaging.imageoptions.TiffOptions createOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.TiffDeflateRgba);
createOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0]), true));

com.aspose.imaging.fileformats.tiff.TiffImage image =
        (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createOptions, imageWidth, imageHeight);
try {
    // Tüm görüntü için pikselleri kaydet.
    image.savePixels(image.getBounds(), colors);

    // Pikseller, orijinal görüntüde önceden çarpılmamış biçimde depolanır.
    // Önceden çarpılmış renk bileşenlerini elde etmek için ilgili seçeneği açıkça belirtmek gerekir.
    // Önceden çarpılmış renk bileşenleri aşağıdaki formüllerle hesaplanır:
    // kırmızı = orijinal_kırmızı * alfa / 255;
    // yeşil = orijinal_yeşil * alfa / 255;
    // mavi = orijinal_mavi * alfa / 255;
    image.setPremultiplyComponents(true);
    com.aspose.imaging.Color[] premultipliedColors = image.loadPixels(image.getBounds());

    for (int i = 0; i < colors.length; i++) {
        System.out.println("Original color: " + colors[i].toString());
        System.out.println("Premultiplied color: " + premultipliedColors[i].toString());
    }
} finally {
    image.dispose();
}

//Çıktı şu şekilde görünecek:
//Orijinal renk: Color [A=127, R=255, G=0, B=0]
//Ön çarpılmış renk: Color [A=127, R=127, G=0, B=0]
//Orijinal renk: Color [A=127, R=0, G=255, B=0]
//Ön çarpılmış renk: Color [A=127, R=0, G=127, B=0]
//Orijinal renk: Color [A=127, R=0, G=0, B=255]
//Ön çarpılmış renk: Color [A=127, R=0, G=0, B=127]
//Orijinal renk: Color [A=127, R=255, G=255, B=0]
//Ön çarpılmış renk: Color [A=127, R=127, G=127, B=0]
//Orijinal renk: Color [A=127, R=255, G=0, B=255]
//Önceden çarpılmış renk: Color [A=127, R=127, G=0, B=127]
//Orijinal renk: Color [A=127, R=0, G=255, B=255]
//Önceden çarpılmış renk: Color [A=127, R=0, G=127, B=127]
```

### getByteOrder() {#getByteOrder--}
```
public final int getByteOrder()
```


TIFF dosyaları için bayt sırasını sorunsuz bir şekilde değiştirin, veri yorumlaması üzerinde kesin kontrol sağlayın. Uygulamalarınıza çeşitli dosya özelliklerine uyum sağlama esnekliği kazandırarak uyumluluğu ve veri işleme verimliliğini artırın.

**Returns:**
int - TIFF bayt sırası.
### setByteOrder(int value) {#setByteOrder-int-}
```
public final void setByteOrder(int value)
```


TIFF dosyaları için bayt sırasını sorunsuz bir şekilde değiştirin, veri yorumlaması üzerinde kesin kontrol sağlayın. Uygulamalarınıza çeşitli dosya özelliklerine uyum sağlama esnekliği kazandırarak uyumluluğu ve veri işleme verimliliğini artırın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | TIFF bayt sırası. |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Belirtilen [Image](../../com.aspose.imaging/image) nesnesinin inç başına piksel cinsinden yatay çözünürlüğünü alın, kesin ayarlama ve render yeteneklerini kolaylaştırın. Temel görüntü meta verilerine zahmetsizce erişin, geliştirilmiş kullanıcı deneyimleri için sorunsuz görüntü işleme iş akışlarını güçlendirin.

**Returns:**
double - Yatay çözünürlük.

Not: varsayılan olarak bu değer her zaman 96'dır çünkü farklı platformlar ekran çözünürlüğünü döndüremez. Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanmayı düşünebilirsiniz.

**Example: The following example shows how to set horizontal/vertical resolution of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // TiffImage'ın yatay ve dikey çözünürlüğünü alın.
    double horizontalResolution = tiffImage.getHorizontalResolution();
    double verticalResolution = tiffImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanın.
        System.out.println("Set resolution values to 96 dpi");
        tiffImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + tiffImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + tiffImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Çıktı şöyle görünebilir:
// Yatay çözünürlük, inç başına piksel olarak: 96.0
// Dikey çözünürlük, inç başına piksel olarak: 96.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Belirtilen [Image](../../com.aspose.imaging/image) nesnesinin inç başına piksel cinsinden yatay çözünürlüğünü değiştirir, kesin ayarlama ve render yeteneklerini kolaylaştırır. Temel görüntü meta verilerine zahmetsizce erişir, geliştirilmiş kullanıcı deneyimleri için sorunsuz görüntü işleme iş akışlarını güçlendirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Yatay çözünürlük. |

Not: varsayılan olarak bu değer her zaman 96'dır çünkü farklı platformlar ekran çözünürlüğünü döndüremez. Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanmayı düşünebilirsiniz. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Belirtilen [Image](../../com.aspose.imaging/image) nesnesinin inç başına piksel cinsinden dikey çözünürlüğüne erişin, kesin ayarlamalar ve render iyileştirmeleri sağlayın. Temel görüntü verilerini zahmetsizce kullanarak görüntü işleme iş akışlarını basitleştirin, uygulamalarınızda üstün kalite ve performans garantileyin.

**Returns:**
double - Dikey çözünürlük.

Not: varsayılan olarak bu değer her zaman 96'dır çünkü farklı platformlar ekran çözünürlüğünü döndüremez. Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanmayı düşünebilirsiniz.

**Example: The following example shows how to set horizontal/vertical resolution of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // TiffImage'ın yatay ve dikey çözünürlüğünü alın.
    double horizontalResolution = tiffImage.getHorizontalResolution();
    double verticalResolution = tiffImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanın.
        System.out.println("Set resolution values to 96 dpi");
        tiffImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + tiffImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + tiffImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Çıktı şöyle görünebilir:
// Yatay çözünürlük, inç başına piksel olarak: 96.0
// Dikey çözünürlük, inç başına piksel olarak: 96.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Belirtilen [Image](../../com.aspose.imaging/image) nesnesinin inç başına piksel cinsinden dikey çözünürlüğüne erişin, kesin ayarlamalar ve render iyileştirmeleri sağlayın. Temel görüntü verilerini zahmetsizce kullanarak görüntü işleme iş akışlarını basitleştirin, uygulamalarınızda üstün kalite ve performans garantileyin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Dikey çözünürlük. |

Not: varsayılan olarak bu değer her zaman 96'dır çünkü farklı platformlar ekran çözünürlüğünü döndüremez. Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanmayı düşünebilirsiniz. |

### getActiveFrame() {#getActiveFrame--}
```
public final TiffFrame getActiveFrame()
```


Aktif çerçeveyi sorunsuz bir şekilde yönetin, belirlenen bağlam içinde dinamik gezinme ve manipülasyonu kolaylaştırın. Uygulamanızın çoklu ortam içeriğiyle verimli etkileşime girmesini sağlayarak kullanıcı katılımını ve verimliliği artırın.

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - Active frame.

**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Bu, bireysel çerçevelerde metin çizmek için Font ve Brush'tir.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // 5 çerçeve oluştur.
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Bir PNG görüntüsü oluştur ve üzerine sayfa numarasını çiz.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // PNG görüntüsüne dayalı bir çerçeve oluştur.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Çerçeveyi TIFF görüntüsüne ekle.
        tiffImage.addFrame(frame);
    }

    // Görüntü tek bir varsayılan çerçeve ile oluşturulmuştu. Hadi onu kaldıralım.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Çerçeveyi başka bir TiffImage'a eklemeyecekseniz, serbest bırakmayı unutmayın.
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### setActiveFrame(TiffFrame value) {#setActiveFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void setActiveFrame(TiffFrame value)
```


Aktif çerçeveyi sorunsuz bir şekilde yönetin, belirlenen bağlam içinde dinamik gezinme ve manipülasyonu kolaylaştırın. Uygulamanızın çoklu ortam içeriğiyle verimli etkileşime girmesini sağlayarak kullanıcı katılımını ve verimliliği artırın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Aktif çerçeve. |


**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Bu, bireysel çerçevelerde metin çizmek için Font ve Brush'tir.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // 5 çerçeve oluştur.
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Bir PNG görüntüsü oluştur ve üzerine sayfa numarasını çiz.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // PNG görüntüsüne dayalı bir çerçeve oluştur.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Çerçeveyi TIFF görüntüsüne ekle.
        tiffImage.addFrame(frame);
    }

    // Görüntü tek bir varsayılan çerçeve ile oluşturulmuştu. Hadi onu kaldıralım.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Çerçeveyi başka bir TiffImage'a eklemeyecekseniz, serbest bırakmayı unutmayın.
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getFrames() {#getFrames--}
```
public final TiffFrame[] getFrames()
```


TIFF görüntüsü içindeki bireysel çerçevelere kapsamlı erişim ve manipülasyon sağlayan bir [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) örnekleri dizisini alın. Görsel içeriğin kesin kontrolü ve optimizasyonunu sağlamak için bu dizinin gücünden yararlanarak görüntü işleme iş akışlarını basitleştirin.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffFrame[] - [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) dizisi.

**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Bu, bireysel çerçevelerde metin çizmek için Font ve Brush'tir.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // 5 çerçeve oluştur.
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Bir PNG görüntüsü oluştur ve üzerine sayfa numarasını çiz.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // PNG görüntüsüne dayalı bir çerçeve oluştur.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Çerçeveyi TIFF görüntüsüne ekle.
        tiffImage.addFrame(frame);
    }

    // Görüntü tek bir varsayılan çerçeve ile oluşturulmuştu. Hadi onu kaldıralım.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Çerçeveyi başka bir TiffImage'a eklemeyecekseniz, serbest bırakmayı unutmayın.
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Belirtilen belgedeki sayfa toplam sayısını alın, çok sayfalı içeriğin verimli gezinmesi ve yönetimini kolaylaştırın. Kullanıcı deneyimini artırmak için bu işlevi ekleyin, kapsamlı belge yapılarının sorunsuz erişimini sağlayın.

**Returns:**
int - sayfa sayısı.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Belgenin sayfalarına sorunsuz bir şekilde erişin, içerik yapısı içinde dinamik gezinme ve manipülasyonu mümkün kılın. Uygulamanıza bireysel sayfalara verimli erişim sağlayarak belge işleme sürecini basitleştirin ve kullanıcı etkileşimini artırın.

**Returns:**
com.aspose.imaging.Image[] - sayfalar.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Görüntünün alfa kanalı olup olmadığını belirleyin, render ve birleştirme işlemleri için kritik bilgi sağlayın. Şeffaf öğelerin doğru temsilini ve manipülasyonunu sağlamak için görsel işleme iş akışlarını optimize etmek amacıyla bu özelliği entegre edin.

**Returns:**
boolean - alfa kanalı varsa `true`.

**Example: The following example loads a TIFF image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";

String fileName = dir + "sample.tif";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Aktif TIFF çerçevesi alfa kanalına sahipse, tüm TIFF görüntüsü alfa kanalı olduğu kabul edilir.
    System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s\r\n", fileName, tiffImage.getRawDataFormat(), tiffImage.hasAlpha());

    int i = 0;
    for (com.aspose.imaging.fileformats.tiff.TiffFrame frame : tiffImage.getFrames()) {
        System.out.printf("Frame=%s, FileFormat=%s, HasAlpha=%s\r\n", ++i, frame.getRawDataFormat(), frame.hasAlpha());
    }
} finally {
    image.dispose();
}

// Çıktı şöyle görünebilir:
// ImageFile=c:\temp\sample.tif, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=1, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=2, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
```

### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Bu `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) değerini `null` olarak ayarlayarak bu görüntü örneği meta verilerini kaldırır.

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Orijinal dosya ayarlarından türetilen seçenekleri alın, bit derinliği ve orijinal görüntünün diğer temel özellikleri gibi ana parametrelerin sorunsuz korunmasını kolaylaştırın. Bu yöntemi, görüntü işleme görevlerinde doğruluk ve tutarlılığı korumak, gereksiz değişiklikler olmadan optimum sonuçlar sağlamak için kullanın. Örneğin, 1 bit/piksel siyah-beyaz bir PNG görüntüsü yükleyip ardından [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-) yöntemiyle kaydederseniz, çıktı PNG görüntüsü 8 bit/piksel olarak üretilecektir. Bunu önlemek ve PNG görüntüsünü 1 bit/piksel olarak kaydetmek için, bu yöntemi kullanarak ilgili kaydetme seçeneklerini alın ve ikinci parametre olarak [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) yöntemine geçirin.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Incorporate a new page into the existing image seamlessly, expanding its content and versatility. Utilize this method to enhance document composition and management, empowering efficient handling of multipage images within your application.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | Eklenecek sayfa. |

### alignResolutions() {#alignResolutions--}
```
public final void alignResolutions()
```


Implement the AlignResolutions helper method to synchronize horizontal and vertical resolutions, ensuring uniformity in image dimensions. This functionality facilitates streamlined image processing workflows by harmonizing resolution parameters, optimizing visual quality and consistency across various platforms and devices.

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Establishes the resolution for the specified [RasterImage](../../com.aspose.imaging/rasterimage), enabling precise control over image rendering and display properties. Integrate this functionality to optimize visual output and ensure compatibility with diverse output devices and platforms, enhancing the overall user experience.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dpiX | double | The horizontal resolution, in dots per inch, of the [RasterImage](../../com.aspose.imaging/rasterimage). |
| dpiY | double | The vertical resolution, in dots per inch, of the [RasterImage](../../com.aspose.imaging/rasterimage). |


**Example: The following example shows how to set horizontal/vertical resolution of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // TiffImage'ın yatay ve dikey çözünürlüğünü alın.
    double horizontalResolution = tiffImage.getHorizontalResolution();
    double verticalResolution = tiffImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanın.
        System.out.println("Set resolution values to 96 dpi");
        tiffImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + tiffImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + tiffImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Çıktı şöyle görünebilir:
// Yatay çözünürlük, inç başına piksel olarak: 96.0
// Dikey çözünürlük, inç başına piksel olarak: 96.0
```

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.imaging.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Utilize the NormalizeAngle method specifically designed for scanned text documents to rectify skewed scans, ensuring accurate alignment. Seamlessly integrate this functionality into your text processing workflows to enhance document readability and quality, improving overall efficiency in text recognition and analysis tasks. This method uses [RasterImage.getSkewAngle](../../com.aspose.imaging/rasterimage\#getSkewAngle) and [RasterImage.rotate(float, boolean, Color)](../../com.aspose.imaging/rasterimage\#rotate-float--boolean--Color-) methods.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| resizeProportionally | boolean | Eğer `true` olarak ayarlanırsa, görüntü boyutunuz döndürülmüş dikdörtgen (köşe noktaları) projeksiyonlarına göre değişir; diğer durumda boyutlar dokunulmaz kalır ve yalnızca iç görüntü içeriği döndürülür. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Arka planın rengi. |

### addFrame(TiffFrame frame) {#addFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void addFrame(TiffFrame frame)
```


Incorporate the specified frame seamlessly into the image, expanding its content and versatility. Utilize this method to enhance image composition and management, empowering efficient handling of multi-frame images within your application.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | The frame to add. |


**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Bu, bireysel çerçevelerde metin çizmek için Font ve Brush'tir.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // 5 çerçeve oluştur.
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Bir PNG görüntüsü oluştur ve üzerine sayfa numarasını çiz.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // PNG görüntüsüne dayalı bir çerçeve oluştur.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Çerçeveyi TIFF görüntüsüne ekle.
        tiffImage.addFrame(frame);
    }

    // Görüntü tek bir varsayılan çerçeve ile oluşturulmuştu. Hadi onu kaldıralım.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Çerçeveyi başka bir TiffImage'a eklemeyecekseniz, serbest bırakmayı unutmayın.
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### add(TiffImage image) {#add-com.aspose.imaging.fileformats.tiff.TiffImage-}
```
public final void add(TiffImage image)
```


Add the frames from the specified image seamlessly into the current frame, consolidating their content and enhancing compositional flexibility. Integrate this method to streamline frame management and manipulation within your application, facilitating efficient handling of multi-frame images.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage) | The source image. |

### addFrames(TiffFrame[] frames) {#addFrames-com.aspose.imaging.fileformats.tiff.TiffFrame---}
```
public final void addFrames(TiffFrame[] frames)
```


Integrate the array of frames seamlessly into the image, enriching its content and versatility. Utilize this method to enhance image composition and management, enabling efficient handling of multi-frame images within your application.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| frames | [TiffFrame\[\]](../../com.aspose.imaging.fileformats.tiff/tiffframe) | The frames array to add |

### insertFrame(int index, TiffFrame frame) {#insertFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void insertFrame(int index, TiffFrame frame)
```


Insert the new frame at the specified index within the frame sequence, ensuring precise control over frame arrangement. Employ this method to manage frame sequences effectively, facilitating dynamic manipulation and organization of image content within your application.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | The index of `frame`. |
| frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | The frame for insertion. |

### replaceFrame(int index, TiffFrame newFrame) {#replaceFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final TiffFrame replaceFrame(int index, TiffFrame newFrame)
```


Substitute the frame at the designated position with another frame seamlessly, facilitating dynamic frame management within the image sequence. Integrate this method to enhance flexibility and precision in frame manipulation, ensuring optimal organization and presentation of image content within your application.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | The zero based frame position. |
|  | newFrame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | The frame to replace. |

Note: do not forget to dispose/close the frame if you will not add it to some other TiffImage. |

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - The removed frame.
### removeFrame(int index) {#removeFrame-int-}
```
public final TiffFrame removeFrame(int index)
```


Effortlessly eliminate the frame identified by its index from the image sequence, streamlining frame management within your application. Integrate this functionality to enhance efficiency and precision in frame manipulation, facilitating seamless organization and presentation of image content.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | index | int | Index of frame to be removed. |

--------------------

Note: do not forget to Dispose the frame if you will not add it to some other TiffImage. |

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - The removed frame.

**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Bu, bireysel çerçevelerde metin çizmek için Font ve Brush'tir.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // 5 çerçeve oluştur.
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Bir PNG görüntüsü oluştur ve üzerine sayfa numarasını çiz.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // PNG görüntüsüne dayalı bir çerçeve oluştur.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Çerçeveyi TIFF görüntüsüne ekle.
        tiffImage.addFrame(frame);
    }

    // Görüntü tek bir varsayılan çerçeve ile oluşturulmuştu. Hadi onu kaldıralım.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Çerçeveyi başka bir TiffImage'a eklemeyecekseniz, serbest bırakmayı unutmayın.
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### removeFrame(TiffFrame frame) {#removeFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void removeFrame(TiffFrame frame)
```


Efficiently remove the specified frame from the image sequence, facilitating streamlined frame management within your application. Integrate this functionality to enhance precision and flexibility in frame manipulation, ensuring seamless organization and presentation of image content.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | The frame to remove. |

--------------------

Note: do not forget to Dispose the frame if you will not add it to some other TiffImage. |

### resizeProportional(int newWidth, int newHeight, int resizeType) {#resizeProportional-int-int-int-}
```
public final void resizeProportional(int newWidth, int newHeight, int resizeType)
```


Conduct a proportional resize operation on the image, preserving its aspect ratio while adjusting its dimensions. Employ this method to dynamically scale images within your application, ensuring consistent visual representation of content integrity. The proportional resize will resize each frame according to the ratio of `newWidth`/width and `newHeight`/height.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| newHeight | int | Yeni yükseklik. |
| resizeType | int | Yeniden boyutlandırma türü. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Görselin enini, en‑boy oranını koruyarak ayarlayın, optimal görsel sunum için orantılı yeniden boyutlandırmayı sağlayın. Bu yöntemi uygulamanız içinde görüntüleri dinamik olarak ölçeklendirmek için kullanın, çeşitli görüntüleme bağlamlarında tutarlı ve estetik açıdan hoş bir render elde etmeyi kolaylaştırın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| resizeType | int | Yeniden boyutlandırma türü. |


**Example: This example loads a TIFF image and resizes it proportionally using various resizing methods.**
Bu örnek bir TIFF görüntüsü yükler ve çeşitli yeniden boyutlandırma yöntemleri kullanarak orantılı olarak yeniden boyutlandırır. Yalnızca genişlik belirtilir, yükseklik otomatik olarak hesaplanır.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat büyüt.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Varsayılan seçeneklerle PNG olarak kaydedin.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat küçült.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Varsayılan seçeneklerle PNG olarak kaydedin.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat büyüt.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Varsayılan seçeneklerle PNG olarak kaydedin.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat küçült.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Varsayılan seçeneklerle PNG olarak kaydedin.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Görselin yüksekliğini orantılı olarak ayarlayın, tutarlı görsel bütünlük için en‑boy oranını koruyun. Bu yöntemi uygulamanız içinde görüntüleri dinamik olarak yeniden boyutlandırmak için kullanın, içerik kalitesinden ödün vermeden çeşitli platform ve cihazlarda optimal görüntüleme sağlayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newHeight | int | Yeni yükseklik. |
| resizeType | int | Yeniden boyutlandırma türü. |


**Example: This example loads a TIFF image and resizes it proportionally using various resizing methods.**
Bu örnek bir TIFF görüntüsü yükler ve çeşitli yeniden boyutlandırma yöntemleri kullanarak orantılı olarak yeniden boyutlandırır. Yalnızca yükseklik belirtilir, genişlik otomatik olarak hesaplanır.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat büyüt.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Varsayılan seçeneklerle PNG olarak kaydedin.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat küçült.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Varsayılan seçeneklerle PNG olarak kaydedin.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat büyüt.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Varsayılan seçeneklerle PNG olarak kaydedin.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat küçült.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Varsayılan seçeneklerle PNG olarak kaydedin.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Döndürme, çevirme veya her iki işlemin bir kombinasyonunu yalnızca aktif karede gerçekleştirin. Bu yöntem, görüntü dizisindeki tek tek karelerin hassas manipülasyonunu sağlar, uygulamanız içinde görüntü düzenleme ve kompozisyon esnekliğini artırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rotateFlipType | int | Döndürme ve çevirme türü. |


**Example: This example loads a TIFF image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java
String dir = "c:\\temp\\";

// Bu bir yardımcı sınıftır.
class Utils {
    // Döndürme çevirme türünün dize temsilini alır.
    public String rotateFlipTypeToString(int rotateFilpType) {
        switch (rotateFilpType) {
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipNone:
                return "RotateNoneFlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipNone:
                return "Rotate90FlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipNone:
                return "Rotate180FlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipNone:
                return "Rotate270FlipNone";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipX:
                return "RotateNoneFlipX";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipX:
                return "Rotate90FlipX";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipX:
                return "Rotate180FlipX";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipX:
                return "Rotate270FlipX";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipY:
                return "RotateNoneFlipY";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipY:
                return "Rotate90FlipY";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipY:
                return "Rotate180FlipY";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipY:
                return "Rotate270FlipY";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipXY:
                return "RotateNoneFlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipXY:
                return "Rotate90FlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipXY:
                return "Rotate180FlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipXY:
                return "Rotate270FlipXY";
            default:
                throw new java.lang.IllegalArgumentException("rotateFlipType");
        }
    }
}

// İşte ana örnek.
Utils utils = new Utils();

int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

for (int rotateFlipType : rotateFlipTypes) {
    // Döndür, çevir ve çıktıyı dosyaya kaydet.
    com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + utils.rotateFlipTypeToString(rotateFlipType) + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Mevcut görüntüde renk tonlaması (dithering) uygulayarak görsel kalitesini artırın ve renk bantlama artefaktlarını azaltın. Bu yöntemi görüntü işleme iş akışınıza entegre edin, renk geçişlerini daha yumuşak hâle getirerek genel görüntü görünümünü ve netliğini iyileştirin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ditheringMethod | int | Dithering yöntemi. |
| bitsCount | int | Dithering için son bit sayısı. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Dithering için özel palet. |


**Example: The following example loads a TIFF image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // 16 renk içeren 4-bit renk paleti kullanarak eşik dithering uygulayın.
    // Daha fazla bit belirtildiğinde çıktı görüntüsünün kalitesi daha yüksek ve boyutu daha büyük olur.
    // Şu anda yalnızca 1-bit, 4-bit ve 8-bit paletlerin desteklendiğini unutmayın.
    tiffImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    tiffImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Sadece 2 renk (siyah ve beyaz) içeren 1-bit renk paleti kullanarak Floyd dithering uygulayın.
    // Daha fazla bit belirtildiğinde çıktı görüntüsünün kalitesi daha yüksek ve boyutu daha büyük olur.
    // Şu anda yalnızca 1-bit, 4-bit ve 8-bit paletlerin desteklendiğini unutmayın.
    tiffImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    tiffImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Belirtilen dikdörtgen bölgeyi kullanarak görüntüyü kırpın, istenen içeriği hassas bir şekilde seçmenizi sağlar. Bu yöntemi görüntü işleme iş akışınıza entegre edin, istenmeyen alanları verimli bir şekilde kaldırın ve temel detaylara odaklanın, görüntünün genel netliğini ve kompozisyonunu artırın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Dikdörtgen. |


**Example: The following example crops a TIFF image.**
Aşağıdaki örnek bir TIFF görüntüsünü kırpar. Kırpma alanı Aspose.Imaging.Rectangle aracılığıyla belirtilir.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Görüntüyü kırp. Kırpma alanı, görüntünün dikdörtgen merkezi alanıdır.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(
            tiffImage.getWidth() / 4, tiffImage.getHeight() / 4, tiffImage.getWidth() / 2, tiffImage.getHeight() / 2);
    tiffImage.crop(area);

    // Kırpılmış görüntüyü PNG olarak kaydet.
    tiffImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Görüntüyü, sol, sağ, üst ve alt yönlerde kaydırmalar belirterek kırpın. Bu yöntem, görüntünün istenen bölümünü hassas bir şekilde seçmenizi sağlar, istenmeyen alanların verimli bir şekilde kaldırılmasını ve temel içeriğe odaklanılmasını kolaylaştırır. Bu işlevi uygulamanız içinde görüntü işleme hattına entegre edin, ihtiyaç duyulduğunda netlik ve kompozisyonu artırın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| leftShift | int | Sol kaydırma. |
| rightShift | int | Sağ kaydırma. |
| topShift | int | Üst kaydırma. |
| bottomShift | int | Alt kaydırma. |


**Example: The following example crops a TIFF image.**
Aşağıdaki örnek bir TIFF görüntüsünü kırpar. Kırpma alanı Sol, Üst, Sağ, Alt kenar boşluklarıyla belirtilir.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Tekrar kırpın. Görüntü boyutunun %10'u kadar bir kenar boşluğu ayarlayın.
    int horizontalMargin = tiffImage.getWidth() / 10;
    int verticalMargin = tiffImage.getHeight() / 10;
    tiffImage.crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // Kırpılmış görüntüyü PNG olarak kaydedin.
    tiffImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Önceden tanımlı bir eşik kullanarak görüntüye ikilileştirme uygulayın, onu belirgin ön plan ve arka plan bölgeleri içeren ikili bir görüntüye dönüştürün. Bu yöntemi görüntü işleme iş akışınıza dahil edin, segmentasyon ve özellik çıkarma görevlerini kolaylaştırın, uygulamanız içinde görüntü analizinin doğruluğunu ve verimliliğini artırın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threshold | byte | Eşik değeri. Bir pikselin ilgili gri değeri eşiğin üzerindeyse, ona 255 değeri atanır, aksi takdirde 0 atanır. |


**Example: The following example binarizes a TIFF image with the predefined threshold.**
Aşağıdaki örnek, önceden tanımlı eşik ile bir TIFF görüntüsünü ikilileştirir. İkilileştirilmiş görüntüler yalnızca 2 renk içerir - siyah ve beyaz.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Görüntüyü 127 eşik değeriyle ikilileştirin.
    // Bir pikselin ilgili gri değeri 127'den büyükse, ona 255 değeri atanır, aksi takdirde 0.
    tiffImage.binarizeFixed((byte) 127);
    tiffImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Görüntüde ikilileştirme yapmak için Otsu eşikleme yöntemini kullanın, görüntünün histogramına dayanarak optimal eşik değerini otomatik olarak belirleyin. Bu yöntemi görüntü işleme iş akışınıza entegre edin, etkili segmentasyon ve özellik çıkarımı elde edin, uygulamanız içinde görüntü analiz görevlerinin doğruluğunu ve güvenilirliğini artırın.


**Example: The following example binarizes a TIFF image with Otsu thresholding.**
Aşağıdaki örnek, Otsu eşikleme ile bir TIFF görüntüsünü ikilileştirir. İkilileştirilmiş görüntüler yalnızca 2 renk içerir - siyah ve beyaz.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Görüntüyü Otsu eşikleme ile ikilileştirin.
    tiffImage.binarizeOtsu();
    tiffImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Görüntüde ikilileştirme uygulamak için Bradley'ın adaptif eşikleme algoritmasını bütünsel görüntü eşikleme ile kullanın. Bu yaklaşım, görüntünün komşuluğuna dayalı olarak yerel eşikleri dinamik olarak hesaplar, değişen aydınlatma koşullarına uyum yeteneğini artırır ve uygulamanız içinde sonraki işleme görevleri için sağlam bir segmentasyon sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brightnessDifference | double | Bu pikselin etrafında merkezlenmiş s x s piksellik bir pencerenin ortalaması ile piksel arasındaki parlaklık farkı. |
| windowSize | int | Bu pikselin etrafında merkezlenmiş s x s piksellik pencerenin boyutu |


**Example: The following example binarizes a TIFF image with Bradley's adaptive thresholding algorithm with the specified window size.**
Aşağıdaki örnek, belirtilen pencere boyutuyla Bradley'ın adaptif eşikleme algoritmasını kullanarak bir TIFF görüntüsünü ikilileştirir. İkilileştirilmiş görüntüler yalnızca 2 renk içerir - siyah ve beyaz.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Görüntüyü 5 parlaklık farkı ile ikili hale getirin. Parlaklık, bir piksel ile bu pikselin etrafındaki 10 x 10 pencere ortalaması arasındaki farktır.
    tiffImage.binarizeBradley(5, 10);
    tiffImage.save(dir + "sample.BinarizeBradley5_10x10.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


Görüntüyü gri tonlamalı temsiline dönüştürün, her pikselin yoğunluğu temsil ettiği tek kanallı bir görüntü haline getirin. Bu yöntemi görüntü işleme hattınıza entegre edin, analizi basitleştirin ve gri tonlamalı tabanlı algoritmalarla uyumluluğu artırın, uygulamanız içinde çeşitli bilgisayarlı görü ve görüntü analizi görevlerini kolaylaştırın.


**Example: The following example transforms a colored TIFF image to its grayscale representation.**
Aşağıdaki örnek, renkli bir TIFF görüntüsünü gri tonlamalı temsiline dönüştürür. Gri tonlamalı görüntüler yalnızca gri tonlardan oluşur ve sadece yoğunluk bilgisi taşır.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    tiffImage.grayscale();
    tiffImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Görüntüye gama düzeltmesi uygulayın, piksel yoğunluklarını istediğiniz renk dengesine ulaşacak şekilde ayarlayın. Bu yöntemi görüntü işleme iş akışınıza dahil edin, görsel kaliteyi artırın ve uygulamanız içinde sonraki analiz veya görüntüleme görevlerinin doğruluğunu iyileştirin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| gamma | float | Kırmızı, yeşil ve mavi kanallar için gamma katsayısı |


**Example: The following example performs gamma-correction of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Kırmızı, yeşil ve mavi kanallar için gamma katsayısını ayarlayın.
    tiffImage.adjustGamma(2.5f);
    tiffImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Görüntüde kırmızı, yeşil ve mavi kanallar için ayrı katsayılar kullanarak gama düzeltmesi yapın, renk dengesi ve kontrastı ince ayarlarla düzenleyin. Bu yöntemi görüntü işleme hattınıza entegre edin, renk render'ı üzerinde hassas kontrol sağlayın ve uygulamanız içinde görsel sadakati artırın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| gammaRed | float | Kırmızı kanal katsayısı için gama |
| gammaGreen | float | Yeşil kanal katsayısı için gama |
| gammaBlue | float | Mavi kanal katsayısı için gamma |


**Example: The following example performs gamma-correction of a TIFF image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Kırmızı, yeşil ve mavi kanallar için ayrı ayrı gamma katsayılarını ayarlayın.
    tiffImage.adjustGamma(1.5f, 2.5f, 3.5f);
    tiffImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


`brightness` ayarlamasını görüntüye uygulayın, genel parlaklık seviyelerinin değiştirilmesini sağlayın. Bu yöntemi görüntü işleme iş akışınıza dahil edin, görünürlüğü artırın ve uygulamanız içinde görüntülerin görsel kalitesini iyileştirin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brightness | int | Parlaklık değeri. |


**Example: The following example performs brightness correction of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Parlaklık değerini ayarlayın. Kabul edilen parlaklık değerleri [-255, 255] aralığındadır.
    tiffImage.adjustBrightness(50);
    tiffImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


[Image](../../com.aspose.imaging/image) örneğinin kontrastını artırın, ışık ve karanlık bölgeler arasındaki farkları büyütün. Bu işlevi entegre ederek uygulamanız içinde görüntünün görsel netliğini ve genel kalitesini iyileştirin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| contrast | float | Kontrast değeri ([-100; 100] aralığında) |


**Example: The following example performs contrast correction of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Kontrast değerini ayarlayın. Kabul edilen kontrast değerleri [-100f, 100f] aralığındadır.
    tiffImage.adjustContrast(50f);
    tiffImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Belirtilen dikdörtgen içindeki içeriği filtreleyin, seçilen bölgeyi geliştirmek veya değiştirmek için belirlenmiş bir görüntü işleme filtresi uygulayın. Bu yöntemi görüntü manipülasyonu iş akışınıza entegre edin, uygulamanız içinde hedeflenmiş iyileştirmeler veya dönüşümler elde edin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Dikdörtgen. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Seçenekler. |


**Example: The following example applies various types of filters to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Tüm görüntüye, dikdörtgen boyutu 5 olan bir medyan filtresi uygula.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    tiffImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Tüm görüntüye, çekirdek boyutu 5 olan çift taraflı yumuşatma filtresi uygula.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    tiffImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Tüm görüntüye, yarıçapı 5 ve sigma değeri 4.0 olan bir Gaussian bulanıklaştırma filtresi uygula.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    tiffImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Tüm görüntüye, yarıçapı 5 ve pürüzsüzlük değeri 4.0 olan bir Gauss-Wiener filtresi uygula.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    tiffImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Tüm görüntüye, uzunluğu 5, pürüzsüzlük değeri 4.0 ve açısı 90.0 derece olan bir hareket Wiener filtresi uygula.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    tiffImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Tüm görüntüye, çekirdek boyutu 5 ve sigma değeri 4.0 olan bir keskinleştirme filtresi uygula.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    tiffImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Belirtilen ayarlara göre görüntünün boyutunu ayarlayın, boyutlar, en‑boy oranı ve ölçekleme davranışı üzerinde hassas kontrol sağlar. Bu yöntemi görüntü işleme iş akışınıza entegre ederek uygulamanızın özel gereksinimlerine göre özelleştirilmiş yeniden boyutlandırma işlemlerine ulaşın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| newHeight | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Yeniden boyutlandırma ayarları. |


**Example: This example loads a TIFF image and resizes it using various resizing settings.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.ImageResizeSettings resizeSettings = new com.aspose.imaging.ImageResizeSettings();

// Ağırlıklı ve karıştırılmış rasyonel fonksiyon ve lanczos3 enterpolasyonu üzerine kurulu uyarlamalı algoritma.
resizeSettings.setMode(com.aspose.imaging.ResizeType.AdaptiveResample);

// Küçük dikdörtgen filtre
resizeSettings.setFilterType(com.aspose.imaging.ImageFilterType.SmallRectangular);

// Palet içindeki renk sayısı.
resizeSettings.setEntriesCount(256);

// Renk kantitatizasyonu kullanılmaz
resizeSettings.setColorQuantizationMethod(com.aspose.imaging.ColorQuantizationMethod.None);

// Euclidian yöntemi
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);

com.aspose.imaging.Image image = (com.aspose.imaging.Image) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Uyarlanabilir yeniden örnekleme kullanarak 2 kat küçült.
    tiffImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // PNG'ye kaydet
    tiffImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

