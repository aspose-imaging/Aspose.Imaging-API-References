---
title: "OdImage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Açık belge"
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.fileformats.opendocument/odimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage)

**All Implemented Interfaces:**
com.aspose.internal.fileformats.opendocument.IOdImage
```
public abstract class OdImage extends VectorMultipageImage implements IOdImage
```

Açık belge
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDefaultPage()](#getDefaultPage--) | Görüntüyle ilişkili varsayılan sayfayı alır ve görüntü koleksiyonundaki birincil sayfaya temel erişim sağlar. |
| [isCached()](#isCached--) | Nesnenin verisinin şu anda önbelleğe alınıp alınmadığını gösteren bir boolean değer elde eder, böylece veri okuma ihtiyacını ortadan kaldırır. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Görüntü için piksel başına bit sayısını alır. |
| [getPageCount()](#getPageCount--) | Görüntü içindeki sayfaların toplam sayısını alır. |
| [getOdMetadata()](#getOdMetadata--) | OpenDocument dosyalarına özgü meta verileri alır. |
| [getRecords()](#getRecords--) | Görüntü içinde depolanan OpenDocument kayıtlarını alır. |
### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


Görüntüyle ilişkili varsayılan sayfayı alır ve görüntü koleksiyonundaki birincil sayfaya temel erişim sağlar. Bu özellik, görüntü verilerinin gezinmesini ve manipülasyonunu kolaylaştırarak yazılım geliştirme iş akışlarının verimliliğini artırır.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### isCached() {#isCached--}
```
public boolean isCached()
```


Nesnenin verisinin şu anda önbellekte olup olmadığını gösteren bir boolean değer elde eder, böylece veri okuma ihtiyacını ortadan kaldırır. Bu özellik, gereksiz veri erişim işlemlerini en aza indirerek performansı artıran bir optimizasyon göstergesi olarak hizmet eder.

**Returns:**
boolean - nesnenin verisinin şu anda önbelleğe alınıp alınmadığını ve veri okumanın gerekip gerekmediğini gösteren bir değer.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Görüntü için piksel başına bit sayısını alır. Bu özellik, görüntüde temsil edilen ayrıntı seviyesi ve renk derinliği hakkında bilgi sağlar, çeşitli görüntü işleme görevlerine ve optimizasyonlara yardımcı olur.

**Returns:**
int - görüntünün piksel başına bit sayısı.
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Görüntü içindeki sayfaların toplam sayısını alır. Bu özellik, çok sayfalı görüntüleri yöneten uygulamalar için gereklidir; işleme veya gösterime uygun sayfa sayısını doğru bir şekilde belirlemelerini sağlar.

**Returns:**
int - sayfa sayısı.
### getOdMetadata() {#getOdMetadata--}
```
public final OdMetadata getOdMetadata()
```


OpenDocument dosyalarına özgü meta verileri alır. Bu özellik, OD dosyalarına gömülü temel bilgilere erişim sağlar ve meta verilerin çıkarılması, değiştirilmesi veya analiz edilmesi gibi çeşitli işlemleri kolaylaştırır.

**Returns:**
[OdMetadata](../../com.aspose.imaging.fileformats.opendocument.objects/odmetadata) - the metadata.
### getRecords() {#getRecords--}
```
public final OdObject[] getRecords()
```


Görüntü içinde depolanan OpenDocument kayıtlarını alır. Bu özellik, OpenDocument dosyalarına gömülü belirli yapılandırılmış veri öğelerine erişim sağlar ve ilgili bilgilerin daha sonraki işleme veya analiz için alınmasını veya manipüle edilmesini kolaylaştırır.

**Returns:**
com.aspose.imaging.fileformats.opendocument.OdObject[] - kayıtlar.
