---
title: "BigTiffImage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bu sınıf ile BigTiff görüntü formatı dosyalarını zahmetsizce manipüle edebilirsiniz."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.fileformats.bigtiff/bigtiffimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage), [com.aspose.imaging.fileformats.tiff.TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage)
```
public final class BigTiffImage extends TiffImage
```

Bu sınıfı kullanarak [BigTiffImage](../../com.aspose.imaging.fileformats.bigtiff/bigtiffimage) ile BigTiff görüntü formatı dosyalarını zahmetsizce manipüle edebilirsiniz. API'miz sorunsuz işleme ve özelleştirme seçenekleri sunar, büyük ölçekli görüntü verilerinin optimal işlenmesini, belirli gereksinimlerinize göre uyarlanmış çok yönlü özelliklerle sağlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BigTiffImage(TiffFrame frame)](#BigTiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Yeni bir [BigTiffImage](../../com.aspose.imaging.fileformats.bigtiff/bigtiffimage) sınıf örneği oluşturmak için bir TiffFrame parametresiyle başlatın. |
| [BigTiffImage(TiffFrame[] frames)](#BigTiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame---) | [BigTiffImage](../../com.aspose.imaging.fileformats.bigtiff/bigtiffimage) sınıfını sorunsuz bir şekilde kullanmaya başlamak için bir TiffFrames listesi parametresiyle yeni bir örnek başlatın. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Bu [Image](../../com.aspose.imaging/image) örneğinin dosya formatını alır. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Bu sezgisel yöntemle yeni bir sayfa ekleyerek BigTiff görüntünüzü zahmetsizce genişletin. |
### BigTiffImage(TiffFrame frame) {#BigTiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public BigTiffImage(TiffFrame frame)
```


Yeni bir [BigTiffImage](../../com.aspose.imaging.fileformats.bigtiff/bigtiffimage) sınıf örneği oluşturmak için bir TiffFrame parametresiyle başlatın. BigTiffImage nesneleriyle çalışmak için uygun bir yol arayan geliştiriciler için idealdir, esneklik ve projelerine entegrasyon kolaylığı sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Resmi başlatmak için kullanılacak tiff çerçevesi. |

### BigTiffImage(TiffFrame[] frames) {#BigTiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame---}
```
public BigTiffImage(TiffFrame[] frames)
```


[BigTiffImage](../../com.aspose.imaging.fileformats.bigtiff/bigtiffimage) sınıfını sorunsuz bir şekilde kullanmaya başlamak için bir TiffFrames listesi parametresiyle yeni bir örnek başlatın. Birden fazla çerçeve içeren BigTiffImage nesneleriyle çalışmak için basit bir yöntem arayan geliştiriciler için mükemmeldir, projelerinin verimliliğini sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| frames | [TiffFrame\[\]](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Çerçeveler. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Bu [Image](../../com.aspose.imaging/image) örneğinin dosya formatını alır.

**Returns:**
long - bu [Image](../../com.aspose.imaging/image) örneğinin dosya formatı.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Bu sezgisel yöntemle yeni bir sayfa ekleyerek BigTiff görüntünüzü zahmetsizce genişletin. Çok sayfalı görüntülerinin içeriğini dinamik olarak artırmak isteyen geliştiriciler için mükemmeldir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | Eklenecek sayfa. |

