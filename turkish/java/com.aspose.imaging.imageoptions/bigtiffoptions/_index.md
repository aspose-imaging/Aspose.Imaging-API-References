---
title: "BigTiffOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "BigTIFF raster görüntü formatı oluşturma API'si, tarayıcılardan büyük ölçekli görüntü verileri kullanan uygulamaların benzersiz gereksinimlerini karşılamak üzere özel olarak tasarlanmıştır."
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.imageoptions/bigtiffoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase), [com.aspose.imaging.imageoptions.TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions)
```
public final class BigTiffOptions extends TiffOptions
```

BigTIFF raster görüntü formatı oluşturma API'si, tarayıcılardan büyük ölçekli görüntü verileri kullanan uygulamaların benzersiz gereksinimlerini karşılayacak şekilde özel olarak tasarlanmıştır. Bu API, birden çok TIFF görüntüsünü tek bir kapsamlı görüntüde birleştiren BigTIFF formatının sorunsuz oluşturulmasını sağlar. Geniş görüntü verilerinin verimli işlenmesini temin eder ve geliştiricilere yüksek çözünürlüklü, çoklu görüntü formatlarını oluşturma ve işleme konusunda güçlü bir araç sunar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BigTiffOptions(int expectedFormat)](#BigTiffOptions-int-) | Yeni bir [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions) sınıfı örneği başlatır. |
| [BigTiffOptions(TiffOptions options)](#BigTiffOptions-com.aspose.imaging.imageoptions.TiffOptions-) | Yeni bir [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions) sınıfı örneği başlatır. |
| [BigTiffOptions(TiffDataType[] tags)](#BigTiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Yeni bir [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions) sınıfı örneği başlatır. |
| [BigTiffOptions(int expectedFormat, int byteOrder)](#BigTiffOptions-int-int-) | Yeni bir [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [deepClone()](#deepClone--) | Bu örneği kopyalar. |
### BigTiffOptions(int expectedFormat) {#BigTiffOptions-int-}
```
public BigTiffOptions(int expectedFormat)
```


Yeni bir [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions) sınıfı örneği başlatır. Varsayılan olarak küçük endian kuralı kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| expectedFormat | int | Beklenen Tiff dosya formatı. |

### BigTiffOptions(TiffOptions options) {#BigTiffOptions-com.aspose.imaging.imageoptions.TiffOptions-}
```
public BigTiffOptions(TiffOptions options)
```


Yeni bir [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Seçenek kaynağı. |

### BigTiffOptions(TiffDataType[] tags) {#BigTiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public BigTiffOptions(TiffDataType[] tags)
```


Yeni bir [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Seçenek başlatma için etiketler. |

### BigTiffOptions(int expectedFormat, int byteOrder) {#BigTiffOptions-int-int-}
```
public BigTiffOptions(int expectedFormat, int byteOrder)
```


Yeni bir [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| expectedFormat | int | Beklenen Tiff dosya formatı. |
| byteOrder | int | Kullanılacak tiff dosya formatı bayt sırası. |

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Bu örneği kopyalar.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Returns a deep clone.
