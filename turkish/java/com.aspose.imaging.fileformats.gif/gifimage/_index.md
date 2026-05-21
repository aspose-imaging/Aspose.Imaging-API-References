---
title: "GifImage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Graphical Interchange Format GIF görüntü dosyası için API, geliştiricilere sıkıştırılmış raster görüntüler ve animasyonlu GIF'ler işlemek için çok yönlü araçlar sağlar."
type: docs
weight: 13
url: /tr/java/com.aspose.imaging.fileformats.gif/gifimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext), com.aspose.fileformats.core.interfaces.IInterlaced
```
public final class GifImage extends RasterCachedMultipageImage implements IMultipageImageExt, IInterlaced
```

Graphical Interchange Format (GIF) görüntü dosyası için API, geliştiricilere sıkıştırılmış raster görüntüler ve animasyonlu GIF'leri işlemek için çok yönlü araçlar sunar. XMP meta veri işleme, renk paleti ayarları, arka plan ve şeffaf renk kontrolü, opaklık ayarları, yeniden boyutlandırma, kırpma, filtre uygulama, gama düzeltmeleri, kontrast ayarı, gri tonlama dönüşümü ve diğer formatlara dönüştürme gibi özellikler sağlar. Bu API, GIF görüntülerinin sorunsuz bir şekilde manipülasyonu ve iyileştirilmesini geniş bir uygulama yelpazesi için mümkün kılar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)](#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-) | İlk çerçeve ve global palet için belirtilen parametrelerle yeni bir [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage) nesnesi başlatın. |
| [GifImage(GifFrameBlock firstFrame)](#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-) | [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage) yapıcı ile GIF görüntüleri oluşturmak zahmetsiz hale gelir. |
| [GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, boolean isPaletteSorted, byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, boolean hasTrailer)](#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-boolean-byte-byte-byte-boolean-) | [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage) yapıcı ile zahmetsizce başlayın. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Bu özellik ile dosya formatını zahmetsizce alın. |
| [hasTrailer()](#hasTrailer--) | Bu özellik ile GIF dosyalarınızda bir trailer'ın varlığını yönetin. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | Bu özellik ile GIF dosyalarınızda bir trailer'ın varlığını yönetin. |
| [isPaletteSorted()](#isPaletteSorted--) | Bu özellik kullanarak GIF görüntülerinizdeki palet sıralamasını kontrol edin. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Bu özellik kullanarak GIF görüntülerinizdeki palet sıralamasını kontrol edin. |
| [getLoopsCount()](#getLoopsCount--) | Bu özellik ile döngü sayısını zahmetsizce alın. |
| [setLoopsCount(int value)](#setLoopsCount-int-) | Bu özellik ile döngü sayısını zahmetsizce alın. |
| [getPaletteColorResolutionBits()](#getPaletteColorResolutionBits--) | Bu özellik ile GIF görüntülerinizin palet renk çözünürlüğünü yönetin. |
| [setPaletteColorResolutionBits(byte value)](#setPaletteColorResolutionBits-byte-) | Bu özellik ile GIF görüntülerinizin palet renk çözünürlüğünü yönetin. |
| [getPageCount()](#getPageCount--) | Bu basit özellik ile görüntü içinde bulunan toplam sayfa sayısını alın. |
| [getPages()](#getPages--) | Bu kullanışlı özellik sayesinde görüntü içindeki sayfalara erişin, ihtiyaç duyulduğunda tek tek sayfaları sorunsuzca gezip manipüle edin. |
| [getBlocks()](#getBlocks--) | Bu özellik ile GIF bloklarına sorunsuzca erişin, görüntünün temel veri yapılarını kolayca alıp manipüle edin. |
| [isInterlaced()](#isInterlaced--) | Görüntünün taramalı (interlaced) olup olmadığını belirler, bu da yükleme sırasında görüntülenmesini etkiler. |
| [getOriginalOptions()](#getOriginalOptions--) | Orijinal dosya ayarlarına dayalı seçenekleri alın; bu, görüntü işleme ve manipülasyonda doğruluk ve tutarlılığı korumak için kritiktir. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Yeni bir sayfayı mevcut görüntüye sorunsuzca ekleyin, içeriğini zenginleştirin ve kapsamını genişletin. |
| [getActiveFrame()](#getActiveFrame--) | Bu özellik ile çerçeveleri yönetin ve manipüle edin, GIF görüntüsündeki aktif çerçeveye sorunsuzca gezinmeyi ve değiştirmeyi sağlayın. |
| [setActiveFrame(GifFrameBlock value)](#setActiveFrame-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-) | Bu özellik ile çerçeveleri yönetin ve manipüle edin, GIF görüntüsündeki aktif çerçeveye sorunsuzca gezinmeyi ve değiştirmeyi sağlayın. |
| [getBackgroundColor()](#getBackgroundColor--) | Bu özellik ile GIF görüntüsünün arka plan rengini yönetin. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Bu özellik ile GIF görüntüsünün arka plan rengini yönetin. |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Bu özellik kullanarak GIF görüntüsünün arka plan renk indeksini kontrol edin. |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Bu özellik kullanarak GIF görüntüsünün arka plan renk indeksini kontrol edin. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | Bu özellik ile GIF görüntüsünün piksel en‑boy oranını yönetin. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Bu özellik ile GIF görüntüsünün piksel en‑boy oranını yönetin. |
| [hasTransparentColor()](#hasTransparentColor--) | GIF görüntüsünün aktif çerçevesinin şeffaf bir renk içerip içermediğini belirleyin. |
| [getTransparentColor()](#getTransparentColor--) | GIF görüntüsündeki aktif çerçevenin şeffaf rengini alın. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | GIF görüntüsünün aktif çerçevesinin şeffaf bir renk içerip içermediğini belirleyin. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Bu özellik, GIF görüntüsünün bir arka plan rengine sahip olup olmadığını belirler. |
| [getImageOpacity()](#getImageOpacity--) | Görüntü içindeki aktif çerçevenin opaklığını alın, şeffaflık seviyesine dair bilgi sağlar. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Bu [Image](../../com.aspose.imaging/image) örneğinin boyutunu değiştirir. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Bu [Image](../../com.aspose.imaging/image) örneğinin boyutunu değiştirir. |
| [resizeFullFrame(int newWidth, int newHeight, int resizeType)](#resizeFullFrame-int-int-int-) | GIF'teki her sayfa için tam çerçeveleri göz önünde bulundurarak görüntünün yeniden boyutlandırılması, böylece olası artefaktların oluşmasını önler. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Sadece aktif çerçeve üzerinde döndürme, çevirme veya her ikisini birden uygulayın. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Mevcut görüntüye dithering uygulayın. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Belirtilen dikdörtgen alanı kullanarak görüntüyü kırpın. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Gamma düzeltmesi uygulayarak görüntü kalitesini artırın. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Görüntünün belirlenen alanına özel bir filtre uygulayın, görsel kalitesini artırın veya görünümünü istediğiniz gibi değiştirin. |
| [setFrameTime(int time)](#setFrameTime-int-) | Her çerçevenin süresini milisaniye cinsinden ayarlar, görüntü dizisi boyunca tutarlı zamanlamayı sağlar. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Görüntünün parlaklığını belirtilen `brightness` parametresine göre ayarlar. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Görüntünün kontrastını ayarlar, pikseller arasındaki parlaklık farkını artırır veya azaltır. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Bir görüntünün gama düzeltmesi, piksel değerlerine doğrusal olmayan bir ayar uygular; kırmızı, yeşil ve mavi kanallar için belirtilen katsayılara göre parlaklığı artırır veya azaltır. |
| [grayscale()](#grayscale--) | Bir görüntünün gri tonlamalı temsile dönüştürülmesi, renk bilgisini kaldırarak ve parlaklığı koruyarak renkli görüntüyü gri tonlamalı bir versiyona çevirir. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Önceden tanımlı bir eşik ile bir görüntünün ikilileştirilmesi, gri tonlamalı veya renkli görüntüyü ikili bir görüntüye dönüştürür; her piksel, yoğunluk değeri belirtilen eşiği aşarsa siyah veya beyaz olarak sınıflandırılır. |
| [binarizeOtsu()](#binarizeOtsu--) | Otsu eşikleme ile bir görüntünün ikilileştirilmesi, gri tonlamalı bir görüntüyü ikili bir görüntüye dönüştürmek için optimal eşik değerini otomatik olarak belirlemek amacıyla kullanılan bir yöntemdir. |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Bradley'in adaptif eşikleme algoritması ve integral görüntü eşikleme kullanılarak bir görüntünün ikilileştirilmesi, gri tonlamalı bir görüntüyü ikili bir görüntüye dönüştürmek için bir yöntemdir. |
| [orderBlocks()](#orderBlocks--) | GIF bloklarını GIF spesifikasyonuna göre sıralamak, doğru GIF düzenini ve standarda uyumu sağlar. |
| [clearBlocks()](#clearBlocks--) | Tüm GIF bloklarını temizlemek, görüntü içinde depolanmış mevcut verileri kaldırır. |
| [insertBlock(int index, IGifBlock block)](#insertBlock-int-com.aspose.imaging.fileformats.gif.IGifBlock-) | Yeni bir GIF bloğu eklemek, görüntü içinde belirli bir konuma özel veri eklemenizi sağlar. |
| [addBlock(IGifBlock block)](#addBlock-com.aspose.imaging.fileformats.gif.IGifBlock-) | Yeni bir GIF bloğu eklemek, görüntü içinde ek veri eklemenize olanak tanır. |
| [removeBlock(IGifBlock block)](#removeBlock-com.aspose.imaging.fileformats.gif.IGifBlock-) | Bir GIF bloğunu kaldırmak, görüntüden belirli verileri siler ve görüntü yapısını temizleme veya değiştirme imkanı sunar. |
| [resizeProportional(int newWidth, int newHeight, int resizeType)](#resizeProportional-int-int-int-) | Orantılı yeniden boyutlandırma, görüntünün en‑boy oranını korurken boyutunu ayarlar ve görüntünün gerilmiş veya bozulmuş görünmesini engeller. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Bu yöntem, görüntüyü merkez noktasının etrafında döndürür. |

## Example: This example shows how to create a GIF image and save it to a file.

``` java
String dir = "c:\\temp\\";

// 100x100 piksel boyutunda bir GIF Çerçeve bloğu oluşturun.
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
try {
    // Tüm bloğu kırmızı ile doldurun.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(firstBlock);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    gr.fillRectangle(brush, firstBlock.getBounds());

    com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
    try {
        gifImage.save(dir + "output.gif");
    } finally {
        gifImage.dispose();
    }
} finally {
    firstBlock.dispose();
}
```


## Example: Create multipage GIF image using single page raster images.

``` java
static void main(String[] args)
{
    // Çerçeveleri yükle
    RasterImage[] frames = loadFrames("Animation frames");

    // İlk çerçeveyi kullanarak GIF görüntüsü oluşturun
    try (GifImage image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // AddPage yöntemiyle GIF görüntüsüne çerçeveler ekleyin
        for (int index = 1; index < frames.length; index++)
        {
            image.addPage(frames[index]);
        }

        // GIF görüntüsünü kaydedin
        image.save("Multipage.gif");
    }

    // kaynakları serbest bırak
    for (RasterImage frame : frames)
    {
        frame.close();
    }
}

private static RasterImage[] loadFrames(String directory)
{
    LinkedList<RasterImage> list = new LinkedList<RasterImage>();
    String[] fileList = new File(directory).list();
    if (fileList != null)
    {
        for (String filePath : fileList)
        {
            list.add((RasterImage) Image.load(filePath));
        }
    }
                
    return list.toArray(new RasterImage[0]);
}
```


## Example: Export of part of animation from GIF image based on time interval.

``` java
try (Image image = Image.load("Animation.gif"))
{
    GifOptions options = new GifOptions();
    options.setFullFrame(true);
    final MultiPageOptions multiPageOptions = new MultiPageOptions();
    multiPageOptions.setMode(MultiPageMode.TimeInterval);
    multiPageOptions.setTimeInterval(new TimeInterval(0, 400));
    options.setMultiPageOptions(multiPageOptions);

    image.save("PartOfAnimation.gif", options);
}
```

### GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette) {#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-}
```
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)
```


İlk çerçeve ve global palet için belirtilen parametrelerle yeni bir [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage) nesnesi başlatın. GIF görüntülerini hızlı bir şekilde yönetmeye başlayın, özelleştirilebilir ayarlarla doğru temsili ve optimal sonuçları sağlayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| firstFrame | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | GIF görüntüsünü başlatmak için kullanılacak ilk çerçeve. |
| globalPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Kullanılacak global palet. `firstFrame` ve `globalPalette` ikisi de null ise varsayılan global paletin kullanılacağını unutmayın. |

### GifImage(GifFrameBlock firstFrame) {#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-}
```
public GifImage(GifFrameBlock firstFrame)
```


GIF görüntüleri oluşturmak, [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage) yapıcısı sayesinde zahmetsiz hale gelir. Sadece firstFrame parametresiyle, dinamik görsel iletişimin bir dünyasına adım atarsınız.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| firstFrame | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | GIF görüntüsünü başlatmak için kullanılacak ilk çerçeve. |

### GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, boolean isPaletteSorted, byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, boolean hasTrailer) {#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-boolean-byte-byte-byte-boolean-}
```
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, boolean isPaletteSorted, byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, boolean hasTrailer)
```


Get started effortlessly with the [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage) constructor. Bu basit yöntemle, animasyonlu GIF'ler oluşturmanın içine kolayca dalabilirsiniz. Sadece firstFrame, globalPalette, paletteColorResolution, aspectRatio ve diğer parametreleri sağlayın, böylece görsellerinizi hayata geçirmek için hazırsınız.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| firstFrame | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | GIF görüntüsünü başlatmak için kullanılacak ilk çerçeve. |
| globalPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Kullanılacak global palet. `firstFrame` ve `globalPalette` ikisi de null ise varsayılan global paletin kullanılacağını unutmayın. |
| isPaletteSorted | boolean | `true` olarak ayarlanırsa palet sıralanır. Not: parametre `globalPalette` null olmadığında kullanılır. |
| paletteColorResolution | byte | Palet renk çözünürlüğü. Not: parametre `globalPalette` null olmadığında kullanılır. |
| paletteBackgroundColorIndex | byte | Palet arka plan renk indeksi. |
| aspectRatio | byte | En-boy oranı. |
| hasTrailer | boolean | `true` olarak ayarlanırsa GIF görüntüsü trailer içerir, aksi takdirde akışın sonunda trailer yazılmaz. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Bu özellik ile dosya formatını zahmetsizce alın. Dosyalarınızın formatını tanımlamak için başvuracağınız kaynaktır. İş akışınıza sorunsuz bir şekilde entegre olur ve herhangi bir zorluk olmadan hayati bilgiler sunar.

**Returns:**
long
### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Bu özellik ile GIF dosyalarınızda trailer varlığını yönetin. Trailer'ın mevcut olup olmadığını kontrol etmeniz ya da varlığını ayarlamanız gerektiğinde, bu özellik süreci basitleştirir. GIF dosyalarınızı yapılandırılmış ve uyumlu tutmak için bu sezgisel özelliği kullanın.

**Returns:**
boolean - `true` ise GIF'in trailer'ı vardır; aksi takdirde `false`.
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Bu özellik ile GIF dosyalarınızda trailer varlığını yönetin. Trailer'ın mevcut olup olmadığını kontrol etmeniz ya da varlığını ayarlamanız gerektiğinde, bu özellik süreci basitleştirir. GIF dosyalarınızı yapılandırılmış ve uyumlu tutmak için bu sezgisel özelliği kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | `true` ise GIF'in trailer'ı vardır; aksi takdirde `false`. |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Bu özellik ile GIF görüntülerinizde paletin sıralanmasını kontrol edin. Paletin sıralı olup olmadığını kontrol etmeniz ya da sıralama davranışını ayarlamanız gerektiğinde, bu özellik palet organizasyonunu yönetmenin doğrudan bir yolunu sunar.

**Returns:**
boolean - palet sıralıysa `true`; aksi takdirde `false`.
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Bu özellik ile GIF görüntülerinizde paletin sıralanmasını kontrol edin. Paletin sıralı olup olmadığını kontrol etmeniz ya da sıralama davranışını ayarlamanız gerektiğinde, bu özellik palet organizasyonunu yönetmenin doğrudan bir yolunu sunar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | `true` if palette is sorted; otherwise, `false`. |

### getLoopsCount() {#getLoopsCount--}
```
public int getLoopsCount()
```


Bu özellik ile döngü sayısını zahmetsizce alın. GIF görüntünüz döngü bilgisi içeriyorsa, bu özellik döngü sayısına hızlı erişim sağlar ve GIF dosyalarınızda döngü davranışını sorunsuz bir şekilde yönetmenize olanak tanır.

**Returns:**
int - Döngü sayısı veya 1 (varsayılan değer)
### setLoopsCount(int value) {#setLoopsCount-int-}
```
public void setLoopsCount(int value)
```


Bu özellik ile döngü sayısını zahmetsizce alın. GIF görüntünüz döngü bilgisi içeriyorsa, bu özellik döngü sayısına hızlı erişim sağlar ve GIF dosyalarınızda döngü davranışını sorunsuz bir şekilde yönetmenize olanak tanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Döngü sayısı veya 1 (varsayılan değer) |

### getPaletteColorResolutionBits() {#getPaletteColorResolutionBits--}
```
public byte getPaletteColorResolutionBits()
```


Bu özellik ile GIF görüntülerinizin palet renk çözünürlüğünü yönetin. Palette renkleri temsil etmek için kullanılan bit sayısını ayarlayarak renk derinliği ve görüntü kalitesi üzerinde hassas kontrol sağlayın.

**Returns:**
byte - Palet renk çözünürlüğü bitleri.
### setPaletteColorResolutionBits(byte value) {#setPaletteColorResolutionBits-byte-}
```
public void setPaletteColorResolutionBits(byte value)
```


Bu özellik ile GIF görüntülerinizin palet renk çözünürlüğünü yönetin. Palette renkleri temsil etmek için kullanılan bit sayısını ayarlayarak renk derinliği ve görüntü kalitesi üzerinde hassas kontrol sağlayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte | Palet renk çözünürlüğü bitleri. |

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Bu basit özellik ile görüntü içinde bulunan toplam sayfa sayısını alın. Görüntü içeriğinin kapsamını hızlıca değerlendirmek için idealdir.

**Returns:**
int - sayfa sayısı.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Bu kullanışlı özellik sayesinde görüntü içindeki sayfalara erişin, ihtiyaç duyulduğunda tek tek sayfaları sorunsuzca gezip manipüle edin.

**Returns:**
com.aspose.imaging.Image[] - sayfalar.
### getBlocks() {#getBlocks--}
```
public IGifBlock[] getBlocks()
```


Bu özellik ile GIF bloklarına sorunsuzca erişin, görüntünün temel veri yapılarını kolayca alıp manipüle edin.

**Returns:**
com.aspose.imaging.fileformats.gif.IGifBlock[] - GIF blokları.
### isInterlaced() {#isInterlaced--}
```
public boolean isInterlaced()
```


Görüntünün taramalı (interlaced) olup olmadığını belirler, bu da yükleme sırasında görüntülenmesini etkiler. Bu özellik, görüntünün render davranışı hakkında bilgi sunar ve yükleme stratejilerini optimize etmek ve genel izleme deneyimini artırmak için gereklidir.

**Returns:**
boolean - bu görüntü örneği taramalıysa `true`; aksi takdirde `false`.
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Orijinal dosya ayarlarına dayalı seçenekleri alın, bu seçenekler görüntü işleme ve manipülasyonunda doğruluk ve tutarlılığı korumak için kritiktir. Bu yöntem, dosyaya özgü parametrelerin sonraki işlemlere sorunsuz entegrasyonunu sağlar, doğru bir render ve görüntünün doğal özelliklerine uyumu temin eder. Bu, orijinal görüntünün bit derinliği ve diğer parametrelerinin değişmeden kalmasına yardımcı olabilir. Örneğin, 1 bit/piksel siyah-beyaz bir PNG görüntüsü yüklerseniz ve ardından [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-) yöntemini kullanarak kaydederseniz, 8 bit/piksel çıkış PNG görüntüsü üretilir. Bunu önlemek ve 1 bit/piksel PNG görüntüsü kaydetmek için bu yöntemi kullanarak ilgili kaydetme seçeneklerini alın ve bunları ikinci parametre olarak [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) yöntemine geçirin.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Yeni bir sayfayı mevcut görüntüye sorunsuz bir şekilde ekleyin, içeriğini zenginleştirin ve kapsamını genişletin. Bu yöntem, görüntü koleksiyonlarını ek içerikle artırarak görüntü yönetimi ve kompozisyonunda yaratıcılık ve esnekliği teşvik eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | Eklenecek sayfa. |


**Example: Create multipage GIF image using single page raster images.**

``` java
static void main(String[] args)
{
    // Çerçeveleri yükle
    RasterImage[] frames = loadFrames("Animation frames");

    // İlk çerçeveyi kullanarak GIF görüntüsü oluşturun
    try (GifImage image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // AddPage yöntemiyle GIF görüntüsüne çerçeveler ekleyin
        for (int index = 1; index < frames.length; index++)
        {
            image.addPage(frames[index]);
        }

        // GIF görüntüsünü kaydedin
        image.save("Multipage.gif");
    }

    // kaynakları serbest bırak
    for (RasterImage frame : frames)
    {
        frame.close();
    }
}

private static RasterImage[] loadFrames(String directory)
{
    LinkedList<RasterImage> list = new LinkedList<RasterImage>();
    String[] fileList = new File(directory).list();
    if (fileList != null)
    {
        for (String filePath : fileList)
        {
            list.add((RasterImage) Image.load(filePath));
        }
    }
                
    return list.toArray(new RasterImage[0]);
}
```

### getActiveFrame() {#getActiveFrame--}
```
public GifFrameBlock getActiveFrame()
```


Bu özellik ile çerçeveleri yönetin ve manipüle edin, GIF görüntüsündeki aktif çerçeveye sorunsuzca gezinmeyi ve değiştirmeyi sağlayın.

**Returns:**
[GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) - the active frame.

**Example: The following example shows how to remove all blocks from a GIF image.**

``` java
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
try {
    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }

    System.out.println("Clear all the blocks");
    gifImage.clearBlocks();

    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }
} finally {
    firstBlock.dispose();
    gifImage.dispose();
}

// Çıktı şu şekilde görünür:
// Etkin çerçeve boyutu: { Width = 100, Height = 100}
// Tüm blokları temizle
// Etkin çerçeve ayarlanmamış
```

### setActiveFrame(GifFrameBlock value) {#setActiveFrame-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-}
```
public void setActiveFrame(GifFrameBlock value)
```


Bu özellik ile çerçeveleri yönetin ve manipüle edin, GIF görüntüsündeki aktif çerçeveye sorunsuzca gezinmeyi ve değiştirmeyi sağlayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | etkin çerçeve. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Bu özellik ile GIF görüntüsünün arka plan rengini yönetin. Tutarlılığı sağlamak ve görsel çekiciliği artırmak için arka plan rengini ayarlayabilir veya alabilirsiniz.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Bu özellik ile GIF görüntüsünün arka plan rengini yönetin. Tutarlılığı sağlamak ve görsel çekiciliği artırmak için arka plan rengini ayarlayabilir veya alabilirsiniz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | arka plan rengi. |

### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Bu özellik kullanarak GIF görüntüsünün arka plan renk indeksini kontrol edin. Tutarlılığı korumak veya istenen görsel etkileri elde etmek için indeksi ayarlayabilir veya alabilirsiniz.

**Returns:**
byte - arka plan renk indeksi.
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Bu özellik kullanarak GIF görüntüsünün arka plan renk indeksini kontrol edin. Tutarlılığı korumak veya istenen görsel etkileri elde etmek için indeksi ayarlayabilir veya alabilirsiniz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte | arka plan renk indeksi. |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Bu özellik ile GIF görüntüsünün piksel en‑boy oranını yönetin. Doğru renderleme sağlamak ve görsel doğruluğu korumak için en‑boy oranını ayarlayabilir veya alabilirsiniz.

**Returns:**
byte - piksel en‑boy oranı.
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Bu özellik ile GIF görüntüsünün piksel en‑boy oranını yönetin. Doğru renderleme sağlamak ve görsel doğruluğu korumak için en‑boy oranını ayarlayabilir veya alabilirsiniz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte | piksel en‑boy oranı. |

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


GIF görüntüsünün etkin çerçevesinin şeffaf bir renk içerip içermediğini belirleyin. Bu özellik, görüntü içinde şeffaflığı kontrol etmenin pratik bir yolunu sunar.

**Returns:**
boolean - etkin çerçevenin şeffaf renk içerip içermediğini gösteren bir değer.
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


GIF görüntüsündeki etkin çerçevenin şeffaf rengini alın. Bu özellik, şu anda etkin olan çerçevede şeffaf olarak belirlenmiş belirli renge erişmenizi sağlar.

**Returns:**
[Color](../../com.aspose.imaging/color) - active frame transparent color.
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


GIF görüntüsünün etkin çerçevesinin şeffaf bir renk içerip içermediğini belirleyin. Bu özellik, görüntü içinde şeffaflığı kontrol etmenin pratik bir yolunu sunar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | etkin çerçevenin şeffaf renk içerip içermediğini gösteren bir değer. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Bu özellik, GIF görüntüsünün bir arka plan rengi içerip içermediğini belirler. True ise, görüntünün bir arka plan rengi içerdiğini gösterir.

**Returns:**
boolean - görüntünün arka plan rengine sahip olup olmadığını gösteren bir değer.
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Görüntüdeki etkin çerçevenin opaklığını alın, şeffaflık seviyesine dair bilgi sağlar. Bu özellik, görüntüdeki etkin çerçevenin şeffaflık ya da matlık derecesini anlamak için özellikle faydalıdır.

0.0 (tamamen şeffaf) ile 1.0 (tamamen opak) arasında opaklık değeri.

**Returns:**
float - bu görüntünün (etkin çerçeve) opaklığı.
### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Bu [Image](../../com.aspose.imaging/image) örneğinin boyutunu değiştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| newHeight | int | Yeni yükseklik. |
| resizeType | int | Yeniden boyutlandırma türü. |


**Example: This example loads a GIF image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.gif.GifImage image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat büyüt.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat küçült.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat büyüt.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat küçült.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Bu [Image](../../com.aspose.imaging/image) örneğinin boyutunu değiştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| newHeight | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Ayarlar. |


**Example: This example loads a GIF image and resizes it using various resizing settings.**

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

// Öklid yöntemi
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Uyarlanabilir yeniden örnekleme kullanarak 2 kat küçült.
    gifImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // PNG'ye kaydet
    gifImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeFullFrame(int newWidth, int newHeight, int resizeType) {#resizeFullFrame-int-int-int-}
```
public void resizeFullFrame(int newWidth, int newHeight, int resizeType)
```


GIF'teki her sayfa için tam çerçeveleri dikkate alarak görüntünün yeniden boyutlandırılması, böylece olası artefaktların ortaya çıkmasını önler. Bu yöntem, özellikle hareketli GIF'lerle veya çerçeve dizileriyle çalışırken görüntünün bütünlüğünü ve kalitesini korumak için gereklidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| newHeight | int | Yeni yükseklik. |
| resizeType | int | Yeniden boyutlandırma türü. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Aktif çerçeve üzerinde yalnızca döndürme, çevirme veya her ikisini gerçekleştirin. Bu işlem, yalnızca görüntünün şu anda aktif olan çerçevesine dönüşümler uygular ve dizideki diğer çerçevelerin bütünlüğünü korur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rotateFlipType | int | Döndürme çevirme türü. |


**Example: This example loads a GIF image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java

// Aşağıdaki ana örnekte kullanılan yardımcı sınıf.
class Utils {
    // Dosya formatının dize temsili almayı sağlayan yardımcı metod.
    public String getRotateFlipTypeString(int rotateFlipType) {
        if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipNone) {
            return "RotateNoneFlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipNone) {
            return "Rotate90FlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipNone) {
            return "Rotate180FlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipNone) {
            return "Rotate270FlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipX) {
            return "RotateNoneFlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipX) {
            return "Rotate90FlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipX) {
            return "Rotate180FlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipX) {
            return "Rotate270FlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipY) {
            return "RotateNoneFlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipY) {
            return "Rotate90FlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipY) {
            return "Rotate180FlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipY) {
            return "Rotate270FlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipXY) {
            return "RotateNoneFlipXY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipXY) {
            return "Rotate90FlipXY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipXY) {
            return "Rotate180FlipXY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipXY) {
            return "Rotate270FlipXY";
        } else {
            return "UNDEFINED";
        }
    }
}

// İşte ana örnek.
Utils utils = new Utils();

String dir = "c:\\temp\\";

int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

for (int rotateFlipType : rotateFlipTypes) {
    // Döndür, çevir ve çıktıyı dosyaya kaydet.
    com.aspose.imaging.fileformats.gif.GifImage image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + utils.getRotateFlipTypeString(rotateFlipType) + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Mevcut görüntüye dithering uygulayın. Bu süreç, renk bantlamasını azaltarak ve renk geçişlerini iyileştirerek görüntü kalitesini artırır, daha pürüzsüz bir görünüm sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ditheringMethod | int | Dithering yöntemi. |
| bitsCount | int | Dithering için son bit sayısı. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Dithering için özel palet. |


**Example: The following example loads a GIF image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // 16 renk içeren 4-bit renk paleti kullanarak eşik dithering uygulayın.
    // Daha fazla bit belirtildiğinde çıktı görüntüsünün kalitesi daha yüksek ve boyutu daha büyük olur.
    // Şu anda yalnızca 1-bit, 4-bit ve 8-bit paletlerin desteklendiğini unutmayın.
    gifImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    gifImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Sadece 2 renk (siyah ve beyaz) içeren 1-bit renk paleti kullanarak Floyd dithering uygulayın.
    // Daha fazla bit belirtildiğinde çıktı görüntüsünün kalitesi daha yüksek ve boyutu daha büyük olur.
    // Şu anda yalnızca 1-bit, 4-bit ve 8-bit paletlerin desteklendiğini unutmayın.
    gifImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    gifImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Belirtilen dikdörtgen alanı kullanarak görüntüyü kırpın. Bu işlem, görüntünün dış kısmını kaldırır ve yalnızca dikdörtgenle tanımlanan seçili bölgeyi bırakır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Dikdörtgen. |


**Example: The following example crops a GIF image.**
Aşağıdaki örnek bir GIF görüntüsünü kırpar. Kırpma alanı Aspose.Imaging.Rectangle aracılığıyla belirtilir.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Görüntüyü kırp. Kırpma alanı, görüntünün dikdörtgen merkezi alanıdır.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(
            gifImage.getWidth() / 4,
            gifImage.getHeight() / 4,
            gifImage.getWidth() / 2,
            gifImage.getHeight() / 2);
    gifImage.crop(area);

    // Kırpılmış görüntüyü PNG olarak kaydet.
    gifImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Görüntü kalitesini gama düzeltmesi uygulayarak artırın. Bu yöntem, görüntünün renk gamasını optimal görsel netliğe ulaşacak şekilde ayarlar. Her pikselin gama değerini değiştirerek renk sunumunu ve genel görüntü görünümünü iyileştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| gamma | float | Kırmızı, yeşil ve mavi kanallar için gamma katsayısı |


**Example: The following example performs gamma-correction of a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Kırmızı, yeşil ve mavi kanallar için gamma katsayısını ayarlayın.
    gifImage.adjustGamma(2.5f);
    gifImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Görüntünün belirlenen alanına özel bir filtre uygulayın, görsel kalitesini artırın veya istediğiniz gibi görünümünü değiştirin. Bu yöntem, tanımlı dikdörtgen içindeki pikselleri seçici olarak işler, hedefli ayarlamaların yapılmasına izin verirken çevredeki görüntü verisinin bütünlüğünü korur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Dikdörtgen. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Seçenekler. |


**Example: The following example applies various types of filters to a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Tüm görüntüye, dikdörtgen boyutu 5 olan bir medyan filtresi uygula.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    gifImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Tüm görüntüye, çekirdek boyutu 5 olan çift taraflı yumuşatma filtresi uygula.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    gifImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Tüm görüntüye, yarıçapı 5 ve sigma değeri 4.0 olan bir Gaussian bulanıklaştırma filtresi uygula.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    gifImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Tüm görüntüye, yarıçapı 5 ve pürüzsüzlük değeri 4.0 olan bir Gauss-Wiener filtresi uygula.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    gifImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Tüm görüntüye, uzunluğu 5, pürüzsüzlük değeri 4.0 ve açısı 90.0 derece olan bir hareket Wiener filtresi uygula.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    gifImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Tüm görüntüye, çekirdek boyutu 5 ve sigma değeri 4.0 olan bir keskinleştirme filtresi uygula.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    gifImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### setFrameTime(int time) {#setFrameTime-int-}
```
public void setFrameTime(int time)
```


Her çerçevenin süresini milisaniye cinsinden ayarlar, görüntü dizisi boyunca tutarlı zamanlamayı sağlar. Bu yöntem, her çerçeve için görüntüleme süresini eşit şekilde ayarlar ve animasyon hızının hassas kontrolüne izin verir. Bu değeri değiştirmek, tüm çerçevelerin gecikmesini sıfırlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| zaman | int | Çerçeve süresinin milisaniye cinsinden zamanı. |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Görüntünün parlaklığını belirtilen `brightness` parametresine göre ayarlar. Bu yöntem, tüm görüntünün parlaklığını eşit şekilde değiştirir, istenen etkiyi elde etmek için genel parlaklığı artırır veya azaltır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brightness | int | Parlaklık değeri. |


**Example: The following example performs brightness correction of a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Parlaklık değerini ayarlayın. Kabul edilen parlaklık değerleri [-255, 255] aralığındadır.
    gifImage.adjustBrightness(50);
    gifImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Görüntünün kontrastını ayarlar, pikseller arasındaki parlaklık farkını artırır veya azaltır. Bu yöntem, görüntünün genel ton aralığını değiştirir, karanlık bölgeleri daha karanlık, parlak bölgeleri daha parlak yaparak görsel netliği ve detayı iyileştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| contrast | float | Kontrast değeri ([-100; 100] aralığında) |


**Example: The following example performs contrast correction of a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Kontrast değerini ayarlayın. Kabul edilen kontrast değerleri [-100f, 100f] aralığındadır.
    gifImage.adjustContrast(50f);
    gifImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Bir görüntünün gama düzeltmesi, piksel değerlerine doğrusal olmayan bir ayarlama uygular, kırmızı, yeşil ve mavi kanallar için belirtilen katsayılara göre parlaklığı artırır veya azaltır. Bu yöntem, renk dengesini ve görüntünün parlaklığını ince ayarlamaya yardımcı olur, genel görünümünü ve görsel kalitesini iyileştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| gammaRed | float | Kırmızı kanal katsayısı için gama |
| gammaGreen | float | Yeşil kanal katsayısı için gama |
| gammaBlue | float | Mavi kanal katsayısı için gamma |


**Example: The following example performs gamma-correction of a GIF image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Kırmızı, yeşil ve mavi kanallar için ayrı ayrı gamma katsayılarını ayarlayın.
    gifImage.adjustGamma(1.5f, 2.5f, 3.5f);
    gifImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


Bir görüntünün gri tonlamalı temsile dönüştürülmesi, renk bilgisini kaldırarak ve parlaklığı koruyarak renkli görüntüyü gri tonlamalı bir versiyona çevirir. Bu süreç, görüntüyü gri tonlara indirger ve baskı, belge işleme ve gri ton analizi gibi çeşitli uygulamalar için uygun hale getirir.


**Example: The following example transforms a colored GIF image to its grayscale representation.**
Aşağıdaki örnek renkli bir GIF görüntüsünü gri tonlamalı temsile dönüştürür. Gri tonlamalı görüntüler yalnızca gri tonlardan oluşur ve sadece yoğunluk bilgisi taşır.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    gifImage.grayscale();
    gifImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Önceden tanımlı bir eşik ile bir görüntünün ikilileştirilmesi, gri tonlamalı veya renkli görüntüyü ikili bir görüntüye dönüştürür; her piksel, yoğunluk değeri belirtilen eşiği aşarsa siyah veya beyaz olarak sınıflandırılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threshold | byte | Eşik değeri. Bir pikselin ilgili gri değeri eşiğin üzerindeyse, ona 255 değeri atanır, aksi takdirde 0 atanır. |


**Example: The following example binarizes a GIF image with the predefined threshold.**
Aşağıdaki örnek önceden tanımlı eşik değeriyle bir GIF görüntüsünü ikili hâle getirir. İkili görüntüler yalnızca 2 renk içerir - siyah ve beyaz.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage djvuImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Görüntüyü 127 eşik değeriyle ikilileştirin.
    // Bir pikselin ilgili gri değeri 127'den büyükse, ona 255 değeri atanır, aksi takdirde 0.
    djvuImage.binarizeFixed((byte) 127);
    djvuImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Otsu eşikleme ile bir görüntünün ikili hâle getirilmesi, gri tonlamalı bir görüntüyü ikili bir görüntüye dönüştürmek için optimal eşik değerini otomatik olarak belirlemek amacıyla kullanılan bir yöntemdir. Otsu eşikleme algoritması, iki ortaya çıkan sınıftaki (ön plan ve arka plan) piksel yoğunluklarının sınıf içi varyansını en aza indirecek eşik değerini hesaplar. Bu teknik, optimal eşik değeri bilinmediğinde ve görüntünün histogramına dayalı olarak uyarlamalı bir şekilde belirlenmesi gerektiğinde özellikle faydalıdır.


**Example: The following example binarizes a GIF image with Otsu thresholding.**
Aşağıdaki örnek Otsu eşikleme ile bir GIF görüntüsünü ikili hâle getirir. İkili görüntüler yalnızca 2 renk içerir - siyah ve beyaz.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Görüntüyü Otsu eşikleme ile ikilileştirin.
    gifImage.binarizeOtsu();
    gifImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


Bradley'in bütünsel görüntü eşikleme algoritmasıyla uyarlamalı eşikleme kullanarak bir görüntünün ikili hâle getirilmesi, gri tonlamalı bir görüntüyü ikili bir görüntüye dönüştürmek için bir yöntemdir. Bu algoritma, belirli bir pencere içinde çevredeki piksellerin ortalama yoğunluğuna dayanarak her piksel için yerel bir eşik hesaplar. Yerel piksel yoğunluklarına göre eşik uyarlamalı olarak ayarlandığında, Bradley yöntemi görüntüdeki ışık ve kontrast varyasyonlarını etkili bir şekilde yönetir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brightnessDifference | double | Bu pikselin etrafında merkezlenmiş s x s piksellik bir pencerenin ortalaması ile piksel arasındaki parlaklık farkı. |

### orderBlocks() {#orderBlocks--}
```
public void orderBlocks()
```


GIF bloklarını GIF spesifikasyonuna göre sıralamak, doğru GIF düzenini ve standarda uyumu sağlar. Bu süreç, blokları spesifikasyonda tanımlanan doğru sıraya yerleştirmeyi içerir. Ayrıca, son düzen için gerekli olmayan belirli [GifGraphicsControlBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock) örneklerini kaldırmayı da içerebilir. GIF spesifikasyonuna uyarak, ortaya çıkan görüntü doğru şekilde yapılandırılacak ve GIF görüntüleme uygulamalarıyla uyumlu olacaktır.

### clearBlocks() {#clearBlocks--}
```
public void clearBlocks()
```


Tüm GIF bloklarını temizlemek, görüntü içinde depolanan mevcut verileri kaldırır. Bu işlem, görüntüyü etkili bir şekilde boş bir duruma sıfırlar ve önceden eklenmiş blokları kaldırır. Bir GIF görüntüsü oluşturmak veya değiştirmek için temiz bir başlangıca ihtiyaç duyduğunuzda bu yöntemi kullanın.


**Example: The following example shows how to remove all blocks from a GIF image.**

``` java
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
try {
    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }

    System.out.println("Clear all the blocks");
    gifImage.clearBlocks();

    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }
} finally {
    firstBlock.dispose();
    gifImage.dispose();
}

// Çıktı şu şekilde görünür:
// Etkin çerçeve boyutu: { Width = 100, Height = 100}
// Tüm blokları temizle
// Etkin çerçeve ayarlanmamış
```

### insertBlock(int index, IGifBlock block) {#insertBlock-int-com.aspose.imaging.fileformats.gif.IGifBlock-}
```
public void insertBlock(int index, IGifBlock block)
```


Yeni bir GIF bloğu eklemek, görüntü içinde belirli bir konuma özel veri eklemenizi sağlar. Bu yöntem, GIF görüntüsünde istediğiniz konuma özel bloklar yerleştirmenize olanak tanır ve görüntü verisini düzenleme ve yapılandırmada esneklik sunar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Sıfır tabanlı öğe, bloğun ekleneceği konum. |
| block | [IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock) | Eklenecek GIF bloğu. |

### addBlock(IGifBlock block) {#addBlock-com.aspose.imaging.fileformats.gif.IGifBlock-}
```
public void addBlock(IGifBlock block)
```


Yeni bir GIF bloğu eklemek, görüntü içinde ek veri eklemenizi sağlar. Bu yöntem, GIF görüntüsüne çeşitli bilgi türlerini içerebilecek özel bloklar eklemenize olanak tanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| block | [IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock) | Eklenecek GIF bloğu. |


**Example: The following example shows how to compose an animated GIF image from individual GIF blocks.**

``` java
String dir = "c:\\temp\\";

// 100 x 100 piksel bir GIF görüntüsü oluşturun.
// İlk blok varsayılan olarak tamamen siyahtır.
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
try {
    // İlk daire kırmızıdır.
    com.aspose.imaging.brushes.SolidBrush brush1 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    // İkinci daire siyahtır.
    com.aspose.imaging.brushes.SolidBrush brush2 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getBlack());

    // Kırmızı yay şeklinin açısını kademeli olarak artırın.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock block = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);

        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(block);
        gr.fillPie(brush1, block.getBounds(), 0, angle);

        gifImage.addBlock(block);
    }

    // Siyah yay açısını kademeli olarak artırın ve kırmızı yay'ı silin.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock block = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);

        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(block);
        gr.fillPie(brush2, block.getBounds(), 0, angle);
        gr.fillPie(brush1, block.getBounds(), angle, 360 - angle);

        gifImage.addBlock(block);
    }

    gifImage.save(dir + "animated_radar.gif");
} finally {
    firstBlock.dispose();
    gifImage.dispose();
}
```

### removeBlock(IGifBlock block) {#removeBlock-com.aspose.imaging.fileformats.gif.IGifBlock-}
```
public void removeBlock(IGifBlock block)
```


Bir GIF bloğunu kaldırmak, görüntüden belirli verileri siler ve görüntü yapısını temizleme veya değiştirme imkanı sunar. Bu yöntem, istenmeyen veya gereksiz blokları kaldırmanıza olanak tanır ve GIF görüntüsünü verimli depolama için optimize eder. Bu işlevi, görüntünün bütünlüğünü ve kalitesini korurken eski bilgileri ortadan kaldırmak için kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | block | [IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock) | Kaldırılacak blok. |

--------------------

Not: Bloğu başka bir GifImage'e eklemeyecekseniz Dispose etmeyi unutmayın. |

### resizeProportional(int newWidth, int newHeight, int resizeType) {#resizeProportional-int-int-int-}
```
public void resizeProportional(int newWidth, int newHeight, int resizeType)
```


Orantılı yeniden boyutlandırma, görüntünün boyutunu ayarlarken en boy oranını korur ve görüntünün gerilmiş veya bozulmuş görünmesini engeller. Bu yöntem, görüntüyü orantılı olarak yeniden boyutlandırır ve genişlik ile yüksekliği aynı faktörle ölçeklendirir. Orantılı yeniden boyutlandırma, her çerçeveyi `newWidth`/width ve `newHeight`/height oranına göre yeniden boyutlandırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| newHeight | int | Yeni yükseklik. |
| resizeType | int | Yeniden boyutlandırma türü. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Bu yöntem, görüntüyü merkez noktasının etrafında döndürür. Döndürme açısını belirterek, görüntüyü saat yönünde veya saat yönünün tersine döndürerek istenen yönelimi elde edebilirsiniz. Bu dönüş, görüntünün sunumunu veya hizalamasını içeriğini bozmadan ayarlamaya yardımcı olur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| angle | float | Dönüş açısı dereceler cinsindendir. Pozitif değerler saat yönünde dönecektir. |
| resizeProportionally | boolean | eğer `true` olarak ayarlanırsa, görüntü boyutunuz döndürülmüş dikdörtgenin (köşe noktaları) izdüşümlerine göre değişir; diğer durumda boyutlar dokunulmaz kalır ve sadece `` görüntü içeriği döndürülür. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Arka planın rengi. |

