---
title: "DjvuImage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "DjVu belge sınıfı, grafik dosya formatını destekler ve taranmış belgeler ile kitapların metin, çizim, görüntü ve fotoğrafları tek bir formatta bütünleştirerek sorunsuz yönetimini sağlar."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.fileformats.djvu/djvuimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)
```
public final class DjvuImage extends RasterCachedMultipageImage
```

DjVu belge sınıfı, grafik dosya formatını destekler ve taranmış belgeler ile kitapların metin, çizim, görüntü ve fotoğrafları tek bir formatta bütünleştirerek sorunsuz yönetimini sağlar. Çok sayfalı işlemleri destekleyerek, benzersiz belge kimliklerine verimli bir şekilde erişebilir, sayfaları sayabilir, aktif sayfaları ayarlayabilir ve belirli belge sayfalarını alabilirsiniz. Yeniden boyutlandırma, döndürme, titreme, kırpma, gri ton dönüşümü, gama düzeltmeleri, ayarlamalar ve filtre uygulamaları gibi özelliklerle, bu sınıf DjVu görüntülerinin hassas manipülasyonu ve iyileştirilmesini kolaylık ve kesinlikle çeşitli uygulama ihtiyaçlarını karşılayacak şekilde güçlendirir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [DjvuImage(InputStream stream)](#DjvuImage-java.io.InputStream-) | Bir Stream parametresi kullanarak [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) sınıfının yeni bir örneğini başlatarak DjVu görüntüleriyle çalışmaya başlayın. |
| [DjvuImage(InputStream stream, LoadOptions loadOptions)](#DjvuImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Bu yapıcıyı kullanarak, bir Stream ve LoadOptions parametreleriyle yeni bir [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) sınıfı örneği başlatarak DjVu görüntüleriyle sorunsuz bir şekilde çalışmaya başlayın. |
| [DjvuImage(System.IO.Stream stream, LoadOptions loadOptions)](#DjvuImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-) | Bu yapıcıyı kullanarak, bir Stream ve LoadOptions parametreleriyle yeni bir [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) sınıfı örneği başlatarak DjVu görüntüleriyle sorunsuz bir şekilde çalışmaya başlayın. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [PropertyChanged](#PropertyChanged) | Bir özellik değeri değiştiğinde oluşur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [loadDocument(InputStream stream)](#loadDocument-java.io.InputStream-) | Bu yöntemle DjVu belgenizi yükleyin. |
| [loadDocument(InputStream stream, LoadOptions loadOptions)](#loadDocument-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Belgeyi yükler. |
| [getIdentifier()](#getIdentifier--) | Belge için benzersiz tanımlayıcıyı alır |
| [getPageCount()](#getPageCount--) | Bu özellik ile DjVu görüntü koleksiyonunuzdaki toplam sayfa sayısını alır. |
| [getPages()](#getPages--) | Bu özellik ile DjVu görüntü koleksiyonunuzdaki bireysel sayfalara erişirsiniz. |
| [getDjvuPages()](#getDjvuPages--) | Bu özelliği kullanarak DjVu belgenizde bulunan tüm sayfaları hızlıca alırsınız. |
| [getActivePage()](#getActivePage--) | Bu özelliği kullanarak DjVu belgenizdeki mevcut etkin sayfaya erişerek veya ayarlayarak gezinirsiniz. |
| [setActivePage(DjvuPage value)](#setActivePage-com.aspose.imaging.fileformats.djvu.DjvuPage-) | Bu özelliği kullanarak DjVu belgenizdeki mevcut etkin sayfaya erişerek veya ayarlayarak gezinirsiniz. |
| [getFirstPage()](#getFirstPage--) | Bu özellik ile DjVu belgenizin ilk sayfasına erişirsiniz. |
| [getLastPage()](#getLastPage--) | Bu özellik ile DjVu belgenizin son sayfasını alırsınız. |
| [getNextPage()](#getNextPage--) | Bu kullanışlı özellik ile DjVu belgenizde bir sonraki sayfaya erişerek gezinirsiniz. |
| [getPreviousPage()](#getPreviousPage--) | Bu kullanışlı özellik ile DjVu belgenizde önceki sayfaya erişerek görüntüleme veya işleme görevlerinde hızlıca geri hareket edersiniz. |
| [getFileFormat()](#getFileFormat--) | DjVu görüntü dosyanızla ilişkili dosya formatı bilgilerini elde edin. |
| [hasAlpha()](#hasAlpha--) | DjVu görüntü dosyanızın alfa kanalı içerip içermediğini hızlıca belirleyin. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | RasterCachedMultipageImage sınıfının Rotate yöntemiyle görüntüyü merkez etrafında döndürün. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Görüntüyü \`Resize\` yöntemiyle yeniden boyutlandırın; bu, gereksinimlerinize göre görüntülerinizin boyutlarını ayarlamanın basit ve etkili bir yolunu sunar. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | \`ResizeWidthProportionally\` yöntemi, görüntünüzün genişliğini en boy oranını koruyarak ayarlamak için kullanışlı bir çözüm sunar. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | \`ResizeHeightProportionally\` yöntemi, görüntünüzün yüksekliğini en boy oranını koruyarak ayarlamanıza olanak tanır. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | \`RotateFlip\` yöntemi, görüntünüz için çok yönlü işleme seçenekleri sunar; etkin çerçeve üzerinde bağımsız olarak döndürme, çevirme veya her ikisini birden yapmanıza izin verir. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | \"Dither\" işlevi, görüntünüze bir titreme etkisi uygular; bant oluşumunu azaltarak ve renk geçişlerini iyileştirerek görsel kalitesini artırır. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | \"Crop\" görüntünüzü belirli detaylara odaklanmak veya istenmeyen öğeleri kaldırmak için kırpar; kompozisyonunu ve görsel etkisini artırır. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Kaydırmalı kırpma, bir görüntü içinde kırpılan alanın konumunu ve boyutlarını hassas bir şekilde ayarlamanıza olanak tanır. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Önceden tanımlı bir eşik ile ikileştirme, karmaşık görüntüleri ikili temsillere sadeleştirir; pikseller, belirtilen eşik değerine göre yoğunlukları temelinde siyah ya da beyaz olarak sınıflandırılır. |
| [binarizeOtsu()](#binarizeOtsu--) | Otsu eşikleme kullanarak ikileştirme, görüntünün histogramına dayalı olarak otomatik olarak optimal bir eşik değeri hesaplayan bir tekniktir. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Bradley'in adaptif eşikleme algoritması ve integral görüntü eşikleme kullanarak ikileştirme, her piksel için yerel bir komşuluğa dayalı yerel eşik hesaplayan bir yöntemdir. |
| [grayscale()](#grayscale--) | Gri tonlamalı dönüşüm, bir görüntüyü siyah-beyaz temsile dönüştürür; her pikselin yoğunluğu, siyah ile beyaz arasında bir değerle temsil edilir. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Gamma düzeltmesi, özellikle kırmızı, yeşil ve mavi kanallar için, her renk bileşeninin parlaklığını ayrı ayrı ayarlamayı içerir. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Gamma düzeltmesi, kırmızı, yeşil ve mavi kanallar için özelleştirilebilir parametrelerle bir görüntüye uygulanır; bu, renk dengesi ve parlaklığın hassas ayarlanmasını sağlar. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Belirli bir parametre kullanarak bir görüntünün `brightness` değerini ayarlayın, optimal görsel netlik için parlaklık seviyeleri üzerinde kontrol sağlar. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Bu yöntemle [Görüntü](../../com.aspose.imaging/image) kontrastını artırarak görsel netliği iyileştirin ve detayları vurgulayın; ışık ve karanlık alanlar arasındaki parlaklık farkını ayarlar. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Görüntü içinde belirtilen dikdörtgen alana filtreler uygulayarak görünümünü iyileştirin veya değiştirin. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Görüntüyü belirtilen genişlik ve yüksekliğe yeniden boyutlandırın; gerektiğinde ek ayarları uygulayın. |
| [cacheData()](#cacheData--) | Verileri özel olarak önbelleğe alarak performansı optimize edin ve dış kaynaklardan tekrarlanan veri alım ihtiyacını azaltın. |

## Example: This example shows how to load a DJVU image from a file stream.

``` java
String dir = "c:\\temp\\";

// Bir dosya akışından DJVU görüntüsü yükleyin.
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
try {
    // Her sayfayı ayrı bir PNG görüntüsü olarak kaydedin.
    for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
        // Sayfa numarasına dayalı bir dosya adı oluşturun.
        String fileName = String.format("sample.%s.png", djvuPage.getPageNumber());
        djvuPage.save(dir + fileName, new com.aspose.imaging.imageoptions.PngOptions());
    }
} finally {
    djvuImage.dispose();
    stream.close();
}
```

### DjvuImage(InputStream stream) {#DjvuImage-java.io.InputStream-}
```
public DjvuImage(InputStream stream)
```


Bir Stream parametresi kullanarak [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) sınıfının yeni bir örneğini başlatarak DjVu görüntüleriyle çalışmaya başlayın. DjVu görüntü işleme entegrasyonunu projelerine sorunsuz eklemek isteyen geliştiriciler için mükemmeldir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Akış. |

### DjvuImage(InputStream stream, LoadOptions loadOptions) {#DjvuImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public DjvuImage(InputStream stream, LoadOptions loadOptions)
```


Bu yapıcıyı kullanarak DjVu görüntüleriyle sorunsuz bir şekilde çalışmaya başlayın; bir Stream ve LoadOptions parametreleriyle yeni bir [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) sınıf örneği başlatır. DjVu görüntü yükleme seçenekleri üzerinde hassas kontrol sağlarken basitlik ve verimliliği korumak isteyen geliştiriciler için idealdir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Yüklenecek akış. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Yükleme seçenekleri. |

### DjvuImage(System.IO.Stream stream, LoadOptions loadOptions) {#DjvuImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-}
```
public DjvuImage(System.IO.Stream stream, LoadOptions loadOptions)
```


Bu yapıcıyı kullanarak DjVu görüntüleriyle sorunsuz bir şekilde çalışmaya başlayın; bir Stream ve LoadOptions parametreleriyle yeni bir [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) sınıf örneği başlatır. DjVu görüntü yükleme seçenekleri üzerinde hassas kontrol sağlarken basitlik ve verimliliği korumak isteyen geliştiriciler için idealdir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | com.aspose.ms.System.IO.Stream | Yüklenecek akış. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Yükleme seçenekleri. |

### PropertyChanged {#PropertyChanged}
```
public final StdEvent<System.ComponentModel.PropertyChangedEventArgs> PropertyChanged
```


Bir özellik değeri değiştiğinde oluşur.

### loadDocument(InputStream stream) {#loadDocument-java.io.InputStream-}
```
public static DjvuImage loadDocument(InputStream stream)
```


Bu yöntemle DjVu belgenizi yükleyin. DjVu dosyalarınıza hızlıca erişerek ve uygulamanıza aktararak sürecinizi sadeleştirin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Akış. |

**Returns:**
[DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) - Loaded djvu document
### loadDocument(InputStream stream, LoadOptions loadOptions) {#loadDocument-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static DjvuImage loadDocument(InputStream stream, LoadOptions loadOptions)
```


Belgeyi yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Akış. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Yükleme seçenekleri. |

**Returns:**
[DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) - Loaded djvu document
### getIdentifier() {#getIdentifier--}
```
public int getIdentifier()
```


Belge için benzersiz tanımlayıcıyı alır

**Returns:**
int - Tanımlayıcı.
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Bu özellik ile DjVu görüntü koleksiyonunuzdaki toplam sayfa sayısını alın. DjVu formatında depolanan belgenizin veya kitabınızın kapsamını hızlıca değerlendirmek için idealdir. Doğru sayfa sayısı bilgisiyle iş akışı verimliliğinizi artırın.

**Returns:**
int - Sayfa sayısı.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Bu özellik ile DjVu görüntü koleksiyonunuzdaki bireysel sayfalara erişin. DjVu formatında depolanan belgenizin veya kitabınızın gezinmesini ve manipülasyonunu her sayfaya doğrudan erişerek basitleştirin. Kolay sayfa alımıyla iş akışı verimliliğinizi artırın.

**Returns:**
com.aspose.imaging.Image[] - Sayfalar.

**Example: This example shows how to load a DJVU image from a file stream.**

``` java
String dir = "c:\\temp\\";

// Bir dosya akışından DJVU görüntüsü yükleyin.
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
try {
    // Her sayfayı ayrı bir PNG görüntüsü olarak kaydedin.
    for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
        // Sayfa numarasına dayalı bir dosya adı oluşturun.
        String fileName = String.format("sample.%s.png", djvuPage.getPageNumber());
        djvuPage.save(dir + fileName, new com.aspose.imaging.imageoptions.PngOptions());
    }
} finally {
    djvuImage.dispose();
    stream.close();
}
```

### getDjvuPages() {#getDjvuPages--}
```
public DjvuPage[] getDjvuPages()
```


Bu özellik ile DjVu belgenizdeki tüm sayfaları hızlıca alın. DjVu dosyalarınızda bireysel sayfalara kolayca erişerek ve yöneterek belge işleme iş akışınızı basitleştirin. Kullanışlı sayfa alımıyla verimliliği artırın ve görevlerinizi düzenleyin.

**Returns:**
com.aspose.imaging.fileformats.djvu.DjvuPage[] - Sayfalar.
### getActivePage() {#getActivePage--}
```
public DjvuPage getActivePage()
```


Bu özellik ile mevcut aktif sayfayı alarak veya ayarlayarak DjVu belgenizde gezin. Belirli içeriğe odaklanmak ve belge görüntüleme deneyiminizi geliştirmek için sayfalar arasında sorunsuzca geçiş yapın.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage)

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Bir dosya akışından DJVU görüntüsü yükleyin.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//Çıktı şöyle görünebilir:
//Toplam sayfa sayısı: 2
//Etkin sayfa numarası:    1
//İlk sayfa numarası:     1
//Son sayfa numarası:      2
//--------------------------------------------------
//Sayfa numarası:     1
//Sayfa boyutu:       { Width = 2481, Height = 3508}
//Sayfa ham formatı: RgbIndexed1Bpp, kullanılan kanallar: 1
//--------------------------------------------------
//Sayfa numarası:     2
//Sayfa boyutu:       { Width = 2481, Height = 3508}
//Sayfa ham formatı: RgbIndexed1Bpp, kullanılan kanallar: 1
```

### setActivePage(DjvuPage value) {#setActivePage-com.aspose.imaging.fileformats.djvu.DjvuPage-}
```
public void setActivePage(DjvuPage value)
```


Bu özellik ile mevcut aktif sayfayı alarak veya ayarlayarak DjVu belgenizde gezin. Belirli içeriğe odaklanmak ve belge görüntüleme deneyiminizi geliştirmek için sayfalar arasında sorunsuzca geçiş yapın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) | Aktif sayfa. |

### getFirstPage() {#getFirstPage--}
```
public DjvuPage getFirstPage()
```


Bu özellik ile DjVu belgenizin ilk sayfasına erişin. Belgeyi verimli bir şekilde görüntülemeye veya işlemeye başlamak için ilk sayfayı hızlıca alın.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The first page.

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Bir dosya akışından DJVU görüntüsü yükleyin.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//Çıktı şöyle görünebilir:
//Toplam sayfa sayısı: 2
//Etkin sayfa numarası:    1
//İlk sayfa numarası:     1
//Son sayfa numarası:      2
//--------------------------------------------------
//Sayfa numarası:     1
//Sayfa boyutu:       { Width = 2481, Height = 3508}
//Sayfa ham formatı: RgbIndexed1Bpp, kullanılan kanallar: 1
//--------------------------------------------------
//Sayfa numarası:     2
//Sayfa boyutu:       { Width = 2481, Height = 3508}
//Sayfa ham formatı: RgbIndexed1Bpp, kullanılan kanallar: 1
```

### getLastPage() {#getLastPage--}
```
public DjvuPage getLastPage()
```


Bu özellik ile DjVu belgenizin son sayfasını alın. Görüntüleme veya işleme amaçları için son sayfaya kolayca ve hızlıca erişin.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The last page.

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Bir dosya akışından DJVU görüntüsü yükleyin.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//Çıktı şöyle görünebilir:
//Toplam sayfa sayısı: 2
//Etkin sayfa numarası:    1
//İlk sayfa numarası:     1
//Son sayfa numarası:      2
//--------------------------------------------------
//Sayfa numarası:     1
//Sayfa boyutu:       { Width = 2481, Height = 3508}
//Sayfa ham formatı: RgbIndexed1Bpp, kullanılan kanallar: 1
//--------------------------------------------------
//Sayfa numarası:     2
//Sayfa boyutu:       { Width = 2481, Height = 3508}
//Sayfa ham formatı: RgbIndexed1Bpp, kullanılan kanallar: 1
```

### getNextPage() {#getNextPage--}
```
public DjvuPage getNextPage()
```


Bu kullanışlı özellik ile sonraki sayfaya erişerek DjVu belgenizde gezin. Belge görüntüleme veya işleme görevlerinde hızlıca ileriye hareket edin.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The next page.
### getPreviousPage() {#getPreviousPage--}
```
public DjvuPage getPreviousPage()
```


Bu kullanışlı özellik ile önceki sayfaya erişerek DjVu belge görüntüleme veya işleme görevlerinde hızlıca geri hareket edin. Belgenizde sorunsuz ve verimli bir şekilde gezin.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The previous page.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


DjVu görüntü dosyanıza ilişkin dosya formatı bilgilerini edinin. İş akışınıza sorunsuz entegrasyon için dosyanızın formatını hızlıca belirleyin.

**Returns:**
long
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


DjVu görüntü dosyanızın alfa kanalı içerip içermediğini hızlıca belirleyin. Görüntülerinizde şeffaflık bilgisinin varlığını kontrol ederek iş akışınızı basitleştirin.

**Returns:**
boolean - Alfa kanalı vardır.
### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Resmi merkez etrafında, RasterCachedMultipageImage sınıfının Rotate metodunu kullanarak döndürün. Bu kullanışlı özellik, görüntülerin yönünü kolayca ayarlamanıza ve merkez konumlarını korumanıza olanak tanır, görüntü işleme yeteneklerinizi geliştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| angle | float | Derece cinsinden döndürme açısı. Pozitif değerler saat yönünde döndürür. |
| resizeProportionally | boolean | eğer `true` olarak ayarlanırsa, görüntü boyutunuz döndürülmüş dikdörtgenin (köşe noktaları) izdüşümlerine göre değişir; diğer durumda boyutlar dokunulmaz kalır ve sadece `` görüntü içeriği döndürülür. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Arka planın rengi. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Görüntüyü \`Resize\` metodunu kullanarak yeniden boyutlandırın; bu, görüntülerinizin boyutlarını gereksinimlerinize göre ayarlamanın basit ve etkili bir yolunu sunar. Bu çok yönlü işlevsellik, görüntüleri istediğiniz boyuta kolayca ölçeklemenizi sağlar ve çeşitli platform ve uygulamalarda kullanılabilirliğini artırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| newHeight | int | Yeni yükseklik. |
| resizeType | int | Yeniden boyutlandırma türü. |


**Example: This example loads a DJVU image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat büyüt.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Varsayılan seçeneklerle PNG olarak kaydet.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat küçült.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Varsayılan seçeneklerle PNG olarak kaydet.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat büyüt.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Varsayılan seçeneklerle PNG olarak kaydet.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat küçült.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Varsayılan seçeneklerle PNG olarak kaydet.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


\`ResizeWidthProportionally\` metodu, görüntünüzün genişliğini en boy oranını koruyarak ayarlamak için kullanışlı bir çözüm sunar. Genişliği orantılı olarak yeniden boyutlandırarak, görüntülerinizin farklı cihaz ve ekran boyutlarında görsel olarak çekici ve tutarlı kalmasını sağlayabilir, çeşitli bağlamlarda çok yönlülük ve kullanılabilirliğini artırabilirsiniz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| resizeType | int | Yeniden boyutlandırma türü. |


**Example: This example loads a DJVU image and resizes it proportionally using various resizing methods.**
Bu örnek, bir DJVU görüntüsü yükler ve çeşitli yeniden boyutlandırma yöntemlerini kullanarak orantılı bir şekilde yeniden boyutlandırır. Yalnızca genişlik belirtilir, yükseklik otomatik olarak hesaplanır.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat büyüt.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Varsayılan seçeneklerle PNG olarak kaydedin.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat küçült.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Varsayılan seçeneklerle PNG olarak kaydedin.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat büyüt.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Varsayılan seçeneklerle PNG olarak kaydedin.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
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


\`ResizeHeightProportionally\` metodu, görüntünüzün yüksekliğini en boy oranını koruyarak ayarlamanıza olanak tanır. Bu, görüntünüzün oranlarını korumasını, bozulmayı önlemesini ve görsel bütünlüğünü sürdürmesini sağlar. Görüntüleri web sayfaları, mobil uygulamalar veya basılı medya için optimize ediyor olsanız da, bu metod görüntülerinizin farklı platform ve cihazlarda en iyi şekilde görünmesini temin eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newHeight | int | Yeni yükseklik. |
| resizeType | int | Yeniden boyutlandırma türü. |


**Example: This example loads a DJVU image and resizes it proportionally using various resizing methods.**
Bu örnek, bir DJVU görüntüsü yükler ve çeşitli yeniden boyutlandırma yöntemlerini kullanarak orantılı bir şekilde yeniden boyutlandırır. Yalnızca yükseklik belirtilir, genişlik otomatik olarak hesaplanır.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat büyüt.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Varsayılan seçeneklerle PNG olarak kaydedin.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat küçült.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Varsayılan seçeneklerle PNG olarak kaydedin.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat büyüt.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Varsayılan seçeneklerle PNG olarak kaydedin.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
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


\`RotateFlip\` metodu, görüntünüz için çok yönlü manipülasyon seçenekleri sunar; aktif çerçeve üzerinde bağımsız olarak döndürme, çevirme veya her iki işlemi aynı anda yapmanıza olanak tanır. Fotoğraf düzenliyor, grafik oluşturuyor veya dijital sanatı geliştiriyor olsanız da, bu metod görüntülerinizin yönü ve kompozisyonu üzerinde hassas kontrol sağlar ve yaratıcı vizyonunuza kolay ve verimli bir şekilde ulaşmanızı temin eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rotateFlipType | int | Döndürme çevirme türü. |


**Example: This example loads a DJVU image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java
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
    com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + rotateFlipType + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


\"Dither\" işlevi, görüntünüze bir titreme efekti uygular; bant oluşumunu azaltarak ve renk geçişlerini iyileştirerek görsel kalitesini artırır. Dijital sanat, fotoğrafçılık veya grafik tasarım projeleri üzerinde çalışıyor olsanız da, bu özellik görüntülerinize profesyonel bir dokunuş katar, daha pürüzsüz ve rafine görünmelerini sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ditheringMethod | int | Dithering yöntemi. |
| bitsCount | int | Dithering için son bit sayısı. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Dithering için özel palet. |


**Example: The following example loads a DJVU image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage dicomImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // 16 renk içeren 4-bit renk paleti kullanarak eşik dithering uygulayın.
    // Daha fazla bit belirtildiğinde çıktı görüntüsünün kalitesi daha yüksek ve boyutu daha büyük olur.
    // Şu anda yalnızca 1-bit, 4-bit ve 8-bit paletlerin desteklendiğini unutmayın.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    dicomImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage dicomImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Sadece 2 renk (siyah ve beyaz) içeren 1-bit renk paleti kullanarak Floyd dithering uygulayın.
    // Daha fazla bit belirtildiğinde çıktı görüntüsünün kalitesi daha yüksek ve boyutu daha büyük olur.
    // Şu anda yalnızca 1-bit, 4-bit ve 8-bit paletlerin desteklendiğini unutmayın.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    dicomImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


\"Crop\" görüntünüzü belirli detaylara odaklanmak veya istenmeyen öğeleri kaldırmak için kırpar; kompozisyonunu ve görsel etkisini artırır. Sosyal medya için fotoğrafları ayarlıyor, web sitesi bannerları oluşturuyor veya basılı materyaller tasarlıyor olsanız da, bu araç görüntülerinizi hassas ve net bir şekilde iyileştirmenize yardımcı olur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Dikdörtgen. |


**Example: The following example crops a DJVU image.**
Aşağıdaki örnek bir DJVU görüntüsünü kırpar. Kırpma alanı Aspose.Imaging.Rectangle aracılığıyla belirtilir.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Görüntüyü kırp. Kırpma alanı, görüntünün dikdörtgen merkezi alanıdır.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(
            djvuImage.getWidth() / 4, djvuImage.getHeight() / 4, djvuImage.getWidth() / 2, djvuImage.getHeight() / 2);
    djvuImage.crop(area);

    // Kırpılmış görüntüyü PNG olarak kaydet.
    djvuImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Kaydırmalı kırpma, görüntü içindeki kırpılan alanın konumunu ve boyutlarını hassas bir şekilde ayarlamanızı sağlar. Bu özellik, kompozisyonları iyileştirmek, öğeleri hizalamak ve görsellerinizde odak noktalarını vurgulamak için son derece değerlidir. Kaydırmaların kırpma sürecine dahil edilmesiyle, pikselle mükemmel bir hassasiyet elde edebilir ve görüntülerinizin çerçevelendirmesini kolayca ince ayar yapabilirsiniz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| leftShift | int | Sol kaydırma. |
| rightShift | int | Sağ kaydırma. |
| topShift | int | Üst kaydırma. |
| bottomShift | int | Alt kaydırma. |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Önceden tanımlı bir eşik ile ikileştirme, karmaşık görüntüleri ikili temsillere basitleştirir; pikseller, belirli bir eşik değerine göre yoğunlukları temel alınarak siyah ya da beyaz olarak sınıflandırılır. Bu teknik, görüntü işleme alanında netliği artırmak, analizi basitleştirmek ve optik karakter tanıma (OCR) gibi sonraki işleme adımları için görüntüleri hazırlamak amacıyla yaygın olarak kullanılır. Sabit bir eşik uygulayarak, gri tonlamalı görüntüleri hızlıca ikili forma dönüştürebilir ve bunların yorumlanmasını ve anlamlı bilgi çıkarılmasını kolaylaştırabilirsiniz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threshold | byte | Eşik değeri. Bir pikselin ilgili gri değeri eşiğin üzerindeyse, ona 255 değeri atanır, aksi takdirde 0 atanır. |


**Example: The following example binarizes a DJVU image with the predefined threshold.**
Aşağıdaki örnek, önceden tanımlı eşik ile bir DJVU görüntüsünü ikileştirir. İkileştirilmiş görüntüler yalnızca 2 renk içerir - siyah ve beyaz.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

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


Otsu eşikleme kullanarak ikileştirme, görüntünün histogramına dayanarak otomatik olarak optimal bir eşik değeri hesaplayan bir tekniktir. Sınıf içi varyansı minimize ederek görüntüyü ön plan ve arka plan olarak ayırır. Otsu yöntemi, özellikle piksel yoğunluk dağılımı ikili ya da çoklu modlu olduğunda, görüntüleri ikili forma bölmek için yaygın olarak kullanılır. Bu yaklaşım, nesne tespiti, görüntü segmentasyonu ve özellik çıkarımı gibi, ön plan ile arka plan arasındaki doğru ayrımın kritik olduğu görevler için faydalıdır.


**Example: The following example binarizes a DJVU image with Otsu thresholding.**
Aşağıdaki örnek, Otsu eşikleme ile bir DJVU görüntüsünü ikileştirir. İkileştirilmiş görüntüler yalnızca 2 renk içerir - siyah ve beyaz.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Görüntüyü Otsu eşikleme ile ikilileştirin.
    djvuImage.binarizeOtsu();
    djvuImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Bradley'nin adaptif eşikleme algoritması ve integral görüntü eşikleme kullanarak ikileştirme, her piksel için yerel bir komşuluk temelinde yerel bir eşik hesaplayan bir yöntemdir. Görüntü üzerindeki aydınlatma değişikliklerine uyum sağlar; bu da düzensiz ışık koşullarına sahip görüntüler için uygundur. Eşiği integral görüntülerle hesaplayarak büyük komşulukları verimli bir şekilde işler ve gerçek zamanlı uygulamalara uygundur. Bu teknik, belge işleme, OCR (Optik Karakter Tanıma) ve görüntü segmentasyonu görevlerinde, sonraki analiz için doğru ikileştirmenin kritik olduğu durumlarda yaygın olarak kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brightnessDifference | double | Bu pikselin etrafında merkezlenmiş s x s piksellik bir pencerenin ortalaması ile piksel arasındaki parlaklık farkı. |
| windowSize | int | Bu pikselin etrafında merkezlenmiş s x s piksellik pencerenin boyutu |


**Example: The following example binarizes a DJVU image with Bradley's adaptive thresholding algorithm with the specified window size.**
Aşağıdaki örnek, belirtilen pencere boyutu ile Bradley'nin adaptif eşikleme algoritmasını kullanarak bir DJVU görüntüsünü ikileştirir. İkileştirilmiş görüntüler yalnızca 2 renk içerir - siyah ve beyaz.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Görüntüyü 5 parlaklık farkı ile ikili hale getirin. Parlaklık, bir piksel ile bu pikselin etrafındaki 10 x 10 pencere ortalaması arasındaki farktır.
    djvuImage.binarizeBradley(5, 10);
    djvuImage.save(dir + "sample.BinarizeBradley5_10x10.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


Gri tonlama dönüşümü, bir görüntüyü siyah-beyaz temsile çevirir; her pikselin yoğunluğu siyah ile beyaz arasında tek bir değerle temsil edilir. Bu süreç renk bilgisini kaldırarak tek renkli bir görüntü oluşturur. Gri tonlamalı görüntüler, rengin gereksiz olduğu veya sadeliğin tercih edildiği uygulamalarda yaygın olarak kullanılır; örneğin belge tarama, baskı ve belirli görüntü analiz türleri.


**Example: The following example transforms a colored DJVU image to its grayscale representation.**
Aşağıdaki örnek, renkli bir DJVU görüntüsünü gri tonlamalı temsiline dönüştürür. Gri tonlamalı görüntüler yalnızca gri tonlardan oluşur ve sadece yoğunluk bilgisi taşır.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    djvuImage.grayscale();
    djvuImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Gamma düzeltmesi, özellikle kırmızı, yeşil ve mavi kanallar için, her renk bileşeninin parlaklığını ayrı ayrı ayarlamayı içerir. RGB kanallarına farklı gamma katsayıları uygulayarak, bir görüntünün genel parlaklığını ve kontrastını ince ayar yapabilirsiniz. Bu teknik, doğru renk temsili sağlar ve görüntünün farklı gösterim cihazları üzerindeki görsel kalitesini artırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| gamma | float | Kırmızı, yeşil ve mavi kanallar için gamma katsayısı |


**Example: The following example performs gamma-correction of a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Kırmızı, yeşil ve mavi kanallar için gamma katsayısını ayarlayın.
    djvuImage.adjustGamma(2.5f);
    djvuImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Gamma düzeltmesi, kırmızı, yeşil ve mavi kanallar için özelleştirilebilir parametrelerle bir görüntüye uygulanır; bu, renk dengesi ve parlaklığın hassas ayarlanmasını sağlar. Bu metod, renk temsiliyi ince ayarlayarak görüntü kalitesini artırır ve farklı gösterim cihazları üzerinde optimal render almayı temin eder. Tek tek kanallar için gamma değerlerini ayarlamak, renk dengesini ve görsel çekiciliği iyileştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| gammaRed | float | Kırmızı kanal katsayısı için gama |
| gammaGreen | float | Yeşil kanal katsayısı için gama |
| gammaBlue | float | Mavi kanal katsayısı için gamma |


**Example: The following example performs gamma-correction of a DJVU image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Kırmızı, yeşil ve mavi kanallar için ayrı ayrı gamma katsayılarını ayarlayın.
    djvuImage.adjustGamma(1.5f, 2.5f, 3.5f);
    djvuImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Belirtilen bir parametre kullanarak bir görüntünün `brightness` (parlaklık) değerini ayarlayın; bu, optimal görsel netlik için aydınlık seviyeleri üzerinde kontrol sağlar. Bu metod, görüntünün genel parlaklığını artırır veya azaltır ve istenen ışık etkilerini elde etmek için ince ayarlamalara izin verir. Parlaklığı modüle ederek, kullanıcılar görüntü görünürlüğünü optimize edebilir ve detay üretimini iyileştirerek daha iyi bir izleme deneyimi sağlayabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brightness | int | Parlaklık değeri. |


**Example: The following example performs brightness correction of a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Parlaklık değerini ayarlayın. Kabul edilen parlaklık değerleri [-255, 255] aralığındadır.
    djvuImage.adjustBrightness(50);
    djvuImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


[Image](../../com.aspose.imaging/image) kontrastını artırarak görsel netliği iyileştirin ve detayları vurgulayın; bu metod, aydınlık ve karanlık alanlar arasındaki parlaklık farkını ayarlar. Kontrast seviyelerini ince ayarlayarak, kullanıcılar daha canlı ve etkileyici görüntüler elde eder, genel görüntü kalitesini artırır ve detay görünürlüğünü maksimize eder. Bu ayar, renk ve doku üzerindeki ince nüansları ortaya çıkararak daha dinamik ve görsel açıdan çekici görüntüler sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| contrast | float | Kontrast değeri ([-100; 100] aralığında) |


**Example: The following example performs contrast correction of a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Kontrast değerini ayarlayın. Kabul edilen kontrast değerleri [-100f, 100f] aralığındadır.
    djvuImage.adjustContrast(50f);
    djvuImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Görüntü içinde belirtilen dikdörtgen bir alana filtreler uygulayarak görünümünü iyileştirin veya değiştirin. Belirli bölgeleri hedef alarak, bu metod bulanıklaştırma, keskinleştirme veya sanatsal efektler uygulama gibi hassas ayarlamalara olanak tanır ve istenen görsel sonuçları elde etmenizi sağlar. Seçili alanlarda filtreleri ince ayarlamak, kullanıcıların görüntü estetiğini özelleştirmesini, netliği artırmasını ve tercihlerine göre sanatsal efektler yaratmasını sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Dikdörtgen. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Seçenekler. |


**Example: The following example applies various types of filters to a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Tüm görüntüye, dikdörtgen boyutu 5 olan bir medyan filtresi uygula.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    djvuImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Tüm görüntüye, çekirdek boyutu 5 olan çift taraflı yumuşatma filtresi uygula.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    djvuImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Tüm görüntüye, yarıçapı 5 ve sigma değeri 4.0 olan bir Gaussian bulanıklaştırma filtresi uygula.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    djvuImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Tüm görüntüye, yarıçapı 5 ve pürüzsüzlük değeri 4.0 olan bir Gauss-Wiener filtresi uygula.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    djvuImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Tüm görüntüye, uzunluğu 5, pürüzsüzlük değeri 4.0 ve açısı 90.0 derece olan bir hareket Wiener filtresi uygula.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    djvuImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Tüm görüntüye, çekirdek boyutu 5 ve sigma değeri 4.0 olan bir keskinleştirme filtresi uygula.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    djvuImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Gerekli olduğunda ek ayarları uygulayarak görüntüyü belirtilen genişlik ve yüksekliğe yeniden boyutlandırın. Bu yöntem, kullanıcıların görüntünün boyutlarını, en‑boy oranı, görüntü kalitesi ve sıkıştırma ayarları gibi istenen özellikleri koruyarak ayarlamasını sağlar. Yeniden boyutlandırma seçeneklerinde esneklik sunarak, kullanıcılar görüntüyü belirli gereksinimlere uyacak şekilde özelleştirebilir ve çeşitli uygulama ve platformlar için görünümünü optimize edebilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| newHeight | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Yeniden boyutlandırma ayarları. |


**Example: This example loads a DJVU image and resizes it using various resizing settings.**

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

com.aspose.imaging.Image image = (com.aspose.imaging.Image) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Uyarlanabilir yeniden örnekleme kullanarak 2 kat küçült.
    djvuImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // PNG'ye kaydet
    djvuImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### cacheData() {#cacheData--}
```
public void cacheData()
```


Performansı optimize etmek ve dış kaynaklardan tekrarlanan veri alımına olan ihtiyacı azaltmak için verileri özel olarak önbelleğe alın. Bu yaklaşım ayrıca, veri erişiminin sık olduğu veya kaynakların sınırlı olduğu senaryolarda kaynakların korunmasına da yardımcı olur.


**Example: The following example shows how to cache all pages of a DJVU image.**

``` java
String dir = "c:\\temp\\";

// Bir DJVU dosyasından görüntü yükleyin.
com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Bu çağrı, tüm sayfaları önbelleğe alır, böylece temel veri akışından ek veri yüklemesi yapılmaz.
    image.cacheData();

    // Veya sayfaları tek tek önbelleğe alabilirsiniz.
    for (com.aspose.imaging.fileformats.djvu.DjvuPage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

