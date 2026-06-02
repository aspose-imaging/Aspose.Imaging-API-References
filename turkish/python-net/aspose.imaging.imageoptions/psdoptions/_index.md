---
title: "PsdOptions Sınıfı"
type: docs
weight: 260
url: /tr/python-net/aspose.imaging.imageoptions/psdoptions/
---

**Summary:** Create Photoshop Document (PSD) images with our API, offering versatile options<br/>            with different format versions, compression methods, color modes, and<br/>            bits counts per color channel. Seamlessly handle XMP metadata containers,<br/>            ensuring comprehensive image processing with the power of PSD format features<br/>            like image layers, layer masks, and file information for customization<br/>            and creativity in your designs.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PsdOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [PsdOptions()](#PsdOptions__1) | Yeni bir [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) sınıfını başlatır. |
| [PsdOptions(options)](#PsdOptions_options_2) | Yeni bir [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) sınıfını başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| channel_bits_count | int | r/w | Renk kanalı başına bit sayısını alır veya ayarlar. |
| channels_count | int | r/w | Renk kanallarının sayısını alır veya ayarlar. |
| [color_mode](#color_mode1) | [ColorModes](/imaging/python-net/aspose.imaging.fileformats.psd/colormodes/) | r/w | psd renk modunu alır veya ayarlar. |
| [compression_method](#compression_method2) | [CompressionMethod](/imaging/python-net/aspose.imaging.fileformats.psd/compressionmethod/) | r/w | psd sıkıştırma yöntemini alır veya ayarlar. |
| dağıtıldı | bool | r | Bu örneğin dağıtılıp dağıtılmadığını gösteren bir değer alır. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Exif verilerini alır veya ayarlar. |
| full_frame | bool | r/w | Tam çerçeve [full frame] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| keep_metadata | bool | r/w | Dışa aktarırken orijinal görüntü meta verilerini tutup tutmayacağını gösteren bir değeri alır. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Çok sayfalı seçenekler |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Renk paletini alır veya ayarlar. |
| psd_version | [PsdVersion](/imaging/python-net/aspose.imaging.fileformats.psd/psdversion/) | r/w | Dosya formatı sürümünü alır veya ayarlar. PSD veya PSB olabilir. |
| refresh_image_preview_data | bool | r/w | Bir değeri alır veya ayarlar; [refresh image preview data] gösterilip gösterilmediğini belirtir - başka PSD görüntüleyicileriyle uyumluluğu en üst düzeye çıkarmak için kullanılan seçenek.<br/>            Lütfen not edin, metin katmanlarının son düzene çizilmesi Compact Framework platformunda desteklenmez. |
| remove_global_text_engine_resource | bool | r/w | Bir değeri alır veya ayarlar; - Global metin motoru kaynağını kaldır - İşlem sonrası Adobe Photoshop'ta açılamayan bazı metin katmanlı psd dosyaları için kullanılır (çoğunlukla eksik fontlarla ilgili metin katmanları).<br/>            Bu seçeneği kullandıktan sonra, kullanıcı Photoshop'ta açılan dosyada şu adımları yapmalıdır: Menü \"Text\" -&gt; \"Process absent fonts\". Bu işlemden sonra tüm metin tekrar görünecektir.<br/>            Lütfen not edin, bu işlem bazı son düzen değişikliklerine neden olabilir. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Çözünürlük ayarlarını alır veya ayarlar. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Görüntünün oluşturulacağı kaynağı alır veya ayarlar. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| vectorization_options | [PsdVectorizationOptions](/imaging/python-net/aspose.imaging.imageoptions/psdvectorizationoptions/) | r/w | PSD vektörleştirme seçeneklerini alır veya ayarlar. |
| version | int | r/w | psd dosya sürümünü alır veya ayarlar. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | XMP veri konteynerini al veya ayarla |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [clone()](#clone__1) | Bu örneğin üye bazlı bir klonunu oluşturur. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Bu [Image](/imaging/python-net/aspose.imaging/image/) örneği destekliyor ve [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) örneğini uyguluyorsa, bir _metadata_ örneği ayarlamaya çalışır. |


### Constructor: PsdOptions() {#PsdOptions__1}


```
 PsdOptions() 
```

Yeni bir [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) sınıfını başlatır.

### Constructor: PsdOptions(options) {#PsdOptions_options_2}


```
 PsdOptions(options) 
```

Yeni bir [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) sınıfını başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| options | [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) | Seçenekler. |

### Property: color_mode {#color_mode1}

psd renk modunu alır veya ayarlar.

**See also:**

**[Example # 1](#example_11)**: This example demonstrates the use of `aspose.imaging` API to convert Images t...


### Property: compression_method {#compression_method2}

psd sıkıştırma yöntemini alır veya ayarlar.

**See also:**

**[Example # 1](#example_11)**: This example demonstrates the use of `aspose.imaging` API to convert Images t...


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
### This example demonstrates the use of `aspose.imaging` API to convert Images to PSD format. To achieve this goal this example loads an existing image and then saves it back to PSD format. {#example_11}
``` python

from aspose.imaging import Image, RotateFlipType
from aspose.imaging.imageoptions import PsdOptions
from aspose.imaging.fileformats.psd import CompressionMethod, ColorModes
from os.path import join as path_join

directory = "c:\\temp\\"

#image sınıfının bir örneğini oluşturur ve dosya yolu aracılığıyla mevcut bir dosyayla başlatır.
with Image.load(path_join(directory, "sample.bmp")) as image:
	#PsdOptions sınıfının bir örneğini oluştur.
	psdOptions = PsdOptions()
	#CompressionMethod'ı RLE olarak ayarla
	#Not: Diğer desteklenen CompressionMethod, CompressionMethod.RAW [Sıkıştırma Yok]
	psdOptions.compression_method = CompressionMethod.RLE
	#ColorMode'u GRAYSCALE olarak ayarlayın
	#Not: Diğer desteklenen ColorMode'lar ColorModes.BITMAP ve ColorModes.RGB'dir
	psdOptions.color_mode = ColorModes.GRAYSCALE
	#Görüntüyü, sağlanan PsdOptions ayarlarıyla disk konumuna kaydedin
	image.save(path_join(directory, "output.psd"), psdOptions)
}

```

