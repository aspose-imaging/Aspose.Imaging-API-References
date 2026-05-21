---
title: "OtgImage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "OpenDocument Şablonu OTG çizim görüntü dosyalarını, Grafik İçeriğiyle OpenDocument XML formatını kullanan API'mizle sorunsuz bir şekilde işleyin."
type: docs
weight: 13
url: /tr/java/com.aspose.imaging.fileformats.opendocument/otgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage), [com.aspose.imaging.fileformats.opendocument.OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage)
```
public class OtgImage extends OdImage
```

OpenDocument Şablonu (OTG) çizim görüntü dosyalarını API'mizle işleyin, Grafik İçeriğiyle OpenDocument XML formatını kullanarak sorunsuz bir şekilde manipüle edin. Belgeleri kolayca ayrıştırın, arka plan renklerini özelleştirin ve sayfa boyutlarını ayarlayın; böylece OTG vektör grafik projeleriniz için optimum kontrol ve esneklik sağlarsınız.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [OtgImage(StreamContainer streamContainer, LoadOptions loadOptions)](#OtgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Bir akış konteyneri ve yükleme seçenekleri sağlayarak yeni bir [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) nesnesi başlatın. |
| [OtgImage(StreamContainer streamContainer)](#OtgImage-com.aspose.imaging.StreamContainer-) | Bir akış konteyneri sağlayarak [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) sınıfının yeni bir nesnesini oluşturun. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Bu özellik, OTG dosya biçimine erişim sağlar ve görüntü dosyasında kapsüllenmiş veri türü hakkında önemli bilgiler sunar. |
| [getPages()](#getPages--) | Görüntüyle ilişkili sayfalar koleksiyonunu alır, böylece yazılım geliştiricileri her bir sayfaya verimli bir şekilde erişebilir ve bunları manipüle edebilir. |
### OtgImage(StreamContainer streamContainer, LoadOptions loadOptions) {#OtgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public OtgImage(StreamContainer streamContainer, LoadOptions loadOptions)
```


Bir akış konteyneri ve yükleme seçenekleri sağlayarak yeni bir [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) nesnesi başlatın. Bu yapıcı, geliştiricilerin akışlardan OTG görüntülerini verimli bir şekilde yüklemelerini ve özel yükleme yapılandırmalarını belirtmelerini sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Akış. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Yükleme seçenekleri. |

### OtgImage(StreamContainer streamContainer) {#OtgImage-com.aspose.imaging.StreamContainer-}
```
public OtgImage(StreamContainer streamContainer)
```


Bir akış konteyneri sağlayarak [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) sınıfının yeni bir nesnesini oluşturun. Bu yapıcı, geliştiricilerin OTG görüntülerini doğrudan akış konteynerlerinden oluşturmasını sağlayarak OTG görüntü verileriyle çalışmayı kolaylaştırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Akış konteyneri. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Bu özellik, OTG dosya biçimine erişim sağlar ve görüntü dosyasında kapsüllenmiş veri türü hakkında önemli bilgiler sunar. Yazılım geliştiricileri için kritik bir referans noktası olarak hizmet verir, böylece uygulamalarında OTG dosyalarını etkili bir şekilde yönetebilirler. Bu özelliği kullanarak, görüntü dosyasının belirli biçimini belirleyebilir, OTG dosyalarının yazılım sistemlerine sorunsuz entegrasyonunu ve manipülasyonunu kolaylaştırabilirsiniz.

**Returns:**
long
### getPages() {#getPages--}
```
public Image[] getPages()
```


Görüntüyle ilişkili sayfalar koleksiyonunu alır, böylece yazılım geliştiricileri her bir sayfaya verimli bir şekilde erişebilir ve bunları manipüle edebilir. Bu özellik, çeşitli işlemler için sayfalar arasında sorunsuz bir iterasyonu kolaylaştırarak görüntü işleme uygulamalarının işlevselliğini ve çok yönlülüğünü artırır.

**Returns:**
com.aspose.imaging.Image[] - sayfalar.
