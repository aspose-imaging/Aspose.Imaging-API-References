---
title: "BmpOptions Sınıfı"
type: docs
weight: 30
url: /tr/python-net/aspose.imaging.imageoptions/bmpoptions/
---

**Summary:** The API for BMP and DIB raster image format creation options provides developers<br/>            with a versatile toolset for generating custom Bitmap (BMP) and Device<br/>            Independent Bitmap (DIB) images. With this API, you can precisely define<br/>            image characteristics such as bits per pixel, compression level and compression<br/>            type, tailoring the output to meet specific requirements. This feature-rich<br/>            API empowers developers to create high-quality, customized raster images<br/>            with ease and flexibility for diverse applications.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.BmpOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [BmpOptions()](#BmpOptions__1) | Yeni bir [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) sınıfı örneği başlatır. |
| [BmpOptions(bmp_options)](#BmpOptions_bmp_options_2) | Yeni bir [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| [bits_per_pixel](#bits_per_pixel1) | int | r/w | Görüntünün piksel başına bit sayısını alır veya ayarlar. |
| buffer_size_hint | int | r/w | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| [compression](#compression2) | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | r/w | Sıkıştırma türünü alır veya ayarlar. Varsayılan sıkıştırma türü [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) olup, bir [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) şeffaflıkla kaydetmeye izin verir. |
| dağıtıldı | bool | r | Bu örneğin dağıtılıp dağıtılmadığını gösteren bir değer alır. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Exif verilerini alır veya ayarlar. |
| full_frame | bool | r/w | Tam çerçeve [full frame] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| keep_metadata | bool | r/w | Dışa aktarırken orijinal görüntü meta verilerini tutup tutmayacağını gösteren bir değeri alır. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Çok sayfalı seçenekler |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Renk paletini alır veya ayarlar. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Çözünürlük ayarlarını alır veya ayarlar. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Görüntünün oluşturulacağı kaynağı alır veya ayarlar. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | XMP meta veri kapsayıcısını alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [clone()](#clone__1) | Bu örneğin üye bazlı bir klonunu oluşturur. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Bu [Image](/imaging/python-net/aspose.imaging/image/) örneği destekliyor ve [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) örneğini uyguluyorsa, bir _metadata_ örneği ayarlamaya çalışır. |


### Constructor: BmpOptions() {#BmpOptions__1}


```
 BmpOptions() 
```

Yeni bir [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) sınıfı örneği başlatır.


**See also:**

**[Example # 1](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...

**[Example # 2](#example_92)**: The following example creates a palettized grayscale BMP image and then saves...


### Constructor: BmpOptions(bmp_options) {#BmpOptions_bmp_options_2}


```
 BmpOptions(bmp_options) 
```

Yeni bir [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| bmp_options | [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) | BMP seçenekleri. |

### Property: bits_per_pixel {#bits_per_pixel1}

Görüntünün piksel başına bit sayısını alır veya ayarlar.

**See also:**

**[Example # 1](#example_20)**: The following example shows how to set a palette to a BMP image to reduce its...

**[Example # 2](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...

**[Example # 3](#example_92)**: The following example creates a palettized grayscale BMP image and then saves...


### Property: compression {#compression2}

Sıkıştırma türünü alır veya ayarlar. Varsayılan sıkıştırma türü [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) olup, bir [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) şeffaflıkla kaydetmeye izin verir.

**See also:**

**[Example # 1](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...

**[Example # 2](#example_92)**: The following example creates a palettized grayscale BMP image and then saves...

**[Example # 3](#example_208)**: Decompress BMP image which was previously compressed using DXT1 compression a...

**[Example # 4](#example_225)**: The example shows how to export a BMP from a PNG file while keeping the alpha...

**[Example # 5](#example_226)**: The example shows how to export a BMP with the RGB compression type.


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
### This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance. Several properties for BmpOptions instance are set before creating the actual image. Especially the Source property, that refers to the actual disk location in this case. {#example_4}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#`BmpOptions` bir örnek oluştur ve çeşitli özelliklerini ayarla
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24

	#`FileCreateSource` bir örnek oluştur ve `BmpOptions` örneği için `source` olarak ata
	#İkinci `Boolean` parametre, oluşturulacak dosyanın geçici olup olmadığını belirler
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp", False)

	#Image bir örnek oluştur ve Create metodunu çağırarak BmpOptions örneğiyle başlat
	with Image.create(bmp_options, 500, 500) as image:
		#bazı görüntü işleme yap
		# tüm değişiklikleri kaydet
		image.save()


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

### The following example shows how to set a palette to a BMP image to reduce its output size. {#example_20}
``` python

from aspose.pycore import as_of
from aspose.imaging import Point, Color, Graphics, ColorPaletteHelper
from aspose.imaging.brushes import LinearGradientBrush
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging.imageoptions import BmpOptions
from os.path import join as path_join

# 100 x 100 piksel boyutunda bir BMP görüntüsü oluştur.
with BmpImage(100, 100) as bmpImage:
	# Görüntünün sol üst köşesinden sağ alt köşesine uzanan lineer degrade.
	brush = LinearGradientBrush(Point(0, 0), Point(bmpImage.width, bmpImage.height),
								Color.red,
								Color.green)
	# Tüm görüntüyü lineer degrade fırçası ile doldur.
	gr = Graphics(bmpImage)
	gr.fill_rectangle(brush, bmpImage.bounds)
	# Mümkün olduğunca çok pikseli kapsayan en yakın 8-bit renk paletini al, böylece paletli bir görüntü
	# paletsiz bir bmp'den neredeyse görsel olarak ayırt edilemez olur
	palette = ColorPaletteHelper.get_close_image_palette(bmpImage, 256)
	# 8-bit palet en fazla 256 renk içerir.
	saveOptions = BmpOptions()
	saveOptions.palette = palette
	saveOptions.bits_per_pixel = 8
	
	with stream_ext.create_memory_stream() as stream:
		bmpImage.save(stream, saveOptions)
		print(f"The size of image with palette is {stream.tell()} bytes.")
		stream.seek(0)
		bmpImage.save(stream)
		print(f"The size of image without palette is {stream.tell()} bytes.")

# Çıktı şu şekilde görünür:
# Paletli görüntünün boyutu 11078 bayttır.
# Paletsiz görüntünün boyutu 40054 bayttır.

```

### The following example loads a BMP image and saves it back to BMP using various save options. {#example_91}
``` python
from aspose.imaging import Image, RasterImage, ColorPaletteHelper, ResolutionSetting
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.fileformats.bmp import BitmapCompression
import os
import aspose.pycore as aspycore

directory = "c:\\temp\\"

with Image.load(os.path.join(directory, "sample.bmp")) as image:
	
	rasterImage = aspycore.as_of(image, RasterImage)

	# BmpOptions oluştur
	saveOptions = BmpOptions()

	# Çıktı görüntüsünün boyutunu azaltmak için piksel başına 8 bit kullan.
	saveOptions.bits_per_pixel = 8

	# Görüntü piksellerinin en yüksek sayısını kapsayan en yakın 8-bit renk paletini ayarla, böylece paletli bir görüntü
	# neredeyse görsel olarak paletlenmemiş birine fark edilemez.
	saveOptions.palette = ColorPaletteHelper.get_close_image_palette(rasterImage, 256)

	# Sıkıştırma olmadan kaydet.
	# Çıktı görüntüsünün boyutunu azaltmak için RLE-8 sıkıştırmasını da kullanabilirsiniz.
	saveOptions.compression = BitmapCompression.RGB

	# Yatay ve dikey çözünürlüğü 96 dpi olarak ayarlayın.
	saveOptions.resolution_settings = ResolutionSetting(96.0, 96.0)

	image.save(os.path.join(directory, "sample.bmpoptions.bmp"), saveOptions)


```

### The following example creates a palettized grayscale BMP image and then saves it to a file. {#example_92}
``` python

from os.path import join as path_join
from aspose.imaging import Image, ColorPaletteHelper, ResolutionSetting, Graphics, Point, Color
from aspose.imaging.sources import FileCreateSource
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.fileformats.bmp import BitmapCompression
from aspose.imaging.brushes import LinearGradientBrush

directory = "c:\\temp\\"
createOptions = BmpOptions()

# Bir dosyaya kaydet
createOptions.source = FileCreateSource(path_join(directory, "output.palette8bit.bmp"), False)
	
# Çıktı görüntüsünün boyutunu azaltmak için piksel başına 8 bit kullan.
createOptions.bits_per_pixel = 8

# Tüm gri tonlamalı renkleri kapsayan standart 8-bit gri tonlama renk paletini ayarlayın.
# İşlenen görüntü yalnızca gri tonlamalı renkler içeriyorsa, onun paletli sürümü
# görsel olarak paletlenmemiş birine fark edilemez.
createOptions.palette = ColorPaletteHelper.create_8_bit_grayscale(False)

# Sıkıştırma olmadan kaydet.
# Çıktı görüntüsünün boyutunu azaltmak için RLE-8 sıkıştırmasını da kullanabilirsiniz.
createOptions.compression = BitmapCompression.RGB

# Yatay ve dikey çözünürlüğü 96 dpi olarak ayarlayın.
createOptions.resolution_settings = ResolutionSetting(96.0, 96.0)

# 100 x 100 piksel boyutunda bir BMP görüntüsü oluşturun ve bir dosyaya kaydedin.
with Image.create(createOptions, 100, 100) as image:
	graphics = Graphics(image)
	gradientBrush = LinearGradientBrush(Point(0, 0), Point(image.width, image.height), Color.black, Color.white)
	# Görüntüyü bir gri tonlamalı degrade ile doldurun
	graphics.fill_rectangle(gradientBrush, image.bounds)
	image.save()


```

### Decompress BMP image which was previously compressed using DXT1 compression algorithm. {#example_208}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions

with Image.load("CompressedTiger.bmp") as image:
	image.save("DecompressedTiger.bmp", BmpOptions())


```

### The example shows how to export a BMP from a PNG file while keeping the alpha channel, save a BMP file with transparency. {#example_225}
``` python
from aspose.imaging import Image
from aspose.imaging.fileformats.png import BmpOptions

source_path = "input.png"
output_path_def = "result_def.bmp"
output_path_def_2 = "result_def-2.bmp"
output_path_bitfields = "result_bitfields.bmp"
# Bir dosyadan PNG görüntüsü yükle.
with Image.load(source_path) as pngImage:
	# BMP görüntüsü varsayılan olarak şeffaflık desteğiyle kaydedilir.
	# Bu modu açıkça belirtmek istiyorsanız, BmpOptions'ın `compression` özelliği BitmapCompression.BITFIELDS olarak ayarlanmalıdır.
	# BitmapCompression.BITFIELDS sıkıştırma yöntemi, BmpOptions içinde varsayılan sıkıştırma yöntemidir.
	# Bu nedenle, şeffaflıkla bir Bmp görüntüsü dışa aktarmanın aynı sonucu aşağıdaki yöntemlerden biriyle elde edilebilir.
	# Örtük varsayılan seçeneklerle:
	pngImage.save(output_path_def)
	# Açık varsayılan seçeneklerle:
	pngImage.save(output_path_def_2, BmpOptions())
	# BitmapCompression.BITFIELDS sıkıştırma yöntemini belirterek:
	bmp_options = BmpOptions()
	bmp_options.compression = BitmapCompression.BITFIELDS
	pngImage.save(output_path_bitfields, bmp_options)


```

### The example shows how to export a BMP with the RGB compression type. {#example_226}
``` python

from aspose.imaging import Image
from aspose.imaging.fileformats.bmp import BitmapCompression
from aspose.imaging.imageoptions import BmpOptions

source_path = "input.png"
output_path = "output.png"
# Bir dosyadan PNG görüntüsü yükle.
with Image.load(source_path) as pngImage:
	# BMP görüntüsü varsayılan olarak şeffaflık desteğiyle kaydedilir, bu da BitmapCompression.BITFIELDS sıkıştırma yöntemi kullanılarak sağlanır.
	# RGB sıkıştırma yöntemiyle bir BMP görüntüsü kaydetmek için, `compression` özelliği BitmapCompression.RGB olarak ayarlanmış BmpOptions belirtilmelidir.
	bmp_options = BmpOptions()
	bmp_options.compression = BitmapCompression.RGB
	pngImage.save(output_path, bmp_options)


```

