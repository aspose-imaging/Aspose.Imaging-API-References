---
title: "GifOptions Sınıfı"
type: docs
weight: 120
url: /tr/python-net/aspose.imaging.imageoptions/gifoptions/
---

**Summary:** The API for Graphical Interchange Format (GIF) raster image file creation offers<br/>            developers comprehensive options for generating GIF images with precise<br/>            control. With features to set background color, color palette, resolution,<br/>            interlaced type, transparent color, XMP metadata container, and image<br/>            compression, this API ensures flexibility and efficiency in creating optimized<br/>            and visually appealing GIFs tailored to specific application requirements.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.GifOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [GifOptions()](#GifOptions__1) | Yeni bir [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/) sınıfı örneği başlatır. |
| [GifOptions(gif_options)](#GifOptions_gif_options_2) | Yeni bir [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Arka plan rengini alır veya ayarlar. |
| background_color_index | System.Byte | r/w | GIF arka plan renk indeksini alır veya ayarlar. |
| buffer_size_hint | int | r/w | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| color_resolution | System.Byte | r/w | GIF renk çözünürlüğünü alır veya ayarlar. |
| dağıtıldı | bool | r | Bu örneğin dağıtılıp dağıtılmadığını gösteren bir değer alır. |
| do_palette_correction | bool | r/w | Palet düzeltmesinin uygulanıp uygulanmadığını gösteren değeri alır veya ayarlar. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Exif verilerini alır veya ayarlar. |
| full_frame | bool | r/w | Tam çerçeve [full frame] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| has_trailer | bool | r/w | GIF'in trailer içerip içermediğini gösteren değeri alır veya ayarlar. |
| has_transparent_color | System.Nullable`1[[System.Boolean]] | r/w | Bir GIF görüntüsünün şeffaf renge sahip olup olmadığını gösteren değeri alır veya ayarlar. <br/>            Eğer dönüş değeri **None** ise, bu özellik kaynak görüntü bağlamı tarafından geçersiz kılınır. |
| interlaced | bool | r/w | Görüntünün taramalı olması gerekiyorsa True. |
| is_palette_sorted | bool | r/w | Palet girişlerinin sıralanıp sıralanmadığını gösteren değeri alır veya ayarlar. |
| keep_metadata | bool | r/w | Dışa aktarırken orijinal görüntü meta verilerini tutup tutmayacağını gösteren bir değeri alır. |
| loops_count | int | r/w | Döngü sayısını alır veya ayarlar (Varsayılan 1 döngü) |
| max_diff | int | r/w | İzin verilen maksimum piksel farkını alır veya ayarlar. Sıfırdan büyükse, kayıplı sıkıştırma kullanılacaktır.<br/>            Optimum kayıplı sıkıştırma için önerilen değer 80'dir. 30 çok hafif sıkıştırma, 200 ise ağırdır.<br/>            Sadece az miktarda kayıp getirildiğinde en iyi sonuç verir ve sıkıştırma algoritmasının sınırlamaları nedeniyle çok yüksek kayıp seviyeleri fazla kazanç sağlamaz.<br/>            İzin verilen değer aralığı [0, 1000]'dir. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Çok sayfalı seçenekler |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Renk paletini alır veya ayarlar. |
| pixel_aspect_ratio | System.Byte | r/w | GIF piksel en-boy oranını alır veya ayarlar. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Çözünürlük ayarlarını alır veya ayarlar. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Görüntünün oluşturulacağı kaynağı alır veya ayarlar. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | XMP meta veri kapsayıcısını alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [clone()](#clone__1) | Bu örneğin üye bazlı bir klonunu oluşturur. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Bu [Image](/imaging/python-net/aspose.imaging/image/) örneği destekliyor ve [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) örneğini uyguluyorsa, bir _metadata_ örneği ayarlamaya çalışır. |


### Constructor: GifOptions() {#GifOptions__1}


```
 GifOptions() 
```

Yeni bir [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/) sınıfı örneği başlatır.

### Constructor: GifOptions(gif_options) {#GifOptions_gif_options_2}


```
 GifOptions(gif_options) 
```

Yeni bir [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| gif_options | [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/) | GIF Seçenekleri. |

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
### This example shows how to load a pixels information in an array of Color, manipulates the array and set it back to the image. To perform these operations, this example creates a new Image file (in GIF format) using MemoryStream object. {#example_7}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Color
from aspose.imaging.externsions import StreamExtensions as strm_ext
from aspose.imaging.imageoptions import GifOptions
from aspose.imaging.sources import StreamSource

# MemoryStream'in bir örneğini oluşturun
with strm_ext.create_memory_stream() as stream:
	#GifOptions bir örneği oluşturun ve Source özelliği dahil çeşitli özelliklerini ayarlayın
	with GifOptions() as gifOptions:
		gifOptions.source = StreamSource(stream)

		# Image sınıfının bir örneğini oluşturun
		with as_of(Image.create(gifOptions, 500, 500), RasterImage) as image:
			# Görüntünün pikselini, alanı görüntü sınırı olarak belirterek alın
			pixels = image.load_pixels(image.bounds)

			yellow_color = Color.yellow
			blue_color = Color.blue
			#Diziyi döngüye al ve alternatif indeksli pikselin rengini ayarla
			for index in range(pixel.length):
				if index % 2 == 0:
					#İndeksli piksel rengini sarıya ayarla
					pixels[index] = yellow_color
				else:
					#İndeksli piksel rengini maviye ayarla
					pixels[index] = blue_color

			#Piksel değişikliklerini görüntüye uygula
			image.save_pixels(image.bounds, pixels)

			# Tüm değişiklikleri kaydedin.
			image.save()

	# MemoryStream'i dosyaya yaz
	stream.seek(0)
	with open(r"C:\temp\output.gif", "wb") as fileStream:
		fileStream.write(stream.read())
}

```

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

