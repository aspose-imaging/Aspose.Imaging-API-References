---
title: "ApngImage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Animasyonlu PNG (Animated Portable Network Graphics) görüntü dosyası formatı için API, uygulamalarına animasyonlu içerik entegre etmek isteyen geliştiriciler için çok yönlü bir çözümdür."
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.fileformats.apng/apngimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext)
```
public final class ApngImage extends RasterCachedMultipageImage implements IMultipageImageExt
```

Animasyonlu PNG (Animated Portable Network Graphics) görüntü dosyası formatı için API, uygulamalarına animasyonlu içerik entegre etmek isteyen geliştiriciler için çok yönlü bir çözümdür. Bu API, çerçeve ayarları üzerinde kapsamlı kontrol sağlar ve kullanıcıların döngü süresi ve PNG dosya ayarları dahil olmak üzere çerçeveye özgü parametreleri tanımlamasına olanak tanır. Bu özellik bakımından zengin araç sayesinde APNG görüntülerinin görüntülenmesini zahmetsizce yönetebilir ve optimize edebilir, görüntüleri içe ve dışa aktarabilir, uygulamalarınızın dinamik ve etkileşimli yönlerini geliştirebilirsiniz.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ApngImage(ApngOptions options, int width, int height)](#ApngImage-com.aspose.imaging.imageoptions.ApngOptions-int-int-) | Yeni bir örnek başlatarak [ApngImage](../../com.aspose.imaging.fileformats.apng/apngimage) sınıfı ile çalışmaya zahmetsizce başlayın. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Bu kullanışlı özellik sayesinde dosya formatı hakkında bilgiye hızlıca erişin. |
| [getPageCount()](#getPageCount--) | Bu özellik ile görüntü dosyanızdaki toplam sayfa sayısını zahmetsizce alın. |
| [getPages()](#getPages--) | Bu kullanışlı özellik sayesinde görüntünüzün sayfalarına zahmetsizce erişin. |
| [getNumPlays()](#getNumPlays--) | Bu çok yönlü özellik sayesinde animasyonunuzun kaç kez döngü yapacağını zahmetsizce kontrol edin. |
| [setNumPlays(int value)](#setNumPlays-int-) | Bu çok yönlü özellik sayesinde animasyonunuzun kaç kez döngü yapacağını zahmetsizce kontrol edin. |
| [getDefaultFrameTime()](#getDefaultFrameTime--) | Bu esnek özellik ile yeni çerçeveler oluşturmak için varsayılan çerçeve süresini kolayca ayarlayın. |
| [setDefaultFrameTime(long value)](#setDefaultFrameTime-long-) | Bu esnek özellik ile yeni çerçeveler oluşturmak için varsayılan çerçeve süresini kolayca ayarlayın. |
| [getInterlaced()](#getInterlaced--) | Bu kullanışlı özellik sayesinde bu [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) nesnesinin taramalı olup olmadığını hızlıca belirleyin. |
| [getOriginalOptions()](#getOriginalOptions--) | Bu sezgisel yöntemle orijinal dosya ayarlarına dayalı seçenekleri zahmetsizce alın. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Bu basit yöntemle varsayılan seçenekleri zahmetsizce alın. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Bu kullanıcı dostu yöntemle kaynak görüntünün en son ne zaman değiştirildiğini tarih ve saat olarak hızlıca elde edin. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Bu sezgisel yöntemle görüntüye yeni bir sayfa ekleyin. |
| [addFrame()](#addFrame--) | /\*\* |
| [addFrame(RasterImage frameImage)](#addFrame-com.aspose.imaging.RasterImage-) | Bu sezgisel yöntemle yeni bir çerçeveyi sona ekleyerek çerçeve koleksiyonunuzu zahmetsizce genişletin. |
| [addFrame(RasterImage frameImage, long frameTime)](#addFrame-com.aspose.imaging.RasterImage-long-) | Bu sezgisel yöntemle yeni bir çerçeve ekleyerek çerçeve koleksiyonunuzu sorunsuz bir şekilde genişletin. |
| [insertFrame(int index)](#insertFrame-int-) | Bu sezgisel yöntemle belirtilen konuma yeni bir çerçeve ekleyerek çerçeve koleksiyonunuza zahmetsizce ekleyin. |
| [insertFrame(int index, RasterImage frameImage)](#insertFrame-int-com.aspose.imaging.RasterImage-) | Belirtilen indekste yeni çerçeveyi kendi çerçeve koleksiyonuna ekler. |
| [insertFrame(int index, RasterImage frameImage, long frameTime)](#insertFrame-int-com.aspose.imaging.RasterImage-long-) | Belirtilen indekste yeni çerçeveyi kendi çerçeve koleksiyonuna ekler. |
| [popFrameAt(int index)](#popFrameAt-int-) | Bu sezgisel yöntemle çerçeve koleksiyonunuzdan belirtilen indeksteki çerçeveyi kaldırın ve alın. |
| [removeFrameAt(int index)](#removeFrameAt-int-) | Bu yöntemle çerçeve koleksiyonunuzdan belirtilen indeksteki çerçeveyi sorunsuz bir şekilde kaldırın. |
| [removeAllFrames()](#removeAllFrames--) | Bu sezgisel yöntemle tüm çerçeveleri kaldırarak çerçeve koleksiyonunuzu temizleyin. |
| [setDefaultImage(RasterImage image)](#setDefaultImage-com.aspose.imaging.RasterImage-) | Bu yöntemle belirtilen raster görüntüyü mevcut animasyon için varsayılan görüntü olarak zahmetsizce ayarlayın. |
| [resetDefaultImage()](#resetDefaultImage--) | Bu sezgisel yöntemle daha önce ayarlanmış varsayılan görüntüyü kaldırın. |

## Example: The following example shows how to export to APNG file format.

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // APNG animasyonunu varsayılan olarak sınırsız animasyon döngüsüyle dışa aktar
    image.save("Animation1.webp.png", new ApngOptions());
    // Animasyon döngülerini ayarlama
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```


## Example: The following example shows how to export apng APNG file format from other non-animated multi-page format.

``` java
import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("img4.tif"))
{
    // Varsayılan kare süresini ayarlama
    ApngOptions options = new ApngOptions();
    options.setDefaultFrameTime(500);
    image.save("img4.tif.500ms.png", options); // 500 ms
    options.setDefaultFrameTime(250);
    image.save("img4.tif.250ms.png", options); // 250 ms
}
```

### ApngImage(ApngOptions options, int width, int height) {#ApngImage-com.aspose.imaging.imageoptions.ApngOptions-int-int-}
```
public ApngImage(ApngOptions options, int width, int height)
```


Yeni bir örnek başlatarak [ApngImage](../../com.aspose.imaging.fileformats.apng/apngimage) sınıfı ile çalışmaya başlayın. Projelerinde ApngImage nesnelerini hızlı ve verimli bir şekilde kullanmaya başlayan geliştiriciler için mükemmeldir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions) | Seçenekler. |
| genişlik | int | Genişlik. |
| yükseklik | int | Yükseklik. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Bu kullanışlı özellik sayesinde dosya formatı hakkında bilgileri hızlıca erişin. Apng dosyalarının format detaylarını kolayca almak isteyen geliştiriciler için idealdir.

**Returns:**
long
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Bu özellik ile görüntü dosyanızdaki toplam sayfa sayısını zahmetsizce alın. Sayfa sayısı bilgisine hızlı erişime ihtiyaç duyan geliştiriciler için idealdir.

Değer: Sayfa sayısı.

**Returns:**
int
### getPages() {#getPages--}
```
public Image[] getPages()
```


Bu kullanışlı özellik sayesinde görüntünüzün sayfalarına zahmetsizce erişin. Tek tek sayfaları manipüle etmek için hızlı ve kolay erişim arayan geliştiriciler için mükemmeldir.

Değer: Sayfalar.

**Returns:**
com.aspose.imaging.Image[]
### getNumPlays() {#getNumPlays--}
```
public int getNumPlays()
```


Bu çok yönlü özellik ile animasyonunuzun kaç kez döngüye gireceğini zahmetsizce kontrol edin. Değer 0 olduğunda sınırsız döngü desteğiyle animasyon davranışını hassas bir şekilde kontrol etmek isteyen geliştiriciler için mükemmeldir.

Değer: Döngü sayısı.

**Returns:**
int
### setNumPlays(int value) {#setNumPlays-int-}
```
public void setNumPlays(int value)
```


Bu çok yönlü özellik ile animasyonunuzun kaç kez döngüye gireceğini zahmetsizce kontrol edin. Değer 0 olduğunda sınırsız döngü desteğiyle animasyon davranışını hassas bir şekilde kontrol etmek isteyen geliştiriciler için mükemmeldir.

Değer: Döngü sayısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getDefaultFrameTime() {#getDefaultFrameTime--}
```
public long getDefaultFrameTime()
```


Bu esnek özellik sayesinde yeni çerçeveler oluşturmak için varsayılan çerçeve süresini kolayca ayarlayın. Animasyonlarında çerçeve zamanlamasını verimli bir şekilde özelleştirmek isteyen geliştiriciler için mükemmeldir.

Değer: Varsayılan çerçeve süresi, milisaniye cinsinden.

**Returns:**
long
### setDefaultFrameTime(long value) {#setDefaultFrameTime-long-}
```
public void setDefaultFrameTime(long value)
```


Bu esnek özellik sayesinde yeni çerçeveler oluşturmak için varsayılan çerçeve süresini kolayca ayarlayın. Animasyonlarında çerçeve zamanlamasını verimli bir şekilde özelleştirmek isteyen geliştiriciler için mükemmeldir.

Değer: Varsayılan çerçeve süresi, milisaniye cinsinden.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Bu kullanışlı özellik sayesinde bu [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) nesnesinin taramalı olup olmadığını hızlıca belirleyin. PNG görüntülerinin tarama durumunu kolayca kontrol etmesi gereken geliştiriciler için idealdir.

Değer: `true` ise taramalı; aksi takdirde `false`.

**Returns:**
boolean
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Bu sezgisel yöntemle orijinal dosya ayarlarına dayalı seçenekleri zahmetsizce alın. Orijinal dosyanın özellikleriyle uyumlu ayarları erişmek ve kullanmak isteyen geliştiriciler için mükemmeldir. Bu, orijinal görüntünün bit derinliği ve diğer parametrelerinin değişmeden kalmasını sağlamada yardımcı olabilir. Örneğin, 1 bit/piksel siyah-beyaz bir PNG görüntüsü yükleyip ardından [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-) yöntemiyle kaydederseniz, çıktı PNG görüntüsü 8 bit/piksel olarak üretilir. Bunu önlemek ve PNG görüntüsünü 1 bit/piksel olarak kaydetmek için, bu yöntemi kullanarak ilgili kaydetme seçeneklerini alın ve ikinci parametre olarak [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) yöntemine geçirin.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Bu basit yöntemle varsayılan seçenekleri zahmetsizce alın. Varsayılan Apng görüntü ayarlarına hızlı erişim isteyen geliştiriciler için idealdir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argümanlar | java.lang.Object[] | Argümanlar. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


Bu kullanıcı dostu yöntemle kaynak görüntünün en son ne zaman değiştirildiğini tarih ve saat olarak hızlıca elde edin. Değişiklikleri izlemek ve kaynakları etkili bir şekilde yönetmek isteyen geliştiriciler için idealdir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| useDefault | boolean | `true` olarak ayarlanırsa, FileInfo'dan gelen bilgileri varsayılan değer olarak kullanır. |

**Returns:**
java.util.Date - Kaynak görüntünün en son değiştirildiği tarih ve saat.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Bu sezgisel yöntemle görüntüye yeni bir sayfa ekleyin. Görüntü dosyalarının içeriğini dinamik olarak genişletmek isteyen geliştiriciler için mükemmeldir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | Eklenecek sayfa. |

### addFrame() {#addFrame--}
```
public ApngFrame addFrame()
```


/\*\*

Bu basit yöntemle çerçeve koleksiyonunuzun sonuna yeni bir çerçeve ekleyin. Çok çerçeveli görüntülerle animasyonlar için çerçeve koleksiyonunu dinamik olarak genişletmek isteyen geliştiriciler için idealdir. Yeni çerçeve, mevcut görüntünün boyutuna göre oluşturulacaktır.

**Returns:**
[ApngFrame](../../com.aspose.imaging.fileformats.apng/apngframe) - The newly created APNG frame.
### addFrame(RasterImage frameImage) {#addFrame-com.aspose.imaging.RasterImage-}
```
public void addFrame(RasterImage frameImage)
```


Bu sezgisel yöntemle çerçeve koleksiyonunuza sonuna yeni bir çerçeve ekleyerek zahmetsizce genişletin. Çok çerçeveli görüntü animasyonlarını dinamik olarak geliştirmek isteyen geliştiriciler için mükemmeldir. Yeni çerçevenin içeriği belirtilen görüntüden doldurulacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Çerçeve görüntüsü. |

### addFrame(RasterImage frameImage, long frameTime) {#addFrame-com.aspose.imaging.RasterImage-long-}
```
public void addFrame(RasterImage frameImage, long frameTime)
```


Bu sezgisel yöntemle yeni bir çerçeve ekleyerek çerçeve koleksiyonunuzu sorunsuz bir şekilde genişletin. Çok çerçeveli görüntü animasyonlarını zenginleştirmek isteyen geliştiriciler için idealdir. Yeni çerçevenin içeriği belirtilen görüntüden doldurulacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Çerçeve görüntüsü. |
| frameTime | long | Çerçeve süresi, milisaniye cinsinden. |

### insertFrame(int index) {#insertFrame-int-}
```
public ApngFrame insertFrame(int index)
```


Bu sezgisel yöntemle belirtilen konuma yeni bir çerçeve ekleyerek çerçeve koleksiyonunuza zahmetsizce ekleyin. Çok çerçeveli görüntü animasyonlarında çerçeve düzeni üzerinde hassas kontrol arayan geliştiriciler için idealdir. Yeni çerçeve, mevcut görüntünün boyutuna göre oluşturulacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | İndeks. |

**Returns:**
[ApngFrame](../../com.aspose.imaging.fileformats.apng/apngframe) - The newly created APNG frame.
### insertFrame(int index, RasterImage frameImage) {#insertFrame-int-com.aspose.imaging.RasterImage-}
```
public void insertFrame(int index, RasterImage frameImage)
```


Belirtilen indekste kendi çerçeve koleksiyonuna yeni bir çerçeve ekler. Yeni çerçevenin içeriği belirtilen görüntüden doldurulacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | İndeks. |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Çerçeve görüntüsü. |

### insertFrame(int index, RasterImage frameImage, long frameTime) {#insertFrame-int-com.aspose.imaging.RasterImage-long-}
```
public void insertFrame(int index, RasterImage frameImage, long frameTime)
```


Belirtilen indekste kendi çerçeve koleksiyonuna yeni bir çerçeve ekler. Yeni çerçevenin içeriği belirtilen görüntüden doldurulacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | İndeks. |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Çerçeve görüntüsü. |
| frameTime | long | Çerçeve süresi, milisaniye cinsinden. |

### popFrameAt(int index) {#popFrameAt-int-}
```
public ApngFrame popFrameAt(int index)
```


Bu sezgisel yöntemle çerçeve koleksiyonunuzdan belirtilen indeksteki çerçeveyi kaldırın ve alın. Animasyonlarındaki çerçeveleri verimli bir şekilde yönetmek isteyen geliştiriciler için mükemmeldir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | İndeks. |

**Returns:**
[ApngFrame](../../com.aspose.imaging.fileformats.apng/apngframe) - The removed APNG frame.
### removeFrameAt(int index) {#removeFrameAt-int-}
```
public void removeFrameAt(int index)
```


Bu yöntemle çerçeve koleksiyonunuzdan belirtilen indeksteki çerçeveyi sorunsuz bir şekilde kaldırın. Çok çerçeveli görüntülerindeki çerçevelerin düzenli yönetimini arayan geliştiriciler için mükemmeldir. Silinecek çerçeve imha edilecektir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | İndeks. |

### removeAllFrames() {#removeAllFrames--}
```
public void removeAllFrames()
```


Bu sezgisel yöntemle tüm kareleri kaldırarak çerçeve koleksiyonunuzu temizleyin. Animasyonlarını sıfırlamak veya yenilemek isteyen geliştiriciler için idealdir.

### setDefaultImage(RasterImage image) {#setDefaultImage-com.aspose.imaging.RasterImage-}
```
public void setDefaultImage(RasterImage image)
```


Bu yöntemle belirtilen raster görüntüyü mevcut animasyon için varsayılan görüntü olarak zahmetsizce ayarlayın. Animasyonlarındaki varsayılan görüntüyü özelleştirmek isteyen geliştiriciler için mükemmeldir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Görüntü. |

### resetDefaultImage() {#resetDefaultImage--}
```
public void resetDefaultImage()
```


Bu sezgisel yöntemle daha önce ayarlanmış varsayılan görüntüyü kaldırın. Animasyonundaki varsayılan görüntüyü sıfırlamak veya temizlemek isteyen geliştiriciler için idealdir. Bundan sonra, varsayılan görüntü kendi çerçeve koleksiyonundaki ilk kare olur (bu yöntemle silinemez).

