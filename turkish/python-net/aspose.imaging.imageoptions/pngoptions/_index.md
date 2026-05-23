---
title: "PngOptions Sınıfı"
type: docs
weight: 250
url: /tr/python-net/aspose.imaging.imageoptions/pngoptions/
---

**Summary:** Create high-quality Portable Network Graphics (PNG) raster images effortlessly<br/>            with our API, offering customizable options for compression levels,<br/>            bits per pixel depths, and alpha bits. Seamlessly process XMP metadata containers,<br/>            ensuring comprehensive image metadata management, and empowering you to tailor<br/>            PNG images to your exact specifications with ease.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PngOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [PngOptions()](#PngOptions__1) | Yeni bir [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) sınıfı örneği başlatır. |
| [PngOptions(png_options)](#PngOptions_png_options_2) | Yeni bir [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| DEFAULT_COMPRESSION_LEVEL [static] | [PngCompressionLevel](/imaging/python-net/aspose.imaging.imageoptions/pngcompressionlevel/) | r | Varsayılan sıkıştırma seviyesi. |
| bit_depth | System.Byte | r/w | Bit derinliği değerlerini 1, 2, 4, 8, 16 aralığında alır veya ayarlar.<br/>            <br/><br/>            Aşağıdaki sınırlamalara dikkat edin:<br/>            <br/><br/>[PngColorType.INDEXED_COLOR](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) 1, 2, 4, 8 bit derinliğini destekler.<br/>            <br/><br/>[PngColorType.GRAYSCALE](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/), [PngColorType.GRAYSCALE_WITH_ALPHA](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) 8 bit derinliğini destekler.<br/>            <br/><br/>[PngColorType.TRUECOLOR](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/), [PngColorType.TRUECOLOR_WITH_ALPHA](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) 8, 16 bit derinliğini destekler.<br/>            <br/> |
| buffer_size_hint | int | r/w | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| [color_type](#color_type1) | [PngColorType](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) | r/w | Renk tipini alır veya ayarlar. |
| [compression_level](#compression_level2) | int | r/w | [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) sıkıştırma seviyesini alır veya ayarlar. |
| dağıtıldı | bool | r | Bu örneğin dağıtılıp dağıtılmadığını gösteren bir değer alır. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Exif verilerini alır veya ayarlar. |
| filter_type | [PngFilterType](/imaging/python-net/aspose.imaging.fileformats.png/pngfiltertype/) | r/w | png dosyası kaydetme sürecinde kullanılan filtre tipini alır veya ayarlar. |
| full_frame | bool | r/w | Tam çerçeve [full frame] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| keep_metadata | bool | r/w | Dışa aktarırken orijinal görüntü meta verilerini tutup tutmayacağını gösteren bir değeri alır. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | Çok sayfalı seçenekler |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Renk paletini alır veya ayarlar. |
| png_compression_level | [PngCompressionLevel](/imaging/python-net/aspose.imaging.imageoptions/pngcompressionlevel/) | r/w | [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) sıkıştırma seviyesini alır veya ayarlar. |
| [progressive](#progressive3) | bool | r/w | Bir [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) ilerleyici olup olmadığını gösteren bir değeri alır veya ayarlar. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Çözünürlük ayarlarını alır veya ayarlar. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Görüntünün oluşturulacağı kaynağı alır veya ayarlar. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | XMP meta veri kapsayıcısını alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [clone()](#clone__1) | Bu örneğin üye bazlı bir klonunu oluşturur. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Bu [Image](/imaging/python-net/aspose.imaging/image/) örneği destekliyor ve [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) örneğini uyguluyorsa, bir _metadata_ örneği ayarlamaya çalışır. |


### Constructor: PngOptions() {#PngOptions__1}


```
 PngOptions() 
```

Yeni bir [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) sınıfı örneği başlatır.

### Constructor: PngOptions(png_options) {#PngOptions_png_options_2}


```
 PngOptions(png_options) 
```

Yeni bir [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| png_options | [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) | PNG seçenekleri. |

### Property: color_type {#color_type1}

Renk tipini alır veya ayarlar.

**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


### Property: compression_level {#compression_level2}

[PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) sıkıştırma seviyesini alır veya ayarlar.

**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


### Property: progressive {#progressive3}

Bir [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) ilerleyici olup olmadığını gösteren bir değeri alır veya ayarlar.

**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


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
### This example uses Graphics class to create primitive shapes on the Image surface. To demonstrate the operation, the example creates a new Image in PNG format and draw primitive shapes on Image surface using Draw methods exposed by Graphics class {#example_12}
``` python

from aspose.imaging import Image, RotateFlipType, Graphics, Color, Pen, Rectangle, Point, Size,\
	Font, PointF
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.psd import CompressionMethod, ColorModes
from aspose.imaging.sources import StreamSource

from os.path import join as path_join

#Bir dosya akışı örneği oluşturur.
with open(r"C:\temp\output.png", "w+b") as stream:
	#PngOptions bir örnek oluştur ve çeşitli özelliklerini ayarla.
	pngOptions = PngOptions()
	#PngOptions için Kaynak ayarla.
	pngOptions.source = StreamSource(stream)
	#Image bir örnek oluştur.
	with Image.create(pngOptions, 500, 500) as image:
		#Graphics sınıfının bir örneğini oluştur ve başlat.
		graphics = Graphics(image)
		#Graphics yüzeyini temizle.
		graphics.clear(Color.wheat);
		#Siyah renkli Pen nesnesini belirterek bir Yay çizin, 
		#Yayı çevreleyen bir Rectangle, Başlangıç Açısı ve Tarama Açısı
		graphics.draw_arc(Pen(Color.black, 2.0), Rectangle(200, 200, 100, 200), 0, 300)
		#Mavi renkli Pen nesnesini ve koordinat noktalarını belirterek bir Bezier çizin.
		graphics.draw_bezier(Pen(Color.blue, 2.0), Point(250, 100), Point(300, 30), Point(450, 100), Point(235, 25))
		#Pen nesnesini Yeşil renkli olarak belirterek ve bir dizi Nokta ile bir Eğri çizin
		graphics.draw_curve(Pen(Color.green, 2.0), [Point(100, 200), Point(100, 350), Point(200, 450)])
		#Pen nesnesini ve çevresindeki Rectangle kullanarak bir Elips çizin
		graphics.draw_ellipse(Pen(Color.yellow, 2.0), Rectangle(300, 300, 100, 100))
		#Bir Çizgi çizin
		graphics.draw_line(Pen(Color.violet, 2.0), Point(100, 100), Point(200, 200))
		#Bir Pasta dilimi çizin
		graphics.draw_pie(Pen(Color.silver, 2.0), Rectangle(Point(200, 20), Size(200, 200)), 0, 45);
		#Pen nesnesini Kırmızı renkli olarak belirterek ve bir dizi Nokta ile bir Çokgen çizin
		graphics.draw_polygon(Pen(Color.red, 2.0), [Point(20, 100), Point(20, 200), Point(220, 20)])
		#Bir Dikdörtgen çizin
		graphics.draw_rectangle(Pen(Color.orange, 2.0), Rectangle(Point(250, 250), Size(100, 100)))
		#SolidBrush nesnesi oluşturun ve çeşitli özelliklerini ayarlayın
		brush = SolidBrush()
		brush.color = Color.purple
		#SolidBrush nesnesi ve Font kullanarak, belirli bir Point'ta bir Dize çizin
		graphics.draw_string("This image is created by Aspose.Imaging API", Font("Times New Roman", 16),
							 brush, PointF(50.0, 400.0))
		# Tüm değişiklikleri kaydedin.
		image.save();

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

