---
title: "CmxImage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Corel Metafile Exchange CMX vektör görüntü formatı için meta veri açıklamaları desteği sağlayan API, CMX dosyalarıyla çalışan geliştiriciler için kapsamlı bir çözümdür."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.fileformats.cmx/cmximage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.ICmxImage](../../com.aspose.imaging.fileformats.cmx/icmximage)
```
public class CmxImage extends VectorMultipageImage implements ICmxImage
```

Corel Metafile Exchange (CMX) vektör görüntü formatı için meta veri açıklamaları desteği sağlayan API, CMX dosyalarıyla çalışan geliştiriciler için kapsamlı bir çözümdür. Bu API, CMX görüntülerinin sorunsuz bir şekilde yüklenmesini, piksel başına bit, nesne boyutları gibi meta verilerin çıkarılmasını ve daha fazlasını sağlar. Yeniden boyutlandırma, döndürme, palet ayarlama ve diğer formatlara dönüştürme gibi ek işlevselliklerle, bu API geliştiricilerin CMX vektör görüntülerini belirli uygulama gereksinimlerine uygun şekilde verimli bir şekilde manipüle etmelerini ve özelleştirmelerini sağlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CmxImage(StreamContainer streamContainer, LoadOptions loadOptions)](#CmxImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Yeni bir örnek oluşturup streamContainer ve loadOptions parametreleriyle başlatarak [CmxImage](../../com.aspose.imaging.fileformats.cmx/cmximage) sınıfı ile sorunsuz bir şekilde çalışmaya başlayın. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Bu kullanıcı dostu özellik sayesinde görüntünün dosya formatını zahmetsizce alın. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Bu kullanıcı dostu özellik sayesinde görüntünün bit derinliğini zahmetsizce alın. |
| [getDefaultPage()](#getDefaultPage--) | Bu sezgisel özellik sayesinde görüntünün varsayılan sayfasını zahmetsizce alın. |
| [isCached()](#isCached--) | Nesnenin verisinin şu anda önbellekte olup olmadığını belirleyin, veri okuma ihtiyacını ortadan kaldırın. |
| [getWidthF()](#getWidthF--) | Bu sezgisel özellik sayesinde nesnenin genişliğini inç cinsinden alın. |
| [getHeightF()](#getHeightF--) | Bu kullanıcı dostu özellik sayesinde nesnenin yüksekliğini, inç olarak ölçülmüş şekilde, zahmetsizce elde edin. |
| [getDocument()](#getDocument--) | Bu sezgisel özellik sayesinde CMX belgesini zahmetsizce alın. |
| [getCmxPage()](#getCmxPage--) | Bu sezgisel özellik sayesinde görüntünün CMX sayfasını zahmetsizce alın. |
| [getPageCount()](#getPageCount--) | Bu sezgisel özellik sayesinde görüntünün toplam sayfa sayısını alın. |
| [getPages()](#getPages--) | Bu sezgisel özellik sayesinde görüntünün sayfalarını sorunsuz bir şekilde alın. |
| [cacheData()](#cacheData--) | Bu kullanışlı yöntemle verileri önbelleğe alarak temel kaynaktan [DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter) ek yüklemeyi önleyin. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Bu sezgisel yöntemle görüntünün renk paletini özelleştirin. |

## Example: The following example shows how to cache all pages of a CMX image.

``` java
String dir = "c:\\temp\\";

// Bir CMX dosyasından görüntü yükle.
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // Bu çağrı yalnızca varsayılan sayfayı önbelleğe alır.
    image.cacheData();

    // Tüm sayfaları önbelleğe al, böylece temel veri akışından ek veri yüklemesi yapılmaz.
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### CmxImage(StreamContainer streamContainer, LoadOptions loadOptions) {#CmxImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public CmxImage(StreamContainer streamContainer, LoadOptions loadOptions)
```


Yeni bir örnek oluşturup streamContainer ve loadOptions parametreleriyle başlatarak [CmxImage](../../com.aspose.imaging.fileformats.cmx/cmximage) sınıfı ile sorunsuz bir şekilde çalışmaya başlayın. Çeşitli veri kaynaklarından CMX görüntülerini yüklemek ve yükleme sürecini gerektiği gibi özelleştirmek isteyen geliştiriciler için idealdir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Akış konteyneri. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Yükleme seçenekleri. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Bu kullanıcı dostu özellik sayesinde görüntünün dosya formatını zahmetsizce alın. Görüntülerinin formatını dinamik olarak belirlemek, uyumluluğu ve uygulamalarında doğru işleme sağlamak isteyen geliştiriciler için idealdir.

**Returns:**
long - Dosya formatı [FileFormat.Cmx](../../com.aspose.imaging/fileformat\#Cmx)
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Bu kullanıcı dostu özellik sayesinde görüntünün bit derinliğini zahmetsizce alın. Görüntülerindeki detay seviyesini veya renk derinliğini belirlemek, doğru işleme ve manipülasyon sağlamak isteyen geliştiriciler için idealdir.

**Returns:**
int - Görüntünün piksel başına bit sayısı.
### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


Bu sezgisel özellik sayesinde görüntünün varsayılan sayfasını zahmetsizce alın. Görüntülerinin birincil sayfasına hızlı erişim sağlamak, verimli gezinme ve yönetim isteyen geliştiriciler için idealdir.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### isCached() {#isCached--}
```
public boolean isCached()
```


Nesnenin verisinin şu anda önbellekte olup olmadığını belirleyin, veri okuma ihtiyacını ortadan kaldırın. Önbellekteki verileri verimli bir şekilde kullanarak performansı optimize etmek ve nesne bilgilerine daha hızlı erişim sağlamak isteyen geliştiriciler için idealdir.

**Returns:**
boolean - nesnenin verisi önbellekteyse `true`; aksi takdirde `false`.
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Bu sezgisel özellik sayesinde nesnenin genişliğini inç cinsinden alın. Uygulamalarında nesnelerin hassas ölçümlerini elde etmek, doğru düzen ve sunum sağlamak isteyen geliştiriciler için idealdir.

**Returns:**
float - Nesnenin genişliği, inç cinsinden.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Bu kullanıcı dostu özellik sayesinde nesnenin yüksekliğini, inç olarak ölçülmüş şekilde, zahmetsizce elde edin. Uygulamalarında etkili düzen ve sunum için hassas boyutsal bilgi arayan geliştiriciler için idealdir.

**Returns:**
float - Nesnenin yüksekliği, inç cinsinden.
### getDocument() {#getDocument--}
```
public final CmxDocument getDocument()
```


Bu sezgisel özellik sayesinde CMX belgesini zahmetsizce alın. CMX görüntülerine erişmek veya bunları değiştirmek, uygulamalarında esneklik ve verimlilik sağlamak isteyen geliştiriciler için idealdir.

**Returns:**
[CmxDocument](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxdocument) - The CMX document.
### getCmxPage() {#getCmxPage--}
```
public final CmxPage getCmxPage()
```


Bu sezgisel özellik sayesinde görüntünün CMX sayfasını zahmetsizce alın. CMX görüntülerindeki bireysel sayfalara hızlı erişim sağlamak, verimli gezinme ve yönetim isteyen geliştiriciler için idealdir.

**Returns:**
[CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) - The CMX page.
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Bu sezgisel özellik ile görüntünün toplam sayfa sayısını alın. Çok sayfalı görüntüleri dinamik olarak yönetmek isteyen geliştiriciler için idealdir, görüntü içeriğinin verimli gezinmesini ve manipülasyonunu sağlar.

**Returns:**
int - sayfa sayısı.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Bu sezgisel özellik ile görüntünün sayfalarını sorunsuz bir şekilde alın. Çok sayfalı görüntülerde bireysel sayfalara erişmek ve bunları manipüle etmek isteyen geliştiriciler için idealdir, verimli gezinme ve işleme sağlar.

**Returns:**
com.aspose.imaging.Image[] - sayfalar.

**Example: The following example shows how to cache all pages of a CMX image.**

``` java
String dir = "c:\\temp\\";

// Bir CMX dosyasından görüntü yükle.
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // Bu çağrı yalnızca varsayılan sayfayı önbelleğe alır.
    image.cacheData();

    // Tüm sayfaları önbelleğe al, böylece temel veri akışından ek veri yüklemesi yapılmaz.
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### cacheData() {#cacheData--}
```
public void cacheData()
```


Bu kullanışlı yöntemle verileri önbelleğe alarak temel kaynaktan ek yüklemeyi önleyin [DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter). Verileri önceden yükleyerek performansı optimize etmeyi hedefleyen geliştiriciler için idealdir, uygulamalarında daha hızlı erişim ve daha sorunsuz çalışma sağlar.


**Example: The following example shows how to cache all pages of a CMX image.**

``` java
String dir = "c:\\temp\\";

// Bir CMX dosyasından görüntü yükle.
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // Bu çağrı yalnızca varsayılan sayfayı önbelleğe alır.
    image.cacheData();

    // Tüm sayfaları önbelleğe al, böylece temel veri akışından ek veri yüklemesi yapılmaz.
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
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

