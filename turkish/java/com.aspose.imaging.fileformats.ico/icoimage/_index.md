---
title: "IcoImage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "API'mizle çeşitli dosya formatlarını ve PNG ile BMP dahil çerçeve tiplerini destekleyerek ICO görüntü dosyalarını zahmetsizce manipüle edin."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.fileformats.ico/icoimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext)
```
public class IcoImage extends RasterCachedMultipageImage implements IMultipageImageExt
```

API'mizle çeşitli dosya formatlarını ve PNG ile BMP dahil çerçeve tiplerini destekleyerek ICO görüntü dosyalarını zahmetsizce manipüle edin. Piksel başına bit ayarlarını özelleştirin ve görüntü boyutlarını sorunsuz bir şekilde güncelleyin, böylece ikonlarınızın farklı platformlarda optimal temsili ve uyumluluğu sağlansın.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [IcoImage(int width, int height, IcoOptions options)](#IcoImage-int-int-com.aspose.imaging.imageoptions.IcoOptions-) | [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) sınıfını kullanarak ICO görüntüsü oluşturmayı zahmetsizce başlatın. |
| [IcoImage(Image image, IcoOptions icoOptions)](#IcoImage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-) | Basitlik ve verimlilik için tasarlanmış [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) sınıfı, ICO görüntülerini kolayca oluşturmanızı sağlar. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Bu özellik sayesinde dosya formatını zahmetsizce alın, iş akışınıza sorunsuz entegrasyon sağlar. |
| [getPageCount()](#getPageCount--) | Bu basit özellik sayesinde belge yapısı hakkında anında bilgi edinin. |
| [getPages()](#getPages--) | Bu özellik aracılığıyla belgenin sayfalarıyla ilgili kapsamlı bilgileri zahmetsizce alın. |
| [hasAlpha()](#hasAlpha--) | Bu özellik ile bu örnekte alfa kanalının bulunup bulunmadığını belirleyin. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) kullanarak bir görüntü sayfa girişi ekleyerek ICO görüntünüzü genişletin. |
| [addPage(Image page)](#addPage-com.aspose.imaging.Image-) | [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) varsayılan ayarlarını kullanarak bir görüntü sayfa girişi ekleyerek ICO görüntünüzü zahmetsizce zenginleştirin. |
| [addPage(Image page, IcoOptions icoOptions)](#addPage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-) | Belirtilen [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) ile ihtiyaçlarınıza göre özelleştirilmiş bir görüntü girişi ekleyerek ICO görüntünüzü zahmetsizce çeşitlendirin. |
| [removePage(int index)](#removePage-int-) | Dosya içinde belirtilen `` konumundaki belirli bir görüntü girişini kaldırarak ICO görüntünüzü ince ayar yapın. |
### IcoImage(int width, int height, IcoOptions options) {#IcoImage-int-int-com.aspose.imaging.imageoptions.IcoOptions-}
```
public IcoImage(int width, int height, IcoOptions options)
```


[IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) sınıfını kullanarak ICO görüntüsü oluşturmayı zahmetsizce başlatın. Bu yapıcı, genişlik, yükseklik ve oluşturma seçenekleri parametrelerini belirterek yeni ICO görüntüsü örnekleri başlatmanıza olanak tanır. Bu basit yapıcı sayesinde ICO görüntülerini tam olarak istediğiniz gibi özelleştirebilir, farklı platform ve cihazlarda sorunsuz uyumluluk ve görsel çekicilik sağlayabilirsiniz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int | Genişlik. |
| yükseklik | int | Yükseklik. |
| options | [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) | ICO oluşturma seçenekleri. |

### IcoImage(Image image, IcoOptions icoOptions) {#IcoImage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-}
```
public IcoImage(Image image, IcoOptions icoOptions)
```


[IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) sınıfı, basitlik ve verimlilik için tasarlanmıştır ve ICO görüntülerini kolayca oluşturmanızı sağlar. Bu yapıcı, sınıfın yeni bir örneğini başlatarak görüntü işleme ihtiyaçlarınız için sağlam bir temel sunar. İster uygulama geliştiriyor olun ister kullanıcı arayüzlerini iyileştiriyor olun, [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) sınıfı ICO görüntü yönetimini basitleştirir ve olağanüstü deneyimler sunmaya odaklanmanıza olanak tanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Görüntü. |
| icoOptions | [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) | ICO seçenekleri. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Bu özellik sayesinde dosya biçimini zahmetsizce alın, iş akışınıza sorunsuz entegrasyon sağlar. Bu özelliği kullanarak dosyanızın formatı hakkında kritik bilgilere erişir, uyumluluğu ve verimli işleme garantilersiniz.

**Returns:**
long
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Bu basit özellik ile belge yapısı hakkında anında bilgi edinin. Bu özelliği çağırarak dosyada bulunan toplam sayfa sayısını zahmetsizce elde edersiniz.

**Returns:**
int - sayfa sayısı.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Bu özellik aracılığıyla belgenin sayfalarıyla ilgili kapsamlı bilgileri zahmetsizce alın. Bu özelliğe erişerek belgede bulunan tüm sayfaları içeren bir koleksiyon veya diziye ulaşabilirsiniz.

**Returns:**
com.aspose.imaging.Image[] - sayfalar.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Bu özellik ile bu örnekte alfa kanalının bulunup bulunmadığını belirleyin. Görüntünün veya belgenin alfa kanalı içerip içermediğini hızlıca kontrol etmenizi sağlar; bu, çeşitli görüntü işleme ve renderleme görevleri için kritiktir. Görüntü ve belgelerde uyumluluğu sağlamak ve şeffaflık efektlerini yönetmek için idealdir.

**Returns:**
boolean - bu örneğin alfa içerip içermediğini gösteren bir değer.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public final void addPage(RasterImage page)
```


[IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) kullanarak bir görüntü sayfa girişi ekleyerek ICO görüntünüzü genişletin. Bu yöntem, raster görüntüleri ICO dosyanıza sorunsuz bir şekilde ekler ve yüksek kaliteli 32-bit PNG formatına dönüştürür. Raster görüntülerle ICO dosyalarınızı geliştirmek ve optimal uyumluluk ve render kalitesi sağlamak için mükemmeldir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | Görüntü. |

### addPage(Image page) {#addPage-com.aspose.imaging.Image-}
```
public final void addPage(Image page)
```


[IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) varsayılan ayarlarını kullanarak bir görüntü sayfa girişi ekleyerek ICO görüntünüzü zahmetsizce zenginleştirin. Bu yöntem, eklenen görüntüyü 32-bit PNG formatına kolayca dönüştürür, ICO görüntüsü içinde uyumluluk ve yüksek kaliteli render sağlar. PNG görüntüleri ICO dosyalarınıza sorunsuz ve verimli bir şekilde entegre etmek için mükemmeldir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page | [Image](../../com.aspose.imaging/image) | Görüntü. |

### addPage(Image page, IcoOptions icoOptions) {#addPage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-}
```
public final void addPage(Image page, IcoOptions icoOptions)
```


Belirtilen [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) ile ihtiyaçlarınıza göre özelleştirilmiş bir görüntü girişi ekleyerek ICO görüntünüzü zahmetsizce çeşitlendirin. Bu yöntem, görüntüyü özelleştirilmiş seçeneklerinize göre sorunsuz bir şekilde ekler, ICO dosyanızda esneklik ve hassasiyet sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page | [Image](../../com.aspose.imaging/image) | Görüntü. |
| icoOptions | [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) | ICO seçenekleri. |

### removePage(int index) {#removePage-int-}
```
public final void removePage(int index)
```


Dosya içinde belirtilen `` konumundaki belirli bir görüntü girişini kaldırarak ICO dosyanızı ince ayar yapın. Bu yöntem, görüntü kompozisyonunuz üzerinde hassas kontrol sağlar ve ICO dosyanızı zahmetsizce iyileştirmenize olanak tanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | İndeks. |

