---
title: "CdrImage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "CorelDRAW CDR vektör görüntü formatı desteği için API, vektör grafikleriyle çalışan geliştiriciler için vazgeçilmez bir araç setidir."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.fileformats.cdr/cdrimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cdr.ICdrImage](../../com.aspose.imaging.fileformats.cdr/icdrimage)
```
public class CdrImage extends VectorMultipageImage implements ICdrImage
```

CorelDRAW CDR vektör görüntü formatı desteği için API, vektör grafikleriyle çalışan geliştiriciler için temel bir araç setidir. Bu API, CDR dosyalarının sorunsuz işlenmesini sağlar ve metin, çizgiler, şekiller, görüntüler, renkler ve efektler gibi çeşitli öğelerin depolanmasına ve manipüle edilmesine olanak tanır. Kapsamlı yetenekleri sayesinde, geliştiriciler görüntü içeriklerinin vektör temsilleriyle verimli bir şekilde çalışabilir, CorelDRAW vektör grafiklerini programlı olarak oluşturma ve düzenlemede hassasiyet ve esneklik sağlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CdrImage(InputStream stream, LoadOptions loadOptions)](#CdrImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Yeni bir akış ve loadOptions parametreleriyle bir örnek başlatarak [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) sınıfı ile sorunsuz bir şekilde çalışmaya başlayın. |
| [CdrImage(System.IO.Stream stream, LoadOptions loadOptions)](#CdrImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-) | Yeni bir akış ve loadOptions parametreleriyle bir örnek başlatarak [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) sınıfı ile sorunsuz bir şekilde çalışmaya başlayın. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDefaultPage()](#getDefaultPage--) | Bu kullanıcı dostu özelliği kullanarak görüntünün varsayılan sayfasını kolayca alın. |
| [isCached()](#isCached--) | Veri okuma ihtiyacını ortadan kaldırarak, nesnenin verisinin şu anda önbellekte olup olmadığını sorunsuz bir şekilde belirleyin. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Bu kullanıcı dostu özellik sayesinde görüntünün bit derinliğini zahmetsizce alın. |
| [getPageCount()](#getPageCount--) | Bu sezgisel özellik sayesinde görüntünün toplam sayfa sayısını sorunsuz bir şekilde alabilir veya güncelleyebilirsiniz. |
| [getPages()](#getPages--) | Bu sezgisel özellik sayesinde görüntünün sayfalarını sorunsuz bir şekilde alın. |
| [getCdrDocument()](#getCdrDocument--) | Bu sezgisel özelliği kullanarak CDR belgesini sorunsuz bir şekilde alabilir veya güncelleyebilirsiniz. |
| [getFileFormat()](#getFileFormat--) | Bu sezgisel özellik ile görüntünün dosya formatını sorunsuz bir şekilde alın. |
| [getWidth()](#getWidth--) | Görüntünün genişliğini alır. |
| [getHeight()](#getHeight--) | Görüntünün yüksekliğini alır. |
| [cacheData()](#cacheData--) | Bu kullanıcı dostu yöntemle veriyi önbelleğe alarak temel kaynaktan ek yüklemeyi önleyin. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Bu sezgisel yöntemle görüntünün renk paletini özelleştirin. |

## Example: The following example shows how to cache all pages of a CDR image.

``` java
String dir = "c:\\temp\\";

// Bir CDR dosyasından görüntü yükleyin.
com.aspose.imaging.fileformats.cdr.CdrImage image = (com.aspose.imaging.fileformats.cdr.CdrImage) com.aspose.imaging.Image.load(dir + "sample.cdr");
try {
    // Bu çağrı yalnızca varsayılan sayfayı önbelleğe alır.
    image.cacheData();

    // Tüm sayfaları önbelleğe al, böylece temel veri akışından ek veri yüklemesi yapılmaz.
    for (com.aspose.imaging.fileformats.cdr.CdrImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### CdrImage(InputStream stream, LoadOptions loadOptions) {#CdrImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public CdrImage(InputStream stream, LoadOptions loadOptions)
```


Yeni bir akış ve loadOptions parametreleriyle bir örnek başlatarak [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) sınıfı ile sorunsuz bir şekilde çalışmaya başlayın. Çeşitli veri kaynaklarından CDR görüntülerini yüklemek için uygun bir yol arayan ve gerektiğinde yükleme sürecini özelleştirmek isteyen geliştiriciler için idealdir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Akış. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Yükleme seçenekleri. |

### CdrImage(System.IO.Stream stream, LoadOptions loadOptions) {#CdrImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-}
```
public CdrImage(System.IO.Stream stream, LoadOptions loadOptions)
```


Yeni bir akış ve loadOptions parametreleriyle bir örnek başlatarak [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) sınıfı ile sorunsuz bir şekilde çalışmaya başlayın. Çeşitli veri kaynaklarından CDR görüntülerini yüklemek için uygun bir yol arayan ve gerektiğinde yükleme sürecini özelleştirmek isteyen geliştiriciler için idealdir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | com.aspose.ms.System.IO.Stream | Akış. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Yükleme seçenekleri. |

### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


Bu kullanıcı dostu özelliği kullanarak görüntünün varsayılan sayfasını kolayca alın. Görüntülerinin birincil sayfasına hızlı erişim arayan ve etkili gezinme ve yönetim sağlayan geliştiriciler için mükemmeldir.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### isCached() {#isCached--}
```
public boolean isCached()
```


Veri okuma ihtiyacını ortadan kaldırarak, nesnenin verisinin şu anda önbellekte olup olmadığını sorunsuz bir şekilde belirleyin. Önbelleğe alınan veriyi verimli bir şekilde kullanarak performansı optimize etmeyi hedefleyen ve nesne bilgilerine daha hızlı erişim sağlayan geliştiriciler için idealdir.

**Returns:**
boolean - nesnenin verisi önbellekteyse `true`; aksi takdirde `false`.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Bu kullanıcı dostu özellik sayesinde görüntünün bit derinliğini zahmetsizce alın. Görüntülerindeki detay seviyesini veya renk derinliğini belirlemek, doğru işleme ve manipülasyon sağlamak isteyen geliştiriciler için idealdir.

**Returns:**
int - Görüntünün piksel başına bit sayısı.
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Bu sezgisel özellik sayesinde görüntünün toplam sayfa sayısını sorunsuz bir şekilde alabilir veya güncelleyebilirsiniz. Çok sayfalı görüntüleri dinamik olarak yönetmek ve görüntü içeriğinin etkili gezinme ve manipülasyonunu sağlamak isteyen geliştiriciler için idealdir.

**Returns:**
int - sayfa sayısı.
### getPages() {#getPages--}
```
public final Image[] getPages()
```


Bu sezgisel özellik ile görüntünün sayfalarını sorunsuz bir şekilde alın. Çok sayfalı görüntülerde bireysel sayfalara erişmek ve bunları manipüle etmek isteyen geliştiriciler için idealdir, verimli gezinme ve işleme sağlar.

**Returns:**
com.aspose.imaging.Image[] - sayfalar.

**Example: The following example shows how to export a single page of CDR document to PDF.**

``` java
int pageNumber = 0;
String dir = "c:\\aspose.imaging\\java\\issues\\1445'\\";
String inputCdrFileName = dir + "tiger.cdr";
String outputPdfFileName = dir + "tiger.cdr.page" + pageNumber + ".pdf";

com.aspose.imaging.fileformats.cdr.CdrImage image = (com.aspose.imaging.fileformats.cdr.CdrImage) com.aspose.imaging.Image.load(inputCdrFileName);
try {
    com.aspose.imaging.Image imagePage = image.getPages()[pageNumber];

    com.aspose.imaging.imageoptions.PdfOptions pdfOptions = new com.aspose.imaging.imageoptions.PdfOptions();
    com.aspose.imaging.imageoptions.CdrRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.CdrRasterizationOptions();
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    rasterizationOptions.setPageWidth(image.getWidth());
    rasterizationOptions.setPageHeight(image.getHeight());

    pdfOptions.setVectorRasterizationOptions(rasterizationOptions);

    imagePage.save(outputPdfFileName, pdfOptions);
}
finally {
    image.close();
}
```

### getCdrDocument() {#getCdrDocument--}
```
public final CdrDocument getCdrDocument()
```


Bu sezgisel özelliği kullanarak CDR belgesini sorunsuz bir şekilde alabilir veya güncelleyebilirsiniz. CDR belgesine erişmek veya onu değiştirmek isteyen ve uygulamalarında esneklik ve verimlilik sağlayan geliştiriciler için idealdir.

**Returns:**
[CdrDocument](../../com.aspose.imaging.fileformats.cdr.objects/cdrdocument) - the CDR document.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Bu sezgisel özellik ile görüntünün dosya formatını sorunsuz bir şekilde alın. Görüntülerinin formatını dinamik olarak belirlemek ve uygulamalarında uyumluluk ve doğru işleme sağlamak isteyen geliştiriciler için idealdir.

**Returns:**
long
### getWidth() {#getWidth--}
```
public int getWidth()
```


Görüntünün genişliğini alır.

Değer: Görüntünün genişliği.

**Returns:**
int - görüntünün genişliği.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Görüntünün yüksekliğini alır.

Değer: Görüntünün yüksekliği.

**Returns:**
int - görüntünün yüksekliği.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Bu kullanıcı dostu yöntemle veriyi önbelleğe alarak temel kaynaktan ek yüklemeyi önleyin. Veriyi önceden yükleyerek performansı optimize etmeyi hedefleyen ve uygulamalarında daha hızlı erişim ve sorunsuz çalışma sağlayan geliştiriciler için idealdir. `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)/[DataStreamSupporter.setDataStreamContainer\_internalized(StreamContainer)](../../com.aspose.imaging/datastreamsupporter\#setDataStreamContainer-internalized-StreamContainer-)).


**Example: The following example shows how to cache all pages of a CDR image.**

``` java
String dir = "c:\\temp\\";

// Bir CDR dosyasından görüntü yükleyin.
com.aspose.imaging.fileformats.cdr.CdrImage image = (com.aspose.imaging.fileformats.cdr.CdrImage) com.aspose.imaging.Image.load(dir + "sample.cdr");
try {
    // Bu çağrı yalnızca varsayılan sayfayı önbelleğe alır.
    image.cacheData();

    // Tüm sayfaları önbelleğe al, böylece temel veri akışından ek veri yüklemesi yapılmaz.
    for (com.aspose.imaging.fileformats.cdr.CdrImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Bu sezgisel yöntemle görüntünün renk paletini özelleştirin. Belirli renk şemalarını veya ayarlamaları dinamik olarak uygulamak isteyen geliştiriciler için idealdir, görüntülerinin görsel görünümünü hassas bir şekilde kontrol etmeyi sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Ayarlanacak palet. |
| updateColors | boolean | `true` olarak ayarlanırsa renkler yeni palete göre güncellenecek; aksi takdirde renk indeksleri değişmeden kalır. Değişmeyen indekslerin, bazı indekslerin karşılık gelen palet girdileri olmaması durumunda görüntünün yüklenirken çökmesine neden olabileceğini unutmayın. |

