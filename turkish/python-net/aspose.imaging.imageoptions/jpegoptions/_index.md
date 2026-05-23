---
title: "JpegOptions Sınıfı"
type: docs
weight: 160
url: /tr/python-net/aspose.imaging.imageoptions/jpegoptions/
---

**Summary:** Create high-quality JPEG images effortlessly with our API, offering adjustable<br/>            levels of compression to optimize storage size without compromising image quality.<br/>            Benefit from support for various compression types, near lossless coding,<br/>            RGB and CMYK color profiles, as well as EXIF, JFIF image data, and XMP<br/>            containers, ensuring versatile and customizable options for your image creation needs.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.JpegOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IHasJpegExifData, ImageOptionsBase

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [JpegOptions()](#JpegOptions__1) | Yeni bir [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/) sınıfı örneği başlatır. |
| [JpegOptions(jpeg_options)](#JpegOptions_jpeg_options_2) | Yeni bir [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bits_per_channel | System.Byte | r/w | Kayıpsız jpeg görüntüsü için bits per channel alır veya ayarlar. Şimdi 2 ile 8 bits per channel destekliyoruz. |
| buffer_size_hint | int | r/w | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| cmyk_color_profile | [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) | r/w | CMYK jpeg görüntüleri için hedef CMYK renk profili. Görüntüleri kaydederken kullanılır. Doğru renk dönüşümü için RGBColorProfile ile eşleşmelidir. |
| color_type | [JpegCompressionColorMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegcompressioncolormode/) | r/w | jpeg görüntüsü için renk tipini alır veya ayarlar. |
| yorum | string | r/w | jpeg dosya yorumunu alır veya ayarlar. |
| compression_type | [JpegCompressionMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegcompressionmode/) | r/w | Sıkıştırma tipini alır veya ayarlar. |
| default_memory_allocation_limit | int | r/w | Varsayılan bellek tahsis sınırını alır veya ayarlar. |
| dağıtıldı | bool | r | Bu örneğin dağıtılıp dağıtılmadığını gösteren bir değer alır. |
| exif_data | [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) | r/w | Exif veri kapsayıcısını al veya ayarla. |
| full_frame | bool | r/w | Tam çerçeve [full frame] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| horizontal_sampling | System.Byte | r/w | Her bileşen için yatay alt örneklemeleri alır veya ayarlar. |
| jfif | [JFIFData](/imaging/python-net/aspose.imaging.fileformats.jpeg/jfifdata/) | r/w | jfif'i alır veya ayarlar. |
| jpeg_ls_allowed_lossy_error | int | r/w | JPEG-LS fark sınırını, kayıpsız yakın kodlama için (JPEG-LS spesifikasyonundaki NEAR parametresi) alır veya ayarlar. |
| jpeg_ls_interleave_mode | [JpegLsInterleaveMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpeglsinterleavemode/) | r/w | JPEG-LS ara katman modunu alır veya ayarlar. |
| jpeg_ls_preset | [JpegLsPresetCodingParameters](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters/) | r/w | JPEG-LS ön ayar parametrelerini alır veya ayarlar. |
| keep_metadata | bool | r/w | Dışa aktarırken orijinal görüntü meta verilerini tutup tutmayacağını gösteren bir değeri alır. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Çok sayfalı seçenekler |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Renk paletini alır veya ayarlar. |
| preblend_alpha_if_present | bool | r/w | Alfa kanalı mevcut ise kırmızı, yeşil ve mavi bileşenlerin bir arka plan rengiyle karıştırılıp karıştırılmayacağını belirten bir değeri alır veya ayarlar. |
| quality | int | r/w | Görüntü kalitesini alır veya ayarlar. |
| rd_opt_settings | [RdOptimizerSettings](/imaging/python-net/aspose.imaging.imageoptions/rdoptimizersettings/) | r/w | RD optimizasyon ayarlarını alır veya ayarlar. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Çözünürlük ayarlarını alır veya ayarlar. |
| resolution_unit | [ResolutionUnit](/imaging/python-net/aspose.imaging/resolutionunit/) | r/w | Çözünürlük birimini alır veya ayarlar. |
| rgb_color_profile | [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) | r/w | CMYK jpeg görüntüleri için hedef RGB renk profili. Görüntüleri kaydederken kullanılır. Doğru renk dönüşümü için CMYKColorProfile ile eşleşmelidir. |
| sample_rounding_mode | [SampleRoundingMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/sampleroundingmode/) | r/w | 8-bit bir değeri n-bit bir değere sığdırmak için örnek yuvarlama modunu alır veya ayarlar. _JpegOptions.BitsPerChannel_ |
| scaled_quality | int | r | Ölçeklenmiş kalite. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Görüntünün oluşturulacağı kaynağı alır veya ayarlar. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| vertical_sampling | System.Byte | r/w | Her bileşen için dikey alt örneklemeleri alır veya ayarlar. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | XMP meta veri kapsayıcısını alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [clone()](#clone__1) | Bu örneğin üye bazlı bir klonunu oluşturur. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Bu [Image](/imaging/python-net/aspose.imaging/image/) örneği destekliyor ve [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) örneğini uyguluyorsa, bir _metadata_ örneği ayarlamaya çalışır. |


### Constructor: JpegOptions() {#JpegOptions__1}


```
 JpegOptions() 
```

Yeni bir [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/) sınıfı örneği başlatır.

### Constructor: JpegOptions(jpeg_options) {#JpegOptions_jpeg_options_2}


```
 JpegOptions(jpeg_options) 
```

Yeni bir [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| jpeg_options | [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/) | JPEG seçenekleri. |

### Method: clone() {#clone__1}


```
 clone() 
```

Bu örneğin üye bazlı bir klonunu oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Bu örneğin üye bazlı bir klonu. |


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_2}


```
 try_set_metadata(metadata) 
```

Bu [Image](/imaging/python-net/aspose.imaging/image/) örneği destekliyor ve [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) örneğini uyguluyorsa, bir _metadata_ örneği ayarlamaya çalışır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | Meta veriler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Doğru, eğer [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) örneği [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) örneğini destekliyor ve/veya uyguluyorsa; aksi takdirde, yanlış. |


## **Examples**
### This example demonstrates the use of different classes from `imageoptions` package for export purposes. A gif image is loaded as an instance of Image and then exported out to several formats. {#example_15}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions, JpegOptions, PngOptions, TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from os.path import join as path_join

directory = "c:\\temp\\"
#Mevcut bir gif görüntüsünü Image sınıfının bir örneği olarak yükle
with Image.load(path_join(directory, "sample.gif")) as image:
	# Varsayılan seçenekleri kullanarak BMP dosya formatına dışa aktar
	image.save(path_join(directory, "output.bmp"), BmpOptions())
	# Varsayılan seçenekleri kullanarak JPEG dosya formatına dışa aktar
	image.save(path_join(directory, "output.jpg"), JpegOptions())
	# Varsayılan seçenekleri kullanarak PNG dosya formatına dışa aktar
	image.save(path_join(directory, "output.png"), PngOptions())
	# Varsayılan seçenekleri kullanarak TIFF dosya formatına dışa aktar
	image.save(path_join(directory, "output.tif"), TiffOptions(TiffExpectedFormat.DEFAULT))


```

