---
title: "ImageOptionsBase Sınıfı"
type: docs
weight: 5760
url: /tr/python-net/aspose.imaging/imageoptionsbase/
---

**Summary:** The image base options.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageOptionsBase

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, DisposableObject

## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| [buffer_size_hint](#buffer_size_hint1) | int | r/w | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| dağıtıldı | bool | r | Bu örneğin dağıtılıp dağıtılmadığını gösteren bir değer alır. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Exif verilerini alır veya ayarlar. |
| full_frame | bool | r/w | Tam çerçeve [full frame] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| keep_metadata | bool | r/w | Dışa aktarırken orijinal görüntü meta verilerini tutup tutmayacağını gösteren bir değeri alır. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Çok sayfalı seçenekler |
| [palette](#palette2) | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Renk paletini alır veya ayarlar. |
| [resolution_settings](#resolution_settings3) | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Çözünürlük ayarlarını alır veya ayarlar. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Görüntünün oluşturulacağı kaynağı alır veya ayarlar. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | XMP meta veri kapsayıcısını alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [clone()](#clone__1) | Bu örneğin üye bazlı bir klonunu oluşturur. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Bu [Image](/imaging/python-net/aspose.imaging/image/) örneği destekliyor ve [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) örneğini uyguluyorsa, bir _metadata_ örneği ayarlamaya çalışır. |


### Property: buffer_size_hint {#buffer_size_hint1}

Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar.

**See also:**

**[Example # 1](#example_180)**: The following example shows how to set a memory limit when creating a new JPE...


### Property: palette {#palette2}

Renk paletini alır veya ayarlar.

**See also:**

**[Example # 1](#example_20)**: The following example shows how to set a palette to a BMP image to reduce its...

**[Example # 2](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...

**[Example # 3](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...


### Property: resolution_settings {#resolution_settings3}

Çözünürlük ayarlarını alır veya ayarlar.

**See also:**

**[Example # 1](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...

**[Example # 2](#example_92)**: The following example creates a palettized grayscale BMP image and then saves...


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

### The following example shows how to compress a PNG image, using indexed color with best fit palette {#example_21}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, ColorPaletteHelper, RasterImage, PaletteMiningMethod
from aspose.imaging.fileformats.png import PngColorType

# png görüntüsü yükler        
sourceFilePath = "OriginalRings.png"
outputFilePath = "OriginalRingsOutput.png"
with Image.load(sourceFilePath) as image:
	png_options = PngOptions()
	png_options.progressive = True
	# Dizine dayalı renk türünü kullan
	png_options.color_type = PngColorType.INDEXED_COLOR
	# Maksimum sıkıştırmayı kullan
	png_options.compression_level = 9
	# Mümkün olduğunca çok pikseli kapsayan en yakın 8-bit renk paletini al, böylece bir görüntü
	# paletli, paletsiz bir görüntüden neredeyse görsel olarak ayırt edilemez.
	png_options.palette = ColorPaletteHelper.get_close_image_palette(
						as_of(image, RasterImage), 256, 
						PaletteMiningMethod.HISTOGRAM)
		 
	image.save(outputFilePath, png_options);
}
# Çıktı dosya boyutu önemli ölçüde azaltılmalıdır.

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

### The following example shows how to set a memory limit when creating a new JPEG image. The memory limit is the maximum allowed size (in megabytes) for all internal buffers. {#example_180}
``` python
from os.path import join
from aspose.imaging import Image
from aspose.imaging.sources import FileCreateSource
from aspose.imaging.imageoptions import JpegOptions
from aspose.imaging.fileformats.jpeg import JpegCompressionMode

dir_: str = "c:\\aspose.imaging\\issues\\net\\3404\\"
# Hedef oluşturulan görüntü için 50 megabayt bellek sınırı ayarlanıyor
create_options = JpegOptions()
create_options.compression_type = JpegCompressionMode.PROGRESSIVE
create_options.buffer_size_hint = 50
create_options.source = FileCreateSource(join(dir_, "createdFile.jpg"), False)
with Aspose.Imaging.Image.create(create_options, 1000, 1000) as image:
	# aynı konuma kaydet
	image.save()


```

